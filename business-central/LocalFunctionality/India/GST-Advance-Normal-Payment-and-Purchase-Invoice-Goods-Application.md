---
title: GST on Advance Payment application with Purchase Invoice
description: GST on Advance Payment application with Purchase Invoice
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 5e7a69730cfe83fb24c3a2a328b6b7b957f50e30
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948656"
---
# <a name="gst-on-advance-payment-or-normal-payment-application-with-purchase-invoice"></a>GST on Advance Payment or Normal Payment Application with Purchase Invoice

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

An advance payment made to vendor for a transaction that is subject to reverse charge is to be reported in GSTR-2. 

If the advance payment is applied to the invoice in the same month, then such applications need not be disclosed in GSTR-2. However, if advance payment is paid in a month and is applied to invoice in the subsequent month, then this application is to be reported in GSTR-2. 

Process for application and un-application of payment and invoice has been explained in this document


## <a name="gst-on-advance-payment-and-application-with-purchase-invoice"></a>GST on advance payment and application with purchase invoice

 GST is liable at the time of advance payment to vendor, for example, service amount is INR 20000 and advance payment made to vendor for INR 10000 and 18% GST (i.e. 9% CGST and 9% SGST/UTGST) has to be charged. Taxpayer paying advance is not eligible to claim ITC on advance paid. The taxpayer can claim ITC on advance paid only on receipt of services.

- GST calculation for Intra-State or Intra-Union Territory transactions will appear in the Fact Box, as following:
    
    |Component|Amount|
    |----------------------------------|---------------------------------------|  
    |**GST Base Amount**|10,000|  
    |**CGST**|900|  
    |**SGST**|900| 

- GL Entries for advance payment made to vendor, will be as following:

    |Particulars|Amount|
    |----------------------------------|---------------------------------------|  
    |**Vendor Account**|10,000|  
    |**SGST/UTGST Receivable (Interim) Account**|900|  
    |**CGST Receivable (Interim) Account**|900| 
    |**SGST/UTGST Payable Account**|-900| 
    |**CGST Payable Account**|-900| 
    |**Bank Account**|-10000| 


Later invoice for service purchase issued by vendor for INR 20,000 and 18% GST (i.e. 9% CGST and 9% SGST/UTGST), will be charged.

- GST Calculation will appear in the Fact Box, as following:

    |Component|Amount|
    |----------------------------------|---------------------------------------|  
    |**GST Base Amount**|20000|  
    |**CGST**|1800|  
    |**SGST**|1800| 


- GL Entries for application of an advance payment with an invoice for services, where input tax credit is available:

    |Particulars|Amount|
    |----------------------------------|---------------------------------------|  
    |**Service Account**|20000|  
    |**CGST Receivable (Interim) Account**|1800| 
    |**SGST/UTGST Receivable (Interim) Account**|1800|
    |**CGST Payable (Interim) Account**|-1800|
    |**SGST/UTGST Payable (Interim) Account**|-1800| 
    |**Vendor Account**|-20000| 
    |**CGST Payable (Interim) Account**|900|   
    |**SGST/UTGST Payable (Interim) Account**|900|
    |**CGST Receivable Account**|900|
    |**SGST/UTGST Receivable  Account**|900|
    |**CGST Receivable (Interim) Account**|-1800|
    |**SGST/UTGST Receivable (Interim) Account**|-1800|


- GL Entries for application of an advance payment with an invoice for services, where input tax credit is not available:

    |Particulars|Amount|
    |----------------------------------|---------------------------------------|  
    |**Service Account**|23600|  
    |**CGST Payable (Interim) Account**|-1800| 
    |**SGST/UTGST Payable (Interim) Account**|-1800|
    |**Vendor Account**|-20000|
    |**CGST Payable (Interim) Account**|900|
    |**SGST/UTGST Payable (Interim) Account**|900|
    **CGST Receivable (Interim) Account**|-900|
    |**SGST/UTGST Receivable (Interim) Account**|-900|

