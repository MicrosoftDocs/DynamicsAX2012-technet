---
title: Launch data upgrade
TOCTitle: Launch data upgrade
ms:assetid: 0413b647-718a-4371-984f-84fbdf685a24
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg751344(v=AX.60)
ms:contentKeyID: 35132530
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- bulk copy
- presynchronization
---

# Launch data upgrade [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Launch data upgrade** task opens the **Data upgrade cockpit (%1 -\> %2)**, where you can begin bulk copying data from the source Microsoft Dynamics AX system and running data upgrade scripts on the target system.

## Run bulk copy and scripts

In the **Data upgrade cockpit (%1 -\> %2)**, click **Run** to perform the bulk copy, run post-synchronization scripts on the copied data, and create check constraints and indexes.


> [!WARNING]
> <P>Prior to this point in the upgrade process, it has been possible to keep the source system online. Beginning with this step, you must enter single-user mode on both your source and target systems, making them unavailable to regular users.</P>




> [!TIP]
> <P>Within the upgrade cockpit, pausing a task that displays a status of ready is not guaranteed to prevent the job from being sent to batch execution. This depends on the underlying status of the task in the batch queue. If the status of the task is already marked as ready, pausing the job will have no effect on the script and it will be executed as soon as a the batch framework becomes available to process it. Only scripts with the underlying batch status of Waiting can be paused.</P>
> <P>To pause execution on all tasks not currently executing, you can temporarily remove the AOS from the upgrade batch group, using the <STRONG>Batch groups</STRONG> form.</P>
> <P>For more information, see <A href="https://technet.microsoft.com/en-us/library/aa575384(v=ax.60)">Batch groups (form)</A> and <A href="create-a-batch-group.md">Create a batch group</A>.</P>


  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

