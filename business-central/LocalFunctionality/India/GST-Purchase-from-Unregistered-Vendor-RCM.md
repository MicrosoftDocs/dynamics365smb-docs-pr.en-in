---
title: Purchase of Goods from an Unregistered Vendor (Reverse Charge)
description: Purchase of Goods from an Unregistered Vendor (Reverse Charge)
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: b8da3da4d6564969aa108844f67974b30638c121
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948637"
---
# <a name="purchase-of-goods-from-an-unregistered-vendor-reverse-charge"></a><span data-ttu-id="25918-103">Purchase of Goods from an Unregistered Vendor (Reverse Charge)</span><span class="sxs-lookup"><span data-stu-id="25918-103">Purchase of Goods from an Unregistered Vendor (Reverse Charge)</span></span>

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="25918-104">Persons whose aggregate turnover in a financial year does not exceed forty lakh rupees are not required to be registered with the GST authorities.</span><span class="sxs-lookup"><span data-stu-id="25918-104">Persons whose aggregate turnover in a financial year does not exceed forty lakh rupees are not required to be registered with the GST authorities.</span></span> <span data-ttu-id="25918-105">Such persons are called unregistered vendors.</span><span class="sxs-lookup"><span data-stu-id="25918-105">Such persons are called unregistered vendors.</span></span> <span data-ttu-id="25918-106">Any purchases from unregistered vendors do not attract GST.</span><span class="sxs-lookup"><span data-stu-id="25918-106">Any purchases from unregistered vendors do not attract GST.</span></span> <span data-ttu-id="25918-107">However, there are some notified services under GST, on supply of such services GST is applicable under reverse charge mechanism i.e. the purchasers are required to pay GST tax to the Government.</span><span class="sxs-lookup"><span data-stu-id="25918-107">However, there are some notified services under GST, on supply of such services GST is applicable under reverse charge mechanism i.e. the purchasers are required to pay GST tax to the Government.</span></span>

<span data-ttu-id="25918-108">Purchase process for unregistered vendor has been explained in this document.</span><span class="sxs-lookup"><span data-stu-id="25918-108">Purchase process for unregistered vendor has been explained in this document.</span></span>

## <a name="create-a-purchase-invoice"></a><span data-ttu-id="25918-109">Create a purchase invoice</span><span class="sxs-lookup"><span data-stu-id="25918-109">Create a purchase invoice</span></span>


1. <span data-ttu-id="25918-110">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Purchase Invoice** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="25918-110">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Purchase Invoice** , and then choose the related link.</span></span> 
2. <span data-ttu-id="25918-111">Select Vendor on **Purchase Invoice** header, GST vendor type should be **Unregistered** .</span><span class="sxs-lookup"><span data-stu-id="25918-111">Select Vendor on **Purchase Invoice** header, GST vendor type should be **Unregistered** .</span></span>
3. <span data-ttu-id="25918-112">Select **Item Code** for goods, **G/L Account** for Service purchase, **Fixed Asset** for Fixed Asset purchase and **Charge (Item)** for Item Charge on **Purchase Invoice** line.</span><span class="sxs-lookup"><span data-stu-id="25918-112">Select **Item Code** for goods, **G/L Account** for Service purchase, **Fixed Asset** for Fixed Asset purchase and **Charge (Item)** for Item Charge on **Purchase Invoice** line.</span></span> <span data-ttu-id="25918-113">GST Group Code, HSN/SAC Code and GST Credit value should be selected as **Availment** if the tax input credit is available or else **Non-Availment** should be selected on the Item or G/L Account.</span><span class="sxs-lookup"><span data-stu-id="25918-113">GST Group Code, HSN/SAC Code and GST Credit value should be selected as **Availment** if the tax input credit is available or else **Non-Availment** should be selected on the Item or G/L Account.</span></span> 
4. <span data-ttu-id="25918-114">GST Credit option can be changed on invoice line.</span><span class="sxs-lookup"><span data-stu-id="25918-114">GST Credit option can be changed on invoice line.</span></span>

