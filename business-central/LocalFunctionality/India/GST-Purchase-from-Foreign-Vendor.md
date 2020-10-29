---
title: Import from Foreign Vendor
description: Import from Foreign Vendor
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 8b4246888d01f6c74bfbc68a07011d9c6411e983
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948641"
---
# <a name="import-from-foreign-vendor"></a><span data-ttu-id="1a29b-103">Import from Foreign Vendor</span><span class="sxs-lookup"><span data-stu-id="1a29b-103">Import from Foreign Vendor</span></span>

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="1a29b-104">Purchasing goods in India from a place outside India is import of goods.</span><span class="sxs-lookup"><span data-stu-id="1a29b-104">Purchasing goods in India from a place outside India is import of goods.</span></span> <span data-ttu-id="1a29b-105">For services, if the supplier is located outside India, the recipient is located in India and the place of supply is in India, then it is called Import of services.</span><span class="sxs-lookup"><span data-stu-id="1a29b-105">For services, if the supplier is located outside India, the recipient is located in India and the place of supply is in India, then it is called Import of services.</span></span> <span data-ttu-id="1a29b-106">Purchase of goods and/or services from a foreign vendor is subject to reverse charge i.e. the person importing goods or services has to remit tax to the government.</span><span class="sxs-lookup"><span data-stu-id="1a29b-106">Purchase of goods and/or services from a foreign vendor is subject to reverse charge i.e. the person importing goods or services has to remit tax to the government.</span></span> 

<span data-ttu-id="1a29b-107">Process for purchase from a foreign vendor has been explained in this document.</span><span class="sxs-lookup"><span data-stu-id="1a29b-107">Process for purchase from a foreign vendor has been explained in this document.</span></span>

## <a name="create-a-purchase-invoice"></a><span data-ttu-id="1a29b-108">Create a purchase invoice</span><span class="sxs-lookup"><span data-stu-id="1a29b-108">Create a purchase invoice</span></span>

1. <span data-ttu-id="1a29b-109">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Purchase Invoice** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="1a29b-109">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Purchase Invoice** , and then choose the related link.</span></span>
2. <span data-ttu-id="1a29b-110">Select **Vendor** on **Purchase Invoice** header, GST vendor type should be **Import** .</span><span class="sxs-lookup"><span data-stu-id="1a29b-110">Select **Vendor** on **Purchase Invoice** header, GST vendor type should be **Import** .</span></span>
3. <span data-ttu-id="1a29b-111">Select **Item Code** for goods, **G/L Account** for Service purchase and **Fixed Asset** for Fixed Asset purchase on **Purchase Invoice** line.</span><span class="sxs-lookup"><span data-stu-id="1a29b-111">Select **Item Code** for goods, **G/L Account** for Service purchase and **Fixed Asset** for Fixed Asset purchase on **Purchase Invoice** line.</span></span> <span data-ttu-id="1a29b-112">GST Group Code, HSN/SAC Code and GST Credit value should be selected as **Availment** if the tax input credit is available or else **Non-Availment** on the Item or G/L Account.</span><span class="sxs-lookup"><span data-stu-id="1a29b-112">GST Group Code, HSN/SAC Code and GST Credit value should be selected as **Availment** if the tax input credit is available or else **Non-Availment** on the Item or G/L Account.</span></span>
4. <span data-ttu-id="1a29b-113">GST Credit option can be changed in document line.</span><span class="sxs-lookup"><span data-stu-id="1a29b-113">GST Credit option can be changed in document line.</span></span>

- <span data-ttu-id="1a29b-114">In case of import of goods from foreign vendor, IGST is to be calculated on GST Assessable Value + Basic Custom Duty.</span><span class="sxs-lookup"><span data-stu-id="1a29b-114">In case of import of goods from foreign vendor, IGST is to be calculated on GST Assessable Value + Basic Custom Duty.</span></span> 

