---
title: Set up action filters for Retail data
TOCTitle: Set up action filters for Retail data
ms:assetid: 0fe96a60-7051-47ea-8834-ca70884ef218
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ679909(v=AX.60)
ms:contentKeyID: 49557892
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Set up action filters for Retail data 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

Action filters specify which tables and fields are monitored for changes that must be distributed to stores. If a user creates, modifies, or deletes a record in a table that is monitored, the action filter automatically collects the information that changed in a data record. This data record is called a preaction. To send the modifications to stores, you must convert the preactions to actions.


> [!NOTE]
> <P>The information in this topic applies only to Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 Feature Pack.</P>



The distribution settings for the table determine whether a change is distributed, which locations the change is distributed to, and whether records in child tables are distributed together with the change. For information about how to set up table distributions, see [Set up or modify table distributions](set-up-or-modify-table-distributions.md).

## Set up action filters

Create an action filter to monitor tables and fields for changes that must be distributed to stores.

Use table distributions to apply action filters to specific distribution locations. If you create an action filter for a table but do not include the table in a table distribution, changes that are made to records in that table are automatically sent to all locations.

1.  Click **Retail** \> **Setup** \> **Retail scheduler** \> **Filter on action creations**.

2.  Click **New** to create a new action filter.

3.  In the **Table number** field, select a table to monitor.
    
    To monitor specific fields in the table, click **Add**. In the **Field number** field, specify a field in the selected table.
    

    > [!NOTE]
    > <P>If you want to monitor all changes that are made to a table, do not select individual fields. For new tables, a developer must modify the insert, update, and delete methods of the table object.</P>



4.  When you have finished making changes, close the form.

## Convert preactions to actions

When modifications are made in tables for which you have set up action filters, preactions are created automatically. The preaction list is a holding area for these data records. You must convert the preactions to actions and send the modifications to stores by using an A job. You can set up a batch job to run the A job automatically.


> [!WARNING]
> <P>We recommend that you not change the primary key for a record for which changes are being distributed. The primary key is used as a reference in other tables. These tables include the preactions table. When the primary key is changed, the references are broken. In this situation, preactions are not created, and the changes are not distributed to stores.</P>



  - To view a list of preactions: Click **Retail** \> **Periodic** \> **Data distribution** \> **Preactions**.

  - To set up a batch job to convert preactions to actions: Click **Retail** \> **Periodic** \> **Data distribution** \> **Create actions**.

  - To view a list of actions: Click **Retail** \> **Periodic** \> **Data distribution** \> **Actions**.

  


