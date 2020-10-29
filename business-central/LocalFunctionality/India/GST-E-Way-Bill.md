---
title: E-Way Bill
description: E-Way Bill
author: v-debapd
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: India, local, IN, English
ms.date: 10/01/2020
ms.author: v-debapd
ms.openlocfilehash: b8027072a2ff2310a464b269c85973690a3bece9
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3948654"
---
# <a name="e-way-bill"></a>E-Way Bill

[!INCLUDE[vnext_preview](../../includes/vnext_preview.md)]

An electronic way bill or e-Way Bill is essential for the transport of goods that are worth more than INR 50,000. There are also some goods for which an e-way bill is essential even if the amount does not exceed INR 50,000. E-Way Bill Template is designed to meet the formats or requirements provided by government. 

- Business user will be able to generate excel file from system which will be helpful for them to enter data into E-Waybill JSON Preparation tool. Business user can copy and paste data from excel sheet exported from system to preparation tool.
- Transactions posted through Journals will not be a part of E-Waybill template report. User will be able to generate E-Waybill template against transactions posted from documents only.
- User will be able to generate E-Waybill for movement of goods for Transfers (shipment), Sales and Purchase transactions. System will only consider Items and FA with GST Group Type as 'Goods' in this report.


## <a name="e-way-bill-template-generation"></a>E-Way Bill template generation

- E-Way Bill template feature enables the user to generate excel file from system which will be helpful for them to enter data into E-Waybill JSON Preparation tool.

  1. Choose the ![Search for Page or Report](image/search_small.png "Search for Page or Report icon") icon, enter **E-Way Bill File Format** , and then choose the related link.
  2. GST Registration No. and State Code should be updated for **Shipping Agent** .
  3. Transportation Mode field should not be blank in **Transport Method**
  4. Select the following information in the request page and click OK to generate the report

     |Field|Description|
     |---------|---------|
     |**Start Date**|Specifies the starting date of the report.|
     |**End Date**|Specifies the ending date of the report.|
     |**Location Registration No.**|Specifies the GST registration number for which report will be generated.|
     |**Transaction Type**|Select the relevant Transaction Type.|
     |**Source Type**|Specify the relevant source type.|
     |**Source No.**|Specify the relevant source number.|




