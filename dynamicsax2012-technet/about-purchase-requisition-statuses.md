---
title: About purchase requisition statuses
TOCTitle: About purchase requisition statuses
ms:assetid: c4588f87-db59-4f47-ac6e-cebd236d4dee
ms:mtpsurl: https://technet.microsoft.com/library/Hh271645(v=AX.60)
ms:contentKeyID: 36384277
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About purchase requisition statuses 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Enterprise Portal for Microsoft Dynamics AX, you can view the status of a purchase requisition header and individual lines if you create or have permission to view purchase requisitions. The status is automatically updated during the purchase requisition life cycle.


> [!NOTE]
> <P>This topic includes information about features that were added or changed for Microsoft Dynamics AX 2012 R2. This information also applies to AX 2012 R3. See the section later in this topic.</P>



1.  Do one of the following:
    
      - Click **Procurement** on the top link bar, and then click **Purchase requisitions** \> **Purchase requisitions prepared by me** on the Quick Launch.
    
      - On the Employee services site, click **Order products** on the top link bar, and then click **My orders** \> **All purchase requisitions** on the Quick Launch.

2.  To view the status of individual lines in a purchase requisition, select a purchase requisition, and then on the **Action Pane**, click **View**.

On the **View purchase requisition** page, on the **Lines** FastTab, the status of the purchase requisition line is displayed in the **Status** field.

A purchase requisition can have any of the following statuses:

  - **Draft** – The purchase requisition has not been submitted for review, or it has been recalled and has not been resubmitted for review. You can modify a purchase requisition that has a status of **Draft**.

  - **In review** – The purchase requisition has been submitted to workflow for review, but not all purchase requisition lines have completed the review process.

  - **Approved** – All purchase requisition lines have completed the review process. All purchase requisition lines that have not been approved have been canceled.

  - **Rejected** – The purchase requisition has been rejected. All purchase requisition lines that have not been canceled have been rejected.

  - **Cancelled** – All purchase requisition lines have been canceled. Only purchase requisition lines that were previously approved can be canceled.

  - **Closed** – The purchase requisition is closed, and if the requisition purpose is consumption, a purchase order has been generated for the purchase requisition line. If the requisition purpose is replenishment, one or more fulfillment documents have been generated. If you no longer need an item on a purchase requisition line that has been closed, you must cancel the line on the fulfillment document that was generated for the purchase requisition line.
    

    > [!NOTE]
    > <P>Changes to the requisition fulfillment process have been introduced in Microsoft Dynamics AX 2012 R2. See the section “New or changed for Microsoft Dynamics AX 2012 R2,” later in this topic.</P>



The status of the purchase requisition header depends on the status of the lines in the purchase requisition. After a purchase requisition is submitted for review, the header has a status of **In review** until all lines in the purchase requisition have a status of **Approved** or **Cancelled**.

## New or changed for Microsoft Dynamics AX 2012 R2

In Microsoft Dynamics AX 2012 R2, requisition demand can now be fulfilled by a purchase order, a transfer order, a production order, or kanban depending on the needs of your organization and how it is set up. The requisition purpose and the corresponding policy rules that have been defined for a specific legal entity determine the fulfillment method.

In Enterprise Portal for Microsoft Dynamics AX 2012 R2, you can create and modify requisitions for which the purpose is consumption or replenishment. However, on the Employee services site, you can only create and modify requisitions for which the purpose is consumption. For more information, see [About purchase requisitions (Enterprise Portal)](about-purchase-requisitions-enterprise-portal.md).

## See also

[About purchase requisitions (Enterprise Portal)](about-purchase-requisitions-enterprise-portal.md)

[About purchase requisition workflows](about-purchase-requisition-workflows.md)

  


