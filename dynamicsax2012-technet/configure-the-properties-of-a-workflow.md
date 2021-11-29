---
title: Configure the properties of a workflow
TOCTitle: Configure the properties of a workflow
ms:assetid: d1f7d42a-47fe-41d4-9130-94d287df7535
ms:mtpsurl: https://technet.microsoft.com/library/Gg188988(v=AX.60)
ms:contentKeyID: 35410568
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- workflow
audience: Application User
ms.search.region: Global
---

# Configure the properties of a workflow 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To configure the properties of a workflow, open the workflow in the workflow editor. Click the canvas of the workflow editor and then click **Properties** to open the **Properties** form. Use the following procedures to configure the properties of the workflow.

## Name the workflow

Follow these steps to enter a name for the workflow.

1.  In the left pane, click **Basic Settings**.

2.  In the **Name** field, enter a unique name for the workflow.
    
    For example, if you create purchase requisition workflows for each country or region in which you operate, you can name a purchase requisition workflow *Purchase Requisitions Denmark* or *Purchase Requisitions Spain*.

## Specify the workflow owner

The workflow owner is the person who manages and maintains this workflow. Follow these steps to specify the workflow owner.

1.  In the left pane, click **Basic Settings**.

2.  From the **Owner** list, select the name of the person who will manage this workflow.

## Select an email template

Follow these steps to select the email template that will be used to generate notification messages regarding this workflow.

1.  In the left pane, click **Basic Settings**.

2.  From the **Email template for workflow notifications** list, select the template.

## Enter instructions for users

You can provide instructions to users who submit documents for processing and approval. This documentation refers to these users as originators.

For example, suppose that you are creating a purchase requisition workflow. The instructions that you provide can be viewed by users entering purchase requisitions in the **Purchase requisitions** form.

To view instructions, the originator clicks the icon in the workflow message bar. The following figure shows the location of the workflow message bar and the icon that originators click to view instructions.

![Workflow message bar with the Submit button](images/Gg188988.Workflow_SubmitButton(AX.60).gif "Workflow message bar with the Submit button")

Follow these steps to enter instructions for users.

1.  In the left pane, click **Basic Settings**.

2.  In the **Submission instructions** text box, enter the instructions.

3.  To personalize the instructions, you can insert placeholders, which are replaced with the appropriate data when they are displayed to users. To insert a placeholder, follow these steps:
    
    1.  Click in the text box to specify where the placeholder should appear.
    
    2.  Click **Insert placeholder**.
    
    3.  From the list that is displayed, select the placeholder to insert.
    
    4.  Click **Insert**.

4.  To add translations of the instructions, click **Translations**. In the form that is displayed, follow these steps:
    
    1.  Click the **Add** button.
    
    2.  In the list that is displayed, select the language in which you will enter the text.
    
    3.  In the **Translated text** text box, enter the text.
    
    4.  To personalize the text, you can insert placeholders. See the previous step for instructions about how to enter a placeholder.
    
    5.  Click **Close**.

## Specify when this workflow is used

You can create multiple workflows that are based on the same type. For example, you can create a purchase requisition workflow for each country or region in which you operate, such as *Purchase Requisitions Denmark* and *Purchase Requisitions Spain*.

When you have multiple workflows that are based on the same type, you must specify when each workflow is used. Continuing with the example, you would specify the following conditions:

  - Purchase Requisitions Denmark is used when: country/region = DK

  - Purchase Requisitions Spain is used when: country/region = ES

Follow these steps to specify when the workflow that you are configuring is used.

1.  On the left pane, click **Activation**.

2.  Select the **Set the conditions for running this workflow** check box.

3.  Click **Add condition**.

4.  Enter a condition.

5.  Enter additional conditions, if they are required.

6.  To verify that the conditions that you entered are set correctly, click **Test**. The **Test workflow condition** form is displayed.
    
    Select a record in the **Validate condition** area of the form. Click **Test**. The system evaluates the record to determine whether it meets the conditions that you specified.
    
    For example, if you create a purchase requisition workflow for Spain, the **Validate condition** area of the form displays a list of purchase requisitions. When you click **Test**, the system evaluates the selected purchase requisition to determine whether the country/region = ES.
    
    Click **OK** or **Cancel** to return to the **Properties** form.

