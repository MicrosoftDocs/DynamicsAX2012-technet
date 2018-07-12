---
title: Configure a manual task
TOCTitle: Configure a manual task
ms:assetid: 1798c3e0-9c83-49a1-b2dd-2a23fb77d88c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dd309606(v=AX.60)
ms:contentKeyID: 35132560
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Configure a manual task 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To configure a manual task, in the workflow editor, right-click the task, and then click **Properties** to open the **Properties** form. Use the following procedures to configure the properties for the manual task.

## Name the task

Follow these steps to enter a name for the manual task.

1.  In the left pane, click **Basic Settings**.

2.  In the **Name** field, enter a unique name for the task.

## Enter a subject line and instructions

You must provide a subject line and instructions to users who are assigned to the task.

For example, if you are configuring a task for purchase requisitions, the user who is assigned to the task sees the subject line and instructions in the **Purchase requisitions** form. The subject line appears in the message bar of the form. The user can click the icon in the message bar to view the instructions. The following figure shows the location of the message bar and the icon that the user clicks to view instructions.

![Workflow message bar with the Actions button](images/Dd309606.Workflow_ActionButon(AX.60).gif "Workflow message bar with the Actions button")

Follow these steps to enter a subject line and instructions.

1.  In the left pane, click **Basic Settings**.

2.  In the **Work item subject** text box, enter the subject line.

3.  To personalize the subject line, you can insert placeholders. Placeholders are replaced with the appropriate data when they are displayed to users.
    
    1.  Click in the text box at the location where you want the placeholder to appear.
    
    2.  Click **Insert placeholder**.
    
    3.  In the list that is displayed, select the placeholder to insert.
    
    4.  Click **Insert**.

4.  To add translations of the subject line, click **Translations**. In the form that is displayed, follow these steps:
    
    1.  Click **Add**.
    
    2.  In the list that is displayed, select the language in which you will enter the text.
    
    3.  In the **Translated text** text box, enter the text.
    
    4.  To personalize the text, insert placeholders.
    
    5.  Click **Close**.

5.  In the **Work item instructions** text box, enter the instructions.

6.  To personalize the instructions, you can insert placeholders. Placeholders are replaced with the appropriate data when they are displayed to users. Follow these steps to insert a placeholder:
    
    1.  Click in the text box at the location where the placeholder should appear.
    
    2.  Click **Insert placeholder**.
    
    3.  In the list that is displayed, select the placeholder to insert.
    
    4.  Click **Insert**.

7.  To add translations of the instructions, click **Translations**. In the form that is displayed, follow these steps:
    
    1.  Click **Add**.
    
    2.  In the list that is displayed, select the language in which you will enter the text.
    
    3.  In the **Translated text** text box, enter the text.
    
    4.  To personalize the text, insert placeholders.
    
    5.  Click **Close**.

## Assign the task

Follow these steps to specify who the manual task should be assigned to.

1.  In the left pane, click **Assignment**.

