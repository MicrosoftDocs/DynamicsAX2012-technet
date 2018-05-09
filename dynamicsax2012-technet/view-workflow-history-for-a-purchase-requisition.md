---
title: View workflow history for a purchase requisition
TOCTitle: View workflow history for a purchase requisition
ms:assetid: 7ba99d27-62c0-45d7-b0ea-de5c41e675f0
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh271574(v=AX.60)
ms:contentKeyID: 36384205
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- WorkflowHistoryDetails
---

# View workflow history for a purchase requisition 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The workflow history of a purchase requisition includes information about who created the workflow work item, the time and date when the work item was created, a list of actions associated with the work item, and any comments that were entered during the workflow process.

On the **Workflow history details** page, you can recall a purchase requisition from workflow if you created the requisition.


> [!NOTE]
> <P>If a purchase requisition has never been submitted to workflow, workflow history is not available.</P>



## View workflow details

Use this procedure to view the workflow history of a purchase requisition.

1.  Click **Procurement** on the top link bar. On the Quick Launch, click **Purchase requisitions**, and then click **Purchase requisitions prepared by me**.

2.  Select a purchase requisition from the list. The requisition must have a status of **In review**, **Approved**, **Rejected**, or **Cancelled**.

3.  Click **Actions**, and then **View history**.

4.  On the **Workflow history details** page, you can view details about the workflow activities and the status of each task in the purchase requisition workflow.

## Recall a purchase requisition from workflow

Use this procedure to recall a purchase requisition from workflow. You can either delete the recalled purchase requisition or modify the purchase requisition and resubmit it to workflow.

1.  Click **Procurement** on the top link bar. On the Quick Launch, click **Purchase requisitions**, and then click **Purchase requisitions prepared by me**.

2.  Select a purchase requisition from the list. The requisition must have a status of **In review**.

3.  On the **Lines** FastTab, click **Purchase requisition line** \> **Actions**, and then **Recall**.

4.  On the **Workflow history details** page, click **Recall**.

5.  The status of the purchase requisition changes to **Draft**. You can modify the purchase requisition and resubmit it to workflow.

## See also

[Create and maintain purchase requisitions](create-and-maintain-purchase-requisitions.md)

[View purchase requisition history (Enterprise Portal)](view-purchase-requisition-history-enterprise-portal.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

