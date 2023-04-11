---
title: Create and print a credit note for customer invoices
TOCTitle: Create and print a credit note for customer invoices
ms:assetid: 110d56b9-c3b7-45e5-af5f-4132259b3511
ms:mtpsurl: https://technet.microsoft.com/library/Dn818480(v=AX.60)
ms:contentKeyID: 63172365
author: tonyafehr
ms.date: 10/15/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create and print a credit note for customer invoices 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


You can create an invoice with a negative amount; such an invoice is classified as a credit note. You must select the transactions that were previously posted for a customer invoice and then edit the transactions to create and print a credit note. With the exception of legal entities whose primary address is Germany, the title of the invoice is **Corrective invoice**.

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
<td><p>Related setup tasks</p></td>
<td><ol>
<li><p>Select a number sequence code for the corrective invoice reference in the <strong>Accounts receivable parameters</strong> form.</p></li>
<li><p>(DEU) Select the <strong>Print corrective invoice on sales credit memo</strong> check box, and specify the date from which the corrective invoices are printed instead of credit notes in the <strong>Legal entities</strong> form.</p>
<div class="alert">

> [!NOTE]
> <P>This control is available only for legal entities whose primary address is Germany.</P>


</div></li>
<li><p>Create and post a sales order invoice. For more information, see <a href="https://technet.microsoft.com/library/aa585863(v=ax.60)">Sales orders (form)</a>.</p></li>
</ol></td>
</tr>
</tbody>
</table>


## Create and print a credit note for a posted sales order

To create and print a credit note for returned items that are invoiced for a posted sales order, follow these steps:

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**. Select an invoiced sales order.

2.  On the **Sell** tab, click **Credit note**.

3.  Select the **Select all** check box to select all sales invoice transactions, or in the lower pane, select the **Mark** check box next to the sales order line that you want to correct the quantity of the returned items.

4.  Specify a reason code and a description for the selected sales order transaction.

5.  Click **OK** to update the selected sales invoice transaction with a negative amount for the returned items. On the **Invoice** tab, click **Invoice** to post the invoice for the sales order.

6.  In the **Quantity** field, select **Deliver now**, and then select the **Print invoice** check box to print the invoice.

7.  Click **OK** to post and print the credit note.

## Create and print a credit note for a return sales order

Create a return sales order for the returned items and specify a reason code for returning the items. After you create the return sales order, send the return order acknowledgement to the customer to return the items. Create an item arrival journal based on the returned items, and then post the journal to invoice them. You can generate a packing slip for the returned items and post the invoice for the return sales order to print the credit note.

## Create and post a return sales order

To create and post a return sales order, follow these steps:

1.  Click **Sales and marketing** \> **Common** \> **Return orders** \> **All return orders**.

2.  Create a new return sales order, and then specify a customer account number and reason code for returning the items.

3.  Click **OK**, and on the **Action Pane**, click **Return** \> **Find sales order**.

4.  Select the **Select all** check box to select all sales invoice transactions, or in the lower pane, select the **Mark** check box next to the sales order line that you want to correct the quantity of the returned items for.

5.  Select a reason code, and then enter a reason comment for the selected sales order transaction.

6.  Click **OK** to update the selected sales invoice transaction with the selected return items.

7.  On the **Action pane**, in the **Send** field group, click **Return order** to post the return sales order.

## Create and post an item arrival journal

To create and post an item arrival journal, follow these steps:

1.  Click **Inventory management** \> **Periodic** \> **Arrival overview**.

2.  On the **Overview** tab, in the **Setup name** field, select the return order type, and then click **Update** to update the overall item arrival list.

3.  In the **Receipts** pane, select the **Select for arrival** check box for a sales order, or in the **Lines** pane, select the check box for a sales order line that the return order is created for.

4.  Click **Start arrival** to generate an item arrival journal.

5.  Click **Inventory management** \> **Journals** \> **Item arrival** \> **Item arrival**.

6.  Select an item arrival journal, and then click **Lines** to enter the disposition codes for all of the journal lines.

7.  Click **Validate** to validate the journal lines, and then click **Post** to post the item arrival journal.

## Print the credit note for the return sales order

To print the credit note for the return sales order, follow these steps:

1.  Click **Sales and marketing** \> **Common** \> **Return orders** \> **Open return orders**.

2.  Select the return sales order for which the item arrival journal is posted.

3.  Click **Send** \> **Acknowledgement** to send the acknowledgement to the customer that the return order was created.

4.  Click **Generate**\>**Packing slip** to generate the packing slip for the returned items.

5.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**. Select the invoiced sales order.

