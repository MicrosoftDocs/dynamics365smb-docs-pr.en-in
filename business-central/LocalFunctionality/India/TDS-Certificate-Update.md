---
title: TDS Certificate Tracking
description: Specifies the TDS Certificate Tracking
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 2b12ae2c17d10be20a71f927ca2b54ef102048a8
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948610"
---
# <a name="tds-certificate-tracking"></a><span data-ttu-id="0d3ca-103">TDS Certificate Tracking</span><span class="sxs-lookup"><span data-stu-id="0d3ca-103">TDS Certificate Tracking</span></span>

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="0d3ca-104">This topic explains how to track and update the TDS certificate receivable or received from a customer.</span><span class="sxs-lookup"><span data-stu-id="0d3ca-104">This topic explains how to track and update the TDS certificate receivable or received from a customer.</span></span>

## <a name="tds-certificate-details-assign-update-and-rectification-process"></a><span data-ttu-id="0d3ca-105">TDS certificate details assign, update and rectification process</span><span class="sxs-lookup"><span data-stu-id="0d3ca-105">TDS certificate details assign, update and rectification process</span></span>

- <span data-ttu-id="0d3ca-106">Assign TDS certificate details</span><span class="sxs-lookup"><span data-stu-id="0d3ca-106">Assign TDS certificate details</span></span>

  <span data-ttu-id="0d3ca-107">Customer Ledger entries, which are not marked, against which TDS certificate is receivable can be assigned separately.</span><span class="sxs-lookup"><span data-stu-id="0d3ca-107">Customer Ledger entries, which are not marked, against which TDS certificate is receivable can be assigned separately.</span></span> <span data-ttu-id="0d3ca-108">Provision is available to mark the posted customer transactions (invoices or payments) for which TDS certificate is receivable.</span><span class="sxs-lookup"><span data-stu-id="0d3ca-108">Provision is available to mark the posted customer transactions (invoices or payments) for which TDS certificate is receivable.</span></span>

   1. <span data-ttu-id="0d3ca-109">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Update TDS Certificate Details** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="0d3ca-109">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Update TDS Certificate Details** , and then choose the related link.</span></span> 
   2. <span data-ttu-id="0d3ca-110">Select relevant customer code in **Customer No.**</span><span class="sxs-lookup"><span data-stu-id="0d3ca-110">Select relevant customer code in **Customer No.**</span></span> <span data-ttu-id="0d3ca-111">field then Acton -> Function -> Assign TDS Cert. Details, system will open the customer ledger entry of the customer.</span><span class="sxs-lookup"><span data-stu-id="0d3ca-111">field then Acton -> Function -> Assign TDS Cert. Details, system will open the customer ledger entry of the customer.</span></span> <span data-ttu-id="0d3ca-112">Select and update the relevant documents by marking 'TDS Certificate Receivable' field true.</span><span class="sxs-lookup"><span data-stu-id="0d3ca-112">Select and update the relevant documents by marking 'TDS Certificate Receivable' field true.</span></span> <span data-ttu-id="0d3ca-113">Marked document will be removed from the 'Assign TDS Cert. Details' page and will be added in 'Update TDS Cert. Details' page.</span><span class="sxs-lookup"><span data-stu-id="0d3ca-113">Marked document will be removed from the 'Assign TDS Cert. Details' page and will be added in 'Update TDS Cert. Details' page.</span></span>
   3. <span data-ttu-id="0d3ca-114">System will update the 'TDS Certificate Receivable' field as true in Customer Ledger Entry.</span><span class="sxs-lookup"><span data-stu-id="0d3ca-114">System will update the 'TDS Certificate Receivable' field as true in Customer Ledger Entry.</span></span>

