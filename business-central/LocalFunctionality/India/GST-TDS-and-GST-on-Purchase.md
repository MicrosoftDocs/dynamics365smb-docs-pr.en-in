---
title: Calculation of Income Tax TDS and GST on Purchase Transactions
description: Calculation of Income Tax TDS and GST on Purchase Transactions
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 3167fb5903ecb2783d8bfb7c958a5926ba82df7f
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948620"
---
# <a name="calculation-of-income-tax-tds-and-gst-on-purchase-transactions"></a><span data-ttu-id="f1f2d-103">Calculation of Income Tax TDS and GST on Purchase Transactions</span><span class="sxs-lookup"><span data-stu-id="f1f2d-103">Calculation of Income Tax TDS and GST on Purchase Transactions</span></span>

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="f1f2d-104">There are certain services on which GST applies along with the provisions of TDS under income tax.</span><span class="sxs-lookup"><span data-stu-id="f1f2d-104">There are certain services on which GST applies along with the provisions of TDS under income tax.</span></span> <span data-ttu-id="f1f2d-105">TDS should not be calculated on GST amount, in some cases where payment terms is set as 100% advance, full order value has to be paid as advance payment.</span><span class="sxs-lookup"><span data-stu-id="f1f2d-105">TDS should not be calculated on GST amount, in some cases where payment terms is set as 100% advance, full order value has to be paid as advance payment.</span></span> <span data-ttu-id="f1f2d-106">In such cases, amount paid to vendor will be inclusive of GST and if TDS has to deducted while paying amount to vendor, then TDS is deducted only on the base amount and not on GST amount.</span><span class="sxs-lookup"><span data-stu-id="f1f2d-106">In such cases, amount paid to vendor will be inclusive of GST and if TDS has to deducted while paying amount to vendor, then TDS is deducted only on the base amount and not on GST amount.</span></span>

## <a name="create-a-purchase-invoice"></a><span data-ttu-id="f1f2d-107">Create a purchase invoice</span><span class="sxs-lookup"><span data-stu-id="f1f2d-107">Create a purchase invoice</span></span>

1. <span data-ttu-id="f1f2d-108">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Purchase Invoice** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="f1f2d-108">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Purchase Invoice** , and then choose the related link.</span></span>
2. <span data-ttu-id="f1f2d-109">Select **Vendor** on **Invoice Header** .</span><span class="sxs-lookup"><span data-stu-id="f1f2d-109">Select **Vendor** on **Invoice Header** .</span></span>
3. <span data-ttu-id="f1f2d-110">Select **G/L Account** for Service purchase on **Purchase Invoice** line.</span><span class="sxs-lookup"><span data-stu-id="f1f2d-110">Select **G/L Account** for Service purchase on **Purchase Invoice** line.</span></span> <span data-ttu-id="f1f2d-111">GST Group Code, HSN/SAC Code should not be blank and GST Credit value should be selected as **Availment** if the tax input credit is available or else **Non-Availment** on the Item or G/L Account.</span><span class="sxs-lookup"><span data-stu-id="f1f2d-111">GST Group Code, HSN/SAC Code should not be blank and GST Credit value should be selected as **Availment** if the tax input credit is available or else **Non-Availment** on the Item or G/L Account.</span></span> 

<span data-ttu-id="f1f2d-112">For example, there is a purchase invoice for INR 10,000 and 18% GST (i.e. 9% CGST and 9% SGST/UTGST in case of Intra-State or Intra-Union Territory transaction or 18% IGST in case of Inter-State transaction) has to be charged and Income Tax TDS @10% also to be charged.</span><span class="sxs-lookup"><span data-stu-id="f1f2d-112">For example, there is a purchase invoice for INR 10,000 and 18% GST (i.e. 9% CGST and 9% SGST/UTGST in case of Intra-State or Intra-Union Territory transaction or 18% IGST in case of Inter-State transaction) has to be charged and Income Tax TDS @10% also to be charged.</span></span>

