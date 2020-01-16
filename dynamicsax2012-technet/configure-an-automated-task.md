---
title: Configure an automated task
TOCTitle: Configure an automated task
ms:assetid: e98729b6-e5be-4b70-9aec-dcdc4ed242bd
ms:mtpsurl: https://technet.microsoft.com/library/Gg732234(v=AX.60)
ms:contentKeyID: 35133175
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Configure an automated task 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To configure an automated task, in the workflow editor, right-click the task and then click **Properties** to open the **Properties** form. Use the following procedures to configure the properties for the automated task.

## Name the task

Follow these steps to enter a name for the automated task.

1.  In the left pane, click **Basic Settings**.

2.  In the **Name** field, enter a unique name for the task.

## Specify when notifications are sent

You can send notifications to people when an automated task has been run or canceled. Follow these steps to specify when notifications are sent, and who they are sent to.

1.  In the left pane, click **Notifications**.

2.  Select the check box next to the events to send notifications for:
    
      - **Execution** – Notifications are sent when the task has been run.
    
      - **Canceled** – Notifications are sent when the task has been canceled.

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
    <li><p>In the <strong>Participant</strong> list, select the group or role to send notifications to.</p></li>
    </ol></td>
    </tr>
    <tr class="even">
    <td><p><strong>Workflow user</strong></p></td>
    <td><p>Users who participate in the current workflow</p></td>
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

## See also

[About the workflow editor](about-the-workflow-editor.md)

[Create a workflow](create-a-workflow.md)

[Configure the properties of a workflow](configure-the-properties-of-a-workflow.md)

[Configure workflow elements](configure-workflow-elements.md)

  