<span data-ttu-id="25918-115">For example, invoice will be issued for INR 10,000 on which 18% GST (9% CGST and 9% SGST/UTGST in case of Intra-State or Intra-Union Territory transaction or 18% IGST in case of Inter-State transaction), has to be charged.</span><span class="sxs-lookup"><span data-stu-id="25918-115">For example, invoice will be issued for INR 10,000 on which 18% GST (9% CGST and 9% SGST/UTGST in case of Intra-State or Intra-Union Territory transaction or 18% IGST in case of Inter-State transaction), has to be charged.</span></span>

- <span data-ttu-id="25918-116">GST calculation will appear in the Fact Box, as following:</span><span class="sxs-lookup"><span data-stu-id="25918-116">GST calculation will appear in the Fact Box, as following:</span></span>
    
    |<span data-ttu-id="25918-117">Component</span><span class="sxs-lookup"><span data-stu-id="25918-117">Component</span></span>|<span data-ttu-id="25918-118">Amount</span><span class="sxs-lookup"><span data-stu-id="25918-118">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="25918-119">**GST Base Amount**</span><span class="sxs-lookup"><span data-stu-id="25918-119">**GST Base Amount**</span></span>|<span data-ttu-id="25918-120">10,000</span><span class="sxs-lookup"><span data-stu-id="25918-120">10,000</span></span>|  
    |<span data-ttu-id="25918-121">**CGST**</span><span class="sxs-lookup"><span data-stu-id="25918-121">**CGST**</span></span>|<span data-ttu-id="25918-122">900</span><span class="sxs-lookup"><span data-stu-id="25918-122">900</span></span>|  
    |<span data-ttu-id="25918-123">**SGST**</span><span class="sxs-lookup"><span data-stu-id="25918-123">**SGST**</span></span>|<span data-ttu-id="25918-124">900</span><span class="sxs-lookup"><span data-stu-id="25918-124">900</span></span>|
    |<span data-ttu-id="25918-125">**IGST**</span><span class="sxs-lookup"><span data-stu-id="25918-125">**IGST**</span></span>|<span data-ttu-id="25918-126">1800</span><span class="sxs-lookup"><span data-stu-id="25918-126">1800</span></span>|

- <span data-ttu-id="25918-127">GL Entries for Intra-State purchase of goods and services from an unregistered vendor where input tax credit is available (reverse charge), will be as following:</span><span class="sxs-lookup"><span data-stu-id="25918-127">GL Entries for Intra-State purchase of goods and services from an unregistered vendor where input tax credit is available (reverse charge), will be as following:</span></span>
    
    |<span data-ttu-id="25918-128">Particulars</span><span class="sxs-lookup"><span data-stu-id="25918-128">Particulars</span></span>|<span data-ttu-id="25918-129">Amount</span><span class="sxs-lookup"><span data-stu-id="25918-129">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="25918-130">**Service Account**</span><span class="sxs-lookup"><span data-stu-id="25918-130">**Service Account**</span></span>|<span data-ttu-id="25918-131">10000</span><span class="sxs-lookup"><span data-stu-id="25918-131">10000</span></span>|  
    |<span data-ttu-id="25918-132">**SGST/UTGST Receivable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="25918-132">**SGST/UTGST Receivable (Interim) Account**</span></span>|<span data-ttu-id="25918-133">900</span><span class="sxs-lookup"><span data-stu-id="25918-133">900</span></span>|
    |<span data-ttu-id="25918-134">**CGST Receivable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="25918-134">**CGST Receivable (Interim) Account**</span></span>|<span data-ttu-id="25918-135">900</span><span class="sxs-lookup"><span data-stu-id="25918-135">900</span></span>|
    |<span data-ttu-id="25918-136">**SGST/UTGST Payable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="25918-136">**SGST/UTGST Payable (Interim) Account**</span></span>|<span data-ttu-id="25918-137">-900</span><span class="sxs-lookup"><span data-stu-id="25918-137">-900</span></span>|
    |<span data-ttu-id="25918-138">**CGST Payable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="25918-138">**CGST Payable (Interim) Account**</span></span>|<span data-ttu-id="25918-139">-900</span><span class="sxs-lookup"><span data-stu-id="25918-139">-900</span></span>|
    |<span data-ttu-id="25918-140">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="25918-140">**Vendor Account**</span></span>|<span data-ttu-id="25918-141">-10000</span><span class="sxs-lookup"><span data-stu-id="25918-141">-10000</span></span>|

