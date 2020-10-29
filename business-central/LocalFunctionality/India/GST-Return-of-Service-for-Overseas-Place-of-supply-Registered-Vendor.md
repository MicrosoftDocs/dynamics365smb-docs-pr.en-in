---
title: Purchase Return of Services for Overseas Place of Supply to Registered Vendor
description: Purchase Return of Services for Overseas Place of Supply to Registered Vendor
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: fe77a2b71b8d31b38d53218a5059917d92b112fc
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948634"
---
# <a name="purchase-return-of-services-for-overseas-place-of-supply-to-registered-vendor"></a><span data-ttu-id="14028-103">Purchase Return of Services for Overseas Place of Supply to Registered Vendor</span><span class="sxs-lookup"><span data-stu-id="14028-103">Purchase Return of Services for Overseas Place of Supply to Registered Vendor</span></span>

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="14028-104">The supply of goods or services or both when the supplier is located in India and the place of supply is outside India shall be treated to be a supply of goods or services or both in the course of inter-state trade or commerce.</span><span class="sxs-lookup"><span data-stu-id="14028-104">The supply of goods or services or both when the supplier is located in India and the place of supply is outside India shall be treated to be a supply of goods or services or both in the course of inter-state trade or commerce.</span></span>

<span data-ttu-id="14028-105">The process of computing tax on purchase return to a vendor with overseas place of supply has been explained in this document.</span><span class="sxs-lookup"><span data-stu-id="14028-105">The process of computing tax on purchase return to a vendor with overseas place of supply has been explained in this document.</span></span>

## <a name="create-a-purchase-return-order-or-purchase-credit-memo"></a><span data-ttu-id="14028-106">Create a purchase return order or purchase credit memo</span><span class="sxs-lookup"><span data-stu-id="14028-106">Create a purchase return order or purchase credit memo</span></span>

1. <span data-ttu-id="14028-107">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Purchase Return Order** or **Purchase Credit Memo** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="14028-107">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Purchase Return Order** or **Purchase Credit Memo** , and then choose the related link.</span></span>
2. <span data-ttu-id="14028-108">Select **Vendor** on **Purchase Credit Memo** header, GST vendor type should be **Registered** .</span><span class="sxs-lookup"><span data-stu-id="14028-108">Select **Vendor** on **Purchase Credit Memo** header, GST vendor type should be **Registered** .</span></span>
3. <span data-ttu-id="14028-109">Select **G/L Account** on **Purchase Credit Memo** line.</span><span class="sxs-lookup"><span data-stu-id="14028-109">Select **G/L Account** on **Purchase Credit Memo** line.</span></span> <span data-ttu-id="14028-110">GST Group Code, HSN/SAC Code and GST Credit value should be selected as **Availment** if the tax input credit is available or else **Non-Availment** in the G/L Account.</span><span class="sxs-lookup"><span data-stu-id="14028-110">GST Group Code, HSN/SAC Code and GST Credit value should be selected as **Availment** if the tax input credit is available or else **Non-Availment** in the G/L Account.</span></span> 
4. <span data-ttu-id="14028-111">GST Credit option can be changed on **Purchase Credit Memo** line.</span><span class="sxs-lookup"><span data-stu-id="14028-111">GST Credit option can be changed on **Purchase Credit Memo** line.</span></span>

<span data-ttu-id="14028-112">For example, if a service recipient has a GSTIN for West Bengal and the Vendor has a GSTIN in West Bengal, but the place of supply is outside India.</span><span class="sxs-lookup"><span data-stu-id="14028-112">For example, if a service recipient has a GSTIN for West Bengal and the Vendor has a GSTIN in West Bengal, but the place of supply is outside India.</span></span> <span data-ttu-id="14028-113">In this case, IGST will be charged as place of supply is outside India.</span><span class="sxs-lookup"><span data-stu-id="14028-113">In this case, IGST will be charged as place of supply is outside India.</span></span> <span data-ttu-id="14028-114">So, return order or credit memo will be issued for INR 10,000 on which 18% IGST, has to be charged.</span><span class="sxs-lookup"><span data-stu-id="14028-114">So, return order or credit memo will be issued for INR 10,000 on which 18% IGST, has to be charged.</span></span>

