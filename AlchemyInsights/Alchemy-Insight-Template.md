---
title: igual ao nome de ficheiro é melhor
ms.author: pebaum
author: pebaum
manager: jackiesm
ms.date: 4/27/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: 5555
ms.assetid: (guid of old soc version if any)
ms.openlocfilehash: 68f743ee9c448565470815f8410cc6ce4b384bed
ms.sourcegitcommit: 0b6e9470c6b73616ba8bacef7010f739b7fac332
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 03/21/2019
ms.locfileid: "30742442"
---
# <a name="required-alchemy-header-h1-h2s-dont-work"></a><span data-ttu-id="97a28-102">Necessário Alquimia cabeçalho H1, H2 não funcionam.</span><span class="sxs-lookup"><span data-stu-id="97a28-102">Required Alchemy Header H1, H2's dont work.</span></span>
<span data-ttu-id="97a28-103">Procedimentos recomendados e orientações para a criação de Alquimia:</span><span class="sxs-lookup"><span data-stu-id="97a28-103">Best Practices and guidelines for Alchemy authoring:</span></span>

1. <span data-ttu-id="97a28-104">**Não se aninham conhecimentos aprofundados de Alquimia em pastas**- Isto irá interromper a estrutura de URLs.</span><span class="sxs-lookup"><span data-stu-id="97a28-104">**Do not nest Alchemy Insights in folders**- this will break the url structure.</span></span> <span data-ttu-id="97a28-105">Procuramos, para corrigir isto.</span><span class="sxs-lookup"><span data-stu-id="97a28-105">We're looking into fixing this.</span></span>
1. <span data-ttu-id="97a28-106">Ficheiros na pasta **AlchemyInsights** devem ter nomes de ficheiros em minúsculas com hífenes para espaços ex.</span><span class="sxs-lookup"><span data-stu-id="97a28-106">Files in the **AlchemyInsights** folder should have lowercase filenames with hyphens for spaces ex.</span></span> <span data-ttu-id="97a28-107">***how-para-activar-litígio-aguardar***.</span><span class="sxs-lookup"><span data-stu-id="97a28-107">***how-to-enable-litigation-hold***.</span></span>
    1. <span data-ttu-id="97a28-108">Inclua o ID de ID da regra ou balde a partir do [portal para parceiros de Alquimia](https://alchemyportal.azurewebsites.net) no campo ms.custom.</span><span class="sxs-lookup"><span data-stu-id="97a28-108">Include the Rule ID or bucket ID from the [Alchemy Partner portal](https://alchemyportal.azurewebsites.net) in the ms.custom field.</span></span> <span data-ttu-id="97a28-109">ex.</span><span class="sxs-lookup"><span data-stu-id="97a28-109">ex.</span></span> <span data-ttu-id="97a28-110">***MS.Custom: 100021***</span><span class="sxs-lookup"><span data-stu-id="97a28-110">***ms.custom: 100021***</span></span>
1. <span data-ttu-id="97a28-111">Utilize o resto dos metadados na parte superior deste ficheiro como modelo.</span><span class="sxs-lookup"><span data-stu-id="97a28-111">Use the rest of the metadata at the top of this file as your template.</span></span>
1. <span data-ttu-id="97a28-112">No [portal para parceiros de Alquimia](https://alchemyportal.azurewebsites.net), navegue para a secção **cliente Insight título:** e a utilização que, como um iniciar, aponte para o título H1 para a visão.</span><span class="sxs-lookup"><span data-stu-id="97a28-112">In the [Alchemy Partner portal](https://alchemyportal.azurewebsites.net), navigate down to the section **Customer Insight Title:** and use that as a starting point for your H1 title for the insight.</span></span> 
    > [!NOTE]
    > <span data-ttu-id="97a28-113">Alquimia informações privilegiadas deve ter apenas um único H1 na parte superior ou vão quebrar na produção.</span><span class="sxs-lookup"><span data-stu-id="97a28-113">Alchemy Insights MUST have only a single H1 at the top or they will break in production.</span></span> <span data-ttu-id="97a28-114">H2s não compor assim utilização **negrito** ou outras convenções para significar secções separadas.</span><span class="sxs-lookup"><span data-stu-id="97a28-114">H2s dont render either so use **bold** or other conventions to signify separate sections.</span></span>
1. <span data-ttu-id="97a28-115">Em seguida, preencha o corpo de texto utilizando o material de projecto na secção informações de cliente da página regra de Alquimia</span><span class="sxs-lookup"><span data-stu-id="97a28-115">Next, fill in the body text using the draft material in the Customer Insights section of the Alchemy Rule page</span></span>
    1. <span data-ttu-id="97a28-116">Listas com marcas estão correctos</span><span class="sxs-lookup"><span data-stu-id="97a28-116">Bulleted lists are fine</span></span>
    1. <span data-ttu-id="97a28-117">Listas numeradas demasiado</span><span class="sxs-lookup"><span data-stu-id="97a28-117">Numbered lists too</span></span>
    1. <span data-ttu-id="97a28-118">**Negrito** e *itálico* são a-ok</span><span class="sxs-lookup"><span data-stu-id="97a28-118">**Bold** and *italic* are a-ok</span></span>
    1. <span data-ttu-id="97a28-119">Hiperligações devem ser sempre quer **"ligações Web" / externo** ou **deep-hiperligações para elementos da IU**, as hiperligações não internas.</span><span class="sxs-lookup"><span data-stu-id="97a28-119">Links should always be either **"links to web"/external** OR **deep-links to UI elements**, not internal links.</span></span>
    1. <span data-ttu-id="97a28-120">Imagens não são suportadas oficialmente neste momento, mas é o plano.</span><span class="sxs-lookup"><span data-stu-id="97a28-120">Pictures are not officially supported at this time, but it's on the roadmap.</span></span>

<span data-ttu-id="97a28-121">E realmente já é um pouco demasiado longo.</span><span class="sxs-lookup"><span data-stu-id="97a28-121">And this is really already a bit too long.</span></span> <span data-ttu-id="97a28-122">Recomenda-se cerca de 400 caracteres--</span><span class="sxs-lookup"><span data-stu-id="97a28-122">Best practice is about 400 characters ---------------------------------</span></span>

<span data-ttu-id="97a28-123">Depois do conteúdo estiver pronto, puxe-lo para o ramo vivo.</span><span class="sxs-lookup"><span data-stu-id="97a28-123">Once your content is ready, pull it to the live branch.</span></span> <span data-ttu-id="97a28-124">Em seguida, vá para o [portal de parceiro de Alquimia](https://alchemyportal.azurewebsites.net) e introduza o nome de ficheiro para o campo de url.</span><span class="sxs-lookup"><span data-stu-id="97a28-124">Then, go to the [Alchemy Partner portal](https://alchemyportal.azurewebsites.net) and enter the filename into the url field.</span></span> <span data-ttu-id="97a28-125">M</span><span class="sxs-lookup"><span data-stu-id="97a28-125">M</span></span>