- <span data-ttu-id="f1f2d-113">GST calculation will appear in the Fact Box, as following :</span><span class="sxs-lookup"><span data-stu-id="f1f2d-113">GST calculation will appear in the Fact Box, as following :</span></span>

    |<span data-ttu-id="f1f2d-114">Component</span><span class="sxs-lookup"><span data-stu-id="f1f2d-114">Component</span></span>|<span data-ttu-id="f1f2d-115">Amount</span><span class="sxs-lookup"><span data-stu-id="f1f2d-115">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="f1f2d-116">**Transaction Value**</span><span class="sxs-lookup"><span data-stu-id="f1f2d-116">**Transaction Value**</span></span>|<span data-ttu-id="f1f2d-117">10000</span><span class="sxs-lookup"><span data-stu-id="f1f2d-117">10000</span></span>|
    |<span data-ttu-id="f1f2d-118">**GST Base Amount**</span><span class="sxs-lookup"><span data-stu-id="f1f2d-118">**GST Base Amount**</span></span>|<span data-ttu-id="f1f2d-119">10,000</span><span class="sxs-lookup"><span data-stu-id="f1f2d-119">10,000</span></span>|  
    |<span data-ttu-id="f1f2d-120">**CGST**</span><span class="sxs-lookup"><span data-stu-id="f1f2d-120">**CGST**</span></span>|<span data-ttu-id="f1f2d-121">900</span><span class="sxs-lookup"><span data-stu-id="f1f2d-121">900</span></span>|  
    |<span data-ttu-id="f1f2d-122">**SGST**</span><span class="sxs-lookup"><span data-stu-id="f1f2d-122">**SGST**</span></span>|<span data-ttu-id="f1f2d-123">900</span><span class="sxs-lookup"><span data-stu-id="f1f2d-123">900</span></span>|
    |<span data-ttu-id="f1f2d-124">**IGST**</span><span class="sxs-lookup"><span data-stu-id="f1f2d-124">**IGST**</span></span>|<span data-ttu-id="f1f2d-125">1800</span><span class="sxs-lookup"><span data-stu-id="f1f2d-125">1800</span></span>|
    |<span data-ttu-id="f1f2d-126">**TDS**</span><span class="sxs-lookup"><span data-stu-id="f1f2d-126">**TDS**</span></span>|<span data-ttu-id="f1f2d-127">1000</span><span class="sxs-lookup"><span data-stu-id="f1f2d-127">1000</span></span>|

- <span data-ttu-id="f1f2d-128">GL Entries for Income Tax TDS and GST in Intra-State purchase transactions, will be as following:</span><span class="sxs-lookup"><span data-stu-id="f1f2d-128">GL Entries for Income Tax TDS and GST in Intra-State purchase transactions, will be as following:</span></span>
    
    |<span data-ttu-id="f1f2d-129">Particular</span><span class="sxs-lookup"><span data-stu-id="f1f2d-129">Particular</span></span>|<span data-ttu-id="f1f2d-130">Amount</span><span class="sxs-lookup"><span data-stu-id="f1f2d-130">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="f1f2d-131">**Service Account**</span><span class="sxs-lookup"><span data-stu-id="f1f2d-131">**Service Account**</span></span>|<span data-ttu-id="f1f2d-132">10000</span><span class="sxs-lookup"><span data-stu-id="f1f2d-132">10000</span></span>|  
    |<span data-ttu-id="f1f2d-133">**SGST/UTGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="f1f2d-133">**SGST/UTGST Receivable Account**</span></span>|<span data-ttu-id="f1f2d-134">900</span><span class="sxs-lookup"><span data-stu-id="f1f2d-134">900</span></span>|  
    |<span data-ttu-id="f1f2d-135">**CGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="f1f2d-135">**CGST Receivable Account**</span></span>|<span data-ttu-id="f1f2d-136">900</span><span class="sxs-lookup"><span data-stu-id="f1f2d-136">900</span></span>|
    |<span data-ttu-id="f1f2d-137">**TDS Payable Account**</span><span class="sxs-lookup"><span data-stu-id="f1f2d-137">**TDS Payable Account**</span></span>|<span data-ttu-id="f1f2d-138">-1000</span><span class="sxs-lookup"><span data-stu-id="f1f2d-138">-1000</span></span>|
    |<span data-ttu-id="f1f2d-139">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="f1f2d-139">**Vendor Account**</span></span>|<span data-ttu-id="f1f2d-140">-10800</span><span class="sxs-lookup"><span data-stu-id="f1f2d-140">-10800</span></span>|