2.  On the **Assignment type** tab, select one of the options in the following table, and then follow the additional steps for the option before you go to step 3.
    
    <table>
    <colgroup>
    <col style="width: 33%" />
    <col style="width: 33%" />
    <col style="width: 33%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Option</p></th>
    <th><p>Task is assigned to</p></th>
    <th><p>Additional steps</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Participant</strong></p></td>
    <td><p>Users who are assigned to a specific group or role</p></td>
    <td><ol>
    <li><p>After you select <strong>Participant</strong>, click the <strong>Role based</strong> tab.</p></li>
    <li><p>In the <strong>Type of participant</strong> list, select the type of group or role to assign the task to.</p></li>
    <li><p>In the <strong>Participant</strong> list, select the group or role to assign the task to.</p></li>
    </ol></td>
    </tr>
    <tr class="even">
    <td><p><strong>Hierarchy</strong></p></td>
    <td><p>Users in a specific organizational hierarchy</p></td>
    <td><ol>
    <li><p>After you select <strong>Hierarchy</strong>, click the <strong>Hierarchy selection</strong> tab.</p></li>
    <li><p>In the <strong>Hierarchy type</strong> list, select the type of hierarchy to assign the task to.</p></li>
    <li><p>The system must retrieve a range of user names from the hierarchy. These names represent users who the task may be assigned to. Follow these steps to specify the starting point and ending point of the range of user names that the system retrieves:</p>
    <ul>
    <li><p>To specify the starting point, select a person in the <strong>Start from</strong> list.</p></li>
    <li><p>To specify the ending point, click <strong>Add condition</strong>. Then enter a condition that determines where in the hierarchy the system stops retrieving names.</p></li>
    </ul></li>
    <li><p>Click the <strong>Hierarchy options</strong> tab.</p></li>
    <li><p>Specify which users in the range the task is assigned to:</p>
    <ul>
    <li><p><strong>Assign to all users retrieved</strong> – The task is assigned to all users in the range.</p></li>
    <li><p><strong>Assign only to last user retrieved</strong> – The task is assigned only to the last user in the range.</p></li>
    <li><p><strong>Exclude users with the following condition:</strong> – The task is not assigned to any users in the range who meet a specific condition. Click <strong>Add condition</strong> to specify the condition.</p></li>
    </ul></li>
    </ol></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Workflow user</strong></p></td>
    <td><p>Users in the current workflow</p></td>
    <td><ol>
    <li><p>After you select <strong>Workflow user</strong>, click the <strong>Workflow user</strong> tab.</p></li>
    <li><p>In the <strong>Workflow user</strong> list, select a user who participates in the workflow.</p></li>
    </ol></td>
    </tr>
    <tr class="even">
    <td><p><strong>User</strong></p></td>
    <td><p>Specific Microsoft Dynamics AX users</p></td>
    <td><ol>
    <li><p>After you select <strong>User</strong>, click the <strong>User</strong> tab.</p></li>
    <li><p>The <strong>Available users:</strong> list includes all Microsoft Dynamics AX users. Select the users to assign the task to, and then move these users to the <strong>Selected users:</strong> list.</p></li>
    </ol></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Queue</strong></p></td>
    <td><p>A work item queue</p></td>
    <td><ol>
    <li><p>After you select <strong>Queue</strong>, click the <strong>Queue based</strong> tab.</p></li>
    <li><p>To assign the task to a specific queue, follow these steps:</p>
    <ul>
    <li><p>In the <strong>Queue type</strong> list, select <strong>Work item queues</strong>.</p></li>
    <li><p>In the <strong>Queue name</strong> list, select the queue.</p></li>
    </ul></li>
    <li><p>If a specific condition should determine which queue the task is assigned to, follow these steps:</p>
    <ul>
    <li><p>In the <strong>Queue type</strong> list, select <strong>Conditional work item queues</strong>.</p></li>
    <li><p>In the <strong>Queue name</strong> list, select <strong>Conditional queue</strong>.</p></li>
    </ul></li>
    </ol></td>
    </tr>
    </tbody>
    </table>


3.  Click the **Time limit** tab.

4.  In the **Duration** field, specify how much time the user has to complete the task. Select one of the following options:
    
      - **Hours** – Enter the number of hours that the user has to complete the task. Then select the calendar that your organization uses, and enter information about your organization's work week.
    
      - **Days** – Enter the number of days that the user has to complete the task. Then select the calendar that your organization uses, and enter information about your organization's work week.
    
      - **Weeks** – Enter the number of weeks that the user has to complete the task.
    
      - **Months** – Select the day and week by which the user must complete the task. For example, you may want the user to complete the task by Friday of the third week of the month.
    
      - **Years** – Select the day, week, and month by which the user must complete the task. For example, you may want the user to complete the task by Friday of the third week of December.
    
    If the user does not complete the task in the allotted time, the task is overdue. A task that is overdue can be escalated, based on the options that you select in the **Escalation** area of this form.

## Specify what happens when the task is overdue

