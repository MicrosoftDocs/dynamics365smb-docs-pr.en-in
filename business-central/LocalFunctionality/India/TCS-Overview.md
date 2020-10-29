---
title: Setting up Tax Collected at Source, as per the provisions of the Income Tax Act, 1961
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
ms.openlocfilehash: 0a15d390608c8ee399b2a721feb96ebdfa42d075
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948616"
---
# <a name="setting-up-tax-collected-at-source-tcs-as-per-the-provisions-of-the-income-tax-act-1961"></a>Setting Up Tax Collected at Source (TCS), as per the Provisions of the Income Tax Act, 1961


[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

Business Central has included Tax Collected at Source (TCS) Feature in Indian Localisation.

**TCS** means **Tax Collected at Source** is one of the methods for tax collection by the government. It follows the principle of ‘You pay while you earn’. While ‘Tax Deducted at Source’ (TDS) requires the payer to deduct tax at source and remit the tax to the Government, ‘Tax Collected at Source’ (TCS) requires the receiver or seller to collect tax at source and remit it to the Government. The purpose of this provision is to eliminate tax evasion in certain trades.

## <a name="setting-up-tcs"></a>Setting Up TCS

### <a name="tcs-has-two-types-of-setup"></a>TCS has two types of setup.

- Automatic - These setup are done through Tax Engine.
- Manual - These setups are done manually by the business users.

### <a name="following-is-the-list-of-setups-that-will-be-pre-configured-with-the-help-of-tax-engine"></a>Following is the list of setups that will be pre-configured with the help of **Tax Engine**

- Tax Types
- Tax Entities
- Components
- Attributes
- Rate Setup


For more information about Auto Setup, see **Tax Engine** Information.

### <a name="the-following-are-required-to-be-setup-manually"></a>The following are required to be setup manually

- [TCS Rates](tcs-overview.md#to-set-up-tcs-rates)
- [Tax Accounting Period](tcs-overview.md#to-set-up-tax-accounting-period)
- [T.A.N](tcs-overview.md#)
- [Assessee Code](tcs-overview.md#)
- [TCS Nature of Collection](tcs-overview.md#)
- [Concessional Code](tcs-overview.md#to-set-up-concessional-codes)
- [TCS Posting Setup](tcs-overview.md#to-set-up-tcs-posting-setup)
- [TCS on Customer Master](tcs-overview.md#to-set-up-tcs-on-customer-master)
- [TCS on Location Master](tcs-overview.md#to-set-up-tcs-on-location-master)
- [TCS on Company Information](tcs-overview.md#to-set-up-tcs-on-company-information)
- [TCS on State Code](tcs-overview.md#to-set-up-tcs-on-state-code)

## <a name="to-set-up-tcs-rates"></a>To set up TCS rates

Rate of TCS is defined in combination of TCS nature of collection and assessee code.

1. Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Tax Type** -> **TCS** -> **Action** -> **Tax Rates** , and then choose the related link.
2. Fill in the fields as described in the following table.

    |Field|Description|  
    |---------------------------------|---------------------------------------|  
    |**TCS Nature of Collection**|Specifies the nature of collection of TCS.|
    |**Assessee Code**|Specifies the assessee code.|
    |**Concessional Code**|Specifies the concessional code.|
    |**Effective Date**|Specifies the effective date.|
    |**TCS %**|Specifies the TCS rate.|
    |**Surcharge %**|Specifies the surcharge rate.|
    |**Non PAN TCS %**|Specifies the TCS rate in case of non availability of PAN.|
    |**e Cess %**|Specifies the eCess rate.|
    |**SHE Cess %**|Specifies the SHE Cess rate.|
    |**TCS Threshold Amount**|Specifies the threshold amount applicable for TCS.|
    |**Surcharge Threshold Amount**|Specifies the threshold amount applicable for surcharge.|
    |**Contract Amount**|Specifies the contract amount.|

## <a name="to-set-up-tax-accounting-period"></a>To set up tax accounting period

Tax Accounting period and quarters need to be defined for TCS calculation.

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

## <a name="to-set-up-tcan"></a>To set up T.C.A.N.

Tax Collected Account Number (T.C.A.N.) allotted to a company can be more than one, depending on the number of branch locations from where the company files its returns. All the account numbers allotted to a company need to be captured here.

1. Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **T.C.A.N Nos.** , and then choose the related link. 
2. Fill in the fields as described in the following table.   

    |Field|Description|  
    |---------------------------------|---------------------------------------|   
    |**Code**|Enter the valid registration number provided by tax department.|  
    |**Description**|Specify the description of the registration number.|
    

> [!TIP]
>
> It is mandatory to enter the T.C.A.N. on all TCS Transactions.

## <a name="to-set-up-assessee-code"></a>To set up assessee code

Income Tax Act 1961 defines 'Assessee' as a person by whom any tax or any other sum of money is payable under this Act. The rates of TCS are different for different types of Assessee.

1. Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Assessee Codes** , and then choose the related link. 
2. Fill in the fields as described in the following table.   

    |Field|Description|  
    |---------------------------------|---------------------------------------|   
    |**Code**|Enter the valid Assessee Code, for example, IND, COM.|  
    |**Description**|Enter the description of the assessee code.|
    |**Type**|Select the type of the assessee from drop down list as Company or Others.|

> [!TIP]
>
> Type should be selected correctly while creating Assessee codes as it will reflect in eTDS returns.

## <a name="to-set-up-tcs-nature-of-collection"></a>To set up TCS nature of collection

TCS Nature of Collection represents the various types of payments received for which TCS rates have been specified under the provisions of section 206C of the Income Tax Act 1961.

1. Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **TCS Nature of Collection** , and then choose the related link.
2. Fill in the fields as described in the following table.

    |Field|Description|  
    |---------------------------------|---------------------------------------|   
    |**Code**|Enter the valid TCS Nature of Collection applicable as per the Income Tax Act, 1961|  
    |**Description**|Enter the description of the mentioned TCS Nature of Collection.|
   

## <a name="to-set-up-concessional-codes"></a>To set up concessional codes

Concessional codes are used for cases authorised for concessional rates exclusively defined by the government.    

1. Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Concessional Codes** , and then choose the related link.
2. Fill in the fields as described in the following table.

    |Field|Description|  
    |---------------------------------|---------------------------------------|   
    |**Code**|Enter the valid Concessional Codes applicable as per the Income Tax Act|  
    |**Description**|Enter the description of the mentioned Concessional Codes|

## <a name="to-set-up-tcs-posting-setup"></a>To set up TCS posting setup

Specifies the general ledger account for each TCS Nature of Collection defined in the system. System will update the TCS payable amount in the defined general ledger account.

1. Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **TCS Posting Setup** , and then choose the related link.
2. Fill in the fields as described in the following table.

    |Field|Description|  
    |---------------------------------|---------------------------------------|
    |**TCS Nature of Collection**|Enter the valid TCS nature of collection.|
    |**Effective Date**|Specifies the starting date.|
    |**TCS Account**|Specifies the general ledger account for posting of TCS payable amount.|


## <a name="to-set-up-tcs-on-customer-master"></a>To set up TCS on customer master

TCS nature of collection and concessional codes need to be defined for each customer that is liable to TCS. Multiple TCS NOC can be attached to one customer.

- To define the TCS Nature of Collection on the Customer Card

  1. Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Customers** -> **Customer** -> **Allowed NOC** and then choose the related link.
  2. **Assessee Code** needs to be filled on the customer master.
  3. **PAN** needs to be filled on customer master. If no PAN is provided, higher rate of TCS will be deducted.
  4. Fill in the fields as described in the following table.

      |Field|Description|  
      |---------------------------------|---------------------------------------|
      |**TCS Nature of Collection**|Select the valid category from lookup list depending on the kind of product sold to the customer.|
      |**Description**|Enter the description of the selected Nature of Collection.|
      |**Default NOC**|Mark true if the Nature of Collection needs to be defined as default NOC.|
      |**Threshold Overlook**|Place a check mark in this field to overlook the TCS Threshold amount defined in 'Tax Rates'|
      |**Surcharge Overlook**|Place a check mark in this field to overlook the Surcharge Threshold amount defined in 'Tax Rates'|
      
- To define the concessional code on customer card

  1. Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Customers** -> **Customer** -> **Customer Concessional Codes** and then choose the related link.
  2. Fill in the fields as described in the following table.

      |Field|Description|  
      |---------------------------------|---------------------------------------|
      |**TCS Nature of Collection**|Select the valid Nature of Collection from lookup list depending on the kind of product sold by customer.|
      |**Description**|Enter the description of the selected Nature of Collection.|
      |**Concessional Code**|Select the valid concessional code from lookup list depending on the kind of product sold by customer.|
      |**Concessional Form No.**|Certificate number provided by the customer can be defined to justify the lower tax deduction.  |

## <a name="to-set-up-tcs-on-location-master"></a>To set up TCS on location master

**T.C.A.N.** needs to be defined for locations from where the company files its returns.

## <a name="to-set-up-tcs-on-company-information"></a>To set up TCS on company information

-  Following information needs to be defined on company information.

      |Field|Description|  
      |---------------------------------|---------------------------------------|
      |**T.C.A.N No.**|Specifies the TCAN of the legal entity.|
      |**P.A.N No.**|Specifies the PAN of the legal entity.|
      |**Deductor Category**|Specifies the deductor category of the legal entity.|
      |**Circle No.**|Specifies circle number.|
      |**Assessing Officer**|Specifies the assessing officer.|
      |**Ward No.**|Specifies the ward number.|

## <a name="to-set-up-tcs-on-state-code"></a>To set up TCS on state code

**State Code for eTDS/TCS** needs to be defined on States master.

















