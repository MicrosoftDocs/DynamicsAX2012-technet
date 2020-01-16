---
title: Configure a manual decision
TOCTitle: Configure a manual decision
ms:assetid: c0479554-b42c-43d3-919b-8811ad0c7acf
ms:mtpsurl: https://technet.microsoft.com/library/Gg731919(v=AX.60)
ms:contentKeyID: 35132847
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Configure a manual decision 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To configure a manual decision, in the workflow editor, right-click the manual decision and then click **Properties** to open the **Properties** form. Use the following procedures to configure the properties of the manual decision.

## Name the decision

Follow these steps to enter a name for the manual decision.

1.  In the left pane, click **Basic Settings**.

2.  In the **Name** field, enter a unique name for the manual decision.

## Enter a subject line and instructions

You must provide a subject line and instructions to users who are assigned to the manual decision.

For example, if you are configuring a decision for purchase requisitions, the user who is assigned to the decision sees the subject line and instructions in the **Purchase requisitions** form. The subject line appears in the message bar of the form. The user can click the icon in the message bar to view the instructions. The following figure shows the location of the message bar and the icon that the user clicks to view instructions.

![Workflow message bar with the Actions button](images/Dd309606.Workflow_ActionButon(AX.60).gif "Workflow message bar with the Actions button")

Follow these steps to enter a subject line and instructions.

1.  In the left pane, click **Basic Settings**.

2.  Click the **Instructions:** tab.

3.  In the **Work item subject** text box, enter the subject line.

4.  To personalize the subject line, you can insert placeholders, which are replaced with the appropriate data when they are displayed to users. Follow these steps to insert a placeholder:
    
    1.  Click in the text box at the location where the placeholder should appear.
    
    2.  Click **Insert placeholder**.
    
    3.  In the list that is displayed, select the placeholder to insert.
    
    4.  Click **Insert**.

5.  To add translations of the subject line, click **Translations**. In the form that appears, follow these steps:
    
    1.  Click **Add**.
    
    2.  In the list that is displayed, select the language in which you will enter the text.
    
    3.  In the **Translated text** text box, enter the text.
    
    4.  To personalize the text, insert placeholders.
    
    5.  Click **Close**.

6.  In the **Work item instructions** text box, enter the instructions.

7.  To personalize the instructions, you can insert placeholders, which are replaced with the appropriate data when they are displayed to users. Follow these steps to insert a placeholder:
    
    1.  Click in the text box at the location where you want the placeholder to appear.
    
    2.  Click **Insert placeholder**.
    
    3.  In the list that is displayed, select the placeholder to insert.
    
    4.  Click **Insert**.

8.  To add translations of the instructions, click **Translations**. In the form that is displayed, follow these steps:
    
    1.  Click **Add**.
    
    2.  In the list that is displayed, select the language in which you will enter the text.
    
    3.  In the **Translated text** text box, enter the text.
    
    4.  To personalize the text, insert placeholders.
    
    5.  Click **Close**.

## Specify the possible outcomes of a decision

When a document is assigned to a decision maker, the decision maker is typically asked a question. The answer to the question is typically **Yes** or **No**, or **True** or **False**.

Follow these steps to specify the possible outcomes of the manual decision.

1.  In the left pane, click **Basic Settings**.

2.  Click the **Outcomes** tab.

3.  In the **Outcome 1** field, enter the name of the outcome, or the option.

4.  To add translations of the outcome, click **Translations**. In the form that is displayed, follow these steps:
    
    1.  Click **Add**.
    
    2.  In the list that is displayed, select the language in which you will enter the text.
    
    3.  In the **Translated text** text box, enter the text.
    
    4.  Click **Close**.

5.  In the **Outcome 2** field, enter the name of the outcome, or the option.

6.  To add translations of the outcome, click **Translations**. In the form that is displayed, follow these steps:
    
    1.  Click **Add**.
    
    2.  In the list that is displayed, select the language in which you will enter the text.
    
    3.  In the **Translated text** text box, enter the text.
    
    4.  Click **Close**.

## Specify when notifications are sent

You can send notifications to people when a decision has been made, delegated, or escalated.

Follow these steps to specify when notifications are sent, and who the notifications are sent to.

1.  In the left pane, click **Notifications**.

2.  Select the check box next to the events that notifications should be sent for:
    
      - **\[Choice 1\]** – When the assigned user has selected **\[Choice 1\]**.
    
      - **\[Choice 2\]** – When the assigned user has selected **\[Choice 2\]**.
    
      - **Delegate** – When the assigned user has assigned the decision to another user.
    
      - **Escalate** – When the assigned user has not made the decision in the allotted time.

3.  Select the row for an event that you selected in step 2.

4.  Click the **Notification text** tab.

5.  In the text box, enter the text of the notification.

