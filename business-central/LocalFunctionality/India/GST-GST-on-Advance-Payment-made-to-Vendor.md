---
title: GST on Advance Payment made to Vendor, with reverse charge
description: GST on Advance Payment made to Vendor, with reverse charge
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 39935b3558cb89c78aff4499428dfbfe22ded483
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948649"
---
# <a name="gst-on-advance-payment-made-to-vendor-with-reverse-charge"></a>GST on Advance Payment Made to Vendor, with Reverse Charge

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

The tax needs to be paid if supplier gets the payment first, therefore we need to calculate GST at the time of advance payment made to the vendor. However, when ‘supplier of goods’ receives advance payment, he is not required to pay GST at the time of the receipt of advance payment, while GST is required to be paid in case of supply of services.

The process of GST calculation on advance payment to vendor has been explained in this document.

### <a name="create-a-general-journal-or-a-bank-or-cash-payment-voucher"></a>Create a general journal or a bank or cash payment voucher

1.  Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **General Journal** or **Bank Payment Voucher** or **Cash Payment Voucher** , and then choose the related link. 
2. Select **Vendor** in account type and select relevant **Vendor Code** , GST vendor type and registration number should be filled in vendor master.
3. Select **G/L Account** or **Bank Account** in balancing account type, and select the cash or the bank account. 
4. Advance Payment made to vendor does not include tax payment, as the purchaser is liable to pay tax under reverse charge. Hence, tax is applied straight away on base. 
5. GST on Advance Payment field needs to be activated on General Journal Line for computation of GST on Advance Payment. In addition, GST Group code and GST Place of Supply should not be blank for computation of GST.

For example, advance payment made to vendor against supply of services of INR 10,000 on which 18% GST (9% CGST and 9% SGST/UTGST in case of Intra-State or Intra-Union Territory transaction or 18% IGST in case of Inter-State transaction) has to be charged.

- GST Calculation will appear in the Fact Box as following:
    
    |Component|Amount|
    |----------------------------------|---------------------------------------|  
    |**GST Base Amount**|10,000|  
    |**CGST**|900|  
    |**SGST**|900|
    |**IGST**|1800|

- GL Entries for Advance Payment made to Vendor, will be as following:

    |Particulars|Amount|
    |----------------------------------|---------------------------------------|  
    |**Vendor Account**|10,000|  
    |**SGST/UTGST Receivable (Interim) Account**|900|  
    |**CGST Receivable (Interim) Account**|900|
    |**SGST/UTGST Payable Account**|-900|
    |**CGST Payable Account**|-900|
    |**Bank Account**|-10000|

## <a name="reversal-of-advance-payment-made-to-vendor-where-there-are-reverse-charges"></a>Reversal of advance payment made to vendor, where there are reverse charges

If the vendor advance needs to be corrected or the entry is wrongly posted, in such a case the entry can be reversed and new entry can be created.

- Reversal GL Entries for Advance Payment made to Vendor, will be as following:

    |Particulars|Amount|
    |----------------------------------|---------------------------------------|  
    |**Bank Account**|10000| 
    |**SGST/UTGST Payable Account**|900|
    |**CGST Payable Account**|900|
    |**SGST/UTGST Receivable (Interim) Account**|-900|  
    |**CGST Receivable (Interim) Account**|-900|
    |**Vendor Account**|-10,000|  
    
> [!TIP]
> In case of Inter-State Advance Payment, IGST will be calculated.






































