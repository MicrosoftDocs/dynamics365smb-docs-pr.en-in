---
title: TDS Adjustments
description: TDS Adjustments
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 9d0a3b0ab22e0c6e4435eeecc0dbefd67256823e
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948612"
---
# <a name="tds-adjustments"></a>TDS Adjustments

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

TDS adjustment can be required, for any corrections in the TDS amount, TDS rate or TDS base amount already deducted but not paid to the government authorities. The revised TDS amount will be updated in the relevant GL Accounts for TDS Payable and Vendor Account. Existing TDS entry will be updated with revised TDS percentages, TDS amount and TDS base amount.

## <a name="tds-adjustment-process"></a>TDS adjustment process

1. Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **TDS Adjustment Journal** , and then choose the related link.
2. Select the relevant transaction number in **Transaction No.** field from the drop down, and the selected line will be populated with the posted record. Following information can be changed in the adjustment journal as per the requirement:
  
    |Field Name|Use|
    |----------------------------------|---------------------------------------|  
    |**TDS % Applied**|Fill the revised TDS %.|  
    |**TDS Base Applied**|Fill the revised TDS base amount.|

3. On posting of the adjustment journal G/L Entry, TDS Entry, Vendor Ledger Entry and Detailed Vendor Ledger Entry will be updated with the adjusted amount and revised information.
