If a user does not complete the manual task in the allotted time, the task is overdue. A task that is overdue can be escalated, or assigned automatically to another user. Follow these steps to escalate the task if it is overdue.

1.  In the left pane, click **Escalation**.

2.  Select the **Use escalation path** check box to create an escalation path. The system automatically assigns the task to the users who are listed in the escalation path.
    
    For example, the following table represents an escalation path.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Sequence</p></th>
    <th><p>Escalation path</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>1</p></td>
    <td><p>Assign to: Donna</p></td>
    </tr>
    <tr class="even">
    <td><p>2</p></td>
    <td><p>Assign to: Erin</p></td>
    </tr>
    <tr class="odd">
    <td><p>3</p></td>
    <td><p>Final action: Reject</p></td>
    </tr>
    </tbody>
    </table>
    
    In this example, the system assigns the overdue task to Donna. If Donna does not complete the task in the allotted time, the system assigns the task to Erin. If Erin does not complete the task in the allotted time, the system rejects the document that was submitted for processing.

3.  To add a user to the escalation path, click **Add escalation**. Click the **Assignment type** tab, select one of the options in the following table, and then follow the additional steps for the option before you go to step 4.
    
    <table>
    <colgroup>
    <col style="width: 33%" />
    <col style="width: 33%" />
    <col style="width: 33%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Option</p></th>
    <th><p>Users that the task is escalated to</p></th>
    <th><p>Additional steps</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Hierarchy</strong></p></td>
    <td><p>Users in a specific organizational hierarchy</p></td>
    <td><ol>
    <li><p>After you select <strong>Hierarchy</strong>, click the <strong>Hierarchy selection</strong> tab.</p></li>
    <li><p>In the <strong>Hierarchy type</strong> list, select the type of hierarchy to escalate the task to.</p></li>
    <li><p>The system must retrieve a range of user names from the hierarchy. These names represent users who the task may be escalated to. Follow these steps to specify the starting point and ending point of the range of user names that the system retrieves:</p>
    <ul>
    <li><p>To specify the starting point, select a person in the <strong>Start from</strong> list.</p></li>
    <li><p>To specify the ending point, click <strong>Add condition</strong>. Then enter a condition that determines where in the hierarchy the system stops retrieving names.</p></li>
    </ul></li>
    <li><p>Click the <strong>Hierarchy options</strong> tab.</p></li>
    <li><p>Specify which users in the range that the task is escalated to:</p>
    <ul>
    <li><p><strong>Assign to all users retrieved</strong> – The task is escalated to all users in the range.</p></li>
    <li><p><strong>Assign only to last user retrieved</strong> – The task is escalated only to the last user in the range.</p></li>
    <li><p><strong>Exclude users with the following condition:</strong> – This task is not escalated to any users in the range who meet a specific condition. Click <strong>Add condition</strong> to specify the condition.</p></li>
    </ul></li>
    </ol></td>
    </tr>
    <tr class="even">
    <td><p><strong>Workflow user</strong></p></td>
    <td><p>Users in the current workflow</p></td>
    <td><ol>
    <li><p>After you select <strong>Workflow user</strong>, click the <strong>Workflow user</strong> tab.</p></li>
    <li><p>In the <strong>Workflow user</strong> list, select a user who participates in the workflow.</p></li>
    </ol></td>
    </tr>
    <tr class="odd">
    <td><p><strong>User</strong></p></td>
    <td><p>Specific Microsoft Dynamics AX users</p></td>
    <td><ol>
    <li><p>After you select <strong>User</strong>, click the <strong>User</strong> tab.</p></li>
    <li><p>The <strong>Available users:</strong> list includes all Microsoft Dynamics AX users. Select the users to escalate the task to, and then move these users to the <strong>Selected users:</strong> list.</p></li>
    </ol></td>
    </tr>
    </tbody>
    </table>


4.  Click the **Time limit** tab.

