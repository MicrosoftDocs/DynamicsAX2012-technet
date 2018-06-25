---
title: Synchronize the job table
TOCTitle: Synchronize the job table
ms:assetid: f0cbf941-d0ed-4380-8439-2284b843ed8b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa551588(v=AX.60)
ms:contentKeyID: 36688043
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- sync
- job
- synchronise
- synchronize
---

# Synchronize the job table [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Workers can make registrations on various kinds of jobs in **Time and attendance**:

  - Production orders

  - Projects and project activities

  - Absence registrations

  - Indirect activities

All jobs to be used for registration are maintained in the **Time and attendance** job table. This job table must be synchronized with the tables that contain the original jobs, for example, production jobs, or project activities.

## Online synchronization

In **Production control** \> **Setup** \> **Time and attendance** \> **Parameters**, in the **General** section, select **Online** in the **Job table synchronization mode** field.

Refer to the Initial synchronization section at the end of this topic to make an initial synchronization. After the initial synchronization, the job table will be updated by the system every time a new job is created.

## Offline synchronization

In **Production control** \> **Setup** \> **Time and attendance** \> **Parameters**, in the **General** section, select **Offline** in the **Job table synchronization mode** field.

Refer to the following section to make an initial synchronization. Click **Human resources** \> **Periodic** \> **Time and attendance** \> **Update** \> **Synchronize job table**. This approach allows you to define how frequently the job table should be updated.


> [!TIP]
> <P>This type of synchronization provides optimal performance.</P>



## Initial synchronization

The initial synchronization will update the job table.

1.  Click **Human resources** \> **Periodic** \> **Time and attendance** \> **Update** \> **Synchronize job table**.

2.  Select the types of jobs on which to perform the synchronization.

3.  If you have selected to run **Offline** synchronization, as described in the Offline section of this topic, select the parameters to be used for the batch job.

## See also

[Synchronize job table (class form)](https://technet.microsoft.com/en-us/library/aa575320\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

