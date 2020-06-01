---
title: Endereçamento de equipas de erro de inscrição AADSTS9000411
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9000744"
- "5689"
ms.openlocfilehash: b70f1320ea1dfa29e6fa489bd02acfcd1d92971b
ms.sourcegitcommit: 88d2918aa51f4ba10771527380c3e0db0f5a9147
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 05/20/2020
ms.locfileid: "44357873"
---
# <a name="addressing-teams-sign-in-error-aadsts9000411"></a><span data-ttu-id="f2788-102">Endereçamento de equipas de erro de inscrição AADSTS9000411</span><span class="sxs-lookup"><span data-stu-id="f2788-102">Addressing Teams sign-in error AADSTS9000411</span></span>

<span data-ttu-id="f2788-103">Ao iniciar sessão no Microsoft Teams, pode receber o erro: **Desculpe, mas estamos com dificuldades em contratá-lo em AADSTS900411: O pedido não está devidamente formatado. O parâmetro "login_hint" é duplicado.**</span><span class="sxs-lookup"><span data-stu-id="f2788-103">When signing in to Microsoft Teams, you may receive the error: **Sorry, but we're having trouble with signing you in AADSTS9000411: The request is not properly formatted. The parameter "login_hint" is duplicated.**</span></span>

<span data-ttu-id="f2788-104">Para resolver este problema, certifique-se de que os seus clientes da Microsoft Teams estão atualizados.</span><span class="sxs-lookup"><span data-stu-id="f2788-104">To address this issue, please ensure your Microsoft Teams clients are updated.</span></span> <span data-ttu-id="f2788-105">Para obter mais informações sobre a atualização do seu cliente, consulte [Atualizar as Equipas microsoft](https://support.office.com/article/Update-Microsoft-Teams-535a8e4b-45f0-4f6c-8b3d-91bca7a51db1).</span><span class="sxs-lookup"><span data-stu-id="f2788-105">For more information on updating your client, see [Update Microsoft Teams](https://support.office.com/article/Update-Microsoft-Teams-535a8e4b-45f0-4f6c-8b3d-91bca7a51db1).</span></span>

<span data-ttu-id="f2788-106">Se não conseguir atualizar o seu cliente por alguma razão, o registo do cliente irá limpar a maioria dos dados em cache.</span><span class="sxs-lookup"><span data-stu-id="f2788-106">If you cannot update your client for some reason, logging off the client will clear most cached data.</span></span> <span data-ttu-id="f2788-107">No entanto, se ainda tiver problemas após o logoff/logon, desista das Equipas e, por favor, limpe a cache do seu cliente fazendo o seguinte:</span><span class="sxs-lookup"><span data-stu-id="f2788-107">However, if you still have issues after logoff/logon, quit Teams and please clear your client cache by doing the following:</span></span>
1. <span data-ttu-id="f2788-108">Feche as equipas da Microsoft.</span><span class="sxs-lookup"><span data-stu-id="f2788-108">Close Microsoft Teams.</span></span>
2. <span data-ttu-id="f2788-109">Vá a: %appdata%\microsoft\teams e delete todos os ficheiros.</span><span class="sxs-lookup"><span data-stu-id="f2788-109">Go to: %appdata%\microsoft\teams and delete all the files.</span></span>
3. <span data-ttu-id="f2788-110">Reabra as Equipas microsoft.</span><span class="sxs-lookup"><span data-stu-id="f2788-110">Reopen Microsoft Teams.</span></span>