- <span data-ttu-id="f1f2d-141">GL Entries for Income Tax TDS and GST in Intra-State or Intra-Union Territory purchase transactions (reverse charge) will be as following:</span><span class="sxs-lookup"><span data-stu-id="f1f2d-141">GL Entries for Income Tax TDS and GST in Intra-State or Intra-Union Territory purchase transactions (reverse charge) will be as following:</span></span>
    
    |<span data-ttu-id="f1f2d-142">Particular</span><span class="sxs-lookup"><span data-stu-id="f1f2d-142">Particular</span></span>|<span data-ttu-id="f1f2d-143">Amount</span><span class="sxs-lookup"><span data-stu-id="f1f2d-143">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="f1f2d-144">**Service Account**</span><span class="sxs-lookup"><span data-stu-id="f1f2d-144">**Service Account**</span></span>|<span data-ttu-id="f1f2d-145">10000</span><span class="sxs-lookup"><span data-stu-id="f1f2d-145">10000</span></span>|  
    |<span data-ttu-id="f1f2d-146">**SGST/UTGST Receivable Account (Interim)**</span><span class="sxs-lookup"><span data-stu-id="f1f2d-146">**SGST/UTGST Receivable Account (Interim)**</span></span>|<span data-ttu-id="f1f2d-147">900</span><span class="sxs-lookup"><span data-stu-id="f1f2d-147">900</span></span>|  
    |<span data-ttu-id="f1f2d-148">**CGST Receivable Account (Interim)**</span><span class="sxs-lookup"><span data-stu-id="f1f2d-148">**CGST Receivable Account (Interim)**</span></span>|<span data-ttu-id="f1f2d-149">900</span><span class="sxs-lookup"><span data-stu-id="f1f2d-149">900</span></span>|
    |<span data-ttu-id="f1f2d-150">**TDS Payable Account**</span><span class="sxs-lookup"><span data-stu-id="f1f2d-150">**TDS Payable Account**</span></span>|<span data-ttu-id="f1f2d-151">-1000</span><span class="sxs-lookup"><span data-stu-id="f1f2d-151">-1000</span></span>|
    |<span data-ttu-id="f1f2d-152">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="f1f2d-152">**Vendor Account**</span></span>|<span data-ttu-id="f1f2d-153">-9000</span><span class="sxs-lookup"><span data-stu-id="f1f2d-153">-9000</span></span>|
    |<span data-ttu-id="f1f2d-154">**SGST/UTGST Payable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="f1f2d-154">**SGST/UTGST Payable (Interim) Account**</span></span>|<span data-ttu-id="f1f2d-155">-900</span><span class="sxs-lookup"><span data-stu-id="f1f2d-155">-900</span></span>|
    |<span data-ttu-id="f1f2d-156">**CGST Payable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="f1f2d-156">**CGST Payable (Interim) Account**</span></span>|<span data-ttu-id="f1f2d-157">-900</span><span class="sxs-lookup"><span data-stu-id="f1f2d-157">-900</span></span>|

