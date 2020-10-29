---
title: Purchase from Registered Vendors
description: Purchase from Registered Vendors
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: f3be88515bc4c7d6ba18397ab4ea6375732ec7da
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948639"
---
# <a name="purchase-from-registered-vendors"></a><span data-ttu-id="1441c-103">Purchase from Registered Vendors</span><span class="sxs-lookup"><span data-stu-id="1441c-103">Purchase from Registered Vendors</span></span>

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="1441c-104">A registered vendor is a person registered with GST authorities.</span><span class="sxs-lookup"><span data-stu-id="1441c-104">A registered vendor is a person registered with GST authorities.</span></span> <span data-ttu-id="1441c-105">For a registered vendor, on the vendor card, update the following fields:</span><span class="sxs-lookup"><span data-stu-id="1441c-105">For a registered vendor, on the vendor card, update the following fields:</span></span>
  - <span data-ttu-id="1441c-106">GST Vendor Type as Registered.</span><span class="sxs-lookup"><span data-stu-id="1441c-106">GST Vendor Type as Registered.</span></span> 
  - <span data-ttu-id="1441c-107">GST Registration No.</span><span class="sxs-lookup"><span data-stu-id="1441c-107">GST Registration No.</span></span>
  - <span data-ttu-id="1441c-108">State Code</span><span class="sxs-lookup"><span data-stu-id="1441c-108">State Code</span></span>

<span data-ttu-id="1441c-109">For purchases from registered vendors for services attracting reverse charge, purchasers are required to pay the GST tax, to the Government.</span><span class="sxs-lookup"><span data-stu-id="1441c-109">For purchases from registered vendors for services attracting reverse charge, purchasers are required to pay the GST tax, to the Government.</span></span>
<span data-ttu-id="1441c-110">If exempted goods and services are purchased from registered vendor, then no GST is to be paid to supplier or to the Government.</span><span class="sxs-lookup"><span data-stu-id="1441c-110">If exempted goods and services are purchased from registered vendor, then no GST is to be paid to supplier or to the Government.</span></span>

<span data-ttu-id="1441c-111">Process for purchase from a registered vendor has been explained in this document.</span><span class="sxs-lookup"><span data-stu-id="1441c-111">Process for purchase from a registered vendor has been explained in this document.</span></span>


## <a name="create-a-purchase-invoice"></a><span data-ttu-id="1441c-112">Create a purchase invoice</span><span class="sxs-lookup"><span data-stu-id="1441c-112">Create a purchase invoice</span></span>

1. <span data-ttu-id="1441c-113">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Purchase Invoice** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="1441c-113">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Purchase Invoice** , and then choose the related link.</span></span> 
2. <span data-ttu-id="1441c-114">Select **Vendor** on **Purchase Invoice** header, GST vendor type should be **Registered** .</span><span class="sxs-lookup"><span data-stu-id="1441c-114">Select **Vendor** on **Purchase Invoice** header, GST vendor type should be **Registered** .</span></span>
3. <span data-ttu-id="1441c-115">Select **Item Code** for goods, **G/L Account** for Service purchase, **Fixed Asset** for Fixed Asset purchase and **Charge (Item)** for Item Charge on **Purchase Invoice** line.</span><span class="sxs-lookup"><span data-stu-id="1441c-115">Select **Item Code** for goods, **G/L Account** for Service purchase, **Fixed Asset** for Fixed Asset purchase and **Charge (Item)** for Item Charge on **Purchase Invoice** line.</span></span> <span data-ttu-id="1441c-116">GST Group Code, HSN/SAC Code and GST Credit value should be selected as **Availment** if the tax input credit is available or else **Non-Availment** should be selected on the Item or G/L Account.</span><span class="sxs-lookup"><span data-stu-id="1441c-116">GST Group Code, HSN/SAC Code and GST Credit value should be selected as **Availment** if the tax input credit is available or else **Non-Availment** should be selected on the Item or G/L Account.</span></span> 
4. <span data-ttu-id="1441c-117">GST Credit option can be changed on invoice line.</span><span class="sxs-lookup"><span data-stu-id="1441c-117">GST Credit option can be changed on invoice line.</span></span>

