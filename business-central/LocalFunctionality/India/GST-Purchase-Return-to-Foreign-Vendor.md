---
title: Purchase Credit Memo or Return Order to Foreign Vendor
description: Purchase Credit Memo or Return Order to Foreign Vendor
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 0e2ea588fd2621660a88fc3d28d35bc5aa4ccac8
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948643"
---
# <a name="purchase-credit-memo-or-return-order-to-foreign-vendor"></a><span data-ttu-id="82e96-103">Purchase Credit Memo or Return Order to Foreign Vendor</span><span class="sxs-lookup"><span data-stu-id="82e96-103">Purchase Credit Memo or Return Order to Foreign Vendor</span></span>

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="82e96-104">Purchasing goods in India from a place outside India is import of goods.</span><span class="sxs-lookup"><span data-stu-id="82e96-104">Purchasing goods in India from a place outside India is import of goods.</span></span> <span data-ttu-id="82e96-105">For services, if the supplier is located outside India, the recipient is located in India and the place of supply is in India, then it is called Import of services.</span><span class="sxs-lookup"><span data-stu-id="82e96-105">For services, if the supplier is located outside India, the recipient is located in India and the place of supply is in India, then it is called Import of services.</span></span> <span data-ttu-id="82e96-106">Purchase of goods and/or services from a foreign vendor are subject to reverse charge i.e. the person importing goods or services is required to remit tax to the Government.</span><span class="sxs-lookup"><span data-stu-id="82e96-106">Purchase of goods and/or services from a foreign vendor are subject to reverse charge i.e. the person importing goods or services is required to remit tax to the Government.</span></span>

<span data-ttu-id="82e96-107">A buyer may have to return the goods or issue credit note due to various reasons like damaged goods, quality issues etc.</span><span class="sxs-lookup"><span data-stu-id="82e96-107">A buyer may have to return the goods or issue credit note due to various reasons like damaged goods, quality issues etc.</span></span>

<span data-ttu-id="82e96-108">Process for purchase returns to foreign vendor has been explained in this document.</span><span class="sxs-lookup"><span data-stu-id="82e96-108">Process for purchase returns to foreign vendor has been explained in this document.</span></span>

## <a name="create-a-purchase-return-order-or-credit-memo"></a><span data-ttu-id="82e96-109">Create a purchase return order or credit memo</span><span class="sxs-lookup"><span data-stu-id="82e96-109">Create a purchase return order or credit memo</span></span>

1. <span data-ttu-id="82e96-110">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Purchase Return Order or Credit Memo** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="82e96-110">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Purchase Return Order or Credit Memo** , and then choose the related link.</span></span> 
2. <span data-ttu-id="82e96-111">Select **Vendor** on **Purchase Credit Memo** header, GST vendor type should be **Import** .</span><span class="sxs-lookup"><span data-stu-id="82e96-111">Select **Vendor** on **Purchase Credit Memo** header, GST vendor type should be **Import** .</span></span>
3. <span data-ttu-id="82e96-112">Select **Item Code** for goods, **G/L Account** for Service purchase, **Fixed Asset** for Fixed Asset purchase on **Purchase Credit Memo** line.</span><span class="sxs-lookup"><span data-stu-id="82e96-112">Select **Item Code** for goods, **G/L Account** for Service purchase, **Fixed Asset** for Fixed Asset purchase on **Purchase Credit Memo** line.</span></span> <span data-ttu-id="82e96-113">GST Group Code, HSN/SAC Code and GST Credit value should be selected as **Availment** if the tax input credit is available or else **Non-Availment** on the Item, G/L Account, Fixed Asset.</span><span class="sxs-lookup"><span data-stu-id="82e96-113">GST Group Code, HSN/SAC Code and GST Credit value should be selected as **Availment** if the tax input credit is available or else **Non-Availment** on the Item, G/L Account, Fixed Asset.</span></span>
4. <span data-ttu-id="82e96-114">GST Credit option can be changed on **Purchase Credit Memo** line.</span><span class="sxs-lookup"><span data-stu-id="82e96-114">GST Credit option can be changed on **Purchase Credit Memo** line.</span></span>

- <span data-ttu-id="82e96-115">Purchase Credit Memo or Return Order for Imported Goods or Fixed asset, IGST is to be calculated on GST Assessable Value + Basic Custom Duty.</span><span class="sxs-lookup"><span data-stu-id="82e96-115">Purchase Credit Memo or Return Order for Imported Goods or Fixed asset, IGST is to be calculated on GST Assessable Value + Basic Custom Duty.</span></span> 

