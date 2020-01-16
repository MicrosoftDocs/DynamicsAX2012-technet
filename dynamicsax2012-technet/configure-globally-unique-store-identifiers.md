---
title: Configure globally unique store identifiers
TOCTitle: Configure globally unique store identifiers
ms:assetid: e9027a3d-3e45-4320-abde-7881d7b1400d
ms:mtpsurl: https://technet.microsoft.com/library/JJ733501(v=AX.60)
ms:contentKeyID: 49685465
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Configure globally unique store identifiers 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Store identifiers in Retail installations of Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012 R2, and Microsoft Dynamics AX 2012 R3 are shared globally across companies. Therefore, when you upgrade an installation of Microsoft Dynamics AX 2009 for Retail that has multiple companies, you must assign a globally unique identifier to each store.

Additionally, because Microsoft Dynamics AX 2012 R2 and R3 support data partitioning, globally shared store identifiers can exist only for companies that are contained in a single data partition. If you have multiple partitions that contain multiple companies, you must perform the following procedure separately on each partition. For more information about data partitions, see [Plan for data partitioning](plan-for-data-partitioning.md).


> [!NOTE]
> <P>Administrators who configure store IDs should use a consistent numbering scheme that complies with the retailer’s business requirements.</P>



Use the following procedure to map old store identifiers to new identifiers.

1.  Click the **Configure globally unique store identifiers** task in the checklist to open the form that has the same name.

2.  Microsoft Dynamics AX 2012 R2 and R3 only: In the **Partition key** field, select a partition.

3.  The grid in the form displays a list of stores and their associated companies in the source system. Use the **New store ID** field to assign a globally unique ID to each store.

4.  Click **Ready for upgrade**.

  


