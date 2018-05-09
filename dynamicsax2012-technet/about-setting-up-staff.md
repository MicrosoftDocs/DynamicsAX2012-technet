---
title: About setting up staff
TOCTitle: About setting up staff
ms:assetid: 5bc9dc51-4246-4a99-8dd4-815849b5a63f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh597104(v=AX.60)
ms:contentKeyID: 39519152
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# About setting up staff 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

Before a worker can perform job duties in a retail store, you must set up the worker in Microsoft Dynamics AX. You must also assign the worker appropriate privileges, so that the worker can log on and perform tasks by using the Microsoft Dynamics AX for Retail POS system.

Retail uses the worker features in Microsoft Dynamics AX to set up employee data, and to configure the job and position data that is used to create a staff member for retail processes. To set up a retail worker, you must complete the following tasks:

1.  Define the settings for point of sale (POS) permissions. The POS permission settings specify the actions that workers can perform when they use the POS system. Each staff member is assigned Retail POS permissions. For example, the permissions define whether the staff member can void transactions, perform tender declarations, or override prices. The permissions also define the maximum discount that the staff member can give. Each staff member can be assigned to only one store.
    
    For more information about how to configure POS permissions, see [Set up permissions and operations](set-up-permissions-and-operations.md).

2.  Set up a job. A job is a collection of tasks and responsibilities that are required of any person who is assigned to the job. You must link POS permissions to each job.
    
    For general information about how to set up a job, see [Key tasks: Jobs](key-tasks-jobs.md).

3.  Set up a position. A position is an individual instance of a job. You must assign each worker to a position. By assigning a worker to a position, you associate the worker with a specific job. Therefore, you also assign the POS permissions that the worker requires to use the POS system in the retail store.
    
    For general information about how to set up a position, see [Key tasks: New worker positions](key-tasks-new-worker-positions.md).

4.  Set up a worker. The information that you enter for a worker includes personnel details. You must assign each worker to an address book. The address book is used to assign the worker to a store.
    
    For general information about how to set up a worker, see [Key tasks: Workers](key-tasks-workers.md).

If you have set up Enterprise Portal for Microsoft Dynamics AX, you must set up user profiles for the employees who access Enterprise Portal. These profiles define each user's role and specify the store information that the user has access to.

## See also

[Set up permissions and operations](set-up-permissions-and-operations.md)

[Set up staff members](set-up-staff-members.md)

[Set up Enterprise Portal profiles and users](set-up-enterprise-portal-profiles-and-users.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

