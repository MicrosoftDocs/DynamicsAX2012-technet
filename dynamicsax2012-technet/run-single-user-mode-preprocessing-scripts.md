---
title: Run single-user mode preprocessing scripts
TOCTitle: Run single-user mode preprocessing scripts
ms:assetid: 70619580-7926-45af-92c9-d91bd3c26b6d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg731829(v=AX.60)
ms:contentKeyID: 35132678
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- scripts
- offline
- single-user
---

# Run single-user mode preprocessing scripts [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

**Run single-user mode preprocessing scripts** is the final task in the **Preprocessing upgrade checklist**. This task first checks that the system is running with only a single administrative user logged in. If this test is successful, the **Upgrade single-user preprocessing** form opens. Clicking **Run** on this form launches the delta upgrade scripts for a final time and then launches the upgrade scripts that prepare data to be bulk copied to the target system. These scripts run using set-based operation.

## Use parallel processing to reduce downtime

Single-user mode operation of your Microsoft Dynamics AX system means that the system is unavailable for business transactions. The upgrade framework enables parallel processing of the source system data in order to keep downtime to a minimum. If you are upgrading from Microsoft Dynamics AX 2009, this checklist task will initiate parallel processing of the data automatically. If you are upgrading from Microsoft Dynamics AX 4.0, you can manually initiate parallel processing.

When you run single-user mode preprocessing on a Microsoft Dynamics AX 4.0 system, each client connection enables a single batch thread to run. To run multiple batch threads and improve performance, you allow the system to accept new connections, and then open multiple clients using the administrative login. While the system is accepting new connections, you must insure that no non-administrative users connect and make transactions. Any transaction made after you enter single-user mode will invalidate the data and the upgrade will fail. Also, if the source system uses multiple instances of the application object server (AOS), you must make sure that only one instance of the AOS allows new connections.

For more information, see [Enter into single-user mode](enter-into-single-user-mode.md).

## Prepare for single-user mode preprocessing

Before you run the single-user mode preprocessing scripts, back up the Microsoft SQL Server database and set the database recovery model to *simple*. For more information about how to prepare for running the single-user mode preprocessing scripts, see [Enter into single-user mode](enter-into-single-user-mode.md).

Single-user mode preprocessing scripts on the source system run concurrently with the bulk copy of data to the Microsoft Dynamics AX 2012 target system, synchronization of the Microsoft SQL Server database on the source system, and post-synchronization of the database. This process will take several hours.

## Run the single-user mode preprocessing scripts

Complete the following steps to run the single-user mode preprocessing scripts and complete the tasks on the **Preprocessing upgrade checklist**

1.  (Recommended) Restart AOS.

2.  In the **Preprocessing upgrade checklist**, click **Run single-user mode preprocessing scripts**.

3.  In the **Upgrade single-user preprocessing** form, click **Run** to start running the single-user mode preprocessing scripts.

## See also

[Upgrade preprocessing scripts (form)](https://technet.microsoft.com/en-us/library/hh202100\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

