---
title: 'Key tasks: Work with production jobs in Manufacturing execution'
TOCTitle: 'Key tasks: Work with production jobs in Manufacturing execution'
ms:assetid: c4d53512-bb9e-491e-a0fc-9a619cad5778
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242841(v=AX.60)
ms:contentKeyID: 36059297
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- bundle jobs - manufacturing execution
- manufacturing execution
- clock out
- move jobs between resources - manufacturing execution
- clock in
- register as an assistant - manufacturing execution
- open job registration form - manufacturing execution
- report feedback on production job - manufacturing execution
- reprioritize jobs - manufacturing execution
- work with jobs - manufacturing execution
- start a production job - manufacturing execution
---

# Key tasks: Work with production jobs in Manufacturing execution [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In the **Job registration** form, you can perform tasks that are related to one or more production jobs. For example, you can view the instructions for jobs, register feedback about jobs, and administer jobs.


> [!NOTE]
> <P>You can configure the <STRONG>Job registration</STRONG> form so that it displays information based on your requirements. The path that you use to open the form can vary, depending on the configuration of the form. For more information, see <A href="https://technet.microsoft.com/en-us/library/aa616991(v=ax.60)">Configure registration forms (form)</A>. For the tasks that are described in this topic, the <STRONG>Job registration</STRONG> form is set up so that all users can use the form.</P>



## What do you want to do?

Open the Job registration form

Clock in

Clock out

Start a production job

Read the files that are attached to a production job

Report feedback about production jobs

Register as an assistant and centralize registration

Bundle jobs

Reprioritize the jobs in a job list

Assign a different resource to a job

Find form help

Find related tasks

## Open the Job registration form

Click **Production control** \> **Periodic** \> **Manufacturing execution** \> **Job registration**. In the **Select resource and action** form, select a production unit, resource group, or resource, and then click **Open production unit**, **Open resource group**, or **Open resource**. In the **Welcome** form, enter your logon information. In the **Select resource and action** form, click **Job registration**.

Back to top

## Clock in

When you arrive at work, you must clock in before you can start your tasks.

1.  In the **Welcome** form, enter your access code. Depending on the settings that are defined in the **Time and attendance parameters** form, this might be your personnel ID number, badge ID, or personal identification number (PIN).

2.  Click **Log in**.


> [!NOTE]
> <P>If no activity is registered in the form, a time-out event will occur and you must log on again. Also, if you arrive late to work, you might be prompted to select a reason for the absence when you clock in.</P>



Back to top

## Clock out

At the end of the workday, you must clock out before you leave work.

1.  In the **Job registration** form, on the **Action Pane**, click **Time and attendance** \> **Clock out**.

2.  In the **Clock out** form, click **OK**.


> [!NOTE]
> <P>Your workday is defined in your profile. If you clock out before the end of the workday, you might be prompted to select a reason for the absence.</P>



Back to top

## Start a production job

1.  In the **Job registration** form, view or select the production view, and then select the jobs that you want to start. The data that is displayed depends on whether you are using a touchscreen or a standard computer.
    
      - If you are using a touchscreen, tap the jobs that you want to start.
    
      - If you are not using a touchscreen, select the **Select** check box for each job that you want to start.

2.  Click or tap **Start jobs** on the **Action Pane**.

You can start more than one job at the same time. This action is called job bundling. You can also add jobs to an existing job bundle. For more information, see the “Bundle jobs” section later in this topic.

Back to top

## Read the files that are attached to a production job

You can attach files to a job. For example, the files can contain production instructions or a diagram.

If the files that are attached to a job are categorized as mandatory reading, the **View attachments** form is displayed when you start the job. This form contains a list of the documents that you must read before you can start the job.

1.  In the **View attachments** form, select an attachment, and then click **Open documents**.

2.  After you read the files that are categorized as mandatory reading, confirm that you have read them. You are then logged off.

3.  Log on again to continue to work in the **Job registration** form.

If the attachments are not classified as mandatory reading, the **View attachments** form is not displayed when you start the job. To see whether files are attached to the job, in the **Job registration** form, select the job in the list, click the **General** **(** **F12** **)** tab on the **Action Pane**, and then click **Attachments**.