<span data-ttu-id="1a29b-115">For example, purchase invoice is issued INR 10000, Custom Duty is INR 1000.</span><span class="sxs-lookup"><span data-stu-id="1a29b-115">For example, purchase invoice is issued INR 10000, Custom Duty is INR 1000.</span></span> <span data-ttu-id="1a29b-116">Therefore, on GST Assessable Value INR 11000,(IGST @18%) has to be charged.</span><span class="sxs-lookup"><span data-stu-id="1a29b-116">Therefore, on GST Assessable Value INR 11000,(IGST @18%) has to be charged.</span></span> <span data-ttu-id="1a29b-117">Calculation base: (18% on 11,000 GST Assessable Value + 1,000 BCD) (12,000\*18%).</span><span class="sxs-lookup"><span data-stu-id="1a29b-117">Calculation base: (18% on 11,000 GST Assessable Value + 1,000 BCD) (12,000\*18%).</span></span>

  - <span data-ttu-id="1a29b-118">GST calculation will appear in the Fact Box, as following:</span><span class="sxs-lookup"><span data-stu-id="1a29b-118">GST calculation will appear in the Fact Box, as following:</span></span>
    
      |<span data-ttu-id="1a29b-119">Component</span><span class="sxs-lookup"><span data-stu-id="1a29b-119">Component</span></span>|<span data-ttu-id="1a29b-120">Amount</span><span class="sxs-lookup"><span data-stu-id="1a29b-120">Amount</span></span>|
      |----------------------------------|---------------------------------------|  
      |<span data-ttu-id="1a29b-121">**Transaction Value**</span><span class="sxs-lookup"><span data-stu-id="1a29b-121">**Transaction Value**</span></span>|<span data-ttu-id="1a29b-122">10000</span><span class="sxs-lookup"><span data-stu-id="1a29b-122">10000</span></span>|
      |<span data-ttu-id="1a29b-123">**GST Base Amount**</span><span class="sxs-lookup"><span data-stu-id="1a29b-123">**GST Base Amount**</span></span>|<span data-ttu-id="1a29b-124">11,000</span><span class="sxs-lookup"><span data-stu-id="1a29b-124">11,000</span></span>|
      |<span data-ttu-id="1a29b-125">**Custom Duty (BCD)**</span><span class="sxs-lookup"><span data-stu-id="1a29b-125">**Custom Duty (BCD)**</span></span>|<span data-ttu-id="1a29b-126">1000</span><span class="sxs-lookup"><span data-stu-id="1a29b-126">1000</span></span>|  
      |<span data-ttu-id="1a29b-127">**IGST**</span><span class="sxs-lookup"><span data-stu-id="1a29b-127">**IGST**</span></span>|<span data-ttu-id="1a29b-128">2160 (18% on 11,000 GST Assessable Value + 1,000 BCD) (12,000\*18%)</span><span class="sxs-lookup"><span data-stu-id="1a29b-128">2160 (18% on 11,000 GST Assessable Value + 1,000 BCD) (12,000\*18%)</span></span>|  


  - <span data-ttu-id="1a29b-129">GL Entries for import of goods from foreign vendor where input tax credit is available, will be as following:</span><span class="sxs-lookup"><span data-stu-id="1a29b-129">GL Entries for import of goods from foreign vendor where input tax credit is available, will be as following:</span></span>
    
      |<span data-ttu-id="1a29b-130">Particulars</span><span class="sxs-lookup"><span data-stu-id="1a29b-130">Particulars</span></span>|<span data-ttu-id="1a29b-131">Amount</span><span class="sxs-lookup"><span data-stu-id="1a29b-131">Amount</span></span>|
      |----------------------------------|---------------------------------------|  
      |<span data-ttu-id="1a29b-132">**Purchase Account (Transactional Value+ BCD)**</span><span class="sxs-lookup"><span data-stu-id="1a29b-132">**Purchase Account (Transactional Value+ BCD)**</span></span>|<span data-ttu-id="1a29b-133">11000</span><span class="sxs-lookup"><span data-stu-id="1a29b-133">11000</span></span>|  
      |<span data-ttu-id="1a29b-134">**IGST Receivable Account (GST on GST Assessable Value + BCD)**</span><span class="sxs-lookup"><span data-stu-id="1a29b-134">**IGST Receivable Account (GST on GST Assessable Value + BCD)**</span></span>|<span data-ttu-id="1a29b-135">2160</span><span class="sxs-lookup"><span data-stu-id="1a29b-135">2160</span></span>| 
      |<span data-ttu-id="1a29b-136">**Customs House Account (GST Amount + BCD)**</span><span class="sxs-lookup"><span data-stu-id="1a29b-136">**Customs House Account (GST Amount + BCD)**</span></span>|<span data-ttu-id="1a29b-137">-3160</span><span class="sxs-lookup"><span data-stu-id="1a29b-137">-3160</span></span>|
      |<span data-ttu-id="1a29b-138">**Vendor Account (Transaction Value)**</span><span class="sxs-lookup"><span data-stu-id="1a29b-138">**Vendor Account (Transaction Value)**</span></span>|<span data-ttu-id="1a29b-139">-10000</span><span class="sxs-lookup"><span data-stu-id="1a29b-139">-10000</span></span>|

  - <span data-ttu-id="1a29b-140">GL Entries for import of goods from foreign vendor where input tax credit is not available, will be as following:</span><span class="sxs-lookup"><span data-stu-id="1a29b-140">GL Entries for import of goods from foreign vendor where input tax credit is not available, will be as following:</span></span>
    
      |<span data-ttu-id="1a29b-141">Particulars</span><span class="sxs-lookup"><span data-stu-id="1a29b-141">Particulars</span></span>|<span data-ttu-id="1a29b-142">Amount</span><span class="sxs-lookup"><span data-stu-id="1a29b-142">Amount</span></span>|
      |----------------------------------|---------------------------------------|  
      |<span data-ttu-id="1a29b-143">**Purchase Account (Transactional Value+ BCD + IGST Amount)**</span><span class="sxs-lookup"><span data-stu-id="1a29b-143">**Purchase Account (Transactional Value+ BCD + IGST Amount)**</span></span>|<span data-ttu-id="1a29b-144">13160</span><span class="sxs-lookup"><span data-stu-id="1a29b-144">13160</span></span>|  
      |<span data-ttu-id="1a29b-145">**Customs House Account (GST Amount + BCD)**</span><span class="sxs-lookup"><span data-stu-id="1a29b-145">**Customs House Account (GST Amount + BCD)**</span></span>|<span data-ttu-id="1a29b-146">-3160</span><span class="sxs-lookup"><span data-stu-id="1a29b-146">-3160</span></span>|
      |<span data-ttu-id="1a29b-147">**Vendor Account (Transaction Value)**</span><span class="sxs-lookup"><span data-stu-id="1a29b-147">**Vendor Account (Transaction Value)**</span></span>|<span data-ttu-id="1a29b-148">-10000</span><span class="sxs-lookup"><span data-stu-id="1a29b-148">-10000</span></span>|