- <span data-ttu-id="14028-115">GST calculation will appear in the Fact Box, as following:</span><span class="sxs-lookup"><span data-stu-id="14028-115">GST calculation will appear in the Fact Box, as following:</span></span>
    
    |<span data-ttu-id="14028-116">Component</span><span class="sxs-lookup"><span data-stu-id="14028-116">Component</span></span>|<span data-ttu-id="14028-117">Amount</span><span class="sxs-lookup"><span data-stu-id="14028-117">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="14028-118">**GST Base Amount**</span><span class="sxs-lookup"><span data-stu-id="14028-118">**GST Base Amount**</span></span>|<span data-ttu-id="14028-119">10,000</span><span class="sxs-lookup"><span data-stu-id="14028-119">10,000</span></span>|  
    |<span data-ttu-id="14028-120">**IGST**</span><span class="sxs-lookup"><span data-stu-id="14028-120">**IGST**</span></span>|<span data-ttu-id="14028-121">1800</span><span class="sxs-lookup"><span data-stu-id="14028-121">1800</span></span>|  

- <span data-ttu-id="14028-122">GL Entries for Return or Credit Note of services for overseas place of supply from registered vendor where input tax credit is available, will be as following:</span><span class="sxs-lookup"><span data-stu-id="14028-122">GL Entries for Return or Credit Note of services for overseas place of supply from registered vendor where input tax credit is available, will be as following:</span></span>

    |<span data-ttu-id="14028-123">Particulars</span><span class="sxs-lookup"><span data-stu-id="14028-123">Particulars</span></span>|<span data-ttu-id="14028-124">Amount</span><span class="sxs-lookup"><span data-stu-id="14028-124">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="14028-125">**Services Account**</span><span class="sxs-lookup"><span data-stu-id="14028-125">**Services Account**</span></span>|<span data-ttu-id="14028-126">11800</span><span class="sxs-lookup"><span data-stu-id="14028-126">11800</span></span>|  
    |<span data-ttu-id="14028-127">**IGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="14028-127">**IGST Receivable Account**</span></span>|<span data-ttu-id="14028-128">-1800</span><span class="sxs-lookup"><span data-stu-id="14028-128">-1800</span></span>|  
    |<span data-ttu-id="14028-129">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="14028-129">**Vendor Account**</span></span>|<span data-ttu-id="14028-130">-10000</span><span class="sxs-lookup"><span data-stu-id="14028-130">-10000</span></span>|

- <span data-ttu-id="14028-131">GL Entries for Return or Credit Note of services for overseas place of supply from registered vendor where input tax credit is not available, will be as following:</span><span class="sxs-lookup"><span data-stu-id="14028-131">GL Entries for Return or Credit Note of services for overseas place of supply from registered vendor where input tax credit is not available, will be as following:</span></span>

    |<span data-ttu-id="14028-132">Particulars</span><span class="sxs-lookup"><span data-stu-id="14028-132">Particulars</span></span>|<span data-ttu-id="14028-133">Amount</span><span class="sxs-lookup"><span data-stu-id="14028-133">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="14028-134">**Services Account**</span><span class="sxs-lookup"><span data-stu-id="14028-134">**Services Account**</span></span>|<span data-ttu-id="14028-135">-11800</span><span class="sxs-lookup"><span data-stu-id="14028-135">-11800</span></span>|  
    |<span data-ttu-id="14028-136">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="14028-136">**Vendor Account**</span></span>|<span data-ttu-id="14028-137">11800</span><span class="sxs-lookup"><span data-stu-id="14028-137">11800</span></span>|






































