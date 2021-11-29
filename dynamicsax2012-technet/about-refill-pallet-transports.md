---
title: About refill pallet transports
TOCTitle: About refill pallet transports
ms:assetid: 6fd54cde-5896-417b-b33b-85f706330346
ms:mtpsurl: https://technet.microsoft.com/library/Gg231821(v=AX.60)
ms:contentKeyID: 44080992
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- refill pallet transport
- create a refill pallet transport
- shipment reservation
audience: Application User
ms.search.region: Global
---

# About refill pallet transports 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic applies to features in the **Inventory management** module. It does not apply to features in the [Warehouse management](warehouse-management.md) module.

There are several ways to create a refill pallet transport.

  - You can create a refill pallet transport when you use shipment reservations in the **Shipment reservation combinations** form.

  - You can manually create a refill pallet transport from either the **Picking routes** form or from the **Picking locations** report.
    
      - Click **Inventory management** \> **Common** \> **Picking routes**.
    
      - Click **Inventory management** \> **Reports** \> **Base data** \> **Picking locations**.

  - You can run a batch job. To run a periodic batch job, click **Periodic** \> **Locations** \> **Create refill**.
    

    > [!NOTE]
    > <P>If you have set up automatic refill, you do not have to run this batch job.</P>



If the program should automatically start the refill transport, set up the picking area for automatic activation. Click **Inventory management** \> **Setup** \> **Inventory breakdown** \> **Store areas**. Select the store area that has the **Picking area** type, and then select the **Automatic activation** check box.

You specify the minimum quantity that is required for your picking location in the **Warehouse items** form. Click **Product information management** \> **Common** \> **Released products**. Then, on the **Manage inventory** tab, in the **Warehouse** group, select **Warehouse items**.

## Activate refill pallet transports

1.  Click **Inventory management** \> **Periodic** \> **Locations** \> **Create refill**.

2.  Click **Inventory management** \> **Setup** \> **Inventory breakdown** \> **Store areas**. If the **Automatic activation** check box is selected, pallet refill transports are created and started automatically when one of the following actions occurs:
    
      - A picking route is opened.
    
      - A picking route is started.
    
      - A refill pallet transport is completed.
    
      - During picking, the quantity becomes less than the minimum refill quantity.
        
        The refill check routine examines whether the physical on-hand quantity at the picking location is less than the minimum refill quantity. Picking lines that have a status of **Activated** or **Started** are examined.


> [!TIP]
> <P>To make sure that the number of pallets at the picking location does not become too large, you can set up a maximum storage capacity. Click <STRONG>Inventory management</STRONG> &gt; <STRONG>Periodic</STRONG> &gt; <STRONG>Forecast</STRONG> &gt; <STRONG>Entry</STRONG> &gt; <STRONG>Items</STRONG>. On the <STRONG>Manage inventory</STRONG> tab, in the <STRONG>Warehouse</STRONG> group, click <STRONG>Warehouse items</STRONG>. Then, on the <STRONG>Locations</STRONG> tab, in the <STRONG>Max. storage capacity</STRONG> field, enter the maximum storage capacity. This maximum capacity can be exceeded only if a manual refill is processed, and if an input transport is processed from an incoming dock location to an item picking location.</P>



## See also

[Store areas (form)](https://technet.microsoft.com/library/aa550377\(v=ax.60\))

[Warehouse items (form)](https://technet.microsoft.com/library/aa587742\(v=ax.60\))

[About pallet transports](about-pallet-transports.md)

[Create refill pallet transports for picking locations](create-refill-pallet-transports-for-picking-locations.md)

[About pallet transports](about-pallet-transports.md)

[Shipment reservation combinations (form)](https://technet.microsoft.com/library/hh209514\(v=ax.60\))

[About shipment reservations](about-shipment-reservations.md)

  


