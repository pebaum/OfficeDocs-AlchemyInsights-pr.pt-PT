---
title: Mova mensagens de e-mail para a caixa de correio do Arquivo
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1083"
- "3100008"
ms.assetid: 59cd8630-6196-4680-ad92-1ce0e479f924
ms.openlocfilehash: 35c11f1bfb7c61b28a64f0128c29ddf7b4fce939
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 06/02/2020
ms.locfileid: "44511051"
---
# <a name="move-email-to-the-archive-mailbox"></a>Mova o e-mail para a caixa de correio do arquivo

1. Confirme se foi ativada uma **caixa de correio archive.** Caso contrário, utilize os passos [deste artigo](https://docs.microsoft.com/microsoft-365/compliance/enable-archive-mailboxes) para ativar a caixa de correio de arquivo.

2. Para arquivar automaticamente as mensagens na caixa de correio de arquivo, deve ser definida uma etiqueta de retenção com a ação **Move to archive** para ser aplicada automaticamente na **marcação completa da caixa de correio (predefinição).** Utilize os passos aqui para criar a etiqueta: [Etiqueta Padrão de Arquivo](https://docs.microsoft.com/microsoft-365/compliance/set-up-an-archive-and-deletion-policy-for-mailboxes#create-a-custom-archive-default-policy-tag).

3. Em seguida, adicione a etiqueta **Archive** à sua política de retenção. No centro de administração Exchange, escolha **Políticas de Retenção** > adicione a **etiqueta Move to Archive** à política > **Salvar**.

4. Agora [atribua a Política de Retenção](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/apply-retention-policy) à caixa de correio específica do utilizador. A mesma política será aplicada tanto à **caixa de** correio Primária como ao **Arquivo.**

Pode ser necessário forçar o Assistente de Pasta Gerida (MFA) a executar e aplicar as novas definições na caixa de correio do utilizador. Executar o seguinte comando enquanto [está ligado ao EXO PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps) para iniciar o Assistente de Pasta Gerida para uma caixa de correio específica:
  
Start-ManagedFolderAssistant -Identidade<name of the mailbox>

Para obter mais informações sobre a criação de uma política de arquivo, consulte [configurar uma política de arquivo e eliminação para caixas de correio](https://docs.microsoft.com/microsoft-365/compliance/set-up-an-archive-and-deletion-policy-for-mailboxes#step-1-enable-archive-mailboxes-for-users).
  