---
title: Purchase of Services for Overseas Place of Supply from Registered Vendor
description: Purchase of Services for Overseas Place of Supply from Registered Vendor
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 815ac18d60488a082b0abcacd52ba249bb779358
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948629"
---
# <a name="purchase-of-services-for-overseas-place-of-supply-from-registered-vendor"></a><span data-ttu-id="cd209-103">Purchase of Services for Overseas Place of Supply from Registered Vendor</span><span class="sxs-lookup"><span data-stu-id="cd209-103">Purchase of Services for Overseas Place of Supply from Registered Vendor</span></span>

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="cd209-104">The supply of goods or services or both when the supplier is located in India and the place of supply is outside India shall be treated to be a supply of goods or services or both in the course of inter-state trade or commerce.</span><span class="sxs-lookup"><span data-stu-id="cd209-104">The supply of goods or services or both when the supplier is located in India and the place of supply is outside India shall be treated to be a supply of goods or services or both in the course of inter-state trade or commerce.</span></span>

<span data-ttu-id="cd209-105">The process of computing tax on purchase from vendor with overseas place of supply has been explained in this document.</span><span class="sxs-lookup"><span data-stu-id="cd209-105">The process of computing tax on purchase from vendor with overseas place of supply has been explained in this document.</span></span>

## <a name="create-a-purchase-invoice"></a><span data-ttu-id="cd209-106">Create a purchase invoice</span><span class="sxs-lookup"><span data-stu-id="cd209-106">Create a purchase invoice</span></span>

1. <span data-ttu-id="cd209-107">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Purchase Invoice** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="cd209-107">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Purchase Invoice** , and then choose the related link.</span></span>
2. <span data-ttu-id="cd209-108">Select **Vendor** on **Purchase Invoice** header, GST vendor type should be **Registered** .</span><span class="sxs-lookup"><span data-stu-id="cd209-108">Select **Vendor** on **Purchase Invoice** header, GST vendor type should be **Registered** .</span></span>
3. <span data-ttu-id="cd209-109">Select **G/L Account** on **Purchase Invoice** line.</span><span class="sxs-lookup"><span data-stu-id="cd209-109">Select **G/L Account** on **Purchase Invoice** line.</span></span> <span data-ttu-id="cd209-110">GST Group Code, HSN/SAC Code and GST Credit value should be selected as **Availment** if the tax input credit is available or else **Non-Availment** on the G/L Account.</span><span class="sxs-lookup"><span data-stu-id="cd209-110">GST Group Code, HSN/SAC Code and GST Credit value should be selected as **Availment** if the tax input credit is available or else **Non-Availment** on the G/L Account.</span></span> 
4. <span data-ttu-id="cd209-111">GST Credit option can be changed on **Purchase Invoice** line.</span><span class="sxs-lookup"><span data-stu-id="cd209-111">GST Credit option can be changed on **Purchase Invoice** line.</span></span>

<span data-ttu-id="cd209-112">For example, the service recipient has a GSTIN in West Bengal and the Vendor also has a GSTIN for West Bengal, but service provider and place of supply is outside India.</span><span class="sxs-lookup"><span data-stu-id="cd209-112">For example, the service recipient has a GSTIN in West Bengal and the Vendor also has a GSTIN for West Bengal, but service provider and place of supply is outside India.</span></span> <span data-ttu-id="cd209-113">In this case, IGST will be charged as place of supply is outside India.</span><span class="sxs-lookup"><span data-stu-id="cd209-113">In this case, IGST will be charged as place of supply is outside India.</span></span> <span data-ttu-id="cd209-114">So, invoice will be issued for INR 10,000 on which 18% IGST, has to be charged.</span><span class="sxs-lookup"><span data-stu-id="cd209-114">So, invoice will be issued for INR 10,000 on which 18% IGST, has to be charged.</span></span>

- <span data-ttu-id="cd209-115">GST calculation will appear in the Fact Box, as following:</span><span class="sxs-lookup"><span data-stu-id="cd209-115">GST calculation will appear in the Fact Box, as following:</span></span>
    
    |<span data-ttu-id="cd209-116">Component</span><span class="sxs-lookup"><span data-stu-id="cd209-116">Component</span></span>|<span data-ttu-id="cd209-117">Amount</span><span class="sxs-lookup"><span data-stu-id="cd209-117">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="cd209-118">**GST Base Amount**</span><span class="sxs-lookup"><span data-stu-id="cd209-118">**GST Base Amount**</span></span>|<span data-ttu-id="cd209-119">10,000</span><span class="sxs-lookup"><span data-stu-id="cd209-119">10,000</span></span>|  
    |<span data-ttu-id="cd209-120">**IGST**</span><span class="sxs-lookup"><span data-stu-id="cd209-120">**IGST**</span></span>|<span data-ttu-id="cd209-121">1800</span><span class="sxs-lookup"><span data-stu-id="cd209-121">1800</span></span>|

- <span data-ttu-id="cd209-122">GL Entries for purchase of services for overseas place of supply from registered vendor where input tax credit is available, will be as following:</span><span class="sxs-lookup"><span data-stu-id="cd209-122">GL Entries for purchase of services for overseas place of supply from registered vendor where input tax credit is available, will be as following:</span></span>
    
    |<span data-ttu-id="cd209-123">Particulars</span><span class="sxs-lookup"><span data-stu-id="cd209-123">Particulars</span></span>|<span data-ttu-id="cd209-124">Amount</span><span class="sxs-lookup"><span data-stu-id="cd209-124">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="cd209-125">**Services Account**</span><span class="sxs-lookup"><span data-stu-id="cd209-125">**Services Account**</span></span>|<span data-ttu-id="cd209-126">10000</span><span class="sxs-lookup"><span data-stu-id="cd209-126">10000</span></span>|
    |<span data-ttu-id="cd209-127">**IGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="cd209-127">**IGST Receivable Account**</span></span>|<span data-ttu-id="cd209-128">1800</span><span class="sxs-lookup"><span data-stu-id="cd209-128">1800</span></span>|  
    |<span data-ttu-id="cd209-129">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="cd209-129">**Vendor Account**</span></span>|<span data-ttu-id="cd209-130">-11800</span><span class="sxs-lookup"><span data-stu-id="cd209-130">-11800</span></span>|

- <span data-ttu-id="cd209-131">GL Entries for purchase of services for overseas place of supply from registered vendor where input tax credit is not available, will be as following:</span><span class="sxs-lookup"><span data-stu-id="cd209-131">GL Entries for purchase of services for overseas place of supply from registered vendor where input tax credit is not available, will be as following:</span></span>
    
    |<span data-ttu-id="cd209-132">Particulars</span><span class="sxs-lookup"><span data-stu-id="cd209-132">Particulars</span></span>|<span data-ttu-id="cd209-133">Amount</span><span class="sxs-lookup"><span data-stu-id="cd209-133">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="cd209-134">**Services Account**</span><span class="sxs-lookup"><span data-stu-id="cd209-134">**Services Account**</span></span>|<span data-ttu-id="cd209-135">11800</span><span class="sxs-lookup"><span data-stu-id="cd209-135">11800</span></span>|
    |<span data-ttu-id="cd209-136">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="cd209-136">**Vendor Account**</span></span>|<span data-ttu-id="cd209-137">-11800</span><span class="sxs-lookup"><span data-stu-id="cd209-137">-11800</span></span>|






































