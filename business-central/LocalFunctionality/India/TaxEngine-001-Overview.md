---
title: Tax Engine Overview
description: Tax Engine Overview
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 69ea2221f56b8eba96b1c720feaf81c6c62f5d29
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948601"
---
# <a name="tax-engine-overview"></a><span data-ttu-id="8121c-103">Tax Engine Overview</span><span class="sxs-lookup"><span data-stu-id="8121c-103">Tax Engine Overview</span></span>
[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="8121c-104">In a country, where tax reforms are happening at a fast pace, it is natural to expect frequent changes.</span><span class="sxs-lookup"><span data-stu-id="8121c-104">In a country, where tax reforms are happening at a fast pace, it is natural to expect frequent changes.</span></span> <span data-ttu-id="8121c-105">These changes may pertain to change in rate of tax, calculation method, tax     filing or reporting etc. To manage such changes with least effort, it is necessary to manage, as much as possible through configuration.</span><span class="sxs-lookup"><span data-stu-id="8121c-105">These changes may pertain to change in rate of tax, calculation method, tax     filing or reporting etc. To manage such changes with least effort, it is necessary to manage, as much as possible through configuration.</span></span> 

<span data-ttu-id="8121c-106">Tax Engine is a suite of extensions to enable configuration of tax rules and its computation.</span><span class="sxs-lookup"><span data-stu-id="8121c-106">Tax Engine is a suite of extensions to enable configuration of tax rules and its computation.</span></span> <span data-ttu-id="8121c-107">It consists of a use case designer, which allows modification of existing use cases or creation of new use cases.</span><span class="sxs-lookup"><span data-stu-id="8121c-107">It consists of a use case designer, which allows modification of existing use cases or creation of new use cases.</span></span> <span data-ttu-id="8121c-108">Use case contains the description of business scenario, conditions to be met and event that will trigger calculation of tax.</span><span class="sxs-lookup"><span data-stu-id="8121c-108">Use case contains the description of business scenario, conditions to be met and event that will trigger calculation of tax.</span></span> <span data-ttu-id="8121c-109">A use case can be enabled or disabled as per the business need.</span><span class="sxs-lookup"><span data-stu-id="8121c-109">A use case can be enabled or disabled as per the business need.</span></span>

<span data-ttu-id="8121c-110">Tax Engine extension is a combination of 6 smaller extensions or modules.</span><span class="sxs-lookup"><span data-stu-id="8121c-110">Tax Engine extension is a combination of 6 smaller extensions or modules.</span></span> <span data-ttu-id="8121c-111">Extensions are packaged to deliver functionality related to configuration of tax, tax calculation, import and export of configuration etc.</span><span class="sxs-lookup"><span data-stu-id="8121c-111">Extensions are packaged to deliver functionality related to configuration of tax, tax calculation, import and export of configuration etc.</span></span>



|<span data-ttu-id="8121c-112">Particulars</span><span class="sxs-lookup"><span data-stu-id="8121c-112">Particulars</span></span>|<span data-ttu-id="8121c-113">Description</span><span class="sxs-lookup"><span data-stu-id="8121c-113">Description</span></span>|
|---------|---------|
|<span data-ttu-id="8121c-114">**Tax Engine Core Extension**</span><span class="sxs-lookup"><span data-stu-id="8121c-114">**Tax Engine Core Extension**</span></span>| <span data-ttu-id="8121c-115">Core extension contains the UI elements and related tables which are commonly used throughout Tax Engine.</span><span class="sxs-lookup"><span data-stu-id="8121c-115">Core extension contains the UI elements and related tables which are commonly used throughout Tax Engine.</span></span> <span data-ttu-id="8121c-116">Also, it has library functions, which can be used by other extensions other than Tax Engine, to get any value.</span><span class="sxs-lookup"><span data-stu-id="8121c-116">Also, it has library functions, which can be used by other extensions other than Tax Engine, to get any value.</span></span>|
|<span data-ttu-id="8121c-117">**Tax Engine Tax Type Handler Extension**</span><span class="sxs-lookup"><span data-stu-id="8121c-117">**Tax Engine Tax Type Handler Extension**</span></span>|<span data-ttu-id="8121c-118">Tax Type Handler extension contains UI elements and related tables which enables definition of a new tax type, its attributes and map business entities involved with this tax type.</span><span class="sxs-lookup"><span data-stu-id="8121c-118">Tax Type Handler extension contains UI elements and related tables which enables definition of a new tax type, its attributes and map business entities involved with this tax type.</span></span>|
|<span data-ttu-id="8121c-119">**Tax Engine Tax Use Case Handler Extension**</span><span class="sxs-lookup"><span data-stu-id="8121c-119">**Tax Engine Tax Use Case Handler Extension**</span></span>|<span data-ttu-id="8121c-120">Tax Use Case Handler extension contains UI elements and related tables which are used for configuring a tax use case.</span><span class="sxs-lookup"><span data-stu-id="8121c-120">Tax Use Case Handler extension contains UI elements and related tables which are used for configuring a tax use case.</span></span> <span data-ttu-id="8121c-121">Use case definition includes primary business entity like Sales Order or Purchase Order line table, conditions for execution of use case, rules and formulae for calculation of tax and functionality to script business logic.</span><span class="sxs-lookup"><span data-stu-id="8121c-121">Use case definition includes primary business entity like Sales Order or Purchase Order line table, conditions for execution of use case, rules and formulae for calculation of tax and functionality to script business logic.</span></span>|
|<span data-ttu-id="8121c-122">**Tax Engine Scripting Extension**</span><span class="sxs-lookup"><span data-stu-id="8121c-122">**Tax Engine Scripting Extension**</span></span>|<span data-ttu-id="8121c-123">Script extension contains UI elements and related tables which are used in scripting of Business logic within a use case.</span><span class="sxs-lookup"><span data-stu-id="8121c-123">Script extension contains UI elements and related tables which are used in scripting of Business logic within a use case.</span></span>|
|<span data-ttu-id="8121c-124">**Tax Engine Tax Posting Handler Extension**</span><span class="sxs-lookup"><span data-stu-id="8121c-124">**Tax Engine Tax Posting Handler Extension**</span></span>|<span data-ttu-id="8121c-125">Posting Handler extension contains UI elements and related tables which are used to configure posting of tax components to G/L Accounts and related tax ledgers.</span><span class="sxs-lookup"><span data-stu-id="8121c-125">Posting Handler extension contains UI elements and related tables which are used to configure posting of tax components to G/L Accounts and related tax ledgers.</span></span>|
|<span data-ttu-id="8121c-126">**Tax Engine Json Exchange Extension**</span><span class="sxs-lookup"><span data-stu-id="8121c-126">**Tax Engine Json Exchange Extension**</span></span>|<span data-ttu-id="8121c-127">Json Exchange extension enables import or export of configuration data of tax engine in json format.</span><span class="sxs-lookup"><span data-stu-id="8121c-127">Json Exchange extension enables import or export of configuration data of tax engine in json format.</span></span>|


> [!NOTE]
> <span data-ttu-id="8121c-128">The Tax engine functionality is only available for legal entities with a primary address in India.</span><span class="sxs-lookup"><span data-stu-id="8121c-128">The Tax engine functionality is only available for legal entities with a primary address in India.</span></span>







































