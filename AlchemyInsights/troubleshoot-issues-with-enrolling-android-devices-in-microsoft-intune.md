---
title: Problemas de resolução de problemas com a inscrição de dispositivos Android no Microsoft Intune
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d0269461-20a8-4c9e-83b2-8fcf608dc0a5
ms.custom:
- "787"
- "6200002"
ms.openlocfilehash: bd6d278ebf6cca7fb6e4ac1049deae600b516707
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 04/22/2020
ms.locfileid: "43759631"
---
# <a name="troubleshoot-issues-with-enrolling-android-devices-in-microsoft-intune"></a>Problemas de resolução de problemas com a inscrição de dispositivos Android no Microsoft Intune

Reveja os recursos listados abaixo para resolver o seu problema agora.
  
Algumas questões comuns e passos de resolução:
  
 **Dispositivo não erro encriptado no Portal da Empresa:** As versões mais recentes do Android, particularmente a começar pelo v7.0, requerem uma senha de arranque para garantir que o seu dispositivo está totalmente encriptado. As soluções comuns são para ativar um pin o arranque ou encriptar totalmente o dispositivo. Reveja [este documento](https://docs.microsoft.com/intune-user-help/your-device-appears-encrypted-but-cp-says-otherwise-android) para mais informações.
  
 **Os dispositivos não conseguem fazer o check-in com o serviço Intune ou o display como "Insalubre" na consola de administração Intune:** Alguns dispositivos Samsung 4.4 e 5.5 podem não fazer o check-in no serviço. Existem 3 soluções possíveis para esta questão:
  
1. Abra manualmente a aplicação Intune Company Portal, que iniciará automaticamente uma sincronização do dispositivo.

2. Atualize o dispositivo para Android 6.0 ou superior.

3. Desative o Smart Manager da Samsung na gestão do Portal da Empresa Intune. Reveja [este documento](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune#devices-fail-to-check-in-with-the-intune-service-and-display-as-unhealthy-in-the-intune-admin-console) para mais pormenores sobre estas questões e resoluções.

 **Tipo de licença** de utilizador Inválido ou **Nome de Utilizador Não Reconhecido erro:** O utilizador precisa de ser atribuído a uma licença Intune ou EMS. Reveja estes documentos para atribuir uma licença através de: Office Admin Center ou portal Azure.
  
Recursos adicionais para ajudar a resolver o seu problema:
  
1. Utilize o Portal de Resolução de [Problemas Intune](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) para diagnosticar e resolver falhas comuns de matrícula. Reveja [este documento](https://docs.microsoft.com/intune/help-desk-operators) para mais detalhes.

2. Reveja [este documento](https://docs.microsoft.com/intune-classic/Troubleshoot/troubleshoot-device-enrollment-in-intune) para obter uma lista de erros comuns que impeçam a inscrição e as resoluções de cada um.

3. [Saiba como inscrever dispositivos Android no Microsoft Intune](https://docs.microsoft.com/intune/android-enroll).
