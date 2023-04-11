---
title: 'Key tasks: Process production jobs in Manufacturing execution'
TOCTitle: 'Key tasks: Process production jobs in Manufacturing execution'
ms:assetid: 7fbe1c7f-d6eb-4faa-aa28-9f12c158b91a
ms:mtpsurl: https://technet.microsoft.com/library/Hh209297(v=AX.60)
ms:contentKeyID: 36058334
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- job
- production
- jobs
- manufacturing execution
- shop floor
audience: Application User
ms.search.region: Global
---

# Key tasks: Process production jobs in Manufacturing execution 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In **Manufacturing execution**, various tasks can be conducted by a shop supervisor or manager to handle changes or updates in jobs and operations from released production orders and projects and project activities.

Most tasks can be performed on a Microsoft Dynamics AX client or on a **Manufacturing execution** registration client. Depending on the selected client, the first steps (log on, select menu items) and last steps (submit data, log out) of some procedures can be different. Where relevant, both procedures are included in the procedure descriptions. Also, depending on whether the input device on the **Manufacturing execution** registration terminal is a keyboard or touch screen, the buttons that are available may differ.

## What do you want to do?

Learn more about...

Move jobs from a resource group to a resource

Move jobs from one resource to another

Reprioritize jobs in a job list

Set jobs to High priority

Set up document groups

Attach files to jobs

Correct erroneous registrations

View attendance

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[About registration for manufacturing execution](about-registration-for-manufacturing-execution.md)

[About production feedback](about-production-feedback.md)

## Move jobs from a resource group to a resource

Whether a shop supervisor or manager must manually move jobs from a resource group to a resource depends on the scheduling method that is used during production planning.

If **Operations scheduling** is used, operations (jobs) are planned on dates only, and planning is performed on either resource group level or resource level. If planning is performed on resource groups, you must manually move operations. This must be from the resource group to the resources such as workers or machines within that group. This task can be performed on a Microsoft Dynamics AX client, or on a **Manufacturing execution** registration client.

If **Job scheduling** is used, jobs are planned on both date and time, and planning is always done on the resource level. In this case, you do not have to move jobs from a resource group to resources within that group.

1.  Microsoft Dynamics AX client:
    
    1.  Click **Production control** \> **Periodic** \> **Manufacturing execution** \> **Edit job list**.
    
    2.  In the **Select resource and action** form, select the resource group from which you want to move operations (jobs).

2.  **Manufacturing execution** registration client:
    
    1.  Log on with your **Personnel number**.
    
    2.  In the **Select resource and action** form, select the resource group from which you want to move operations or jobs.
    
    3.  Click the **Edit job list** button.

3.  In the **Edit job list** form, select the operations (jobs) you want to move to a specific resource. Click the **Select** check boxes of the jobs to be moved.

4.  Click the **Move to resource** button.

5.  Select the resource to which the operations (jobs) should be moved. A new **Edit job list** form opens, displaying the job list of the selected resource, and the selected operations (jobs) are inserted in the job list.

6.  If necessary, use the **Move up**, **Move down**, and **Move to line** buttons to move the operations (jobs) to the correct position in the job list.

7.  Click **Submit sequence**.

8.  Repeat the previous steps until all operations (jobs) have been moved from the resource group to a resource.

9.  Complete the following procedure:
    
      - Microsoft Dynamics AX client: Close the **Edit job list** form.
    
      - **Manufacturing execution** registration client: Click **Log out**.

Back to top

## Move jobs from one resource to another

A shop supervisor or manager can move jobs assigned to one resource to another resource. This functionality is useful if, for example, a worker calls in sick and some of his or her jobs have to be completed today. Another example is when the workload in a team is not aligned, and one worker has many jobs in the job list although a colleague is not very busy. Then, the shop supervisor can balance the work load by transferring jobs from one resource to another. This task can be performed on a Microsoft Dynamics AX client, or on a **Manufacturing execution** registration client.


> [!NOTE]
> <P>Jobs can only be moved to another resource in the same resource group.</P>



1.  Microsoft Dynamics AX client:
    
    1.  Click **Production control** \> **Periodic** \> **Manufacturing execution** \> **Edit job list**.
    
    2.  In the **Select resource and action** form, select the resource from which you want to move jobs.

