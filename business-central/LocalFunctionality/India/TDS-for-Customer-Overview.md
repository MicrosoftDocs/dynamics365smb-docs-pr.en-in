---
title: Setting up Tax Deducted at Source by Customer, as per the provisions of the Income Tax Act, 1961
description: Specifies Basic Setups required, as per the provisions of the Income Tax Act, 1961
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 0ab5faed5174caa32971a6f8cf6e17d3022e73a2
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948602"
---
# <a name="setting-up-tax-deducted-at-source-tds-by-customer-as-per-the-provisions-of-the-income-tax-act-1961"></a>Setting Up Tax Deducted at Source (TDS) by Customer, as per the Provisions of the Income Tax Act, 1961

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

Business Central has included Tax Deducted at Source (TDS) by Customer Feature to Indian Localisation.

TDS is a withholding tax, where tax is deducted by the customer, at the time of making the payment or booking of the invoice, whichever is earlier. As per the Income Tax Act, 1961, tax needs to be deducted by the payer, when the payment is of a specific nature.
If the TDS is deducted by the customer (deductor), then the user (deductee) has to calculate TDS on the invoice or revenue and keep a track of TDS deducted. The deductor has to provide the deductee a TDS certificate.


## <a name="setting-up-tds"></a>Setting Up TDS

### <a name="tds-has-two-types-of-setup"></a>TDS has two types of setup.

- Automatic - These setup are done through Tax Engine.
- Manual - These setups are done manually by the business users.

### <a name="following-is-the-list-of-setups-which-will-be-pre-configured-with-help-of-tax-engine"></a>Following is the list of setups which will be pre-configured with help of **Tax Engine**

- Tax Types
- Tax Entities
- Components
- Attributes
- Rate Setup


For more information about Automatic Setup, see **Tax Engine** Information.

### <a name="the-following-are-required-to-be-setup-manually"></a>The following are required to be setup manually

