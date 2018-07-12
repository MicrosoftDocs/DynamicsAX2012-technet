---
title: Copy purchase requisitions
TOCTitle: Copy purchase requisitions
ms:assetid: df7efe77-35b3-454b-a08b-b6731d547b84
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh335179(v=AX.60)
ms:contentKeyID: 36687403
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Copy purchase requisitions 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If you create purchase requisitions that are similar to each other, or request the same items regularly, you can copy an existing purchase requisition so that you do not have to reenter all the information. You can also copy purchase requisition lines from existing purchase requisitions and add them to your current purchase requisition. You can modify information in the copied purchase requisition before you submit it for approval.


> [!NOTE]
> <P>You can copy only from purchase requisitions for which you are the preparer. In Microsoft Dynamics AX 2012 R2, the requisition that you copy to must have the same requisition purpose as the requisition that you copy from. For more information about requisition purposes, see <A href="about-purchase-requisitions.md">About purchase requisitions</A>.</P>



Most of the information in the header of the existing purchase requisition is copied to the new purchase requisition, such as the purchase requisition name and business justification. The requested date of the new requisition is assigned by default as either today’s date or, if there is lead time assigned to an item, a date in the future. You are assigned as the preparer.

If the requisition purpose is consumption and if you copy lines that reference an item number in Microsoft Dynamics AX, then the prices, discounts, and line charges are recalculated, based on the latest master data and trade and purchase agreements. If you copy lines that do not reference an item number in Microsoft Dynamics AX, then the prices, discounts, and charges are copied directly from the purchase requisition lines. Purchase requisition lines that reference items from an external vendor catalog cannot be copied and are ignored by the copy process. If the requisition purpose is replenishment, the site and warehouse are not copied to the new requisition.

## Copy a purchase requisition

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase requisitions** \> **Purchase requisitions prepared by me**.

2.  On the **Purchase requisitions prepared by me** list page, select the purchase requisition that you want to copy.

3.  On the **Action Pane**, on the **Purchase requisition** tab, in the **Copy** group, click **Copy**.

4.  In the **Purchase requisitions** form, review the header and line data. After you make any modifications that you need, you can submit the purchase requisition for review.
    
    For more information about how to create and submit a purchase requisition for review, see [Key tasks: Create and submit a purchase requisition](key-tasks-create-and-submit-a-purchase-requisition.md).

## Copy purchase requisition lines

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase requisitions** \> **Purchase requisitions prepared by me**.

2.  On the **Purchase requisitions prepared by me** list page, double-click a purchase requisition that is in a draft status or create a new purchase requisition.

3.  In the **Purchase requisitions** form, on the **Action Pane**, on the **Purchase requisition** tab, click **Copy lines**.

4.  In the **Purchase requisition - copy lines** form, on the **Purchase requisitions** tab, select the purchase requisition that contains the lines that you want to copy. In the lower pane, select the check box next to the lines that you want to copy. You can also select the **Select all** check box next to the purchase requisition to select all lines on the purchase requisition.

5.  Select the **Delete existing purchase requisition lines** check box to delete any existing lines on your current purchase requisition and replace them with the new lines that you select. Clear the check box to keep the existing lines in the purchase requisition and add the selected lines.

6.  On the **Show selected transactions** tab, view the list of purchase requisition lines that you have selected to copy, and then click **OK** to copy them to your current purchase requisition.

## See also

[About purchase requisitions](about-purchase-requisitions.md)

[Copy purchase - Purchase requisition (form)](https://technet.microsoft.com/en-us/library/hh242898\(v=ax.60\))

[Purchase requisitions (form)](https://technet.microsoft.com/en-us/library/hh209453\(v=ax.60\))

[Purchase requisitions - lines (form)](https://technet.microsoft.com/en-us/library/hh209354\(v=ax.60\))

[Purchase requisitions (list page)](https://technet.microsoft.com/en-us/library/hh227485\(v=ax.60\))

[Key tasks: Create and submit a purchase requisition](key-tasks-create-and-submit-a-purchase-requisition.md)

  


