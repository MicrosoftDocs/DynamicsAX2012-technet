---
title: Create a batch group
TOCTitle: Create a batch group
ms:assetid: 5153936f-a872-430d-bd17-4c910de871d4
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa548911(v=AX.60)
ms:contentKeyID: 35132636
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Create a batch group 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Batch groups are used to group and run selected tasks on a specific batch server. Examples of batch groups include the following:

  - Jobs that run on a specific computer

  - Jobs that require many resources

  - Jobs that belong to a specific module

  - Jobs that run at certain intervals—for example every night, every week, or every month

When the batch process is started, the jobs and reports in the batch group are run according to the start date, start time, and recurrence parameters that are specified on the individual jobs.

Client tasks must be run manually by using the **Set up batch processing** form. For more information, see [Run client and private batch tasks](run-client-and-private-batch-tasks.md).

## Create a batch group

1.  Click **System administration** \> **Setup** \> **Batch group**.

2.  Press CTRL+N to create a new batch group.

3.  In the **Group** field, type an identifier for the batch group.

4.  In the **Description** field, type a name for the batch group that is unique in the system.

## Set a batch group to run on a specific server

1.  Click **System administration** \> **Setup** \> **Batch group**.

2.  Select a batch group, and then click the **Batch servers** tab.
    
    The **Selected servers** list displays the Application Object Server (AOS) instances on which the selected group is specified to run. The **Remaining servers** list displays the remaining AOS instances that are available as batch servers.

3.  Click the arrow buttons to select additional servers or remove servers from the **Selected servers** list.

## See also

[Batch processing overview](batch-processing-overview.md)

[Server configuration (form)](https://technet.microsoft.com/en-us/library/hh208825\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

