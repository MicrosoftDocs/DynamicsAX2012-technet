---
title: Plan for data partitioning
TOCTitle: Plan for data partitioning
ms:assetid: bc872bc1-1575-4de7-b9f4-49c5296f0298
ms:mtpsurl: https://technet.microsoft.com/library/JJ728668(v=AX.60)
ms:contentKeyID: 49556575
author: Khairunj
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Plan for data partitioning 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic provides information that you should consider before you implement the data partitioning feature of Microsoft Dynamics AX 2012 R2. You must be a member of the system administrator role to configure partitions.

## Decision points

Occasionally, you must make decisions about data partitions or create a new partition. Before you plan your implementation, it is important that you understand when and how you can work with partitions. The following list describes some of these decision points:

  - **Installation** – When Microsoft Dynamics AX is installed, the setup creates a default partition. This partition is identified by the partition key that is named **initial**. During installation, you are prompted to create additional partitions as a step in the **Initialization checklist**. However, you do not have to create additional partitions at this point. You can create a new partition any time after installation.
    
    You must initialize the initial partition and any partitions that you create by using the **Partition initialization checklist**.

  - **Upgrade** – During an upgrade from Microsoft Dynamics AX 4.0 or Microsoft Dynamics AX 2009 to Microsoft Dynamics AX 2012 R2, you can create new partitions. You can then map companies, which are equivalent to legal entities in Microsoft Dynamics AX 2012 R2, from the source environment to partitions in the target environment. These steps occur as part of the **Preprocessing upgrade checklist**. You can map all companies to the initial partition, map each company to its own partition, or create any combination of companies and partitions that you require.
    

    > [!IMPORTANT]
    > <P>During an upgrade from Microsoft Dynamics AX 2012 or Microsoft Dynamics AX 2012 Feature Pack to Microsoft Dynamics AX 2012 R2, you cannot add partitions.</P>



  - **After deployment or upgrade** – You can create a new partition any time after deployment by using the **Partitions** form. However, you can never delete a partition.
    

    > [!IMPORTANT]
    > <P>You cannot move a company from one partition to another.</P>



  - **Implementation of financial functionality** – Business data cannot be shared across partitions. Financial functionality that depends on the sharing of data is not available between legal entities when the legal entities are in different partitions.
    
    For example, information for the following financial functionality cannot be shared across partitions and is available only between legal entities that are in the same partition. This list is not exhaustive.
    
      - Intercompany transactions for customer invoices, purchase orders, sales orders, and vendor invoices
    
      - Consolidation transactions
    
      - Elimination transactions
    
      - Centralized payments for customers and vendors
    
      - Allocation transactions

## Number of partitions

To help decide the number of partitions that you require, consider the following questions.

## Is partitioning necessary?

If you do not have to isolate data between legal entities, you do not have to create additional partitions. The initial partition is sufficient for your requirements. However, lots of data is shared between legal entities in Microsoft Dynamics AX 2012 R2. For example, products and parties are global for all companies in a partition. If you do not want this kind of data to be shared, you must create additional partitions. In any case, metadata such as role definitions is shared across all partitions.

## How many legal entities require that their data be isolated?

You must identify each set of one or more legal entities that have sensitive data that other legal entities must not access. Each set requires one partition.

For example, your parent organization has three subsidiaries, and each subsidiary must be isolated from the others. This scenario requires three partitions. Therefore, you create two new partitions, so that the system has a total of three partitions.

## Which legal entities will be in each partition?

Each partition can contain one or more legal entities. Users are configured separately for each partition. Users in a partition might be able to access data from all legal entities in the partition. Therefore, it sometimes is useful to model each partition so that it contains only one legal entity. Role-based security in Microsoft Dynamics AX lets you restrict the data that users in a partition can access, based on the company. This data includes share data. If a role enables access to shared data, users who have the role can see shared data across legal entities in the partition.

In upgrade scenarios, it is especially important that you understand, before you begin the upgrade, how companies map to partitions. During one step of the upgrade, you must explicitly map companies from the source system to partitions in the target system. You must plan carefully for this mapping.

## Do existing legal entities share data?

When you upgrade from an earlier version of Microsoft Dynamics AX, determine whether the existing installation, or source system, contains companies that share business data. If companies in the source system share business data, do not plan to map these companies to different partitions. Mapping companies that share data into different partitions breaks the existing data references.

## Security

To help decide the security configuration of each partition, consider the following questions.

## Who should have access to each partition?

Although the set of roles, duties, and privileges is defined one time for the system, each partition has its own list of authorized users. You must plan which users will be authorized to access each partition. You must also plan which roles, duties, and privileges each user will have in each partition.

After you create a partition, you must create the users for the partition. To create users for a partition, you must log on to the partition by using a Microsoft Dynamics AX client configuration that specifies the partition key. For more information about how to create users, see [Create new users in Microsoft Dynamics AX](create-new-users-in-microsoft-dynamics-ax.md).

## Which users have access to multiple partitions?

When a user has access to more than one partition, you can specify one of the partitions as the default partition for the user. The default partition for a user is the partition that the user can log on to by using a default configuration of the Microsoft Dynamics AX client. For each user who can access multiple partitions, you should determine which partition is the default partition. You can specify the default partition for a user by logging on to the partition and then selecting the **Current partition is default partition** check box in the **User** form.

## Which users must have access to all partitions?

System administrators have access to all partitions in the system. If a user requires access to all partitions, consider whether the user should have the system administrator role. Remember that the system administrator role grants many privileges that may not be appropriate for every user. Instead of making the user an administrator, a better approach might be to add the user to every partition as a separate user who has non-administrative roles.

## See also

[Data partitioning architecture](data-partitioning-architecture.md)

  