6.  To personalize the notification, you can insert placeholders, which are replaced with the appropriate data when they are displayed to users. Follow these steps to insert a placeholder:
    
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
    <li><p>In the <strong>Type of participant</strong> list, select the type of group or role to send notifications to.</p></li>
    <li><p>In the <strong>Participant</strong> list, select the group or to send notifications to.</p></li>
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

## Assign a decision

Follow these steps to specify who a manual decision should be assigned to.

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
    <th><p>Assigned users</p></th>
    <th><p>Additional steps</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Participant</strong></p></td>
    <td><p>Users who are assigned to a specific group or role</p></td>
    <td><ol>
    <li><p>After you select <strong>Participant</strong>, click the <strong>Role based</strong> tab.</p></li>
    <li><p>In the <strong>Type of participant</strong> list, select the type of group or role to assign the decision to.</p></li>
    <li><p>In the <strong>Participant</strong> list, select the group or role to assign the decision to.</p></li>
    </ol></td>
    </tr>
    <tr class="even">
    <td><p><strong>Hierarchy</strong></p></td>
    <td><p>Users in a specific organizational hierarchy</p></td>
    <td><ol>
    <li><p>After you select <strong>Hierarchy</strong>, click the <strong>Hierarchy selection</strong> tab.</p></li>
    <li><p>In the <strong>Hierarchy type</strong> list, select the type of hierarchy to assign the decision to.</p></li>
    <li><p>The system must retrieve a range of user names from the hierarchy. These names represent users that the decision may be assigned to. Follow these steps to specify the starting point and ending point of the range of user names that the system retrieves:</p>
    <ul>
    <li><p>To specify the starting point, select a person in the <strong>Start from</strong> list.</p></li>
    <li><p>To specify the ending point, click <strong>Add condition</strong>. Then enter a condition that determines where in the hierarchy the system stops retrieving names.</p></li>
    </ul></li>
    <li><p>Click the <strong>Hierarchy options</strong> tab.</p></li>
    <li><p>Specify which users in the range the decision is assigned to:</p>
    <ul>
    <li><p><strong>Assign to all users retrieved</strong> – The decision is assigned to all users in the range.</p></li>
    <li><p><strong>Assign only to last user retrieved</strong> – The decision is assigned only to the last user in the range.</p></li>
    <li><p><strong>Exclude users with the following condition:</strong> – The decision is not assigned to any users in the range who meet a specific condition. Click <strong>Add condition</strong> to specify the condition.</p></li>
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
    <li><p>The <strong>Available users:</strong> list includes all Microsoft Dynamics AX users. Select the users to assign the decision to, and then move these users to the <strong>Selected users:</strong> list.</p></li>
    </ol></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Queue</strong></p></td>
    <td><p>A work item queue</p></td>
    <td><ol>
    <li><p>After you select <strong>Queue</strong>, click the <strong>Queue based</strong> tab.</p></li>
    <li><p>To assign the decision to a specific queue, follow these steps:</p>
    <ul>
    <li><p>In the <strong>Queue type</strong> list, select <strong>Work item queues</strong>.</p></li>
    <li><p>In the <strong>Queue name</strong> list, select the queue.</p></li>
    </ul></li>
    <li><p>If a specific condition should determine which queue the decision is assigned to, follow these steps:</p>
    <ul>
    <li><p>In the <strong>Queue type</strong> list, select <strong>Conditional work item queues</strong>.</p></li>
    <li><p>In the <strong>Queue name</strong> list, select <strong>Conditional queue</strong>.</p></li>
    </ul></li>
    </ol></td>
    </tr>
    </tbody>
    </table>


3.  Click the **Time limit** tab.

4.  In the **Duration** field, specify how much time the user has to make the decision. Select one of the following options:
    
      - **Hours** – Enter the number of hours that the user has to make the decision. Then select the calendar that your organization uses, and enter information about your organization's work week.
    
      - **Days** – Enter the number of days that the user has to make the decision. Then select the calendar that your organization uses, and enter information about your organization's work week.
    
      - **Weeks** – Enter the number of weeks that the user has to make the decision.
    
      - **Months** – Select the day and week by which the user must make the decision. For example, you may want the user to make the decision by Friday of the third week of the month.
    
      - **Years** – Select the day, week, and month by which the user must make the decision. For example, you may want the user to make the decision by Friday of the third week of December.
    
    If the user does not make the decision in the allotted time, the decision is overdue. A decision that is overdue is escalated, based on the options that you select in the **Escalation** area of this form.

## Specify what happens when a decision is overdue

If a user does not make the decision in the allotted time, the decision is overdue and can be escalated, or assigned to another user. Follow these steps to escalate the decision if it is overdue.

1.  In the left pane, click **Escalation**.