<span data-ttu-id="1441c-118">For example, invoice will be issued for INR 10,000 on which 18% GST (9% CGST and 9% SGST/UTGST in case of Intra-State or Intra-Union Territory transaction or 18% IGST in case of Inter-State transaction), has to be charged.</span><span class="sxs-lookup"><span data-stu-id="1441c-118">For example, invoice will be issued for INR 10,000 on which 18% GST (9% CGST and 9% SGST/UTGST in case of Intra-State or Intra-Union Territory transaction or 18% IGST in case of Inter-State transaction), has to be charged.</span></span>

- <span data-ttu-id="1441c-119">GST calculation will appear in the Fact Box, as following:</span><span class="sxs-lookup"><span data-stu-id="1441c-119">GST calculation will appear in the Fact Box, as following:</span></span>
    
    |<span data-ttu-id="1441c-120">Component</span><span class="sxs-lookup"><span data-stu-id="1441c-120">Component</span></span>|<span data-ttu-id="1441c-121">Amount</span><span class="sxs-lookup"><span data-stu-id="1441c-121">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="1441c-122">**GST Base Amount**</span><span class="sxs-lookup"><span data-stu-id="1441c-122">**GST Base Amount**</span></span>|<span data-ttu-id="1441c-123">10,000</span><span class="sxs-lookup"><span data-stu-id="1441c-123">10,000</span></span>|  
    |<span data-ttu-id="1441c-124">**CGST**</span><span class="sxs-lookup"><span data-stu-id="1441c-124">**CGST**</span></span>|<span data-ttu-id="1441c-125">900</span><span class="sxs-lookup"><span data-stu-id="1441c-125">900</span></span>|  
    |<span data-ttu-id="1441c-126">**SGST**</span><span class="sxs-lookup"><span data-stu-id="1441c-126">**SGST**</span></span>|<span data-ttu-id="1441c-127">900</span><span class="sxs-lookup"><span data-stu-id="1441c-127">900</span></span>|
    |<span data-ttu-id="1441c-128">**IGST**</span><span class="sxs-lookup"><span data-stu-id="1441c-128">**IGST**</span></span>|<span data-ttu-id="1441c-129">1800</span><span class="sxs-lookup"><span data-stu-id="1441c-129">1800</span></span>|

- <span data-ttu-id="1441c-130">GL Entries for Intra-State or Intra-Union Territory purchase of goods from registered vendor where input tax credit is available, will be as following:</span><span class="sxs-lookup"><span data-stu-id="1441c-130">GL Entries for Intra-State or Intra-Union Territory purchase of goods from registered vendor where input tax credit is available, will be as following:</span></span>
    
    |<span data-ttu-id="1441c-131">Particulars</span><span class="sxs-lookup"><span data-stu-id="1441c-131">Particulars</span></span>|<span data-ttu-id="1441c-132">Amount</span><span class="sxs-lookup"><span data-stu-id="1441c-132">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="1441c-133">**Purchase Account**</span><span class="sxs-lookup"><span data-stu-id="1441c-133">**Purchase Account**</span></span>|<span data-ttu-id="1441c-134">10,000</span><span class="sxs-lookup"><span data-stu-id="1441c-134">10,000</span></span>|  
    |<span data-ttu-id="1441c-135">**SGST/UTGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="1441c-135">**SGST/UTGST Receivable Account**</span></span>|<span data-ttu-id="1441c-136">900</span><span class="sxs-lookup"><span data-stu-id="1441c-136">900</span></span>|  
    |<span data-ttu-id="1441c-137">**CGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="1441c-137">**CGST Receivable Account**</span></span>|<span data-ttu-id="1441c-138">900</span><span class="sxs-lookup"><span data-stu-id="1441c-138">900</span></span>|
    |<span data-ttu-id="1441c-139">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="1441c-139">**Vendor Account**</span></span>|<span data-ttu-id="1441c-140">-11800</span><span class="sxs-lookup"><span data-stu-id="1441c-140">-11800</span></span>|