- <span data-ttu-id="1a29b-149">Import of Fixed Asset from foreign vendor, IGST is to be calculated on GST Assessable Value + Basic Custom Duty.</span><span class="sxs-lookup"><span data-stu-id="1a29b-149">Import of Fixed Asset from foreign vendor, IGST is to be calculated on GST Assessable Value + Basic Custom Duty.</span></span> 

<span data-ttu-id="1a29b-150">For example, purchase invoice is issued for INR 10000, Custom Duty INR 1000, GST Assessable Value INR 11000,(IGST @18%) has to be charged.</span><span class="sxs-lookup"><span data-stu-id="1a29b-150">For example, purchase invoice is issued for INR 10000, Custom Duty INR 1000, GST Assessable Value INR 11000,(IGST @18%) has to be charged.</span></span> <span data-ttu-id="1a29b-151">Calculation base: (18% on 11,000 GST Assessable Value + 1,000 BCD) (12,000\*18%).</span><span class="sxs-lookup"><span data-stu-id="1a29b-151">Calculation base: (18% on 11,000 GST Assessable Value + 1,000 BCD) (12,000\*18%).</span></span>

  - <span data-ttu-id="1a29b-152">GST Calculation will appear in the Fact Box, as following:</span><span class="sxs-lookup"><span data-stu-id="1a29b-152">GST Calculation will appear in the Fact Box, as following:</span></span>
    
      |<span data-ttu-id="1a29b-153">Component</span><span class="sxs-lookup"><span data-stu-id="1a29b-153">Component</span></span>|<span data-ttu-id="1a29b-154">Amount</span><span class="sxs-lookup"><span data-stu-id="1a29b-154">Amount</span></span>|
      |----------------------------------|---------------------------------------|  
      |<span data-ttu-id="1a29b-155">**Transaction Value**</span><span class="sxs-lookup"><span data-stu-id="1a29b-155">**Transaction Value**</span></span>|<span data-ttu-id="1a29b-156">10000</span><span class="sxs-lookup"><span data-stu-id="1a29b-156">10000</span></span>|
      |<span data-ttu-id="1a29b-157">**GST Base Amount**</span><span class="sxs-lookup"><span data-stu-id="1a29b-157">**GST Base Amount**</span></span>|<span data-ttu-id="1a29b-158">11,000</span><span class="sxs-lookup"><span data-stu-id="1a29b-158">11,000</span></span>|
      |<span data-ttu-id="1a29b-159">**Custom Duty (BCD)**</span><span class="sxs-lookup"><span data-stu-id="1a29b-159">**Custom Duty (BCD)**</span></span>|<span data-ttu-id="1a29b-160">1000</span><span class="sxs-lookup"><span data-stu-id="1a29b-160">1000</span></span>|  
      |<span data-ttu-id="1a29b-161">**IGST**</span><span class="sxs-lookup"><span data-stu-id="1a29b-161">**IGST**</span></span>|<span data-ttu-id="1a29b-162">2160 (18% on 11,000 GST Assessable Value + 1,000 BCD) (12,000\*18%)</span><span class="sxs-lookup"><span data-stu-id="1a29b-162">2160 (18% on 11,000 GST Assessable Value + 1,000 BCD) (12,000\*18%)</span></span>|  

  - <span data-ttu-id="1a29b-163">GL Entries for import of goods from foreign vendor where input tax credit is available, will be as following:</span><span class="sxs-lookup"><span data-stu-id="1a29b-163">GL Entries for import of goods from foreign vendor where input tax credit is available, will be as following:</span></span>
    
      |<span data-ttu-id="1a29b-164">Particulars</span><span class="sxs-lookup"><span data-stu-id="1a29b-164">Particulars</span></span>|<span data-ttu-id="1a29b-165">Amount</span><span class="sxs-lookup"><span data-stu-id="1a29b-165">Amount</span></span>|
      |----------------------------------|---------------------------------------|  
      |<span data-ttu-id="1a29b-166">**Fixed Asset Increase During the Year Account (Transactional Value+ BCD)**</span><span class="sxs-lookup"><span data-stu-id="1a29b-166">**Fixed Asset Increase During the Year Account (Transactional Value+ BCD)**</span></span>|<span data-ttu-id="1a29b-167">11000</span><span class="sxs-lookup"><span data-stu-id="1a29b-167">11000</span></span>|  
      |<span data-ttu-id="1a29b-168">**IGST Receivable Account (GST on GST Assessable Value + BCD)**</span><span class="sxs-lookup"><span data-stu-id="1a29b-168">**IGST Receivable Account (GST on GST Assessable Value + BCD)**</span></span>|<span data-ttu-id="1a29b-169">2160</span><span class="sxs-lookup"><span data-stu-id="1a29b-169">2160</span></span>| 
      |<span data-ttu-id="1a29b-170">**Customs House Account (GST Amount + BCD)**</span><span class="sxs-lookup"><span data-stu-id="1a29b-170">**Customs House Account (GST Amount + BCD)**</span></span>|<span data-ttu-id="1a29b-171">-3160</span><span class="sxs-lookup"><span data-stu-id="1a29b-171">-3160</span></span>|
      |<span data-ttu-id="1a29b-172">**Vendor Account (Transaction Value)**</span><span class="sxs-lookup"><span data-stu-id="1a29b-172">**Vendor Account (Transaction Value)**</span></span>|<span data-ttu-id="1a29b-173">-10000</span><span class="sxs-lookup"><span data-stu-id="1a29b-173">-10000</span></span>|

  - <span data-ttu-id="1a29b-174">GL Entries for import of goods from foreign vendor where input tax credit is not available, will be as following:</span><span class="sxs-lookup"><span data-stu-id="1a29b-174">GL Entries for import of goods from foreign vendor where input tax credit is not available, will be as following:</span></span>
    
     |<span data-ttu-id="1a29b-175">Particulars</span><span class="sxs-lookup"><span data-stu-id="1a29b-175">Particulars</span></span>|<span data-ttu-id="1a29b-176">Amount</span><span class="sxs-lookup"><span data-stu-id="1a29b-176">Amount</span></span>|
     |----------------------------------|---------------------------------------|  
     |<span data-ttu-id="1a29b-177">**Fixed Asset Increase During the Year Account (Transactional Value+ BCD + IGST Amount)**</span><span class="sxs-lookup"><span data-stu-id="1a29b-177">**Fixed Asset Increase During the Year Account (Transactional Value+ BCD + IGST Amount)**</span></span>|<span data-ttu-id="1a29b-178">13160</span><span class="sxs-lookup"><span data-stu-id="1a29b-178">13160</span></span>|  
     |<span data-ttu-id="1a29b-179">**Customs House Account (GST Amount + BCD)**</span><span class="sxs-lookup"><span data-stu-id="1a29b-179">**Customs House Account (GST Amount + BCD)**</span></span>|<span data-ttu-id="1a29b-180">-3160</span><span class="sxs-lookup"><span data-stu-id="1a29b-180">-3160</span></span>|
     |<span data-ttu-id="1a29b-181">**Vendor Account (Transaction Value)**</span><span class="sxs-lookup"><span data-stu-id="1a29b-181">**Vendor Account (Transaction Value)**</span></span>|<span data-ttu-id="1a29b-182">-10000</span><span class="sxs-lookup"><span data-stu-id="1a29b-182">-10000</span></span>|