## Specify when notifications are sent

When a document is submitted for processing, a workflow instance is created. You can send notifications to users when workflow instances that are based on this workflow are started, completed, terminated, or stopped because of an error.

Follow these steps to specify when notifications are sent.

1.  On the left pane, click **Notifications**.

2.  Select the check box for each event that will trigger notifications:
    
      - **Started** - Send notifications when a workflow instance starts.
    
      - **Stopped** - Send notifications when a workflow instance stops because of an error.
    
      - **Completed** - Send notifications when a workflow instance is completed.
    
      - **Unrecoverable** - Send notifications when a workflow instance stops because of an unrecoverable error.
    
      - **Terminated** - Send notifications when a workflow instance is terminated.

3.  Select the row of an event that you selected in step 2.

4.  Click the **Notification text** tab.

5.  In the text box, enter the text of the notification.

6.  To personalize the text, you can insert placeholders, which are replaced with the appropriate data when they are displayed to users. To insert a placeholder, follow these steps:
    
    1.  Click in the text box to specify where the placeholder should appear.
    
    2.  Click **Insert placeholder**.
    
    3.  From the list that is displayed, select the placeholder to insert.
    
    4.  Click **Insert**.

7.  To add translations of the text, click **Translations**. In the form that is displayed, follow these steps:
    
    1.  Click the **Add** button.
    
    2.  In the list that is displayed, select the language in which you will enter the text.
    
    3.  In the **Translated text** text box, enter the text.
    
    4.  To personalize the text, you can insert placeholders. See the previous step for instructions about how to enter a placeholder.
    
    5.  Click **Close**.

8.  Click the **Recipient** tab.

9.  Specify who receives the notifications from following options.
    
    <table>
    <colgroup>
    <col style="width: 33%" />
    <col style="width: 33%" />
    <col style="width: 33%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Option</p></th>
    <th><p>Select this option to send notifications to…</p></th>
    <th><p>To send notifications, do this…</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Participant</strong></p></td>
    <td><p>Users who are assigned to a specific group or role</p></td>
    <td><ol>
    <li><p>On the <strong>Recipient</strong> tab, click <strong>Participant</strong>.</p></li>
    <li><p>Click the <strong>Role based</strong> tab.</p></li>
    <li><p>From the <strong>Type of participant</strong> list, select the type of group or role to send notifications to.</p></li>
    <li><p>From the <strong>Participant</strong> list, select the group or role to send notifications to.</p></li>
    </ol></td>
    </tr>
    <tr class="even">
    <td><p><strong>Workflow user</strong></p></td>
    <td><p>Users who are participants in this workflow</p></td>
    <td><ol>
    <li><p>On the <strong>Recipient</strong> tab, click <strong>Workflow user</strong>.</p></li>
    <li><p>Click the <strong>Workflow user</strong> tab.</p></li>
    <li><p>From the <strong>Workflow user</strong> list, select a participant in this workflow.</p></li>
    </ol></td>
    </tr>
    <tr class="odd">
    <td><p><strong>User</strong></p></td>
    <td><p>Specific Microsoft Dynamics AX users</p></td>
    <td><ol>
    <li><p>On the <strong>Recipient</strong> tab, click <strong>User</strong>.</p></li>
    <li><p>Click the <strong>User</strong> tab.</p></li>
    <li><p>The <strong>Available users:</strong> list includes all Microsoft Dynamics AX users. Select the users to send notifications to, and move those users into the <strong>Selected users:</strong> list.</p></li>
    </ol></td>
    </tr>
    </tbody>
    </table>


10. Repeat steps 3 through 9 for each event that you selected in step 2.

## Enter comments about the changes that you made to this workflow

To enter comments about the changes that you made to this workflow, follow these steps.

1.  In the left pane, click **Notes**.

2.  In the **Enter comments about the workflow** text box, enter your comments.

3.  Review your comments. After you add comments, you cannot modify them.

4.  Click **Add** to add comments to the **Comment history** area.

## See also

[About the workflow editor](about-the-workflow-editor.md)

[Create a workflow](create-a-workflow.md)

[Configure workflow elements](configure-workflow-elements.md)

  


