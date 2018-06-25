---
title: Set up charges on intercompany orders
TOCTitle: Set up charges on intercompany orders
ms:assetid: 3783acf2-10cc-45ba-a698-ca992a405487
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa570131(v=AX.60)
ms:contentKeyID: 36056608
ms.date: 07/08/2014
mtps_version: v=AX.60
---

# Set up charges on intercompany orders [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can set up charges to be added to intercompany orders. When a charge is added to an intercompany sales order, it is automatically synchronized to the intercompany purchase order. This works both ways—from the intercompany sales order to the purchase order and the other way around.

You can also use charges to add a profit to an intercompany sales order by defining the charge as an intercompany percentage.

When you set up charges to be applied to intercompany orders, you enable the calculation of internal profit for an intercompany sales order from the net amount of the original sales order. You might want to do this if your intercompany vendor sells to you at cost price. The following procedure describes how to do this for intercompany customers. You can use the same procedure for vendors.

1.  Click **Accounts receivable** \> **Setup** \> **Charges** \> **Customer charge groups**.

2.  Create a charges group.

3.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**. Double-click a customer account. On the Action Pane, click the **Customer** tab, and then click the **Sales order** FastTab.

4.  Click **Edit** on the Action Pane to enable edits to the field. In the **Charges group** field, select the intercompany charges group that you set up in step 2.

5.  Click **Accounts receivable** \> **Setup** \> **Charges** \> **Auto charges**.

6.  Set up the charges by filling in the relevant fields.

7.  In the **Customer relation** field, select the intercompany charges group that you set up in step 2.

8.  On the **Lines** FastTab, in the **Category** field, select **Intercompany percent**.

## See also

[About synchronization of charges](about-synchronization-of-charges.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

