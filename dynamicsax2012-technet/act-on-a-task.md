---
title: Act on a task
TOCTitle: Act on a task
ms:assetid: 50b8ef5a-13f2-4c51-a46c-c2c1f4499b23
ms:mtpsurl: https://technet.microsoft.com/library/Gg212774(v=AX.60)
ms:contentKeyID: 35949293
author: tonyafehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Act on a task 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A task is a unit of work that is associated with a specific business document. For example, the workflow for a purchase requisition may have a task that requires you to:

  - Add a vendor to each line item on the purchase requisition.

  - Call the vendors that are listed on the purchase requisition.

Follow these steps to act on a task that is assigned to you.

1.  Open the document that the task is associated with.

2.  Review the message bar for information about the workflow process. To view detailed instructions, click the icon in the message bar. The following figure shows the location of the message bar and the icon that you click to view instructions.
    
    ![Workflow message bar with the Actions button](images/Dd309606.Workflow_ActionButon(AX.60).gif "Workflow message bar with the Actions button")

3.  A task can be assigned to multiple people, however, only one person can complete the task. If this task is assigned to multiple people, but you want to complete it, click **Actions** \> **Accept**. This indicates that you will complete the task.

4.  Click **Actions** and then click one of the options listed in the following table. The options that you see may vary, depending on how the task was configured.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Option</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Complete</strong></p></td>
    <td><p>Indicate that you have completed the task.</p>
    <p>A dialog box is displayed where you can enter a comment about the document.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Reject</strong></p></td>
    <td><p>Reject the document.</p>
    <p>A dialog box is displayed where you can enter a comment about the document.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Request change</strong></p></td>
    <td><p>Request changes to the document.</p>
    <p>A dialog box is displayed where you can enter a comment about the changes that you are requesting and select the user who should make the changes.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Delegate</strong></p></td>
    <td><p>Reassign the task to another user.</p>
    <p>A dialog box is displayed where you can enter a comment and select the user to delegate the task to.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Reassign</strong></p></td>
    <td><p>Reassign the task to another work item queue.</p>
    <p>A dialog box is displayed where you can enter a comment and select the queue to reassign the task to.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Release</strong></p></td>
    <td><p>Reassign the task to the work item queue that it was originally assigned to. Select this option if you cannot complete the task. The task is returned to the queue so that another user can complete it.</p>
    <p>A dialog box is displayed where you can enter a comment.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>View history</strong></p></td>
    <td><p>View the workflow status and history of the document.</p>
    <p>The <strong>Workflow history</strong> form is displayed. For more information about this form, see <a href="https://technet.microsoft.com/library/hh597256(v=ax.60)">Workflow history (form)</a>.</p></td>
    </tr>
    </tbody>
    </table>

  


