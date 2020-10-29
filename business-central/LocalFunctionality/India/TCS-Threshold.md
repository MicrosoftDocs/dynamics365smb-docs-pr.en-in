---
title: TCS calculation considering threshold limits
description: TCS calculation considering threshold limits
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 434abe1d38ccb5703928d8059227e8dcffa5eac2
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948614"
---
# <a name="tcs-with-threshold"></a><span data-ttu-id="83e2c-103">TCS with Threshold</span><span class="sxs-lookup"><span data-stu-id="83e2c-103">TCS with Threshold</span></span>

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="83e2c-104">This topic explains the requirement of threshold amount in TCS and  the process of calculating TCS for such transactions.</span><span class="sxs-lookup"><span data-stu-id="83e2c-104">This topic explains the requirement of threshold amount in TCS and  the process of calculating TCS for such transactions.</span></span>

## <a name="tcs-calculation-considering-threshold-limits"></a><span data-ttu-id="83e2c-105">TCS calculation considering threshold limits</span><span class="sxs-lookup"><span data-stu-id="83e2c-105">TCS calculation considering threshold limits</span></span>

<span data-ttu-id="83e2c-106">TCS threshold defines the threshold limit for each TCS Nature of Collection.</span><span class="sxs-lookup"><span data-stu-id="83e2c-106">TCS threshold defines the threshold limit for each TCS Nature of Collection.</span></span>  <span data-ttu-id="83e2c-107">TCS can be deducted only if the total transaction with the assessee exceeds the threshold limit in the financial year.</span><span class="sxs-lookup"><span data-stu-id="83e2c-107">TCS can be deducted only if the total transaction with the assessee exceeds the threshold limit in the financial year.</span></span>

<span data-ttu-id="83e2c-108">If a payment under TCS Type A is below Threshold INR 20,000, no tax will be collected.</span><span class="sxs-lookup"><span data-stu-id="83e2c-108">If a payment under TCS Type A is below Threshold INR 20,000, no tax will be collected.</span></span> <span data-ttu-id="83e2c-109">Another factor to be considered is the aggregate of total payments to be made in a year.</span><span class="sxs-lookup"><span data-stu-id="83e2c-109">Another factor to be considered is the aggregate of total payments to be made in a year.</span></span> <span data-ttu-id="83e2c-110">If for a customer it is expected that the threshold limit would be crossed eventually, it means Threshold is overlooked.</span><span class="sxs-lookup"><span data-stu-id="83e2c-110">If for a customer it is expected that the threshold limit would be crossed eventually, it means Threshold is overlooked.</span></span> <span data-ttu-id="83e2c-111">Hence, payments received from customers can cross the TCS threshold of INR 20,000.</span><span class="sxs-lookup"><span data-stu-id="83e2c-111">Hence, payments received from customers can cross the TCS threshold of INR 20,000.</span></span> <span data-ttu-id="83e2c-112">However, if the payment expected is below the threshold limit defined, TCS will not be collected.</span><span class="sxs-lookup"><span data-stu-id="83e2c-112">However, if the payment expected is below the threshold limit defined, TCS will not be collected.</span></span>

1. <span data-ttu-id="83e2c-113">GL Entries for TCS where payment is less than the threshold limits, will be as following:</span><span class="sxs-lookup"><span data-stu-id="83e2c-113">GL Entries for TCS where payment is less than the threshold limits, will be as following:</span></span>
    
    |<span data-ttu-id="83e2c-114">Particulars</span><span class="sxs-lookup"><span data-stu-id="83e2c-114">Particulars</span></span>|<span data-ttu-id="83e2c-115">Amount</span><span class="sxs-lookup"><span data-stu-id="83e2c-115">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="83e2c-116">**Customer Account**</span><span class="sxs-lookup"><span data-stu-id="83e2c-116">**Customer Account**</span></span>|<span data-ttu-id="83e2c-117">19000</span><span class="sxs-lookup"><span data-stu-id="83e2c-117">19000</span></span>|
    |<span data-ttu-id="83e2c-118">**Sales Account**</span><span class="sxs-lookup"><span data-stu-id="83e2c-118">**Sales Account**</span></span>|<span data-ttu-id="83e2c-119">-19000</span><span class="sxs-lookup"><span data-stu-id="83e2c-119">-19000</span></span>|

2. <span data-ttu-id="83e2c-120">GL Entries for TCS where payment is more than (exceeding) Threshold limits, will be as following:</span><span class="sxs-lookup"><span data-stu-id="83e2c-120">GL Entries for TCS where payment is more than (exceeding) Threshold limits, will be as following:</span></span>

    |<span data-ttu-id="83e2c-121">Particulars</span><span class="sxs-lookup"><span data-stu-id="83e2c-121">Particulars</span></span>|<span data-ttu-id="83e2c-122">Amount</span><span class="sxs-lookup"><span data-stu-id="83e2c-122">Amount</span></span>|
    |----------------------------------|---------------------------------------|  
    |<span data-ttu-id="83e2c-123">**Bank Account**</span><span class="sxs-lookup"><span data-stu-id="83e2c-123">**Bank Account**</span></span>|<span data-ttu-id="83e2c-124">10000</span><span class="sxs-lookup"><span data-stu-id="83e2c-124">10000</span></span>| 
    |<span data-ttu-id="83e2c-125">**TCS Payable Account**</span><span class="sxs-lookup"><span data-stu-id="83e2c-125">**TCS Payable Account**</span></span>|<span data-ttu-id="83e2c-126">287</span><span class="sxs-lookup"><span data-stu-id="83e2c-126">287</span></span>| 
    |<span data-ttu-id="83e2c-127">**Customer Account**</span><span class="sxs-lookup"><span data-stu-id="83e2c-127">**Customer Account**</span></span>|<span data-ttu-id="83e2c-128">-9713</span><span class="sxs-lookup"><span data-stu-id="83e2c-128">-9713</span></span>|





































