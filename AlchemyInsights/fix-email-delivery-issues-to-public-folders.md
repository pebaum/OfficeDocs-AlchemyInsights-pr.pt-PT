---
title: Corrigir problemas de entrega de correio electrónico correio nas pastas públicas
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1956
ms.assetid: ''
ms.openlocfilehash: 45665f900014c52e6a920325b0a3b0f6f79fb72d
ms.sourcegitcommit: d1c1d5bcb52ba9083e8dd7603feb72436c5154c8
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 04/17/2019
ms.locfileid: "31910619"
---
# <a name="fix-email-delivery-issues-to-mail-enabled-public-folders"></a>Corrigir problemas de entrega de correio electrónico correio nas pastas públicas

Se remetentes externos não é possível enviar mensagens para as pastas públicas com correio electrónico e os remetentes recebem o erro: **não foi possível localizar (550 5.4.1)**, verifique o domínio de correio electrónico para a pasta pública está configurada como um domínio de retransmissão interno, em vez de um domínio autoritário:

1. Abra o [Centro de administração do Exchange (EAC)](https://docs.microsoft.com/Exchange/exchange-admin-center).

2. Vá para **o fluxo de correio** \> **aceites domínios**, seleccione o domínio aceite e, em seguida, clique em **Editar**.

3. Nas propriedades da página que abre, se o tipo de domínio estiver definido como **autoritários**, altere o valor para **reencaminhamento interno** e, em seguida, clique em **Guardar**.

Se os remetentes externos recebem o erro **que não tem permissão (550 5.7.13)**, execute o seguinte comando no [PowerShell Online do Exchange](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell) para ver as permissões para utilizadores anónimos na pasta pública:

`Get-PublicFolderClientPermission -Identity "<PublicFolderIdentity>" -User Anonymous`Por exemplo, `Get-PublicFolderClientPermission -Identity "\Customer Discussion" -User Anonymous`.

Para permitir que os utilizadores externos enviar correio electrónico para esta pasta pública, adicione o acesso de CreateItems para a direita para o utilizador anónimo. Por exemplo, `Add-PublicFolderClientPermission -Identity "\Customer Discussion" -User Anonymous -AccessRights CreateItems`.