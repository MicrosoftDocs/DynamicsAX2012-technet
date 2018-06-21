---
title: Overview of a purchase requisition workflow
TOCTitle: Overview of a purchase requisition workflow
ms:assetid: 8790f0f9-c672-41a8-9306-efb322bd427a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg242844(v=AX.60)
ms:contentKeyID: 36058430
ms.date: 03/25/2015
mtps_version: v=AX.60
---

# Overview of a purchase requisition workflow [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The workflow process moves purchase requisitions through the review process, from an initial status of **Draft** to a final status of **Approved**. When a purchase requisition is submitted for review, the workflow process is started. After a purchase requisition is approved, a purchase order can be generated for the purchase requisition lines and submitted to the vendor for order fulfillment.


> [!WARNING]
> <P>This topic has been updated to include information about features that were added or changed in the following hotfix for Microsoft Dynamics AX 2012 R3 Cumulative Update 8: KB3047235</P>



Before a purchase requisition can be submitted for review, workflow must be configured. The workflow process can include one or more review steps in any order. The workflow process can also be configured to skip the review tasks and automatically approve the purchase requisition. You can configure the workflow to route the purchase requisition as a single document. Alternatively, you can route individual purchase requisition lines to the appropriate reviewers. You can also create a scenario where the purchase requisition is routed as a single document to some reviewers, and selected purchase requisition lines are routed to other reviewers.

If purchase requisition lines are reviewed individually, the review process must be completed for all purchase requisition lines before workflow can move to the next step in the process, and before the review process for the purchase requisition as a whole can be completed. When the purchase requisition, including all lines, has completed the review process, the overall status of the purchase requisition is updated to **Approved**.

You can configure your workflow to represent the business process for purchase requisitions in your organization. When you configure your purchase requisition workflow process, consider the following points:

  - What expenditures must be reviewed?

  - What expenditures can be automatically approved?

  - Who is required to review and approve expenditure requests? What role are these users assigned to?

  - What is the process for when a reviewer is not available?

The following examples illustrate two ways that you can configure workflow for purchase requisitions.


> [!NOTE]
> <P>This topic includes information about features that were added or changed for Microsoft Dynamics AX 2012 R2. This information also applies to AX 2012 R3. See the section later in this topic.</P>



## Example 1: Route a purchase requisition as a single document for review

The following illustration shows how a purchase requisition can flow through the workflow review process as a single document. The lines on the purchase requisition are not routed individually.

In this example, the following roles are included in the workflow:

  - The requester – The user who requests the items or services. The requester can prepare the purchase requisition, or another worker can prepare the purchase requisition on the requester’s behalf. This worker is the preparer. The preparer is responsible for managing the purchase requisition throughout the review process. Only the preparer of the purchase requisition can modify it.
    

    > [!NOTE]
    > <P>A worker must be granted the appropriate permissions to create a purchase requisition on behalf of someone else. For more information about how to set up the permissions, see <A href="set-up-permissions-for-ordering-products-on-behalf-of-someone-else.md">Set up permissions for ordering products on behalf of someone else</A>.</P>



  - The purchasing agent – The user who performs a procurement review and can approve the document.

  - The requester's manager – The user who performs a managerial review and can approve the document.

![Purchase requisition workflow review process](images/Gg242844.PurchReqWorkflowOverview_Submission(AX.60).gif "Purchase requisition workflow review process")

In this example, the workflow process for the purchase requisition includes the following steps:

1.  The preparer submits a purchase requisition for review.

2.  The purchasing agent receives a notification that requests the purchasing agent to verify the information in the purchase requisition. If required information is missing, the purchasing agent can add the information or return the purchase requisition to the preparer to add it. When the required fields have been filled in, the purchase requisition can move to the next step in the review process.

3.  The requester's manager reviews the purchase requisition.
    
    The purchase requisition may be routed to the requester's manager if, for example, the amount of the purchase requisition exceeds the requester’s spending limit for purchase requisitions. The requester's manager can approve or reject the purchase requisition, or return it to the preparer for changes.

## Example 2: Route the individual purchase requisition lines for review

The following illustration shows how the individual purchase requisition lines can be routed through workflow. The process for each line is generally the same as the process for a purchase requisition that is reviewed as a single document. However, each line must complete the workflow process individually before workflow can be completed for the purchase requisition as a whole.

In this example, a worker enters a request for posters and t-shirts for a marketing campaign. The cost of the posters is split between the Marketing department and the Sales department. If the cost of the posters or t-shirts exceeds the signing limit authority for department managers, the purchase requisition must also be reviewed by the group manager.

The following roles are included in the workflow process for this example:

  - The requester – The user who requests the items or services. The requester can prepare the purchase requisition, or another worker can prepare the purchase requisition on the requester’s behalf. This worker is the preparer. The preparer is responsible for managing the purchase requisition throughout the review process. Only the preparer of the purchase requisition can modify it.
    

    > [!NOTE]
    > <P>A worker must be granted the appropriate permissions to create a purchase requisition on behalf of someone else. For more information about how to set up the permissions, see <A href="set-up-permissions-for-ordering-products-on-behalf-of-someone-else.md">Set up permissions for ordering products on behalf of someone else</A>.</P>



  - The purchasing agent – The user who performs a procurement review and can approve the document.

  - The requester's manager – The user who performs a managerial review and can approve the document.

  - The department manager – The user who performs an expenditure review and can approve the document.

  - The group manager – The user who performs a signature authority review and can approve the document.

