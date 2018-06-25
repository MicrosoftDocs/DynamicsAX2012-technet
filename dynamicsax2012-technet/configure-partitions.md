---
title: Configure partitions
TOCTitle: Configure partitions
ms:assetid: 75c6aa31-b1a0-41d3-8709-8d0986ce33ff
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ721415(v=AX.60)
ms:contentKeyID: 49729979
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Configure partitions [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Microsoft Dynamics AX 2012 R2 and R3 enable data isolation by using data partitions. For example, an organization that is a holding company has several subsidiaries. If the management of the organization does not want employees of one subsidiary to have access to the data for other subsidiaries, data partitions can provide the boundaries that are required for data isolation but enable the metadata that supports business processes to be shared.

Data partitions provide a logical separation of data in the Microsoft Dynamics AX database. To achieve this separation, Microsoft Dynamics AX adds a column to each table that contains data that must be isolated. This column contains a partition ID, which is the RecId of an entry in the **Partitions** table. In a partitioned table, rows that contain the same value for the partition ID belong to the same partition. The partition ID is also added to relevant indexes. A partition key identifies a partition by using a unique string value. Microsoft Dynamics AX displays the partition key in the title bar of the client application and in various administration forms.

When Microsoft Dynamics AX is installed, the setup always creates a single, default partition. This partition is identified by the partition key "Initial".

Each partition contains its own organizational hierarchy, which includes one or more legal entities. Like a new deployment of Microsoft Dynamics AX, each new partition that is created contains the DAT company as a default legal entity. System administrators can add legal entities to each partition. Legal entities are never shared between partitions, even if the legal entities have the same name.

If you want to upgrade from Microsoft Dynamics AX 4.0 or Microsoft Dynamics AX 2009, it is especially important that you first understand how companies map to partitions. You must explicitly map companies in the source system to partitions in the target system. You must plan for this mapping carefully. Changes that are made to the partitioning arrangement after the upgrade process has been completed may be costly.

If you do not have to isolate data between companies, you do not have to create additional partitions. The initial partition is sufficient for your requirements. However, understand that some data is shared between companies in Microsoft Dynamics AX. For example, products and parties are global for all companies in a partition. If you do not want this kind of data to be shared, you must create additional partitions and then map the companies in the source system to the partitions in the target system.

The **Configure partitions** task opens the **Map companies to partitions** form. Use this form to map each company in the source system to the correct partition in the target system.

## Map companies to partitions

You can use the **Map companies to partitions** form to specify how companies are copied from the source system to the target system during upgrade.

1.  In the **Map companies to partitions** form, in the grid, review the mapping. By default, each company in the source system is mapped to the Initial partition in the target system. Therefore, all companies in the source system appear in a single partition in the target system.

2.  If this mapping is acceptable, click **Set ready for upgrade**. Close the warning message, and go to the next step in the checklist.

3.  If you have to change the mapping, you must create additional partitions. Click **Configure partitions**.

4.  In the **Configure partitions** form, press CTRL+N to add a new partition.

5.  In the **Partition key** field, type a string for the partition key. This string can contain a maximum of eight characters. This string is not case sensitive. This string will be visible to users and administrators of the target system.

6.  In the **Partition name** field, type a descriptive name for the partition.

7.  If you require more partitions, repeat steps 4 through 6 to add each partition.

8.  Close the **Configure partitions** form.

9.  In the **Map companies to partitions** form, select a partition key for each company.
    

    > [!WARNING]
    > <P>Do not map companies that share data to different partitions.</P>
    > <P>Partitions provide isolation of business data. If companies share data in the source system, and you map these companies to different partitions in the target system, the references to the shared data are broken.</P>



10. When you have finished specifying a partition for each company, click **Set ready for upgrade**.
    

    > [!WARNING]
    > <P>Carefully read the warning message. If you change the partition mapping after this step, you must restart the upgrade process.</P>


  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

