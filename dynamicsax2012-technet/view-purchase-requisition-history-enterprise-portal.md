---
title: View purchase requisition history (Enterprise Portal)
TOCTitle: View purchase requisition history (Enterprise Portal)
ms:assetid: 84af90dc-4308-4d32-91ef-305312bfd0a2
ms:mtpsurl: https://technet.microsoft.com/library/Hh271585(v=AX.60)
ms:contentKeyID: 36384216
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- EPPurchReqTableVersionList
- EPPurchReqViewDetails
- VersioningCompare
audience: Application User
ms.search.region: Global
---

# View purchase requisition history (Enterprise Portal) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can view and compare the change history for versions of a purchase requisition. When a purchase requisition is submitted for review, the purchase requisition is saved as the first version. Additional versions are created only when a change is made to a field on the purchase requisition header or lines. Version entries are also created when one or more fulfillment documents are generated for the requisition lines or, when the requisition purpose is consumption, if changes are made to the approved requisition lines during demand consolidation. For more information about requisition purposes, see [About purchase requisitions (Enterprise Portal)](about-purchase-requisitions-enterprise-portal.md).

You can view only the purchase requisitions that were created by you, are assigned to you, were created by another user on your behalf, or were created by or for users who report to you, unless you have a role with permission to see all requisitions.


> [!NOTE]
> <P>If the selected purchase requisition has no changes, the buttons are not available.</P>



## View versions of a purchase requisition

1.  Click **Procurement** on the top link bar, and then click **Purchase requisitions** \> **Purchase requisitions prepared by me** on the Quick Launch.

2.  On the **Action Pane**, on the **Review** tab, click **Purchase requisition versions** to view a list of all versions of the selected requisition. The most recent version is at the top of the list.
    
    –or–
    
    On the list page, select a purchase requisition, and then on the **Action Pane**, click **View**. On the **View purchase requisition** page, on the **Action Pane**, on the **Review** tab, click **Purchase requisition versions**.
    

    > [!NOTE]
    > <P>If the selected purchase requisition has never been submitted to workflow, the <STRONG>Purchase requisition versions</STRONG> button is not available.</P>



3.  To see the header and lines details for a version, select a version in the list, and then click **View details**.

## Compare versions of a purchase requisition

1.  Click **Procurement** on the top link bar, and then click **Purchase requisitions** \> **Purchase requisitions prepared by me** on the Quick Launch.

2.  Select a purchase requisition, and then on the **Action Pane**, click **View**.

3.  On the **View purchase requisition** page, on the **Action Pane**, on the **Review** tab, click **View purchase requisition versions**.
    

    > [!NOTE]
    > <P>If the selected purchase requisition has no changes, the button is not available.</P>



4.  Select any two versions to compare, and then click **Compare purchase requisition versions**.

5.  On the **Compare** page, click the change type on the left to view the old value and the new value for the selected versions.

## See also

[Create and maintain purchase requisitions](create-and-maintain-purchase-requisitions.md)

[About purchase requisitions (Enterprise Portal)](about-purchase-requisitions-enterprise-portal.md)

  


