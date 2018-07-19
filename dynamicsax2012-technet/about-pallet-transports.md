---
title: About pallet transports
TOCTitle: About pallet transports
ms:assetid: 0f19b6c8-2d90-4781-b011-fe4f749c419a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa496416(v=AX.60)
ms:contentKeyID: 36056017
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- handle pallet transports
- warehouse location
audience: Application User
ms.search.region: Global
---

# About pallet transports 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic applies to features in the **Inventory management** module. It does not apply to features in the [Warehouse management](warehouse-management.md) module.

The forklift operator, who drives around in the warehouse and makes sure that all the items are placed in the correct location, can use the **Pallet transports** form to handle the pallet transports.

To start a transport job, update the overview by clicking **Update lines**.

Activate pallet transports from the **Shipments** form, or from the **Item arrival** or **Production input** journal. Whole pallets will start a pallet transport; otherwise, a picking route is started.

You can also request to refill a picking location by using a pallet from a bulk location in the **Inventory locations** form.

The order of the pallet transports depends on priority settings in the **Inventory and warehouse management parameters** form. You can set priorities and, thus, the sequence for input and output transport – in addition to refilling – on the **Transport** tab.

## Pallet ID

The pallet ID is the identification of the pallet on which an item is placed. A pallet ID consists of a number on the pallet and the pallet type. A pallet can be any container, box, or pallet that is used for the storage or transport of items. The size of the pallet is indicated for the pallet type, and Microsoft Dynamics AX can then calculate which locations have space for this pallet type and, thus, for the specific pallet.

## See also

[About refill pallet transports](about-refill-pallet-transports.md)

[Start pallet transports](start-pallet-transports.md)

[Complete pallet transports](complete-pallet-transports.md)

  


