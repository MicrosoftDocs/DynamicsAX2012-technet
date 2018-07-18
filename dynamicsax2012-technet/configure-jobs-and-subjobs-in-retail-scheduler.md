---
title: Configure jobs and subjobs in Retail Scheduler
TOCTitle: Configure jobs and subjobs in Retail Scheduler
ms:assetid: ac7af386-fd6c-4f03-bea6-306db0537b87
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ680084(v=AX.60)
ms:contentKeyID: 49558130
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Configure jobs and subjobs in Retail Scheduler 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

In Retail, scheduler jobs are the mechanism for distributing data to and from locations. Each job consists of one or more subjobs. This topic explains how to create jobs and subjobs to distribute retail data.

## Initialize predefined jobs and subjobs

Microsoft Dynamics AX includes predefined scheduler jobs and subjobs that meet the replication requirements of most organizations. To populate these jobs and subjobs, you must initialize Retail. Complete this task even if you want to customize these jobs and subjobs, because it helps save time.


> [!NOTE]
> <P>If you already completed this task when you deployed Retail, you can skip this procedure.</P>



1.  Click **Retail** \> **Setup** \> **Parameters** \> **Retail parameters**.

2.  On the **General** tab, click **Initialize**.


> [!NOTE]
> <P>The procedures in this documentation assume that you are using the jobs that were set up for you when you initialized jobs and subjobs. If you have modified those jobs or created additional jobs, you might want to modify the procedures.</P>



### ![JJ680084.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ680084.collapse_all(en-us,AX.60).gif")Predefined jobs in AX 2012 R3

In AX 2012 R3, the following types of predefined jobs are created:

  - **Download jobs** – Download jobs send data that has changed from Microsoft Dynamics AX to channel databases. Modifications to records are tracked through SQL Server change tracking.

  - **Upload jobs (P jobs)** – Upload jobs pull sales transactions from a channel into the Microsoft Dynamics AX database.
    
    P jobs upload data incrementally. When a P job runs, Async Client checks the replication counter for records that have already been received from a location. The instance of Async Client for the channel sends only those records that have a replication counter that is greater than the largest value found. P jobs do not update data that was previously uploaded.

### ![JJ680084.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ680084.collapse_all(en-us,AX.60).gif")Predefined jobs in AX 2012 R2 and AX 2012 Feature Pack

In AX 2012 R2 and AX 2012 Feature Pack, the following types of predefined jobs are created:

  - **Action (A) jobs** – A jobs send data that has changed from Microsoft Dynamics AX to channel databases. Data modifications are tracked as actions. The locations that receive the jobs are determined by the distribution settings for the records that changed or their parent records.
    
    Use A jobs to distribute data incrementally. A jobs can be used to transfer data to a specific channel, or to customize the way that changes to tables are distributed. If the data in a table is company-specific, an A job sends only the rows that match the legal entity of the destination.

  - **Normal (N) jobs** – N jobs send data from Microsoft Dynamics AX to channel databases. N jobs do not depend on actions. Instead, N jobs send all data in a table. N jobs delete all existing data in the destination tables and then insert data.
    
    Use N jobs to bulk copy data to all the channel locations in your organization. If the data in a table is company-specific, an N job sends only the rows that match the legal entity of the destination.

  - **Pull (P) jobs** – P jobs pull data from a distribution location list and insert that data into the Microsoft Dynamics AX database. Typically, P jobs are used to copy transactions and orders from a channel into Microsoft Dynamics AX.
    
    P jobs distribute data incrementally, but not in the same way as A jobs. When a P job runs, the instance of Synch Service at headquarters checks the replication count for records that have already been received from a location. The instance of Synch Service for the location sends only those records that have a replication count that is greater than the largest value found at headquarters. P jobs do not update data that was previously distributed.

## Create or modify a subjob in AX 2012 R3

If you’re using AX 2012 R3, complete this procedure to create or modify subjobs that distribute data between Microsoft Dynamics AX and retail channels. A subjob contains information about a single table.