- <span data-ttu-id="1441c-141">GL Entries for Intra-State or Intra-Union Territory purchase of goods from registered vendor where input tax credit is not available, will be as following:</span><span class="sxs-lookup"><span data-stu-id="1441c-141">GL Entries for Intra-State or Intra-Union Territory purchase of goods from registered vendor where input tax credit is not available, will be as following:</span></span>
    
    |<span data-ttu-id="1441c-142">Particulars</span><span class="sxs-lookup"><span data-stu-id="1441c-142">Particulars</span></span>|<span data-ttu-id="1441c-143">Amount</span><span class="sxs-lookup"><span data-stu-id="1441c-143">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="1441c-144">**Purchase Account**</span><span class="sxs-lookup"><span data-stu-id="1441c-144">**Purchase Account**</span></span>|<span data-ttu-id="1441c-145">11,800</span><span class="sxs-lookup"><span data-stu-id="1441c-145">11,800</span></span>|  
    |<span data-ttu-id="1441c-146">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="1441c-146">**Vendor Account**</span></span>|<span data-ttu-id="1441c-147">-11800</span><span class="sxs-lookup"><span data-stu-id="1441c-147">-11800</span></span>|

- <span data-ttu-id="1441c-148">GL Entries for Intra-State or Intra-Union Territory purchase of services from registered vendor where input tax credit is available, will be as following:</span><span class="sxs-lookup"><span data-stu-id="1441c-148">GL Entries for Intra-State or Intra-Union Territory purchase of services from registered vendor where input tax credit is available, will be as following:</span></span>

    |<span data-ttu-id="1441c-149">Particulars</span><span class="sxs-lookup"><span data-stu-id="1441c-149">Particulars</span></span>|<span data-ttu-id="1441c-150">Amount</span><span class="sxs-lookup"><span data-stu-id="1441c-150">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="1441c-151">**Services Account**</span><span class="sxs-lookup"><span data-stu-id="1441c-151">**Services Account**</span></span>|<span data-ttu-id="1441c-152">10,000</span><span class="sxs-lookup"><span data-stu-id="1441c-152">10,000</span></span>|  
    |<span data-ttu-id="1441c-153">**SGST/UTGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="1441c-153">**SGST/UTGST Receivable Account**</span></span>|<span data-ttu-id="1441c-154">900</span><span class="sxs-lookup"><span data-stu-id="1441c-154">900</span></span>|  
    |<span data-ttu-id="1441c-155">**CGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="1441c-155">**CGST Receivable Account**</span></span>|<span data-ttu-id="1441c-156">900</span><span class="sxs-lookup"><span data-stu-id="1441c-156">900</span></span>| 
    |<span data-ttu-id="1441c-157">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="1441c-157">**Vendor Account**</span></span>|<span data-ttu-id="1441c-158">-11800</span><span class="sxs-lookup"><span data-stu-id="1441c-158">-11800</span></span>|

- <span data-ttu-id="1441c-159">GL Entries for Intra-State or Intra-Union Territory purchase of services from registered vendor where input tax credit is not available, will be as following:</span><span class="sxs-lookup"><span data-stu-id="1441c-159">GL Entries for Intra-State or Intra-Union Territory purchase of services from registered vendor where input tax credit is not available, will be as following:</span></span>

    |<span data-ttu-id="1441c-160">Particulars</span><span class="sxs-lookup"><span data-stu-id="1441c-160">Particulars</span></span>|<span data-ttu-id="1441c-161">Amount</span><span class="sxs-lookup"><span data-stu-id="1441c-161">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="1441c-162">**Services Account**</span><span class="sxs-lookup"><span data-stu-id="1441c-162">**Services Account**</span></span>|<span data-ttu-id="1441c-163">11,800</span><span class="sxs-lookup"><span data-stu-id="1441c-163">11,800</span></span>|  
    |<span data-ttu-id="1441c-164">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="1441c-164">**Vendor Account**</span></span>|<span data-ttu-id="1441c-165">-11800</span><span class="sxs-lookup"><span data-stu-id="1441c-165">-11800</span></span>|

