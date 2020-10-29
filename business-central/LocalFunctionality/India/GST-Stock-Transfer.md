---
title: Stock Transfer
description: Stock Transfer
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 51598cac372002427564472185a9d9f61617e716
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948625"
---
# <a name="stock-transfer"></a>Stock Transfer

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

Stock transfers between locations, branches or divisions having different registration numbers are taxable under GST. In such a case, where registration number is same, if the shipment location and recipient location both are in the same state, then CGST and SGST/UTGST are levied, other-wise, where the registration number is same, there shall be no levy.

1.  Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Transfer Order** , and then choose the related link. 
2. Select **Transfer-from Code** and **Transfer-to Code** on **Transfer Order** header.  State Code and GST registration number should be filled on the location master.

3. Select **Item** on **Transfer Order** line. GST Group Code, HSN/SAC Code should be filled on **Item** .


For example, inventory for INR 1000 is being transferred from one location to another and 18% GST (9% CGST and 9% SGST/UTGST in case of Intra-State or Intra-Union Territory transaction or 18% IGST in case of Inter-State transaction) has to be charged on INR 1000.

- GST calculation will appear in the Fact Box, as following:
    
    |Component|Amount|
    |----------------------------------|---------------------------------------|  
    |**GST Base Amount**|1000|  
    |**IGST**|180|
    |**CGST**|90| 
    |**SGST**|90|

Post the Transfer Order

- GL Entries for shipment transaction in case of Interstate stock transfer, will be as following:

    |Particulars|Amount|
    |----------------------------------|---------------------------------------|  
    |**Unrealised Profit Account**|180|
    |**IGST Payable Account**|-180|
    |**Inventory Adjustment Account**|1000|
    |**Inventory Account**|-1000|

- GL Entries for receipt transaction in case of Interstate stock transfer, will be as following:
    
    |Particulars|Amount|
    |----------------------------------|---------------------------------------|  
    |**IGST Receivable Account**|180|  
    |**Unrealised Profit Account**|-180|  
    |**Inventory Account**|1000|
    |**Inventory Adjustment Account**|-1000|

- GL Entries for shipment transaction in case of Intra-State or Intra-Union Territory stock transfer, will be as following:

    |Particulars|Amount|
    |----------------------------------|---------------------------------------|  
    |**Unrealised Profit Account**|180|  
    |**CGST Payable Account**|-90|
    |**SGST/UTGST Payable Account**|-90|  
    |**Inventory Account**|-1000|
    |**Inventory Adjustment Account**|1000|

- GL Entries for receipt transaction in case of Intra-State or Intra-Union Territory stock transfer, will be as following:

    |Particulars|Amount|
    |----------------------------------|---------------------------------------|  
    |**Unrealised Profit Account**|-180|  
    |**CGST Receivable Account**|90|
    |**SGST/UTGST Receivable Account**|90|  
    |**Inventory Account**|1000| 
    |**Inventory Adjustment Account**|-1000|

## <a name="stock-transfer-for-bonded-warehouse"></a>Stock transfer for bonded warehouse

Bonded warehouse transfer means transfer of stock from customs warehouse to company warehouse. This scenarios occurs when material is stored at customs warehouse before moving it to company’s warehouse. In this case the customs duty will be paid only when material is moved from bonded warehouse.

1. Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Transfer Order** , and then choose the related link. 
2. Select **Transfer-from Code** and **Transfer-to Code** on **Transfer Order** header. 
3. State Code and GST registration number should be filled on Transfer-to **Location** .
4. **Bonded warehouse** field should be marked true on Transfer-from **Location** .

3. Select **Item** on **Transfer Order** line. GST Group Code, HSN/SAC Code should be filled on **Item** .

4. Enter **GST Assessable Value** and **Custom Duty Amount** on **Transfer Order** lines. System calculates GST on GST Assessable Value and Custom Duty Amount, not on transaction line amount.

5. **Bill of Entry Number** , **Bill of Entry Date** and **Vendor Code** on **Transfer Order** header should not be blank.






































