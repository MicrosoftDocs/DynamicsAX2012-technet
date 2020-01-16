---
title: Set up date-controlled reservations
TOCTitle: Set up date-controlled reservations
ms:assetid: cb00af6e-d132-4c81-933d-b569a9b95168
ms:mtpsurl: https://technet.microsoft.com/library/Aa572665(v=AX.60)
ms:contentKeyID: 36059338
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up date-controlled reservations 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

1.  Click **Inventory management** \> **Setup** \> **Inventory** \> **Item model groups**.

2.  To set up the date reservation, select the inventory model group.

3.  To take the date of receipt of items into consideration when reserving them, click the **Setup** FastTab, and then select the **Date-controlled** check box.
    
    If the **Date-controlled** check box is cleared, available inventory with the lowest batch number will be reserved for sales orders.

4.  To reserve available inventory batches with a date of receipt that is closest to the sales order delivery date, select the **Backward from ship date** check box. This requires that the **Date-controlled** check box be selected.
    
    If the **Backward from ship date** check box is cleared, available inventory batches with the first date of receipt will be reserved for sales orders.

## See also

[Item model groups (form)](https://technet.microsoft.com/library/aa577092\(v=ax.60\))

  


