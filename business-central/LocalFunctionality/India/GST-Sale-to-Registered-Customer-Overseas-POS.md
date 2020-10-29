---
title: Sale of Services to Overseas Place of Supply to registered customer
description: Sale of Services to Overseas Place of Supply to registered customer
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 9eae41b001ebcb20342e74314da0b8674bba0c88
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948632"
---
# <a name="sale-of-services-to-overseas-place-of-supply-to-registered-customer"></a><span data-ttu-id="7f444-103">Sale of Services to Overseas Place of Supply to Registered Customer</span><span class="sxs-lookup"><span data-stu-id="7f444-103">Sale of Services to Overseas Place of Supply to Registered Customer</span></span>

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="7f444-104">GST is destination based tax i.e</span><span class="sxs-lookup"><span data-stu-id="7f444-104">GST is destination based tax i.e</span></span> <span data-ttu-id="7f444-105">consumption tax, which means tax will be levied where goods and services are consumed and will accrue to that state.</span><span class="sxs-lookup"><span data-stu-id="7f444-105">consumption tax, which means tax will be levied where goods and services are consumed and will accrue to that state.</span></span>  <span data-ttu-id="7f444-106">The supply of goods or services or both when the supplier is located in India and the place of supply is outside India shall be treated to be a supply of goods or services or both in the course of inter-state trade or commerce.</span><span class="sxs-lookup"><span data-stu-id="7f444-106">The supply of goods or services or both when the supplier is located in India and the place of supply is outside India shall be treated to be a supply of goods or services or both in the course of inter-state trade or commerce.</span></span>

<span data-ttu-id="7f444-107">Process of sale to a registered customer with overseas place of supply  has been explained in this document.</span><span class="sxs-lookup"><span data-stu-id="7f444-107">Process of sale to a registered customer with overseas place of supply  has been explained in this document.</span></span>

## <a name="create-a-sales-invoice"></a><span data-ttu-id="7f444-108">Create a sales invoice</span><span class="sxs-lookup"><span data-stu-id="7f444-108">Create a sales invoice</span></span>

1. <span data-ttu-id="7f444-109">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Sales Invoice** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="7f444-109">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Sales Invoice** , and then choose the related link.</span></span>

2. <span data-ttu-id="7f444-110">Select **Customer** on **Sales Invoice** header, GST customer type should be **Registered** .</span><span class="sxs-lookup"><span data-stu-id="7f444-110">Select **Customer** on **Sales Invoice** header, GST customer type should be **Registered** .</span></span>

3. <span data-ttu-id="7f444-111">Select **G/L Account** on **Sales Invoice** line.</span><span class="sxs-lookup"><span data-stu-id="7f444-111">Select **G/L Account** on **Sales Invoice** line.</span></span> <span data-ttu-id="7f444-112">GST Group Code, HSN/SAC Code should not be blank on the G/L Account Card.</span><span class="sxs-lookup"><span data-stu-id="7f444-112">GST Group Code, HSN/SAC Code should not be blank on the G/L Account Card.</span></span>

4. <span data-ttu-id="7f444-113">**POS Out of India** field on **Sales Invoice** header should be marked as True.</span><span class="sxs-lookup"><span data-stu-id="7f444-113">**POS Out of India** field on **Sales Invoice** header should be marked as True.</span></span> 

<span data-ttu-id="7f444-114">For example, there is a sales invoice for INR 10,000 and 18% IGST has to be charged on the invoice amount.</span><span class="sxs-lookup"><span data-stu-id="7f444-114">For example, there is a sales invoice for INR 10,000 and 18% IGST has to be charged on the invoice amount.</span></span>

- <span data-ttu-id="7f444-115">GST calculation will appear in the Fact Box, as following:</span><span class="sxs-lookup"><span data-stu-id="7f444-115">GST calculation will appear in the Fact Box, as following:</span></span>

    |<span data-ttu-id="7f444-116">Component</span><span class="sxs-lookup"><span data-stu-id="7f444-116">Component</span></span>|<span data-ttu-id="7f444-117">Amount</span><span class="sxs-lookup"><span data-stu-id="7f444-117">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="7f444-118">**GST Base Amount**</span><span class="sxs-lookup"><span data-stu-id="7f444-118">**GST Base Amount**</span></span>|<span data-ttu-id="7f444-119">10,000</span><span class="sxs-lookup"><span data-stu-id="7f444-119">10,000</span></span>|  
    |<span data-ttu-id="7f444-120">**IGST**</span><span class="sxs-lookup"><span data-stu-id="7f444-120">**IGST**</span></span>|<span data-ttu-id="7f444-121">1800</span><span class="sxs-lookup"><span data-stu-id="7f444-121">1800</span></span>|  
   

- <span data-ttu-id="7f444-122">GL Entries for Intra-State Sale of services to overseas place of supply to registered customer, will be as following:</span><span class="sxs-lookup"><span data-stu-id="7f444-122">GL Entries for Intra-State Sale of services to overseas place of supply to registered customer, will be as following:</span></span>

    |<span data-ttu-id="7f444-123">Particulars</span><span class="sxs-lookup"><span data-stu-id="7f444-123">Particulars</span></span>|<span data-ttu-id="7f444-124">Amount</span><span class="sxs-lookup"><span data-stu-id="7f444-124">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="7f444-125">**Customer Account**</span><span class="sxs-lookup"><span data-stu-id="7f444-125">**Customer Account**</span></span>|<span data-ttu-id="7f444-126">11800</span><span class="sxs-lookup"><span data-stu-id="7f444-126">11800</span></span>|  
    |<span data-ttu-id="7f444-127">**IGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="7f444-127">**IGST Payable Account**</span></span>|<span data-ttu-id="7f444-128">- 1800</span><span class="sxs-lookup"><span data-stu-id="7f444-128">- 1800</span></span>|
    |<span data-ttu-id="7f444-129">**Services Account**</span><span class="sxs-lookup"><span data-stu-id="7f444-129">**Services Account**</span></span>|<span data-ttu-id="7f444-130">- 10000</span><span class="sxs-lookup"><span data-stu-id="7f444-130">- 10000</span></span>|







































