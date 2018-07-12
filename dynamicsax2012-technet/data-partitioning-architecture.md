---
title: Data partitioning architecture
TOCTitle: Data partitioning architecture
ms:assetid: 27ba6c51-7ea7-4403-867a-46ccc1ee053a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ728665(v=AX.60)
ms:contentKeyID: 49556573
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Data partitioning architecture 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Microsoft Dynamics AX 2012 R2 enables data isolation by using data partitions. For example, an organization has several subsidiaries. If the management of the organization does not want employees of one subsidiary to have access to the data for other subsidiaries, data partitions can provide the boundaries that are required for data isolation.

Data partitions provide a logical separation of data in the Microsoft Dynamics AX database. To achieve this separation, Microsoft Dynamics AX adds a column to each table that contains data that must be isolated. This column contains a partition ID, which is the RecId of an entry in the **Partitions** table. In a partitioned table, rows that contain the same partition ID value belong to the same partition. The partition ID is also added to relevant indexes.

Partitions are defined in the **Partitions** form, where the system administrator creates the partition and provides a partition key. A partition key identifies a partition by using a unique string value that the system administrator specifies. Microsoft Dynamics AX displays the partition key in the title bar of the client application. Partitions can also be defined during installation and upgrade.

The following diagram illustrates the architecture for data partitioning.

![Data partitioning architecture](images/JJ728665.AX6_2_Sysdocs_partition_architecture_conceptual(AX.60).jpg "Data partitioning architecture")

**Microsoft Dynamics AX data partitioning architecture**

## Scope of data isolation

It is important to understand that data partitions do not create separate installations of Microsoft Dynamics AX. Consider the following characteristics of partitioned systems:

  - **Shared AOS** – A partitioned system is created in the context of a single instance of Microsoft Dynamics AX Application Object Server (AOS) or an AOS cluster. When Microsoft Dynamics AX is first set up, the system creates a default partition. The partition key for the default partition is "initial". Additional partitions can be created during installation or upgrade, or at any time after the system is deployed. After a partition has been created, it cannot be deleted.

  - **Shared database** – In a partitioned system, all data is stored in the same database or database cluster. Partitions provide only logical data separation. No physical isolation of data occurs. Many system tables are shared tables that do not contain a column for the partition ID.

  - **Shared AOT** – A partitioned system has one Microsoft Dynamics AX Application Object Tree (AOT). Customizations are always shared across all partitions. The model store database is not partitioned. Metadata that describes objects in the AOT is shared. Custom code is shared across the system.
    
    By default, code runs in the context of the partition for the current session. This behavior resembles the behavior of X++, which handles companies by using the dataAreaId field. Therefore, pre-existing code that uses the X++ query mechanism works without modification. Direct SQL calls must be modified to filter on the context of the current partition.
    
    For more information about using data partitions in development projects, see [Partitions, Companies, and Data Isolation in Microsoft Dynamics AX](https://technet.microsoft.com/en-us/library/jj677285\(v=ax.60\)).
    
    The Microsoft Dynamics AX cross-reference system is shared. Role definitions are shared across the system. In Microsoft Dynamics AX 2012 R2 and later versions, multi-partition configurations have no new requirements to define or maintain reports.

  - **Common administration** – Users who have the system administrator role can access data in all partitions. However, to view data in a particular partition, the administrator must log on to a client instance for that partition.
    
    System administrators can create new partitions. Both system administrators and security administrators can manage users in the context of a partition.
    
    License keys and configuration keys are shared across the system.

  - **Common application integration** – In a partitioned system, Services and Application Integration Framework (AIF) is a shared subsystem. To guarantee that incoming requests are correctly isolated, you can restrict an inbound integration port to a particular partition. Additionally, you can specify a target partition for an incoming request by including the partition key in an XML element in the header of the document. Similarly, outbound responses indicate the source partition for the response data by including the partition key in the header.
    
    Because AIF uses a single gateway queue, a system administrator can view all documents in the queue, AIF history, or exceptions list in any partition. The forms that display these lists now have a field that shows the partition key for each document.

  - **Common batch framework** – Like AIF, the batch processing framework is a shared subsystem. One batch server is shared across partitions. However, each batch job is associated with a specific partition. The batch server executes batch jobs in the context of the correct partition. To view batch jobs or their history, you must log on to the partition that the batch jobs are associated with.

  - **Separate application data** – Access to application data is controlled by a combination of the partition ID and the user's role and permissions. The Microsoft Dynamics AX client does not let users view unified data across partitions. Microsoft Dynamics AX does not provide a query mechanism to retrieve and combine data from multiple partitions.

  - **Separate organizational hierarchies** – Each partition contains its own organizational hierarchy, which includes one or more legal entities. Like a new deployment of Microsoft Dynamics AX, each partition that is created contains the DAT company as a default legal entity. System administrators can add legal entities to each partition. Legal entities are never shared between partitions, even if the legal entities have the same name.

  - **Separate user configurations** – Each partition contains its own list of authorized users. The system administrator who created the partition is automatically created as a user who has the system administrator role in the new partition. After a system administrator logs on to a partition, he or she can add authorized users to the partition.
    
    A user can be authorized to access data in more than one partition. However, the user must be created and managed separately in each partition. This user must use a separate client configuration to start a separate client session for each partition. Each user is associated with a default partition. This default partition can be changed by a system administrator. A user who logs on to Microsoft Dynamics AX by using a default client configuration is logged on to the user's default partition.
    
    The Microsoft Dynamics AX client application displays the partition key for the current session in the title bar of the main window.
    
    User roles are assigned for each partition.

  