- <span data-ttu-id="1441c-166">GL Entries for Inter-State purchase of goods from registered vendor where input tax credit is available, will be as following:</span><span class="sxs-lookup"><span data-stu-id="1441c-166">GL Entries for Inter-State purchase of goods from registered vendor where input tax credit is available, will be as following:</span></span>
    
    |<span data-ttu-id="1441c-167">Particulars</span><span class="sxs-lookup"><span data-stu-id="1441c-167">Particulars</span></span>|<span data-ttu-id="1441c-168">Amount</span><span class="sxs-lookup"><span data-stu-id="1441c-168">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="1441c-169">**Purchase Account**</span><span class="sxs-lookup"><span data-stu-id="1441c-169">**Purchase Account**</span></span>|<span data-ttu-id="1441c-170">10,000</span><span class="sxs-lookup"><span data-stu-id="1441c-170">10,000</span></span>|  
    |<span data-ttu-id="1441c-171">**IGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="1441c-171">**IGST Receivable Account**</span></span>|<span data-ttu-id="1441c-172">1800</span><span class="sxs-lookup"><span data-stu-id="1441c-172">1800</span></span>| 
    |<span data-ttu-id="1441c-173">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="1441c-173">**Vendor Account**</span></span>|<span data-ttu-id="1441c-174">-11800</span><span class="sxs-lookup"><span data-stu-id="1441c-174">-11800</span></span>|

- <span data-ttu-id="1441c-175">GL Entries for Inter-State purchase of goods from registered vendor where input tax credit is not available, will be as following:</span><span class="sxs-lookup"><span data-stu-id="1441c-175">GL Entries for Inter-State purchase of goods from registered vendor where input tax credit is not available, will be as following:</span></span>
    
    |<span data-ttu-id="1441c-176">Particular</span><span class="sxs-lookup"><span data-stu-id="1441c-176">Particular</span></span>|<span data-ttu-id="1441c-177">Amount</span><span class="sxs-lookup"><span data-stu-id="1441c-177">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="1441c-178">**Purchase Account**</span><span class="sxs-lookup"><span data-stu-id="1441c-178">**Purchase Account**</span></span>|<span data-ttu-id="1441c-179">11800</span><span class="sxs-lookup"><span data-stu-id="1441c-179">11800</span></span>|  
    |<span data-ttu-id="1441c-180">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="1441c-180">**Vendor Account**</span></span>|<span data-ttu-id="1441c-181">-11800</span><span class="sxs-lookup"><span data-stu-id="1441c-181">-11800</span></span>|

- <span data-ttu-id="1441c-182">GL Entries for Inter-State purchase of services from registered vendor where input tax credit is available, will be as following:</span><span class="sxs-lookup"><span data-stu-id="1441c-182">GL Entries for Inter-State purchase of services from registered vendor where input tax credit is available, will be as following:</span></span>
    
    |<span data-ttu-id="1441c-183">Particulars</span><span class="sxs-lookup"><span data-stu-id="1441c-183">Particulars</span></span>|<span data-ttu-id="1441c-184">Amount</span><span class="sxs-lookup"><span data-stu-id="1441c-184">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="1441c-185">**Services Account**</span><span class="sxs-lookup"><span data-stu-id="1441c-185">**Services Account**</span></span>|<span data-ttu-id="1441c-186">10,000</span><span class="sxs-lookup"><span data-stu-id="1441c-186">10,000</span></span>|  
    |<span data-ttu-id="1441c-187">**IGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="1441c-187">**IGST Receivable Account**</span></span>|<span data-ttu-id="1441c-188">1800</span><span class="sxs-lookup"><span data-stu-id="1441c-188">1800</span></span>|
    |<span data-ttu-id="1441c-189">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="1441c-189">**Vendor Account**</span></span>|<span data-ttu-id="1441c-190">-11800</span><span class="sxs-lookup"><span data-stu-id="1441c-190">-11800</span></span>|