- <span data-ttu-id="25918-142">GL Entries for Intra-State purchase of goods and services from an unregistered vendor where input tax credit is not available (reverse charge), will be as following:</span><span class="sxs-lookup"><span data-stu-id="25918-142">GL Entries for Intra-State purchase of goods and services from an unregistered vendor where input tax credit is not available (reverse charge), will be as following:</span></span>
    
    |<span data-ttu-id="25918-143">Particulars</span><span class="sxs-lookup"><span data-stu-id="25918-143">Particulars</span></span>|<span data-ttu-id="25918-144">Amount</span><span class="sxs-lookup"><span data-stu-id="25918-144">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="25918-145">**Purchase or Services Account**</span><span class="sxs-lookup"><span data-stu-id="25918-145">**Purchase or Services Account**</span></span>|<span data-ttu-id="25918-146">11800</span><span class="sxs-lookup"><span data-stu-id="25918-146">11800</span></span>|  
    |<span data-ttu-id="25918-147">**SGST/UTGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="25918-147">**SGST/UTGST Payable Account**</span></span>|<span data-ttu-id="25918-148">-900</span><span class="sxs-lookup"><span data-stu-id="25918-148">-900</span></span>|
    |<span data-ttu-id="25918-149">**CGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="25918-149">**CGST Payable Account**</span></span>|<span data-ttu-id="25918-150">-900</span><span class="sxs-lookup"><span data-stu-id="25918-150">-900</span></span>|
    |<span data-ttu-id="25918-151">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="25918-151">**Vendor Account**</span></span>|<span data-ttu-id="25918-152">-10000</span><span class="sxs-lookup"><span data-stu-id="25918-152">-10000</span></span>|

- <span data-ttu-id="25918-153">GL Entries for purchase of goods and services from an unregistered vendor with reverse charge exempt, will be as following:</span><span class="sxs-lookup"><span data-stu-id="25918-153">GL Entries for purchase of goods and services from an unregistered vendor with reverse charge exempt, will be as following:</span></span>
    
    |<span data-ttu-id="25918-154">Particulars</span><span class="sxs-lookup"><span data-stu-id="25918-154">Particulars</span></span>|<span data-ttu-id="25918-155">Amount</span><span class="sxs-lookup"><span data-stu-id="25918-155">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="25918-156">**Purchase or Services Account**</span><span class="sxs-lookup"><span data-stu-id="25918-156">**Purchase or Services Account**</span></span>|<span data-ttu-id="25918-157">10000</span><span class="sxs-lookup"><span data-stu-id="25918-157">10000</span></span>|  
    |<span data-ttu-id="25918-158">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="25918-158">**Vendor Account**</span></span>|<span data-ttu-id="25918-159">-10000</span><span class="sxs-lookup"><span data-stu-id="25918-159">-10000</span></span>|