2.  **Manufacturing execution** registration client:
    
    1.  Log on by entering your **Personnel number**.
    
    2.  In the **Select resource and action** form, select the resource from which you want to move jobs.
    
    3.  Click the **Edit job list** button.
    

    > [!NOTE]
    > <P>Depending on the legal entity setup, you may want to select <STRONG>Production unit</STRONG> and <STRONG>Resource group</STRONG>. If your legal entity has only one <STRONG>Production unit</STRONG> and one <STRONG>Resource group</STRONG>, you only have to select a <STRONG>Resource</STRONG>.</P>



3.  In the **Edit job list** form, select the jobs you want to move to another resource. Click the **Select** check boxes of the jobs to be moved.

4.  Click the **Move to resource** button.

5.  Select the resource to which the jobs should be moved. A new **Edit job list** form opens, displaying the job list of the selected resource, and the selected jobs are inserted in the job list.

6.  If necessary, use the **Move up**, **Move down**, and **Move to line** buttons to move the jobs to the correct position in the job list.

7.  Click **Submit sequence**.

8.  Repeat the previous steps until all relevant jobs have been moved to another resource.

9.  Complete the following procedure:
    
      - Microsoft Dynamics AX client: Close the **Edit job list** form.
    
      - **Manufacturing execution** registration client: Click **Log out**.

Back to top

 

## Reprioritize jobs in a job list

A shop supervisor or manager can reprioritize jobs in a worker’s job list. For example, a production may have been upgraded to a rush order that has to be completed as soon as possible. Consequently, the supervisor must be able to reprioritize jobs to make sure that all relevant jobs get the highest priority. This task can be performed on a Microsoft Dynamics AX client, or on a **Manufacturing execution** registration client.

1.  Microsoft Dynamics AX client:
    
    1.  Click **Production control** \> **Periodic** \> **Manufacturing execution** \> **Edit job list**.
    
    2.  In the **Select resource and action** form, select the resource for which you want to reprioritize jobs.

2.  **Manufacturing execution** registration client:
    
    1.  Log on by entering your **Personnel number**.
    
    2.  In the **Select resource and action** form, select the resource for which you want to reprioritize jobs.
    
    3.  Click the **Edit job list** button.
    

    > [!NOTE]
    > <P>Depending on the legal entity setup, you may have to select <STRONG>Production unit</STRONG> and <STRONG>Resource group</STRONG>. If your legal entity has only one <STRONG>Production unit</STRONG> and one <STRONG>Resource group</STRONG>, you only have to select a <STRONG>Resource</STRONG>.</P>



3.  In the **Edit job list** form, select the jobs you want to reprioritize. Click the **Select** check boxes of those jobs.

4.  Use the **Move up**, **Move down**, and **Move to line** buttons to move the jobs to the correct position in the job list.
    

    > [!NOTE]
    > <P>All the jobs connected to a specific operation will be moved. This means that if an operation consists of three jobs, and you have selected only one of those jobs, all three jobs will automatically be moved.</P>



5.  Click **Submit sequence**.

6.  Complete the following procedure:
    
      - Microsoft Dynamics AX client: Close the **Edit job list** form.
    
      - **Manufacturing execution** registration client: Click **Log out**.

Back to top

## Set jobs to High priority

A shop supervisor or manager can prioritize jobs in a worker’s job list and set the jobs to **High priority**. This functionality is useful if you want to make sure that a worker does not change the sequence for certain jobs in his or her job list. This task can be performed on a Microsoft Dynamics AX client, or on a **Manufacturing execution** registration client.

1.  Microsoft Dynamics AX client:
    
    1.  Click **Production control** \> **Periodic** \> **Manufacturing execution** \> **Edit job list**.
    
    2.  In the **Select resource and action** form, select the resource for which you want to set jobs to **High priority**.

2.  **Manufacturing execution** registration client:
    
    1.  Log on by entering your **Personnel number**.
    
    2.  In the **Select resource and action** form, select the resource for which you want to set jobs to **High priority**.
    
    3.  Click the **Edit job list** button.
    

    > [!NOTE]
    > <P>Depending on the legal entity setup, you may want to select <STRONG>Production unit</STRONG> and <STRONG>Resource group</STRONG>. If your legal entity has only one <STRONG>Production unit</STRONG> and one <STRONG>Resource group</STRONG>, you only have to select a <STRONG>Resource</STRONG>.</P>



