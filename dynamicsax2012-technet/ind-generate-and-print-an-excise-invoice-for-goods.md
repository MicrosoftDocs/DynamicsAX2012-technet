---
title: (IND) Generate and print an excise invoice for goods
TOCTitle: (IND) Generate and print an excise invoice for goods
ms:assetid: aeb44b01-e5ca-4f1f-ac75-72e8cbef4133
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn876578(v=AX.60)
ms:contentKeyID: 63378994
ms.date: 11/13/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.SalesTableListPage
- Forms.PurchTableListPage
- Forms.InventTransferOrders
- excise invoice
- excise register
- Forms.TaxReportingCode_IN
- print an excise invoice
- generate an excise invoice
audience: Application User
ms.search.region: India
---

# (IND) Generate and print an excise invoice for goods 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

You can generate and print an excise invoice for goods that are transported from a factory or warehouse using a sales order, a stock transfer order, or a purchase return order. You can modify the assessable value to calculate the excise duty in a stock transfer order.

## Prerequisites

The following table shows the prerequisites that must be in place before you start.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Version</strong></p></td>
<td><p>Microsoft Dynamics AX 2012 R3 with cumulative update 8 (CU8)</p></td>
</tr>
<tr class="even">
<td><p><strong>Country/region</strong></p></td>
<td><p>The primary address for the legal entity must be in the following countries/regions: India</p></td>
</tr>
<tr class="odd">
<td><p><strong>Related setup tasks</strong></p></td>
<td><ol>
<li><p>In the <strong>General ledger parameters</strong> form, in the <strong>Sales tax</strong> area, in the <strong>Apply India taxes</strong> field group, select the <strong>Excise</strong> check box and <strong>Customs</strong> checkbox. For more information, see <a href="https://technet.microsoft.com/en-us/library/jj677901(v=ax.60)">(IND) General ledger parameters (modified form)</a>.</p></li>
<li><p>In the <strong>Exchange rate types</strong> form, set up the exchange rate types to be used for the tax calculation. For more information, see <a href="https://technet.microsoft.com/en-us/library/hh242857(v=ax.60)">Exchange rate types (form)</a>.</p></li>
<li><p>In the <strong>Released product details</strong> form, on the <strong>General</strong> FastTab in the <strong>Excise</strong> field group, select the <strong>Excise record type</strong> for the product. For more information, see <a href="https://technet.microsoft.com/en-us/library/aa615563(v=ax.60)">Released product details (form)</a>.</p></li>
<li><p>In the <strong>Enterprise tax registration numbers</strong> form, specify <strong>Excise</strong> for the <strong>Tax type</strong>, <strong>Company</strong> as the <strong>Registration number type</strong>, and the number sequence code for the <strong>Excise invoice</strong>.</p></li>
<li><p>In the <strong>Tax reporting code</strong> form, create reporting codes for an excise invoice. For more information, see <a href="ind-set-up-tax-registration-numbers.md">(IND) Set up tax registration numbers</a>.</p></li>
<li><p>In the <strong>Inventory and warehouse management parameters</strong> form, in the <strong>Stock transfer</strong> field group, select the <strong>Activate stock transfer</strong> check box.</p></li>
</ol></td>
</tr>
</tbody>
</table>


## Set up a tax reporting code

You can set up tax reporting codes to print the excise duty and excise cess in an excise invoice.

To setup tax reporting codes, follow these steps:

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **India** \> **Tax reporting code**.

2.  Click **New** and enter a description of the reporting code for the excise invoice.

3.  Click **Tax aggregate category**.

4.  Click **New** and then in the **Tax reporting aggregate category** field, enter a category for the excise reporting code.

5.  On the **Setup** FastTab, click **Add** and then select a **Tax component** for the category.

## Generate and print an excise invoice for a sales order

To generate and print an excise invoice for a manufacturer or a trader using a sales order, follow these steps:

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**. Create a new sales order and specify the item details. For more information, see [Create or edit a sales order](create-or-edit-a-sales-order.md).

