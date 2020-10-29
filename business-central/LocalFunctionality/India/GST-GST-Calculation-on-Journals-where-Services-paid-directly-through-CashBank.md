---
title: GST on Journals where Services paid directly through Cash or Bank
description: GST on Journals where Services paid directly through Cash or Bank
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: e137117a45d82bf22ab845d0b4fad016132eb33f
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948651"
---
# <a name="gst-on-journals-where-services-are-paid-directly-through-cash-or-bank"></a><span data-ttu-id="e6ecd-103">GST on Journals where Services are Paid Directly through Cash or Bank</span><span class="sxs-lookup"><span data-stu-id="e6ecd-103">GST on Journals where Services are Paid Directly through Cash or Bank</span></span>

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="e6ecd-104">Invoice and credit memo can be posted from journals.</span><span class="sxs-lookup"><span data-stu-id="e6ecd-104">Invoice and credit memo can be posted from journals.</span></span> <span data-ttu-id="e6ecd-105">GST calculation logic for journals will be same as GST calculation for documents.</span><span class="sxs-lookup"><span data-stu-id="e6ecd-105">GST calculation logic for journals will be same as GST calculation for documents.</span></span> 

<span data-ttu-id="e6ecd-106">GST calculation process has been explained in this document.</span><span class="sxs-lookup"><span data-stu-id="e6ecd-106">GST calculation process has been explained in this document.</span></span>

## <a name="create-a-general-journal-or-a-bank-or-cash-payment-voucher"></a><span data-ttu-id="e6ecd-107">Create a general journal or a bank or cash payment voucher</span><span class="sxs-lookup"><span data-stu-id="e6ecd-107">Create a general journal or a bank or cash payment voucher</span></span>

1. <span data-ttu-id="e6ecd-108">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **General Journal** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="e6ecd-108">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **General Journal** , and then choose the related link.</span></span>
2. <span data-ttu-id="e6ecd-109">Select **G/L Account** in account type and **G/L Account** or **Bank Account** in balancing account type, and then select the cash or bank accounts.</span><span class="sxs-lookup"><span data-stu-id="e6ecd-109">Select **G/L Account** in account type and **G/L Account** or **Bank Account** in balancing account type, and then select the cash or bank accounts.</span></span>
3. <span data-ttu-id="e6ecd-110">GST (CGST/SGST/UTGST/IGST) to be calculated on Direct Expenses (Services) being paid through cash or bank, any legal fees, telephone expenses, etc.</span><span class="sxs-lookup"><span data-stu-id="e6ecd-110">GST (CGST/SGST/UTGST/IGST) to be calculated on Direct Expenses (Services) being paid through cash or bank, any legal fees, telephone expenses, etc.</span></span> 

<span data-ttu-id="e6ecd-111">For example, there is an expense of INR 10,000 and 18% GST (i.e. 9% CGST and 9% SGST/UTGST in case of Intra-State or Intra-Union Territory transaction or 18% IGST in case of Inter-State transaction) has to be charged on expense amount.</span><span class="sxs-lookup"><span data-stu-id="e6ecd-111">For example, there is an expense of INR 10,000 and 18% GST (i.e. 9% CGST and 9% SGST/UTGST in case of Intra-State or Intra-Union Territory transaction or 18% IGST in case of Inter-State transaction) has to be charged on expense amount.</span></span>

- <span data-ttu-id="e6ecd-112">GST calculation will appear in the Fact Box, as following:</span><span class="sxs-lookup"><span data-stu-id="e6ecd-112">GST calculation will appear in the Fact Box, as following:</span></span>
    
    |<span data-ttu-id="e6ecd-113">Component</span><span class="sxs-lookup"><span data-stu-id="e6ecd-113">Component</span></span>|<span data-ttu-id="e6ecd-114">Amount</span><span class="sxs-lookup"><span data-stu-id="e6ecd-114">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="e6ecd-115">**GST Base Amount**</span><span class="sxs-lookup"><span data-stu-id="e6ecd-115">**GST Base Amount**</span></span>|<span data-ttu-id="e6ecd-116">10,000</span><span class="sxs-lookup"><span data-stu-id="e6ecd-116">10,000</span></span>|  
    |<span data-ttu-id="e6ecd-117">**CGST**</span><span class="sxs-lookup"><span data-stu-id="e6ecd-117">**CGST**</span></span>|<span data-ttu-id="e6ecd-118">900</span><span class="sxs-lookup"><span data-stu-id="e6ecd-118">900</span></span>|  
    |<span data-ttu-id="e6ecd-119">**SGST**</span><span class="sxs-lookup"><span data-stu-id="e6ecd-119">**SGST**</span></span>|<span data-ttu-id="e6ecd-120">900</span><span class="sxs-lookup"><span data-stu-id="e6ecd-120">900</span></span>|
    |<span data-ttu-id="e6ecd-121">**IGST**</span><span class="sxs-lookup"><span data-stu-id="e6ecd-121">**IGST**</span></span>|<span data-ttu-id="e6ecd-122">1800</span><span class="sxs-lookup"><span data-stu-id="e6ecd-122">1800</span></span>| 

