---
title: GST on Advance Payment Application with Sales Invoice
description: GST on Advance Payment Application with Sales Invoice
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 4a6f7b9e850de61c71e31f8294e952afeb5188fb
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948647"
---
# <a name="gst-on-advance-payment-and-application-with-sales-invoice"></a><span data-ttu-id="8451b-103">GST on Advance Payment and Application with Sales Invoice</span><span class="sxs-lookup"><span data-stu-id="8451b-103">GST on Advance Payment and Application with Sales Invoice</span></span>

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="8451b-104">GST can also be liable at the time of receiving advance payment from customer.</span><span class="sxs-lookup"><span data-stu-id="8451b-104">GST can also be liable at the time of receiving advance payment from customer.</span></span> <span data-ttu-id="8451b-105">If advance payment is applied to an invoice in the same month, then such applications need not be disclosed in GSTR-1.</span><span class="sxs-lookup"><span data-stu-id="8451b-105">If advance payment is applied to an invoice in the same month, then such applications need not be disclosed in GSTR-1.</span></span> <span data-ttu-id="8451b-106">However, if advance payment is paid in a month and is applied to invoice in the subsequent month, then this application needs to be reported in GSTR-1.</span><span class="sxs-lookup"><span data-stu-id="8451b-106">However, if advance payment is paid in a month and is applied to invoice in the subsequent month, then this application needs to be reported in GSTR-1.</span></span>

<span data-ttu-id="8451b-107">Process of application of advance payment from customer and sale invoice has been explained in this document.</span><span class="sxs-lookup"><span data-stu-id="8451b-107">Process of application of advance payment from customer and sale invoice has been explained in this document.</span></span>

<span data-ttu-id="8451b-108">For example, service amount is INR 20000 and customer made an advance payment of INR 10,000 and 18% GST (i.e. 9% CGST and 9% SGST/UTGST) has to be charged on the advance payment.</span><span class="sxs-lookup"><span data-stu-id="8451b-108">For example, service amount is INR 20000 and customer made an advance payment of INR 10,000 and 18% GST (i.e. 9% CGST and 9% SGST/UTGST) has to be charged on the advance payment.</span></span>

- <span data-ttu-id="8451b-109">GST Calculation will appear in the Fact Box, as following:</span><span class="sxs-lookup"><span data-stu-id="8451b-109">GST Calculation will appear in the Fact Box, as following:</span></span>
    
    |<span data-ttu-id="8451b-110">Component</span><span class="sxs-lookup"><span data-stu-id="8451b-110">Component</span></span>|<span data-ttu-id="8451b-111">Amount</span><span class="sxs-lookup"><span data-stu-id="8451b-111">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="8451b-112">**GST Base Amount**</span><span class="sxs-lookup"><span data-stu-id="8451b-112">**GST Base Amount**</span></span>|<span data-ttu-id="8451b-113">10,000</span><span class="sxs-lookup"><span data-stu-id="8451b-113">10,000</span></span>|
    |<span data-ttu-id="8451b-114">**GST Transactional Value**</span><span class="sxs-lookup"><span data-stu-id="8451b-114">**GST Transactional Value**</span></span>|<span data-ttu-id="8451b-115">8,474 (10000\*100/118)</span><span class="sxs-lookup"><span data-stu-id="8451b-115">8,474 (10000\*100/118)</span></span>|
    |<span data-ttu-id="8451b-116">**CGST**</span><span class="sxs-lookup"><span data-stu-id="8451b-116">**CGST**</span></span>|<span data-ttu-id="8451b-117">763 (8,475\*9%)</span><span class="sxs-lookup"><span data-stu-id="8451b-117">763 (8,475\*9%)</span></span>|  
    |<span data-ttu-id="8451b-118">**SGST**</span><span class="sxs-lookup"><span data-stu-id="8451b-118">**SGST**</span></span>|<span data-ttu-id="8451b-119">763 (8,475\*9%)</span><span class="sxs-lookup"><span data-stu-id="8451b-119">763 (8,475\*9%)</span></span>|

