---
title: Set up table links
TOCTitle: Set up table links
ms:assetid: b803b6aa-4485-4da0-9cc5-eaf8bf5ec741
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ679932(v=AX.60)
ms:contentKeyID: 49557914
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Set up table links [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

Table links define the conditions that must be met before the records in a child table can be distributed based on the distribution type of a parent table. A table link applies only to data distribution between Microsoft Dynamics AX and channels.


> [!NOTE]
> <P>The information in this topic applies only to Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 Feature Pack.</P>



Table distributions specify how changes that are made to data are distributed from the Microsoft Dynamics AX database to the databases at channel locations. If you select a distribution type of **Same as parent distribution**, changes that are made to a table are distributed based on the distribution type of a parent table. If you select this distribution type, you must set up table links to specify the relationships between parent tables and child tables.

## How table links work

When a record in a child table is modified, the resulting preaction is converted to an action. If data distribution for the table is controlled by the settings of a parent table, Retail Scheduler checks whether the modified record meets the distribution criteria that are specified for the parent table.

If a table link includes multiple fields, distribution occurs only if distribution criteria are met for all the fields. If a modified record does not meet the criteria of any of the links to the parent table, distribution does not occur.

A table can be the child of more than one parent table. In this case, the child table appears in the hierarchy more than one time. Depending on the settings, changes to a record in the child table might be distributed through multiple parent tables.

## Set up table links

There must be a logical relation between the tables that you link. For example, you cannot link the Item table to the Customer table, because there is no logical relation between those two tables. The effect of setting up a table link is comparable to the effect of setting up a link between a primary key and a foreign key in Microsoft SQL Server.

  - For parent fields, you must select fields that are part of the primary key for the parent table.

  - For child fields, we recommend that you select fields that are either part of the primary key or part of a properly indexed foreign key for the child table.

Complete the following procedure to set up table links.

1.  In the **Table distribution** form, select the table to link to its parent table. The parent table must already be listed in the table distribution.

2.  Click **Table links**.

3.  In the **Table links** form, click **New**.

4.  In the **Parent distribution** field, select the ID of a parent table. If there are multiple entries in the list, a link is created if the criteria of any one table are met. This condition corresponds to an SQL OR operation.

5.  In the **Field ID** field, select the field to link to a field in the parent table. The field name is displayed automatically. If there are multiple entries in the list, all the criteria must be met before the link can be created. This condition corresponds to an SQL AND operation.

6.  In the **Parent field** field, select the field in the parent table to link the child field to. The name of the parent field is displayed automatically.

7.  If the parent field must contain a specific value, type that value in the **Value** field.

8.  Repeat steps 4 through 7 for any additional criteria for this table link.

## See also

[Configure table distribution settings for Retail data](configure-table-distribution-settings-for-retail-data.md)

[Set up action filters for Retail data](set-up-action-filters-for-retail-data.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

