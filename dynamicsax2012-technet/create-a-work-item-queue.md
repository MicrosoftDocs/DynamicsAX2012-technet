---
title: Create a work item queue
TOCTitle: Create a work item queue
ms:assetid: 4b91b3a6-7a21-453b-ae61-75497a3db801
ms:mtpsurl: https://technet.microsoft.com/library/Gg731789(v=AX.60)
ms:contentKeyID: 35132627
author: Khairunj
ms.date: 05/02/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create a work item queue 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The following procedures explain how to create and manage work item queues.

## Create a queue

To create a queue, complete the following procedure.

When you create a queue, you are automatically assigned as an administrator of the queue. Queue administrators can change the status of the queue, assign users to or unassign users from the queue, and specify the conditions under which the queue is used.

1.  Click **Organization administration > Workflow > Work item queues**. 

2.  Click **New**.

3.  In the **Name** field, enter a name for the queue.

4.  In the **Description** field, enter a description to help you identify the queue.

5.  In the **Document** field, select the type of document that will be sent to this queue for processing.

6.  In the **Status** field, select one of the following options.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Status</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Active</strong></p></td>
    <td><p>Documents can be sent to the queue for processing.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>On hold</strong></p></td>
    <td><p>Documents cannot be sent to the queue for processing. Use this status when you want to process all of the documents in the queue before you set the status of the queue to <strong>Inactive</strong>.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Inactive</strong></p></td>
    <td><p>Documents cannot be sent to the queue.</p></td>
    </tr>
    </tbody>
    </table>


## Assign users to or unassign users from a queue

A queue must have users assigned to it who are responsible for monitoring the queue and processing the documents in it. Before you assign users to the queue, verify that those users have permission to process the documents that are in the queue. For example, if the queue contains purchase requisitions, make sure that the users who you assign to the queue have permission to view and modify purchase requisitions.

To assign users to or unassign users from a queue, complete the following procedure.

1.  Click **Organization administration** \> **Setup** \> **Workflow** \> **Work item queues**.

2.  Select the queue to assign users to or unassign users from.

3.  Expand the **Users** tab.

4.  To assign a user to the queue, click **Add**. Then follow these steps:
    
    1.  In the **User** field, select the user name of the Microsoft Dynamics AX user to assign to the queue.
    
    2.  Select the **Administrator** check box if this user should be an administrator of the queue.
        
        A queue must have at least one administrator. Queue administrators can change the status of the queue, assign users to or unassign users from the queue, and specify the conditions under which this queue is used.

5.  To unassign a user from the queue, select the row for that user. Then follow these steps:
    
    1.  Click **Remove**.
    
    2.  Confirm that you want to unassign the user from the queue.

## Change the status of a queue

To change the status of a queue, complete the following procedure.

1.  Click **Organization administration** \> **Setup** \> **Workflow** \> **Work item queues**.

2.  Select the queue to change the status of.

3.  Expand the **General** tab.

4.  In the **Status** field, select one of the following options.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Status</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Active</strong></p></td>
    <td><p>Documents can be sent to the queue for processing.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>On hold</strong></p></td>
    <td><p>Documents cannot be sent to the queue for processing. Use this status when you want to process all of the documents in the queue before you set the status of the queue to <strong>Inactive</strong>.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Inactive</strong></p></td>
    <td><p>Documents cannot be sent to the queue.</p></td>
    </tr>
    </tbody>
    </table>


## Specify the conditions under which a queue is used

You can enter conditions to specify when documents are sent to a particular queue. These conditions are called *assignment rules*. You can create several assignment rules and specify the order in which the rules are evaluated.

## Example of how assignment rules are used

To understand how assignment rules are used, suppose that you have created the following assignment rules for queues for purchase requisitions.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Evaluation order</p></th>
<th><p>Assignment rule</p></th>
<th><p>Conditions under which the rule applies</p></th>
<th><p>Queue that purchase requisitions are sent to</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>1</p></td>
<td><p>Rule A</p></td>
<td><ul>
<li><p>Total amount &gt; USD 10,000</p></li>
<li><p>Vendor = Contoso, Ltd</p></li>
</ul></td>
<td><p>Contoso High Cost Queue</p></td>
</tr>
<tr class="even">
<td><p>2</p></td>
<td><p>Rule B</p></td>
<td><ul>
<li><p>Total amount &gt; USD 10,000</p></li>
<li><p>Vendor = Adventure Works</p></li>
</ul></td>
<td><p>Adventure Works High Cost Queue</p></td>
</tr>
<tr class="odd">
<td><p>3</p></td>
<td><p>Rule C</p></td>
<td><ul>
<li><p>Vendor = Contoso, Ltd</p></li>
</ul></td>
<td><p>Contoso Low Cost Queue</p></td>
</tr>
<tr class="even">
<td><p>4</p></td>
<td><p>Rule D</p></td>
<td><ul>
<li><p>Vendor = Adventure Works</p></li>
</ul></td>
<td><p>Adventure Works Low Cost Queue</p></td>
</tr>
</tbody>
</table>


To better understand how these assignment rules are used, assume that an employee has submitted a purchase requisition totaling USD 15,000 for Adventure Works. In this scenario:

1.  Rule A is evaluated. The purchase requisition does not meet the conditions of the rule.

2.  Rule B is evaluated. The purchase requisition meets the conditions of the rule. Therefore, the purchase requisition is sent to the queue that is named Adventure Works High Cost Queue.

Now suppose that an employee has submitted a purchase requisition totaling USD 100 for Contoso, Ltd. In this scenario:

1.  Rule A is evaluated. The purchase requisition does not meet the conditions of the rule.

2.  Rule B is evaluated. The purchase requisition does not meet the conditions of the rule.

3.  Rule C is evaluated. The purchase requisition meets the conditions of the rule. Therefore, the purchase requisition is sent to the queue that is named Contoso Low Cost Queue.

## Create an assignment rule

Complete the following procedure to create an assignment rule.

1.  Click **Organization administration** \> **Setup** \> **Workflow** \> **Work item queues**.

2.  Click **Work item queue assignment rules**. The **Work item queue assignment rules** form is displayed.

3.  Select a type of document from the **Document** list. This indicates that the rule applies to a queue that is configured for the selected type of document.

4.  Click **New** to create a new assignment rule.

5.  In the **Create new work item queue assignment rule** form that appears, follow these steps:
    
    1.  In the **Name** field, enter a name for the assignment rule.
    
    2.  In the **Description** field, enter a brief description to help you identify the rule.
    
    3.  In the **Queue name** field, select a queue. Documents that meet the specified conditions of the rule will be sent to this queue.
    
    4.  Click **Create rule** to create the rule.

6.  To specify the conditions under which this rule applies, follow these steps:
    
    1.  Select the rule in the left pane of the form.
    
    2.  Expand the **Conditions** tab.
    
    3.  Click **Add condition**.
    
    4.  Enter a condition.
    
    5.  Enter additional conditions, if they are required.

7.  To specify when this rule is evaluated, select the **Move up** or **Move down** buttons.

  