1.  Click **Retail** \> **Setup** \> **Retail scheduler** \> **Scheduler subjobs**.

2.  Click **New** to create a new subjob, or select the subjob to modify.
    
    You can also copy the settings of an existing subjob to a new subjob.

3.  If you are creating a subjob, enter a unique identifier for the subjob in the **Subjob number** field. Optionally, enter a description.

4.  If the subjob replicates data from the channel database and writes data to the Microsoft Dynamics AX database, select the **Pull data** check box.

5.  In the **Retail channel schema** field, select the schema to use for the subjob, based on the Microsoft Dynamics AX version and type of channel.

6.  In the **Channel table name** field, enter the name of the table in the channel database. In the **Microsoft Dynamics AX table name** field, enter the name of the table in the Microsoft Dynamics AX database. For P jobs, you must also specify the temporary database table to use. To create the temporary table, click **Create staging table**.

7.  Enter other information in the form, if more information is required. For help with fields that are not described in this topic, see [Scheduler subjobs (form)](https://technet.microsoft.com/en-us/library/hh597422\(v=ax.60\)).

## Create or modify a subjob in AX 2012 R2 and AX 2012 Feature Pack

If you’re using AX 2012 R2 or AX 2012 Feature Pack, complete this procedure to create or modify subjobs that distribute data modifications in selected tables to specific locations. A subjob contains information about a single table.

1.  Click **Retail** \> **Setup** \> **Retail scheduler** \> **Scheduler subjobs**.

2.  Click **New** to create a new subjob, or select the subjob to modify.
    
    You can also copy the settings of an existing subjob to a new subjob.

3.  If you are creating a subjob, enter a unique identifier for the subjob in the **Subjob number** field.

4.  If the subjob replicates data from the channel database and writes data to the Microsoft Dynamics AX database, select the **Pull data** check box.
    
    If the subjob replicates data from the Microsoft Dynamics AX database and writes data to the channel database, select **Normal** or **By actions** in the **Replication method** field. If you select **Normal**, all existing data is deleted in the destination tables, and then updated data is inserted. If you select **By actions**, only data that changed is distributed, and the distribution is based on action filters.

5.  In the **Channel table name** field, enter the name of the table in the destination database. In the **Microsoft Dynamics AX table name** field, enter the name of the table in the Microsoft Dynamics AX database. For P jobs, you must also specify the temporary database table to use. To create the temporary table, click **Create staging table**.

6.  Enter other information in the form, if more information is required. For help with fields that are not described in this topic, see [Scheduler subjobs (form)](https://technet.microsoft.com/en-us/library/hh597422\(v=ax.60\)).

## Create or modify a scheduler job

Each scheduler job consists of one or more subjobs. Jobs should contain subjobs that are related. For example, the Currency job contains subjobs that update currencies and exchange rates.


> [!NOTE]
> <P>In AX 2012 R2 and AX 2012 Feature Pack, jobs should contain subjobs that use replication methods that are consistent. As a rule, N jobs and P jobs should contain subjobs that use <STRONG>Normal</STRONG> replication, and A jobs should contain subjobs that use <STRONG>By actions</STRONG> replication.</P>



1.  Click **Retail** \> **Setup** \> **Retail scheduler** \> **Scheduler jobs**.

2.  Click **New** to create a new job, or select the job to modify.
    
    You can also copy the settings of an existing job to a new job.

3.  If you are creating a job, enter a unique identifier for the job in the **Job name** field. Optionally, add a description.

4.  In the **Retail channel schema** field, select the schema to use for the job, based on the Microsoft Dynamics AX version and type of channel.

5.  In AX 2012 R3, if the subjob replicates data from the channel database and writes data to the Microsoft Dynamics AX database, select the **Is upload** check box.

6.  Add subjobs to the job.
    

    > [!NOTE]
    > <P>You can assign a subjob to more than one job.</P>



7.  Enter other information in the form, if more information is required. For help with fields that are not described in this topic, see [Scheduler job (form)](https://technet.microsoft.com/en-us/library/hh672166\(v=ax.60\)).

  