- <span data-ttu-id="1441c-191">GL Entries for Inter-State purchase of services from registered vendor where input tax credit is not available, will be as following:</span><span class="sxs-lookup"><span data-stu-id="1441c-191">GL Entries for Inter-State purchase of services from registered vendor where input tax credit is not available, will be as following:</span></span>
    
    |<span data-ttu-id="1441c-192">Particulars</span><span class="sxs-lookup"><span data-stu-id="1441c-192">Particulars</span></span>|<span data-ttu-id="1441c-193">Amount</span><span class="sxs-lookup"><span data-stu-id="1441c-193">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="1441c-194">**Services Account**</span><span class="sxs-lookup"><span data-stu-id="1441c-194">**Services Account**</span></span>|<span data-ttu-id="1441c-195">11800</span><span class="sxs-lookup"><span data-stu-id="1441c-195">11800</span></span>|  
    |<span data-ttu-id="1441c-196">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="1441c-196">**Vendor Account**</span></span>|<span data-ttu-id="1441c-197">-11800</span><span class="sxs-lookup"><span data-stu-id="1441c-197">-11800</span></span>|

- <span data-ttu-id="1441c-198">GL Entries for the Intra-State purchase from registered vendor (reverse charge), will be as following:</span><span class="sxs-lookup"><span data-stu-id="1441c-198">GL Entries for the Intra-State purchase from registered vendor (reverse charge), will be as following:</span></span>
    
    |<span data-ttu-id="1441c-199">Particulars</span><span class="sxs-lookup"><span data-stu-id="1441c-199">Particulars</span></span>|<span data-ttu-id="1441c-200">Amount</span><span class="sxs-lookup"><span data-stu-id="1441c-200">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="1441c-201">**Purchase or Services Account**</span><span class="sxs-lookup"><span data-stu-id="1441c-201">**Purchase or Services Account**</span></span>|<span data-ttu-id="1441c-202">10000</span><span class="sxs-lookup"><span data-stu-id="1441c-202">10000</span></span>|  
    |<span data-ttu-id="1441c-203">**CGST Receivable Account (Interim)**</span><span class="sxs-lookup"><span data-stu-id="1441c-203">**CGST Receivable Account (Interim)**</span></span>|<span data-ttu-id="1441c-204">900</span><span class="sxs-lookup"><span data-stu-id="1441c-204">900</span></span>|
    |<span data-ttu-id="1441c-205">**SGST Receivable Account (Interim)**</span><span class="sxs-lookup"><span data-stu-id="1441c-205">**SGST Receivable Account (Interim)**</span></span>|<span data-ttu-id="1441c-206">900</span><span class="sxs-lookup"><span data-stu-id="1441c-206">900</span></span>|
    |<span data-ttu-id="1441c-207">**CGST Payable Account (Interim)**</span><span class="sxs-lookup"><span data-stu-id="1441c-207">**CGST Payable Account (Interim)**</span></span>|<span data-ttu-id="1441c-208">-900</span><span class="sxs-lookup"><span data-stu-id="1441c-208">-900</span></span>|
    |<span data-ttu-id="1441c-209">**SGST Payable Account (Interim)**</span><span class="sxs-lookup"><span data-stu-id="1441c-209">**SGST Payable Account (Interim)**</span></span>|<span data-ttu-id="1441c-210">-900</span><span class="sxs-lookup"><span data-stu-id="1441c-210">-900</span></span>|
    |<span data-ttu-id="1441c-211">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="1441c-211">**Vendor Account**</span></span>|<span data-ttu-id="1441c-212">-10000</span><span class="sxs-lookup"><span data-stu-id="1441c-212">-10000</span></span>|

