---
title: About statuses for purchase requisitions
TOCTitle: About statuses for purchase requisitions
ms:assetid: 47a8992a-64e5-434f-9fe8-98243745e196
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg231397(v=AX.60)
ms:contentKeyID: 36056915
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# About statuses for purchase requisitions 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you create a purchase requisition, it is assigned a status. Each line that you add to a purchase requisition is also assigned a status. When you submit a purchase requisition to workflow for review, the status of the purchase requisition and the status of each line are updated as the lines move through the purchase requisition process.

You can configure the purchase requisition workflow process to route a purchase requisition through the review process as a single document. Alternatively, the lines on a purchase requisition can be routed individually to the appropriate reviewers. If the purchase requisition lines are reviewed individually, the purchase requisition line status can be updated as the line moves through the review process. When all lines have completed the review process and there are no review steps remaining for the purchase requisition, the status for the whole purchase requisition is updated.


> [!NOTE]
> <P>This topic includes information about features that were added or changed for Microsoft Dynamics AX 2012 R2. This information also applies to AX 2012 R3. See the section later in this topic.</P>



## Purchase requisition status process flow

The following diagram illustrates the statuses that are assigned to a purchase requisition and purchase requisition line as it moves through the workflow process.

![Purchase requisition header and line statuses](images/Gg231397.PurchaseRequisiton_headerline_statuses(AX.60).gif "Purchase requisition header and line statuses")

## Purchase requisition header and line status relationships

The overall status of a purchase requisition is controlled by the status of the purchase requisition lines. Therefore, the review process must be completed for all purchase requisition lines before the review process for the purchase requisition can be completed.

The following table describes the statuses that are assigned to a purchase requisition header and lines as the purchase requisition moves through the process.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Purchase requisition status</p></th>
<th><p>Purchase requisition line status</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Draft</strong></p></td>
<td><p><strong>Draft</strong></p></td>
<td><p>The purchase requisition and purchase requisition line have been created, but have not been submitted for review. The purchase requisition and requisition line can be modified when they have a status of <strong>Draft</strong>.</p>
<p>A purchase requisition or purchase requisition line can also have a status of <strong>Draft</strong> if it has been recalled and it has not been resubmitted for review.</p>
<div class="alert"> 

> [!NOTE]
> <P>You can submit or recall a purchase requisition at the document level. However, you cannot submit or recall a single purchase requisition line.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>In review</strong></p></td>
<td><ul>
<li><p><strong>In review</strong></p></li>
<li><p><strong>Rejected</strong></p></li>
</ul></td>
<td><p>If workflow has been configured to route purchase requisition lines to individual reviewers, each line can have a status of <strong>In review</strong> or <strong>Rejected</strong>. The purchase requisition status is updated when the review process is complete for purchase requisition lines and there are no review steps remaining for the purchase requisition.</p>
<ul>
<li><p><strong>In review</strong> – The purchase requisition lines have been submitted for review. When the workflow process is complete for a purchase requisition line, it remains in a status of <strong>In review</strong> until all the purchase requisition lines have been reviewed.</p></li>
<li><p><strong>Rejected</strong> – A purchase requisition line has been rejected. The purchase requisition line can be modified and resubmitted.</p>
<p>If you resubmit a purchase requisition line that has been rejected, the review process starts over for all lines in the purchase requisition that are still in review.</p></li>
</ul>
<div class="alert"> 