6.  On the **Invoice** tab, click **Invoice** to post the credit note.

7.  In the **Quantity** field, select **Deliver now**, and then select the **Print invoice** check box to print the invoice.

8.  Click **OK** to post and print the credit note.

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
<td><p><strong>Configuration keys</strong></p></td>
<td><p>Click <strong>System administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Licensing</strong> &gt; <strong>License configuration</strong>. Select the <strong>Return orders</strong> configuration key.</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles and duties</strong></p></td>
<td><p>To perform this task, you must have the following roles:</p>
<ul>
<li><p>Accountant (LedgerAccountant)</p></li>
<li><p>Accounts payable clerk (VendInvoiceAccountsPayableClerk)</p></li>
<li><p>Accounts payable manager (VendInvoiceAccountsPayableManager)</p></li>
<li><p>Buying agent (TradeBuyingAgent)</p></li>
<li><p>Customer service manager (TradeCustomerServiceManager)</p></li>
<li><p>Customer service representative (TradeCustomerServiceRepresentative)</p></li>
<li><p>Production supervisor (ProdProductionSupervisor)</p></li>
<li><p>Project assistant (ProjProjectClerk)</p></li>
<li><p>Project manager (ProjProjectManager)</p></li>
<li><p>Purchasing agent (VendPurchasingAgent)</p></li>
<li><p>Purchasing agent - Public Sector (VendPurchasingAgent_PSN)</p></li>
<li><p>Purchasing manager (TradePurchasingManager)</p></li>
<li><p>Retail store manager (RetailStoreManager)</p></li>
<li><p>Sales clerk (TradeSalesClerk)</p></li>
<li><p>Sales manager (TradeSalesManager)</p></li>
<li><p>Sales representative (TradeSalesRepresentative)</p></li>
</ul>
<p>To create and print a credit note for a customer invoice, you must be a member of a security role that includes the following duties:</p>
<div class="caption">
</div>
<div class="tableSection">
<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Duty</p></th>
<th><p>Name</p></th>
<th><p>Procedure</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>PurchOrderToInvoiceProgressInquire</p></td>
<td><p>Inquire into purchase order to invoice progress</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>PurchOrderMaintain</p></td>
<td><p>Maintain purchase orders</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>MCRReturnSalesReturnOrderMaintain</p></td>
<td><p>Maintain sales return order</p></td>
<td><p>Create and print a credit note for a return sales order</p></td>
</tr>
<tr class="even">
<td><p>ReturnSalesReturnOrderProgressInquire</p></td>
<td><p>Inquire into sales return order progress</p></td>
<td><p>Create and print a credit note for a return sales order</p></td>
</tr>
<tr class="odd">
<td><p>ReturnAcknowledgementApprove</p></td>
<td><p>Approve return acknowledgement</p></td>
<td><p>Create and print a credit note for a return sales order</p></td>
</tr>
<tr class="even">
<td><p>ReturnSalesReturnOrderMaintain</p></td>
<td><p>Maintain sales return order</p></td>
<td><p>Create and print a credit note for a return sales order</p></td>
</tr>
<tr class="odd">
<td><p>KanbanExecutionServiceReceiptsMaintain</p></td>
<td><p>Maintain service receipts kanban execution</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>KanbanSchedulePurchaseOrdersMaintain</p></td>
<td><p>Maintain kanban purchase orders schedule</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>PurchOrderApprove</p></td>
<td><p>Approve purchase order</p></td>
<td><p></p></td>
</tr>
</tbody>
</table>

</div></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To create and print a credit note for a customer invoice, you must be a member of a security role that includes the following privileges:</p>
<div class="caption">

</div>
<div class="tableSection">
<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Privilege</p></th>
<th><p>Name</p></th>
<th><p>Procedure</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>PurchTableDetailsMaintain</p></td>
<td><p>Maintain purchase order details</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>PurchTableDetailsView</p></td>
<td><p>View purchase order details</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>MCRCreateRMAMaintain</p></td>
<td><p>Maintain new RMA's</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>MCRReturnTableDetailView</p></td>
<td><p>View return order details</p></td>
<td><p>Create and print a credit note for a return sales order</p></td>
</tr>
<tr class="odd">
<td><p>ReturnTableDetailsView</p></td>
<td><p>View return order details</p></td>
<td><p>Create and print a credit note for a return sales order</p></td>
</tr>
<tr class="even">
<td><p>ReturnTableDetailsMaintain</p></td>
<td><p>Maintain return order details</p></td>
<td><p>Create and print a credit note for a return sales order</p></td>
</tr>
</tbody>
</table>

</div></td>
</tr>
</tbody>
</table>

  


