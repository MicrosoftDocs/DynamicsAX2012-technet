---
title: Create refill pallet transports for picking locations
TOCTitle: Create a refill pallet transport for a picking location
ms:assetid: 14332878-e240-4b11-9e49-78046cd59631
ms:mtpsurl: https://technet.microsoft.com/library/Gg230939(v=AX.60)
ms:contentKeyID: 36056052
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- pallet transport creation
- pallet transport for picking
- refill pallet transport
- refill pallet transport creation
audience: Application User
ms.search.region: Global
---

# Create refill pallet transports for picking locations 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic applies to features in the **Inventory management** module. It does not apply to features in the [Warehouse management](warehouse-management.md) module.

You can create a refill pallet transport with a full or partial refill from the bulk location to the picking location.

1.  Click **Inventory management** \> **Common** \> **Pallet transports**.

2.  Select the pallet that you want to start the transport for. If you want to ensure that no other employee can start this transport, click **Lock transport**.

3.  Click **Start transport**.

4.  In the **Start transport** form you can view the pallet ID that the program automatically assigns for the to location.
    

    > [!NOTE]
    > <P>If the transport is a partial refill, you can assign a new pallet at the to location by clicking <STRONG>Create new To pallet</STRONG> and assign the pallet that you want to assign to the transport. Enter the relevant information in the <STRONG>Pallet type</STRONG> and <STRONG>Pallet ID</STRONG> fields. Click <STRONG>OK</STRONG>. The program sets the status to <STRONG>Started</STRONG>.</P>



5.  Click **Complete transport**.
    

    > [!NOTE]
    > <P>If you have not specified the to location pallet and this is required, the program prompts you to assign a pallet at the to location in the <STRONG>Complete transport</STRONG> form.</P>



## See also

[About refill pallet transports](about-refill-pallet-transports.md)

[About pallet transports](about-pallet-transports.md)

  