<span data-ttu-id="8451b-120">Later sales invoice for services is issued to the customer for INR 20,000.</span><span class="sxs-lookup"><span data-stu-id="8451b-120">Later sales invoice for services is issued to the customer for INR 20,000.</span></span> <span data-ttu-id="8451b-121">18% GST (i.e. 9% CGST and 9% SGST/UTGST in case of Intra-State or Intra-Union Territory transaction or 18% IGST in case of Inter-State transaction) has to be charged on the invoice amount.</span><span class="sxs-lookup"><span data-stu-id="8451b-121">18% GST (i.e. 9% CGST and 9% SGST/UTGST in case of Intra-State or Intra-Union Territory transaction or 18% IGST in case of Inter-State transaction) has to be charged on the invoice amount.</span></span>

- <span data-ttu-id="8451b-122">GST calculation will appear in the Fact Box, as following:</span><span class="sxs-lookup"><span data-stu-id="8451b-122">GST calculation will appear in the Fact Box, as following:</span></span>

    |<span data-ttu-id="8451b-123">Component</span><span class="sxs-lookup"><span data-stu-id="8451b-123">Component</span></span>|<span data-ttu-id="8451b-124">Amount</span><span class="sxs-lookup"><span data-stu-id="8451b-124">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="8451b-125">**GST Base Amount**</span><span class="sxs-lookup"><span data-stu-id="8451b-125">**GST Base Amount**</span></span>|<span data-ttu-id="8451b-126">20000</span><span class="sxs-lookup"><span data-stu-id="8451b-126">20000</span></span>|  
    |<span data-ttu-id="8451b-127">**CGST**</span><span class="sxs-lookup"><span data-stu-id="8451b-127">**CGST**</span></span>|<span data-ttu-id="8451b-128">1800</span><span class="sxs-lookup"><span data-stu-id="8451b-128">1800</span></span>|  
    |<span data-ttu-id="8451b-129">**SGST**</span><span class="sxs-lookup"><span data-stu-id="8451b-129">**SGST**</span></span>|<span data-ttu-id="8451b-130">1800</span><span class="sxs-lookup"><span data-stu-id="8451b-130">1800</span></span>|

- <span data-ttu-id="8451b-131">GL Entries for application of advance payment with sales invoice, will be as following:</span><span class="sxs-lookup"><span data-stu-id="8451b-131">GL Entries for application of advance payment with sales invoice, will be as following:</span></span>

    |<span data-ttu-id="8451b-132">Particulars</span><span class="sxs-lookup"><span data-stu-id="8451b-132">Particulars</span></span>|<span data-ttu-id="8451b-133">Amount</span><span class="sxs-lookup"><span data-stu-id="8451b-133">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="8451b-134">**Customer Account**</span><span class="sxs-lookup"><span data-stu-id="8451b-134">**Customer Account**</span></span>|<span data-ttu-id="8451b-135">23600</span><span class="sxs-lookup"><span data-stu-id="8451b-135">23600</span></span>|  
    |<span data-ttu-id="8451b-136">**CGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="8451b-136">**CGST Payable Account**</span></span>|<span data-ttu-id="8451b-137">-1800</span><span class="sxs-lookup"><span data-stu-id="8451b-137">-1800</span></span>|  
    |<span data-ttu-id="8451b-138">**SGST/UTGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="8451b-138">**SGST/UTGST Payable Account**</span></span>|<span data-ttu-id="8451b-139">-1800</span><span class="sxs-lookup"><span data-stu-id="8451b-139">-1800</span></span>| 
    |<span data-ttu-id="8451b-140">**Sales Account**</span><span class="sxs-lookup"><span data-stu-id="8451b-140">**Sales Account**</span></span>|<span data-ttu-id="8451b-141">-20000</span><span class="sxs-lookup"><span data-stu-id="8451b-141">-20000</span></span>| 
    |<span data-ttu-id="8451b-142">**CGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="8451b-142">**CGST Payable Account**</span></span>|<span data-ttu-id="8451b-143">763</span><span class="sxs-lookup"><span data-stu-id="8451b-143">763</span></span>| 
    |<span data-ttu-id="8451b-144">**SGST/UTGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="8451b-144">**SGST/UTGST Payable Account**</span></span>|<span data-ttu-id="8451b-145">763</span><span class="sxs-lookup"><span data-stu-id="8451b-145">763</span></span>| 
    |<span data-ttu-id="8451b-146">**CGST Payable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="8451b-146">**CGST Payable (Interim) Account**</span></span>|<span data-ttu-id="8451b-147">-763</span><span class="sxs-lookup"><span data-stu-id="8451b-147">-763</span></span>|   
    |<span data-ttu-id="8451b-148">**SGST/UTGST Payable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="8451b-148">**SGST/UTGST Payable (Interim) Account**</span></span>|<span data-ttu-id="8451b-149">-763</span><span class="sxs-lookup"><span data-stu-id="8451b-149">-763</span></span>|  

