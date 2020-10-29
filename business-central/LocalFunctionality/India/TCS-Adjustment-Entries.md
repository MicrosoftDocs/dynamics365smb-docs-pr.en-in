---
title: TCS Adjustment Entries
description: TCS Adjustment Entries
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: 2813ddebc9e69513c66635c2810da5736663e8d1
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948617"
---
# <a name="tcs-adjustment-entries"></a>TCS Adjustment Entries

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

TCS adjustment is applicable for any correction of the TCS amount, TCS rate and TCS base amount already calculated but not paid to the government authorities. Provision is available to enter the new TCS rates, new TCS amount and new TCS base amount for the TCS entry which was created against invoice or payment and not paid to the government authorities. System should recalculate TCS amount and adjustments would be made accordingly. The revised TCS amount should be updated in the relevant GL Accounts for TCS Payable and Customer Account. Existing TCS entry should be updated with revised TCS percentages, TCS amount and TCS base amount.

## <a name="tcs-adjustment-process"></a>TCS adjustment process

1. Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **TCS Adjustment Journal** , and then choose the related link.
2. Select the relevant transaction number in **Transaction No.** field from the drop down, and the selected line, will get populated with the posted record. Following information can be changed, in the adjustment journal as per the requirements:
  
    |Field Name|Use|
    |----------------------------------|---------------------------------------|  
    |**TCS % Applied**|Fill the revised TCS %.|  
    |**Surcharge % Applied**|Fill the revised Surcharge %.|
    |**eCESS % Applied**| Fill the revised eCess %.|
    |**SHE Cess % Applied**|Fill the revised SHE Cess %.|
    |**TCS Base Applied**|Fill the revised TCS base amount.|

3. On posting of the adjustment journal G/L Entry, TCS Entry, Customer Ledger Entry and Detailed Customer Ledger Entry will be updated with the adjusted amount and revised information.
























