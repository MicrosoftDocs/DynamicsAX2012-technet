---
title: View or modify purchase requisition information on a purchase order
TOCTitle: View or modify purchase requisition information on a purchase order
ms:assetid: db0a7935-c848-4c02-8d11-5417ce5d35a1
ms:mtpsurl: https://technet.microsoft.com/library/Gg243189(v=AX.60)
ms:contentKeyID: 36687402
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- purchase order
- modify purchase requisition
audience: Application User
ms.search.region: Global
---

# View or modify purchase requisition information on a purchase order 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

After a purchase order has been created from a purchase requisition, you can use this procedure to view or modify the purchase requisition information on the purchase order.

You process purchase orders that were created from purchase requisitions just as you process other purchase orders.


> [!NOTE]
> <P>You can delete a purchase order line only if it has not been confirmed. When you delete an unconfirmed purchase order line, the purchase order reference on the purchase requisition line is also deleted. If you delete an entire purchase order, the purchase order reference is deleted on all purchase requisition lines. In both cases, the status of the purchase requisition changes to <STRONG>Approved</STRONG> and you can generate another purchase order for the purchase requisition.</P>



1.  Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  On the **All purchase orders** list page, double-click a purchase order that was created from a purchase requisition.
    

    > [!NOTE]
    > <P>The purchase requisition reference is displayed only at the purchase order line level. For information about how to view line details for a purchase order, see step 5 in this procedure.</P>



3.  To view the header information for the purchase order, in the **Purchase order** form, on the **Action pane**, on the **Purchase order** tab, in the **Show** group, click **Header view**. Then do any of the following:
    
      - To view the requester who requested the items on the purchase order, look on the **Setup** FastTab, in the **Requester** field. If this field is blank, multiple users have requested the items that are included on this purchase order.
    
      - To view the attention information for the purchase order, look on the **Address** FastTab, in the **Attention information** field. If this field is blank, multiple types of attention information have been used for this purchase order.

4.  To modify header information for the purchase order, in the **Purchase order** form, on the **Action pane**, on the **Purchase order** tab, click **Edit**. Then do any of the following:
    
      - To modify the requester for the purchase order, on the **Setup** FastTab, in the **Requester** field, select a requester.
    
      - To add attention information for the purchase order, on the **Address** FastTab, in the **Attention information** field, type the attention information.
    

    > [!NOTE]
    > <P>If change management is enabled, you must request permission to change the purchase order before you can modify it. On the <STRONG>Action Pane</STRONG>, on the <STRONG>Purchase order</STRONG> tab, in the <STRONG>Maintain</STRONG> group, click <STRONG>Request change</STRONG>.</P>



5.  To view the line details for the purchase order, in the **Purchase order** form, on the **Action pane**, on the **Purchase order** tab, in the **Show** group, click **Line view**. Select a purchase order line, and then click the **Line details** FastTab. At the bottom of the lower pane, do any of the following:
    
      - Click the **General** tab to view or modify the reference to the purchase requisition in the **Purchase requisition** field.
    
      - Click the **Address** tab to view or modify the delivery address or the requester for the purchase order line.
    
      - Click the **Financial dimensions** tab to view or modify the financial dimensions that are assigned to the purchase order line.

## See also

[About statuses for purchase requisitions](about-statuses-for-purchase-requisitions.md)

[Create purchase orders manually from purchase requisitions](create-purchase-orders-manually-from-purchase-requisitions.md)

  


