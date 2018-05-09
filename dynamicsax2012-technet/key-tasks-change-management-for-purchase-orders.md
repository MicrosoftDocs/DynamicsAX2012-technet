---
title: 'Key tasks: Change management for purchase orders'
TOCTitle: 'Key tasks: Change management for purchase orders'
ms:assetid: 1f149219-fb27-4386-997b-139f053588c3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh802989(v=AX.60)
ms:contentKeyID: 44080955
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- purchase order
- purchase orders
- change management
---

# Key tasks: Change management for purchase orders 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use change management to control the changes that you make to purchase orders in your organization. Change management introduces a managed workflow that makes sure that purchase orders are locked when they have been approved. The purchase orders cannot be changed until you start the change request workflow. When the workflow starts, all changes are stored in a history log, so that you can review the changes and compare purchase order versions.

To understand the change management process, you must understand how the change process fits into the life cycle of the purchase order. There are six approval statuses that the purchase order travels through, from **Draft** to **Finalized**. Change requests can be raised in only two of the approval statuses.


> [!NOTE]
> <P>A change request cannot be canceled. It must always be submitted and approved through the workflow.</P>



<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Approval status</p></th>
<th><p>Description</p></th>
<th><p>Change requests allowed</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Draft</strong></p></td>
<td><p>The purchase order is a draft and has not been submitted for approval in the purchase order workflow.</p></td>
<td><p>No</p></td>
</tr>
<tr class="even">
<td><p><strong>In review</strong></p></td>
<td><p>The purchase order was submitted for approval in the purchase order workflow. Approval is pending.</p></td>
<td><p>No</p></td>
</tr>
<tr class="odd">
<td><p><strong>Rejected</strong></p></td>
<td><p>The purchase order was rejected during the approval process.</p></td>
<td><p>No</p></td>
</tr>
<tr class="even">
<td><p><strong>Approved</strong></p></td>
<td><p>The purchase order was approved.</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="odd">
<td><p><strong>Confirmed</strong></p></td>
<td><p>The purchase order was confirmed. A purchase order cannot be confirmed until it has been approved.</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="even">
<td><p><strong>Finalized</strong></p></td>
<td><p>The purchase order was made final. It is financially closed and can no longer be changed.</p></td>
<td><p>No</p></td>
</tr>
</tbody>
</table>


Purchase order statuses cannot be increased for intercompany trading partners when change management is enabled. Also, purchase orders that have been created by firming planned orders from master planning are always set to **Approved**, regardless of the change management settings.

## What do you want to do?

Learn more about...

Set up change management for purchase orders

Set up workflow for change management

Change a purchase order

View purchase order history and compare versions

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[About purchase order types](about-purchase-order-types.md)

[About purchase order posting types](about-purchase-order-posting-types.md)

## Set up change management for purchase orders

1.  Click **Procurement and sourcing** \> **Setup** \> **Procurement and sourcing parameters**.

2.  In the **General** area, select the **Activate change management** check box to enable change management for purchase orders in the current legal entity.

3.  Select the **Allow override of settings per vendor** check box if you want to be able to override the default settings for each vendor. This means that you can enable or disable the change management process for each vendor, regardless of the settings for the current legal entity.
    

    > [!NOTE]
    > <P>To override the change management settings for a vendor, select the <STRONG>Override settings</STRONG> check box on the <STRONG>Purchase order defaults</STRONG> FastTab in the <STRONG>Vendors</STRONG> form.</P>



Back to top

## Set up workflow for change management

A purchase order must have an **Approved** status before you can request that a change be made to the purchase order. A purchase order can have this status only if it is processed through a workflow. Therefore, when you enable change management, you must also set up a purchase order workflow. You do this on the **Procurement and sourcing workflows** list page. When you have set up the workflow, you must also enable it. For information about how to set up workflows, see [Create a workflow](create-a-workflow.md) and [Set up Procurement and sourcing workflows](set-up-procurement-and-sourcing-workflows.md).

A workflow represents a business process. It defines how a document flows through the system and indicates who must complete a task or approve a document. There are several benefits of using the workflow system in your organization:

  - **Consistent processes** — You can define the approval process for specific documents, such as purchase requisitions and expense reports. Using the workflow system helps to ensure that documents are processed and approved in a consistent and efficient manner.

  - **Process visibility** — You can track the status, history, and performance metrics of a specific workflow instance. This helps you determine whether changes should be made to the workflow to improve efficiency.

  - **Centralized work list** — Users can view a centralized work list to view the workflow tasks and approvals assigned to them. This work list is available from the Role Center pages in the Microsoft Dynamics AX client and Enterprise Portal.

For an overview of workflow in Microsoft Dynamics AX, see [Overview of the workflow system](overview-of-the-workflow-system.md) and [Workflow concepts](workflow-concepts.md).

1.  Click **Procurement and sourcing** \> **Setup** \> **Procurement and sourcing workflows**.

2.  On the **Action Pane**, click **New**.

3.  Select the type of workflow to create, and then click **Create workflow**.

4.  In the workflow editor, design the workflow by dragging workflow elements onto the canvas.

5.  Configure each element of the workflow. For more information, see [Configuring the workflow system](configuring-the-workflow-system.md).

6.  Repeat steps 2 through 5 to create additional workflows for Procurement and sourcing.

Back to top

## Change a purchase order

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**.
    
    –or–
    
    Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Select the purchase order. On the **Action Pane**, on the **Purchase order** tab, in the **Maintain** group, click **Request change**.
    

    > [!NOTE]
    > <P>The selected purchase order can be changed only if it has been approved. If change management has not been enabled, a purchase order can be approved when it is created. If change management has been enabled, the purchase order can be approved through a workflow.</P>



3.  Enter the required changes on the purchase order. The approval status is set to **Draft**, and the purchase order must be approved again by all approvers before the purchase order can be processed.

Back to top

## View purchase order history and compare versions

When you change a purchase order, a copy of the changes is saved. All changes that you make at the header level and at the line level are saved. You can then view the difference between the approved purchase order and the changes that were made, and you can compare the purchase order versions.

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**.
    
    –or–
    
    Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Select the purchase order.

3.  On the **Action Pane**, on the **Manage** tab, in the **History** group, click **Compare purchase order versions**.

4.  In the **Compare purchase order versions** form, review the changes that were made to the selected purchase order. All changes to individual fields are listed on the **Changed fields** FastTab. These values apply on the purchase order lines:
    
      - Exclamation point – One or more changes were made to the existing data.
    
      - Check mark – No changes were made to the existing data.
    
      - Plus sign – A new purchase order line was added.
    
      - Red X – The line was deleted.

5.  Click **Close** to return to the **All purchase orders** list page.

6.  On the **Action Pane**, on the **Manage** tab, in the **History** group, click **View purchase order versions**.

7.  In the **Purchase order versions** form, view a list of the available versions of the selected purchase order. You can sort the list by change date or approval status.

Back to top

## Find form help

[Purchase order (form)](https://technet.microsoft.com/en-us/library/aa557983\(v=ax.60\))

[Finalize purchase order (form)](https://technet.microsoft.com/en-us/library/hh209586\(v=ax.60\))

[Compare purchase order versions (form)](https://technet.microsoft.com/en-us/library/hh209288\(v=ax.60\))

## Find related tasks

[Create a purchase order](create-a-purchase-order.md)

[Journalize purchase orders](journalize-purchase-orders.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

