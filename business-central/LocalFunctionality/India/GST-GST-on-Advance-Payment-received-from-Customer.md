---
title: GST on Advance Payment received from Customer
description: GST on Advance Payment received from Customer
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 160a174e75d19817a06b802f7b078d163d3518be
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948648"
---
# <a name="gst-on-advance-payment-received-from-customer"></a><span data-ttu-id="c6a69-103">GST on Advance Payment Received from Customer</span><span class="sxs-lookup"><span data-stu-id="c6a69-103">GST on Advance Payment Received from Customer</span></span>

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="c6a69-104">The advance payments received from the customers may need to be reported in GSTR-1 along with GST Rates.</span><span class="sxs-lookup"><span data-stu-id="c6a69-104">The advance payments received from the customers may need to be reported in GSTR-1 along with GST Rates.</span></span>

<span data-ttu-id="c6a69-105">Process of GST calculation on advance payment from customer has been explained in this document.</span><span class="sxs-lookup"><span data-stu-id="c6a69-105">Process of GST calculation on advance payment from customer has been explained in this document.</span></span>

### <a name="create-a-general-journal-or-a-bank-or-cash-receipt-voucher"></a><span data-ttu-id="c6a69-106">Create a general journal or a bank or cash receipt voucher</span><span class="sxs-lookup"><span data-stu-id="c6a69-106">Create a general journal or a bank or cash receipt voucher</span></span>

1. <span data-ttu-id="c6a69-107">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **General Journal** or **Bank Payment Voucher** or **Cash Receipt Voucher** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="c6a69-107">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **General Journal** or **Bank Payment Voucher** or **Cash Receipt Voucher** , and then choose the related link.</span></span>
2. <span data-ttu-id="c6a69-108">Select **Customer** in account type and select relevant **Customer Code** , GST customer type and registration number should not be blank on customer master.</span><span class="sxs-lookup"><span data-stu-id="c6a69-108">Select **Customer** in account type and select relevant **Customer Code** , GST customer type and registration number should not be blank on customer master.</span></span>
3. <span data-ttu-id="c6a69-109">Select **G/L Account** or **Bank Account** in balancing account type, and select the cash or bank account.</span><span class="sxs-lookup"><span data-stu-id="c6a69-109">Select **G/L Account** or **Bank Account** in balancing account type, and select the cash or bank account.</span></span> 
4. <span data-ttu-id="c6a69-110">GST on Advance Payment field needs to be activated in General Journal Line for computation of GST on Advance Payment.</span><span class="sxs-lookup"><span data-stu-id="c6a69-110">GST on Advance Payment field needs to be activated in General Journal Line for computation of GST on Advance Payment.</span></span> <span data-ttu-id="c6a69-111">In addition, GST Group code and GST Place of Supply are to be entered for computation of GST.</span><span class="sxs-lookup"><span data-stu-id="c6a69-111">In addition, GST Group code and GST Place of Supply are to be entered for computation of GST.</span></span>

<span data-ttu-id="c6a69-112">For example, advance payment received from customer for INR 10000 on which 18% GST (i.e. 9% CGST and 9% SGST/UTGST) has to be charged.</span><span class="sxs-lookup"><span data-stu-id="c6a69-112">For example, advance payment received from customer for INR 10000 on which 18% GST (i.e. 9% CGST and 9% SGST/UTGST) has to be charged.</span></span>

- <span data-ttu-id="c6a69-113">GST calculation will appear in the Fact Box, as following:</span><span class="sxs-lookup"><span data-stu-id="c6a69-113">GST calculation will appear in the Fact Box, as following:</span></span>
    
    |<span data-ttu-id="c6a69-114">Component</span><span class="sxs-lookup"><span data-stu-id="c6a69-114">Component</span></span>|<span data-ttu-id="c6a69-115">Amount</span><span class="sxs-lookup"><span data-stu-id="c6a69-115">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="c6a69-116">**Advance Payment**</span><span class="sxs-lookup"><span data-stu-id="c6a69-116">**Advance Payment**</span></span>|<span data-ttu-id="c6a69-117">10,000</span><span class="sxs-lookup"><span data-stu-id="c6a69-117">10,000</span></span>|
    |<span data-ttu-id="c6a69-118">**GST Transitional Value**</span><span class="sxs-lookup"><span data-stu-id="c6a69-118">**GST Transitional Value**</span></span>|<span data-ttu-id="c6a69-119">8,474 (10000\*100/118)</span><span class="sxs-lookup"><span data-stu-id="c6a69-119">8,474 (10000\*100/118)</span></span>|
    |<span data-ttu-id="c6a69-120">**CGST**</span><span class="sxs-lookup"><span data-stu-id="c6a69-120">**CGST**</span></span>|<span data-ttu-id="c6a69-121">763 (8,475\*9%)</span><span class="sxs-lookup"><span data-stu-id="c6a69-121">763 (8,475\*9%)</span></span>|  
    |<span data-ttu-id="c6a69-122">**SGST/UTGST**</span><span class="sxs-lookup"><span data-stu-id="c6a69-122">**SGST/UTGST**</span></span>|<span data-ttu-id="c6a69-123">763 (8,475\*9%)</span><span class="sxs-lookup"><span data-stu-id="c6a69-123">763 (8,475\*9%)</span></span>|

