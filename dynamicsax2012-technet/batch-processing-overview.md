---
title: Batch processing overview
TOCTitle: Batch processing overview
ms:assetid: e805b094-a822-4e4e-ab06-ba6edb51c97d
ms:mtpsurl: https://technet.microsoft.com/library/Gg243235(v=AX.60)
ms:contentKeyID: 35133147
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Batch processing overview 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how you can use batch processing to enable you to run specific tasks as batch jobs, which can be scheduled and run on a different computer (a batch server). Many tasks in Microsoft Dynamics AX can be run as part of batch jobs. For example, batch jobs can include tasks for printing reports, performing maintenance, or sending electronic documents. By using batch jobs, you can avoid slowing down your computer or the server during typical working hours.

Most batch tasks can be run on a batch server, but some must be run on the client. Tasks that run on the server can run automatically as part of batch jobs, regardless of whether a client is open. However, tasks that run on the client must be run manually by using the **Set up batch processing** form. If a client task is marked **Private**, only the user who created that task can run it.

The tasks in a batch job can run sequentially or at the same time. In addition, you can create dependencies between tasks. This means that you can set up a different sequence of tasks depending on whether an earlier task succeeds or fails.

You can set up recurrence patterns for batch jobs. For example, you can set up a job to process invoices automatically at the end of every month.

To monitor batch jobs, you can set up alerts. Alerts can be sent when the batch job succeeds, fails, or finishes.

After a batch job has been processed, you can view history. This includes any messages encountered when the job is running.

Use batch groups to categorize batch tasks and run them on specific servers. The servers in your environment may have different software installed or may be available at different times of day. Batch groups are used to direct batch tasks to the most appropriate server. Tasks in the same batch job can belong to different batch groups.

For example, you might have Server A set up to print reports and Server B set up to send electronic documents. You can use batch groups to make sure that reporting tasks are run on Server A and electronic documents are processed by Server B.

Batch jobs run on a per-partition basis. A system administrator can create, change, and view the history for the batch jobs in each partition. The batch job administration forms show only the information about the batch jobs for the partition to which you are currently logged on.

## See also

[Create a batch job](create-a-batch-job.md)

[View or change batch job status](view-or-change-batch-job-status.md)

[Run client and private batch tasks](run-client-and-private-batch-tasks.md)

  