- <span data-ttu-id="e6ecd-123">GL Entries for Intra-State or Intra-Union Territory purchase of services where service provider is unregistered, will be as following:</span><span class="sxs-lookup"><span data-stu-id="e6ecd-123">GL Entries for Intra-State or Intra-Union Territory purchase of services where service provider is unregistered, will be as following:</span></span>
    
    |<span data-ttu-id="e6ecd-124">Particulars</span><span class="sxs-lookup"><span data-stu-id="e6ecd-124">Particulars</span></span>|<span data-ttu-id="e6ecd-125">Amount</span><span class="sxs-lookup"><span data-stu-id="e6ecd-125">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="e6ecd-126">**Service Account**</span><span class="sxs-lookup"><span data-stu-id="e6ecd-126">**Service Account**</span></span>|<span data-ttu-id="e6ecd-127">10000</span><span class="sxs-lookup"><span data-stu-id="e6ecd-127">10000</span></span>|  
    |<span data-ttu-id="e6ecd-128">**SGST/UTGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="e6ecd-128">**SGST/UTGST Receivable Account**</span></span>|<span data-ttu-id="e6ecd-129">900</span><span class="sxs-lookup"><span data-stu-id="e6ecd-129">900</span></span>|  
    |<span data-ttu-id="e6ecd-130">**CGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="e6ecd-130">**CGST Receivable Account**</span></span>|<span data-ttu-id="e6ecd-131">900</span><span class="sxs-lookup"><span data-stu-id="e6ecd-131">900</span></span>|
    |<span data-ttu-id="e6ecd-132">**Cash/Bank Account**</span><span class="sxs-lookup"><span data-stu-id="e6ecd-132">**Cash/Bank Account**</span></span>|<span data-ttu-id="e6ecd-133">-10000</span><span class="sxs-lookup"><span data-stu-id="e6ecd-133">-10000</span></span>|
    |<span data-ttu-id="e6ecd-134">**SGST/UTGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="e6ecd-134">**SGST/UTGST Payable Account**</span></span>|<span data-ttu-id="e6ecd-135">-900</span><span class="sxs-lookup"><span data-stu-id="e6ecd-135">-900</span></span>|
    |<span data-ttu-id="e6ecd-136">**CGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="e6ecd-136">**CGST Payable Account**</span></span>|<span data-ttu-id="e6ecd-137">-900</span><span class="sxs-lookup"><span data-stu-id="e6ecd-137">-900</span></span>|
    
- <span data-ttu-id="e6ecd-138">GL Entries for Intra-state purchase of services where service provider is registered, will be as following:</span><span class="sxs-lookup"><span data-stu-id="e6ecd-138">GL Entries for Intra-state purchase of services where service provider is registered, will be as following:</span></span>

    |<span data-ttu-id="e6ecd-139">Particulars</span><span class="sxs-lookup"><span data-stu-id="e6ecd-139">Particulars</span></span>|<span data-ttu-id="e6ecd-140">Amount</span><span class="sxs-lookup"><span data-stu-id="e6ecd-140">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="e6ecd-141">**Service Account**</span><span class="sxs-lookup"><span data-stu-id="e6ecd-141">**Service Account**</span></span>|<span data-ttu-id="e6ecd-142">10000</span><span class="sxs-lookup"><span data-stu-id="e6ecd-142">10000</span></span>| 
    |<span data-ttu-id="e6ecd-143">**CGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="e6ecd-143">**CGST Receivable Account**</span></span>|<span data-ttu-id="e6ecd-144">900</span><span class="sxs-lookup"><span data-stu-id="e6ecd-144">900</span></span>| 
    |<span data-ttu-id="e6ecd-145">**SGST/UTGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="e6ecd-145">**SGST/UTGST Receivable Account**</span></span>|<span data-ttu-id="e6ecd-146">900</span><span class="sxs-lookup"><span data-stu-id="e6ecd-146">900</span></span>| 
    |<span data-ttu-id="e6ecd-147">**Cash/Bank Account**</span><span class="sxs-lookup"><span data-stu-id="e6ecd-147">**Cash/Bank Account**</span></span>|<span data-ttu-id="e6ecd-148">-11800</span><span class="sxs-lookup"><span data-stu-id="e6ecd-148">-11800</span></span>|  

> [!TIP]
> <span data-ttu-id="e6ecd-149">In case of Inter-State purchase of services, IGST will be applicable.</span><span class="sxs-lookup"><span data-stu-id="e6ecd-149">In case of Inter-State purchase of services, IGST will be applicable.</span></span>




































