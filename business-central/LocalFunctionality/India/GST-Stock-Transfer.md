---
title: Stock Transfer
description: Stock Transfer
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 51598cac372002427564472185a9d9f61617e716
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948625"
---
# <a name="stock-transfer"></a><span data-ttu-id="8a99e-103">Stock Transfer</span><span class="sxs-lookup"><span data-stu-id="8a99e-103">Stock Transfer</span></span>

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="8a99e-104">Stock transfers between locations, branches or divisions having different registration numbers are taxable under GST.</span><span class="sxs-lookup"><span data-stu-id="8a99e-104">Stock transfers between locations, branches or divisions having different registration numbers are taxable under GST.</span></span> <span data-ttu-id="8a99e-105">In such a case, where registration number is same, if the shipment location and recipient location both are in the same state, then CGST and SGST/UTGST are levied, other-wise, where the registration number is same, there shall be no levy.</span><span class="sxs-lookup"><span data-stu-id="8a99e-105">In such a case, where registration number is same, if the shipment location and recipient location both are in the same state, then CGST and SGST/UTGST are levied, other-wise, where the registration number is same, there shall be no levy.</span></span>

1.  <span data-ttu-id="8a99e-106">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Transfer Order** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="8a99e-106">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Transfer Order** , and then choose the related link.</span></span> 
2. <span data-ttu-id="8a99e-107">Select **Transfer-from Code** and **Transfer-to Code** on **Transfer Order** header.</span><span class="sxs-lookup"><span data-stu-id="8a99e-107">Select **Transfer-from Code** and **Transfer-to Code** on **Transfer Order** header.</span></span>  <span data-ttu-id="8a99e-108">State Code and GST registration number should be filled on the location master.</span><span class="sxs-lookup"><span data-stu-id="8a99e-108">State Code and GST registration number should be filled on the location master.</span></span>

3. <span data-ttu-id="8a99e-109">Select **Item** on **Transfer Order** line.</span><span class="sxs-lookup"><span data-stu-id="8a99e-109">Select **Item** on **Transfer Order** line.</span></span> <span data-ttu-id="8a99e-110">GST Group Code, HSN/SAC Code should be filled on **Item** .</span><span class="sxs-lookup"><span data-stu-id="8a99e-110">GST Group Code, HSN/SAC Code should be filled on **Item** .</span></span>


<span data-ttu-id="8a99e-111">For example, inventory for INR 1000 is being transferred from one location to another and 18% GST (9% CGST and 9% SGST/UTGST in case of Intra-State or Intra-Union Territory transaction or 18% IGST in case of Inter-State transaction) has to be charged on INR 1000.</span><span class="sxs-lookup"><span data-stu-id="8a99e-111">For example, inventory for INR 1000 is being transferred from one location to another and 18% GST (9% CGST and 9% SGST/UTGST in case of Intra-State or Intra-Union Territory transaction or 18% IGST in case of Inter-State transaction) has to be charged on INR 1000.</span></span>

- <span data-ttu-id="8a99e-112">GST calculation will appear in the Fact Box, as following:</span><span class="sxs-lookup"><span data-stu-id="8a99e-112">GST calculation will appear in the Fact Box, as following:</span></span>
    
    |<span data-ttu-id="8a99e-113">Component</span><span class="sxs-lookup"><span data-stu-id="8a99e-113">Component</span></span>|<span data-ttu-id="8a99e-114">Amount</span><span class="sxs-lookup"><span data-stu-id="8a99e-114">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="8a99e-115">**GST Base Amount**</span><span class="sxs-lookup"><span data-stu-id="8a99e-115">**GST Base Amount**</span></span>|<span data-ttu-id="8a99e-116">1000</span><span class="sxs-lookup"><span data-stu-id="8a99e-116">1000</span></span>|  
    |<span data-ttu-id="8a99e-117">**IGST**</span><span class="sxs-lookup"><span data-stu-id="8a99e-117">**IGST**</span></span>|<span data-ttu-id="8a99e-118">180</span><span class="sxs-lookup"><span data-stu-id="8a99e-118">180</span></span>|
    |<span data-ttu-id="8a99e-119">**CGST**</span><span class="sxs-lookup"><span data-stu-id="8a99e-119">**CGST**</span></span>|<span data-ttu-id="8a99e-120">90</span><span class="sxs-lookup"><span data-stu-id="8a99e-120">90</span></span>| 
    |<span data-ttu-id="8a99e-121">**SGST**</span><span class="sxs-lookup"><span data-stu-id="8a99e-121">**SGST**</span></span>|<span data-ttu-id="8a99e-122">90</span><span class="sxs-lookup"><span data-stu-id="8a99e-122">90</span></span>|