- <span data-ttu-id="f1f2d-158">GL Entries for Income Tax TDS and GST in Inter-State purchase transactions, will be as following:</span><span class="sxs-lookup"><span data-stu-id="f1f2d-158">GL Entries for Income Tax TDS and GST in Inter-State purchase transactions, will be as following:</span></span>
   
    |<span data-ttu-id="f1f2d-159">Particulars</span><span class="sxs-lookup"><span data-stu-id="f1f2d-159">Particulars</span></span>|<span data-ttu-id="f1f2d-160">Amount</span><span class="sxs-lookup"><span data-stu-id="f1f2d-160">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="f1f2d-161">**Service Account**</span><span class="sxs-lookup"><span data-stu-id="f1f2d-161">**Service Account**</span></span>|<span data-ttu-id="f1f2d-162">10000</span><span class="sxs-lookup"><span data-stu-id="f1f2d-162">10000</span></span>|
    |<span data-ttu-id="f1f2d-163">**IGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="f1f2d-163">**IGST Receivable Account**</span></span>|<span data-ttu-id="f1f2d-164">1800</span><span class="sxs-lookup"><span data-stu-id="f1f2d-164">1800</span></span>|
    |<span data-ttu-id="f1f2d-165">**TDS Payable Account**</span><span class="sxs-lookup"><span data-stu-id="f1f2d-165">**TDS Payable Account**</span></span>|<span data-ttu-id="f1f2d-166">-1000</span><span class="sxs-lookup"><span data-stu-id="f1f2d-166">-1000</span></span>|
    |<span data-ttu-id="f1f2d-167">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="f1f2d-167">**Vendor Account**</span></span>|<span data-ttu-id="f1f2d-168">-10800</span><span class="sxs-lookup"><span data-stu-id="f1f2d-168">-10800</span></span>|

- <span data-ttu-id="f1f2d-169">GL Entries for Income Tax TDS and GST in Inter-State purchase transactions (reverse charge), will be as following:</span><span class="sxs-lookup"><span data-stu-id="f1f2d-169">GL Entries for Income Tax TDS and GST in Inter-State purchase transactions (reverse charge), will be as following:</span></span>
    
    |<span data-ttu-id="f1f2d-170">Particular</span><span class="sxs-lookup"><span data-stu-id="f1f2d-170">Particular</span></span>|<span data-ttu-id="f1f2d-171">Amount</span><span class="sxs-lookup"><span data-stu-id="f1f2d-171">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="f1f2d-172">**Service Account**</span><span class="sxs-lookup"><span data-stu-id="f1f2d-172">**Service Account**</span></span>|<span data-ttu-id="f1f2d-173">10000</span><span class="sxs-lookup"><span data-stu-id="f1f2d-173">10000</span></span>|
    |<span data-ttu-id="f1f2d-174">**IGST Receivable Account (Interim)**</span><span class="sxs-lookup"><span data-stu-id="f1f2d-174">**IGST Receivable Account (Interim)**</span></span>|<span data-ttu-id="f1f2d-175">1800</span><span class="sxs-lookup"><span data-stu-id="f1f2d-175">1800</span></span>|
    |<span data-ttu-id="f1f2d-176">**TDS Payable Account**</span><span class="sxs-lookup"><span data-stu-id="f1f2d-176">**TDS Payable Account**</span></span>|<span data-ttu-id="f1f2d-177">-1000</span><span class="sxs-lookup"><span data-stu-id="f1f2d-177">-1000</span></span>|
    |<span data-ttu-id="f1f2d-178">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="f1f2d-178">**Vendor Account**</span></span>|<span data-ttu-id="f1f2d-179">-9000</span><span class="sxs-lookup"><span data-stu-id="f1f2d-179">-9000</span></span>|
    |<span data-ttu-id="f1f2d-180">**IGST Payable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="f1f2d-180">**IGST Payable (Interim) Account**</span></span>|<span data-ttu-id="f1f2d-181">-1800</span><span class="sxs-lookup"><span data-stu-id="f1f2d-181">-1800</span></span>|







































