---
title: Export of Goods and/or Services to Foreign Customer
description: Export of Goods and Services to Foreign Customer
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 9282b0819b5b8702f889683e71db2f6a7945e95d
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948635"
---
# <a name="export-of-goods-and-services-to-foreign-customer"></a><span data-ttu-id="ac316-103">Export of Goods and Services to Foreign Customer</span><span class="sxs-lookup"><span data-stu-id="ac316-103">Export of Goods and Services to Foreign Customer</span></span>

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="ac316-104">Export of goods is defined as taking goods out of India to a place outside India.</span><span class="sxs-lookup"><span data-stu-id="ac316-104">Export of goods is defined as taking goods out of India to a place outside India.</span></span> <span data-ttu-id="ac316-105">Export of services means the supply of services where the supplier of service is located in India, recipient of service is located outside India and the place of supply is outside India.</span><span class="sxs-lookup"><span data-stu-id="ac316-105">Export of services means the supply of services where the supplier of service is located in India, recipient of service is located outside India and the place of supply is outside India.</span></span> <span data-ttu-id="ac316-106">Exports can be without Payment of duty or with payment of duty.</span><span class="sxs-lookup"><span data-stu-id="ac316-106">Exports can be without Payment of duty or with payment of duty.</span></span>
 
<span data-ttu-id="ac316-107">Process of sale to foreign customer has been explained in this document.</span><span class="sxs-lookup"><span data-stu-id="ac316-107">Process of sale to foreign customer has been explained in this document.</span></span>

## <a name="create-a-sales-invoice"></a><span data-ttu-id="ac316-108">Create a sales invoice</span><span class="sxs-lookup"><span data-stu-id="ac316-108">Create a sales invoice</span></span>

1. <span data-ttu-id="ac316-109">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Sales Invoice** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="ac316-109">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Sales Invoice** , and then choose the related link.</span></span>
2. <span data-ttu-id="ac316-110">Select **Customer** on **Sales Invoice** header, GST customer type should be **Export** or **Deemed Export** or **SEZ Development** or **SEZ Unit** .</span><span class="sxs-lookup"><span data-stu-id="ac316-110">Select **Customer** on **Sales Invoice** header, GST customer type should be **Export** or **Deemed Export** or **SEZ Development** or **SEZ Unit** .</span></span>
3. <span data-ttu-id="ac316-111">Select **G/L Account** or **Item Code** on **Sales Invoice** line.</span><span class="sxs-lookup"><span data-stu-id="ac316-111">Select **G/L Account** or **Item Code** on **Sales Invoice** line.</span></span> <span data-ttu-id="ac316-112">GST Group Code, HSN/SAC Code should not be blank on the G/L Account or Item Card.</span><span class="sxs-lookup"><span data-stu-id="ac316-112">GST Group Code, HSN/SAC Code should not be blank on the G/L Account or Item Card.</span></span> 

<span data-ttu-id="ac316-113">For example, there is a sales invoice for INR 10,000 and 18% IGST has to be charged on the invoice amount.</span><span class="sxs-lookup"><span data-stu-id="ac316-113">For example, there is a sales invoice for INR 10,000 and 18% IGST has to be charged on the invoice amount.</span></span>
- <span data-ttu-id="ac316-114">GST calculation will appear in the Fact Box, as following:</span><span class="sxs-lookup"><span data-stu-id="ac316-114">GST calculation will appear in the Fact Box, as following:</span></span>
    
    |<span data-ttu-id="ac316-115">Component</span><span class="sxs-lookup"><span data-stu-id="ac316-115">Component</span></span>|<span data-ttu-id="ac316-116">Amount</span><span class="sxs-lookup"><span data-stu-id="ac316-116">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="ac316-117">**GST Base Amount**</span><span class="sxs-lookup"><span data-stu-id="ac316-117">**GST Base Amount**</span></span>|<span data-ttu-id="ac316-118">10,000</span><span class="sxs-lookup"><span data-stu-id="ac316-118">10,000</span></span>|  
    |<span data-ttu-id="ac316-119">**IGST**</span><span class="sxs-lookup"><span data-stu-id="ac316-119">**IGST**</span></span>|<span data-ttu-id="ac316-120">1800</span><span class="sxs-lookup"><span data-stu-id="ac316-120">1800</span></span>|  
    