2.  Select the **Use escalation path** check box to create an escalation path. The system assigns the decision to the users who are listed in the escalation path.
    
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
    <td><p>Final action: [Choice 1]</p></td>
    </tr>
    </tbody>
    </table>
    
    In this example, the system assigns the overdue decision to Donna. If Donna does not make the decision in the allotted time, the system assigns the decision to Erin. If Erin does not make the decision in the allotted time, the system selects **\[Choice 1\]** as the decision.

3.  To add a user to the escalation path, click **Add escalation**. Select one of the options in the following table, and then follow the additional steps for the option before you go to step 4.
    
    <table>
    <colgroup>
    <col style="width: 33%" />
    <col style="width: 33%" />
    <col style="width: 33%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Option</p></th>
    <th><p>Users that the decision is escalated to</p></th>
    <th><p>Additional steps</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Hierarchy</strong></p></td>
    <td><p>Users in a specific organizational hierarchy</p></td>
    <td><ol>
    <li><p>After you select <strong>Hierarchy</strong>, click the <strong>Hierarchy selection</strong> tab.</p></li>
    <li><p>In the <strong>Hierarchy type</strong> list, select the type of hierarchy to escalate the decision to.</p></li>
    <li><p>The system must retrieve a range of user names from the hierarchy. These names represent users that the decision may be escalated to. Follow these steps to specify the starting point and ending point of the range of user names that the system retrieves:</p>
    <ul>
    <li><p>To specify the starting point, select a person in the <strong>Start from</strong> list.</p></li>
    <li><p>To specify the ending point, click <strong>Add condition</strong>. Then enter a condition that determines where in the hierarchy the system stops retrieving names.</p></li>
    </ul></li>
    <li><p>Click the <strong>Hierarchy options</strong> tab.</p></li>
    <li><p>Specify which users in the range the decision is escalated to:</p>
    <ul>
    <li><p><strong>Assign to all users retrieved</strong> – The decision is escalated to all users in the range.</p></li>
    <li><p><strong>Assign only to last user retrieved</strong> – The decision is escalated only to the last user in the range.</p></li>
    <li><p><strong>Exclude users with the following condition:</strong> – The decision is not escalated to any users in the range who meet a specific condition. Click <strong>Add condition</strong> to specify the condition.</p></li>
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
    <li><p>The <strong>Available users:</strong> list includes all Microsoft Dynamics AX users. Select the users to escalate the decision to, and then move these users to the <strong>Selected users:</strong> list.</p></li>
    </ol></td>
    </tr>
    </tbody>
    </table>


4.  Click the **Time limit** tab.

5.  In the **Duration** field, specify how much time the user has to make the decision. Select one of the following options:
    
      - **Hours** – Enter the number of hours that the user has to make the decision. Then select the calendar that your organization uses, and enter information about your organization's work week.
    
      - **Days** – Enter the number of days that the user has to make the decision. Then select the calendar that your organization uses, and enter information about your organization's work week.
    
      - **Weeks** – Enter the number of weeks that the user has to make the decision.
    
      - **Months** – Select the day and week by which the user must make the decision. For example, you may want the user to make the decision by Friday of the third week of the month.
    
      - **Years** – Select the day, week, and month by which the user must make the decision. For example, you may want the user to make the decision by Friday of the third week of December.

6.  Repeat steps 3 through 5 for each user to add to the escalation path. You can change the order of the users.

7.  If the users in the escalation path do not make the decision in the allotted time, the system makes the decision. To specify the option that the system selects, select the **Action** row. Then select the option on the **End action** tab.

## Set a time limit

Follow these steps if the decision must be made in a specific time.


> [!NOTE]
> <P>The options that you select in these steps override the options that you selected in the <STRONG>Assignment</STRONG> and <STRONG>Escalation</STRONG> areas of this form.</P>



1.  In the left pane, click **Advanced settings**.

2.  Select the **Set a time limit for the workflow element** check box.

3.  In the **Duration** field, specify when the decision must be made. Select one of the following options:
    
      - **Hours** – Enter the number of hours. Then select the calendar that your organization uses, and enter information about your organization's work week.
    
      - **Days** – Enter the number of days. Then select the calendar that your organization uses, and enter information about your organization's work week.
    
      - **Weeks** – Enter the number of weeks.
    
      - **Months** – Select the day and week by which the decision must be made. For example, you may want the decision made by Friday of the third week of the month.
    
      - **Years** – Select the day, week, and month by which the decision must be made. For example, you may want the decision made by Friday of the third week of December.

4.  If the time limit is exceeded, the system makes the decision. In the **Action** list, select the option that the system should select.

## See also

[About the workflow editor](about-the-workflow-editor.md)

[Create a workflow](create-a-workflow.md)

[Configure the properties of a workflow](configure-the-properties-of-a-workflow.md)

[Configure workflow elements](configure-workflow-elements.md)

  