- <span data-ttu-id="1441c-213">GL Entries for the Inter-State purchase from registered vendor (reverse charge) if time of supply is considered on the basis of payment, will be as following:</span><span class="sxs-lookup"><span data-stu-id="1441c-213">GL Entries for the Inter-State purchase from registered vendor (reverse charge) if time of supply is considered on the basis of payment, will be as following:</span></span>
    
    |<span data-ttu-id="1441c-214">Particulars</span><span class="sxs-lookup"><span data-stu-id="1441c-214">Particulars</span></span>|<span data-ttu-id="1441c-215">Amount</span><span class="sxs-lookup"><span data-stu-id="1441c-215">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="1441c-216">**Purchase or Services Account**</span><span class="sxs-lookup"><span data-stu-id="1441c-216">**Purchase or Services Account**</span></span>|<span data-ttu-id="1441c-217">10000</span><span class="sxs-lookup"><span data-stu-id="1441c-217">10000</span></span>|  
    |<span data-ttu-id="1441c-218">**IGST Receivable Account (Interim)**</span><span class="sxs-lookup"><span data-stu-id="1441c-218">**IGST Receivable Account (Interim)**</span></span>|<span data-ttu-id="1441c-219">1800</span><span class="sxs-lookup"><span data-stu-id="1441c-219">1800</span></span>|
    |<span data-ttu-id="1441c-220">**IGST Payable Account (Interim)**</span><span class="sxs-lookup"><span data-stu-id="1441c-220">**IGST Payable Account (Interim)**</span></span>|<span data-ttu-id="1441c-221">-1800</span><span class="sxs-lookup"><span data-stu-id="1441c-221">-1800</span></span>|
    |<span data-ttu-id="1441c-222">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="1441c-222">**Vendor Account**</span></span>|<span data-ttu-id="1441c-223">-10000</span><span class="sxs-lookup"><span data-stu-id="1441c-223">-10000</span></span>|

- <span data-ttu-id="1441c-224">GL Entries on payment to registered vendor (reverse charge) against Intra-State purchase invoice, will be as following:</span><span class="sxs-lookup"><span data-stu-id="1441c-224">GL Entries on payment to registered vendor (reverse charge) against Intra-State purchase invoice, will be as following:</span></span>
    
    |<span data-ttu-id="1441c-225">Particulars</span><span class="sxs-lookup"><span data-stu-id="1441c-225">Particulars</span></span>|<span data-ttu-id="1441c-226">Amount</span><span class="sxs-lookup"><span data-stu-id="1441c-226">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="1441c-227">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="1441c-227">**Vendor Account**</span></span>|<span data-ttu-id="1441c-228">10000</span><span class="sxs-lookup"><span data-stu-id="1441c-228">10000</span></span>|
    |<span data-ttu-id="1441c-229">**CGST Payable Account (Interim)**</span><span class="sxs-lookup"><span data-stu-id="1441c-229">**CGST Payable Account (Interim)**</span></span>|<span data-ttu-id="1441c-230">900</span><span class="sxs-lookup"><span data-stu-id="1441c-230">900</span></span>|
    |<span data-ttu-id="1441c-231">**SGST Payable Account (Interim)**</span><span class="sxs-lookup"><span data-stu-id="1441c-231">**SGST Payable Account (Interim)**</span></span>|<span data-ttu-id="1441c-232">900</span><span class="sxs-lookup"><span data-stu-id="1441c-232">900</span></span>|
    |<span data-ttu-id="1441c-233">**CGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="1441c-233">**CGST Payable Account**</span></span>|<span data-ttu-id="1441c-234">-900</span><span class="sxs-lookup"><span data-stu-id="1441c-234">-900</span></span>|
    |<span data-ttu-id="1441c-235">**SGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="1441c-235">**SGST Payable Account**</span></span>|<span data-ttu-id="1441c-236">-900</span><span class="sxs-lookup"><span data-stu-id="1441c-236">-900</span></span>|
    |<span data-ttu-id="1441c-237">**Bank Account**</span><span class="sxs-lookup"><span data-stu-id="1441c-237">**Bank Account**</span></span>|<span data-ttu-id="1441c-238">-10000</span><span class="sxs-lookup"><span data-stu-id="1441c-238">-10000</span></span>|  

