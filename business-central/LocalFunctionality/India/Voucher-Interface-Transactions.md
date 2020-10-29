---
title: Transaction on Voucher Interface
description: Transaction on Voucher Interface
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: d86591a63dd81ba2c678c072f9b1b3d8e1af00f4
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948595"
---
# <a name="voucher-transaction"></a>Voucher Transaction

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

This topic explains the process of recording day-to-day transactions through voucher interface.

## <a name="type-of-vouchers-and-transactions"></a>Type of vouchers and transactions

Following are the vouchers needed to record the transactions like Cash, Bank, and Journals for this functionality:
- Cash Receipt Voucher: Entries which affect the Cash accounts while receiving cash payments from customers or refund from vendor. 
- Cash Payment Voucher: Entries which affect the Cash accounts while making cash payments to vendors or refund to customer 
- Bank Receipt Voucher: Entries which affect the Bank accounts while receiving payments from customers or refund from vendor. 
- Bank Payment Voucher: Entries which affect the Bank accounts while making payments to vendors or refund to customer. 
- Contra Voucher: Entries which affect the Cash and Bank Account together are termed as Contra Vouchers. For example, withdrawal from bank is one such transaction. 
- Journal Voucher: Entries which are affecting neither the Cash Account nor the Bank account are termed as Journal Vouchers. 


## <a name="mandatory-fields-for-voucher-entries-through-voucher-interface"></a>Mandatory fields for voucher entries through voucher interface

1. Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Cash Receipt Voucher** , **Cash Payment Voucher** , **Bank Receipt Voucher** , **Bank Payment Voucher** , **Contra Voucher** or **Journal Voucher** , and then choose the related link. 
2. Following are the mandatory fields for any type of voucher entry:

    |Field|Description|
    |----------------------------------|---------------------------------------|  
    |**Posting Date**|Specify the posting date.|  
    |**Document Type**|Specify document type as per transaction requirement i.e. Payment, Refund etc.|
    |**Document Number**|Specifies the document number, this can be manually entered or auto populated from general journal template or batch.|
    |**Account Type**|Select relevant account type, i.e. Customer, Vendor, G/L Account, Bank etc.|
    |**Account No.**|Select the relevant account number|
    |**Debit Amount**|Specify the debit amount|
    |**Credit Amount**|Specify the credit amount|
    |**Balance Account Type**|Select relevant account type, i.e. Customer, Vendor, G/L Account, Bank etc.|
    |**Balance Account No.**|Select the relevant account number|
    |**Cheque No.**|Specify the cheque number, only applicable for bank payment and receipt voucher.|
    |**Cheque Date**|Specify the cheque date, only applicable for bank payment and receipt voucher.|
    |**Line Narration**|Specify the line narration of the journal lines, can be provided for each line.|
    |**Voucher Narration**|Specify the voucher narration, this will be a single narration for the whole document.|
   

### <a name="posted-general-ledger-entries-for-each-voucher"></a>Posted general ledger entries for each voucher

- Payment received in cash from customer for INR 10,000 through Cash Receipt Voucher. 

  GL Entries will be as following:
     
    |Particulars|Amount|
    |----------------------------------|---------------------------------------|  
    |**Cash Account**|10000|
    |**Customer Account**|-10000|

> [!TIP]
> Cash will always be debited in Cash receipt voucher.

- Payment made in cash to vendor for INR 10,000 through Cash Payment Voucher. 

  GL Entries will be as following:
     
    |Particulars|Amount|
    |----------------------------------|---------------------------------------|  
    |**Cash Account**|-10000|
    |**Vendor Account**|10000|

> [!TIP]
> Cash will always be credited in Cash payment voucher.

- Payment received by cheque from customer for INR 10,000 through Bank Receipt Voucher. 

  GL Entries will be as following:
     
    |Particulars|Amount|
    |----------------------------------|---------------------------------------|  
    |**Bank Account**|10000|
    |**Customer Account**|-10000|

> [!TIP]
> Bank will always be debited in Bank receipt voucher.

- Payment made by cheque to vendor for INR 10,000 through Bank Payment Voucher. 

  GL Entries will be as following:
     
    |Particulars|Amount|
    |----------------------------------|---------------------------------------|  
    |**Bank Account**|-10000|
    |**Vendor Account**|10000|

> [!TIP]
> Bank will always be credited in Bank payment voucher.

- Payment made by cheque to vendor for INR 12,000 and INR 200 as Bank Charges through Bank Payment Voucher. 

  GL Entries will be as following:
     
    |Particulars|Amount|
    |----------------------------------|---------------------------------------|  
    |**Bank Account**|-12200|
    |**Vendor Account**|12000|
    |**Bank Charges Account**|200|

> [!TIP]
> Bank will always be credited in Bank payment voucher.

- Cash Withdrawn/deposited or Transfer between bank accounts through Contra Voucher, for example Cash Withdrawn from Bank for INR 10,000. 

  GL Entries will be as following:
     
    |Particulars|Amount|
    |----------------------------------|---------------------------------------|  
    |**Bank Account**|-10000|
    |**Cash Account**|10000|

> [!TIP]
> Only Bank or Cash accounts can be allowed in Contra Voucher.

- Expense booked for INR 10,000 and crediting Vendor through Journal Voucher.

  GL Entries will be as following:
     
    |Particulars|Amount|
    |----------------------------------|---------------------------------------|  
    |**Expenses Account**|10000|
    |**Vendor Account**|-10000|

> [!TIP]
> Bank and Cash accounts are not allowed in Journal Voucher.

## <a name="opening-balances-for-gst"></a>Opening balances for GST

GST opening balances shall be created in Business Central. In Journal Voucher, options available to provide the opening balances for – 
    
-   GST Credit
-   GST Liability
-   GST TDS Credit
-   GST TCS Credit

> [!NOTE]
> Only positive amounts are allowed for GST Credit opening balances.
>
> Only negative amounts are allowed for GST Liability opening balances.
>
> System should record the values in GST Sub-Ledger.


## <a name="tds-and-tcs-payment-to-government"></a>TDS and TCS payment to government

It is required to pay the TDS and TCS to government authorities through Bank/Cash Payment Vouchers. Provision is available to select the TDS and TCS sub-ledger entries by applying filters like Companies/Non-Companies, etc. and on the basis of TAN and TCAN Numbers. 

> [!NOTE]
> Details are available in respective TDS and TCS documents.