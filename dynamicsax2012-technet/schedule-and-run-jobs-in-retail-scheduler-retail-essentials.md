---
title: Schedule and run jobs in Retail Scheduler (Retail essentials)
TOCTitle: Schedule and run jobs in Retail Scheduler (Retail essentials)
ms:assetid: a71c9229-3fa8-41b5-b1ed-9534426f81c2
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn736928(v=AX.60)
ms:contentKeyID: 62200401
ms.date: 08/15/2014
mtps_version: v=AX.60
f1_keywords:
- 9c603eb2-1a13-4ff1-b9c9-504f051034a8
- a71c9229-3fa8-41b5-b1ed-9534426f81c2
- MsDynAx060.a71c9229-3fa8-41b5-b1ed-9534426f81c2
---

# Schedule and run jobs in Retail Scheduler (Retail essentials) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes how to schedule and run the data transfer between Retail essentials and retail channels. Commerce Data Exchange uses Retail Scheduler jobs and distribution schedules.

Jobs and subjobs contain the data distribution settings for specific tables and fields in the database. A distribution schedule associates scheduler jobs with the locations where data must be synchronized. After you have created distribution schedules, you can run them either automatically in a batch or manually.

Before you can set up a distribution schedule, you must create scheduler jobs and data groups. For more information, see [Configure jobs and subjobs in Retail Scheduler](configure-jobs-and-subjobs-in-retail-scheduler.md) and [Create a channel data group](create-a-channel-data-group.md).

This topic contains the following sections:

  - Create a distribution schedule

  - Set up batch processing for scheduler jobs

  - Run a scheduler job manually

  - View the status of data distribution

## Create a distribution schedule

To create a distribution schedule, follow these steps:

1.  Click **Retail essentials** \> **Data synchronization** \> **Distribution schedule**.

2.  Click **New** to create a new distribution schedule, or select a distribution schedule to modify.

3.  Enter a unique name and an optional description for the distribution schedule.

4.  By default, the **Active** check box is selected. If this check box is cleared, the distribution schedule does not run.

5.  If you are creating a new distribution schedule, select the direction that the data flows:
    
      - Select **Download** if the jobs in the distribution schedule transfer data from Microsoft Dynamics AX to channels.
    
      - Select **Upload** if the jobs in the distribution schedule transfer data from channels to Microsoft Dynamics AX.
    
    The direction that you select determines the jobs that you can add to the distribution schedule. For example, you can’t add job P-0001 (POS transactions) to a distribution schedule that the **Download** direction is selected for.

6.  On the **Data groups** FastTab, click **Add** to add one or more data groups to the schedule. When you run the distribution schedule, a data package is generated for each data group. All channel databases in a data group receive the same data.
    
    To remove a data group from the schedule, select the data group, and then click **Remove**.

7.  On the **Scheduler jobs** FastTab, click **Add** to add one or more jobs to the schedule. To remove a job from the schedule, select the job, and then click **Remove**.

## Set up batch processing for scheduler jobs

A batch job is a scheduled run of a job or a group of jobs. When you create a batch job, you set up the timing of the batch job in the instance of Microsoft Dynamics AX Application Object Server (AOS). The batch job is then run automatically on the server. To run batch jobs, you must configure the batch server. For more information, see [Configure an AOS instance as a batch server](configure-an-aos-instance-as-a-batch-server.md).

To set up a batch job for a distribution schedule, follow these steps:

1.  Click **Retail essentials** \> **Data synchronization** \> **Distribution schedule**.

2.  Select a distribution schedule.

3.  On the **Scheduler jobs** FastTab, select the **Enabled** check box for each scheduler job to run in the batch job.

4.  At the top of the form, click **Create batch job**. In the form that is displayed, enter information about the batch job, and then click **OK**. For more information about the options in the form, see [Submit a batch processing job from a form](submit-a-batch-processing-job-from-a-form.md).

## Run a scheduler job manually

To run an individual scheduler job manually, follow these steps. The job runs for all locations that are in the distribution schedule.

1.  Click **Retail essentials** \> **Data synchronization** \> **Distribution schedule**.

2.  In the **Distribution schedule** form, on the **Scheduler jobs** FastTab, select the job to run.

3.  On the top menu, click **Run now**.

## View the status of data distribution

To view the status of a data distribution schedule, follow these steps:

1.  Click **Retail essentials** \> **Data synchronization** \> **Distribution schedule**.

2.  In the **Distribution schedule** form, in the left pane, select a distribution schedule, and then click **History**.

3.  In the **Download history** form, in the left pane, select a job. Then review the information for the job and the channels that sent or received data. For more information, see [View history for a distribution schedule](view-history-for-a-distribution-schedule.md).

## See also

[Schedule Retail data distribution (Retail essentials)](schedule-retail-data-distribution-retail-essentials.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

