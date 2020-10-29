---
title: Tax Engine - Lookup
description: Tax Engine - Lookup
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: f037f0914a13d046fa2b48e25c0ab8965a5ab664
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948608"
---
# <a name="tax-engine---lookup"></a><span data-ttu-id="3d555-103">Tax Engine - Lookup</span><span class="sxs-lookup"><span data-stu-id="3d555-103">Tax Engine - Lookup</span></span>

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

<span data-ttu-id="3d555-104">Lookup is a utility to fetch value from the system or from a variable.</span><span class="sxs-lookup"><span data-stu-id="3d555-104">Lookup is a utility to fetch value from the system or from a variable.</span></span>

## <a name="source-type"></a><span data-ttu-id="3d555-105">Source Type</span><span class="sxs-lookup"><span data-stu-id="3d555-105">Source Type</span></span>

<span data-ttu-id="3d555-106">Source type is to specify the source of value.</span><span class="sxs-lookup"><span data-stu-id="3d555-106">Source type is to specify the source of value.</span></span>


#### <a name="current-record"></a><span data-ttu-id="3d555-107">Current record</span><span class="sxs-lookup"><span data-stu-id="3d555-107">Current record</span></span>
<span data-ttu-id="3d555-108">If value of a field is to be picked from the current record (that is source table of the rule).</span><span class="sxs-lookup"><span data-stu-id="3d555-108">If value of a field is to be picked from the current record (that is source table of the rule).</span></span>

#### <a name="variable"></a><span data-ttu-id="3d555-109">Variable</span><span class="sxs-lookup"><span data-stu-id="3d555-109">Variable</span></span>

<span data-ttu-id="3d555-110">If value of a variable is to be picked.</span><span class="sxs-lookup"><span data-stu-id="3d555-110">If value of a variable is to be picked.</span></span> <span data-ttu-id="3d555-111">Variables of a rule can be created or viewed from the rule editor card.</span><span class="sxs-lookup"><span data-stu-id="3d555-111">Variables of a rule can be created or viewed from the rule editor card.</span></span>

#### <a name="table"></a><span data-ttu-id="3d555-112">Table</span><span class="sxs-lookup"><span data-stu-id="3d555-112">Table</span></span>

<span data-ttu-id="3d555-113">If value of a field is to be picked from a table that is related to the current record / source table.</span><span class="sxs-lookup"><span data-stu-id="3d555-113">If value of a field is to be picked from a table that is related to the current record / source table.</span></span> <span data-ttu-id="3d555-114">This is very much like CALCFORMULA in AL.</span><span class="sxs-lookup"><span data-stu-id="3d555-114">This is very much like CALCFORMULA in AL.</span></span>

- <span data-ttu-id="3d555-115">Table Name : Specify the table from where the value is to be picked.</span><span class="sxs-lookup"><span data-stu-id="3d555-115">Table Name : Specify the table from where the value is to be picked.</span></span>

- <span data-ttu-id="3d555-116">Table Filters : Specify the relationship between the current record and the table from where the value is to be picked.</span><span class="sxs-lookup"><span data-stu-id="3d555-116">Table Filters : Specify the relationship between the current record and the table from where the value is to be picked.</span></span>

- <span data-ttu-id="3d555-117">Table Sorting : Sorting to be applied on table records.</span><span class="sxs-lookup"><span data-stu-id="3d555-117">Table Sorting : Sorting to be applied on table records.</span></span> <span data-ttu-id="3d555-118">If sorting is specified, records will be sorted on Primary Key.</span><span class="sxs-lookup"><span data-stu-id="3d555-118">If sorting is specified, records will be sorted on Primary Key.</span></span>

- <span data-ttu-id="3d555-119">Field Name: Value is picked from this field based on the method you have selected.</span><span class="sxs-lookup"><span data-stu-id="3d555-119">Field Name: Value is picked from this field based on the method you have selected.</span></span>

- <span data-ttu-id="3d555-120">Method :</span><span class="sxs-lookup"><span data-stu-id="3d555-120">Method :</span></span> 

  - <span data-ttu-id="3d555-121">First: Value is picked from the first record.</span><span class="sxs-lookup"><span data-stu-id="3d555-121">First: Value is picked from the first record.</span></span>
  - <span data-ttu-id="3d555-122">Last: Value is picked from the last record.</span><span class="sxs-lookup"><span data-stu-id="3d555-122">Last: Value is picked from the last record.</span></span>
  - <span data-ttu-id="3d555-123">Sum: Calculate sum of all values from a selected field after applying table filters.</span><span class="sxs-lookup"><span data-stu-id="3d555-123">Sum: Calculate sum of all values from a selected field after applying table filters.</span></span>
  - <span data-ttu-id="3d555-124">Average: Calculate average value from a selected field after applying table filters.</span><span class="sxs-lookup"><span data-stu-id="3d555-124">Average: Calculate average value from a selected field after applying table filters.</span></span>
  - <span data-ttu-id="3d555-125">Min: Min value from a selected field after applying table filters.</span><span class="sxs-lookup"><span data-stu-id="3d555-125">Min: Min value from a selected field after applying table filters.</span></span>
  - <span data-ttu-id="3d555-126">Max: Max value from a selected field after applying table filters.</span><span class="sxs-lookup"><span data-stu-id="3d555-126">Max: Max value from a selected field after applying table filters.</span></span>
  - <span data-ttu-id="3d555-127">Count: Count of records after applying table filters.</span><span class="sxs-lookup"><span data-stu-id="3d555-127">Count: Count of records after applying table filters.</span></span>

