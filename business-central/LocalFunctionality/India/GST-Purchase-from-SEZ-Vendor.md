---
title: Purchase of Goods from SEZ Vendor
description: Purchase of Goods from SEZ Vendor
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: a98da449146a994ef99b2ed3c196079234a88700
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948638"
---
# <a name="purchase-of-goods-from-sez-vendor"></a><span data-ttu-id="69203-103">Purchase of Goods from SEZ Vendor</span><span class="sxs-lookup"><span data-stu-id="69203-103">Purchase of Goods from SEZ Vendor</span></span>

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="69203-104">A special economic zone (SEZ) is a dedicated zone wherein businesses enjoy simpler tax and easier legal compliances.</span><span class="sxs-lookup"><span data-stu-id="69203-104">A special economic zone (SEZ) is a dedicated zone wherein businesses enjoy simpler tax and easier legal compliances.</span></span> <span data-ttu-id="69203-105">The transactions with SEZ’s are deemed  exports and imports.</span><span class="sxs-lookup"><span data-stu-id="69203-105">The transactions with SEZ’s are deemed  exports and imports.</span></span> <span data-ttu-id="69203-106">The SEZ supply of goods can be made with cover of bill of entry or without cover of bill of entry.</span><span class="sxs-lookup"><span data-stu-id="69203-106">The SEZ supply of goods can be made with cover of bill of entry or without cover of bill of entry.</span></span>
 
<span data-ttu-id="69203-107">Process for purchase from SEZ vendor has been explained in this document.</span><span class="sxs-lookup"><span data-stu-id="69203-107">Process for purchase from SEZ vendor has been explained in this document.</span></span>

## <a name="create-a-purchase-invoice"></a><span data-ttu-id="69203-108">Create a purchase invoice</span><span class="sxs-lookup"><span data-stu-id="69203-108">Create a purchase invoice</span></span>

1. <span data-ttu-id="69203-109">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Purchase Invoice** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="69203-109">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Purchase Invoice** , and then choose the related link.</span></span>
2. <span data-ttu-id="69203-110">Select **Vendor** on **Purchase Invoice** header, GST vendor type should be **SEZ** .</span><span class="sxs-lookup"><span data-stu-id="69203-110">Select **Vendor** on **Purchase Invoice** header, GST vendor type should be **SEZ** .</span></span>
3. <span data-ttu-id="69203-111">Select **Item Code** for goods , **Fixed Asset** for Fixed Asset purchase on **Purchase Invoice** line.</span><span class="sxs-lookup"><span data-stu-id="69203-111">Select **Item Code** for goods , **Fixed Asset** for Fixed Asset purchase on **Purchase Invoice** line.</span></span> <span data-ttu-id="69203-112">GST Group Code, HSN/SAC Code should be filled up on Item.</span><span class="sxs-lookup"><span data-stu-id="69203-112">GST Group Code, HSN/SAC Code should be filled up on Item.</span></span>
4. <span data-ttu-id="69203-113">IGST is to be calculated on GST Assessable Value + Basic Custom Duty.</span><span class="sxs-lookup"><span data-stu-id="69203-113">IGST is to be calculated on GST Assessable Value + Basic Custom Duty.</span></span> 

<span data-ttu-id="69203-114">For example, purchase invoice will be issued for INR 10000, Custom Duty INR 1000, GST Assessable Value INR 11000 (IGST @18%), has to be charged.</span><span class="sxs-lookup"><span data-stu-id="69203-114">For example, purchase invoice will be issued for INR 10000, Custom Duty INR 1000, GST Assessable Value INR 11000 (IGST @18%), has to be charged.</span></span> <span data-ttu-id="69203-115">Calculation base: (18% on 11,000 GST Assessable Value + 1,000 BCD) (12,000\*18%)</span><span class="sxs-lookup"><span data-stu-id="69203-115">Calculation base: (18% on 11,000 GST Assessable Value + 1,000 BCD) (12,000\*18%)</span></span>

- <span data-ttu-id="69203-116">GST calculation will appear in the Fact Box, as following:</span><span class="sxs-lookup"><span data-stu-id="69203-116">GST calculation will appear in the Fact Box, as following:</span></span>
    
    |<span data-ttu-id="69203-117">Component</span><span class="sxs-lookup"><span data-stu-id="69203-117">Component</span></span>|<span data-ttu-id="69203-118">Amount</span><span class="sxs-lookup"><span data-stu-id="69203-118">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="69203-119">**GST Base Amount**</span><span class="sxs-lookup"><span data-stu-id="69203-119">**GST Base Amount**</span></span>|<span data-ttu-id="69203-120">11,000</span><span class="sxs-lookup"><span data-stu-id="69203-120">11,000</span></span>|
    |<span data-ttu-id="69203-121">**Custom Duty (BCD)**</span><span class="sxs-lookup"><span data-stu-id="69203-121">**Custom Duty (BCD)**</span></span>|<span data-ttu-id="69203-122">1000</span><span class="sxs-lookup"><span data-stu-id="69203-122">1000</span></span>|  
    |<span data-ttu-id="69203-123">**IGST**</span><span class="sxs-lookup"><span data-stu-id="69203-123">**IGST**</span></span>|<span data-ttu-id="69203-124">2160</span><span class="sxs-lookup"><span data-stu-id="69203-124">2160</span></span>|  