- <span data-ttu-id="25918-160">GL Entries for Intra-State purchase of fixed asset from an unregistered vendor where input tax credit is available (reverse charge), will be as following:</span><span class="sxs-lookup"><span data-stu-id="25918-160">GL Entries for Intra-State purchase of fixed asset from an unregistered vendor where input tax credit is available (reverse charge), will be as following:</span></span>
    
    |<span data-ttu-id="25918-161">Particulars</span><span class="sxs-lookup"><span data-stu-id="25918-161">Particulars</span></span>|<span data-ttu-id="25918-162">Amount</span><span class="sxs-lookup"><span data-stu-id="25918-162">Amount</span></span>|
    |----------------------------------|---------------------------------------|
    |<span data-ttu-id="25918-163">**Fixed Asset Increases during the Year**</span><span class="sxs-lookup"><span data-stu-id="25918-163">**Fixed Asset Increases during the Year**</span></span>|<span data-ttu-id="25918-164">10000</span><span class="sxs-lookup"><span data-stu-id="25918-164">10000</span></span>|
    |<span data-ttu-id="25918-165">**SGST Receivable Account (Interim)**</span><span class="sxs-lookup"><span data-stu-id="25918-165">**SGST Receivable Account (Interim)**</span></span>|<span data-ttu-id="25918-166">900</span><span class="sxs-lookup"><span data-stu-id="25918-166">900</span></span>|
    |<span data-ttu-id="25918-167">**CGST Receivable Account (Interim)**</span><span class="sxs-lookup"><span data-stu-id="25918-167">**CGST Receivable Account (Interim)**</span></span>|<span data-ttu-id="25918-168">900</span><span class="sxs-lookup"><span data-stu-id="25918-168">900</span></span>|
    |<span data-ttu-id="25918-169">**SGST Payable Account (Interim)**</span><span class="sxs-lookup"><span data-stu-id="25918-169">**SGST Payable Account (Interim)**</span></span>|<span data-ttu-id="25918-170">-900</span><span class="sxs-lookup"><span data-stu-id="25918-170">-900</span></span>|
    |<span data-ttu-id="25918-171">**CGST Payable Account (Interim)**</span><span class="sxs-lookup"><span data-stu-id="25918-171">**CGST Payable Account (Interim)**</span></span>|<span data-ttu-id="25918-172">-900</span><span class="sxs-lookup"><span data-stu-id="25918-172">-900</span></span>|
    |<span data-ttu-id="25918-173">**Vendor**</span><span class="sxs-lookup"><span data-stu-id="25918-173">**Vendor**</span></span>|<span data-ttu-id="25918-174">10000</span><span class="sxs-lookup"><span data-stu-id="25918-174">10000</span></span>|

- <span data-ttu-id="25918-175">GL Entries for Intra-State purchase of fixed asset from an unregistered vendor where input tax credit is not available (reverse charge), will be as following:</span><span class="sxs-lookup"><span data-stu-id="25918-175">GL Entries for Intra-State purchase of fixed asset from an unregistered vendor where input tax credit is not available (reverse charge), will be as following:</span></span>
    
    |<span data-ttu-id="25918-176">Particulars</span><span class="sxs-lookup"><span data-stu-id="25918-176">Particulars</span></span>|<span data-ttu-id="25918-177">Amount</span><span class="sxs-lookup"><span data-stu-id="25918-177">Amount</span></span>|
    |----------------------------------|---------------------------------------|
    |<span data-ttu-id="25918-178">**Fixed Asset Increases during the Year**</span><span class="sxs-lookup"><span data-stu-id="25918-178">**Fixed Asset Increases during the Year**</span></span>|<span data-ttu-id="25918-179">11800</span><span class="sxs-lookup"><span data-stu-id="25918-179">11800</span></span>|
    |<span data-ttu-id="25918-180">**SGST Payable Account (Interim)**</span><span class="sxs-lookup"><span data-stu-id="25918-180">**SGST Payable Account (Interim)**</span></span>|<span data-ttu-id="25918-181">-900</span><span class="sxs-lookup"><span data-stu-id="25918-181">-900</span></span>|
    |<span data-ttu-id="25918-182">**CGST Payable Account (Interim)**</span><span class="sxs-lookup"><span data-stu-id="25918-182">**CGST Payable Account (Interim)**</span></span>|<span data-ttu-id="25918-183">-900</span><span class="sxs-lookup"><span data-stu-id="25918-183">-900</span></span>|
    |<span data-ttu-id="25918-184">**Vendor**</span><span class="sxs-lookup"><span data-stu-id="25918-184">**Vendor**</span></span>|<span data-ttu-id="25918-185">10000</span><span class="sxs-lookup"><span data-stu-id="25918-185">10000</span></span>|

