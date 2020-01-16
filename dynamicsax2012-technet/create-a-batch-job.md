---
title: Create a batch job
TOCTitle: Create a batch job
ms:assetid: 81a1c46c-d305-4b78-81f1-fb8029d575f7
ms:mtpsurl: https://technet.microsoft.com/library/Gg213151(v=AX.60)
ms:contentKeyID: 35132702
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Create a batch job 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A batch job is a group of tasks that are submitted to an AOS instance for automatic processing.

The tasks in a batch job can run sequentially or simultaneously. In addition, you can create dependencies between one task and another. This means that you can set up a different sequence of tasks, depending on whether an earlier task succeeds or fails.

Batch jobs are run by using the security credentials of the user who created the job.

Batch jobs run on a per-partition basis. A system administrator can create, change, and view the history for the batch jobs in each partition. The batch job administration forms show information about batch jobs only for the partition to which you are currently logged on.

## Create a batch job

1.  Click **System administration** \> **Inquiries** \> **Batch jobs** \> **Batch jobs**.

2.  Press CTRL+N to create a new batch job.

3.  Enter a description for the batch job.

4.  In the **Scheduled start date/time** field, enter the date and time at which you want the batch job to run. If you do not enter a date and time, the current date and time will be entered for you.

5.  Press CTRL+S to save the job.

6.  To set up a recurring job, click the **Recurrence** button, and enter a range and pattern for the recurrence.

7.  To set up an alert for the batch job, click the **Alerts** button, and select alert options.
    

    > [!NOTE]
    > <P>Alerts will always be sent if the <STRONG>Save job to history</STRONG> option on the <STRONG>General</STRONG> tab is set to <STRONG>Always</STRONG>. If this option is set to <STRONG>Errors only</STRONG>, alerts will be sent only if the job was unsuccessful. If this option is set to <STRONG>Never</STRONG>, alerts will not be sent.</P>



## Add a task to a batch job

1.  In the **Batch jobs** form, click the **View tasks** button.

2.  Press CTRL+N to create a new task.

3.  Enter a description for the batch task.

4.  In the **Company accounts** field, select the company database in which the task will run.

5.  In the **Class name** field, select the process that you want the task to run. (Classes appear in the list only if the **CanGoBatchJournal** property is enabled.)
    

    > [!IMPORTANT]
    > <P>Some classes are designated to run on the client. You can add client tasks to a batch job. However, you must run client tasks manually by using the <STRONG>Set up batch processing</STRONG> form. For more information, see <A href="run-client-and-private-batch-tasks.md">Run client and private batch tasks</A>.</P>
    > <P>In Microsoft Dynamics AX 2012, the list of batch classes is only updated when the client is started. For newly-added classes to be reflected in the list of classes, restart the client.</P>



6.  If appropriate, select a batch group for the task.
    
    Client tasks must be assigned to a batch group, and they are automatically assigned to the default batch group (also known as the Empty batch group).

7.  Press CTRL+S to save the task.

8.  To make the selected task dependent on another task in the job, click in the **Has conditions** grid, and follow these steps.
    
    1.  Press CTRL+N to create a new condition.
    
    2.  Select the task ID of the parent task.
    
    3.  Select the status that the parent task must reach before the dependent task can run.
    
    4.  Press CTRL+S to save the condition.
    
    If you have entered more than one condition, and if all conditions must be met before the dependent task can run, select a condition type of **All**. Select a condition type of **Any** if the dependent task can run after any of the conditions has been met.

9.  Choose how to handle task failures. To ignore the failure of a specific task, on the **General** tab, mark the **Ignore task failure** option for that task. If this option is marked, the failure of the task will not cause the job to fail. You can also use the **Maximum retries** field to specify the number of times that a task should be retried before it is considered to have failed.

## See also

[Batch tasks (form)](https://technet.microsoft.com/library/hh209494\(v=ax.60\))

[Recurrence (form)](https://technet.microsoft.com/library/aa616143\(v=ax.60\))

[Set up alert for batch job (form)](https://technet.microsoft.com/library/hh209082\(v=ax.60\))

  


