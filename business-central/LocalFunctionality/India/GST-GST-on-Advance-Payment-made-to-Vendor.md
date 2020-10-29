---
title: GST on Advance Payment made to Vendor, with reverse charge
description: GST on Advance Payment made to Vendor, with reverse charge
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 39935b3558cb89c78aff4499428dfbfe22ded483
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948649"
---
# <a name="gst-on-advance-payment-made-to-vendor-with-reverse-charge"></a><span data-ttu-id="d477e-103">GST on Advance Payment Made to Vendor, with Reverse Charge</span><span class="sxs-lookup"><span data-stu-id="d477e-103">GST on Advance Payment Made to Vendor, with Reverse Charge</span></span>

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="d477e-104">The tax needs to be paid if supplier gets the payment first, therefore we need to calculate GST at the time of advance payment made to the vendor.</span><span class="sxs-lookup"><span data-stu-id="d477e-104">The tax needs to be paid if supplier gets the payment first, therefore we need to calculate GST at the time of advance payment made to the vendor.</span></span> <span data-ttu-id="d477e-105">However, when ‘supplier of goods’ receives advance payment, he is not required to pay GST at the time of the receipt of advance payment, while GST is required to be paid in case of supply of services.</span><span class="sxs-lookup"><span data-stu-id="d477e-105">However, when ‘supplier of goods’ receives advance payment, he is not required to pay GST at the time of the receipt of advance payment, while GST is required to be paid in case of supply of services.</span></span>

<span data-ttu-id="d477e-106">The process of GST calculation on advance payment to vendor has been explained in this document.</span><span class="sxs-lookup"><span data-stu-id="d477e-106">The process of GST calculation on advance payment to vendor has been explained in this document.</span></span>

### <a name="create-a-general-journal-or-a-bank-or-cash-payment-voucher"></a><span data-ttu-id="d477e-107">Create a general journal or a bank or cash payment voucher</span><span class="sxs-lookup"><span data-stu-id="d477e-107">Create a general journal or a bank or cash payment voucher</span></span>

1.  <span data-ttu-id="d477e-108">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **General Journal** or **Bank Payment Voucher** or **Cash Payment Voucher** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="d477e-108">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **General Journal** or **Bank Payment Voucher** or **Cash Payment Voucher** , and then choose the related link.</span></span> 
2. <span data-ttu-id="d477e-109">Select **Vendor** in account type and select relevant **Vendor Code** , GST vendor type and registration number should be filled in vendor master.</span><span class="sxs-lookup"><span data-stu-id="d477e-109">Select **Vendor** in account type and select relevant **Vendor Code** , GST vendor type and registration number should be filled in vendor master.</span></span>
3. <span data-ttu-id="d477e-110">Select **G/L Account** or **Bank Account** in balancing account type, and select the cash or the bank account.</span><span class="sxs-lookup"><span data-stu-id="d477e-110">Select **G/L Account** or **Bank Account** in balancing account type, and select the cash or the bank account.</span></span> 
4. <span data-ttu-id="d477e-111">Advance Payment made to vendor does not include tax payment, as the purchaser is liable to pay tax under reverse charge.</span><span class="sxs-lookup"><span data-stu-id="d477e-111">Advance Payment made to vendor does not include tax payment, as the purchaser is liable to pay tax under reverse charge.</span></span> <span data-ttu-id="d477e-112">Hence, tax is applied straight away on base.</span><span class="sxs-lookup"><span data-stu-id="d477e-112">Hence, tax is applied straight away on base.</span></span> 
5. <span data-ttu-id="d477e-113">GST on Advance Payment field needs to be activated on General Journal Line for computation of GST on Advance Payment.</span><span class="sxs-lookup"><span data-stu-id="d477e-113">GST on Advance Payment field needs to be activated on General Journal Line for computation of GST on Advance Payment.</span></span> <span data-ttu-id="d477e-114">In addition, GST Group code and GST Place of Supply should not be blank for computation of GST.</span><span class="sxs-lookup"><span data-stu-id="d477e-114">In addition, GST Group code and GST Place of Supply should not be blank for computation of GST.</span></span>