- <span data-ttu-id="c6a69-124">GL Entries for advance payment received from customer, will be as following:</span><span class="sxs-lookup"><span data-stu-id="c6a69-124">GL Entries for advance payment received from customer, will be as following:</span></span>

    |<span data-ttu-id="c6a69-125">Particulars</span><span class="sxs-lookup"><span data-stu-id="c6a69-125">Particulars</span></span>|<span data-ttu-id="c6a69-126">Amount</span><span class="sxs-lookup"><span data-stu-id="c6a69-126">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="c6a69-127">**Bank Account**</span><span class="sxs-lookup"><span data-stu-id="c6a69-127">**Bank Account**</span></span>|<span data-ttu-id="c6a69-128">10000</span><span class="sxs-lookup"><span data-stu-id="c6a69-128">10000</span></span>|  
    |<span data-ttu-id="c6a69-129">**CGST Payable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="c6a69-129">**CGST Payable (Interim) Account**</span></span>|<span data-ttu-id="c6a69-130">763</span><span class="sxs-lookup"><span data-stu-id="c6a69-130">763</span></span>|  
    |<span data-ttu-id="c6a69-131">**SGST/UTGST Payable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="c6a69-131">**SGST/UTGST Payable (Interim) Account**</span></span>|<span data-ttu-id="c6a69-132">763</span><span class="sxs-lookup"><span data-stu-id="c6a69-132">763</span></span>| 
    |<span data-ttu-id="c6a69-133">**CGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="c6a69-133">**CGST Payable Account**</span></span>|<span data-ttu-id="c6a69-134">-763</span><span class="sxs-lookup"><span data-stu-id="c6a69-134">-763</span></span>| 
    |<span data-ttu-id="c6a69-135">**SGST/UTGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="c6a69-135">**SGST/UTGST Payable Account**</span></span>|<span data-ttu-id="c6a69-136">-763</span><span class="sxs-lookup"><span data-stu-id="c6a69-136">-763</span></span>| 
    |<span data-ttu-id="c6a69-137">**Customer Account**</span><span class="sxs-lookup"><span data-stu-id="c6a69-137">**Customer Account**</span></span>|<span data-ttu-id="c6a69-138">-10000</span><span class="sxs-lookup"><span data-stu-id="c6a69-138">-10000</span></span>| 

## <a name="reversal-of-advance-payment-received-from-customer"></a><span data-ttu-id="c6a69-139">Reversal of advance payment received from customer</span><span class="sxs-lookup"><span data-stu-id="c6a69-139">Reversal of advance payment received from customer</span></span>

<span data-ttu-id="c6a69-140">If the customer advance needs to be corrected or the entry is wrongly posted, in such a case the entry can be reversed and new entry can be created.</span><span class="sxs-lookup"><span data-stu-id="c6a69-140">If the customer advance needs to be corrected or the entry is wrongly posted, in such a case the entry can be reversed and new entry can be created.</span></span>

- <span data-ttu-id="c6a69-141">Reversal GL Entries for advance payment received from customer, will be as following:</span><span class="sxs-lookup"><span data-stu-id="c6a69-141">Reversal GL Entries for advance payment received from customer, will be as following:</span></span>

    |<span data-ttu-id="c6a69-142">Particulars</span><span class="sxs-lookup"><span data-stu-id="c6a69-142">Particulars</span></span>|<span data-ttu-id="c6a69-143">Amount</span><span class="sxs-lookup"><span data-stu-id="c6a69-143">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="c6a69-144">**Customer Account**</span><span class="sxs-lookup"><span data-stu-id="c6a69-144">**Customer Account**</span></span>|<span data-ttu-id="c6a69-145">10000</span><span class="sxs-lookup"><span data-stu-id="c6a69-145">10000</span></span>| 
    |<span data-ttu-id="c6a69-146">**CGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="c6a69-146">**CGST Payable Account**</span></span>|<span data-ttu-id="c6a69-147">763</span><span class="sxs-lookup"><span data-stu-id="c6a69-147">763</span></span>| 
    |<span data-ttu-id="c6a69-148">**SGST/UTGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="c6a69-148">**SGST/UTGST Payable Account**</span></span>|<span data-ttu-id="c6a69-149">763</span><span class="sxs-lookup"><span data-stu-id="c6a69-149">763</span></span>| 
    |<span data-ttu-id="c6a69-150">**CGST Payable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="c6a69-150">**CGST Payable (Interim) Account**</span></span>|<span data-ttu-id="c6a69-151">-763</span><span class="sxs-lookup"><span data-stu-id="c6a69-151">-763</span></span>|  
    |<span data-ttu-id="c6a69-152">**SGST/UTGST Payable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="c6a69-152">**SGST/UTGST Payable (Interim) Account**</span></span>|<span data-ttu-id="c6a69-153">-763</span><span class="sxs-lookup"><span data-stu-id="c6a69-153">-763</span></span>| 
    |<span data-ttu-id="c6a69-154">**Bank Account**</span><span class="sxs-lookup"><span data-stu-id="c6a69-154">**Bank Account**</span></span>|<span data-ttu-id="c6a69-155">-10,000</span><span class="sxs-lookup"><span data-stu-id="c6a69-155">-10,000</span></span>|  
    
> [!TIP]
> <span data-ttu-id="c6a69-156">In case of Inter-State Advance Payment, IGST will be calculated.</span><span class="sxs-lookup"><span data-stu-id="c6a69-156">In case of Inter-State Advance Payment, IGST will be calculated.</span></span>






