If this is found that the payment and invoice was wrongly applied and the application needs to be reversed, in such a case un-apply functionality can be used. Un-application entries are same for both online application and offline application.

- GL Entries for un-application of an advance payment with an invoice for services, where input tax credit is available:
    
    |Particulars|Amount|
    |----------------------------------|---------------------------------------|  
    |**CGST Receivable (Interim) Account**|1800| 
    |**SGST/UTGST Receivable (Interim) Account**|1800| 
    |**CGST Receivable Account**|-900|
    |**SGST/UTGST Receivable Account**|-900|
    |**CGST Payable (Interim) Account**|-900| 
    |**SGST/UTGST Payable (Interim) Account**|-900|
            
- GL Entries for un-application of an advance payment with an invoice of services, where input tax credit is not available:
    
    |Particulars|Amount|
    |----------------------------------|---------------------------------------|  
    |**CGST Receivable (Interim) Account**|900| 
    |**SGST/UTGST Receivable (Interim) Account**|900| 
    |**CGST Payable (Interim) Account**|-900| 
    |**SGST/UTGST Payable (Interim) Account**|-900|

## <a name="normal-payment-to-vendor-and-application-with-purchase-invoice"></a>Normal Payment to vendor and application with purchase invoice

For unregistered, import vendor and reverse charge purchase of service from registered vendor, user has to post a separate invoice for goods and services in the system. No GST calculation is done at the time of application.
In ordinary course, when a normal payment is applied to the invoice, system proportionately posts the liability from Payable Interim Account to Payable Account and credit (if applicable) from Receivable Interim Account to Receivable Account. 

For example, Purchase Invoice for service purchase issued to vendor for INR 60,000 and 18% GST (i.e. 9% CGST and 9% SGST/UTGST), has to be charged. Later a payment of INR 10,000 has been made to vendor against to the purchase invoice, which doesn't have any GST impact.

- GST Calculation will appear in the Fact Box, as following:
    
    |Component|Amount|
    |----------------------------------|---------------------------------------|  
    |**Total GST Transactional Value**|60000| 
    |**Invoice Total CGST Amount**|5,400 (60000*9%)| 
    |**Invoice Total SGST/UTGST Amount**|5,400 (60,000*9%)|  
    |**Normal Payment Applied**|10000| 
    |**SGST/UTGST Amount = Invoice Total SGST/UTGST amount x (Normal Payment Applied/Total Transactional Value)**|900 (5,400*(10,000/60,000)|
    |**CGST Amount = Invoice Total CGST amount x (Normal Payment Applied/Total Transactional Value)**|900 (5,400*(10,000/60,000)|

- GL Entries for Application of invoice with normal payment:

    |Particulars|Amount|
    |----------------------------------|---------------------------------------|  
    |**Vendor Account**|10000|  
    |**CGST Payable (Interim) Account**|900|  
    |**SGST/UTGST Payable (Interim) Account**|900|
    |**CGST Receivable Account**|900|
    |**SGST/UTGST Receivable Account**|900|
    |**CGST Payable Account**|-900|
    |**SGST/UTGST Payable Account**|-900|
    |**CGST Receivable (Interim) Account**|-900|
    |**SGST/UTGST Receivable (Interim) Account**|-900|  
    |**Bank Account**|10000|

If this is found that the payment and invoice was wrongly applied and the application needs to be reversed, in such a case un apply functionality can be used. Un-application entries are same for both online application and offline application.

- GL Entries for un-application of invoice with normal payment:

    |Particulars|Amount|
    |----------------------------------|---------------------------------------|  
    |**CGST Payable Account**|900|  
    |**SGST/UTGST Payable Account**|900|  
    |**CGST Receivable (Interim) Account**|900|
    |**SGST/UTGST Receivable (Interim) Account**|900|
    |**CGST Payable (Interim) Account**|-900| 
    |**SGST/UTGST Payable (Interim) Account**|-900|
    |**SGST/UTGST Receivable Account**|-900|
    |**CGST Receivable Account**|-900| 

>[!Tip]
>
> Note: In case of Inter-State Purchase, IGST will be calculated.






