- <span data-ttu-id="ac316-121">GL Entries for export of goods and/or services with payment of duty to Foreign Customer, SEZ Unit, SEZ Development Customer will be as following:</span><span class="sxs-lookup"><span data-stu-id="ac316-121">GL Entries for export of goods and/or services with payment of duty to Foreign Customer, SEZ Unit, SEZ Development Customer will be as following:</span></span>

    |<span data-ttu-id="ac316-122">Particulars</span><span class="sxs-lookup"><span data-stu-id="ac316-122">Particulars</span></span>|<span data-ttu-id="ac316-123">Amount</span><span class="sxs-lookup"><span data-stu-id="ac316-123">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="ac316-124">**Customer Account**</span><span class="sxs-lookup"><span data-stu-id="ac316-124">**Customer Account**</span></span>|<span data-ttu-id="ac316-125">10,000</span><span class="sxs-lookup"><span data-stu-id="ac316-125">10,000</span></span>|  
    |<span data-ttu-id="ac316-126">**IGST Refund Account**</span><span class="sxs-lookup"><span data-stu-id="ac316-126">**IGST Refund Account**</span></span>|<span data-ttu-id="ac316-127">1800</span><span class="sxs-lookup"><span data-stu-id="ac316-127">1800</span></span>|
    |<span data-ttu-id="ac316-128">**IGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="ac316-128">**IGST Payable Account**</span></span>|<span data-ttu-id="ac316-129">-1800</span><span class="sxs-lookup"><span data-stu-id="ac316-129">-1800</span></span>|
    |<span data-ttu-id="ac316-130">**Sales Account**</span><span class="sxs-lookup"><span data-stu-id="ac316-130">**Sales Account**</span></span>|<span data-ttu-id="ac316-131">-10000</span><span class="sxs-lookup"><span data-stu-id="ac316-131">-10000</span></span>|

- <span data-ttu-id="ac316-132">GL Entries for export of goods and/or services without payment of duty to Foreign Customer, SEZ Unit, SEZ Development Customer will be as following:</span><span class="sxs-lookup"><span data-stu-id="ac316-132">GL Entries for export of goods and/or services without payment of duty to Foreign Customer, SEZ Unit, SEZ Development Customer will be as following:</span></span>

    |<span data-ttu-id="ac316-133">Particulars</span><span class="sxs-lookup"><span data-stu-id="ac316-133">Particulars</span></span>|<span data-ttu-id="ac316-134">Amount</span><span class="sxs-lookup"><span data-stu-id="ac316-134">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="ac316-135">**Customer Account**</span><span class="sxs-lookup"><span data-stu-id="ac316-135">**Customer Account**</span></span>|<span data-ttu-id="ac316-136">10,000</span><span class="sxs-lookup"><span data-stu-id="ac316-136">10,000</span></span>|  
    |<span data-ttu-id="ac316-137">**Sales Account**</span><span class="sxs-lookup"><span data-stu-id="ac316-137">**Sales Account**</span></span>|<span data-ttu-id="ac316-138">-10000</span><span class="sxs-lookup"><span data-stu-id="ac316-138">-10000</span></span>|


> [!NOTE]
> <span data-ttu-id="ac316-139">Export or Deemed export will have same treatment, as it is treated as interstate transaction and only IGST is applicable irrespective of location of receiver.</span><span class="sxs-lookup"><span data-stu-id="ac316-139">Export or Deemed export will have same treatment, as it is treated as interstate transaction and only IGST is applicable irrespective of location of receiver.</span></span> <span data-ttu-id="ac316-140">There is no scenario of deemed export without payment of Duty, as company has to pay IGST and claim refund.</span><span class="sxs-lookup"><span data-stu-id="ac316-140">There is no scenario of deemed export without payment of Duty, as company has to pay IGST and claim refund.</span></span> <span data-ttu-id="ac316-141">Refund can be claimed either by seller or recipient.</span><span class="sxs-lookup"><span data-stu-id="ac316-141">Refund can be claimed either by seller or recipient.</span></span>







































