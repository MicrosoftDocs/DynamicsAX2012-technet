---
title: Enter into single-user mode
TOCTitle: Enter into single-user mode
ms:assetid: b417a37d-18ed-48fb-84df-136820c4dc66
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg731904(v=AX.60)
ms:contentKeyID: 35132822
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- upgrade
- offline
- preprocessing
---

# Enter into single-user mode 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You enter into single-user mode on the Microsoft Dynamics AX source system to make sure that the system is unavailable for business use. In single-user mode, only an upgrade user who has administrative permissions is connected. No other users can start a client session when the source system is in final preprocessing and source data is being bulk copied to the Microsoft Dynamics AX 2012 target system. After you enter into single-user mode, you can run the single-user mode preprocessing scripts and begin bulk copy of data to the target system.

In this step, you will do the following:

  - Enter into single-user mode and end current user sessions by using the **Online users** form.

  - Reopen client sessions for an administrative user on a single instance of the AOS (Microsoft Dynamics AX 4.0 only).

  - Back up the source system database.

  - Set the Microsoft SQL Server database recovery model to *simple.*

## (Retail only) Verify that final POS transactions have been posted

This section applies to scenarios described by the following Retail-specific upgrade paths.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Legacy version</p></th>
<th><p>Target version</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Microsoft Dynamics AX 2009 for Retail R2 Refresh</p></td>
<td><p>Microsoft Dynamics AX 2012 Feature Pack</p></td>
</tr>
<tr class="even">
<td><p>Microsoft Dynamics AX 2009 for Retail R2 Refresh</p></td>
<td><p>Microsoft Dynamics AX 2012 R2 or R3</p></td>
</tr>
<tr class="odd">
<td><p>Microsoft Dynamics AX 2012 Feature Pack</p></td>
<td><p>Microsoft Dynamics AX 2012 R2 or R3</p></td>
</tr>
</tbody>
</table>


Verifying that all transactions have been posted is mandatory for an upgrade to Microsoft Dynamics AX 2012 Feature Pack, since all POS terminals and databases must be shut down and redeployed during the upgrade process. It is optional during an upgrade to Microsoft Dynamics AX 2012 R2 or R3, which support multiple versions of the store software. This means that store redeployment is no longer tied to the head-office upgrade schedule, since stores can continue operating during upgrade, and a store must be shut down (and final transactions posted) only when the store’s actual redeployment is scheduled to occur. For more information, see the multi-version POS support [white paper](http://go.microsoft.com/fwlink/?linkid=259822).

For any stores being redeployed, the head-office Retail system undergoing upgrade must post any outstanding point-of-sale (POS) transactions before entering single-user mode. The upgrade administrator should coordinate with the administrator at each store to perform the following tasks:

1.  Set the cut-off time for the last POS transactions.

2.  Use **View journals** on each POS terminal to inspect the transaction logs and confirm the time and ID of the final transaction.

3.  On the head office system, open the **Transactions** form (in Microsoft Dynamics AX 2009 Retail R2 Refresh, **Retail Headquarters** \> **Inquiries** \> **Transactions**; in Microsoft Dynamics AX 2012 Feature Pack, **Retail** \> **Inquiries** \> **Transactions**). Compare the information from the store logs to the transaction records and confirm that all transactions have an **Entry status** of **posted**.

## Enter single-user mode and end current user sessions

**To enter single-user mode**

1.  In the **Preprocessing upgrade checklist**, click **Enter into single-user mode**.

2.  **Click Administration** \> **Forms** \> **Online users**.

3.  Click the **Server Instances** tab to see a list of all instances of the AOS that are running.

4.  Select a server instance, click **Reject new clients**, and then click **OK** to confirm that you want to stop the AOS from accepting new client sessions.
    
    In the **Status** column, the status changes to **Draining**. This status means that no users can start a new client session in the AOS instance. However, rejecting new clients does not end any current sessions.

5.  Repeat step four for all server instances that are running.

After you set the AOS instances to reject new client sessions, end all current client sessions. Before you do, make sure that all users who have active client sessions have finished their work.

**To end client sessions**

1.  In the **Online users** form, click the **Client Sessions** tab.

2.  Select the user sessions that you want to end (other than a single administrative user session), and then click **End sessions**.

3.  In the **End sessions** window, click **OK**, and then click **Close**.

## Reopen client sessions to set up batch threads in Microsoft Dynamics AX 4.0

The client-based batch framework in Microsoft Dynamics AX 4.0 supports only a single batch thread for each active client session. If you are upgrading from Microsoft Dynamics AX 4.0, you can open up to eight user sessions to allow multiple batch threads. These batch threads are necessary for running the final preprocessing scripts and bulk copying data to the target system. All user sessions must be opened by an upgrade user who has administrative permissions. Open these client sessions on a single AOS instance.

**To allow new client sessions**

1.  In the **Online users** form, click the **Server instances** tab.

2.  Select a server instance, and then click **Accept new clients**.
    
    After you begin running the preprocessing upgrade scripts in the next checklist task, **Run single-user mode preprocessing scripts**, you can open the new client sessions for batch threads on Microsoft Dynamics AX 4.0. If you open additional sessions before starting the script run, the run will fail.

3.  After you have opened the client sessions that you need for batch threads, return to the **Online users** form and click **Reject new clients** to prevent additional sessions from being opened.


> [!WARNING]
> <P>If you allow reopening client sessions in Microsoft Dynamics AX 4.0, you must take steps to ensure that no other users log on to make transactions when preprocessing scripts are being run and bulk copy is in progress. If any transactions are made on the Microsoft Dynamics AX source system during this time, your data will be invalid and the upgrade will fail.</P>



## Back up the source system database

Back up the source system SQL Server database to protect your data from any loss that may be caused by unexpected issues during single-user mode preprocessing. The backup also sets the initial recovery point for the simple recovery model that you will set for your SQL Server database during this stage of upgrade. To find the procedures for backing up your SQL Server database, use the following links:

  - To back up a SQL Server 2008 database, see [How to: Back Up a Database (SQL Server Management Studio)](http://go.microsoft.com/fwlink/?linkid=186062)

  - To back up a SQL Server 2005 database, see [How to: Back Up a Database (SQL Server Management Studio)](http://go.microsoft.com/fwlink/?linkid=186063)

## Set the Microsoft SQL Server recovery model to simple

Before you begin final preprocessing on the source system, set the source system SQL Server recovery model to *simple*. By setting the recovery model to simple, you permit the high-performance bulk copy process that is optimal for running the single-user mode preprocessing scripts and bulk copy of the source data to the target system.

1.  Open Microsoft SQL Server Management Studio (**Start** \> **All Programs** \> **Microsoft SQL Server \[version\]** \> **SQL Server Management Studio**).

2.  In **Object explorer**, select the database to open the **Database properties - \<database name\>** form.

3.  In the **Select a page** pane, click **Options**.

4.  In the **Recovery model** list, select **Simple**.

5.  Click **OK**.

  


