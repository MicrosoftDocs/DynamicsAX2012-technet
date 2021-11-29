---
title: About purchase requisition workflows
TOCTitle: About purchase requisition workflows
ms:assetid: df6a9eca-eb77-48c4-8451-727709489837
ms:mtpsurl: https://technet.microsoft.com/library/Hh271676(v=AX.60)
ms:contentKeyID: 36384307
author: Khairunj
ms.author: daxcpft
ms.date: 05/01/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About purchase requisition workflows 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To move a purchase requisition through the review process from an initial status of **Draft** to a final status of **Approved**, you submit it to the workflow system. You set up a workflow for purchase requisitions in the Microsoft Dynamics AX client. The workflow can be configured to include one or more review steps.

The workflow system can route the purchase requisition through the review process as a single document. Alternatively, the lines on the purchase requisition can be routed individually to the appropriate reviewers. If the purchase requisition lines are reviewed individually, the review process must be completed for all purchase requisition lines before the review process for the purchase requisition as a whole can be completed. The overall status of the purchase requisition is controlled by the status of the purchase requisition lines. The workflow system can also be configured to skip the review tasks and automatically approve the purchase requisition when it is submitted for review.

After the requisition is set to a status of **Approved**, a purchase order can be generated for the requisition lines and submitted to the vendor for fulfillment.

For more information about how to configure workflow for purchase requisitions, see "Set up purchase requisition workflow" in the Application User Help in the Microsoft Dynamics AX client. For more information about the workflow statuses that are used for purchase requisitions, see [About purchase requisition statuses](about-purchase-requisition-statuses.md).


> [!NOTE]
> <P>This topic includes information about features that were added or changed for Microsoft Dynamics AX 2012 R2. This information also applies to AX 2012 R3. See the section later in this topic.</P>



## Example: Purchase requisition workflow

The purchase requisition workflow represents the business process for purchase requisitions in your organization. The workflow defines how a purchase requisition flows through your organization by determining who can complete and approve purchase requisitions. The example in the following illustration shows how a purchase requisition can flow through the workflow review process. In this example, the purchase requisition is being routed through the workflow process as a single document. The lines on the purchase requisition are not being routed individually.

Purchase requisition review process

  
![Purchase requisition workflow review process](images/Gg242844.PurchReqWorkflowOverview_Submission(AX.60).gif "Purchase requisition workflow review process")Purchase requisition review process

In this example, three business roles in the organization are included in the workflow:

  - The user who requests the items or services – The requester

  - The purchasing agent – An approver

  - The requester's manager – An approver


> [!NOTE]
> <P>The requester is the worker who requested the items or services that are on the purchase requisition, and who receives those items or services. However, this worker does not have to be the person who prepares the purchase requisition. Another worker can be granted permission to create and submit purchase requisitions on behalf of the requester. This worker is called the preparer. The preparer is responsible for managing the purchase requisition after it is submitted, until it is approved or canceled. In this scenario, the requester cannot modify the purchase requisition.</P>



In this example, the purchase requisition follows these steps in the workflow process:

1.  The preparer creates a purchase requisition and submits it for review.

2.  The purchasing agent receives a notification. The notification requests that the purchasing agent verify the information in the purchase requisition and fill in any required information that is missing. Required information can include the net amount and vendor information. The purchasing agent can also return the purchase requisition to the preparer. When the required fields have been filled in, the purchase requisition can move forward in the review process.
    

    > [!NOTE]
    > <P>If workflow is configured to skip the review tasks when a purchase requisition contains no errors, the purchase requisition can automatically be set to a status of <STRONG>Approved</STRONG>.</P>