## <a name="gst-un-application-of-customer-advance-with-sales-invoice"></a><span data-ttu-id="8451b-150">GST un-application of customer advance with sales invoice</span><span class="sxs-lookup"><span data-stu-id="8451b-150">GST un-application of customer advance with sales invoice</span></span>

<span data-ttu-id="8451b-151">If this is found that the payment and invoice was wrongly applied  and the application needs to be reversed, in such a case un apply functionality can be used.</span><span class="sxs-lookup"><span data-stu-id="8451b-151">If this is found that the payment and invoice was wrongly applied  and the application needs to be reversed, in such a case un apply functionality can be used.</span></span> <span data-ttu-id="8451b-152">Un-application entries are same for both online application and offline application.</span><span class="sxs-lookup"><span data-stu-id="8451b-152">Un-application entries are same for both online application and offline application.</span></span>

> [!TIP]
> <span data-ttu-id="8451b-153">An advance receipt and invoice application cannot be unapplied, if the tax liability on both is discharged through GST Settlement Screen.</span><span class="sxs-lookup"><span data-stu-id="8451b-153">An advance receipt and invoice application cannot be unapplied, if the tax liability on both is discharged through GST Settlement Screen.</span></span>

- <span data-ttu-id="8451b-154">GL Entries for un-application of an advance payment and sales invoice:</span><span class="sxs-lookup"><span data-stu-id="8451b-154">GL Entries for un-application of an advance payment and sales invoice:</span></span>

    |<span data-ttu-id="8451b-155">Particulars</span><span class="sxs-lookup"><span data-stu-id="8451b-155">Particulars</span></span>|<span data-ttu-id="8451b-156">Amount</span><span class="sxs-lookup"><span data-stu-id="8451b-156">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="8451b-157">**CGST Payable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="8451b-157">**CGST Payable (Interim) Account**</span></span>|<span data-ttu-id="8451b-158">763</span><span class="sxs-lookup"><span data-stu-id="8451b-158">763</span></span>|  
    |<span data-ttu-id="8451b-159">**SGST/UTGST Payable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="8451b-159">**SGST/UTGST Payable (Interim) Account**</span></span>|<span data-ttu-id="8451b-160">763</span><span class="sxs-lookup"><span data-stu-id="8451b-160">763</span></span>|  
    |<span data-ttu-id="8451b-161">**CGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="8451b-161">**CGST Payable Account**</span></span>|<span data-ttu-id="8451b-162">-763</span><span class="sxs-lookup"><span data-stu-id="8451b-162">-763</span></span>| 
    |<span data-ttu-id="8451b-163">**SGST/UTGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="8451b-163">**SGST/UTGST Payable Account**</span></span>|<span data-ttu-id="8451b-164">-763</span><span class="sxs-lookup"><span data-stu-id="8451b-164">-763</span></span>| 


> [!TIP]
> <span data-ttu-id="8451b-165">In case of Inter-State Sale, IGST will be calculated.</span><span class="sxs-lookup"><span data-stu-id="8451b-165">In case of Inter-State Sale, IGST will be calculated.</span></span>