> [!NOTE]
> <P>You can recall a purchase requisition that has already been submitted. When you recall a purchase requisition, all purchase requisition lines are also recalled. Purchase requisition lines that have been recalled can be deleted.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>Rejected</strong></p></td>
<td><p><strong>Rejected</strong></p></td>
<td><p>The purchase requisition has been rejected and all purchase requisition lines have been rejected. Purchase requisitions and purchase requisition lines that have been rejected can be resubmitted.</p></td>
</tr>
<tr class="even">
<td><p><strong>Approved</strong></p></td>
<td><ul>
<li><p><strong>Approved</strong></p></li>
<li><p><strong>Cancelled</strong></p></li>
<li><p><strong>Closed</strong></p></li>
</ul></td>
<td><p>All purchase requisition lines have completed the review process and there are no more review steps for the purchase requisition.</p>
<ul>
<li><p><strong>Approved</strong> – The review process for a purchase requisition line has been completed and the line is approved.</p></li>
<li><p><strong>Cancelled</strong> – The purchase requisition line was approved, but has been canceled because it is no longer needed. Only purchase requisition lines that have been approved can be canceled.</p></li>
<li><p><strong>Closed</strong> – The purchase requisition line has been approved and if the requisition purpose is consumption, a purchase order has been generated for the purchase requisition line. If the requisition purpose is replenishment, one or more fulfillment documents have been generated.</p>
<div class="alert"> 

> [!NOTE]
> <P>Changes to the requisition fulfillment process have been introduced in Microsoft Dynamics AX 2012 R2. See “New or changed for Microsoft Dynamics AX 2012 R2,” later in this topic.</P>


</div></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Cancelled</strong></p></td>
<td><p><strong>Cancelled</strong></p></td>
<td><p>The purchase requisition and all purchase requisition lines have been canceled.</p>
<div class="alert"> 

> [!NOTE]
> <P>If you no longer need an item that is on a purchase requisition line, you must cancel the purchase requisition line if it has been approved. Only purchase requisition lines that have been approved can be canceled. If any purchase requisition lines are in review, the purchase requisition will also have a status of <STRONG>In review</STRONG>. You can recall the purchase requisition, and delete the purchase requisition line.</P>


</div>
<p></p></td>
</tr>
<tr class="even">
<td><p><strong>Closed</strong></p></td>
<td><ul>
<li><p><strong>Closed</strong></p></li>
<li><p><strong>Cancelled</strong></p></li>
</ul></td>
<td><p>The purchase requisition is closed, and one or more fulfillment documents have been generated.</p>
<div class="alert"> 

> [!NOTE]
> <P>Changes to the requisition fulfillment process have been introduced in Microsoft Dynamics AX 2012 R2. See the section “New or changed for Microsoft Dynamics AX 2012 R2,” later in this topic.</P>


</div>
<ul>
<li><p><strong>Closed</strong> – The purchase requisition line has been approved and if the requisition purpose is consumption, a purchase order has been generated for the purchase requisition line. If the requisition purpose is replenishment, one or more fulfillment documents have been generated.</p></li>
<li><p><strong>Cancelled</strong> – The purchase requisition line was approved, but has been canceled because it is no longer needed. Only purchase requisition lines that have been approved can be canceled.</p></li>
</ul>
<div class="alert"> 

> [!NOTE]
> <P>If you no longer need an item on a purchase requisition line that has been closed, you must cancel the line on the fulfillment document that was generated for the purchase requisition line.</P>


</div></td>
</tr>
</tbody>
</table>


## New or changed for Microsoft Dynamics AX 2012 R2

In Microsoft Dynamics AX 2012 R2, requisition demand can now be fulfilled by a purchase order, a transfer order, a production order, or kanban depending on the needs of your organization and how it is set up. The requisition purpose and the corresponding policy rules that have been defined for a specific legal entity determine the fulfillment method. For more information, see [About purchase requisitions](about-purchase-requisitions.md).

## See also

[About purchase requisitions](about-purchase-requisitions.md)

[Overview of a purchase requisition workflow](overview-of-a-purchase-requisition-workflow.md)

[Key tasks: Create and submit a purchase requisition](key-tasks-create-and-submit-a-purchase-requisition.md)

[Purchase requisitions (list page)](https://technet.microsoft.com/en-us/library/hh227485\(v=ax.60\))

[Purchase requisitions (form)](https://technet.microsoft.com/en-us/library/hh209453\(v=ax.60\))

[Purchase requisitions - lines (form)](https://technet.microsoft.com/en-us/library/hh209354\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

