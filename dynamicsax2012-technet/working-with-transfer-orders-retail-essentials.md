---
title: Working with transfer orders (Retail essentials)
TOCTitle: Working with transfer orders (Retail essentials)
ms:assetid: c94a1435-a9ec-4703-a38c-4f509bd5e09b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn859568(v=AX.60)
ms:contentKeyID: 63820142
ms.date: 12/17/2014
mtps_version: v=AX.60
---

# Working with transfer orders (Retail essentials) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to set up a transfer order. You can use transfer orders to handle items that are in transit between retail stores that are in the same company but different geographical sites. You can manage transfer orders from the **Transfer orders** form.

## Set up a transfer order

Use this procedure to set up a transfer order for items that must be transferred between retail store locations.

1.  Click **Retail essentials** \> **Inventory management** \> **Transfer orders**.

2.  In the upper pane, select a transfer order, or click **New** to create a transfer order.

3.  In the lower pane, select a transfer order line, or click **Add** to create a transfer order line.

4.  On the **Lines** tab, in the **Ship date** and **Receipt date** fields, change the shipment and receipt dates that are proposed for the transfer order lines, if changes are appropriate.

5.  Click **Inventory** to open a menu that you can use to reserve or pick items from transfer order lines before the transfer.

6.  Close the form to save your changes.

If you do not want to make a shipment or receipt for the full quantity on the lines, enter another quantity in the **Ship now** field on the **Ship now** tab or the **Receive now** field on the **Receive now** tab. For more information, see [Specifying overdelivery or underdelivery on transfer order lines](specifying-overdelivery-or-underdelivery-on-transfer-order-lines.md).

## Receive a transfer order

Use this procedure to receive a transfer order for items that have been transferred between retail store locations.

1.  Click **Retail essentials** \> **Inventory management** \> **Transfer orders**.

2.  In the upper pane, select the transfer order to update.

3.  Click **Posting** \> **Receive**.

4.  In the **Update** field, select an option. For example, to update the quantity that was previously entered in the **Receive now** field on the **Receive now** tab in the **Transfer orders** form, select **Receive now**.

5.  Click **OK** to close the form and save your changes.

6.  In the **Transfer orders** form, click **Print**, and then click **Transfer overview** to print the receipt papers for the receipt.

7.  On the **General** tab, select a print option, and then click **OK**.
    

    > [!NOTE]
    > <P>You cannot receive more than the shipped quantity.</P>


  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