- <span data-ttu-id="1a29b-183">Import of services from foreign vendor.</span><span class="sxs-lookup"><span data-stu-id="1a29b-183">Import of services from foreign vendor.</span></span> 

<span data-ttu-id="1a29b-184">For example, purchase invoice is issued for INR 10000, (IGST @18%) has to be charged.</span><span class="sxs-lookup"><span data-stu-id="1a29b-184">For example, purchase invoice is issued for INR 10000, (IGST @18%) has to be charged.</span></span>

  - <span data-ttu-id="1a29b-185">GST Calculation will appear in the Fact Box, as following:</span><span class="sxs-lookup"><span data-stu-id="1a29b-185">GST Calculation will appear in the Fact Box, as following:</span></span>
    
     |<span data-ttu-id="1a29b-186">Component</span><span class="sxs-lookup"><span data-stu-id="1a29b-186">Component</span></span>|<span data-ttu-id="1a29b-187">Amount</span><span class="sxs-lookup"><span data-stu-id="1a29b-187">Amount</span></span>|
     |----------------------------------|---------------------------------------|  
     |<span data-ttu-id="1a29b-188">**GST Base Amount**</span><span class="sxs-lookup"><span data-stu-id="1a29b-188">**GST Base Amount**</span></span>|<span data-ttu-id="1a29b-189">10000</span><span class="sxs-lookup"><span data-stu-id="1a29b-189">10000</span></span>|
     |<span data-ttu-id="1a29b-190">**IGST**</span><span class="sxs-lookup"><span data-stu-id="1a29b-190">**IGST**</span></span>|<span data-ttu-id="1a29b-191">1800</span><span class="sxs-lookup"><span data-stu-id="1a29b-191">1800</span></span>|  

  - <span data-ttu-id="1a29b-192">GL Entries for import of services from foreign vendor where input tax credit is available, will be as following:</span><span class="sxs-lookup"><span data-stu-id="1a29b-192">GL Entries for import of services from foreign vendor where input tax credit is available, will be as following:</span></span>
    
     |<span data-ttu-id="1a29b-193">Particulars</span><span class="sxs-lookup"><span data-stu-id="1a29b-193">Particulars</span></span>|<span data-ttu-id="1a29b-194">Amount</span><span class="sxs-lookup"><span data-stu-id="1a29b-194">Amount</span></span>|
     |----------------------------------|---------------------------------------|  
     |<span data-ttu-id="1a29b-195">**Services Account**</span><span class="sxs-lookup"><span data-stu-id="1a29b-195">**Services Account**</span></span>|<span data-ttu-id="1a29b-196">10000</span><span class="sxs-lookup"><span data-stu-id="1a29b-196">10000</span></span>|  
     |<span data-ttu-id="1a29b-197">**IGST Receivable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="1a29b-197">**IGST Receivable (Interim) Account**</span></span>|<span data-ttu-id="1a29b-198">1800</span><span class="sxs-lookup"><span data-stu-id="1a29b-198">1800</span></span>|
     |<span data-ttu-id="1a29b-199">**IGST Payable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="1a29b-199">**IGST Payable (Interim) Account**</span></span>|<span data-ttu-id="1a29b-200">-1800</span><span class="sxs-lookup"><span data-stu-id="1a29b-200">-1800</span></span>|
     |<span data-ttu-id="1a29b-201">**Vendor Account (Transaction Value)**</span><span class="sxs-lookup"><span data-stu-id="1a29b-201">**Vendor Account (Transaction Value)**</span></span>|<span data-ttu-id="1a29b-202">-10000</span><span class="sxs-lookup"><span data-stu-id="1a29b-202">-10000</span></span>|

  - <span data-ttu-id="1a29b-203">GL Entries for import of services from foreign vendor where input tax credit is not available, will be as following:</span><span class="sxs-lookup"><span data-stu-id="1a29b-203">GL Entries for import of services from foreign vendor where input tax credit is not available, will be as following:</span></span>
    
      |<span data-ttu-id="1a29b-204">Particulars</span><span class="sxs-lookup"><span data-stu-id="1a29b-204">Particulars</span></span>|<span data-ttu-id="1a29b-205">Amount</span><span class="sxs-lookup"><span data-stu-id="1a29b-205">Amount</span></span>|
      |----------------------------------|---------------------------------------|  
      |<span data-ttu-id="1a29b-206">**Services Account**</span><span class="sxs-lookup"><span data-stu-id="1a29b-206">**Services Account**</span></span>|<span data-ttu-id="1a29b-207">11800</span><span class="sxs-lookup"><span data-stu-id="1a29b-207">11800</span></span>|  
      |<span data-ttu-id="1a29b-208">**IGST Payable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="1a29b-208">**IGST Payable (Interim) Account**</span></span>|<span data-ttu-id="1a29b-209">-1800</span><span class="sxs-lookup"><span data-stu-id="1a29b-209">-1800</span></span>|
      |<span data-ttu-id="1a29b-210">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="1a29b-210">**Vendor Account**</span></span>|<span data-ttu-id="1a29b-211">-10000</span><span class="sxs-lookup"><span data-stu-id="1a29b-211">-10000</span></span>|