- <span data-ttu-id="69203-125">GL Entries for import of goods with input tax credit available from SEZ vendor with cover of Bill of Entry, will be as following:</span><span class="sxs-lookup"><span data-stu-id="69203-125">GL Entries for import of goods with input tax credit available from SEZ vendor with cover of Bill of Entry, will be as following:</span></span>

    |<span data-ttu-id="69203-126">Particulars</span><span class="sxs-lookup"><span data-stu-id="69203-126">Particulars</span></span>|<span data-ttu-id="69203-127">Amount</span><span class="sxs-lookup"><span data-stu-id="69203-127">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="69203-128">**Purchase Account (Transactional Value+ BCD)**</span><span class="sxs-lookup"><span data-stu-id="69203-128">**Purchase Account (Transactional Value+ BCD)**</span></span>|<span data-ttu-id="69203-129">11000</span><span class="sxs-lookup"><span data-stu-id="69203-129">11000</span></span>|  
    |<span data-ttu-id="69203-130">**IGST Receivable Account (on GST Assessable Value + BCD)**</span><span class="sxs-lookup"><span data-stu-id="69203-130">**IGST Receivable Account (on GST Assessable Value + BCD)**</span></span>|<span data-ttu-id="69203-131">2160</span><span class="sxs-lookup"><span data-stu-id="69203-131">2160</span></span>| 
    |<span data-ttu-id="69203-132">**Customs House Account (GST Amount + BCD)**</span><span class="sxs-lookup"><span data-stu-id="69203-132">**Customs House Account (GST Amount + BCD)**</span></span>|<span data-ttu-id="69203-133">-3160</span><span class="sxs-lookup"><span data-stu-id="69203-133">-3160</span></span>|
    |<span data-ttu-id="69203-134">**Vendor Account (Transaction Value)**</span><span class="sxs-lookup"><span data-stu-id="69203-134">**Vendor Account (Transaction Value)**</span></span>|<span data-ttu-id="69203-135">-10000</span><span class="sxs-lookup"><span data-stu-id="69203-135">-10000</span></span>|

- <span data-ttu-id="69203-136">GL Entries for import of goods with input tax credit available from SEZ vendor without cover of Bill of Entry, will be as following:</span><span class="sxs-lookup"><span data-stu-id="69203-136">GL Entries for import of goods with input tax credit available from SEZ vendor without cover of Bill of Entry, will be as following:</span></span>

    |<span data-ttu-id="69203-137">Particulars</span><span class="sxs-lookup"><span data-stu-id="69203-137">Particulars</span></span>|<span data-ttu-id="69203-138">Amount</span><span class="sxs-lookup"><span data-stu-id="69203-138">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="69203-139">**Purchase Account (Transactional Value+ BCD)**</span><span class="sxs-lookup"><span data-stu-id="69203-139">**Purchase Account (Transactional Value+ BCD)**</span></span>|<span data-ttu-id="69203-140">11000</span><span class="sxs-lookup"><span data-stu-id="69203-140">11000</span></span>|  
    |<span data-ttu-id="69203-141">**IGST Receivable Account (on GST Assessable Value + BCD)**</span><span class="sxs-lookup"><span data-stu-id="69203-141">**IGST Receivable Account (on GST Assessable Value + BCD)**</span></span>|<span data-ttu-id="69203-142">2160</span><span class="sxs-lookup"><span data-stu-id="69203-142">2160</span></span>| 
    |<span data-ttu-id="69203-143">**Vendor Account (Transaction Value)**</span><span class="sxs-lookup"><span data-stu-id="69203-143">**Vendor Account (Transaction Value)**</span></span>|<span data-ttu-id="69203-144">-13160</span><span class="sxs-lookup"><span data-stu-id="69203-144">-13160</span></span>|