<span data-ttu-id="d477e-115">For example, advance payment made to vendor against supply of services of INR 10,000 on which 18% GST (9% CGST and 9% SGST/UTGST in case of Intra-State or Intra-Union Territory transaction or 18% IGST in case of Inter-State transaction) has to be charged.</span><span class="sxs-lookup"><span data-stu-id="d477e-115">For example, advance payment made to vendor against supply of services of INR 10,000 on which 18% GST (9% CGST and 9% SGST/UTGST in case of Intra-State or Intra-Union Territory transaction or 18% IGST in case of Inter-State transaction) has to be charged.</span></span>

- <span data-ttu-id="d477e-116">GST Calculation will appear in the Fact Box as following:</span><span class="sxs-lookup"><span data-stu-id="d477e-116">GST Calculation will appear in the Fact Box as following:</span></span>
    
    |<span data-ttu-id="d477e-117">Component</span><span class="sxs-lookup"><span data-stu-id="d477e-117">Component</span></span>|<span data-ttu-id="d477e-118">Amount</span><span class="sxs-lookup"><span data-stu-id="d477e-118">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="d477e-119">**GST Base Amount**</span><span class="sxs-lookup"><span data-stu-id="d477e-119">**GST Base Amount**</span></span>|<span data-ttu-id="d477e-120">10,000</span><span class="sxs-lookup"><span data-stu-id="d477e-120">10,000</span></span>|  
    |<span data-ttu-id="d477e-121">**CGST**</span><span class="sxs-lookup"><span data-stu-id="d477e-121">**CGST**</span></span>|<span data-ttu-id="d477e-122">900</span><span class="sxs-lookup"><span data-stu-id="d477e-122">900</span></span>|  
    |<span data-ttu-id="d477e-123">**SGST**</span><span class="sxs-lookup"><span data-stu-id="d477e-123">**SGST**</span></span>|<span data-ttu-id="d477e-124">900</span><span class="sxs-lookup"><span data-stu-id="d477e-124">900</span></span>|
    |<span data-ttu-id="d477e-125">**IGST**</span><span class="sxs-lookup"><span data-stu-id="d477e-125">**IGST**</span></span>|<span data-ttu-id="d477e-126">1800</span><span class="sxs-lookup"><span data-stu-id="d477e-126">1800</span></span>|

- <span data-ttu-id="d477e-127">GL Entries for Advance Payment made to Vendor, will be as following:</span><span class="sxs-lookup"><span data-stu-id="d477e-127">GL Entries for Advance Payment made to Vendor, will be as following:</span></span>

    |<span data-ttu-id="d477e-128">Particulars</span><span class="sxs-lookup"><span data-stu-id="d477e-128">Particulars</span></span>|<span data-ttu-id="d477e-129">Amount</span><span class="sxs-lookup"><span data-stu-id="d477e-129">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="d477e-130">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="d477e-130">**Vendor Account**</span></span>|<span data-ttu-id="d477e-131">10,000</span><span class="sxs-lookup"><span data-stu-id="d477e-131">10,000</span></span>|  
    |<span data-ttu-id="d477e-132">**SGST/UTGST Receivable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="d477e-132">**SGST/UTGST Receivable (Interim) Account**</span></span>|<span data-ttu-id="d477e-133">900</span><span class="sxs-lookup"><span data-stu-id="d477e-133">900</span></span>|  
    |<span data-ttu-id="d477e-134">**CGST Receivable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="d477e-134">**CGST Receivable (Interim) Account**</span></span>|<span data-ttu-id="d477e-135">900</span><span class="sxs-lookup"><span data-stu-id="d477e-135">900</span></span>|
    |<span data-ttu-id="d477e-136">**SGST/UTGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="d477e-136">**SGST/UTGST Payable Account**</span></span>|<span data-ttu-id="d477e-137">-900</span><span class="sxs-lookup"><span data-stu-id="d477e-137">-900</span></span>|
    |<span data-ttu-id="d477e-138">**CGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="d477e-138">**CGST Payable Account**</span></span>|<span data-ttu-id="d477e-139">-900</span><span class="sxs-lookup"><span data-stu-id="d477e-139">-900</span></span>|
    |<span data-ttu-id="d477e-140">**Bank Account**</span><span class="sxs-lookup"><span data-stu-id="d477e-140">**Bank Account**</span></span>|<span data-ttu-id="d477e-141">-10000</span><span class="sxs-lookup"><span data-stu-id="d477e-141">-10000</span></span>|

