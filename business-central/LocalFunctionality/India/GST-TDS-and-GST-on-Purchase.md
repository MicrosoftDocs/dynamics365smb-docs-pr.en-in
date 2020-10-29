---
title: Calculation of Income Tax TDS and GST on Purchase Transactions
description: Calculation of Income Tax TDS and GST on Purchase Transactions
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 3167fb5903ecb2783d8bfb7c958a5926ba82df7f
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948620"
---
# <a name="calculation-of-income-tax-tds-and-gst-on-purchase-transactions"></a>Calculation of Income Tax TDS and GST on Purchase Transactions

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

There are certain services on which GST applies along with the provisions of TDS under income tax. TDS should not be calculated on GST amount, in some cases where payment terms is set as 100% advance, full order value has to be paid as advance payment. In such cases, amount paid to vendor will be inclusive of GST and if TDS has to deducted while paying amount to vendor, then TDS is deducted only on the base amount and not on GST amount.

## <a name="create-a-purchase-invoice"></a>Create a purchase invoice

1. Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Purchase Invoice** , and then choose the related link.
2. Select **Vendor** on **Invoice Header** .
3. Select **G/L Account** for Service purchase on **Purchase Invoice** line. GST Group Code, HSN/SAC Code should not be blank and GST Credit value should be selected as **Availment** if the tax input credit is available or else **Non-Availment** on the Item or G/L Account. 

For example, there is a purchase invoice for INR 10,000 and 18% GST (i.e. 9% CGST and 9% SGST/UTGST in case of Intra-State or Intra-Union Territory transaction or 18% IGST in case of Inter-State transaction) has to be charged and Income Tax TDS @10% also to be charged.

- GST calculation will appear in the Fact Box, as following :

    |Component|Amount|
    |----------------------------------|---------------------------------------|  
    |**Transaction Value**|10000|
    |**GST Base Amount**|10,000|  
    |**CGST**|900|  
    |**SGST**|900|
    |**IGST**|1800|
    |**TDS**|1000|

- GL Entries for Income Tax TDS and GST in Intra-State purchase transactions, will be as following:
    
    |Particular|Amount|
    |----------------------------------|---------------------------------------|  
    |**Service Account**|10000|  
    |**SGST/UTGST Receivable Account**|900|  
    |**CGST Receivable Account**|900|
    |**TDS Payable Account**|-1000|
    |**Vendor Account**|-10800|

- GL Entries for Income Tax TDS and GST in Intra-State or Intra-Union Territory purchase transactions (reverse charge) will be as following:
    
    |Particular|Amount|
    |----------------------------------|---------------------------------------|  
    |**Service Account**|10000|  
    |**SGST/UTGST Receivable Account (Interim)**|900|  
    |**CGST Receivable Account (Interim)**|900|
    |**TDS Payable Account**|-1000|
    |**Vendor Account**|-9000|
    |**SGST/UTGST Payable (Interim) Account**|-900|
    |**CGST Payable (Interim) Account**|-900|

- GL Entries for Income Tax TDS and GST in Inter-State purchase transactions, will be as following:
   
    |Particulars|Amount|
    |----------------------------------|---------------------------------------|  
    |**Service Account**|10000|
    |**IGST Receivable Account**|1800|
    |**TDS Payable Account**|-1000|
    |**Vendor Account**|-10800|

- GL Entries for Income Tax TDS and GST in Inter-State purchase transactions (reverse charge), will be as following:
    
    |Particular|Amount|
    |----------------------------------|---------------------------------------|  
    |**Service Account**|10000|
    |**IGST Receivable Account (Interim)**|1800|
    |**TDS Payable Account**|-1000|
    |**Vendor Account**|-9000|
    |**IGST Payable (Interim) Account**|-1800|







