<span data-ttu-id="8a99e-123">Post the Transfer Order</span><span class="sxs-lookup"><span data-stu-id="8a99e-123">Post the Transfer Order</span></span>

- <span data-ttu-id="8a99e-124">GL Entries for shipment transaction in case of Interstate stock transfer, will be as following:</span><span class="sxs-lookup"><span data-stu-id="8a99e-124">GL Entries for shipment transaction in case of Interstate stock transfer, will be as following:</span></span>

    |<span data-ttu-id="8a99e-125">Particulars</span><span class="sxs-lookup"><span data-stu-id="8a99e-125">Particulars</span></span>|<span data-ttu-id="8a99e-126">Amount</span><span class="sxs-lookup"><span data-stu-id="8a99e-126">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="8a99e-127">**Unrealised Profit Account**</span><span class="sxs-lookup"><span data-stu-id="8a99e-127">**Unrealized Profit Account**</span></span>|<span data-ttu-id="8a99e-128">180</span><span class="sxs-lookup"><span data-stu-id="8a99e-128">180</span></span>|
    |<span data-ttu-id="8a99e-129">**IGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="8a99e-129">**IGST Payable Account**</span></span>|<span data-ttu-id="8a99e-130">-180</span><span class="sxs-lookup"><span data-stu-id="8a99e-130">-180</span></span>|
    |<span data-ttu-id="8a99e-131">**Inventory Adjustment Account**</span><span class="sxs-lookup"><span data-stu-id="8a99e-131">**Inventory Adjustment Account**</span></span>|<span data-ttu-id="8a99e-132">1000</span><span class="sxs-lookup"><span data-stu-id="8a99e-132">1000</span></span>|
    |<span data-ttu-id="8a99e-133">**Inventory Account**</span><span class="sxs-lookup"><span data-stu-id="8a99e-133">**Inventory Account**</span></span>|<span data-ttu-id="8a99e-134">-1000</span><span class="sxs-lookup"><span data-stu-id="8a99e-134">-1000</span></span>|

- <span data-ttu-id="8a99e-135">GL Entries for receipt transaction in case of Interstate stock transfer, will be as following:</span><span class="sxs-lookup"><span data-stu-id="8a99e-135">GL Entries for receipt transaction in case of Interstate stock transfer, will be as following:</span></span>
    
    |<span data-ttu-id="8a99e-136">Particulars</span><span class="sxs-lookup"><span data-stu-id="8a99e-136">Particulars</span></span>|<span data-ttu-id="8a99e-137">Amount</span><span class="sxs-lookup"><span data-stu-id="8a99e-137">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="8a99e-138">**IGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="8a99e-138">**IGST Receivable Account**</span></span>|<span data-ttu-id="8a99e-139">180</span><span class="sxs-lookup"><span data-stu-id="8a99e-139">180</span></span>|  
    |<span data-ttu-id="8a99e-140">**Unrealised Profit Account**</span><span class="sxs-lookup"><span data-stu-id="8a99e-140">**Unrealized Profit Account**</span></span>|<span data-ttu-id="8a99e-141">-180</span><span class="sxs-lookup"><span data-stu-id="8a99e-141">-180</span></span>|  
    |<span data-ttu-id="8a99e-142">**Inventory Account**</span><span class="sxs-lookup"><span data-stu-id="8a99e-142">**Inventory Account**</span></span>|<span data-ttu-id="8a99e-143">1000</span><span class="sxs-lookup"><span data-stu-id="8a99e-143">1000</span></span>|
    |<span data-ttu-id="8a99e-144">**Inventory Adjustment Account**</span><span class="sxs-lookup"><span data-stu-id="8a99e-144">**Inventory Adjustment Account**</span></span>|<span data-ttu-id="8a99e-145">-1000</span><span class="sxs-lookup"><span data-stu-id="8a99e-145">-1000</span></span>|

