---
title: (IND) Update excise registers for finished goods and by-products
TOCTitle: (IND) Update excise registers for finished goods and by-products
ms:assetid: cd5753b1-df36-4348-9ee9-032b0fcfc417
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn857500(v=AX.60)
ms:contentKeyID: 63396903
ms.date: 11/17/2014
mtps_version: v=AX.60
f1_keywords:
- production control
- Forms.SalesTableListPage
- Forms.ProdTableListPage
- Forms.InventJournalTable
- Forms.InventTransferOrders
- Forms.ExciseRegisterInquiry_IN
- update dsa register
- update excise register
- DSA quantity
- quantity of scrap
- without payment of duty
audience: Application User
ms.search.region: India
---

# (IND) Update excise registers for finished goods and by-products 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

You can generate and print an excise invoice for goods that are transported from a factory or a warehouse using a sales order, a transfer order, or a purchase return order. You can update the Daily stock account (DSA) and excise registers for finished goods, damaged goods, expired goods, and by-products.

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
<li><p>In the <strong>General ledger parameters</strong> form, in the <strong>Sales tax</strong> area, in the <strong>Apply India taxes</strong> field group, select the <strong>Excise</strong> check box and the <strong>Customs</strong> check box. For more information, see <a href="https://technet.microsoft.com/en-us/library/jj677901(v=ax.60)">(IND) General ledger parameters (modified form)</a>.</p></li>
<li><p>In the <strong>Released product details</strong> form, on the <strong>General</strong> FastTab in the <strong>Excise</strong> field group, select the <strong>Excise record type</strong> for the product. For more information, see <a href="https://technet.microsoft.com/en-us/library/aa615563(v=ax.60)">Released product details (form)</a>.</p></li>
<li><p>Select the <strong>DSA</strong> check box to update the DSA register for product transactions. The <strong>Excise record type</strong> is set to <strong>None</strong> to enable the <strong>DSA</strong> check box.</p></li>
<li><p>In the <strong>Tax reporting code</strong> form, create reporting codes for an excise invoice. For more information, see <a href="ind-set-up-tax-registration-numbers.md">(IND) Set up tax registration numbers</a>.</p></li>
</ol></td>
</tr>
</tbody>
</table>


## Create a production order and update excise registers for finished goods

You can update the excise registers and DSA when an excisable item is consumed for the production of finished goods.

To update excise registers and DSA, follow these steps:

1.  Click **Production control** \> **Common** \> **Production orders** \> **All production orders**. Create a production order.

