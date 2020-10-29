---
title: E-Way Bill
description: E-Way Bill
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: b8027072a2ff2310a464b269c85973690a3bece9
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948654"
---
# <a name="e-way-bill"></a><span data-ttu-id="aaeb0-103">E-Way Bill</span><span class="sxs-lookup"><span data-stu-id="aaeb0-103">E-Way Bill</span></span>

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="aaeb0-104">An electronic way bill or e-Way Bill is essential for the transport of goods that are worth more than INR 50,000.</span><span class="sxs-lookup"><span data-stu-id="aaeb0-104">An electronic way bill or e-Way Bill is essential for the transport of goods that are worth more than INR 50,000.</span></span> <span data-ttu-id="aaeb0-105">There are also some goods for which an e-way bill is essential even if the amount does not exceed INR 50,000.</span><span class="sxs-lookup"><span data-stu-id="aaeb0-105">There are also some goods for which an e-way bill is essential even if the amount does not exceed INR 50,000.</span></span> <span data-ttu-id="aaeb0-106">E-Way Bill Template is designed to meet the formats or requirements provided by government.</span><span class="sxs-lookup"><span data-stu-id="aaeb0-106">E-Way Bill Template is designed to meet the formats or requirements provided by government.</span></span> 

- <span data-ttu-id="aaeb0-107">Business user will be able to generate excel file from system which will be helpful for them to enter data into E-Waybill JSON Preparation tool.</span><span class="sxs-lookup"><span data-stu-id="aaeb0-107">Business user will be able to generate excel file from system which will be helpful for them to enter data into E-Waybill JSON Preparation tool.</span></span> <span data-ttu-id="aaeb0-108">Business user can copy and paste data from excel sheet exported from system to preparation tool.</span><span class="sxs-lookup"><span data-stu-id="aaeb0-108">Business user can copy and paste data from excel sheet exported from system to preparation tool.</span></span>
- <span data-ttu-id="aaeb0-109">Transactions posted through Journals will not be a part of E-Waybill template report.</span><span class="sxs-lookup"><span data-stu-id="aaeb0-109">Transactions posted through Journals will not be a part of E-Waybill template report.</span></span> <span data-ttu-id="aaeb0-110">User will be able to generate E-Waybill template against transactions posted from documents only.</span><span class="sxs-lookup"><span data-stu-id="aaeb0-110">User will be able to generate E-Waybill template against transactions posted from documents only.</span></span>
- <span data-ttu-id="aaeb0-111">User will be able to generate E-Waybill for movement of goods for Transfers (shipment), Sales and Purchase transactions.</span><span class="sxs-lookup"><span data-stu-id="aaeb0-111">User will be able to generate E-Waybill for movement of goods for Transfers (shipment), Sales and Purchase transactions.</span></span> <span data-ttu-id="aaeb0-112">System will only consider Items and FA with GST Group Type as 'Goods' in this report.</span><span class="sxs-lookup"><span data-stu-id="aaeb0-112">System will only consider Items and FA with GST Group Type as 'Goods' in this report.</span></span>


## <a name="e-way-bill-template-generation"></a><span data-ttu-id="aaeb0-113">E-Way Bill template generation</span><span class="sxs-lookup"><span data-stu-id="aaeb0-113">E-Way Bill template generation</span></span>

- <span data-ttu-id="aaeb0-114">E-Way Bill template feature enables the user to generate excel file from system which will be helpful for them to enter data into E-Waybill JSON Preparation tool.</span><span class="sxs-lookup"><span data-stu-id="aaeb0-114">E-Way Bill template feature enables the user to generate excel file from system which will be helpful for them to enter data into E-Waybill JSON Preparation tool.</span></span>

  1. <span data-ttu-id="aaeb0-115">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **E-Way Bill File Format** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="aaeb0-115">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **E-Way Bill File Format** , and then choose the related link.</span></span>
  2. <span data-ttu-id="aaeb0-116">GST Registration No. and State Code should be updated for **Shipping Agent** .</span><span class="sxs-lookup"><span data-stu-id="aaeb0-116">GST Registration No. and State Code should be updated for **Shipping Agent** .</span></span>
  3. <span data-ttu-id="aaeb0-117">Transportation Mode field should not be blank in **Transport Method**</span><span class="sxs-lookup"><span data-stu-id="aaeb0-117">Transportation Mode field should not be blank in **Transport Method**</span></span>
  4. <span data-ttu-id="aaeb0-118">Select the following information in the request page and click OK to generate the report</span><span class="sxs-lookup"><span data-stu-id="aaeb0-118">Select the following information in the request page and click OK to generate the report</span></span>

     |<span data-ttu-id="aaeb0-119">Field</span><span class="sxs-lookup"><span data-stu-id="aaeb0-119">Field</span></span>|<span data-ttu-id="aaeb0-120">Description</span><span class="sxs-lookup"><span data-stu-id="aaeb0-120">Description</span></span>|
     |---------|---------|
     |<span data-ttu-id="aaeb0-121">**Start Date**</span><span class="sxs-lookup"><span data-stu-id="aaeb0-121">**Start Date**</span></span>|<span data-ttu-id="aaeb0-122">Specifies the starting date of the report.</span><span class="sxs-lookup"><span data-stu-id="aaeb0-122">Specifies the starting date of the report.</span></span>|
     |<span data-ttu-id="aaeb0-123">**End Date**</span><span class="sxs-lookup"><span data-stu-id="aaeb0-123">**End Date**</span></span>|<span data-ttu-id="aaeb0-124">Specifies the ending date of the report.</span><span class="sxs-lookup"><span data-stu-id="aaeb0-124">Specifies the ending date of the report.</span></span>|
     |<span data-ttu-id="aaeb0-125">**Location Registration No.**</span><span class="sxs-lookup"><span data-stu-id="aaeb0-125">**Location Registration No.**</span></span>|<span data-ttu-id="aaeb0-126">Specifies the GST registration number for which report will be generated.</span><span class="sxs-lookup"><span data-stu-id="aaeb0-126">Specifies the GST registration number for which report will be generated.</span></span>|
     |<span data-ttu-id="aaeb0-127">**Transaction Type**</span><span class="sxs-lookup"><span data-stu-id="aaeb0-127">**Transaction Type**</span></span>|<span data-ttu-id="aaeb0-128">Select the relevant Transaction Type.</span><span class="sxs-lookup"><span data-stu-id="aaeb0-128">Select the relevant Transaction Type.</span></span>|
     |<span data-ttu-id="aaeb0-129">**Source Type**</span><span class="sxs-lookup"><span data-stu-id="aaeb0-129">**Source Type**</span></span>|<span data-ttu-id="aaeb0-130">Specify the relevant source type.</span><span class="sxs-lookup"><span data-stu-id="aaeb0-130">Specify the relevant source type.</span></span>|
     |<span data-ttu-id="aaeb0-131">**Source No.**</span><span class="sxs-lookup"><span data-stu-id="aaeb0-131">**Source No.**</span></span>|<span data-ttu-id="aaeb0-132">Specify the relevant source number.</span><span class="sxs-lookup"><span data-stu-id="aaeb0-132">Specify the relevant source number.</span></span>|




