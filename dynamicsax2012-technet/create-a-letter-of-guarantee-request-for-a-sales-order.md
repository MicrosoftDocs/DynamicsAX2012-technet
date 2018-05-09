---
title: Create a letter of guarantee request for a sales order
TOCTitle: Create a letter of guarantee request for a sales order
ms:assetid: 8076b3f8-e224-49c5-a43a-b24867ec9a94
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh209302(v=AX.60)
ms:contentKeyID: 36058341
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Create the letter of guarantee request for a sales order
- Letter of guarantee request for a sales order
---

# Create a letter of guarantee request for a sales order 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A letter of guarantee can be issued for a sales order transaction between a principal and a beneficiary. After the sales order is created, the principal can create a letter of guarantee request for the customer and submit it to the bank. When the bank approves the request, the letter of guarantee is issued to the beneficiary. For more information, see [About letter of guarantee](about-letter-of-guarantee.md) and [Activate the letter of guarantee](activate-the-letter-of-guarantee.md).

## Create a sales order

Use the **Create sales order** form to create a sales order with the **Bank document type** as **Letter of guarantee**.

1.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Click **Sales order** to create a new sales order.

3.  In the **Customer account** field, select the customer who has requested the letter of guarantee.

4.  Click the **General** FastTab, and then in the **Bank document type** field, select **Letter of guarantee**. Enter any other required details.

5.  Click **OK** to close the **Create sales order** form and return to the **Sales order** form.

## Create a letter of guarantee request for a sales order

You can request a letter of guarantee for a customer using the **Sales order** form. After you make a request, you must submit the request to the bank for approval.

1.  In the **Sales order** form, on the **Sales order lines** FastTab, click **Add line** to create a sales order line for an item and specify the following: **Item number**, **Quantity**, **Unit**, and **Unit price**.

2.  On the Action Pane, click the **Manage** tab.

3.  In the **Bank document** group, click **Letter of guarantee** to open the **Letter of guarantee** form. For information about how to create the request, submit it to the bank, and issue the letter of guarantee to the beneficiary, see [Request and issue the letter of guarantee](request-and-issue-the-letter-of-guarantee.md)

4.  Close the forms to save your changes.

## See also

[Create a letter of guarantee request for a new project](create-a-letter-of-guarantee-request-for-a-new-project.md)

[Increase or decrease the letter of guarantee value](increase-or-decrease-the-letter-of-guarantee-value.md)

[Liquidate, extend, or cancel a letter of guarantee](liquidate-extend-or-cancel-a-letter-of-guarantee.md)

[Letter of guarantee (form)](https://technet.microsoft.com/en-us/library/hh227662\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

