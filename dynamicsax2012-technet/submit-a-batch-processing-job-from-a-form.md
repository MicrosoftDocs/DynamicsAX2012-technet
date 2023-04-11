---
title: Submit a batch processing job from a form
TOCTitle: Submit a batch processing job from a form
ms:assetid: d8998139-98e3-4ae9-b253-68c29d3e0c38
ms:mtpsurl: https://technet.microsoft.com/library/Aa619588(v=AX.60)
ms:contentKeyID: 36059645
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Submit a batch processing job from a form 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This article describes how to submit a job or report to be run as part of a batch process on a different computer. The batch job is submitted to a batch server, where the jobs are queued and run.


> [!NOTE]
> <P>Some of the options described in this article are not available on all <STRONG>Batch</STRONG> tabs.</P>



## Submit a batch job from a form or report

1.  In any batch-enabled form or report, click the **Batch** tab.

2.  Select the **Batch processing** check box.

3.  Set any of the following options:
    
      - **Caption** – Enter a description for the job.
    
      - **Batch group** - Assign the job to a batch group.
        
        Batch groups are designed to enable you to run specific types of jobs on a specific batch server, or to run jobs on batch servers that are available at specific times. Batch groups are created by system administrators.
    
      - **Private** – Select this check box to restrict other users from processing your batch job. A private job can be run only by the user who submitted it, from the **Set up batch processing** form, and only on the computer where the user is logged on.

4.  Click **Recurrence** to configure a batch job to recur on a specific schedule.

5.  Click **Alerts** to configure alerts for a batch job.


> [!NOTE]
> <P>The <STRONG>Start date</STRONG> at the bottom of the form lists the next scheduled start time for the batch job.</P>



## See also

[Batch processing overview](batch-processing-overview.md)

[Run client and private batch tasks](run-client-and-private-batch-tasks.md)

  