3.  In the **Edit job list** form, select the jobs you want to set to **High priority**. Click the **Select** check boxes of those jobs.

4.  Click **Make high priority**.
    

    > [!NOTE]
    > <P>All the jobs connected to a specific operation will be marked as <STRONG>High priority</STRONG> and moved to the top of the job list. This means that if an operation consists of three jobs, and you selected only one of those jobs, all three jobs will automatically be moved and set to <STRONG>High priority</STRONG>.</P>



5.  Click **Submit sequence**.

6.  Complete the following procedure:
    
      - Microsoft Dynamics AX client: Close the **Edit job list** form.
    
      - **Manufacturing execution** registration client: Click **Log out**.


> [!NOTE]
> <P>If you want to remove a <STRONG>High priority</STRONG> mark previously set on a job, follow the steps earlier in this topic, but in step 4, click the <STRONG>Remove high priority</STRONG> button instead.</P>



Back to top

 

## Set up document groups

In **Manufacturing execution**, you can view documents attached to jobs. Workers can view the documents in the **Job registration** form when they start jobs or continue to work on jobs. However, you have to set up document groups first. For each document group you define the document types to be included in the group. You also specify the workers who can view the document types set up for the document group.

This task can only be performed on a Microsoft Dynamics AX client.

1.  Click **Production control** \> **Setup** \> **Document groups**.

2.  In the **Document groups** form, press CTRL+N to create a new document group, or click **New** on the toolbar.

3.  In the **Document group ID** field, type a name or number to identify the document group.

4.  In the **Description** field, type a description of the document group.

5.  Press CTRL+S to save the document group.

6.  In the **Document types** section, click **Add** to create a new document type.

7.  Select a document type in the **Type** field.

8.  Select the **Required reading** check box if a worker must confirm that he or she has read a document of this kind before a job can be started in the **Job registration** form.
    

    > [!NOTE]
    > <P>If this check box is cleared, the worker does not receive a message about documents that may be attached to the job. In that case, the worker must select the job, and then click the <STRONG>Attachments</STRONG> button in the <STRONG>Job registration</STRONG> form to check if any documents are attached to the job.</P>



9.  Select the **Required once** check box. Do this only if you want the **Required reading** rule to apply the first time that a worker is presented with this kind of document when starting a specific job in the **Job registration** form. Example: A worker starts a job in the **Job registration** form. The worker confirms reading a work instruction. However, the worker does not finish the job that same work day. There are still some items to be produced the next day. The next morning when the worker starts the job again to produce the last items of the order, if this check box is selected, he or she is not asked to confirm reading the work instruction again.
    

    > [!NOTE]
    > <P>If you want to attach safety instructions to a job, you should carefully consider if the instructions have to be read only the first time a job is started by a worker, or if the worker must use the instructions every time that the job is started.</P>



10. Repeat steps 6-9 until you have created all the relevant **Document types**.

11. In the **Members** section, click **Add** to add a worker to the group.

12. Select a worker in the **Worker** field. The name is automatically inserted in the **Name** field.

13. Repeat steps 11-12 until you have created all the relevant **Members** of the document group.

Back to top

 

## Attach files to jobs

You can attach documents or files to an item, a BOM, a production, or an operation. Settings in the **Document groups** form in the **Manufacturing execution** module determine whether a worker must read instructions before they start a particular job in the **Job registration** form. After you have created the **Document groups**, the next step is to attach the relevant files to a record (item, BOM, production, or operation).

This task can only be performed on a Microsoft Dynamics AX client.

For information, see [Create a reference to an existing document](create-a-reference-to-an-existing-document.md)

Back to top

 

## Correct erroneous registrations

A shop supervisor or manager can correct erroneous registrations made by workers. For example, a worker may have reported wrong feedback regarding the produced quantity or the current status of a production job. This task can be performed on a Microsoft Dynamics AX client, or on a **Manufacturing execution** registration client.

1.  Microsoft Dynamics AX client:
    
    1.  Click **Production control** \> **Periodic** \> **Manufacturing execution** \> **Change feedback**.
    
    2.  In the **Select resource and action** form, select the resource for which you want to correct registrations.

