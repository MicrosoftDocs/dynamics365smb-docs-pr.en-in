---
title: Tax Engine - Tax Configuration 02
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
ms.openlocfilehash: 13e2d6b6e520ee3d0f894f2b054ee18bd7a9c186
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948607"
---
# <a name="tax-engine---use-case-configuration"></a>Tax Engine - Use Case Configuration

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

This topic provides information about use case configuration.

## <a name="use-cases"></a>Use cases
Use case describes a business scenario, conditions which need to be met and event which will trigger the calculation of tax. A use case can be enabled or disabled as per the business need.  

Use Case consist of following stages for calculation:

  - **Condition** :

    Condition which determine whether the use case should be executed or not.

    Example of Condition:

     |Operator|Value|Condition|Value 2|
     |--------------------|-----------------------|-----------------|----------|  
     |    |"Applies-to Doc No."|Not Equals|''
     |or|"Applies-to ID"|Not Equals|''
     |and|"GST Vendor Type"|Equals|'Unregistered'
     |and|"Account Type"|Equals|'Vendor'
     |and|"Document Type"|Equals|'Invoice'
     |and|"GST Bill-to/Buy-from State Code"|Equals|'Location State Code'
     |and|"GST Group Code"|Not Equals|''
     |and|"HSN/SAC Code"|Not Equals|''
     |and|"GST Reverse Charge"|Equals|'Yes'


   - **Attribute Mapping** :

     This is defined to map the required attributes with their source of value.
     Example : In case, GST is to be calculated on Sales Line and value of field ‘Type’ on General Journal Line is ‘G/L Account’ then, HSN Code will flow from G/L Account table.

   - **Rate Parameter Mapping** :

     Rate parameter needs to be mapped with their source, but this mapping will be done only for column types ‘Range’ and ‘Value’. If an applicable tax rate is found, then system will return ‘component percent’ defined for that tax rate. Example:

      |Type  |Description  |
      |---------|---------|
      |**Date**|This column will be mapped with a posting date of sales header and the system will analyse whether the posting date falls within the ‘Date from’ to ‘Date To’ range.|
      |**From State**|In case of sales, parameter 'From State' needs to be mapped with state of location code.|
      |**To State**|In case of Sales, parameter 'To State' needs to be mapped with state of customer code.|


   - **Use Case Variables** :

     Variables can be used at the time of computation of an intermediate value or defining validations in a use case. Example: showing alert message on tax execution.


  - **Computation Script** :

     This is an optional step, which will be used to store values in variables.
     Example: storing value of TDS Amount and adding INR 1000 freight to get the final amount.


   - **Component Formula** :

     Define ‘Component formula’ for the components which are specific to the use case. Example: CGST = {“Line Amount” from “Sales Line”} * {CGST %} /100


  - **Use Case Posting** :

    There is a posting entity where the 'G/L Accounts' are configured for the specific 'tax type'. Based on the filters applied on the posting entity, tax engine points to the record from which components can be mapped to posting accounts. In case of reverse charge, same component is adjusted with its payable or receivable account. Configuration will have “Reverse Charge” flag as true and account can be mapped for same to “Reverse Charge G/L Field Name”.


  - **Tax Ledger Mapping** :

    Calculated tax, which is an output of a use case needs to be mapped to a tax ledger table. Example: On posting of general ledger entry for GST, there will be a new GST Entry created as a tax ledger for the posted transaction.


## <a name="how-to-check-tax-information-for-a-transaction"></a>How to check tax information for a transaction

There are two fact boxes available on transaction page to view calculated tax

- Tax Information 
- Tax Component

Statistics Page, will show the tax information in Tax Summary Tab.









































