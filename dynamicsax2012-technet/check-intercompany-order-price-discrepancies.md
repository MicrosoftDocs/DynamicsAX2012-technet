---
title: Check intercompany order price discrepancies
TOCTitle: Check intercompany order price discrepancies
ms:assetid: e0f902f9-be18-49c5-ae92-ca796d5ca0ef
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa551337(v=AX.60)
ms:contentKeyID: 36059707
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Check intercompany order price discrepancies 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use this procedure to check for price discrepancies on intercompany orders.

1.  Click **Procurement and sourcing** \> **Periodic** \> **Clean up** \> **Check intercompany order price discrepancies**.

2.  Set up a batch job, if you need to, and then click **OK** to check the prices and discounts for intercompany sales orders and purchase orders. Otherwise, click **Cancel** to close the form without performing the check.
    

    > [!TIP]
    > <P>If there are any synchronization issues or issues with the prices, these will be listed in an Infolog that will be displayed. You can print the Infolog for reference.</P>



3.  On the Infolog, double-click the relevant line to open the order in the current legal entity. Open the order in the related legal entity by clicking **Intercompany**, and then **Intercompany purchase order** or **Intercompany sales order**.
    

    > [!NOTE]
    > <P>To allow an update of the intercompany order:</P>
    > <OL>
    > <LI>
    > <P>Click <STRONG>Accounts receivable</STRONG> &gt; <STRONG>Common</STRONG> &gt; <STRONG>Customers</STRONG> &gt; <STRONG>All customers</STRONG>. On the Action Pane, click the <STRONG>General</STRONG> tab, and then click <STRONG>Intercompany</STRONG>.</P>
    > <LI>
    > <P>In the <STRONG>Intercompany</STRONG> form, click <STRONG>Purchase order policies</STRONG> or <STRONG>Sales order policies</STRONG>. Select <STRONG>Allow price edit</STRONG> and <STRONG>Allow discount edit</STRONG> in both areas.</P></LI></OL>



4.  Open the relevant intercompany order where you want to keep the price.

5.  For each order line, change the **Unit price** field for the line, and then change it back to the original value. Change the **Discount** field for the line back and forth, and change the relevant **Charges on purchases** or **Sales charges** fields back and forth. Changing the values back and forth will trigger a synchronization of the prices, discounts, and charges from this intercompany order line to the referenced intercompany order line, so they will be automatically aligned.
    

    > [!NOTE]
    > <P>This synchronization is valid only if the intercompany sales order has not been invoiced. If the intercompany sales order has been invoice-posted and a customer invoice journal has been created, changes must be performed directly on the intercompany purchase order lines by setting the prices, discounts, and charges equal to those on the intercompany customer invoice journal. If this is not done, the intercompany purchase order cannot be invoice-posted, because there will be a mismatch in the order totals.</P>



6.  Repeat the procedure until all intercompany purchase and sales orders are synchronized.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