2.  **Manufacturing execution** registration client:
    
    1.  Log on by entering your **Personnel number**.
    
    2.  In the **Select resource and action** form, select the resource for which you want to correct registrations.
    
    3.  Click the **Change feedback** button.
    

    > [!NOTE]
    > <P>Depending on the legal entity legal entity setup, you may want to select <STRONG>Production unit</STRONG> and <STRONG>Resource group</STRONG>. If your legal entity has only one <STRONG>Production unit</STRONG> and one <STRONG>Resource group</STRONG>, you only have to select a <STRONG>Resource</STRONG>.</P>



3.  In the **Change feedback** form, select the jobs for which you want to correct registrations. Click the **Select** check boxes of those jobs.
    

    > [!TIP]
    > <P>Click the <STRONG>Change interval</STRONG> button if you want to select another period for which to see the job list, for example, this week, or this month.</P>



4.  Click the **Update feedback** button. The **Update feedback** form or the **Report feedback** form opens. For more information, see [Key tasks: Work with production jobs in Manufacturing execution](key-tasks-work-with-production-jobs-in-manufacturing-execution.md).

5.  Complete the following procedure after you have corrected all erroneous registrations:
    
      - Microsoft Dynamics AX client: Close the **Change feedback** form.
    
      - **Manufacturing execution** registration client: Click **Log out**.

Back to top

## View attendance

If your legal entity uses **Time and attendance** and **Manufacturing execution**, you can view attendance for a group of workers on the current workday. You can also create absence registrations and clock-out registrations for the workers. These tasks can be performed on a Microsoft Dynamics AX client, or on a **Manufacturing execution** registration client.

1.  Microsoft Dynamics AX client:
    
    1.  Click **Human resources** \> **Inquiries** \> **Time and attendance** \> **Attendance**.
    
    2.  Select a **Calculation group**.

2.  **Manufacturing execution** registration client:
    
    1.  Log on by entering your **Personnel number**.
    
    2.  In the **Select resource and action** form, click the **Attendance** button.
    
    3.  Select a **Calculation group**.

3.  The **Attendance** form shows a list of all workers in the selected calculation group. This includes their clock-in, clock-out, and absence registrations for the current work day. If necessary, you can make registrations for a worker.

4.  Create an absence registration:
    
    1.  In the **Attendance** form, select the worker for which you want to create an absence registration.
    
    2.  Click the **Absence** button.
    
    3.  In the **Absence registration** form, select the relevant absence registrations.
    
    4.  Insert date and time interval for the absence registration.
    
    5.  Select the **Interrupt** check box to automatically stop the absence registration if the worker makes a clock-in registration before the specified end date and time.

5.  Create clock-out registration:
    
    1.  In the **Attendance** form, select the worker you want to clock out.
    
    2.  Click the **Clock out** button.
    
    3.  In the **Clock out workers** form, insert the profile date on which to make the clock-out registration.
    
    4.  Click the **Select** button to select which workers should get a clock-out registration.

6.  Complete the following procedure after you have created all the relevant registrations:
    
      - Microsoft Dynamics AX client: Close the **Attendance** form.
    
      - **Manufacturing execution** registration client: Click **Log out**.

Back to top

## Find form help

[Change feedback (form)](https://technet.microsoft.com/library/aa585926\(v=ax.60\))

[Edit job list (form)](https://technet.microsoft.com/library/hh209583\(v=ax.60\))

[Document groups (form)](https://technet.microsoft.com/library/hh227635\(v=ax.60\))

[Select resource and action (form)](https://technet.microsoft.com/library/hh242202\(v=ax.60\))

[Document handling (form)](https://technet.microsoft.com/library/aa616432\(v=ax.60\))

[Attendance (form)](https://technet.microsoft.com/library/aa585011\(v=ax.60\))

## Find related tasks

[Key tasks: Work with production jobs in Manufacturing execution](key-tasks-work-with-production-jobs-in-manufacturing-execution.md)

[View daily registrations in manufacturing execution](view-daily-registrations-in-manufacturing-execution.md)

[Create a reference to an existing document](create-a-reference-to-an-existing-document.md)

  


