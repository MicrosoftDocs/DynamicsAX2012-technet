---
title: View the inventory close log
TOCTitle: View the inventory close log
ms:assetid: c8f7cd6d-9293-47b0-8a83-94a7ed906743
ms:mtpsurl: https://technet.microsoft.com/library/Gg213651(v=AX.60)
ms:contentKeyID: 36059324
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# View the inventory close log 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

After the inventory close process has been completed, an Infolog message may report that a unit cost price might be wrong because a transaction could not be fully settled.

Before this message is displayed, Microsoft Dynamics AX will report the item number and affected transaction. This message informs you that the cost amount used for this transaction was not updated because of inventory close. It appears when an issue type transaction cannot be settled.

During the inventory close process, Microsoft Dynamics AX checks each financial dimension to see if there are more issues than receipts up to the specified closing date. This type of imbalance can occur when an inventory transaction from a purchase order is not fully posted financially because the vendor invoice has not been received, or because bill of materials (BOM) components that are included in a production on a higher level are not financially posted. (Sub-production is not cost calculated.)

If this occurs, the subsequent closing will not adjust all issues to the correct cost price because not enough receipt information is available.

If **Has log** is selected in the **Closing and adjustment** form, an Infolog exists for the closing or recalculation. To open the Infolog, click **Log**.

If you are receiving many Infolog warnings, we recommend that you take the following actions:

  - Update receipts financially.

  - Advance the closing date.

  - Reevaluate the business procedures.

There might be circumstances where you cannot do anything about the Infolog warning. For example, when marking is used and the marked purchase order has a financial date after the closing date, the closing date cannot be changed.


> [!NOTE]
> <P>To obtain a list of items that cannot be settled during a closing, you can generate the <STRONG>Open quantity</STRONG> report using the closing date.</P>



## See also

[View inventory close settlements](view-inventory-close-settlements.md)

[Preparing to run inventory close](preparing-to-run-inventory-close.md)

[Run inventory close](run-inventory-close.md)

  


