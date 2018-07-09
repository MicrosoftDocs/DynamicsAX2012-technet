---
title: Run client and private batch tasks
TOCTitle: Run client and private batch tasks
ms:assetid: f373cb0b-15ad-41ec-adb3-c103db5e1240
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa551632(v=AX.60)
ms:contentKeyID: 36059977
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Run client and private batch tasks [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This article describes how to run batch jobs on a client computer, including tasks that are designated as private.

Batch jobs contain tasks that are designated to run on either the client computer or the server computer. Tasks that run on the server can run automatically as part of batch jobs, regardless of whether a client is running. However, tasks that run on the client must be run manually by using the **Set up batch processing** form.

Client jobs may be marked as private. Because they run on the client, private jobs are not run automatically, and can be run only by the user who scheduled them.

## Run client tasks

1.  Click **Organization administration** \> **Periodic** \> **Batch processing**.

2.  Select the batch group that the client tasks belong to.
    

    > [!NOTE]
    > <P>The client tasks typically belong to the default or empty batch group.</P>



3.  To run only the private tasks that you created, select the **Private** check box. To run all client tasks in the batch group in addition to your private tasks, clear this check box.
    

    > [!NOTE]
    > <P>You cannot run private tasks that other users created.</P>



4.  Click **OK**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