- <span data-ttu-id="8a99e-146">GL Entries for shipment transaction in case of Intra-State or Intra-Union Territory stock transfer, will be as following:</span><span class="sxs-lookup"><span data-stu-id="8a99e-146">GL Entries for shipment transaction in case of Intra-State or Intra-Union Territory stock transfer, will be as following:</span></span>

    |<span data-ttu-id="8a99e-147">Particulars</span><span class="sxs-lookup"><span data-stu-id="8a99e-147">Particulars</span></span>|<span data-ttu-id="8a99e-148">Amount</span><span class="sxs-lookup"><span data-stu-id="8a99e-148">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="8a99e-149">**Unrealised Profit Account**</span><span class="sxs-lookup"><span data-stu-id="8a99e-149">**Unrealized Profit Account**</span></span>|<span data-ttu-id="8a99e-150">180</span><span class="sxs-lookup"><span data-stu-id="8a99e-150">180</span></span>|  
    |<span data-ttu-id="8a99e-151">**CGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="8a99e-151">**CGST Payable Account**</span></span>|<span data-ttu-id="8a99e-152">-90</span><span class="sxs-lookup"><span data-stu-id="8a99e-152">-90</span></span>|
    |<span data-ttu-id="8a99e-153">**SGST/UTGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="8a99e-153">**SGST/UTGST Payable Account**</span></span>|<span data-ttu-id="8a99e-154">-90</span><span class="sxs-lookup"><span data-stu-id="8a99e-154">-90</span></span>|  
    |<span data-ttu-id="8a99e-155">**Inventory Account**</span><span class="sxs-lookup"><span data-stu-id="8a99e-155">**Inventory Account**</span></span>|<span data-ttu-id="8a99e-156">-1000</span><span class="sxs-lookup"><span data-stu-id="8a99e-156">-1000</span></span>|
    |<span data-ttu-id="8a99e-157">**Inventory Adjustment Account**</span><span class="sxs-lookup"><span data-stu-id="8a99e-157">**Inventory Adjustment Account**</span></span>|<span data-ttu-id="8a99e-158">1000</span><span class="sxs-lookup"><span data-stu-id="8a99e-158">1000</span></span>|

- <span data-ttu-id="8a99e-159">GL Entries for receipt transaction in case of Intra-State or Intra-Union Territory stock transfer, will be as following:</span><span class="sxs-lookup"><span data-stu-id="8a99e-159">GL Entries for receipt transaction in case of Intra-State or Intra-Union Territory stock transfer, will be as following:</span></span>

    |<span data-ttu-id="8a99e-160">Particulars</span><span class="sxs-lookup"><span data-stu-id="8a99e-160">Particulars</span></span>|<span data-ttu-id="8a99e-161">Amount</span><span class="sxs-lookup"><span data-stu-id="8a99e-161">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="8a99e-162">**Unrealised Profit Account**</span><span class="sxs-lookup"><span data-stu-id="8a99e-162">**Unrealized Profit Account**</span></span>|<span data-ttu-id="8a99e-163">-180</span><span class="sxs-lookup"><span data-stu-id="8a99e-163">-180</span></span>|  
    |<span data-ttu-id="8a99e-164">**CGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="8a99e-164">**CGST Receivable Account**</span></span>|<span data-ttu-id="8a99e-165">90</span><span class="sxs-lookup"><span data-stu-id="8a99e-165">90</span></span>|
    |<span data-ttu-id="8a99e-166">**SGST/UTGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="8a99e-166">**SGST/UTGST Receivable Account**</span></span>|<span data-ttu-id="8a99e-167">90</span><span class="sxs-lookup"><span data-stu-id="8a99e-167">90</span></span>|  
    |<span data-ttu-id="8a99e-168">**Inventory Account**</span><span class="sxs-lookup"><span data-stu-id="8a99e-168">**Inventory Account**</span></span>|<span data-ttu-id="8a99e-169">1000</span><span class="sxs-lookup"><span data-stu-id="8a99e-169">1000</span></span>| 
    |<span data-ttu-id="8a99e-170">**Inventory Adjustment Account**</span><span class="sxs-lookup"><span data-stu-id="8a99e-170">**Inventory Adjustment Account**</span></span>|<span data-ttu-id="8a99e-171">-1000</span><span class="sxs-lookup"><span data-stu-id="8a99e-171">-1000</span></span>|

