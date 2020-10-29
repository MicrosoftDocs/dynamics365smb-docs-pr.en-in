---
title: Purchase Return to Registered Vendor
description: Purchase Return to Registered Vendor
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 64c7531a8cb9d7fd8750a8f8bdd139ae58c03b2e
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948646"
---
# <a name="purchase-return-to-registered-vendor"></a>Purchase Return to Registered Vendor

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

A registered vendor is a person who is registered with GST authorities. For purchases from registered vendors for services attracting reverse charge, purchasers themselves has to pay tax to the government.
If exempted goods and services are purchased from registered Vendor, then no GST is to be paid to supplier or to the Government.

A buyer may have to return the goods or issue credit note due to various reasons like damaged goods, quality issues etc.

Process for purchase returns to registered vendor has been explained in this document.


## <a name="create-a-purchase-return-order-or-credit-memo"></a>Create a purchase return order or credit memo

1.  Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Purchase Return Order** or **Purchase Credit Memo** , and then choose the related link. 
2. Select **Vendor** on **Purchase Credit Memo** header, GST vendor type should be **Registered** .
3. Select **Item Code** for goods, **G/L Account** for Service purchase, **Fixed Asset** for Fixed Asset purchase and **Charge (Item)** for Item Charge on **Purchase Credit Memo** line. GST Group Code, HSN/SAC Code and GST Credit value should be selected as **Availment** if the tax input credit is available or else **Non-Availment** on the Item, G/L Account, Fixed Asset, Charge (Item). 

For example, purchase credit memo or return order is issued for INR 10000 on which 18% GST (9% CGST and 9% SGST/UTGST in case of Intra-State or Intra-Union Territory transaction or 18% IGST in case of Inter-State transaction), has to be charged.

- GST calculation will appear in the Fact Box, as following:
    
    |Component|Amount|
    |----------------------------------|---------------------------------------|  
    |**GST Base Amount**|10,000|  
    |**CGST**|900|  
    |**SGST**|900|
    |**IGST**|1800| 

- GL Entries for Intra-State or Intra-Union Territory purchase return of goods, service, fixed asset and item charge to registered vendor where input tax credit is available, will be as following:

    |Particulars|Amount|
    |----------------------------------|---------------------------------------|
    |**Vendor Account**|11800|
    |**SGST/UTGST Receivable Account**|-900|
    |**CGST Receivable Account**|-900|
    |**Purchase or Service Account or Fixed Asset increase during the year**|-10000|

- GL Entries for Intra-State or Intra-Union Territory purchase return of goods, service, fixed asset and item charge to registered vendor where input tax credit is not available, will be as following:

    |Particulars|Amount|
    |----------------------------------|---------------------------------------|
    |**Vendor Account**|11800|
    |**Purchase or Service Account or Fixed Asset increase during the year**|-11800|


- GL Entries for Inter-State purchase return of goods, services, fixed asset, charge item to registered vendor where input tax credit is available, will be as following:

    |Particulars|Amount|
    |----------------------------------|---------------------------------------|    
    |**Vendor Account**|11800| 
    |**IGST Receivable Account**|-1800| 
    |**Purchase or Services Account or Fixed Asset increase during the year**|-10000|

- GL Entries for Inter-State purchase return of goods, services, fixed asset, charge item to registered vendor where input tax credit is not available, will be as following:

    |Particulars|Amount|
    |----------------------------------|---------------------------------------|
    |**Vendor Account**|11800| 
    |**Purchase or Services Account or Fixed Asset increase during the year**|-11800|





































