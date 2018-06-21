---
title: 'Key tasks: Prepayments'
TOCTitle: 'Key tasks: Prepayments'
ms:assetid: 047ed3e2-c3a7-4e7e-bc9e-9a8ce6ec6f11
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242104(v=AX.60)
ms:contentKeyID: 36055947
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- advance
- cancel prepayment
- create prepayment
- partial prepayment
- post prepayment
- prepayment
- reverse prepayment
- settle prepayment
- vendor advance
- prepayments
---

# Key tasks: Prepayments [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

With a prepayment invoice, you can make advance invoice payments to a vendor before the purchase order is fulfilled. For example, a vendor might require a prepayment for specific goods or services. After the prepayment is paid, your legal entity can later apply the prepayment to one or more vendor invoices to offset the amount that was already paid.

## What do you want to do?

Learn more about...

Define a prepayment account

Create a purchase order that has a prepayment

Create a prepayment

Post and settle payments against a prepayment

Post the vendor invoice

Apply a prepayment against a vendor invoice

Reverse the application of a prepayment

Find form help

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[About prepayments and prepayment journal vouchers](about-prepayments-and-prepayment-journal-vouchers.md)

## Define a prepayment account

1.  Click **Inventory management** \> **Setup** \> **Posting** \> **Posting**. Click the **Purchase order** tab.

2.  Select the **Prepayment** option in the **Select** pane.

3.  Click **Add** to add a posting type, and then select values in the fields. For prepayments, select **Category** in the **Item code** field, and then select values in the **Category relation**, **Account code**, and **Main account** fields. For more information, see [Item posting (form)](https://technet.microsoft.com/en-us/library/aa589971\(v=ax.60\)).

Back to top

## Create a purchase order that has a prepayment

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  On the **Action Pane**, click **Purchase order** to create a purchase order.

3.  Select a vendor account in the **Create purchase order** form. Enter any additional header information, and then click **OK**.

4.  In the **Purchase order lines** grid of the **Purchase order** form, enter other information for the purchase order, including the item number, quantity, and unit price. For more information, see [Create a purchase order](create-a-purchase-order.md).

5.  On the **Action Pane**, click the **Purchase** tab, and then click **Prepayment**.

6.  Enter information for the prepayment, including a description, the value of the prepayment, whether the prepayment is a fixed amount or a percentage, and a prepayment category ID. For more information, see [Prepayment (form)](https://technet.microsoft.com/en-us/library/hh227657\(v=ax.60\)).

7.  Click **Save**.

8.  In the **Purchase order** form, on the **Action Pane**, click the **Purchase** tab, and then click **Confirm** to confirm the purchase order.

Back to top

## Create a prepayment

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Double-click a confirmed purchase order that has a prepayment definition.

3.  On the **Action Pane**, click the **Invoice** tab. In the **Generate** group, click **Prepayment invoice**. The **Vendor invoice** form opens.

4.  Enter information for the prepayment invoice, including the invoice number. You cannot change quantities for a prepayment invoice.

5.  On the **Action Pane**, click **Post** to post the prepayment invoice, and then click **Post** in the form that is displayed. For more information, see [Key tasks: Vendor invoices](key-tasks-vendor-invoices.md).

Back to top

## Post and settle payments against a prepayment

Follow these steps to post and a settle a single payment against a prepayment.

1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Click **New** to create a payment journal.

3.  Enter information for the payment journal and then click **Lines**.

4.  In the **Journal voucher** form, select the account, offset account, and other journal voucher details. For more information, see [Journal voucher - Vendor payment journal (form)](https://technet.microsoft.com/en-us/library/aa599011\(v=ax.60\)).

5.  Click **Functions**, and then click **Settlement**. The **Settle open transactions** form opens.

6.  Select the **Mark** check box to mark the prepayment transaction for settlement, and then close the form.

7.  In the **Journal voucher** form, click **Post**, and then click **Post**.

Back to top

## Post the vendor invoice

Follow these steps to create and post a vendor invoice for the purchase order.

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Double-click a purchase order that includes a prepayment. The **Purchase order** form opens.

3.  On the **Action Pane**, click the **Invoice** tab. In the **Generate** group, click **Invoice**. The **Vendor invoice** form opens.

4.  Enter information for the invoice, including the invoice number.

5.  On the **Action Pane**, click **Post** to post the prepayment invoice, and then click **Post** in the form that is displayed. For more information, see [Key tasks: Vendor invoices](key-tasks-vendor-invoices.md).

Back to top

## Apply a prepayment against a vendor invoice

Follow these steps to apply a prepayment against a vendor invoice.

1.  Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.

2.  Double-click the vendor for the vendor invoice that you created. The **Vendors** form opens.

3.  On the **Action Pane**, click the **Invoice** tab, and then click **Apply prepayment**.

4.  In the **Select the invoice to apply the prepayments to** grid, select the vendor invoices to apply the prepayments to. In the **Select prepayments to apply** grid, select the prepayment invoices to apply.

5.  Click **Apply prepayments**.

Back to top

## Reverse the application of a prepayment

Follow these steps to reverse the application of a prepayment that was made against a vendor invoice.

1.  Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.

2.  Select the vendor for the vendor invoice that you created.

3.  On the **Action Pane**, click **Edit**.

4.  On the **Action Pane**, click the **Invoice** tab, and then click **Reverse prepayment application**.

5.  In the **Select the invoice to reverse the prepayments from** grid, select the vendor invoices to reverse the prepayments from. In the **Select prepayments to reverse** grid, select the prepayments to reverse.

6.  Click **Reverse prepayment application**.

Back to top

## Find form help

[Apply prepayments (form)](https://technet.microsoft.com/en-us/library/hh242745\(v=ax.60\))

[Prepayment (form)](https://technet.microsoft.com/en-us/library/hh227657\(v=ax.60\))

[Reverse prepayment application (form)](https://technet.microsoft.com/en-us/library/hh209022\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