## <a name="stock-transfer-for-bonded-warehouse"></a><span data-ttu-id="8a99e-172">Stock transfer for bonded warehouse</span><span class="sxs-lookup"><span data-stu-id="8a99e-172">Stock transfer for bonded warehouse</span></span>

<span data-ttu-id="8a99e-173">Bonded warehouse transfer means transfer of stock from customs warehouse to company warehouse.</span><span class="sxs-lookup"><span data-stu-id="8a99e-173">Bonded warehouse transfer means transfer of stock from customs warehouse to company warehouse.</span></span> <span data-ttu-id="8a99e-174">This scenarios occurs when material is stored at customs warehouse before moving it to company’s warehouse.</span><span class="sxs-lookup"><span data-stu-id="8a99e-174">This scenarios occurs when material is stored at customs warehouse before moving it to company’s warehouse.</span></span> <span data-ttu-id="8a99e-175">In this case the customs duty will be paid only when material is moved from bonded warehouse.</span><span class="sxs-lookup"><span data-stu-id="8a99e-175">In this case the customs duty will be paid only when material is moved from bonded warehouse.</span></span>

1. <span data-ttu-id="8a99e-176">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Transfer Order** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="8a99e-176">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Transfer Order** , and then choose the related link.</span></span> 
2. <span data-ttu-id="8a99e-177">Select **Transfer-from Code** and **Transfer-to Code** on **Transfer Order** header.</span><span class="sxs-lookup"><span data-stu-id="8a99e-177">Select **Transfer-from Code** and **Transfer-to Code** on **Transfer Order** header.</span></span> 
3. <span data-ttu-id="8a99e-178">State Code and GST registration number should be filled on Transfer-to **Location** .</span><span class="sxs-lookup"><span data-stu-id="8a99e-178">State Code and GST registration number should be filled on Transfer-to **Location** .</span></span>
4. <span data-ttu-id="8a99e-179">**Bonded warehouse** field should be marked true on Transfer-from **Location** .</span><span class="sxs-lookup"><span data-stu-id="8a99e-179">**Bonded warehouse** field should be marked true on Transfer-from **Location** .</span></span>

3. <span data-ttu-id="8a99e-180">Select **Item** on **Transfer Order** line.</span><span class="sxs-lookup"><span data-stu-id="8a99e-180">Select **Item** on **Transfer Order** line.</span></span> <span data-ttu-id="8a99e-181">GST Group Code, HSN/SAC Code should be filled on **Item** .</span><span class="sxs-lookup"><span data-stu-id="8a99e-181">GST Group Code, HSN/SAC Code should be filled on **Item** .</span></span>

4. <span data-ttu-id="8a99e-182">Enter **GST Assessable Value** and **Custom Duty Amount** on **Transfer Order** lines.</span><span class="sxs-lookup"><span data-stu-id="8a99e-182">Enter **GST Assessable Value** and **Custom Duty Amount** on **Transfer Order** lines.</span></span> <span data-ttu-id="8a99e-183">System calculates GST on GST Assessable Value and Custom Duty Amount, not on transaction line amount.</span><span class="sxs-lookup"><span data-stu-id="8a99e-183">System calculates GST on GST Assessable Value and Custom Duty Amount, not on transaction line amount.</span></span>

5. <span data-ttu-id="8a99e-184">**Bill of Entry Number** , **Bill of Entry Date** and **Vendor Code** on **Transfer Order** header should not be blank.</span><span class="sxs-lookup"><span data-stu-id="8a99e-184">**Bill of Entry Number** , **Bill of Entry Date** and **Vendor Code** on **Transfer Order** header should not be blank.</span></span>






