- <span data-ttu-id="25918-186">GL Entries for Item Charge in case of Intra-State purchase of fixed asset from an unregistered vendor where input tax credit is available (reverse charge), will be as following:</span><span class="sxs-lookup"><span data-stu-id="25918-186">GL Entries for Item Charge in case of Intra-State purchase of fixed asset from an unregistered vendor where input tax credit is available (reverse charge), will be as following:</span></span>
    
    |<span data-ttu-id="25918-187">Particulars</span><span class="sxs-lookup"><span data-stu-id="25918-187">Particulars</span></span>|<span data-ttu-id="25918-188">Amount</span><span class="sxs-lookup"><span data-stu-id="25918-188">Amount</span></span>|
    |----------------------------------|---------------------------------------| 
    |<span data-ttu-id="25918-189">**Purchase Account**</span><span class="sxs-lookup"><span data-stu-id="25918-189">**Purchase Account**</span></span>|<span data-ttu-id="25918-190">10000</span><span class="sxs-lookup"><span data-stu-id="25918-190">10000</span></span>|
    |<span data-ttu-id="25918-191">**SGST Receivable Account (Interim)**</span><span class="sxs-lookup"><span data-stu-id="25918-191">**SGST Receivable Account (Interim)**</span></span>|<span data-ttu-id="25918-192">900</span><span class="sxs-lookup"><span data-stu-id="25918-192">900</span></span>|
    |<span data-ttu-id="25918-193">**CGST Receivable Account (Interim)**</span><span class="sxs-lookup"><span data-stu-id="25918-193">**CGST Receivable Account (Interim)**</span></span>|<span data-ttu-id="25918-194">900</span><span class="sxs-lookup"><span data-stu-id="25918-194">900</span></span>|
    |<span data-ttu-id="25918-195">**SGST Payable Account (Interim)**</span><span class="sxs-lookup"><span data-stu-id="25918-195">**SGST Payable Account (Interim)**</span></span>|<span data-ttu-id="25918-196">-900</span><span class="sxs-lookup"><span data-stu-id="25918-196">-900</span></span>|
    |<span data-ttu-id="25918-197">**CGST Payable Account (Interim)**</span><span class="sxs-lookup"><span data-stu-id="25918-197">**CGST Payable Account (Interim)**</span></span>|<span data-ttu-id="25918-198">-900</span><span class="sxs-lookup"><span data-stu-id="25918-198">-900</span></span>|
    |<span data-ttu-id="25918-199">**Vendor**</span><span class="sxs-lookup"><span data-stu-id="25918-199">**Vendor**</span></span>|<span data-ttu-id="25918-200">10000</span><span class="sxs-lookup"><span data-stu-id="25918-200">10000</span></span>|

- <span data-ttu-id="25918-201">GL Entries for Item Charge in case of Intra-State purchase of fixed asset from an unregistered vendor where input tax credit is not available (reverse charge),will be as following:</span><span class="sxs-lookup"><span data-stu-id="25918-201">GL Entries for Item Charge in case of Intra-State purchase of fixed asset from an unregistered vendor where input tax credit is not available (reverse charge),will be as following:</span></span>
    
    |<span data-ttu-id="25918-202">Particulars</span><span class="sxs-lookup"><span data-stu-id="25918-202">Particulars</span></span>|<span data-ttu-id="25918-203">Amount</span><span class="sxs-lookup"><span data-stu-id="25918-203">Amount</span></span>|
    |----------------------------------|---------------------------------------| 
    |<span data-ttu-id="25918-204">**Purchase Account**</span><span class="sxs-lookup"><span data-stu-id="25918-204">**Purchase Account**</span></span>|<span data-ttu-id="25918-205">10000</span><span class="sxs-lookup"><span data-stu-id="25918-205">10000</span></span>|
    |<span data-ttu-id="25918-206">**SGST Payable Account (Interim)**</span><span class="sxs-lookup"><span data-stu-id="25918-206">**SGST Payable Account (Interim)**</span></span>|<span data-ttu-id="25918-207">-900</span><span class="sxs-lookup"><span data-stu-id="25918-207">-900</span></span>|
    |<span data-ttu-id="25918-208">**CGST Payable Account (Interim)**</span><span class="sxs-lookup"><span data-stu-id="25918-208">**CGST Payable Account (Interim)**</span></span>|<span data-ttu-id="25918-209">-900</span><span class="sxs-lookup"><span data-stu-id="25918-209">-900</span></span>|
    |<span data-ttu-id="25918-210">**Vendor**</span><span class="sxs-lookup"><span data-stu-id="25918-210">**Vendor**</span></span>|<span data-ttu-id="25918-211">10000</span><span class="sxs-lookup"><span data-stu-id="25918-211">10000</span></span>|







