- <span data-ttu-id="1441c-239">GL Entries on payment to registered vendor (reverse charge) against Inter-State purchase invoice, will be as following:</span><span class="sxs-lookup"><span data-stu-id="1441c-239">GL Entries on payment to registered vendor (reverse charge) against Inter-State purchase invoice, will be as following:</span></span>
    
    |<span data-ttu-id="1441c-240">Particulars</span><span class="sxs-lookup"><span data-stu-id="1441c-240">Particulars</span></span>|<span data-ttu-id="1441c-241">Amount</span><span class="sxs-lookup"><span data-stu-id="1441c-241">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="1441c-242">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="1441c-242">**Vendor Account**</span></span>|<span data-ttu-id="1441c-243">10000</span><span class="sxs-lookup"><span data-stu-id="1441c-243">10000</span></span>|
    |<span data-ttu-id="1441c-244">**IGST Payable Account (Interim)**</span><span class="sxs-lookup"><span data-stu-id="1441c-244">**IGST Payable Account (Interim)**</span></span>|<span data-ttu-id="1441c-245">1800</span><span class="sxs-lookup"><span data-stu-id="1441c-245">1800</span></span>|
    |<span data-ttu-id="1441c-246">**IGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="1441c-246">**IGST Payable Account**</span></span>|<span data-ttu-id="1441c-247">-1800</span><span class="sxs-lookup"><span data-stu-id="1441c-247">-1800</span></span>|
    |<span data-ttu-id="1441c-248">**Bank Account**</span><span class="sxs-lookup"><span data-stu-id="1441c-248">**Bank Account**</span></span>|<span data-ttu-id="1441c-249">-10000</span><span class="sxs-lookup"><span data-stu-id="1441c-249">-10000</span></span>|


- <span data-ttu-id="1441c-250">GL Entries for Intra-State or Intra-Union Territory purchase of fixed asset from registered vendor where input tax credit is available, will be as following:</span><span class="sxs-lookup"><span data-stu-id="1441c-250">GL Entries for Intra-State or Intra-Union Territory purchase of fixed asset from registered vendor where input tax credit is available, will be as following:</span></span>
    
    |<span data-ttu-id="1441c-251">Particulars</span><span class="sxs-lookup"><span data-stu-id="1441c-251">Particulars</span></span>|<span data-ttu-id="1441c-252">Amount</span><span class="sxs-lookup"><span data-stu-id="1441c-252">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="1441c-253">**Fixed Asset Increases during the Year**</span><span class="sxs-lookup"><span data-stu-id="1441c-253">**Fixed Asset Increases during the Year**</span></span>|<span data-ttu-id="1441c-254">10000</span><span class="sxs-lookup"><span data-stu-id="1441c-254">10000</span></span>|
    |<span data-ttu-id="1441c-255">**SGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="1441c-255">**SGST Receivable Account**</span></span>|<span data-ttu-id="1441c-256">900</span><span class="sxs-lookup"><span data-stu-id="1441c-256">900</span></span>|
    |<span data-ttu-id="1441c-257">**CGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="1441c-257">**CGST Receivable Account**</span></span>|<span data-ttu-id="1441c-258">900</span><span class="sxs-lookup"><span data-stu-id="1441c-258">900</span></span>|
    |<span data-ttu-id="1441c-259">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="1441c-259">**Vendor Account**</span></span>|<span data-ttu-id="1441c-260">-11800</span><span class="sxs-lookup"><span data-stu-id="1441c-260">-11800</span></span>|

- <span data-ttu-id="1441c-261">GL Entries for Intra-State or Intra-Union Territory purchase of fixed asset from registered vendor where input tax credit is not available, will be as following:</span><span class="sxs-lookup"><span data-stu-id="1441c-261">GL Entries for Intra-State or Intra-Union Territory purchase of fixed asset from registered vendor where input tax credit is not available, will be as following:</span></span>
    
    |<span data-ttu-id="1441c-262">Particulars</span><span class="sxs-lookup"><span data-stu-id="1441c-262">Particulars</span></span>|<span data-ttu-id="1441c-263">Amount</span><span class="sxs-lookup"><span data-stu-id="1441c-263">Amount</span></span>|
    |----------------------------------|---------------------------------------|
    |<span data-ttu-id="1441c-264">**Fixed Asset Increases during the Year**</span><span class="sxs-lookup"><span data-stu-id="1441c-264">**Fixed Asset Increases during the Year**</span></span>|<span data-ttu-id="1441c-265">11800</span><span class="sxs-lookup"><span data-stu-id="1441c-265">11800</span></span>|
    |<span data-ttu-id="1441c-266">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="1441c-266">**Vendor Account**</span></span>|<span data-ttu-id="1441c-267">-11800</span><span class="sxs-lookup"><span data-stu-id="1441c-267">-11800</span></span>|

