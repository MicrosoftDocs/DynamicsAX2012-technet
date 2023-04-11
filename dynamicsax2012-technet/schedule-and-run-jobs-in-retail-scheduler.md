---
title: Schedule and run jobs in Retail Scheduler
TOCTitle: Schedule and run jobs in Retail Scheduler
ms:assetid: fd0e4d1a-26ec-4ad3-861c-c71b238b4387
ms:mtpsurl: https://technet.microsoft.com/library/JJ710363(v=AX.60)
ms:contentKeyID: 49384244
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Forms.RetailConnSchedule
- Forms.RetailCDXSchedule
- MsDynAx060.Forms.RetailCDXSchedule
- MsDynAx060.Forms.RetailConnSchedule
---

# Schedule and run jobs in Retail Scheduler 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

To schedule and run the data transfer between Microsoft Dynamics AX and retail channels, Commerce Data Exchange uses Retail Scheduler jobs and distribution schedules.

Jobs and subjobs contain the data distribution settings for specific tables and fields in the database. A distribution schedule associates scheduler jobs with the locations where data must be synchronized. After you have created distribution schedules, you can run them automatically in a batch, or you can run them manually.

Before you can set up a distribution schedule, you must create scheduler jobs. If you’re using Microsoft Dynamics AX 2012 R3, you must also set up data groups. If you’re using Microsoft Dynamics AX 2012 R2 or Microsoft Dynamics AX 2012 Feature Pack, you must set up distribution location lists. For more information, see [Configure jobs and subjobs in Retail Scheduler](configure-jobs-and-subjobs-in-retail-scheduler.md), [Create a channel data group](create-a-channel-data-group.md), and [Set up a distribution location list](set-up-a-distribution-location-list.md).

This topic contains the following sections:

  - Create a distribution schedule in AX 2012 R3

  - Create a distribution schedule in AX 2012 R2 or AX 2012 Feature Pack

  - Set up batch processing for scheduler jobs

  - Run a scheduler job manually

  - View the status of data distribution

## Create a distribution schedule in AX 2012 R3

If you are using AX 2012 R3, use the following procedure to create a distribution schedule.

1.  Click **Retail** \> **Periodic** \> **Data distribution** \> **Distribution schedule**.

2.  Click **New** to create a new distribution schedule, or select a distribution schedule to modify.

3.  Enter a name and description for the distribution schedule.

4.  Select **Active** to turn on the distribution schedule. If this option is not marked, the distribution schedule will not run.

5.  If you are creating a new distribution schedule, select the direction that the data will flow:
    
      - Select **Download** if the jobs in the distribution schedule transfer data from Microsoft Dynamics AX to channels.
    
      - Select **Upload** if the jobs in the distribution schedule transfer data from channels to Microsoft Dynamics AX.
    
    The direction that you select determines the jobs that are available to add to the distribution schedule. For example, you can’t add the job P-0001 (POS transactions) to a distribution schedule where **Download** is selected.

6.  On the **Data groups** FastTab, click **Add** to add one or more data groups to the schedule. When you run the distribution schedule, a data package is generated for each data group. All channel databases in a data group subscribe to the same data.
    
    To remove a data group from the schedule, select the data group and then click **Remove**.

7.  On the **Scheduler jobs** FastTab, click **Add** to add one or more jobs to the schedule. To remove a job from the schedule, select the job, and then click **Remove**.

## Create a distribution schedule in AX 2012 R2 or AX 2012 Feature Pack

If you are using AX 2012 R2 or AX 2012 Feature Pack, use the following procedure to create a distribution schedule.

1.  Click **Retail** \> **Periodic** \> **Data distribution** \> **Distribution schedule**.

2.  Click **New** to create a new distribution schedule, or select a distribution schedule to modify.

3.  Enter a name and description for the distribution schedule.

4.  Select an Application Object Server (AOS) connection profile to use for the distribution schedule. For more information, see [Set up an AOS profile](set-up-an-aos-profile.md).

5.  On the **Distribution location list** FastTab, click **Add** to add a distribution location list to the schedule. To remove a distribution location list from the schedule, select the distribution location list, and then click **Remove**.

6.  On the **Scheduler jobs** FastTab, click **Add** to add a job to the schedule. To remove a job from the schedule, select the job, and then click **Remove**.

## Set up batch processing for scheduler jobs

Use the following procedure to set up a batch job for a distribution schedule.

A batch job is a scheduled run of a job or a group of jobs. When you create a batch job, you set up a timer in the AOS instance. The job is then run automatically on the server. To run batch jobs, you must configure the batch server. For more information, see [Configure an AOS instance as a batch server](configure-an-aos-instance-as-a-batch-server.md).

1.  Click **Retail** \> **Periodic** \> **Data distribution** \> **Distribution schedule**.

2.  Select a distribution schedule.

3.  On the **Scheduler jobs** FastTab, select the **Enabled** check box for each scheduler job that the batch job should run.
    
    If you are using AX 2012 R2 or AX 2012 Feature Pack, you can enable or disable multiple jobs at the same time. Select the jobs, and then click **Enable batch job** or **Disable batch job**.

4.  Click **Create batch job**. In the form that is displayed, enter information about the batch job. For more information about the options in the form, see [Submit a batch processing job from a form](submit-a-batch-processing-job-from-a-form.md).

## Run a scheduler job manually

Use the following procedure to run an individual scheduler job manually. The job runs for all distribution location lists that are in the schedule.

1.  Click **Retail** \> **Periodic** \> **Data distribution** \> **Distribution schedule**.

2.  Select the distribution schedule that contains the job to run.

3.  On the **Scheduler jobs** FastTab, select the job to run.

4.  Click **Run now**. (In AX 2012 R2 and AX 2012 Feature Pack, this option is called **Run directly**.)

## View the status of data distribution

In AX 2012 R3, you can view information about past runs of a distribution schedule. In the **Distribution schedule** form, select a distribution schedule and click **History**. For more information, see [View history for a distribution schedule](view-history-for-a-distribution-schedule.md).

  