<span data-ttu-id="82e96-116">For example, purchase credit memo or return order is issued for INR 10000, Custom Duty INR 1000, GST Assessable Value INR 11000 (IGST @18%) has to be charged.</span><span class="sxs-lookup"><span data-stu-id="82e96-116">For example, purchase credit memo or return order is issued for INR 10000, Custom Duty INR 1000, GST Assessable Value INR 11000 (IGST @18%) has to be charged.</span></span> <span data-ttu-id="82e96-117">Calculation base:  (18% on 11,000 GST Assessable Value + 1,000 BCD) (12,000\*18%).</span><span class="sxs-lookup"><span data-stu-id="82e96-117">Calculation base:  (18% on 11,000 GST Assessable Value + 1,000 BCD) (12,000\*18%).</span></span>

  - <span data-ttu-id="82e96-118">GST calculation will appear in the Fact Box, as following:</span><span class="sxs-lookup"><span data-stu-id="82e96-118">GST calculation will appear in the Fact Box, as following:</span></span>
    
      |<span data-ttu-id="82e96-119">Component</span><span class="sxs-lookup"><span data-stu-id="82e96-119">Component</span></span>|<span data-ttu-id="82e96-120">Amount</span><span class="sxs-lookup"><span data-stu-id="82e96-120">Amount</span></span>|
      |----------------------------------|---------------------------------------|  
      |<span data-ttu-id="82e96-121">**GST Base Amount**</span><span class="sxs-lookup"><span data-stu-id="82e96-121">**GST Base Amount**</span></span>|<span data-ttu-id="82e96-122">11,000</span><span class="sxs-lookup"><span data-stu-id="82e96-122">11,000</span></span>|
      |<span data-ttu-id="82e96-123">**Custom Duty (BCD)**</span><span class="sxs-lookup"><span data-stu-id="82e96-123">**Custom Duty (BCD)**</span></span>|<span data-ttu-id="82e96-124">1000</span><span class="sxs-lookup"><span data-stu-id="82e96-124">1000</span></span>|  
      |<span data-ttu-id="82e96-125">**IGST**</span><span class="sxs-lookup"><span data-stu-id="82e96-125">**IGST**</span></span>|<span data-ttu-id="82e96-126">2160</span><span class="sxs-lookup"><span data-stu-id="82e96-126">2160</span></span>|
    
  - <span data-ttu-id="82e96-127">GL Entries for purchase credit memo or return order for imported goods or fixed asset where input tax credit is available, will be as following:</span><span class="sxs-lookup"><span data-stu-id="82e96-127">GL Entries for purchase credit memo or return order for imported goods or fixed asset where input tax credit is available, will be as following:</span></span>

      |<span data-ttu-id="82e96-128">Particulars</span><span class="sxs-lookup"><span data-stu-id="82e96-128">Particulars</span></span>|<span data-ttu-id="82e96-129">Amount</span><span class="sxs-lookup"><span data-stu-id="82e96-129">Amount</span></span>|
      |----------------------------------|---------------------------------------|
      |<span data-ttu-id="82e96-130">**Vendor Account (Transactional Value)**</span><span class="sxs-lookup"><span data-stu-id="82e96-130">**Vendor Account (Transactional Value)**</span></span>|<span data-ttu-id="82e96-131">10000</span><span class="sxs-lookup"><span data-stu-id="82e96-131">10000</span></span>|
      |<span data-ttu-id="82e96-132">**IGST Refund Account**</span><span class="sxs-lookup"><span data-stu-id="82e96-132">**IGST Refund Account**</span></span>|<span data-ttu-id="82e96-133">2160</span><span class="sxs-lookup"><span data-stu-id="82e96-133">2160</span></span>|
      |<span data-ttu-id="82e96-134">**IGST Receivable Account**</span><span class="sxs-lookup"><span data-stu-id="82e96-134">**IGST Receivable Account**</span></span>|<span data-ttu-id="82e96-135">-2160</span><span class="sxs-lookup"><span data-stu-id="82e96-135">-2160</span></span>|
      |<span data-ttu-id="82e96-136">**Purchase Account or Fixed Asset increase during the year (Transactional Value)**</span><span class="sxs-lookup"><span data-stu-id="82e96-136">**Purchase Account or Fixed Asset increase during the year (Transactional Value)**</span></span>|<span data-ttu-id="82e96-137">-10000</span><span class="sxs-lookup"><span data-stu-id="82e96-137">-10000</span></span>|

  - <span data-ttu-id="82e96-138">GL Entries for purchase credit memo or return order for imported goods or fixed asset where input tax credit is not available, will be as following:</span><span class="sxs-lookup"><span data-stu-id="82e96-138">GL Entries for purchase credit memo or return order for imported goods or fixed asset where input tax credit is not available, will be as following:</span></span>

     |<span data-ttu-id="82e96-139">Particulars</span><span class="sxs-lookup"><span data-stu-id="82e96-139">Particulars</span></span>|<span data-ttu-id="82e96-140">Amount</span><span class="sxs-lookup"><span data-stu-id="82e96-140">Amount</span></span>|
     |----------------------------------|---------------------------------------|
     |<span data-ttu-id="82e96-141">**Vendor Account (Transactional Value)**</span><span class="sxs-lookup"><span data-stu-id="82e96-141">**Vendor Account (Transactional Value)**</span></span>|<span data-ttu-id="82e96-142">10000</span><span class="sxs-lookup"><span data-stu-id="82e96-142">10000</span></span>|
     |<span data-ttu-id="82e96-143">**IGST Refund Account**</span><span class="sxs-lookup"><span data-stu-id="82e96-143">**IGST Refund Account**</span></span>|<span data-ttu-id="82e96-144">2160</span><span class="sxs-lookup"><span data-stu-id="82e96-144">2160</span></span>| 
     |<span data-ttu-id="82e96-145">**Purchase Account or Fixed Asset increase during the year (Transactional Value)**</span><span class="sxs-lookup"><span data-stu-id="82e96-145">**Purchase Account or Fixed Asset increase during the year (Transactional Value)**</span></span>|<span data-ttu-id="82e96-146">-12160</span><span class="sxs-lookup"><span data-stu-id="82e96-146">-12160</span></span>|







