> [!TIP]
> <span data-ttu-id="1441c-268">In case of Inter-State purchase, IGST will be calculated.</span><span class="sxs-lookup"><span data-stu-id="1441c-268">In case of Inter-State purchase, IGST will be calculated.</span></span>

- <span data-ttu-id="1441c-269">GL Entries for Charge Item in case of Intra-State or Intra-Union Territory in purchase transaction from registered vendor where input tax credit is available, will be as following:</span><span class="sxs-lookup"><span data-stu-id="1441c-269">GL Entries for Charge Item in case of Intra-State or Intra-Union Territory in purchase transaction from registered vendor where input tax credit is available, will be as following:</span></span>
    
    |<span data-ttu-id="1441c-270">Particulars</span><span class="sxs-lookup"><span data-stu-id="1441c-270">Particulars</span></span>|<span data-ttu-id="1441c-271">Amount</span><span class="sxs-lookup"><span data-stu-id="1441c-271">Amount</span></span>|
    |----------------------------------|---------------------------------------|
    |<span data-ttu-id="1441c-272">**Purchase Account**</span><span class="sxs-lookup"><span data-stu-id="1441c-272">**Purchase Account**</span></span>|<span data-ttu-id="1441c-273">10000</span><span class="sxs-lookup"><span data-stu-id="1441c-273">10000</span></span>|
    |<span data-ttu-id="1441c-274">**SGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="1441c-274">**SGST Receivable Account**</span></span>|<span data-ttu-id="1441c-275">900</span><span class="sxs-lookup"><span data-stu-id="1441c-275">900</span></span>|
    |<span data-ttu-id="1441c-276">**CGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="1441c-276">**CGST Receivable Account**</span></span>|<span data-ttu-id="1441c-277">900</span><span class="sxs-lookup"><span data-stu-id="1441c-277">900</span></span>|
    |<span data-ttu-id="1441c-278">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="1441c-278">**Vendor Account**</span></span>|<span data-ttu-id="1441c-279">-11800</span><span class="sxs-lookup"><span data-stu-id="1441c-279">-11800</span></span>|

- <span data-ttu-id="1441c-280">GL Entries for Charge Item in case of Intra-State or Intra-Union Territory in purchase transaction from registered vendor where input tax credit is not available, will be as following:</span><span class="sxs-lookup"><span data-stu-id="1441c-280">GL Entries for Charge Item in case of Intra-State or Intra-Union Territory in purchase transaction from registered vendor where input tax credit is not available, will be as following:</span></span>
    
    |<span data-ttu-id="1441c-281">Particulars</span><span class="sxs-lookup"><span data-stu-id="1441c-281">Particulars</span></span>|<span data-ttu-id="1441c-282">Amount</span><span class="sxs-lookup"><span data-stu-id="1441c-282">Amount</span></span>|
    |----------------------------------|---------------------------------------|
    |<span data-ttu-id="1441c-283">**Purchase Account**</span><span class="sxs-lookup"><span data-stu-id="1441c-283">**Purchase Account**</span></span>|<span data-ttu-id="1441c-284">11800</span><span class="sxs-lookup"><span data-stu-id="1441c-284">11800</span></span>|
    |<span data-ttu-id="1441c-285">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="1441c-285">**Vendor Account**</span></span>|<span data-ttu-id="1441c-286">-11800</span><span class="sxs-lookup"><span data-stu-id="1441c-286">-11800</span></span>|

> [!TIP]
> <span data-ttu-id="1441c-287">In case of Inter-State purchase, IGST will be calculated.</span><span class="sxs-lookup"><span data-stu-id="1441c-287">In case of Inter-State purchase, IGST will be calculated.</span></span>






































