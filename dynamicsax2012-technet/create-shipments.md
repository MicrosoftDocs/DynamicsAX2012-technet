---
title: Create shipments
TOCTitle: Create shipments
ms:assetid: 6be95629-b433-493e-9c7c-d9a11bd75197
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa571193(v=AX.60)
ms:contentKeyID: 36057995
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- create shipment
- shipment
- shipment creation
---

# Create shipments 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic applies to features in the **Inventory management** module. It does not apply to features in the [Warehouse management](warehouse-management.md) module.

Use this information to create a shipment.

1.  Click **Inventory management** \> **Common** \> **Shipments**.

2.  Create a new shipment using the following mandatory fields: **Warehouse**, **Outbound dock**, and **Sequence ID**.
    
    For more information, see [Shipments (form)](https://technet.microsoft.com/en-us/library/aa615744\(v=ax.60\)).

3.  Click **Show lines** to open the **Shipment lines** form.

4.  Click **Add** to open the **Output order** form.

5.  Select the output order to add. In the **Quantity** field, enter the quantity to add to the shipment. Alternatively, select the **All** check box, which transfers the rest of the quantity to the shipment.

When the shipment has been created, reservations can be activated while the shipment includes lines that are still not in a route. You can click **Functions** \> **Reserve now** to reserve and allocate a picking route.

## Add lines to an existing shipment

When a shipment has been created and is in process, you can add lines until the shipment has actually been sent.

For more information, see [Shipments (form)](https://technet.microsoft.com/en-us/library/aa615744\(v=ax.60\)) and [Shipment lines (form)](https://technet.microsoft.com/en-us/library/aa557910\(v=ax.60\)).

## See also

[About shipments](about-shipments.md)

[Post packing slips and update information for shipping carriers](post-packing-slips-and-update-information-for-shipping-carriers.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