Back to top

## Report feedback about production jobs

To report feedback about production jobs, use one of the following methods. The method can vary, depending on the configuration of the system.

**Report feedback about multiple production jobs**

For this method of reporting feedback, use the **Report feedback** form. Click **Production control** \> **Periodic** \> **Manufacturing execution** \> **Job registration**. Select a production unit, resource group, or resource. Depending on the selection, click **Open production unit**, **Open resource group**, or **Open resource**. The form displays a list of production jobs. You can select jobs and enter feedback.

1.  On the **Action Pane**, on the **Manage activities** **(** **F10** **)** tab, click one of the following buttons. The buttons that are available vary, depending on the configuration of the system.
    
      - **Feedback** – Report feedback about the selected jobs.
    
      - **Completed** – Set the selected jobs to this status if they are completed and do not require more work.
    
      - **Stopped** – Set the selected jobs to this status if they are not completed, but you are not currently working on them.
    
      - **In progress** – Set the selected jobs to this status if you plan to continue to work on them after you report feedback.

2.  In the **Good** field, enter the number of produced items that comply with quality standards.

3.  In the **Error** field, enter the number of scrapped items that were produced, and then select a reason that explains why the items were scrapped.

4.  Change the status of the selected jobs, if this is necessary.

**Report feedback on a single production job**

For this method of reporting feedback, you use the **Update feedback** wizard. This method is convenient if you use a touchscreen.

1.  Click **Production control** \> **Periodic** \> **Manufacturing execution** \> **Change feedback**. Select a production unit, resource group, or resource. Depending on the selection, click **Open production unit**, **Open resource group**, or **Open resource**.

2.  In the **Change feedback** form, on the **Action Pane**, click **Update feedback**.

3.  In the **Status** field group, select one of the following options. The options that are available vary, depending on the configuration of the system.
    
      - **Feedback** – Report feedback about the job.
    
      - **Completed** – Set the job to this status if it is completed and does not require more work.
    
      - **Stopped** – Set the job to this status if it is not completed, but you are not currently working on it.
    
      - **In progress** – Set the job to this status if you plan to continue to work on it after you report feedback.

4.  In the **Report good quantity:** field, enter the number of produced items that comply with quality standards.

5.  In the **Error quantity** field, enter the number of scrapped items that were produced. Then, in the **Error cause** field, select a reason that explains why the items were scrapped.
    
    To create or delete error quantity records, use the **Add** and **Remove** buttons.

6.  Change the status of the job, if this is necessary.

7.  Use the buttons at the bottom of the wizard to view the next job or the previous job.

8.  After you report feedback about all jobs, click **Finish**.

Back to top

 

## Register as an assistant and centralize registration

When multiple workers are assigned to the same production jobs, they can centralize the registration process by registering as an assistant to a selected worker. The result of this registration is a team, and the selected worker becomes the pilot worker for the team. A pilot worker can start jobs and enter registrations for the team members.

When you work as an assistant, you can register time for the jobs that the pilot worker starts. However, you cannot register the quantities that are produced on the jobs.

A team is assembled for the duration of the current shift. When all members of the team log off at the end of the shift, they must register as assistants again the next time that they log on. If you want the team to remain assembled for a longer duration, you can select the **Permanent teams** check box in the **Manufacturing execution parameters** form. If you select the check box, all teams will remain assembled.