- <span data-ttu-id="69203-145">GL Entries for import of goods without input tax credit available from SEZ vendor with cover of Bill of Entry, will be as following:</span><span class="sxs-lookup"><span data-stu-id="69203-145">GL Entries for import of goods without input tax credit available from SEZ vendor with cover of Bill of Entry, will be as following:</span></span>

    |<span data-ttu-id="69203-146">Particular</span><span class="sxs-lookup"><span data-stu-id="69203-146">Particular</span></span>|<span data-ttu-id="69203-147">Amount</span><span class="sxs-lookup"><span data-stu-id="69203-147">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="69203-148">**Purchase Account**</span><span class="sxs-lookup"><span data-stu-id="69203-148">**Purchase Account**</span></span>|<span data-ttu-id="69203-149">13160</span><span class="sxs-lookup"><span data-stu-id="69203-149">13160</span></span>|  
    |<span data-ttu-id="69203-150">**Custom House Account**</span><span class="sxs-lookup"><span data-stu-id="69203-150">**Custom House Account**</span></span>|<span data-ttu-id="69203-151">3160</span><span class="sxs-lookup"><span data-stu-id="69203-151">3160</span></span>| 
    |<span data-ttu-id="69203-152">**Vendor Account (Transaction Value)**</span><span class="sxs-lookup"><span data-stu-id="69203-152">**Vendor Account (Transaction Value)**</span></span>|<span data-ttu-id="69203-153">-10000</span><span class="sxs-lookup"><span data-stu-id="69203-153">-10000</span></span>|

- <span data-ttu-id="69203-154">GL Entries for import of goods without input tax credit available from SEZ vendor without cover of Bill of Entry, will be as following:</span><span class="sxs-lookup"><span data-stu-id="69203-154">GL Entries for import of goods without input tax credit available from SEZ vendor without cover of Bill of Entry, will be as following:</span></span>

    |<span data-ttu-id="69203-155">Particulars</span><span class="sxs-lookup"><span data-stu-id="69203-155">Particulars</span></span>|<span data-ttu-id="69203-156">Amount</span><span class="sxs-lookup"><span data-stu-id="69203-156">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="69203-157">**Purchase Account**</span><span class="sxs-lookup"><span data-stu-id="69203-157">**Purchase Account**</span></span>|<span data-ttu-id="69203-158">13160</span><span class="sxs-lookup"><span data-stu-id="69203-158">13160</span></span>|  
    |<span data-ttu-id="69203-159">**Vendor Account (Transaction Value)**</span><span class="sxs-lookup"><span data-stu-id="69203-159">**Vendor Account (Transaction Value)**</span></span>|<span data-ttu-id="69203-160">-13160</span><span class="sxs-lookup"><span data-stu-id="69203-160">-13160</span></span>|


- <span data-ttu-id="69203-161">GL Entries for import of fixed asset with input tax credit available from SEZ vendor with cover of Bill of Entry, will be as following:</span><span class="sxs-lookup"><span data-stu-id="69203-161">GL Entries for import of fixed asset with input tax credit available from SEZ vendor with cover of Bill of Entry, will be as following:</span></span>

    |<span data-ttu-id="69203-162">Particular</span><span class="sxs-lookup"><span data-stu-id="69203-162">Particular</span></span>|<span data-ttu-id="69203-163">Amount</span><span class="sxs-lookup"><span data-stu-id="69203-163">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="69203-164">**Fixed Asset Increased During the Year Account (Transactional Value+ BCD)**</span><span class="sxs-lookup"><span data-stu-id="69203-164">**Fixed Asset Increased During the Year Account (Transactional Value+ BCD)**</span></span>|<span data-ttu-id="69203-165">11000</span><span class="sxs-lookup"><span data-stu-id="69203-165">11000</span></span>|  
    |<span data-ttu-id="69203-166">**IGST Receivable Account (on GST Assessable Value + BCD)**</span><span class="sxs-lookup"><span data-stu-id="69203-166">**IGST Receivable Account (on GST Assessable Value + BCD)**</span></span>|<span data-ttu-id="69203-167">2160</span><span class="sxs-lookup"><span data-stu-id="69203-167">2160</span></span>| 
    |<span data-ttu-id="69203-168">**Customs House Account (GST Amount + BCD)**</span><span class="sxs-lookup"><span data-stu-id="69203-168">**Customs House Account (GST Amount + BCD)**</span></span>|<span data-ttu-id="69203-169">-3160</span><span class="sxs-lookup"><span data-stu-id="69203-169">-3160</span></span>|
    |<span data-ttu-id="69203-170">**Vendor Account (Transaction Value)**</span><span class="sxs-lookup"><span data-stu-id="69203-170">**Vendor Account (Transaction Value)**</span></span>|<span data-ttu-id="69203-171">-10000</span><span class="sxs-lookup"><span data-stu-id="69203-171">-10000</span></span>|

