---
title: Automatic Breaking Bulk with Directed Put-away and Pick | Microsoft Docs
description: For locations that use directed put-away and pick, you can break a larger unit of measurement into smaller units of measurement, when it creates warehouse instructions that fulfil the needs of source documents, production orders or internal picks and put-aways.
author: SorenGP
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: ''
ms.date: 10/01/2020
ms.author: edupont
ms.openlocfilehash: ea8cbc3b701d8e4fab0d720390db7bab6e1a4e59
ms.sourcegitcommit: ddbb5cede750df1baba4b3eab8fbed6744b5b9d6
ms.translationtype: HT
ms.contentlocale: en-IN
ms.lasthandoff: 10/01/2020
ms.locfileid: "3960013"
---
# <a name="enable-automatic-breaking-bulk-with-directed-put-away-and-pick"></a>Enable Automatic Breaking Bulk with Directed Put-away and Pick
For locations that use directed put-away and pick, [!INCLUDE[d365fin](includes/d365fin_md.md)] can, in various situations, automatically breakbulk, that is, break a larger unit of measurement into smaller units of measurement, when it creates warehouse instructions that fulfil the needs of source documents, production orders or internal picks and put-aways. To breakbulk sometimes also means gathering smaller units of measurement, if necessary, to meet outbound requests by breaking the larger unit of measurement on the source document or production order into the smaller units of measurement that are available in the warehouse.   

## <a name="breakbulking-in-picks"></a>Breakbulking in Picks  
If you want to store items in several different units of measurement and allow them to be automatically combined as needed in the picking process, select the **Allow Breakbulk** field on the location card.  

To fulfil a task, application automatically looks for an item in the same unit of measurement. But if it cannot find this form of the item and this field is selected, the application will suggest that you break a larger unit of measurement into the unit of measurement that is needed.  

If the system can only find smaller units of measurement, it will suggest that you gather items to fulfil the quantity on the shipment or production order. In effect, it breaks the larger unit of measurement on the source document into smaller units for picking.  

## <a name="breakbulking-in-put-aways"></a>Breakbulking in Put-aways  
In the warehouse put-away, the application automatically suggests Place action lines in the put-away unit of measurement, for example, pieces, even though the items arrive in a different unit of measurement.  

## <a name="breakbulking-in-movements"></a>Breakbulking in Movements  
The application also breakbulks automatically in replenishment movements, if the **Allow Breakbulk** field is selected on the **Option** FastTab on the **Calculate Bin Replenishment** page.  

You can view the results of the conversion process from one unit of measurement to another as intermediate breakbulk lines in the put-away, pick or movement instructions.  

> [!NOTE]  
>  If you select the **Set Breakbulk Filter** field on the warehouse instruction header, the application will hide the breakbulk lines whenever the larger unit of measurement is going to be completely used. For example, if a pallet is 12 pieces and you are going to use all 12 pieces, the pick will then direct you to take 1 pallet and place 12 pieces. However, if you have to pick only 9 pieces, then the breakbulk lines will not be hidden, even if you have selected the **Breakbulk Filter** field, because you have to place the remaining three pieces somewhere in the warehouse.  

> [!NOTE]  
>  If you want your units of measurement to perform optimally in the warehouse, also in connection with the breakbulk functionality, wherever possible, you should try to:  
>   
> - Set up the base unit of measurement for an item as the smallest unit of measurement that you expect to handle in your warehouse processes.  
> - Set up your alternative units of measurement for the item as multiples of the base unit of measurement.  

## <a name="see-also"></a>See Also  
[Warehouse Management](warehouse-manage-warehouse.md)  
[Inventory](inventory-manage-inventory.md)  
[Setting Up Warehouse Management](warehouse-setup-warehouse.md)     
[Assembly Management](assembly-assemble-items.md)    
[Design Details: Warehouse Management](design-details-warehouse-management.md)  
[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  
