---
title: Service Transfer
description: Service Transfer
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 96595eeacc9578dd56327905526efaa14d382059
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948628"
---
# <a name="service-transfer"></a>Service Transfer

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

Service transfers between locations, branches or divisions having different registration numbers are taxable under GST. In such a case, if services transferred within the state from one location to another, then CGST and SGST/UTGST will be levied, other-wise, where the registration number is same, there shall be no levy. Service transferred from one state to another state, then IGST will be levied.

## <a name="create-a-service-transfer-order"></a>Create a service transfer order

1. Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **Service Transfer Order** , and then choose the related link. 
2. Select **Transfer-from Code** and **Transfer-to Code** on **Service Transfer Order** header. State Code and GST registration number should not be blank on **Location** card.
3. Select **Ship Control Account** and **Receive Control Account** on **Service Transfer Order** header.

4. Select G/L Account for **Transfer From G/L Account No.** on **Shipment Line** and **Transfer To G/L Account No.** on **Receipt Line** . GST Group Code, HSN/SAC Code should not be blank on **G/L Account** card.

For example, service for INR 10000 is being transferred on which 18% GST (9% CGST and 9% SGST/UTGST in case of Intra-State or Intra-Union Territory transaction or 18% IGST in case of Inter-State transaction), has to be charged.

- GST Calculation on Service Transfer Order will appear in the Fact Box, as following:
    
    |Component|Amount|
    |----------------------------------|---------------------------------------|  
    |**GST Base Amount**|10000|  
    |**IGST**|1800|
    |**CGST**|900| 
    |**SGST**|900|

- On posting of shipment in case of Intra-State or Intra-Union Territory service transfer, GL Entries will be as following:

    |Particulars|Amount|
    |----------------------------------|---------------------------------------|  
    |**Inter-location Control Account**|11800|
    |**CGST Payable Account**|-900|
    |**SGST/UTGST Payable Account**|-900|
    |**Services Account**|-10000|

- On posting of receipt in case of Intra-State or Intra-Union Territory service transfer, GL Entries will be as following:
    
    |Particular|Amount|
    |----------------------------------|---------------------------------------|  
    |**Services Account**|10000|  
    |**SGST/UTGST Receivable Account**|900|  
    |**CGST Receivable Account**|900|
    |**Inter-location Control Account**|-11800|

- On posting of shipment in case of Interstate service transfer, GL Entries will be as following:
    
    |Particular|Amount|
    |----------------------------------|---------------------------------------|  
    |**Inter-location Control Account**|11800|
    |**IGST Payable Account**|-1800|
    |**Services Account**|-10000|

- On posting of receipt in case of Interstate service transfer, GL Entries will be as following:
    
    |Particular|Amount|
    |----------------------------------|---------------------------------------|  
    |**Services Account**|10000|
    |**IGST Receivable Account**|1800|
    |**Inter-location Control Account**|-11800|






































