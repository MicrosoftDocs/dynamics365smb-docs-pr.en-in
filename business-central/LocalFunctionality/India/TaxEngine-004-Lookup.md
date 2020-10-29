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
# <a name="tax-engine---lookup"></a>Tax Engine - Lookup

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

Lookup is a utility to fetch value from the system or from a variable.

## <a name="source-type"></a>Source Type

Source type is to specify the source of value.


#### <a name="current-record"></a>Current record
If value of a field is to be picked from the current record (that is source table of the rule).

#### <a name="variable"></a>Variable

If value of a variable is to be picked. Variables of a rule can be created or viewed from the rule editor card.

#### <a name="table"></a>Table

If value of a field is to be picked from a table that is related to the current record / source table. This is very much like CALCFORMULA in AL.

- Table Name : Specify the table from where the value is to be picked.

- Table Filters : Specify the relationship between the current record and the table from where the value is to be picked.

- Table Sorting : Sorting to be applied on table records. If sorting is specified, records will be sorted on Primary Key.

- Field Name: Value is picked from this field based on the method you have selected.

- Method : 

  - First: Value is picked from the first record.
  - Last: Value is picked from the last record.
  - Sum: Calculate sum of all values from a selected field after applying table filters.
  - Average: Calculate average value from a selected field after applying table filters.
  - Min: Min value from a selected field after applying table filters.
  - Max: Max value from a selected field after applying table filters.
  - Count: Count of records after applying table filters.

#### <a name="database"></a>Database

USERID, COMPANYNAME, SERIALNUMBER, TENANTID, SESSIONID, SERVICEINSTANCEID values can be picked from the current database.


#### <a name="system"></a>System

TIME, TODAY, WORKDATE, CURRENTDATETIME values can be picked from the current database.

#### <a name="tax-attribute"></a>Tax attribute

Tax attributes defined with tax type can be picked.


#### <a name="component"></a>Component

Tax Component amounts computed can be picked from Tax Rates.


#### <a name="record-variable"></a>Record variable

The value of a ‘Record variable’ field used in 'use case' variable can be picked.


#### <a name="component-percent"></a>Component percent

‘Tax Component Percent’ captured from ‘Tax Rates’ can be picked.


#### <a name="column"></a>Column

Value of ‘Tax Rate Parameter’ captured from ‘Tax Rates’ can be picked.


#### <a name="attribute-table"></a>Attribute table

Value of an attribute from existing table can be picked.


#### <a name="posting"></a>Posting

To get the helpers that can be used in posting of a document. (Ex- Dimension Set, General Posting Group’s, GL Entry No. of Tax ledger Entry).

















