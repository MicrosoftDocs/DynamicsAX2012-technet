---
title: Complete, approve, or reject a purchase requisition
TOCTitle: Complete, approve, or reject a purchase requisition
ms:assetid: 2153b0c8-7084-475d-9cbf-6a96940000d2
ms:mtpsurl: https://technet.microsoft.com/library/Gg230985(v=AX.60)
ms:contentKeyID: 36687375
author: Khairunj
ms.date: 04/20/2015
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Complete, approve, or reject a purchase requisition 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use these procedures to respond to purchase requisition work items that are assigned to you from workflow. If your organization is using Role Centers and your work list is displayed on your Role Center, the work list displays your work items.

If your organization is using line-level workflow, the action will only pertain to the purchase requisition line item and not the entire purchase requisition. To view the line item, do one of the following:

  - Expand the list of line items, select the line item to work with, and take the appropriate action.

  - Open the purchase requisition, select the line item that you are assigned to, and then take the appropriate action for the line item.

For more information about work lists, see [View your work items in a workflow](view-your-work-items-in-a-workflow.md).


> [!NOTE]
> <P>If your organization is not using Role Centers, you can skip steps 1 and 2 in the following procedures and complete the remaining steps in the <STRONG>Purchase requisitions</STRONG> form.</P>
> <P>If your organization is using work item queues, use the <STRONG>Work items assigned to my queues</STRONG> form to view your work items. For more information, see <A href="create-a-work-item-queue.md">Create a work item queue</A>.</P>



## Complete a purchase requisition

Use this procedure to complete a purchase requisition when a task has been assigned to you from workflow.


> [!NOTE]
> <P>A task can be completed by only one user. If a task is assigned to several users, you must first accept the task, and then perform the task. After you accept the task, the task is no longer assigned to the other users and is removed from their work lists.</P>



1.  Click **Home**, and locate your work list on your Role Center.

2.  Select the task that was assigned to you, and then click **Actions** \> **Open %1** to view either the purchase requisition or the purchase requisition line details.
    
    You must accept the work item task before you can complete the action for the purchase requisition. To accept ownership of the work item, in the **Purchase requisitions** form, in the workflow message bar, click **Actions** \> **Accept**.

3.  After you accept the item, the instructions to complete the work item task are displayed in the workflow message bar at the top of the form.
    
    You can modify most fields in the purchase requisition. In Microsoft Dynamics AX 2012, and if the requisition purpose is consumption in Microsoft Dynamics AX 2012 R2, you can also do one of the following:
    
      - Create a request for quotation from the purchase requisition. For more information about how to create a request for quotation, see [Create a request for quotation from a purchase requisition](create-a-request-for-quotation-from-a-purchase-requisition.md).
    
      - Modify the vendor on the purchase requisition line. As the work item owner, you are not restricted by the same purchasing policies as the preparer. You can select any vendor.

4.  Click **Actions** \> **Complete** to indicate to the system that you completed the work item and that the workflow process can continue.

For more information about requisition purposes in Microsoft Dynamics AX 2012 R2, see [About purchase requisitions](about-purchase-requisitions.md).

## Approve a purchase requisition

Use this procedure to approve a purchase requisition when an approval has been assigned to you from workflow.

1.  Click **Home**, and find your work list on your Role Center.

2.  Select the approval that was assigned to you, and then click **Actions** \> **Open %1** to view the purchase requisition or, if you are using line-level workflow, the purchase requisition line details.
    
    You are not required to accept approvals before you take action, because more than one user may need to review and approve the same work item.

3.  Verify that the information on the purchase requisition is correct, and then click **Actions** \> **Approve** to approve the work item. This action completes the approval for the work item assigned to you. The purchase requisition status will change to an approved status only when all workflow steps are completed successfully.


> [!NOTE]
> <P>If the work item is assigned to you and you have edit permissions, you can modify the document.</P>



## Delegate a purchase requisition work item

Use this procedure to delegate a work item for a purchase requisition to another user.


> [!NOTE]
> <P>You can configure work item delegation in advance in the <STRONG>Options</STRONG> form, <STRONG>Delegation</STRONG> tab. For more information about how to delegate a work item to another user, see <A href="delegate-work-items-in-a-workflow.md">Delegate work items in a workflow</A>.</P>



1.  Click **Home**, and find your work list on your Role Center.

2.  Select the task that was assigned to you, and then click **Actions** \> **Delegate**.

3.  In the **Delegate** form, select the user to delegate the work item to. You can also type a message in the **Comment** field to provide more information.
    
    The purchase requisition remains in a status of **In review**, and a work item is assigned to the selected user.

## Request changes to a purchase requisition

Use this procedure to add another user into the workflow process, including the preparer of the purchase requisition, if additional information is required for the purchase requisition. The user can change the information in most of the fields in the **Purchase requisitions** form. In Microsoft Dynamics AX 2012 and if the requisition purpose is consumption in Microsoft Dynamics AX 2012 R2, the user can also perform additional actions, such as creating a request for quotation, if they have been granted the appropriate permissions. For more information about requisition purposes in Microsoft Dynamics AX 2012 R2, see [About purchase requisitions](about-purchase-requisitions.md).

After the request is completed by the assigned user, the user can resubmit the purchase requisition to workflow. The workflow process will restart the workflow which will ensure that any conditions set in the workflow will take the changes into account. Use this procedure to add any other user into the review process for a purchase requisition before you take action on it.

1.  Click **Home**, and find your work list on your Role Center.

2.  Select the task that was assigned to you, and then click **Actions** \> **Open %1** to view the purchase requisition or, if you are using line-level workflow, the purchase requisition line details.

3.  To request a change on the purchase requisition or purchase requisition line click **Actions** \> **Request change**.

4.  In the **Request change** dialog box, select the user to send the change request to. You can also type a message to provide more information. The purchase requisition remains in a status of **In review**, and a workflow work item is assigned to the selected user.

When the workflow is re-submitted you can use the workflow history to track that it has been re-submitted on behalf of the preparer.

## Reject a purchase requisition

Use this procedure to reject a purchase requisition when a task or approval has been assigned to you from workflow.

1.  Click **Home**, and find your work list on your Role Center.

2.  Select the task that was assigned to you, and then click **Actions** \> **Open %1** to view the purchase requisition or, if you are using line-level workflow, the purchase requisition line details.

3.  In the **Purchase requisitions** form, in the workflow menu bar, click **Actions** \> **Reject**. In the **Reject** dialog box, you can type a message to provide more information and then click **Reject**. The purchase requisition or purchase requisition line status changes from **In review** to **Rejected**.
    
    The user can change the rejected purchase requisition and then resubmit it to workflow. The purchase requisition review process starts over again. If line-level workflow is enabled and the user changes a rejected purchase requisition line and then resubmits it, the purchase requisition review process starts over again for the whole purchase requisition.

## See also

[About purchase requisitions](about-purchase-requisitions.md)

[About statuses for purchase requisitions](about-statuses-for-purchase-requisitions.md)

[Key tasks: Create and submit a purchase requisition](key-tasks-create-and-submit-a-purchase-requisition.md)

  