5.  In the **Duration** field, specify how much time the user has to complete the task. Select one of the following options:
    
      - **Hours** – Enter the number of hours that the user has to complete the task. Then select the calendar that your organization uses, and enter information about your organization's work week.
    
      - **Days** – Enter the number of days that the user has to complete the task. Then select the calendar that your organization uses, and enter information about your organization's work week.
    
      - **Weeks** – Enter the number of weeks that the user has to complete the task.
    
      - **Months** – Select the day and week by which the user must complete the task. For example, you may want the user to complete the task by Friday of the third week of the month.
    
      - **Years** – Select the day, week, and month by which the user must complete the task. For example, you may want the user to complete the task by Friday of the third week of December.

6.  Repeat steps 3 through 5 for each user to add to the escalation path. You can change the order of the users.

7.  If the users in the escalation path do not complete the task in the allotted time, the system acts on the task. To specify the action that the system takes, select the **Action** row. Then select an action on the **End action** tab.

## Specify when the system automatically acts on the task

You can configure the system to act on the manual task if specific conditions are met.

For example, a task requires that a member of the Expense Reports department review the receipts that are submitted together with an expense report. According to company policy, this task must be performed when the total amount of the expense report is more than USD 100. In this scenario, you can configure the system to automatically mark the task as **Complete** when *total amount \< 100*.

Follow these steps to specify when the system acts on the manual task.

1.  In the left pane, click **Automatic actions**.

2.  Select the **Enable automatic actions** check box.

3.  Click **Add condition**.

4.  Enter a condition.

5.  Enter additional conditions, if they are needed.

6.  To verify that the conditions that you entered are configured correctly, complete the following steps:
    
    1.  Click **Test**. The **Test workflow condition** form is displayed.
    
    2.  Select a record in the **Validate condition** area of the form.
    
    3.  Click **Test**. The system evaluates the record to determine whether it meets the conditions that you defined.
    
    4.  Click **OK** or **Cancel** to return to the **Properties** form.

7.  In the **Auto complete action** list, select the action that the system should take on the task.

## Specify when notifications are sent

You can send notifications to people when a manual task has been delegated, escalated, completed, or rejected, or when a change has been requested.

Follow these steps to specify when notifications are sent, and who the notifications are sent to.

1.  In the left pane, click **Notifications**.

2.  Select the check box next to the events that notifications should be sent for:
    
      - **Delegate** –When the task has been assigned to another user.
    
      - **Escalate** –When the assigned user has not completed the task in the allotted time.
    
      - **Complete** – When the assigned user has completed the task.
    
      - **Reject** –When the assigned user has rejected the document that was submitted.
    
      - **Request change** – When the assigned user has requested a change to the document that was submitted.

3.  Select the row for an event that you selected in step 2.

4.  Click the **Notification text** tab.

5.  In the text box, enter the text of the notification.

6.  To personalize the notification, you can insert placeholders. Placeholders are replaced with the appropriate information when they are displayed to users. Follow these steps to insert a placeholder:
    
    1.  Click in the text box at the location where the placeholder should appear.
    
    2.  Click **Insert placeholder**.
    
    3.  In the list that is displayed, select the placeholder to insert.
    
    4.  Click **Insert**.

7.  To add translations of the notification, click **Translations**. In the form that is displayed, follow these steps:
    
    1.  Click **Add**.
    
    2.  In the list that is displayed, select the language in which you will enter the text.
    
    3.  In the **Translated text** text box, enter the text.
    
    4.  To personalize the text, insert placeholders.
    
    5.  Click **Close**.

8.  Click the **Recipient** tab.

