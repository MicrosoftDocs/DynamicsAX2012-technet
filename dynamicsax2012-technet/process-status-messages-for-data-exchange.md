---
title: Process status messages for data exchange
TOCTitle: Process status messages for data exchange
ms:assetid: dbe1747e-d266-40d0-8193-0c54693e75fd
ms:mtpsurl: https://technet.microsoft.com/library/Dn497850(v=AX.60)
ms:contentKeyID: 62200216
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Process status messages for data exchange 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

Use the following procedure to set up a batch job to process status messages from Commerce Data Exchange.

The batch job transfers messages from the message database to the Microsoft Dynamics AX database. After messages are copied to the Microsoft Dynamics AX database, they can be viewed in Microsoft Dynamics AX. For information about how to view status messages, see [View or cancel retail data distribution sessions](view-or-cancel-retail-data-distribution-sessions.md) and [View history for a distribution schedule](view-history-for-a-distribution-schedule.md).

The batch job also purges expired data from both the Microsoft Dynamics AX database and the message database. Data expiration depends on the retention period that you specified in the parameters for Retail Scheduler.

A batch job is a scheduled run of a process in Microsoft Dynamics AX. When you create a batch job, you set up a timer in the instance of Microsoft Dynamics AX Application Object Server (AOS). The job is then run automatically on the server. To run batch jobs, you must configure the batch server. For more information, see [Configure an AOS instance as a batch server](configure-an-aos-instance-as-a-batch-server.md).

1.  Click **Retail** \> **Periodic** \> **Data distribution** \> **Process status messages**.

2.  In the form, select **Batch processing**.

3.  If you want to run the batch process as part of a group of jobs, select a batch group in the **Batch group** field.

4.  Click **Recurrence**.

5.  In the **Recurrence** form, set the parameters to specify how frequently this job runs. Set the frequency based on how frequently you want status messages from Commerce Data Exchange to be uploaded to Microsoft Dynamics AX. We recommend that you run the job at least one time every day to catch errors promptly.

  


