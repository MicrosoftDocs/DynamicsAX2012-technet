---
title: "What's new: Data partitioning"
TOCTitle: Data partitioning
ms:assetid: 2117ee49-3a6b-4f79-b43d-6440455a4cb7
ms:mtpsurl: https://technet.microsoft.com/library/JJ728664(v=AX.60)
ms:contentKeyID: 49556571
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- partition
- data partioning
- data partition
---

# What's new: Data partitioning 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Microsoft Dynamics AX 2012 R2 enables data isolation by using data partitions. For example, an organization that is a holding company has several subsidiaries. If the management of the organization does not want employees of one subsidiary to have access to the data for other subsidiaries, data partitions can provide the boundaries that are required for data isolation. However, data partitions enable the metadata that supports business processes to be shared.

## Data partitions

Data partitions provide a logical separation of data in the Microsoft Dynamics AX database. To achieve this separation, Microsoft Dynamics AX adds a column to each table that contains data that must be isolated. This column contains a partition ID, which is the RecId of an entry in the Partitions table. In a partitioned table, rows that contain the same partition ID value belong to the same partition. The partition ID is also added to relevant indexes.

Partitions are defined in the **Partitions** form, where the system administrator creates the partition and provides a partition key. A partition key identifies a partition by using a unique string value that the system administrator specifies. When AX 2012 R2 is installed, the setup program always creates a single, default partition. This partition is identified by the partition key **Initial**. Microsoft Dynamics AX displays the partition key in the title bar of the client application. Additional partitions can be defined during installation and upgrade.

Each partition contains its own organizational hierarchy, which includes one or more legal entities. Like a new deployment of Microsoft Dynamics AX, each new partition that is created contains the DAT company as a default legal entity. System administrators can add other legal entities to each partition. Legal entities are never shared between partitions, even if the legal entities have the same name.

## Special considerations

Data partitions do not create separate installations of Microsoft Dynamics AX. Partitioned systems share instances of Microsoft Dynamics AX Application Object Server (AOS), databases, the Microsoft Dynamics AX Application Object Tree (AOT), administration functionality, Microsoft Dynamics AX Application Integration Framework (AIF), and the batch framework. However, partitioned systems maintain separate application data, organizational hierarchies, and user configurations.

If you do not have to isolate data between companies, you do not have to create additional partitions. The default partition (**Initial**) that is created during installation is sufficient for your requirements.

## Upgrade

To upgrade from Microsoft Dynamics AX 4.0 or Microsoft Dynamics AX 2009, you must understand how companies map to partitions. You must explicitly map companies in the source system to partitions in the target system. You must plan carefully for this mapping. Changes that are made to the partitioning arrangement after the upgrade has been completed might be costly.

When you upgrade from AX 4.0 or AX 2009, you must first evaluate whether you require data isolation between companies. For example, the source system might use companies to isolate data. However, lots of data is shared between companies in AX 2012 R2. For example, products and parties are global for all companies in a partition. If you do not want this kind of data to be shared, you must create additional partitions.


> [!NOTE]
> <P>Metadata, such as role definitions, is shared across all partitions.</P>



During the upgrade process, you have the option to create new partitions. If you decide to create new partitions, you must then map companies in the source environment to partitions in the target environment. If you do not have to isolate data between companies, you do not have to create additional partitions. The default partition that is created during installation is sufficient for your requirements.

## Comparison with AX 2009

AX 2009 enabled data isolation by using companies. In Microsoft Dynamics AX 2012 and later versions, some data is shared between companies. For example, products and parties are shared across all companies in a partition. If you do not want this kind of data to be shared, you must create additional partitions and then create companies in the partitions. (Alternatively, you can map companies to partitions during the upgrade process.)

## See also

[Data partitioning architecture](data-partitioning-architecture.md)

[Plan for data partitioning](plan-for-data-partitioning.md)

  


