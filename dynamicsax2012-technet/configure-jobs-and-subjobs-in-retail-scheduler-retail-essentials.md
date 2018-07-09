---
title: Configure jobs and subjobs in Retail Scheduler (Retail essentials)
TOCTitle: Configure jobs and subjobs in Retail Scheduler (Retail essentials)
ms:assetid: 0fa0b1db-53b2-4808-9f84-9f0eede40a4f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn716044(v=AX.60)
ms:contentKeyID: 62200307
ms.date: 08/15/2014
mtps_version: v=AX.60
---

# Configure jobs and subjobs in Retail Scheduler (Retail essentials) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

In Retail essentials, scheduler jobs are used to distribute and synchronize data between Retail essentials and retail stores. Each job consists of one or more subjobs. This topic explains how to create jobs and subjobs to distribute retail data.


> [!NOTE]
> <P>In Retail essentials, the forms that you use to complete these tasks might include a subset of the controls that are available for other configurations of Microsoft Dynamics AX 2012 for Retail. If other topics about these forms describe controls that you don't see, it might be because you’re using Retail essentials.</P>



## Initialize predefined jobs and subjobs

Retail essentials includes predefined scheduler jobs and subjobs that meet the requirements of most organizations. To add information to these jobs and subjobs, you must initialize them in Retail essentials. Complete this task even if you want to customize the jobs and subjobs, because it helps save time.


> [!NOTE]
> <P>If you already completed this task when you deployed Retail essentials, you can skip this procedure.</P>



To initialize predefined jobs and subjobs, follow these steps:

1.  Click **Retail essentials** \> **Channels** \> **Setup** \> **Retail parameters**.

2.  In the upper-left corner of the form, click **Initialize**.

The following types of predefined jobs are created:

  - **Download jobs (N jobs)** – Download jobs, or N jobs, send data from Retail essentials to store databases. N jobs delete all existing data in the destination tables and then insert data.
    
    Use N jobs to bulk copy data to all the store locations in your organization. If the data in a table is company-specific, an N job sends only the rows that match the legal entity of the destination.

  - **Upload (P jobs)** – Upload jobs, or P jobs, pull data from a list of distribution locations and insert that data into the Retail essentials database. Typically, P jobs are used to copy transactions and orders from a store database into Retail essentials.
    
    P jobs upload data incrementally. When a P job runs, Commerce Data Exchange: Async Client checks the replication counter for records that have already been received from a location. The instance of Async Client for the channel sends only those records that have a replication counter that exceeds the largest value that is found. P jobs do not update data that was previously uploaded.


> [!NOTE]
> <P>The following procedures assume that you are using the jobs that were set up for you when you initialized jobs and subjobs. If you modified those jobs or created additional jobs, you might have to modify these procedures.</P>



## Create or modify a subjob

Complete this procedure to create or modify subjobs that distribute data modifications in selected tables to specific locations. A subjob contains information about a single table.

To create or modify a subjob, follow these steps:

1.  Click **Retail essentials** \> **Data synchronization** \> **Setup** \> **Scheduler setup** \> **Scheduler subjobs**.

2.  Click **New** to create a new subjob, or select a subjob to modify.
    
    You can also copy the settings of an existing subjob to a new subjob.

3.  If you are creating a subjob, in the **Subjob number** field, enter a unique identifier for the subjob.

4.  If the subjob replicates data from the point of sale (POS) database or Commerce Runtime (CRT) database, and writes data to the Retail essentials database, select the **Pull data** check box.

5.  In the **Channel table name** field, enter the name of the table in the destination database. In the **Microsoft Dynamics AX table name** field, enter the name of the table in the Retail essentials database.
    
    For P jobs, you must also specify the temporary database table to use. To create the temporary table, click **Create staging table**.

6.  Enter any other information that is required. To find help about fields that are not described in this topic, see [Scheduler subjobs (form)](https://technet.microsoft.com/en-us/library/hh597422\(v=ax.60\)).

## Create or modify a job

Each scheduler job consists of one or more subjobs. Jobs should contain subjobs that are related. For example, the Currency job contains subjobs that update currencies and exchange rates.

To create or modify a job, follow these steps:

1.  Click **Retail essentials** \> **Data synchronization** \> **Setup** \> **Scheduler setup** \> **Scheduler jobs**.

2.  Click **New** to create a new job, or select a job to modify.
    
    You can also copy the settings of an existing job to a new job.

3.  If you are creating a job, in the **Job name** field, enter a unique identifier for the job.

4.  Add subjobs to the job.
    
    You can assign a subjob to more than one job.

5.  Enter any other information that is required. To find help about fields that are not described in this topic, see [Scheduler job (form)](https://technet.microsoft.com/en-us/library/hh672166\(v=ax.60\)).

## See also

[Schedule and run jobs in Retail Scheduler (Retail essentials)](schedule-and-run-jobs-in-retail-scheduler-retail-essentials.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

