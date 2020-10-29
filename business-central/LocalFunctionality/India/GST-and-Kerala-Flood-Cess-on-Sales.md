---
title: GST and Kerala Flood Cess on Sales Transaction
description: GST and Kerala Flood Cess on Sales Transaction
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 08349a18e578064b33f152130735f524d5f55dfb
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948618"
---
# <a name="gst-and-kerala-flood-cess-on-sales-transaction"></a><span data-ttu-id="40784-103">GST and Kerala Flood Cess on Sales Transaction</span><span class="sxs-lookup"><span data-stu-id="40784-103">GST and Kerala Flood Cess on Sales Transaction</span></span>

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="40784-104">Kerala Flood CESS (KFC) is applicable on all intra-state supplies of goods and/or services, made by taxable person to an unregistered person i.e. B2C supplies.</span><span class="sxs-lookup"><span data-stu-id="40784-104">Kerala Flood CESS (KFC) is applicable on all intra-state supplies of goods and/or services, made by taxable person to an unregistered person i.e. B2C supplies.</span></span> <span data-ttu-id="40784-105">Kerala Flood CESS is required to be shown separately on the invoice.</span><span class="sxs-lookup"><span data-stu-id="40784-105">Kerala Flood CESS is required to be shown separately on the invoice.</span></span>

## <a name="create-a-sales-invoice"></a><span data-ttu-id="40784-106">Create a sales invoice</span><span class="sxs-lookup"><span data-stu-id="40784-106">Create a sales invoice</span></span>

1. <span data-ttu-id="40784-107">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Sales Invoice** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="40784-107">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Sales Invoice** , and then choose the related link.</span></span>

2. <span data-ttu-id="40784-108">Select **Customer** on **Sales Invoice** header, GST customer type should be **Unregistered** .</span><span class="sxs-lookup"><span data-stu-id="40784-108">Select **Customer** on **Sales Invoice** header, GST customer type should be **Unregistered** .</span></span>

3. <span data-ttu-id="40784-109">Select **Item Code** for goods or **G/L Account** for service sales on **Sales Invoice** line.</span><span class="sxs-lookup"><span data-stu-id="40784-109">Select **Item Code** for goods or **G/L Account** for service sales on **Sales Invoice** line.</span></span> <span data-ttu-id="40784-110">GST Group Code, HSN/SAC Code should not be blank on **Item** or **G/L Account** .</span><span class="sxs-lookup"><span data-stu-id="40784-110">GST Group Code, HSN/SAC Code should not be blank on **Item** or **G/L Account** .</span></span> 

<span data-ttu-id="40784-111">For example, there is a sales invoice for INR 10,000 and 18% GST (i.e. 9% CGST and 9% SGST/UTGST in case of Intra-State or Intra-Union Territory transaction) and 1% Kerala Flood Cess has to be charged on the invoice amount.</span><span class="sxs-lookup"><span data-stu-id="40784-111">For example, there is a sales invoice for INR 10,000 and 18% GST (i.e. 9% CGST and 9% SGST/UTGST in case of Intra-State or Intra-Union Territory transaction) and 1% Kerala Flood Cess has to be charged on the invoice amount.</span></span>

-  <span data-ttu-id="40784-112">GST calculation will appear in the Fact Box, as following:</span><span class="sxs-lookup"><span data-stu-id="40784-112">GST calculation will appear in the Fact Box, as following:</span></span>
    
    |<span data-ttu-id="40784-113">Component</span><span class="sxs-lookup"><span data-stu-id="40784-113">Component</span></span>|<span data-ttu-id="40784-114">Amount</span><span class="sxs-lookup"><span data-stu-id="40784-114">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="40784-115">**GST Base Amount**</span><span class="sxs-lookup"><span data-stu-id="40784-115">**GST Base Amount**</span></span>|<span data-ttu-id="40784-116">10,000</span><span class="sxs-lookup"><span data-stu-id="40784-116">10,000</span></span>|  
    |<span data-ttu-id="40784-117">**CGST**</span><span class="sxs-lookup"><span data-stu-id="40784-117">**CGST**</span></span>|<span data-ttu-id="40784-118">900</span><span class="sxs-lookup"><span data-stu-id="40784-118">900</span></span>|  
    |<span data-ttu-id="40784-119">**SGST**</span><span class="sxs-lookup"><span data-stu-id="40784-119">**SGST**</span></span>|<span data-ttu-id="40784-120">900</span><span class="sxs-lookup"><span data-stu-id="40784-120">900</span></span>|
    |<span data-ttu-id="40784-121">**KFC**</span><span class="sxs-lookup"><span data-stu-id="40784-121">**KFC**</span></span>|<span data-ttu-id="40784-122">100</span><span class="sxs-lookup"><span data-stu-id="40784-122">100</span></span>|

- <span data-ttu-id="40784-123">On posting the sales invoice for Intra-State or Intra-Union Territory sale of goods to unregistered customer, GL Entries will be as following:</span><span class="sxs-lookup"><span data-stu-id="40784-123">On posting the sales invoice for Intra-State or Intra-Union Territory sale of goods to unregistered customer, GL Entries will be as following:</span></span>

    |<span data-ttu-id="40784-124">Particulars</span><span class="sxs-lookup"><span data-stu-id="40784-124">Particulars</span></span>|<span data-ttu-id="40784-125">Amount</span><span class="sxs-lookup"><span data-stu-id="40784-125">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="40784-126">**Customer Account**</span><span class="sxs-lookup"><span data-stu-id="40784-126">**Customer Account**</span></span>|<span data-ttu-id="40784-127">13700</span><span class="sxs-lookup"><span data-stu-id="40784-127">13700</span></span>|  
    |<span data-ttu-id="40784-128">**SGST/UTGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="40784-128">**SGST/UTGST Payable Account**</span></span>|<span data-ttu-id="40784-129">-1800</span><span class="sxs-lookup"><span data-stu-id="40784-129">-1800</span></span>|  
    |<span data-ttu-id="40784-130">**CGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="40784-130">**CGST Payable Account**</span></span>|<span data-ttu-id="40784-131">-1800</span><span class="sxs-lookup"><span data-stu-id="40784-131">-1800</span></span>|
    |<span data-ttu-id="40784-132">**Kerala Flood Cess**</span><span class="sxs-lookup"><span data-stu-id="40784-132">**Kerala Flood Cess**</span></span>|<span data-ttu-id="40784-133">-100</span><span class="sxs-lookup"><span data-stu-id="40784-133">-100</span></span>|
    |<span data-ttu-id="40784-134">**Sales Account**</span><span class="sxs-lookup"><span data-stu-id="40784-134">**Sales Account**</span></span>|<span data-ttu-id="40784-135">-10000</span><span class="sxs-lookup"><span data-stu-id="40784-135">-10000</span></span>|


> [!TIP]
> <span data-ttu-id="40784-136">System will automatically update 'Nature of Supply' B2C for Unregistered Customer.</span><span class="sxs-lookup"><span data-stu-id="40784-136">System will automatically update 'Nature of Supply' B2C for Unregistered Customer.</span></span>





































