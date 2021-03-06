---
title: Limite diário de e-mail ultrapassado. O fluxo de trabalho está suspenso.
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "5200020"
- "1227"
ms.openlocfilehash: 5a510f1137c7c49cd1de3d3fd2a470759e37ba1e
ms.sourcegitcommit: 286000b588adef1bbbb28337a9d9e087ec783fa2
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 04/27/2020
ms.locfileid: "43908715"
---
# <a name="daily-email-limit-exceeded-workflow-is-suspended"></a>Limite de e-mail diário ultrapassado. O fluxo de trabalho está suspenso.

Este erro pode ser recebido nos seguintes cenários:

- Tem um fluxo de trabalho no SharePoint Online que está a usar o tipo de plataforma de fluxo de trabalho SharePoint 2010 ou SharePoint 2013.
- O fluxo de trabalho está configurado para enviar uma mensagem de correio eletrónico personalizada a mais de 200 utilizadores de cada vez, mais de 10.000 destinatários por dia, ou mais de 30 mensagens por minuto.
- Quando executa o fluxo de trabalho, a mensagem de e-mail não é enviada, e você nota o seguinte comportamento:
    - Para um fluxo de trabalho utilizando o tipo de plataforma SharePoint 2013, você navega para a página **Workflow Status.** Na página do Estado do Fluxo de Trabalho, o **Estado Interno** está definido para **Iniciar**, e o balão de informação mostra Incapaz de enviar a **um destinatário**.

Para resolver este problema, configure o seu fluxo de trabalho para enviar mensagens de correio eletrónico sem exceder os limites de [remetente exchange Online](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits#recipientlimits). Por exemplo, utilize uma pausa no fluxo de trabalho, envie o e-mail para um grupo Microsoft 365, um grupo de distribuição ou grupo de segurança ativado por correio, ou envie a mensagem para menos de 200 destinatários de cada vez.


Para mais informações, consulte o [seguinte artigo](https://support.microsoft.com/help/3150442/daily-email-limit-has-exceeded-and-your-workflow-has-been-suspended-or).

## <a name="related-topics"></a>Tópicos relacionados
- [Criar fluxo](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [SharePoint e Flow](https://flow.microsoft.com/blog/sharepoint-and-flow/) 