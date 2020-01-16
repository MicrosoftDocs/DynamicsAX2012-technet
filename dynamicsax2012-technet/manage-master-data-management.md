---
title: Manage Master Data Management
TOCTitle: Manage Master Data Management
ms:assetid: bb7e73cc-0050-4989-877a-79dae52a701f
ms:mtpsurl: https://technet.microsoft.com/library/Dn720448(v=AX.60)
ms:contentKeyID: 62224154
author: Khairunj
ms.date: 05/14/2014
mtps_version: v=AX.60
---

# Manage Master Data Management 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes how to perform management activities for Microsoft Dynamics AX Master Data Management (MDM). For example, you can resolve conflicts and view the synchronization history.

## Resolving MDM Conflicts

A conflict occurs when the same record is updated in multiple Microsoft Dynamics AX instances, and then those changes are synced to the master data store in Microsoft SQL Server Master Data Services (SQL MDS). For example, Instance 1 and Instance 2 both update the name on the Contoso customer record. However, one instance updates the name to **Contoso LTD**, and the other instance updates it to **Contoso Limited**. In Microsoft Dynamics AX, you can see whether conflicts exist and then use the SQL Server Master Data Service Add-in for Microsoft Excel to resolve them.

## What Occurs Until a Conflict Is Resolved

When a conflict is identified, the conflicting records are stored by SQL MDS until you manually resolve them. While the conflict remains unresolved, the system treats the SQL MDS record as primary and the updated record from the second spoke as secondary. All spokes that pull down master data receive the primary record from SQL MDS.

For example, Instance 1 updates the name on the Contoso customer record to **Contoso LTD**, and Instance 2 updates the name to **Contoso Limited**. Instance 1 then synchronizes to SQL MDS before Instance 2. Therefore, the primary record displays the name **Contoso LTD**, and the secondary record displays the name **Contoso Limited**. Until the conflict is resolved, master data that is shared with the spokes displays the name **Contoso LTD**.

To resolve the conflict, you must modify the data in the primary record.

## Determine Whether a Conflict Exists

To see whether there is a conflict for a subscribed entity, follow these steps.

1.  In Microsoft Dynamics AX 2012, open **Data import export framework**.

2.  In **Master data management**, click **View conflicts**.

3.  In the **View conflicts** form, locate the entity to check. If there are any conflicts for the entity, the **Has conflicts** column has a check mark, and the **Number of conflicts** column indicates the number of conflicts.

4.  When you have finished, click **Close**.

To receive alerts about conflicts, follow these steps.

1.  In AX 2012, open **Data import export framework**.

2.  In **Master data management**, click **View conflicts**.

3.  In the **View conflicts** form, right-click in any row, and then click **Create alert rule**.

4.  In the **Create alert rule** form, in the **Field** field, select Has conflicts.

5.  In the **Event** field, select is set to:, and then select Yes in the field on the right.

6.  Set the other parameters that determine the delivery and contents of alerts. For more information, see [Create alert rules](create-alert-rules.md).

7.  When you have finished, click **OK**.

## Resolve a Conflict

To resolve a conflict, follow these steps.

1.  Open Excel on the computer where the SQL Server Master Data Service Add-in for Excel is installed.

2.  Identify the conflict. The primary record that has a conflict has a value of **1** in the **HASMDMCONFLICT** column. The duplicate record that conflicts with it has a value of **2** in the **HASMDMCONFLICT** column.

3.  Determine whether you want to accept any of the data in the conflicting record, and update the primary record accordingly. For example, the customer name was changed in the conflicting record, and you think that the name in that record is correct. In this case, update the name in the primary record.

4.  Set the **HASMDMCONFLICT** value for the primary record to **0**. Delete the duplicate record.

5.  Click **Publish** to push your changes to SQL MDS.
    
    The updated data is pulled to the spokes the next time that they synchronize.

## View the Synchronization History

You can view the synchronization history to see what operations have been run, and whether those operations were successful. You can also view log messages that are related to synchronization operations, and the status of batch jobs.

To view synchronization history, follow these steps.

1.  In Microsoft Dynamics AX, open **Data import export framework**.

2.  In **Master data management**, click **Manage synchronization**.

3.  In the **Manage synchronization** form, click **History**.

4.  In the **Synchronization history** form, you can review the sync groups that have been processed. The information in this form includes the status of the groups, start and end times, and batch job IDs.

5.  When you have finished, click **Close**.

## View Log Messages

To view log messages that are related to synchronization operations, follow these steps.

1.  In Microsoft Dynamics AX, open **Data import export framework**.

2.  In **Master data management**, click **Manage synchronization**.

3.  In the **Manage synchronization** form, click **History**.

4.  In the **Synchronization history** form, click **View log**.

5.  When you have finished, click **Close**.

## View the Batch Job History

To view log messages that are related to synchronization operations, follow these steps.

1.  In Microsoft Dynamics AX, open **Data import export framework**.

2.  In **Master data management**, click **Manage synchronization**.

3.  In the **Manage synchronization** form, click **History**.

4.  In the **Synchronization history** form, click **Batch job history**.

5.  In the **Batch job history** form, you can review the batch jobs that have been processed. The information in this form includes the status of the jobs, and start and end times.

6.  When you have finished, click **Close**.

  


