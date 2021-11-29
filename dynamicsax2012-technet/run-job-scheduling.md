---
title: Run job scheduling
TOCTitle: Run job scheduling
ms:assetid: c44f11cd-4386-4868-806f-29c3370ad012
ms:mtpsurl: https://technet.microsoft.com/library/Aa550725(v=AX.60)
ms:contentKeyID: 43976726
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- schedule
- operation
- scheduling
- jobs
- dates
- times
audience: Application User
ms.search.region: Global
---

# Run job scheduling 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Job scheduling breaks each operation into individual jobs. These jobs are associated with the resources where the operation occurs, and are scheduled by using the optimal dates and times.

If you specify resource groups, job scheduling uses the resource that has the shortest lead time. For more information, see [Production - Job scheduling (class form)](https://technet.microsoft.com/library/aa584348\(v=ax.60\)) and [Set up job scheduling (form)](https://technet.microsoft.com/library/aa553462\(v=ax.60\)).

1.  Click **Production control** \> **Periodic** \> **Scheduling** \> **Job scheduling**.

2.  Click **Select**, and then enter criteria for the production order to schedule jobs for.

3.  On the **General** tab, in the **Scheduling direction** field, select the scheduling direction to use for the production order.

4.  Select or clear the **Finite capacity**, **Finite material**, and **Finite property** check boxes.
    

    > [!TIP]
    > <P>These options help guarantee that jobs are scheduled based on current capacity, and that start and end times do not overlap.</P>



5.  To change the job that you are scheduling, select a different job in the **Job identification** field.

6.  To change the resource for the job that is selected in the **Job identification** field, select a different resource in the **New resource** field.

7.  To include references between the main production order and the subproductions that are associated with it when you run job scheduling, select the **Schedule references** check box. To exclude these references, clear the check box.

8.  On the **Cancellation** tab, select the types of jobs to exclude from job scheduling.

9.  Click **OK**.

## See also

[About job scheduling](about-job-scheduling.md)

  