3.  The requester's manager reviews and approves the purchase requisition.
    
    The approval may be routed to the requester's manager if, for example, the requester has exceeded his or her spending limit. The requester's manager can approve or reject the purchase requisition, or return it to the preparer and request changes.
    

    > [!NOTE]
    > <P>In this example, the purchase requisition is not assigned to specific users or groups. Instead, it is assigned to users, based on a user hierarchy. Therefore, the requester's manager is the approver. For more information about how to assign reviewers for a workflow task, see "Configure a manual task" in the Application User Help in the Microsoft Dynamics AX client.</P>



If Microsoft Dynamics AX is set up to automatically create purchase orders, purchase orders are created after the purchase requisition is approved. A purchase order is created for each currency, vendor, or legal entity that is identified on the purchase requisition lines. For example, if a purchase requisition has two lines, and each line has a different vendor, currency, or legal entity, two purchase orders are created.

Depending on how purchasing policies are configured for your organization, separate purchase orders can also be created if the purchase requisition lines have different requesters, line types, or procurement categories.

If Microsoft Dynamics AX is not set up to automatically create purchase orders, the purchasing agent must manually select the purchase requisition lines and create the purchase orders.


> [!NOTE]
> <P>For information about how to set up rules to automatically generate purchase orders for approved purchase requisitions, see "Set up purchase order creation and demand consolidation rules" in the Application User Help in the Microsoft Dynamics AX client.</P>



## New or changed for Microsoft Dynamics AX 2012 R2

In Microsoft Dynamics AX 2012 R2, the concept of a requisition purpose has been introduced. A requisition purpose allows for more flexibility in how requisition demand can be fulfilled. When you create a requisition, you can assign one of two purposes to it: consumption or replenishment. Depending on the purpose, requisition demand can be fulfilled by a purchase order, transfer order, production order, or kanban. For more information about requisition purposes and how they affect the requisition process, see [About purchase requisitions (Enterprise Portal)](about-purchase-requisitions-enterprise-portal.md).

**Requisitions that have a purpose of consumption**


> [!NOTE]
> <P>A requisition that has a purpose of consumption in Microsoft Dynamics AX 2012 R2 is equivalent to a purchase requisition in Microsoft Dynamics AX 2012.</P>



The demand that is created by a requisition that has a purpose of consumption is always fulfilled by a purchase order. If Microsoft Dynamics AX is set up to automatically create purchase orders, purchase orders are created after the purchase requisition is approved. A purchase order is created for each currency, vendor, or legal entity that is identified on the purchase requisition lines. For example, if a purchase requisition has two lines, and each line has a different vendor, currency, or legal entity, two purchase orders are created.

Depending on how purchasing policies are configured for your organization, separate purchase orders can also be created if the purchase requisition lines have different requesters, line types, or procurement categories.

If Microsoft Dynamics AX is not set up to automatically create purchase orders, the purchasing agent must manually select the purchase requisition lines and create the purchase orders.


> [!NOTE]
> <P>For information about how to set up rules to automatically generate purchase orders for approved purchase requisitions, see "Set up purchase order creation and demand consolidation rules" in the Application User Help in the Microsoft Dynamics AX client.</P>



**Requisitions that have a purpose of replenishment**

The demand that is created by a requisition that has a purpose of replenishment can be fulfilled by a purchase order, transfer order, production order, or kanban. Microsoft Dynamics AX must be set up to include requisition demand in master planning. After this is set up, the fulfillment method for the demand that is created by a requisition that has a purpose of replenishment is automatically determined by the supply policies that have been set up for the items in your organization and planned by using master planning.


> [!NOTE]
> <P>For more information about how to set up master planning to automatically consider requisition demand when the requisition purpose is replenishment, see “Set up master planning for requisitions” in the Application User Help in the Microsoft Dynamics AX 2012 R2 client.</P>



## See also

[Create and maintain purchase requisitions](create-and-maintain-purchase-requisitions.md)

[About purchase requisitions (Enterprise Portal)](about-purchase-requisitions-enterprise-portal.md)

[View purchase requisition history (Enterprise Portal)](view-purchase-requisition-history-enterprise-portal.md)

  