- [TDS Rate](tds-for-customer-overview.md#to-set-up-tds-rates)
- [Tax Accounting Period](tds-for-customer-overview.md#to-set-up-tax-accounting-period)
- [T.A.N](tds-for-customer-overview.md#to-set-up-tan)
- [Assessee Code](tds-for-customer-overview.md#to-set-up-assessee-code)
- [TDS Section](tds-for-customer-overview.md#to-set-up-tds-section)
- [Concessional Code](tds-for-customer-overview.md#to-set-up-concessional-codes)
- [TDS Posting Setup](tds-for-customer-overview.md#to-set-up-tds-posting-setup)
- [TDS on Customer Master](tds-for-customer-overview.md#to-set-up-tds-on-customer-master)
- [TDS on Location Master](tds-for-customer-overview.md#to-set-up-tds-on-location-master)
- [TDS on Company Information](tds-for-customer-overview.md#to-set-up-tds-on-company-information)
- [TDS on State Code](tds-for-customer-overview.md#to-set-up-tds-on-state-code)

## <a name="to-set-up-tds-rates"></a>To set up TDS rates

Rate of TDS is defined in combination of TDS section and assessee code.

1. Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Tax Type** -> **TDS** -> **Action** -> **Tax Rates** , and then choose the related link.
2. Fill in the fields as described in the following table.

    |Field|Description|  
    |---------------------------------|---------------------------------------|  
    |**Section Code**|Specifies the TDS section code.|
    |**Assessee Code**|Specifies the assessee code.|
    |**Effective Date**|Specifies the date from which rate will be effective.|
    |**Concessional Code**|Specifies the concessional code.|
    |**Nature of Remittance**|Specifies whether the nature of remittance is applicable or not.|
    |**Act Applicable**|Specifies the applicable act.|
    |**Currency Code**|Specifies the currency code.|
    |**TDS %**|Specifies the TDS rate.|
    |**Non PAN TDS %**|Specifies the TDS rate in case of non availability of PAN.|
    |**Surcharge %**|Specifies the surcharge rate.|
    |**eCESS %**|Specifies the eCess rate.|
    |**SHE Cess %**|Specifies the SHE Cess rate.|
    |**Surcharge Threshold Amount**|Specifies the threshold amount applicable for surcharge.|
    |**TDS Threshold Amount**|Specifies the threshold amount applicable for TDS.|
    |**Per Contract Value**|Specifies the per contract value.

## <a name="to-set-up-tax-accounting-period"></a>To set up tax accounting period

Tax Accounting period and quarters need to be defined for TDS calculation.

1. Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Tax Acc. Period Setup** , and then choose the related link. 
2. Fill in the fields as described in the following table.   

    |Field|Description|  
    |---------------------------------|---------------------------------------|   
    |**Code**|Enter the valid tax type.|  
    |**Description**|Specify the description of the tax type.|

3. Select the Tax Type -> Action -> Tax Accounting Period -> Create Year, fill the following information and accounting period will be created.
    
    |Field|Description|  
    |---------------------------------|---------------------------------------|   
    |**Tax Type**|Select the valid tax type.|  
    |**Starting Date**|Specify the starting date of the accounting period.|
    |**No. of Periods**|Specify the number of periods.|
    |**Period Length**|Specify the length of the period.|

## <a name="to-set-up-tan"></a>To set up T.A.N.

Tax Deduction Account Number (T.A.N) allotted to a legal entity can be more than one, depending on the number of branch locations from where the legal entity files its TDs returns. All the account numbers allotted to a legal entity need to be captured here.

1. Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **T.A.N Nos.** , and then choose the related link. 
2. Fill in the fields as described in the following table.   

    |Field|Description|  
    |---------------------------------|---------------------------------------|
    |**Code**|Enter the valid registration number provided by authority.|  
    |**Description**|Specify the description of the registration number.|
    

## <a name="to-set-up-assessee-code"></a>To set up assessee code

Income Tax Act 1961 defines 'Assessee' as a person by whom any tax or any other sum of money is payable under this Act. The rates of TDS are different for different types of Assessee.

1. Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Assessee Codes** , and then choose the related link. 
2. Fill in the fields as described in the following table.   

    |Field|Description|  
    |---------------------------------|---------------------------------------|   
    |**Code**|Enter the valid Assessee Code, for example, IND, COM.|  
    |**Description**|Enter the description of the assessee code.|
    |**Type**|Select the type of the assessee from drop down list as Company or Others.|


## <a name="to-set-up-tds-section"></a>To set up TDS section

TDS Section represents the various sections under which tax deduction takes place as per the Income Tax Act 1961.

1. Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **TDS Sections** , and then choose the related link.
2. Fill in the fields as described in the following table.

    |Field|Description|  
    |---------------------------------|---------------------------------------|   
    |**Code**|Enter the valid TDS Section applicable as per the Income Tax Act, 1961|  
    |**Description**|Enter the description of the mentioned TDS Section.|
    |**e-TDS**|Specifies the section code to be used in the tds return.|

## <a name="to-set-up-concessional-codes"></a>To set up concessional codes

Concessional codes are used for cases authorised for concessional rates exclusively defined by the government. 

1. Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Concessional Codes** , and then choose the related link.
2. Fill in the fields as described in the following table.

    |Field|Description|  
    |---------------------------------|---------------------------------------|   
    |**Code**|Enter the valid Concessional Codes applicable as per the Income Tax Act|  
    |**Description**|Enter the description of the mentioned Concessional Codes|

## <a name="to-set-up-tds-posting-setup"></a>To set up TDS posting setup

Specifies the general ledger account for each TDS Section defined in the system. System will update the tds receivable amount in the defined general ledger account.

1. Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **TDS Posting Setup** , and then choose the related link.
2. Fill in the fields as described in the following table.

    |Field|Description|  
    |---------------------------------|---------------------------------------|   
    |**TDS Section**|Specifies the relevant TDS section|  
    |**Effective Date**|Specifies the start date of the setup line|
    |**TDS Receivable Account**|Specifies the general ledger account in which receivable account will be posted.|

## <a name="to-set-up-tds-on-customer-master"></a>To set up TDS on customer master

TDS Section and concessional codes need to be defined for each customer, who is liable to deduct TDS. Multiple TDS sections can be configured for one customer.

- To define the TDS Sections on the Customer Card.

  1. Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Customer** -> **Customer** -> **Customer Allowed Sections** and then choose the related link.
  2. **Assessee Code** needs to be filled on the customer master.
  3. **PAN** needs to be filled on customer master, PAN is mandatory for TDS calculation for customer.
  4. Fill in the fields as described in the following table.

      |Field|Description|  
      |---------------------------------|---------------------------------------|
      |**TDS Section**|Select the valid section from lookup list depending on the kind of services provided by the customer.|
      |**TDS Section Description**|Enter the description of the selected section.|
      |**TDS Certificate Receivable**|This field should be marked as true.|
      |**Threshold Overlook**|Place a check mark in this field to overlook the TDS Threshold amount defined in 'Tax Rates'|
      |**Surcharge Overlook**|Place a check mark in this field to overlook the Surcharge Threshold amount defined in 'Tax Rates'|

- To define the concessional code on customer card

  1. Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Customer** -> **Customer** -> **TDS Customer Concessional Codes** and then choose the related link.
  2. Fill in the fields as described in the following table.

      |Field|Description|  
      |---------------------------------|---------------------------------------|
      |**Section**|Select the valid section from lookup list depending on the kind of services provided by customer.|
      |**Concessional Code**|Select the valid concessional code from lookup list depending on the kind of services provided by customer.|
      |**Certificate No.**|Certificate number provided by the customer can be defined to justify the lower tax deduction.  |
      

## <a name="to-set-up-tds-on-location-master"></a>To set up TDS on location master

**T.A.N** needs to be defined in locations from where the company files its returns.

## <a name="to-set-up-tds-on-company-information"></a>To set up TDS on company information

-  Following information need to be defined in company information.

      |Field|Description|  
      |---------------------------------|---------------------------------------|
      |**T.A.N. No.**|Specifies the TAN No. of the legal entity.|
      |**P.A.N No.**|Specifies the PAN of the legal entity.|
      |**Deductor Category**|Specifies the deductor category of the legal entity.|
      |**PAO Code**|Specifies the PAO code.|
      |**PAO Registration No.**|Specifies PAO registration number.|
      |**DDO Code**|Specifies DDO code.|
      |**DDO Registration No.**|Specifies the DDO registration number.|
      |**Ministry Type**|Specifies the Ministry type.|
      |**Ministry Code**|Specifies the Ministry code.|

## <a name="to-set-up-tds-on-state-code"></a>To set up TDS on state code

**State Code for eTDS/TCS** needs to be defined in States master.

