2.  On the **Line details** FastTab, on the **Product** tab, select the **Warehouse** of the manufacturer or trader.

3.  On the **Setup** tab, select the sales tax group ID and the item sales tax group ID.

4.  On the **Tax information** tab, select an excise type for the sales order.

5.  Optional: You can change the location in the sales order and the address is also updated.

6.  On the **Invoice** tab, click **Invoice**, and then select the **Print excise invoice** and **Print invoice** check boxes to print the excise invoice and standard invoice for the sales order.

7.  Click **OK**. On the **Pick and pack** tab, click **Packing slip** to generate the packing slip for the sales order. On the **Sell** tab, click **Tax** \> **Sales tax** to view the calculated excise amount in the **Temporary sales tax transactions** form.

## Generate and print an excise invoice for a purchase return order

To generate and print an excise invoice for a manufacturer or a trader using a purchase return order, follow these steps:

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Click **Purchase order**, select a vendor account, and on the **General** FastTab, in the **Purchase type** field, select **Returned order**.

3.  Enter the Return Materials Authorization (RMA) number for the returned items and then click **OK** to create a return type purchase order.

4.  On the **Purchase order lines** FastTab, specify the item number and item quantity using a negative sign.

5.  On the **Line details** FastTab, on the **Product** tab, select the **Warehouse** of the manufacturer or trader.

6.  On the **Setup** tab, select the sales tax group ID and the item sales tax group ID.

7.  On the **Tax information** tab, select an excise type for the purchase order.

8.  Optional: You can change the location in the purchase return order and the address is also updated.

9.  On the **Purchase** tab, in the **Generate** group, click **Confirm** to confirm the purchase order for the returned items. Click **Sales tax** to view the calculated excise amount in the **Sales tax transactions** form.

10. On the **Invoice** tab, click **Invoice**, and then in the **Vendor invoice** form, enter the invoice number and description.

11. Click **Post**. Select the **Print excise invoice** and **Print invoice** check boxes to print the excise invoice and standard invoice for the purchase return order.

12. Click **Post**, and then on the **Receive** tab, click **Product receipt** to post the purchase order as a product receipt.

## Calculate excise duty and print an excise invoice for a stock transfer order

You can calculate excise duty based on the assessable value, generate and print an excise invoice for a manufacturer or a trader using a stock transfer order.

To calculate excise duty, generate and print an excise invoice using a stock transfer order, follow these steps:

1.  Click **Inventory management** \> **Periodic** \> **Transfer orders**.

2.  Create a stock transfer order.

3.  In the lower pane, on the **Tax information** tab, select the tax group ID, and item tax group ID.

4.  In the **From warehouse** and **To warehouse** field groups, select the **Excise type** of the manufacturer or trader.

5.  In the stock transfer order lines, you can modify the **Assessable value**, if required, which is calculated based on the value that you select in the **Price type** field.

6.  Click **Setup** \> **Tax** to view the excise amount that is calculated based on the assessable value, and then click **Close**.

7.  Click **Posting** \> **Ship transfer order** and on the **Overview** tab, select the **Print excise invoice** check box to print the excise invoice for the shipment order. For more information, see [(IND) Create and post shipment orders for transactions](ind-create-and-post-shipment-orders-for-transactions.md).

## Technical information for system administrators

If you don't have access to the pages that are used to complete this task, contact your system administrator and provide the information that is shown in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Security roles</strong></p></td>
<td><p>To perform this task, you must have the following roles:</p>
<ul>
<li><p>Sales agent</p></li>
<li><p>Sales manager</p></li>
<li><p>Accountant</p></li>
<li><p>Accounts receivable administrator</p></li>
<li><p>Purchasing agent</p></li>
<li><p>Purchasing manager</p></li>
<li><p>Accounts payable administrator</p></li>
<li><p>Warehouse manager</p></li>
</ul></td>
</tr>
</tbody>
</table>

  


