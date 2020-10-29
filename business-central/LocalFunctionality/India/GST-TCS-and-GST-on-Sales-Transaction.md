---
title: Calculation of TCS as per the Income Tax Act, 1961 and GST on Sales Transactions
description: Calculation of TCS as per the Income Tax Act, 1961 and GST on Sales Transactions
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 46b68c39d8a7bf10d02d7075f9357a89cd668dcb
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948624"
---
# <a name="calculation-of-tcs-as-per-the-income-tax-act-1961-and-gst-on-sales-transactions"></a><span data-ttu-id="7605c-103">Calculation of TCS as per the Income Tax Act, 1961 and GST on Sales Transactions</span><span class="sxs-lookup"><span data-stu-id="7605c-103">Calculation of TCS as per the Income Tax Act, 1961 and GST on Sales Transactions</span></span>

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="7605c-104">The Government has placed the responsibility on the e-commerce operators to collect the ‘tax’ at a specified rate from the supplier.</span><span class="sxs-lookup"><span data-stu-id="7605c-104">The Government has placed the responsibility on the e-commerce operators to collect the ‘tax’ at a specified rate from the supplier.</span></span> <span data-ttu-id="7605c-105">This shall be done by the Operator by paying the supplier the price of the product or services, less the tax, calculated at the specified rate.</span><span class="sxs-lookup"><span data-stu-id="7605c-105">This shall be done by the Operator by paying the supplier the price of the product or services, less the tax, calculated at the specified rate.</span></span>

<span data-ttu-id="7605c-106">The process of calculation of TCS and GST has been explained in this document.</span><span class="sxs-lookup"><span data-stu-id="7605c-106">The process of calculation of TCS and GST has been explained in this document.</span></span>

## <a name="create-a-sales-invoice"></a><span data-ttu-id="7605c-107">Create a sales invoice</span><span class="sxs-lookup"><span data-stu-id="7605c-107">Create a sales invoice</span></span>

1. <span data-ttu-id="7605c-108">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Sales Invoice** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="7605c-108">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Sales Invoice** , and then choose the related link.</span></span>

2. <span data-ttu-id="7605c-109">Select **Customer** on **Sales Invoice** header.</span><span class="sxs-lookup"><span data-stu-id="7605c-109">Select **Customer** on **Sales Invoice** header.</span></span>

3. <span data-ttu-id="7605c-110">Select **Item** on **Sales Invoice** line.</span><span class="sxs-lookup"><span data-stu-id="7605c-110">Select **Item** on **Sales Invoice** line.</span></span> <span data-ttu-id="7605c-111">GST Group Code, HSN/SAC Code should not be blank on the Item.</span><span class="sxs-lookup"><span data-stu-id="7605c-111">GST Group Code, HSN/SAC Code should not be blank on the Item.</span></span> 

<span data-ttu-id="7605c-112">For example, there is a sales invoice for INR 10,000 and 18% GST (i.e. 9% CGST and 9% SGST/UTGST in case of Intra-State or Intra-Union Territory transaction or 18% IGST in case of Inter-State transaction) and 1% TCS as per Income Tax Act, 1961 has to be charged on the invoice amount.</span><span class="sxs-lookup"><span data-stu-id="7605c-112">For example, there is a sales invoice for INR 10,000 and 18% GST (i.e. 9% CGST and 9% SGST/UTGST in case of Intra-State or Intra-Union Territory transaction or 18% IGST in case of Inter-State transaction) and 1% TCS as per Income Tax Act, 1961 has to be charged on the invoice amount.</span></span>

-  <span data-ttu-id="7605c-113">GST calculation will appear in the Fact Box, as following:</span><span class="sxs-lookup"><span data-stu-id="7605c-113">GST calculation will appear in the Fact Box, as following:</span></span>
    
    |<span data-ttu-id="7605c-114">Component</span><span class="sxs-lookup"><span data-stu-id="7605c-114">Component</span></span>|<span data-ttu-id="7605c-115">Amount</span><span class="sxs-lookup"><span data-stu-id="7605c-115">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="7605c-116">**GST Base Amount**</span><span class="sxs-lookup"><span data-stu-id="7605c-116">**GST Base Amount**</span></span>|<span data-ttu-id="7605c-117">10,000</span><span class="sxs-lookup"><span data-stu-id="7605c-117">10,000</span></span>|  
    |<span data-ttu-id="7605c-118">**CGST**</span><span class="sxs-lookup"><span data-stu-id="7605c-118">**CGST**</span></span>|<span data-ttu-id="7605c-119">900</span><span class="sxs-lookup"><span data-stu-id="7605c-119">900</span></span>|  
    |<span data-ttu-id="7605c-120">**SGST**</span><span class="sxs-lookup"><span data-stu-id="7605c-120">**SGST**</span></span>|<span data-ttu-id="7605c-121">900</span><span class="sxs-lookup"><span data-stu-id="7605c-121">900</span></span>|
    |<span data-ttu-id="7605c-122">**TCS**</span><span class="sxs-lookup"><span data-stu-id="7605c-122">**TCS**</span></span>|<span data-ttu-id="7605c-123">100</span><span class="sxs-lookup"><span data-stu-id="7605c-123">100</span></span>|

-  <span data-ttu-id="7605c-124">On posting of sales invoice, GL Entries will be as following:</span><span class="sxs-lookup"><span data-stu-id="7605c-124">On posting of sales invoice, GL Entries will be as following:</span></span>

    |<span data-ttu-id="7605c-125">Particulars</span><span class="sxs-lookup"><span data-stu-id="7605c-125">Particulars</span></span>|<span data-ttu-id="7605c-126">Amount</span><span class="sxs-lookup"><span data-stu-id="7605c-126">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="7605c-127">**Customer Account**</span><span class="sxs-lookup"><span data-stu-id="7605c-127">**Customer Account**</span></span>|<span data-ttu-id="7605c-128">11900</span><span class="sxs-lookup"><span data-stu-id="7605c-128">11900</span></span>|  
    |<span data-ttu-id="7605c-129">**SGST/UTGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="7605c-129">**SGST/UTGST Payable Account**</span></span>|<span data-ttu-id="7605c-130">-900</span><span class="sxs-lookup"><span data-stu-id="7605c-130">-900</span></span>|  
    |<span data-ttu-id="7605c-131">**CGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="7605c-131">**CGST Payable Account**</span></span>|<span data-ttu-id="7605c-132">-900</span><span class="sxs-lookup"><span data-stu-id="7605c-132">-900</span></span>|
    |<span data-ttu-id="7605c-133">**TCS Payable Account**</span><span class="sxs-lookup"><span data-stu-id="7605c-133">**TCS Payable Account**</span></span>|<span data-ttu-id="7605c-134">-100</span><span class="sxs-lookup"><span data-stu-id="7605c-134">-100</span></span>|
    |<span data-ttu-id="7605c-135">**Sales Account**</span><span class="sxs-lookup"><span data-stu-id="7605c-135">**Sales Account**</span></span>|<span data-ttu-id="7605c-136">-10000</span><span class="sxs-lookup"><span data-stu-id="7605c-136">-10000</span></span>|

> [!TIP]
> <span data-ttu-id="7605c-137">In case of Inter-State Sales, IGST will be calculated with TCS as per the Income Tax Act, 1961.</span><span class="sxs-lookup"><span data-stu-id="7605c-137">In case of Inter-State Sales, IGST will be calculated with TCS as per the Income Tax Act, 1961.</span></span>







































