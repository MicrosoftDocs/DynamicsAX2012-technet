---
title: Follow up on purchase requisitions
TOCTitle: Follow up on purchase requisitions
ms:assetid: a9331013-3fbe-4351-915e-4ae54988a8ae
ms:mtpsurl: https://technet.microsoft.com/library/Gg243068(v=AX.60)
ms:contentKeyID: 36687398
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Follow up on purchase requisitions 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use these procedures to follow up on purchase requisitions. You can follow up on your own purchase requisitions and on purchase requisitions that were created by users who report to you directly or indirectly.

## Follow up on your own purchase requisitions

You can recall and resubmit purchase requisitions that you created. Depending on the status of the purchase requisitions, you can also modify and delete them.

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase requisitions** \> **Purchase requisitions prepared by me**.

2.  On the **Purchase requisitions prepared by me** list page, in the **Requester** field, select your name to view only purchase requisitions that include you as the requester.
    
    You can also extend the filter to display a subset of this information, such as to display only purchase requisitions that have a specific status. Select **Status** in the filter pane, and then enter a status. For more information about list page filters, see [Filter a list page](filter-a-list-page.md).

3.  Select a purchase requisition to view the summary details in the lower pane. To view the full details for the purchase requisition or to take action on the purchase requisition, complete the following tasks:
    
      - To view or modify a purchase requisition, double-click the purchase requisition to open the **Purchase requisitions** form.
    
      - To submit a purchase requisition for review, in the workflow message bar, click **Submit**. The purchase requisition status is changed to **In review**.
    
      - To recall a purchase requisition that has been submitted but not yet approved, in the workflow message bar, click **Actions** \> **Recall**. The purchase requisition status is changed to **Draft**. You can change the purchase requisition and then resubmit it for review.
    
      - To view the workflow history for a purchase requisition, in the workflow message bar, click **Actions** \> **View history**.

## Follow up on purchase requisitions for users who report to you

You can follow up on purchase requisitions that were created and submitted by users who report to you directly or through another user.


> [!NOTE]
> <P>Only the user who created a purchase requisition can change it. If you did not prepare the purchase requisition, you can modify it and perform actions only if a task is assigned to you in workflow.</P>



1.  Click **Procurement and sourcing** \> **Common** \> **Purchase requisitions** \> **Purchase requisitions prepared by me**.

2.  In the **Requester** field, select the name of the user whose purchase requisitions you want to view. The purchase requisitions are displayed as if you were the preparer.

3.  Select a purchase requisition to view the summarized details in the lower pane. To view the full details for the purchase requisition, double-click it to open the **Purchase requisitions** form.

## Follow up on all purchase requisitions

You can use the **All purchase requisitions** form to follow up on all purchase requisitions, regardless of the purchase requisition status or which user requested the items on the purchase requisitions.


> [!NOTE]
> <P>Only users who have been granted permission to view or manage all purchase requisitions have access to this form. Also, only the user who prepared a purchase requisition can change it. If you did not prepare the purchase requisition, you can modify it and perform actions only if a task is assigned to you in workflow.</P>



1.  Click **Procurement and sourcing** \> **Common** \> **Purchase requisitions** \> **All purchase requisitions**.

2.  Select how to view the information:
    
      - Select the name of a user in the **Requester** field to view a list of purchase requisitions that were created by or on behalf of that user.
    
      - Select **Status** in the filter pane and enter a status to view a list of purchase requisitions that have a specific status.
    
      - To view the workflow history for a selected purchase requisition, in the workflow bar, click **Actions** \> **View history**.

For more information about how to act on purchase requisition work items that are assigned to you from workflow, see [Complete, approve, or reject a purchase requisition](complete-approve-or-reject-a-purchase-requisition.md).

## See also

[About statuses for purchase requisitions](about-statuses-for-purchase-requisitions.md)

[Key tasks: Create and submit a purchase requisition](key-tasks-create-and-submit-a-purchase-requisition.md)

  