- <span data-ttu-id="1a29b-212">Import of Services from Import Associate Vendor.</span><span class="sxs-lookup"><span data-stu-id="1a29b-212">Import of Services from Import Associate Vendor.</span></span> 

<span data-ttu-id="1a29b-213">For example, purchase invoice is issued for INR 10000, (IGST @18%) has to be charged.</span><span class="sxs-lookup"><span data-stu-id="1a29b-213">For example, purchase invoice is issued for INR 10000, (IGST @18%) has to be charged.</span></span>

  - <span data-ttu-id="1a29b-214">GST Calculation will appear in the Fact Box, as following:</span><span class="sxs-lookup"><span data-stu-id="1a29b-214">GST Calculation will appear in the Fact Box, as following:</span></span>
    
      |<span data-ttu-id="1a29b-215">Component</span><span class="sxs-lookup"><span data-stu-id="1a29b-215">Component</span></span>|<span data-ttu-id="1a29b-216">Amount</span><span class="sxs-lookup"><span data-stu-id="1a29b-216">Amount</span></span>|
      |----------------------------------|---------------------------------------|  
      |<span data-ttu-id="1a29b-217">**GST Base Amount**</span><span class="sxs-lookup"><span data-stu-id="1a29b-217">**GST Base Amount**</span></span>|<span data-ttu-id="1a29b-218">10000</span><span class="sxs-lookup"><span data-stu-id="1a29b-218">10000</span></span>|
      |<span data-ttu-id="1a29b-219">**IGST**</span><span class="sxs-lookup"><span data-stu-id="1a29b-219">**IGST**</span></span>|<span data-ttu-id="1a29b-220">1800</span><span class="sxs-lookup"><span data-stu-id="1a29b-220">1800</span></span>|

  - <span data-ttu-id="1a29b-221">GL Entries for import of services from import associate vendor where input tax credit is available,will be as following:</span><span class="sxs-lookup"><span data-stu-id="1a29b-221">GL Entries for import of services from import associate vendor where input tax credit is available,will be as following:</span></span>
    
      |<span data-ttu-id="1a29b-222">Particular</span><span class="sxs-lookup"><span data-stu-id="1a29b-222">Particular</span></span>|<span data-ttu-id="1a29b-223">Amount</span><span class="sxs-lookup"><span data-stu-id="1a29b-223">Amount</span></span>|
      |----------------------------------|---------------------------------------|  
      |<span data-ttu-id="1a29b-224">**Services Account**</span><span class="sxs-lookup"><span data-stu-id="1a29b-224">**Services Account**</span></span>|<span data-ttu-id="1a29b-225">10000</span><span class="sxs-lookup"><span data-stu-id="1a29b-225">10000</span></span>|  
      |<span data-ttu-id="1a29b-226">**IGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="1a29b-226">**IGST Receivable Account**</span></span>|<span data-ttu-id="1a29b-227">1800</span><span class="sxs-lookup"><span data-stu-id="1a29b-227">1800</span></span>|
      |<span data-ttu-id="1a29b-228">**IGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="1a29b-228">**IGST Payable Account**</span></span>|<span data-ttu-id="1a29b-229">-1800</span><span class="sxs-lookup"><span data-stu-id="1a29b-229">-1800</span></span>|
      |<span data-ttu-id="1a29b-230">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="1a29b-230">**Vendor Account**</span></span>|<span data-ttu-id="1a29b-231">-10000</span><span class="sxs-lookup"><span data-stu-id="1a29b-231">-10000</span></span>|

  - <span data-ttu-id="1a29b-232">GL Entries for import of services from import associate vendor where input tax credit is not available, will be as following :</span><span class="sxs-lookup"><span data-stu-id="1a29b-232">GL Entries for import of services from import associate vendor where input tax credit is not available, will be as following :</span></span>
    
      |<span data-ttu-id="1a29b-233">Particular</span><span class="sxs-lookup"><span data-stu-id="1a29b-233">Particular</span></span>|<span data-ttu-id="1a29b-234">Amount</span><span class="sxs-lookup"><span data-stu-id="1a29b-234">Amount</span></span>|
      |----------------------------------|---------------------------------------|  
      |<span data-ttu-id="1a29b-235">**Services Account**</span><span class="sxs-lookup"><span data-stu-id="1a29b-235">**Services Account**</span></span>|<span data-ttu-id="1a29b-236">11800</span><span class="sxs-lookup"><span data-stu-id="1a29b-236">11800</span></span>|  
      |<span data-ttu-id="1a29b-237">**IGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="1a29b-237">**IGST Payable Account**</span></span>|<span data-ttu-id="1a29b-238">-1800</span><span class="sxs-lookup"><span data-stu-id="1a29b-238">-1800</span></span>|
      |<span data-ttu-id="1a29b-239">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="1a29b-239">**Vendor Account**</span></span>|<span data-ttu-id="1a29b-240">-10000</span><span class="sxs-lookup"><span data-stu-id="1a29b-240">-10000</span></span>|

> [!NOTE]
>
> <span data-ttu-id="1a29b-241">Import Transaction should be in Foreign Currency.</span><span class="sxs-lookup"><span data-stu-id="1a29b-241">Import Transaction should be in Foreign Currency.</span></span>