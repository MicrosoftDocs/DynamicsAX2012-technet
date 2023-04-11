---
title: Run an estimation
TOCTitle: Run an estimation
ms:assetid: 181f2ffb-aa08-4244-b400-8724c7a75125
ms:mtpsurl: https://technet.microsoft.com/library/Aa569905(v=AX.60)
ms:contentKeyID: 36056093
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Run an estimation 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Estimation is the first of the update jobs in the production life cycle. For more information about the various steps in the life cycle, see [About the production process](about-the-production-process.md).

1.  Click **Production control** \> **Periodic** \> **Production orders** \> **Estimation**.

2.  Click **Select**.

3.  Use the query function to select the production order to estimate. For more information about querying for production orders, see the [Inquiry (form)](https://technet.microsoft.com/library/aa575929\(v=ax.60\)).

4.  Click **OK**.

5.  In the **Estimation** form, click **OK** to run the estimation. When it is complete, the status of the production is **Estimated**.

Depending on the selections that you make, several steps occur when you run estimation.

The following information describes the steps in the estimation process.

## Explosion of phantom lines

If a BOM line contains the **Line type** of **Phantom**, it is exploded when estimation is run and the following actions occur:

  - The phantom line is deleted.

  - The BOM lines in the BOM item that the phantom line pointed to are inserted in the BOM and replace the deleted phantom line.

  - The route to the BOM item that the phantom line pointed to is inserted in the production route.

For more information, see [About line types](about-line-types.md).

## Calculation of references

If this option is selected under the **General** tab, any production references attached to the production order are calculated, including all subproductions. The field is always selected on productions that have not yet been estimated. If you clear it, the estimation includes only what is complete in the internal production.

## Calculation of item consumption and creation of inventory transactions

The item consumption is calculated per BOM line. Consumption is calculated as the quantity specified for the BOM line times the production quantity, taking any conversion factor from BOM units to inventory units into account.

During this process, inventory transactions are created for component items. If there is material consumption (positive quantity specified) for a component item, you can create an issue transaction with an **On order** status. If, on the other hand, there is item profit (negative quantity specified), you can create a receipt transaction with an **Ordered** status.

## Creation of purchases and subproductions

If the production BOM contains BOM lines of the **Line type** of **Vendor**, you can create either a purchase or a vendor production. If the item has a **BOM** item type, you can create a vendor production or you can create a purchase order for the item.

If there are BOM lines of the **Line type** of **Production** in the production BOM, you can create a subproduction for the item. However, the item must, be of the **BOM** item type because productions only can be created for this kind of item.

## Calculation of route consumption

The route consumption is calculated. Quantity-dependent time (process time) is calculated based on the production quantity. This is because time is calculated according to the "process time per quantity" for the resource and the production quantity. Quantity-independent time (setup time) is calculated based on the times specified for the individual resources, regardless of the production quantity.

## Reservation of items

Reservations of the estimated item consumption for the BOM lines are made. Whether or not reservations are necessary depends on the settings in the **Reservation** field for the production order.

## Cost estimate of sub-productions

Estimations are calculated for any subproductions. A cost estimate of subproductions follows all of the estimation steps described here.


> [!NOTE]
> <P>If there are BOM lines of the <STRONG>Line type</STRONG> of <STRONG>Production</STRONG> in a subproduction, a new subproduction subordinate to the first is created, which again follows all the steps described here.</P>



## Price calculation

This step includes the price calculation of the production, its subproductions, and their subproductions.

## See also

[About production order status](about-production-order-status.md)

  


