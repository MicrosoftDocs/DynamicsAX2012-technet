---
title: Set up parameters to post an intercompany order
TOCTitle: Set up parameters to post an intercompany order
ms:assetid: b86649c1-a99f-47ae-9a0e-2a22035e355a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa572251(v=AX.60)
ms:contentKeyID: 36059111
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- intercompany order
- generate order
- place intercompany order
- set up parameter
- post an order
---

# Set up parameters to post an intercompany order [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When an intercompany customer invoice is posted, you can set it up to post both the intercompany purchase order and the original customer invoice automatically.


> [!NOTE]
> <P>Before you perform this procedure, set up the print management in your organization to point to the correct invoice printer. This will make sure that the invoice for the original sales order is printed on the correct printer.</P>



You must set up the following parameters:

1.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**. Double-click the sales order that you want to work with.

2.  On the sales order, on the **Action Pane**, select **Header view** and then click the **Intercompany settings** FastTab and open it.

3.  Go to the **Action Pane** on the **Sales order** tab and then click **Edit**.

4.  Go back to the **Intercompany settings** FastTab and select **Direct delivery** to enable direct delivery throughout the intercompany chain (all orders).

5.  Click **CTRL+S** to save the sales order with the new setting. Then click **Close** to close the sales order.

6.  Click **Procurement and sourcing** \> **Common** \> **Vendors** \> **All vendors**. On the **General** tab, click **Intercompany**.

7.  In the **Intercompany** form, click the **Purchase order policies** link. In the **Intercompany purchase order (direct delivery)** field group, select **Post invoice automatically** and remove the check mark from the **Print invoice automatically** field.

8.  In the **Original sales order (direct delivery)** field group, select the **Post invoice automatically** field and the **Print invoice automatically** field.


> [!NOTE]
> <P>With these parameters set, the intercompany purchase order is not printed, but the original sales order is.</P>


  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

