---
title: Return or Credit Note of Services for Overseas Place of Supply to Registered Customer
description: Return or Credit Note of Services for Overseas Place of Supply to Registered Customer
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: e20194f0de3ab41b9b2b65ff37cb1e14f30968d9
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948631"
---
# <a name="return-or-credit-note-of-services-for-overseas-place-of-supply-to-registered-customer"></a><span data-ttu-id="e2bd1-103">Return or Credit Note of Services for Overseas Place of Supply to Registered Customer</span><span class="sxs-lookup"><span data-stu-id="e2bd1-103">Return or Credit Note of Services for Overseas Place of Supply to Registered Customer</span></span>

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="e2bd1-104">GST is destination based tax i.e</span><span class="sxs-lookup"><span data-stu-id="e2bd1-104">GST is destination based tax i.e</span></span> <span data-ttu-id="e2bd1-105">consumption tax, which means tax will be levied where goods and services are consumed and will accrue to that state.</span><span class="sxs-lookup"><span data-stu-id="e2bd1-105">consumption tax, which means tax will be levied where goods and services are consumed and will accrue to that state.</span></span>  <span data-ttu-id="e2bd1-106">The supply of goods or services or both when the supplier is located in India and the place of supply is outside India shall be treated to be a supply of goods or services or both in the course of inter-state trade or commerce.</span><span class="sxs-lookup"><span data-stu-id="e2bd1-106">The supply of goods or services or both when the supplier is located in India and the place of supply is outside India shall be treated to be a supply of goods or services or both in the course of inter-state trade or commerce.</span></span> 

<span data-ttu-id="e2bd1-107">A customer may require to return the goods or issue credit note due to various reasons like damaged goods, quality issues etc.</span><span class="sxs-lookup"><span data-stu-id="e2bd1-107">A customer may require to return the goods or issue credit note due to various reasons like damaged goods, quality issues etc.</span></span>

<span data-ttu-id="e2bd1-108">Process of sale return from a registered customer with overseas place of supply  has been explained in this document.</span><span class="sxs-lookup"><span data-stu-id="e2bd1-108">Process of sale return from a registered customer with overseas place of supply  has been explained in this document.</span></span>

## <a name="create-a-sales-return-order-or-credit-memo"></a><span data-ttu-id="e2bd1-109">Create a sales return order or credit memo</span><span class="sxs-lookup"><span data-stu-id="e2bd1-109">Create a sales return order or credit memo</span></span>

1. <span data-ttu-id="e2bd1-110">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Sales Return Order** or **Sales Credit Memo** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="e2bd1-110">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Sales Return Order** or **Sales Credit Memo** , and then choose the related link.</span></span> 
2. <span data-ttu-id="e2bd1-111">Select **Customer** on **Sales Return Order** or **Sales Credit Memo** header, GST customer type should be **Registered** .</span><span class="sxs-lookup"><span data-stu-id="e2bd1-111">Select **Customer** on **Sales Return Order** or **Sales Credit Memo** header, GST customer type should be **Registered** .</span></span>
3. <span data-ttu-id="e2bd1-112">Select **G/L Account** on **Sales Return Order** or **Sales Credit Memo** line.</span><span class="sxs-lookup"><span data-stu-id="e2bd1-112">Select **G/L Account** on **Sales Return Order** or **Sales Credit Memo** line.</span></span> <span data-ttu-id="e2bd1-113">GST Group Code, HSN/SAC Code should not be blank on the G/L Account.</span><span class="sxs-lookup"><span data-stu-id="e2bd1-113">GST Group Code, HSN/SAC Code should not be blank on the G/L Account.</span></span>
4. <span data-ttu-id="e2bd1-114">**POS Out of India** field on **Sales Return Order** or **Sales Credit Memo** header should be marked as True.</span><span class="sxs-lookup"><span data-stu-id="e2bd1-114">**POS Out of India** field on **Sales Return Order** or **Sales Credit Memo** header should be marked as True.</span></span> 

<span data-ttu-id="e2bd1-115">For example, there is a sales credit memo for INR 10,000 and 18% IGST has to be charged on the credit memo amount.</span><span class="sxs-lookup"><span data-stu-id="e2bd1-115">For example, there is a sales credit memo for INR 10,000 and 18% IGST has to be charged on the credit memo amount.</span></span>

- <span data-ttu-id="e2bd1-116">GST calculation will appear in the Fact Box, as following:</span><span class="sxs-lookup"><span data-stu-id="e2bd1-116">GST calculation will appear in the Fact Box, as following:</span></span>

    |<span data-ttu-id="e2bd1-117">Component</span><span class="sxs-lookup"><span data-stu-id="e2bd1-117">Component</span></span>|<span data-ttu-id="e2bd1-118">Amount</span><span class="sxs-lookup"><span data-stu-id="e2bd1-118">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="e2bd1-119">**GST Base Amount**</span><span class="sxs-lookup"><span data-stu-id="e2bd1-119">**GST Base Amount**</span></span>|<span data-ttu-id="e2bd1-120">10,000</span><span class="sxs-lookup"><span data-stu-id="e2bd1-120">10,000</span></span>|  
    |<span data-ttu-id="e2bd1-121">**IGST**</span><span class="sxs-lookup"><span data-stu-id="e2bd1-121">**IGST**</span></span>|<span data-ttu-id="e2bd1-122">1800</span><span class="sxs-lookup"><span data-stu-id="e2bd1-122">1800</span></span>|  
  
- <span data-ttu-id="e2bd1-123">GL Entries for Intra-State Return or Credit Note of services for overseas place of supply to registered customer, will be as following:</span><span class="sxs-lookup"><span data-stu-id="e2bd1-123">GL Entries for Intra-State Return or Credit Note of services for overseas place of supply to registered customer, will be as following:</span></span>

    |<span data-ttu-id="e2bd1-124">Particulars</span><span class="sxs-lookup"><span data-stu-id="e2bd1-124">Particulars</span></span>|<span data-ttu-id="e2bd1-125">Amount</span><span class="sxs-lookup"><span data-stu-id="e2bd1-125">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="e2bd1-126">**Service Account**</span><span class="sxs-lookup"><span data-stu-id="e2bd1-126">**Service Account**</span></span>|<span data-ttu-id="e2bd1-127">10000</span><span class="sxs-lookup"><span data-stu-id="e2bd1-127">10000</span></span>|  
    |<span data-ttu-id="e2bd1-128">**IGST Payable Account**</span><span class="sxs-lookup"><span data-stu-id="e2bd1-128">**IGST Payable Account**</span></span>|<span data-ttu-id="e2bd1-129">1800</span><span class="sxs-lookup"><span data-stu-id="e2bd1-129">1800</span></span>|
    |<span data-ttu-id="e2bd1-130">**Customer Account**</span><span class="sxs-lookup"><span data-stu-id="e2bd1-130">**Customer Account**</span></span>|<span data-ttu-id="e2bd1-131">-11800</span><span class="sxs-lookup"><span data-stu-id="e2bd1-131">-11800</span></span>|







