9.  Specify who the notifications are sent to. Select one of the options in the following table, and then follow the additional steps for the option before you go to step 10.
    
    <table>
    <colgroup>
    <col style="width: 33%" />
    <col style="width: 33%" />
    <col style="width: 33%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Option</p></th>
    <th><p>Notification recipients</p></th>
    <th><p>Additional steps</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Participant</strong></p></td>
    <td><p>Users who are assigned to a specific group or role</p></td>
    <td><ol>
    <li><p>After you select <strong>Participant</strong>, click the <strong>Role based</strong> tab.</p></li>
    <li><p>In the <strong>Type of participant</strong> list, select the type of group or role you want to send notifications to.</p></li>
    <li><p>In the <strong>Participant</strong> list, select the group or role to send notifications to.</p></li>
    </ol></td>
    </tr>
    <tr class="even">
    <td><p><strong>Workflow user</strong></p></td>
    <td><p>Users in the current workflow</p></td>
    <td><ol>
    <li><p>After you select <strong>Workflow user</strong>, click the <strong>Workflow user</strong> tab.</p></li>
    <li><p>In the <strong>Workflow user</strong> list, select a user who participates in the workflow.</p></li>
    </ol></td>
    </tr>
    <tr class="odd">
    <td><p><strong>User</strong></p></td>
    <td><p>Specific Microsoft Dynamics AX users</p></td>
    <td><ol>
    <li><p>After you select <strong>User</strong>, click the <strong>User</strong> tab.</p></li>
    <li><p>The <strong>Available users:</strong> list includes all Microsoft Dynamics AX users. Select the users to send notifications to, and then move these users to the <strong>Selected users:</strong> list.</p></li>
    </ol></td>
    </tr>
    </tbody>
    </table>


10. Repeat steps 3 through 9 for each event that you selected in step 2.

## Set a time limit

Follow these steps if the manual task must be completed in a specific time.


> [!NOTE]
> <P>The options that you select in these steps override the options that you selected in the <STRONG>Assignment</STRONG> and <STRONG>Escalation</STRONG> areas of this form.</P>



1.  In the left pane, click **Advanced settings**.

2.  Select the **Set a time limit for the workflow element** check box.

3.  In the **Duration** field, specify when the task must be completed. Select one of the following options:
    
      - **Hours** – Enter the number of hours in which the task must be completed. Then select the calendar that your organization uses, and enter information about your organization's work week.
    
      - **Days** – Enter the number of days in which the task must be completed. Then select the calendar that your organization uses, and enter information about your organization's work week.
    
      - **Weeks** – Enter the number of weeks in which the task must be completed.
    
      - **Months** – Select the day and week by which the task must be completed. For example, you may want the task completed by Friday of the third week of the month.
    
      - **Years** – Select the day, week, and month by which the task must be completed. For example, you may want the task completed by Friday of the third week of December.

4.  If the time limit is exceeded, the system acts on the task. In the **Action** list, select the action that the system should take.

## Specify which actions are available to the user

When the manual task is assigned to a user, the user must act on the task. Follow these steps to specify which actions the user can take on the task.


> [!NOTE]
> <P>The actions available will vary, depending on how the task is designed.</P>



1.  In the left pane, click **Advanced settings**.

2.  Select the **Complete** check box if the user should be able to mark the task as **Complete**.

3.  Select the **Reject** check box if the user should be able to reject the document that was submitted.

4.  Select the **Request change** check box if the user should be able to request changes to the document that was submitted.

5.  Select the **Delegate** check box if the user should be able to assign the task to another user.

6.  Select the **Reassign** check box if the user should be able to reassign the task to another user in the work item queue.

7.  Select the **Release** check box if the user should be able to reassign the task to the work item queue. Another user can then complete the task.

## Specify whether users can act on the task from the work list in Enterprise Portal

By default, users can act on tasks from the **Work list** Web part in Enterprise Portal for Microsoft Dynamics AX. However, there may be cases where you do not want users to be able to act on tasks from this Web part. For example, you might require that users open the documents and act on the tasks from the documents themselves.

Follow these steps to specify whether users can act on the manual task from the **Work list** Web part in Enterprise Portal.

1.  In the left pane, click **Advanced settings**.

2.  To allow users to act on the task from the **Work list** Web part in Enterprise Portal, select the **Enable actions from the work list in Enterprise Portal** check box.

3.  To prevent users from acting on the task from the **Work list** Web part in Enterprise Portal, clear the **Enable actions from the work list in Enterprise Portal** check box.

  