## <a name="reversal-of-advance-payment-made-to-vendor-where-there-are-reverse-charges"></a><span data-ttu-id="d477e-142">Reversal of advance payment made to vendor, where there are reverse charges</span><span class="sxs-lookup"><span data-stu-id="d477e-142">Reversal of advance payment made to vendor, where there are reverse charges</span></span>

<span data-ttu-id="d477e-143">If the vendor advance needs to be corrected or the entry is wrongly posted, in such a case the entry can be reversed and new entry can be created.</span><span class="sxs-lookup"><span data-stu-id="d477e-143">If the vendor advance needs to be corrected or the entry is wrongly posted, in such a case the entry can be reversed and new entry can be created.</span></span>

- <span data-ttu-id="d477e-144">Reversal GL Entries for Advance Payment made to Vendor, will be as following:</span><span class="sxs-lookup"><span data-stu-id="d477e-144">Reversal GL Entries for Advance Payment made to Vendor, will be as following:</span></span>

    |<span data-ttu-id="d477e-145">Particulars</span><span class="sxs-lookup"><span data-stu-id="d477e-145">Particulars</span></span>|<span data-ttu-id="d477e-146">Amount</span><span class="sxs-lookup"><span data-stu-id="d477e-146">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="d477e-147">**Bank Account**</span><span class="sxs-lookup"><span data-stu-id="d477e-147">**Bank Account**</span></span>|<span data-ttu-id="d477e-148">10000</span><span class="sxs-lookup"><span data-stu-id="d477e-148">10000</span></span>| 
    |<span data-ttu-id="d477e-149">**SGST/UTGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="d477e-149">**SGST/UTGST Payable Account**</span></span>|<span data-ttu-id="d477e-150">900</span><span class="sxs-lookup"><span data-stu-id="d477e-150">900</span></span>|
    |<span data-ttu-id="d477e-151">**CGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="d477e-151">**CGST Payable Account**</span></span>|<span data-ttu-id="d477e-152">900</span><span class="sxs-lookup"><span data-stu-id="d477e-152">900</span></span>|
    |<span data-ttu-id="d477e-153">**SGST/UTGST Receivable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="d477e-153">**SGST/UTGST Receivable (Interim) Account**</span></span>|<span data-ttu-id="d477e-154">-900</span><span class="sxs-lookup"><span data-stu-id="d477e-154">-900</span></span>|  
    |<span data-ttu-id="d477e-155">**CGST Receivable (Interim) Account**</span><span class="sxs-lookup"><span data-stu-id="d477e-155">**CGST Receivable (Interim) Account**</span></span>|<span data-ttu-id="d477e-156">-900</span><span class="sxs-lookup"><span data-stu-id="d477e-156">-900</span></span>|
    |<span data-ttu-id="d477e-157">**Vendor Account**</span><span class="sxs-lookup"><span data-stu-id="d477e-157">**Vendor Account**</span></span>|<span data-ttu-id="d477e-158">-10,000</span><span class="sxs-lookup"><span data-stu-id="d477e-158">-10,000</span></span>|  
    
> [!TIP]
> <span data-ttu-id="d477e-159">In case of Inter-State Advance Payment, IGST will be calculated.</span><span class="sxs-lookup"><span data-stu-id="d477e-159">In case of Inter-State Advance Payment, IGST will be calculated.</span></span>






