- <span data-ttu-id="0d3ca-115">Update TDS certificate details</span><span class="sxs-lookup"><span data-stu-id="0d3ca-115">Update TDS certificate details</span></span>

  <span data-ttu-id="0d3ca-116">After receiving the TDS Certificate, it is required to update the TDS certificate details.</span><span class="sxs-lookup"><span data-stu-id="0d3ca-116">After receiving the TDS Certificate, it is required to update the TDS certificate details.</span></span>

  1. <span data-ttu-id="0d3ca-117">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Update TDS Certificate Details** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="0d3ca-117">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Update TDS Certificate Details** , and then choose the related link.</span></span> 
  2. <span data-ttu-id="0d3ca-118">Select relevant information in **Customer No.** , **Certificate No.** , **Date of Receipt** , **Certificate TDS Amount** , **Financial Year** , **TDS Receivable Group** , the Acton -> Function -> Update TDS Cert. Details, system will open the customer ledger entry of the customer for which 'TDS Receivable for Customer' is marked true.</span><span class="sxs-lookup"><span data-stu-id="0d3ca-118">Select relevant information in **Customer No.** , **Certificate No.** , **Date of Receipt** , **Certificate TDS Amount** , **Financial Year** , **TDS Receivable Group** , the Acton -> Function -> Update TDS Cert. Details, system will open the customer ledger entry of the customer for which 'TDS Receivable for Customer' is marked true.</span></span>
  3. <span data-ttu-id="0d3ca-119">Select and update the relevant documents for which company has received the TDS Certificate by marking 'TDS Certificate Received' field true and update.</span><span class="sxs-lookup"><span data-stu-id="0d3ca-119">Select and update the relevant documents for which company has received the TDS Certificate by marking 'TDS Certificate Received' field true and update.</span></span> <span data-ttu-id="0d3ca-120">Marked document will be removed from the 'Update TDS Cert. Details' page and will be added in 'Rectify TDS Cert. Details' page.</span><span class="sxs-lookup"><span data-stu-id="0d3ca-120">Marked document will be removed from the 'Update TDS Cert. Details' page and will be added in 'Rectify TDS Cert. Details' page.</span></span>
  4. <span data-ttu-id="0d3ca-121">System will update the customer ledger entry of the selected document with the input data.</span><span class="sxs-lookup"><span data-stu-id="0d3ca-121">System will update the customer ledger entry of the selected document with the input data.</span></span>

- <span data-ttu-id="0d3ca-122">Rectify TDS certificate details</span><span class="sxs-lookup"><span data-stu-id="0d3ca-122">Rectify TDS certificate details</span></span>

  <span data-ttu-id="0d3ca-123">Rectification of updated details may also be required just in case some wrong information is provided earlier.</span><span class="sxs-lookup"><span data-stu-id="0d3ca-123">Rectification of updated details may also be required just in case some wrong information is provided earlier.</span></span>

   1. <span data-ttu-id="0d3ca-124">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Update TDS Certificate Details** , and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="0d3ca-124">Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Update TDS Certificate Details** , and then choose the related link.</span></span> 
   2. <span data-ttu-id="0d3ca-125">Select relevant customer code in **Customer No.**</span><span class="sxs-lookup"><span data-stu-id="0d3ca-125">Select relevant customer code in **Customer No.**</span></span> <span data-ttu-id="0d3ca-126">field then Acton -> Function -> Rectify TDS Cert. Details, system will open the customer ledger entry for which TDS certificate details are updated.</span><span class="sxs-lookup"><span data-stu-id="0d3ca-126">field then Acton -> Function -> Rectify TDS Cert. Details, system will open the customer ledger entry for which TDS certificate details are updated.</span></span> 
   3. <span data-ttu-id="0d3ca-127">Select and update the relevant documents by marking 'TDS Certificate Receivable' field false.</span><span class="sxs-lookup"><span data-stu-id="0d3ca-127">Select and update the relevant documents by marking 'TDS Certificate Receivable' field false.</span></span> <span data-ttu-id="0d3ca-128">Marked document will be removed from the 'Rectify TDS Cert. Details' page and will be added in 'Update TDS Cert. Details' page.</span><span class="sxs-lookup"><span data-stu-id="0d3ca-128">Marked document will be removed from the 'Rectify TDS Cert. Details' page and will be added in 'Update TDS Cert. Details' page.</span></span>
   4. <span data-ttu-id="0d3ca-129">System will remove the details related to TDS certificate from Customer Ledger Entry.</span><span class="sxs-lookup"><span data-stu-id="0d3ca-129">System will remove the details related to TDS certificate from Customer Ledger Entry.</span></span>