#### <a name="database"></a><span data-ttu-id="3d555-128">Database</span><span class="sxs-lookup"><span data-stu-id="3d555-128">Database</span></span>

<span data-ttu-id="3d555-129">USERID, COMPANYNAME, SERIALNUMBER, TENANTID, SESSIONID, SERVICEINSTANCEID values can be picked from the current database.</span><span class="sxs-lookup"><span data-stu-id="3d555-129">USERID, COMPANYNAME, SERIALNUMBER, TENANTID, SESSIONID, SERVICEINSTANCEID values can be picked from the current database.</span></span>


#### <a name="system"></a><span data-ttu-id="3d555-130">System</span><span class="sxs-lookup"><span data-stu-id="3d555-130">System</span></span>

<span data-ttu-id="3d555-131">TIME, TODAY, WORKDATE, CURRENTDATETIME values can be picked from the current database.</span><span class="sxs-lookup"><span data-stu-id="3d555-131">TIME, TODAY, WORKDATE, CURRENTDATETIME values can be picked from the current database.</span></span>

#### <a name="tax-attribute"></a><span data-ttu-id="3d555-132">Tax attribute</span><span class="sxs-lookup"><span data-stu-id="3d555-132">Tax attribute</span></span>

<span data-ttu-id="3d555-133">Tax attributes defined with tax type can be picked.</span><span class="sxs-lookup"><span data-stu-id="3d555-133">Tax attributes defined with tax type can be picked.</span></span>


#### <a name="component"></a><span data-ttu-id="3d555-134">Component</span><span class="sxs-lookup"><span data-stu-id="3d555-134">Component</span></span>

<span data-ttu-id="3d555-135">Tax Component amounts computed can be picked from Tax Rates.</span><span class="sxs-lookup"><span data-stu-id="3d555-135">Tax Component amounts computed can be picked from Tax Rates.</span></span>


#### <a name="record-variable"></a><span data-ttu-id="3d555-136">Record variable</span><span class="sxs-lookup"><span data-stu-id="3d555-136">Record variable</span></span>

<span data-ttu-id="3d555-137">The value of a ‘Record variable’ field used in 'use case' variable can be picked.</span><span class="sxs-lookup"><span data-stu-id="3d555-137">The value of a ‘Record variable’ field used in 'use case' variable can be picked.</span></span>


#### <a name="component-percent"></a><span data-ttu-id="3d555-138">Component percent</span><span class="sxs-lookup"><span data-stu-id="3d555-138">Component percent</span></span>

<span data-ttu-id="3d555-139">‘Tax Component Percent’ captured from ‘Tax Rates’ can be picked.</span><span class="sxs-lookup"><span data-stu-id="3d555-139">‘Tax Component Percent’ captured from ‘Tax Rates’ can be picked.</span></span>


#### <a name="column"></a><span data-ttu-id="3d555-140">Column</span><span class="sxs-lookup"><span data-stu-id="3d555-140">Column</span></span>

<span data-ttu-id="3d555-141">Value of ‘Tax Rate Parameter’ captured from ‘Tax Rates’ can be picked.</span><span class="sxs-lookup"><span data-stu-id="3d555-141">Value of ‘Tax Rate Parameter’ captured from ‘Tax Rates’ can be picked.</span></span>


#### <a name="attribute-table"></a><span data-ttu-id="3d555-142">Attribute table</span><span class="sxs-lookup"><span data-stu-id="3d555-142">Attribute table</span></span>

<span data-ttu-id="3d555-143">Value of an attribute from existing table can be picked.</span><span class="sxs-lookup"><span data-stu-id="3d555-143">Value of an attribute from existing table can be picked.</span></span>


#### <a name="posting"></a><span data-ttu-id="3d555-144">Posting</span><span class="sxs-lookup"><span data-stu-id="3d555-144">Posting</span></span>

<span data-ttu-id="3d555-145">To get the helpers that can be used in posting of a document.</span><span class="sxs-lookup"><span data-stu-id="3d555-145">To get the helpers that can be used in posting of a document.</span></span> <span data-ttu-id="3d555-146">(Ex- Dimension Set, General Posting Group’s, GL Entry No. of Tax ledger Entry).</span><span class="sxs-lookup"><span data-stu-id="3d555-146">(Ex- Dimension Set, General Posting Group’s, GL Entry No. of Tax ledger Entry).</span></span>

















