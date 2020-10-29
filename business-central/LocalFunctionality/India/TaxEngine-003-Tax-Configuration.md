---
title: Tax Engine - Tax Configuration 01
description: Tax Engine - Tax Configuration
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 0c6f110e26b66131303c35ade9b51a5cbabd4810
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948600"
---
# <a name="tax-engine---configuration-of-tax-type-and-tax-rates"></a>Tax Engine - Configuration of Tax Type and Tax Rates

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

This topic provides information about tax types that a tax authority can levy in the same jurisdiction or a different jurisdiction. Calculation and posting of this type of tax to G/L Accounts.

## <a name="tax-types"></a>Tax types

There can be various type of taxes applicable for a company. Examples:

- **GST** : Goods and Services Tax.
- **TDS** : Tax deducted at source.
- **TCS** : Tax collected at source.
- **WHT** : Withholding Tax.


## <a name="tax-entities"></a>Tax entities

These are tables which are specific to a Tax Type. This is defined to restrict the list of tables in a lookup. A Tax Entity can be of type ‘Master’ or ‘Transaction’.

- Example of Master: Customer, Vendor, Location, Item etc.
- Example of Transaction: Purchase Line, Sales Line, Transfer Line, Gen. Journal Line etc.


## <a name="input-parameters"></a>Input parameters

Attributes of tax type that can be used as a parameter in tax calculation or reporting. For example :

**HSN Code** : It is a parameter to find GST rate of an item and it can also be used as a parameter for filing of online tax to the government.

An attribute can be either linked to a field of an existing table or can be mapped to an existing table as an attribute. (In the same way as Item Attributes are define in item table)

Header contains following information  

- Attribute Name.
- Datatype of Attribute.
- Visible on Interface (Yes/No) 
- Blocked (Yes/No)

In case the attribute needs to be mapped to a field of a table, then the field needs to be entered in 'Mapping Field Name' else it will be created as an attribute for that entity record. Attribute values can be added or viewed in case the type of attribute is an ‘option’.


## <a name="component"></a>Component

Certain tax type may have components that need to be computed as part of tax calculation. Following are some examples of tax components:

- CGST: is a component of Tax Type GST.
- SGST: is a component of Tax Type GST.
- TDS: is a component of Tax Type TDS.
- E-Cess: is a component of Tax Type TDS.


## <a name="rate-setup"></a>Rate setup
For each tax type, parameters are defined basis which rate is specified in the setup.

These Parameters can be of following types:

|Type  |Description  |
|---------|---------|
|**Tax Attributes**|When a tax attribute is used as a parameter for tax rate configuration. (example – HSN Code, GST Group Code etc.)|
|**Value**|This will be used where we want to use a value in the tax rate configuration that is not mapped with a table as an attribute. (example – From State, To State etc.)|
|**Range**|This is used to define slabs in a tax rate setup, such as ‘Date from’ and ‘Date To’. When tax type is defined as 'range', system will create two parameters in tax rate configuration.|
|**Component**|Components are used to define distribution of tax calculated. For example, 50% of GST will go to CGST and remaining will be SGST.|
|**Output Information**|Numeric values that are part of rate setup. (Example – Threshold Amount)|



## <a name="tax-rates"></a>Tax rates
Tax rates can be defined for a combination of tax parameters defined as part of 'Rate Setup' for a 'Tax type'. Rate defined for a combination cannot be repeated.



