- <span data-ttu-id="69203-172">GL Entries for import of fixed assets with input tax credit available from SEZ vendor without cover of Bill of Entry, will be as following:</span><span class="sxs-lookup"><span data-stu-id="69203-172">GL Entries for import of fixed assets with input tax credit available from SEZ vendor without cover of Bill of Entry, will be as following:</span></span>

    |<span data-ttu-id="69203-173">Particulars</span><span class="sxs-lookup"><span data-stu-id="69203-173">Particulars</span></span>|<span data-ttu-id="69203-174">Amount</span><span class="sxs-lookup"><span data-stu-id="69203-174">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="69203-175">**Fixed Asset Increased During the Year Account  (Transactional Value+ BCD)**</span><span class="sxs-lookup"><span data-stu-id="69203-175">**Fixed Asset Increased During the Year Account  (Transactional Value+ BCD)**</span></span>|<span data-ttu-id="69203-176">11000</span><span class="sxs-lookup"><span data-stu-id="69203-176">11000</span></span>|  
    |<span data-ttu-id="69203-177">**IGST Receivable Account (on GST Assessable Value + BCD)**</span><span class="sxs-lookup"><span data-stu-id="69203-177">**IGST Receivable Account (on GST Assessable Value + BCD)**</span></span>|<span data-ttu-id="69203-178">2160</span><span class="sxs-lookup"><span data-stu-id="69203-178">2160</span></span>| 
    |<span data-ttu-id="69203-179">**Vendor Account (Transaction Value)**</span><span class="sxs-lookup"><span data-stu-id="69203-179">**Vendor Account (Transaction Value)**</span></span>|<span data-ttu-id="69203-180">-13160</span><span class="sxs-lookup"><span data-stu-id="69203-180">-13160</span></span>|

- <span data-ttu-id="69203-181">GL Entries for import of fixed asset without input tax credit available from SEZ vendor with cover of Bill of Entry, will be as following:</span><span class="sxs-lookup"><span data-stu-id="69203-181">GL Entries for import of fixed asset without input tax credit available from SEZ vendor with cover of Bill of Entry, will be as following:</span></span>

    |<span data-ttu-id="69203-182">Particular</span><span class="sxs-lookup"><span data-stu-id="69203-182">Particular</span></span>|<span data-ttu-id="69203-183">Amount</span><span class="sxs-lookup"><span data-stu-id="69203-183">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="69203-184">**Fixed Asset Increased During the Year Account**</span><span class="sxs-lookup"><span data-stu-id="69203-184">**Fixed Asset Increased During the Year Account**</span></span>|<span data-ttu-id="69203-185">13160</span><span class="sxs-lookup"><span data-stu-id="69203-185">13160</span></span>|  
    |<span data-ttu-id="69203-186">**Custom House Account**</span><span class="sxs-lookup"><span data-stu-id="69203-186">**Custom House Account**</span></span>|<span data-ttu-id="69203-187">3160</span><span class="sxs-lookup"><span data-stu-id="69203-187">3160</span></span>| 
    |<span data-ttu-id="69203-188">**Vendor Account (Transaction Value)**</span><span class="sxs-lookup"><span data-stu-id="69203-188">**Vendor Account (Transaction Value)**</span></span>|<span data-ttu-id="69203-189">-10000</span><span class="sxs-lookup"><span data-stu-id="69203-189">-10000</span></span>|

- <span data-ttu-id="69203-190">GL Entries for import of fixed asset without input tax credit available from SEZ vendor without cover of Bill of Entry, will be as following:</span><span class="sxs-lookup"><span data-stu-id="69203-190">GL Entries for import of fixed asset without input tax credit available from SEZ vendor without cover of Bill of Entry, will be as following:</span></span>

    |<span data-ttu-id="69203-191">Particular</span><span class="sxs-lookup"><span data-stu-id="69203-191">Particular</span></span>|<span data-ttu-id="69203-192">Amount</span><span class="sxs-lookup"><span data-stu-id="69203-192">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="69203-193">**Fixed Asset Increased During the Year Account**</span><span class="sxs-lookup"><span data-stu-id="69203-193">**Fixed Asset Increased During the Year Account**</span></span>|<span data-ttu-id="69203-194">13160</span><span class="sxs-lookup"><span data-stu-id="69203-194">13160</span></span>|  
    |<span data-ttu-id="69203-195">**Vendor Account (Transaction Value)**</span><span class="sxs-lookup"><span data-stu-id="69203-195">**Vendor Account (Transaction Value)**</span></span>|<span data-ttu-id="69203-196">-13160</span><span class="sxs-lookup"><span data-stu-id="69203-196">-13160</span></span>|

> [!NOTE]
> <span data-ttu-id="69203-197">The GST calculation process for SEZ vendor is same as for an Import vendor.</span><span class="sxs-lookup"><span data-stu-id="69203-197">The GST calculation process for SEZ vendor is same as for an Import vendor.</span></span>







