2.  On the **Tax information** FastTab, in the **Excise** field group, select the **DSA** check box and specify the excise tariff code. For more information, see [Create production order (form)](https://technet.microsoft.com/en-us/library/aa497150\(v=ax.60\)).

3.  On the **Action pane**, in the **Process** field group, click **Estimate** to run an estimate of how much a production order will consume in material and capacity costs. For more information, see [Run an estimation](run-an-estimation.md).

4.  On the **Production order** tab, on the **Action pane**, in the **Process** field group, click **Release** to release production orders for the shop floor. For more information, see [Release production orders](release-production-orders.md).

5.  Click **Start** to send production orders into production on the shop floor. For more information, see [Start production orders](start-production-orders.md). A picking list journal with the default value for the excise record type is generated with raw materials to be consumed for production.

6.  On the **View** tab, in the **Journals** field group, click **Picking list**.

7.  In the **Production journal** form, click **Post** to post the picking list journal.

8.  On the **Schedule** tab, on the **Action pane**, in the **Production order** field group, click **Schedule operations** to schedule operations for a production order. For more information, see [Run operations scheduling](run-operations-scheduling.md).

9.  On the **Production order** tab, on the **Action pane**, in the **Process** field group, click **Report as finished** to report production orders as finished. For more information, see [Report production orders as finished](report-production-orders-as-finished.md).

The excise register RG23A part I register is updated with the quantity of items that are consumed. The updated excise register updates the DSA register with the quantity of finished goods that are produced. For more information, see [(IND) Update excise registers in production control](ind-update-excise-registers-in-production-control.md).

## Update RG 23 Part I for scrap or loss of raw material

To update the RG23 Part I excise register, follow these steps:

1.  Click **Inventory management** \> **Journals** \> **Item transactions** \> **Movement**. Create a movement journal.

2.  In the movement journal lines, on the **Tax information** tab, select **Scrap** as the **Disposal type**.

3.  In the **Excise record type** field, select the excise register to update the excise registers.

4.  Post the movement journal. For more information, see [Journal lines, Inventory movement (form)](https://technet.microsoft.com/en-us/library/aa598740\(v=ax.60\)).

5.  Click **General ledger** \> **Inquiries** \> **Tax** \> **India posted tax** \> **Excise** \> **Excise register**.

6.  Specify the ECC number and the excise register to display the excise transactions for RG23 registers.

7.  In the **Available** field, select **Disposal type** and then click **OK** to update the excise register with transactions as scrap or loss of raw material.

## Update DSA register with the quantity of damaged or finished goods

To update the DSA register, follow these steps:

1.  Click **Inventory management** \> **Journals** \> **Item transactions** \> **Movement**. Create a movement journal.

2.  In the movement journal lines, on the **Tax information** tab, select **Damage** or **Expiry** as the **Disposal type**, and then select the excise type.

3.  In the **Excise record type** field, select **None**, and then select the **DSA** check box to update the quantity of damaged or exported goods in the DSA register.

4.  Post the movement journal. For more information, see [Journal lines, Inventory movement (form)](https://technet.microsoft.com/en-us/library/aa598740\(v=ax.60\)).

5.  Click **General ledger** \> **Inquiries** \> **Tax** \> **India posted tax** \> **Excise** \> **Excise register**.

6.  Specify the ECC number and DSA register to display the excise transactions for.

7.  In the **Available** field, select **Disposal type** and click **OK** to update the DSA quantity for the damaged or expired goods.
    

    > [!NOTE]
    > <P>The DSA register is updated on a daily basis. In case of non-production on a particular date, an entry is created in the DSA register with a quantity of zero.</P>



## Update RG23A or RG23C register with quantity of scrap or capital goods

To update the RG23A or RG23C register, follow these steps:

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**. Create a sales order.

2.  On the **Line details** FastTab, on the **Tax information** tab, select the **Is scrap** check box to identify the item as scrap or capital goods.

3.  In the **Excise record type** field, select **RG23A**, **RG23C**, or **None** to update the RG23A, RG23C, or DSA registers with the scrap quantity.

4.  If required: Select the **DSA** check box to update the scrap quantity in the DSA register.

5.  Post the sales order. For more information, see [Create or edit a sales order](create-or-edit-a-sales-order.md).

6.  Click **General ledger** \> **Inquiries** \> **Tax** \> **India posted tax** \> **Excise** \> **Excise register**.

7.  Specify the ECC number and excise register to display the excise transactions for.

8.  In the **Available** field, select **Scrap quantity** and click **OK** to update the transactions from the sales order as scrap.
    

    > [!NOTE]
    > <P>When the item in the sales order line is identified as a by-product, then the RG23A and RG23C registers are updated with the by-product quantity. For more information, see <A href="create-a-by-product.md">Create a by-product</A>.</P>



## Update DSA register with the quantity of goods without payment of duty

To update the DSA register with quantity of goods without payment of duty, follow these steps:

1.  Click **Inventory management** \> **Periodic** \> **Transfer orders**. Create a stock transfer order.
    
    –or–
    
    Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**. Create an export order.

2.  Select the sales tax code that is marked as **Exempt** in the **Sales tax codes** form.

3.  Optional: View the calculated excise in the **Temporary sales tax transactions** form.

4.  Post the stock transfer order as a ship transfer order. For more information, see [(IND) Create and post shipment orders for transactions](ind-create-and-post-shipment-orders-for-transactions.md)
    
    –or–
    
    Post the export order and generate the invoice. For more information, see [(IND) Create an export sales order and post the confirmation order](ind-create-an-export-sales-order-and-post-the-confirmation-order.md).

5.  Click **General ledger** \> **Inquiries** \> **Tax** \> **India posted tax** \> **Excise** \> **Excise register**.

6.  Specify the ECC number and DSA register to display the excise transactions for.

7.  In the **Available** field, select **Is excise without duty** and click **OK** to update the DSA register with zero tax amount.

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
<li><p>Accountant</p></li>
<li><p>Accounting manager</p></li>
<li><p>Sales clerk</p></li>
<li><p>Purchase clerk</p></li>
<li><p>Sales manager</p></li>
<li><p>Purchasing manager</p></li>
<li><p>Production manager</p></li>
<li><p>Accounts payable coordinator</p></li>
<li><p>Accounts receivable administrator</p></li>
<li><p>Warehouse manager</p></li>
</ul></td>
</tr>
</tbody>
</table>

  


