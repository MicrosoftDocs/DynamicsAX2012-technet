---
title: Set up or modify table distributions
TOCTitle: Set up or modify table distributions
ms:assetid: c9418f6a-8bc3-49a8-8b1c-3e2072e9f99c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ679933(v=AX.60)
ms:contentKeyID: 49557915
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Set up or modify table distributions [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

Use table distribution to specify how changes that are made to data are distributed from the Microsoft Dynamics AX database to channel locations. To use A jobs correctly, you must configure table distribution.


> [!NOTE]
> <P>The information in this topic applies only to Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 Feature Pack.</P>



Action filters specify which tables and fields are monitored for changes. When a record in one of the selected tables is changed, the distribution settings for the table determine whether that change is distributed, which locations the change is distributed to, and whether records in child tables are distributed together with the change.


> [!IMPORTANT]
> <P>Setting up table distribution is a complex task. We recommend that this task be completed only by a person who is experienced in Microsoft SQL Server administration, and who also has detailed knowledge of the tables and fields in the Microsoft Dynamics AX database.</P>



This topic contains the following information about table distribution:

  - Use the default table distribution setup

  - Distribution types

  - Add a table to the table distribution list

  - Remove a table from a table distribution

## Use the default table distribution setup

The default setup for table distribution is appropriate for most organizations. Even if you want to customize the table distribution, you can save time by inserting the default setup first.


> [!NOTE]
> <P>If you inserted the default setup when you configured the Retail module, you can skip this procedure.</P>



1.  Click **Retail** \> **Setup** \> **Retail scheduler** \> **Table distribution**.

2.  Click **Insert default setup**.

## Distribution types

The distribution type for a table determines how changes in the data from that table are distributed.

The manner in which you distribute changes depends on the purpose of the table. For example, you might want to distribute changes in the Product Posting Group table to all store locations. However, you might want to distribute changes in the Item table only to selected store locations, because your organization sells certain items only in selected stores.

The following distribution types are available:

  - **All distribution locations** – Distribute changes to all locations. This distribution type is the default type.
    
    If you want changes to be distributed to all locations, you can create an action filter on the table, but do not include the table in a table distribution. For example, to distribute all the changes in the Product Posting Group table to all locations, create an action filter to monitor for changes, but do not add the table to a table distribution. However, if the table is already included in a table distribution, you must select the **All distribution locations** distribution type for the table.

  - **Same as parent distribution** – Distribute changes based on the distribution type of the parent table. Select this distribution type for records that must always be accompanied by other records. For example, items and the bar codes for those items must have the same data distribution.
    

    > [!IMPORTANT]
    > <P>If you select this distribution type, you must set up table links that describe the relationship between the child table and its parent table. For more information, see <A href="set-up-table-links.md">Set up table links</A>. You must also specify the types of actions that cause child tables to be distributed together with changes in the parent table. You can select to distribute changes based on insert, update, and delete actions.</P>



  - **By distribution groups** – Distribute changes based on the distribution list for the record that was changed in the table. For example, changes that were made to an item are sent only to the stores that sell that item. For more information about distribution lists, see [Set up a distribution location list](set-up-a-distribution-location-list.md).
    

    > [!IMPORTANT]
    > <P>Typically, you select this distribution type only for tables at the top of the table distribution hierarchy.</P>



  - **No distribution** – Do not distribute changes. If a table of this distribution type is the parent of another table, and the distribution type of the child table is set to **Same as parent distribution**, changes in the child table are not distributed.

## Add a table to the table distribution list

1.  Click **Retail** \> **Setup** \> **Retail scheduler** \> **Table distribution**.

2.  Select the **List view** option.

3.  Click **New**.

4.  The **Table ID** field contains the identifiers that are used for tables in the Application Object Tree (AOT). Select the identifier for the table to add to the table distribution.

5.  In the **Distribution type** field, select a method for distributing the data. For more information about the distribution types that are available, see Distribution types.

6.  Specify the types of actions that cause child tables to be distributed together with the selected table. You can select to distribute changes based on insert, update, and delete actions.
    
      - If specific records in child tables must be distributed when a record is added to the selected parent table, select **Linked actions on insert**.
    
      - If specific records in child tables must be distributed when a record is changed in the selected parent table, select **Linked actions on update**.
    
      - If specific records in child tables must be distributed when a record is deleted from the selected parent table, select **Linked actions on delete**.
    

    > [!NOTE]
    > <P>If the selected table does not have child tables, these options do not affect distributions.</P>



## Remove a table from a table distribution

1.  Click **Retail** \> **Setup** \> **Retail scheduler** \> **Table distribution**.

2.  Select the **List view** option.

3.  Select the table to remove from the distribution, and then click **Delete** on the toolbar.

## See also

[Set up action filters for Retail data](set-up-action-filters-for-retail-data.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