You can view the members of the team in the Teams form in **Human resources**. For more information, see [Teams (form)](https://technet.microsoft.com/en-us/library/aa585287\(v=ax.60\)).

To change the pilot of a team, the current pilot can click the **Assistant** button and select another worker. The members of the team become assistants to the new pilot.

The following step describes how to register as an assistant to a worker.

  - In the **Job registration** form, on the **Action Pane**, click **Assistant**, and then select the worker who will be the pilot.
    

    > [!NOTE]
    > <P>If you are working on jobs in a job list, you may be prompted to provide feedback about the jobs before you can start working as an assistant. For more information, see the “Report feedback about production jobs” section in this topic.</P>



Back to top

 

## Bundle jobs

When you work on multiple production jobs or operations at the same time, you are bundling the jobs. In the **Job registration** form, you can start several jobs at the same time. For more information about how to start a job, see “Start a production job” earlier in this topic.

You can add jobs to an existing bundle after you have started one or more of the jobs in the bundle.

1.  In the **Job registration** form, select the jobs to add to the bundle.
    
      - If you are using a touchscreen, tap the jobs that you want to start.
    
      - If you are not using a touchscreen, select the **Select** check box for each job that you want to start.

2.  Click **Bundle** on the **Action Pane**.

3.  Confirm that you want to start the selected jobs.

If you want to start a new job, but you do not want to bundle it with the first job, you must register the status of the first job.

Back to top

 

## Reprioritize the jobs in a job list

In a job list, some jobs might have a high priority. An exclamation point in the **High priority** column identifies a high-priority job. You cannot change the sequence of high-priority jobs. However, depending on the configuration of the system, you might be able to change the sequence of the other jobs in your job list.

1.  Click **Production control** \> **Periodic** \> **Manufacturing execution** \> **Edit job list**. Select a production unit, resource group, or resource. Depending on the selection, click **Open production unit**, **Open resource group**, or **Open resource**.

2.  Select the jobs to reprioritize.
    
      - If you are using a touchscreen, tap the jobs that you want to move.
    
      - If you are not using a touchscreen, select the **Select** check box for each job that you want to move.

3.  Click the **Move up**, **Move down**, and **Move to line** buttons on the **Action Pane** to move the jobs to the correct position in the job list.

4.  Click **Submit sequence** on the **Action Pane**. The production jobs that you selected, and any jobs that are connected to the operation, are moved to the new position in the job list.

5.  Close the form.
    
      - If you are using a touchscreen, tap **Log out**.
    
      - If you are not using a touchscreen, click the **Close** button in the upper-right corner or press the ESC key.

Back to top

 

## Assign a different resource to a job

You can move jobs from one resource to another resource in the same resource group. Moving jobs can be useful when, for example, a worker is ill or jobs are load balanced.

1.  Click **Production control** \> **Periodic** \> **Manufacturing execution** \> **Edit job list**. Select a production unit, resource group, or resource. Depending on the selection, click **Open production unit**, **Open resource group**, or **Open resource**.

2.  Select the jobs to change the resource for.
    
      - If you are using a touchscreen, tap the jobs that you want to change the resource for.
    
      - If you are not using a touchscreen, select the **Select** check box for each job that you want to change the resource for.

3.  Click **Change assigned resource** on the **Action Pane**.

4.  Select the resource to assign to the job.

5.  Click **Submit sequence** on the **Action Pane**. The assigned resource is changed for production jobs that you selected, and for any jobs that are connected to the operation. The **Job registration** form displays these jobs in their new order and priority.

6.  Close the form.
    
    1.  If you are using a touchscreen, tap **Log out**.
    
    2.  If you are not using a touchscreen, click the **Close** button in the upper-right corner, or press the ESC key.

Back to top

## Find form help

[Job registration - resource (form)](https://technet.microsoft.com/en-us/library/aa554833\(v=ax.60\))

[Configure registration forms (form)](https://technet.microsoft.com/en-us/library/aa616991\(v=ax.60\))

[Terminals (form)](https://technet.microsoft.com/en-us/library/aa585567\(v=ax.60\))

[Job registration (Job list) (form)](https://technet.microsoft.com/en-us/library/aa634723\(v=ax.60\))

[Update feedback (form)](https://technet.microsoft.com/en-us/library/hh227469\(v=ax.60\))

[Edit job list (form)](https://technet.microsoft.com/en-us/library/hh209583\(v=ax.60\))

[Select resource and action (form)](https://technet.microsoft.com/en-us/library/hh242202\(v=ax.60\))

## Find related tasks

[About registration for manufacturing execution](about-registration-for-manufacturing-execution.md)

[View daily registrations in manufacturing execution](view-daily-registrations-in-manufacturing-execution.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