![Purchase requisition line workflow review process](images/Gg242844.PurchReqLineWorkflowOverview(AX.60).gif "Purchase requisition line workflow review process")

In this example, the workflow process for the purchase requisition lines includes the following steps:

1.  The preparer submits a purchase requisition for review. Each line is routed to the reviewer who is configured in the workflow process.

2.  The purchasing agent receives a notification that requests the purchasing agent to verify the information in the purchase requisition and purchase requisition lines. If required information is missing, the purchasing agent can add the information or return a purchase requisition line to the preparer to add it. When the required fields have been filled in, the purchase requisition line can move to the next step in the review process. Purchase requisition lines can continue through the review process independent of each other.

3.  The requester's line manager reviews and approves the purchase requisition lines.
    
    The approval may be routed to the requester's manager if, for example, the amount on the purchase requisition line exceeds the requester’s spending limit for purchase requisition lines. The manager can approve or reject one or both of the purchase requisition lines.

4.  The department manager for the Marketing department reviews the purchase requisition lines for both the posters and the t-shirts. The Sales department manager reviews the purchase requisition line only for the posters, because that is the only cost that is being charged to the Sales department.

5.  The group manager reviews and approves the purchase requisition line for the t-shirts only if it is required. For example, if the amount on the purchase requisition line exceeds the department manager’s approval limit. The group manager does not have to approve the purchase requisition line for the posters.

## Configure workflow for purchase requisitions

To route a purchase requisition for review, you must configure the purchase requisition workflow processes. The workflow process that you define controls the interaction between the user who requested the items (the requester) and the reviewer and approver in the workflow. It determines the routing of the purchase requisition based on the conditions specified in the workflow configuration, such as when to route the purchase requisition, the user or role to route it to, and available actions that users can take.

The examples in this topic describe how a purchase requisition can be routed through workflow as a single document or as individual purchase requisition lines. You can also configure workflow for purchase requisitions to reflect the internal control review of purchase requisitions that is defined for your organization. For more information about how to configure workflow for purchase requisitions, see [Set up Procurement and sourcing workflows](set-up-procurement-and-sourcing-workflows.md).

## New or changed for Microsoft Dynamics AX 2012 R2

In Microsoft Dynamics AX 2012 R2, the concept of a requisition purpose has been introduced. A requisition purpose allows for more flexibility in how requisition demand can be fulfilled. When you create a requisition, you can assign one of two purposes to it: consumption or replenishment. Depending on the purpose, requisition demand can be fulfilled by a purchase order, transfer order, production order, or kanban. For more information about requisition purposes and how they affect the requisition process, see [About purchase requisitions](about-purchase-requisitions.md).

**Requisitions that have a purpose of consumption**

The demand that is created by a requisition that has a purpose of consumption is always fulfilled by a purchase order. If Microsoft Dynamics AX is set up to automatically create purchase orders, purchase orders are created after the purchase requisition is approved. A purchase order is created for each currency, vendor, or legal entity that is identified on the purchase requisition lines. For example, if a purchase requisition has two lines, and each line has a different vendor, currency, or legal entity, two purchase orders are created.

Depending on how purchasing policies are configured for your organization, separate purchase orders can also be created if the purchase requisition lines have different requesters, line types, or procurement categories.

If Microsoft Dynamics AX is not set up to automatically create purchase orders, the purchasing agent must manually select the purchase requisition lines and create the purchase orders.


> [!NOTE]
> <P>For information about how to set up rules to automatically generate purchase orders for approved purchase requisitions, see <A href="set-up-rules-for-demand-consolidation-and-for-creating-purchase-orders.md">Set up rules for demand consolidation and for creating purchase orders</A>.</P>



**Requisitions that have a purpose of replenishment**

The demand that is created by a requisition that has a purpose of replenishment can be fulfilled by a purchase order, transfer order, production order, or kanban. Microsoft Dynamics AX must be set up to include requisition demand in master scheduling. After this is set up, the fulfillment method for the demand that is created by a requisition that has a purpose of replenishment is automatically determined by the supply policies that have been set up for the items in your organization and planned by using master scheduling.


> [!NOTE]
> <P>For more information about how to set up master planning to automatically consider requisition demand when the requisition purpose is replenishment, see <A href="set-up-master-plans-to-include-requisitions.md">Set up master plans to include requisitions</A>.</P>



## New or changed for Microsoft Dynamics AX 2012 R3 Cumulative Update 8 with hotfix KB3047235

 For the public sector, if you use workflow with general budget reservations in your procurements, see [Set up general budget reservation workflows (Public sector)](set-up-general-budget-reservation-workflows-public-sector.md).


> [!NOTE]
> <P>General budget reservations are available only if the <STRONG>Public Sector</STRONG> configuration key is selected and if Microsoft Dynamics AX 2012 R3 Cumulative Update 8 is installed with the following hotfix: KB3047235</P>



## See also

[About purchase requisitions](about-purchase-requisitions.md)

[Set up Procurement and sourcing workflows](set-up-procurement-and-sourcing-workflows.md)

[Set up expenditure reviewer configurations](set-up-expenditure-reviewer-configurations.md)

[Set up master plans to include requisitions](set-up-master-plans-to-include-requisitions.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

