---
title: Configure an approval step
TOCTitle: Configure an approval step
ms:assetid: 0f05c963-dd49-4e29-9e28-4854a6c46a2b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dd309592(v=AX.60)
ms:contentKeyID: 35132545
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Configure an approval step [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To configure an approval step, in the workflow editor, right-click the approval step, and then click **Properties** to open the **Properties** form. Use the following procedures to configure the properties of the approval step.

## Name the step

Follow these steps to enter a name for the approval step.

1.  In the left pane, click **Basic Settings**.

2.  In the **Name** field, enter a unique name for the approval step.

## Enter a subject line and instructions

You must provide a subject line and instructions to users who are assigned to the approval step.

For example, if you are configuring an approval step for purchase requisitions, the user who is assigned to the step sees the subject line and instructions in the **Purchase requisitions** form. The subject line appears in the message bar of the form. The user can click the icon in the message bar. The following figure shows the location of the message bar and the icon that the user clicks to view instructions.

![Workflow message bar with the Actions button](images/Dd309606.Workflow_ActionButon(AX.60).gif "Workflow message bar with the Actions button")

Follow these steps to enter a subject line and instructions.

1.  In the left pane, click **Basic Settings**.

2.  In the **Work item subject** text box, enter the subject line.

3.  To personalize the subject line, you can insert placeholders. Placeholders are replaced with the appropriate data when they are displayed to users. Follow these steps to insert a placeholder:
    
    1.  Click in the text box at the location where the placeholder should appear.
    
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

## Assign the approval step

Follow these steps to specify who you want the approval step to be assigned to.

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
    <li><p>In the <strong>Type of participant</strong> list, select the type of group or role that you want to assign the step to.</p></li>
    <li><p>In the <strong>Participant</strong> list, select the group or role that you want to assign the step to.</p></li>
    </ol></td>
    </tr>
    <tr class="even">
    <td><p><strong>Hierarchy</strong></p></td>
    <td><p>Users in a specific organizational hierarchy</p></td>
    <td><ol>
    <li><p>After you select <strong>Hierarchy</strong>, click the <strong>Hierarchy selection</strong> tab.</p></li>
    <li><p>In the <strong>Hierarchy type</strong> list, select the type of hierarchy that you want to assign the step to.</p></li>
    <li><p>The system must retrieve a range of user names from the hierarchy. These names represent users that the step may be assigned to. Follow these steps to specify the starting point and ending point of the range of user names that the system retrieves:</p>
    <ul>
    <li><p>To specify the starting point, select a person in the <strong>Start from</strong> list.</p></li>
    <li><p>To specify the ending point, click <strong>Add condition</strong>. Then enter a condition that determines where in the hierarchy the system stops retrieving names.</p></li>
    </ul></li>
    <li><p>Click the <strong>Hierarchy options</strong> tab.</p></li>
    <li><p>Specify which users in the range the step is assigned to:</p>
    <ul>
    <li><p><strong>Assign to all users retrieved</strong> – The step is assigned to all users in the range.</p></li>
    <li><p><strong>Assign only to last user retrieved</strong> – The step is assigned only to the last user in the range.</p></li>
    <li><p><strong>Exclude users with the following condition:</strong> – The step is not assigned to any users in the range who meet a specific condition. Click <strong>Add condition</strong> to specify the condition.</p></li>
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
    <li><p>The <strong>Available users:</strong> list includes all Microsoft Dynamics AX users. Select the users that you want to assign the step to, and then move these users to the <strong>Selected users:</strong> list.</p></li>
    </ol></td>
    </tr>
    </tbody>
    </table>


3.  Click the **Time limit** tab.

4.  In the **Duration** field, specify how much time the user has to act on, or respond to, documents that reach the approval step. Select one of the following options:
    
      - **Hours** – Enter the number of hours that the user has to respond. Then select the calendar that your organization uses, and enter information about your organization's work week.
    
      - **Days** – Enter the number of days that the user has to respond. Then select the calendar that your organization uses, and enter information about your organization's work week.
    
      - **Weeks** – Enter the number of weeks that the user has to respond.
    
      - **Months** – Select the day and week by which the user must respond. For example, you may want the user to respond by Friday of the third week of the month.
    
      - **Years** – Select the day, week, and month by which the user must respond. For example, you may want the user to respond by Friday of the third week of December.
    
    If the user does not act on the document in the allotted time, the document is overdue. A document that is overdue is escalated, based on the options that you select in the **Escalation** area of this form.

5.  If you assigned the approval step to multiple users, or to a group of users, click the **Completion policy** tab, and then select one of the following options:
    
    **Single approver** – The action that is applied to the document is determined by the first person who responds.
    
    For example, Sam has submitted an expense report for USD 15,000. The expense report is currently assigned to Sue, Jo, and Bill. If Sue is the first person who responds to the document, the action that she takes is applied to the document. If Sue rejects the document, it is rejected and sent back to Sam. If Sue approves the document, it is sent to Ann for approval.
    
    ![Workflow that has an approval process](images/Gg731883.Workflow_MultipleUsersInStep(AX.60).gif "Workflow that has an approval process")
    
    **Majority of approvers** – The action that is applied to the document is determined when most of the approvers respond.
    
    For example, Sam has submitted an expense report for USD 15,000. The expense report is currently assigned to Sue, Jo, and Bill. If Sue and Jo are the first two approvers who respond, the action that they take is applied to the document.
    
      - If Sue approves the document, but Jo rejects it, the document is rejected and sent back to Sam.
    
      - If both Sue and Jo approve the document, it is sent to Ann for approval.
    
    **Percentage of approvers** – The action that is applied to the document is determined when a specific percentage of the approvers respond.
    
    For example, Sam has submitted an expense report for USD 15,000. The expense report is currently assigned to Sue, Jo, and Bill, and you entered **50** as the percentage. If Sue and Jo are the first two approvers who respond, the action that they take is applied to the document because they meet the requirement for 50 percent of approvers.
    
      - If Sue approves the document, but Jo rejects it, the document is rejected and sent back to Sam.
    
      - If both Sue and Jo approve the document, it is sent to Ann for approval.
    
    **All approvers** – All the approvers must approve the document. Otherwise, the workflow cannot continue.
    
    For example, Sam has submitted an expense report for USD 15,000. The expense report is currently assigned to Sue, Jo, and Bill. If Sue and Joe approve the document, but Bill rejects it, the document is rejected and sent back to Sam. If Sue, Jo, and Bill all approve the document, it is sent to Ann for approval.

## Specify when the approval step is required

You can specify when the approval step is required. The approval step may always be required, or it may be required only if specific conditions are met.

## The approval step is always required

Follow these steps if the approval step is always required.

1.  In the left pane, click **Condition**.

2.  Select the **Always run this step** option.

## The approval step is required in specific conditions

The approval step that you are configuring may be required only if specific conditions are met. For example, if you are configuring an approval step for a purchase requisition workflow, you may want the approval step to occur only if the amount of the purchase requisition is more than USD 10,000.

Follow these steps to specify when the approval step is required.

1.  In the left pane, click **Condition**.

2.  Select the **Run this step only when the following condition is met** option.

3.  Enter a condition.

4.  Enter additional conditions, as needed.

5.  To verify that the conditions that you entered are configured correctly, complete the following steps:
    
    1.  Click **Test**. The **Test workflow condition** form is displayed.
    
    2.  Select a record in the **Validate condition** area of the form.
    
    3.  Click **Test**. The system evaluates the record to determine whether it meets the conditions that you defined.
    
    4.  Click **OK** or **Cancel** to return to the **Properties** form.

## Specify what happens when the document is overdue

If a user does not act on a document in the allotted time, the document is overdue. A document that is overdue can be escalated, or assigned automatically to another user for approval. Follow these steps to escalate the document if it is overdue.

1.  In the left pane, click **Escalation**.

2.  Select the **Use escalation path** check box to create an escalation path. The system automatically assigns the document to the users who are listed in the escalation path.
    
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
    
    In this example, the system assigns the overdue document to Donna. If Donna does not respond in the allotted time, the system assigns the document to Erin. If Erin does not respond in the allotted time, the system rejects the document.

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
    <th><p>Users that the document is escalated to</p></th>
    <th><p>Additional steps</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Hierarchy</strong></p></td>
    <td><p>Users in a specific organizational hierarchy</p></td>
    <td><ol>
    <li><p>After you select <strong>Hierarchy</strong>, click the <strong>Hierarchy selection</strong> tab.</p></li>
    <li><p>In the <strong>Hierarchy type</strong> list, select the type of hierarchy to escalate the document to.</p></li>
    <li><p>The system must retrieve a range of user names from the hierarchy. These names represent users that the document may be escalated to. Follow these steps to specify the starting point and ending point of the range of user names that the system retrieves:</p>
    <ul>
    <li><p>To specify the starting point, select a person in the <strong>Start from</strong> list.</p></li>
    <li><p>To specify the ending point, click <strong>Add condition</strong>. Then enter a condition that determines where in the hierarchy the system stops retrieving names.</p></li>
    </ul></li>
    <li><p>Click the <strong>Hierarchy options</strong> tab.</p></li>
    <li><p>Specify which users in the range the document is escalated to:</p>
    <ul>
    <li><p><strong>Assign to all users retrieved</strong> – The document is escalated to all users in the range.</p></li>
    <li><p><strong>Assign only to last user retrieved</strong> – The document is escalated only to the last user in the range.</p></li>
    <li><p><strong>Exclude users with the following condition:</strong> – The document is not escalated to any users in the range who meet a specific condition. Click <strong>Add condition</strong> to specify the condition.</p></li>
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
    <li><p>The <strong>Available users:</strong> list includes all Microsoft Dynamics AX users. Select the users to escalate the document to, and then move these users to the <strong>Selected users:</strong> list.</p></li>
    </ol></td>
    </tr>
    </tbody>
    </table>


4.  Click the **Time limit** tab.

5.  In the **Duration** field, specify how much time the user has to act on, or respond to, documents. Select one of the following options:
    
      - **Hours** – Enter the number of hours that the user has to respond. Then select the calendar that your organization uses, and enter information about your organization's work week.
    
      - **Days** – Enter the number of days that the user has to respond. Then select the calendar that your organization uses, and enter information about your organization's work week.
    
      - **Weeks** – Enter the number of weeks that the user has to respond.
    
      - **Months** – Select the day and week by which the user must respond. For example, you may want the user to respond by Friday of the third week of the month.
    
      - **Years** – Select the day, week, and month by which the user must respond. For example, you may want the user to respond by Friday of the third week of December.

6.  Repeat steps 3 through 5 for each user to add to the escalation path. You can change the order of the users.

7.  If the users in the escalation path do not respond in the allotted time, the system automatically acts on the document. To specify the action that the system takes, select the **Action** row. Then select an action on the **End action** tab.

## See also

[About the workflow editor](about-the-workflow-editor.md)

[Create a workflow](create-a-workflow.md)

[Configure the properties of a workflow](configure-the-properties-of-a-workflow.md)

[Configure workflow elements](configure-workflow-elements.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

