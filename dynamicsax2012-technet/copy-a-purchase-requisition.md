---
title: Copy a purchase requisition
TOCTitle: Copy a purchase requisition
ms:assetid: 464e2460-bb9f-4bf3-a993-c1331472949b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh271517(v=AX.60)
ms:contentKeyID: 36384149
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- PurchReqCopyLines
audience: Application User
ms.search.region: Global
---

# Copy a purchase requisition 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If you create similar purchase requisitions or request the same items regularly, you can copy an existing purchase requisition so that you do not have to re-enter all the information. You can still modify information in the copied purchase requisition before you submit it for approval.


> [!NOTE]
> <P>You can copy only from purchase requisitions for which you are the preparer. In Microsoft Dynamics AX 2012 R2, the requisition that you copy to must have the same requisition purpose as the requisition that you copy from. For more information about requisition purposes, see <A href="about-purchase-requisitions-enterprise-portal.md">About purchase requisitions (Enterprise Portal)</A>.</P>



Most of the information in the header of the existing purchase requisition will be copied to the new purchase requisition. The requested date of the new requisition is today’s date, and you are the preparer.

If the requisition purpose is consumption and if you copy lines that reference an item number in Microsoft Dynamics AX, then the prices, discounts, and line charges are recalculated based on the latest master data and trade and purchasing agreements. If you copy lines that do not reference an item number in Microsoft Dynamics AX, then the prices, discounts, and charges are copied directly from the purchase requisition lines. If the requisition purpose is replenishment, the site and warehouse are not copied to the new requisition.

1.  Click **Procurement** on the top link bar. On the Quick Launch, click **Purchase requisitions**, and then click **Purchase requisitions prepared by me** to view the requisitions that you have permission to copy from.

2.  Select the purchase requisition to copy. On the **Action Pane**, click **Copy**.
    

    > [!NOTE]
    > <P>When the requisition purpose is consumption, only internal catalog items and non-catalog items are copied. To add products from an external catalog, you must add them manually. When the requisition purpose is replenishment, only products that are stocked and released to the specified legal entity are available.</P>



3.  On the **Edit purchase requisition** page, modify the information, as necessary, in the new purchase requisition.

4.  Click **Save and close**, and then you can submit the purchase requisition to the workflow system. For more information about how to create purchase requisitions, see [Create and maintain purchase requisitions](create-and-maintain-purchase-requisitions.md).

## See also

[About purchase requisitions (Enterprise Portal)](about-purchase-requisitions-enterprise-portal.md)

[Create and maintain purchase requisitions](create-and-maintain-purchase-requisitions.md)

[View workflow history for a purchase requisition](view-workflow-history-for-a-purchase-requisition.md)

  


