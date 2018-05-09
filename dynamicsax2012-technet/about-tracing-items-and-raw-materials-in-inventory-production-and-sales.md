---
title: About tracing items and raw materials in inventory, production, and sales
TOCTitle: About tracing items and raw materials in inventory, production, and sales
ms:assetid: 3c21d742-7938-4cc8-9054-3419c335f2ce
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn313035(v=AX.60)
ms:contentKeyID: 54936278
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- trace
- tracing
- track
- Forms.InventTrackingDimTracing
- MsDynAx060.Forms.InventTrackingDimTracing
---

# About tracing items and raw materials in inventory, production, and sales 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic describes how you can use item tracing to identify where items or raw materials have been used, are being used, or will be used in production and sales processes. This functionality is available in the **Item tracing** form.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 6 for AX 2012 R2.</P>



## What is item tracing?

Item tracing is a business intelligence tool that provides visibility into the source and destination of items and raw materials in the supply chain. Manufacturers can trace items, raw materials, or ingredients back to the vendor, and forward through the production and sale of the finished product. Item tracing helps manufacturers comply with regulatory requirements, and helps quality officers and production managers analyze and take action to address variances in the quality of products and materials. For example, manufacturers can use item tracing to perform the following investigations:

  - Identify the amount of an item or raw material that is currently in inventory, and where it is stored.

  - Determine how much of the item or raw material has been shipped, and to which customers.

  - Identify any planned shipments that include the item or raw material.

  - Locate production orders that use the item or raw material and that are planned, in progress, or reported as finished.

  - Find out where the item or raw material was purchased.

  - Investigate where an item or raw material was consumed in the production of another item.

## What can I trace, and are there any limitations?

You can trace historical inventory transactions for items and raw materials based on an item number and a tracking dimension, such as a serial number, batch number, or vendor batch number. If an item or raw material doesn’t have a tracking dimension assigned to it, you can’t trace it.

Because tracing is based on inventory transactions, there are some limitations when tracing items. For example, there are limitations related to transactions for projects, fixed assets, and retail. Additionally, co-products are shown in the trace details, but by-products are not included.

## What criteria can I specify for an item trace?

The criteria that are required for an item trace are the item number, a tracking dimension such as a batch number or serial number, and the direction. The following table describes the criteria that you can use in an item trace.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Field group</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Item number</strong></p></td>
<td><p>Enter the identifier for the item or raw material that you’re tracing.</p></td>
</tr>
<tr class="even">
<td><p><strong>Product dimensions</strong></p></td>
<td><p>Optional: Trace specific aspects of the product definition, such as a configuration, size, color, or style.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Tracking dimensions</strong></p></td>
<td><p>Enter a batch number, vendor batch number, or serial number tracking dimensions. When you use a batch number as criteria, the vendor batch number is displayed if you’ve captured that information.</p></td>
</tr>
<tr class="even">
<td><p><strong>Storage dimensions</strong></p></td>
<td><p>Optional: Trace items that have been stored in a specific location.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Period</strong></p></td>
<td><p>Optional: Enter dates to limit the trace to a specific period. The trace details will display only documents and transactions that were created between these dates.</p></td>
</tr>
<tr class="even">
<td><p><strong>Forward or backward</strong></p></td>
<td><p>Select the direction for the trace. You can trace forward or backward:</p>
<ul>
<li><p><strong>Backward</strong> – Trace downstream to identify the source, the quantity that remains on hand, and any production orders that are at least partially reported as finished.</p></li>
<li><p><strong>Forward</strong> – Trace upstream to identify the destination. You can find the sales orders and the customers to whom the traced item or raw material has been at least partially shipped.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## What information is included in the trace details?

The results of a trace are displayed in chronological order in the tree on the **Details** FastTab in the **Item tracing** form. The order varies, depending on the trace direction. The details include all transactions from the purchase of the item from the vendor to the sale of it to the customer. Trace results also include interim products that are related to the item or the tracking dimension that was specified in the trace criteria. The top node shows the quantity of the item, in the inventory unit, that remains on hand according to the storage dimensions that were specified in the trace criteria.


> [!NOTE]
> <P>The trace details are a snapshot of the information that was available when the trace was performed. The trace details are not updated if the information changed after the trace was performed.</P>



## Why don’t some nodes contain any details?

To reduce the amount of information in the trace details, only the node for the first instance of the item or raw material includes details. If a selected node doesn’t contain details, you can view the node that does by clicking **Go to traced line**. You can return to the node you left by clicking **Go back**.

## Can I view only a particular type of document? For example, can I view only production orders, customers, or vendors?

Yes, you can open list pages that include only a particular type of document or transaction from the trace details. These pages are available on the **Action Pane** in the **Item**, **Sales**, **Purchase**, **Production**, and **Quality** groups. For example, to view a list of the vendors in the trace details, click **Vendors**. The list pages summarize the documents or transactions from the trace details. However, some list pages provide additional information, as described in the table below.


> [!NOTE]
> <P>The <STRONG>Pending transactions</STRONG>, <STRONG>Pending orders</STRONG>, and <STRONG>Not shipped sales orders</STRONG> list pages also show information that is not included in the trace details. Additionally, they always show results as of the current date, regardless of whether a date range has been specified. The following table describes the additional details that these pages can include.</P>



<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Button</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Not shipped sales orders</strong></p></td>
<td><p>View sales order lines that haven’t been picked, and are therefore not displayed in the trace details.</p></td>
</tr>
<tr class="even">
<td><p><strong>Pending orders</strong></p></td>
<td><p>View all pending production orders for the traced item, regardless of the tracking dimensions that were used in the trace criteria. You can also view pending production orders where the traced item is an ingredient, and no registrations have been made and no transactions are reported as finished for the order.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Pending transactions</strong></p></td>
<td><p>View pending inventory transactions for the traced item that includes the specified tracking dimensions or a blank tracking dimension. You can also view pending inventory transactions for items and tracking dimension combinations, or a blank value, in the trace details.</p></td>
</tr>
</tbody>
</table>


## How many levels can I trace up or down in a bill of materials or formula?

You can trace one level up or down in a bill of materials or formula. For example, if you run a trace on raw materials, you can see the finished product and any co-products. However, if you trace a co-product, the trace details do not include the finished product.

## How can I view more details about a document or transaction in the trace details?

On the **Details** FastTab, you can view more information about a selected document or transaction in the trace details in the following ways:

  - When you select a node in the trace details on the **Details** FastTab, the other FastTabs in the form display information about the document or transaction in the node.

  - You can open the details form for the document in a selected node by clicking **View details**. For example, if you select a node that describes a production order and you click **View details**, the **Production orders** details form is displayed.

Some FastTabs offer access to additional information about the selected node. For example, on the **Non conformances** FastTab, you can investigate whether there is a history of non-conformance by clicking **Inquiries**. On the **Batch** FastTab, you can click **On-hand** to view the amount of physical inventory that is currently on hand, and any inventory transactions that involve the batch.

## Can I run more than one trace, and then compare the details?

After you’ve run the trace, you can use the options on the **Trace from node** button to run a new trace on the transaction in the selected node. The options are as follows:

  - **Backward** or **Forward** – Start a new trace for the selected node, and overwrite the details of the current trace.

  - **New backward** or **New forward** – Start a new trace in a new window, and keep the details of the current trace.

## Can I save the trace details?

You can save the information on the **Details** tab as an XML file by clicking **Export** on the **Action Pane**. In addition to the trace details, the trace criteria, parent node, and on-hand quantity are also included. Saving the details of a trace is useful, for example, if you want to attach the information to a quality order or other compliance documentation.You can specify where the file is saved. To view the file immediately, select the **Show document** check box.


> [!NOTE]
> <P>The file is always saved, even if you only want to view it.</P>
> <P>By default, the XML file opens in a browser window. However, you can change that by right-clicking the file, choosing <STRONG>Open with</STRONG>, and then selecting the program to use to display the contents.</P>



## Can I calculate a balance for a particular item or ingredient?

You can export the information from the summary forms to Microsoft Excel. To do so, open the relevant form, click **File**, and then select **Export to Microsoft Excel**. This is especially useful when you want to calculate a mass balance for an item or ingredient from the **Transactions** summary form. In the **Transactions** summary form, you can filter on the item or ingredient, and the batch, if you want to, and then export the information to Excel. In Excel, you can, for example, isolate the on-hand quantity, the quantity that was sold, and the amount that was used in production.

## Can I investigate whether there is a history of problems with items or raw materials?

The trace details include information about quality orders and non-conformances that involve the item or raw material. You can view a summary of quality orders and non-conformances by clicking **Quality orders** or **Non conformances** on the **Action Pane**.


> [!NOTE]
> <P>Destructive quality orders can appear more than once in the trace details. When a destructive quality order is created for a document, such as a purchase order, it is displayed for each transaction for that document.</P>



## Are there any reporting capabilities related to item tracing?

You can generate the **Shipped to customers** report to identify the amount of the item or raw material that has been shipped and the customers to whom it was shipped. You can generate the report for all customers or for a selected customer. If the product was a raw material that was used in the production of a finished item, the finished item is also included.


> [!NOTE]
> <P>If you’re using the features for deleting or archiving sales orders, the report results also include any sales orders that have been deleted or archived.</P>



## Can I trace co-products and by-products?

You can trace co-products, but you can’t trace a by-product because tracking dimensions typically aren’t assigned to them. When you trace an item, any related co-products are included in the trace details. A node that contains a co-product includes the word “co-product” in the details. You can also view details about a co-product by selecting the node in the trace details, and then expanding the **Production** FastTab.

## Don't see your question here?

We're working to include as many questions as we can, so that Microsoft Dynamics AX Help will be more useful to people just like you.

Tell us what question you would like to add to this topic. Send email to <adocs@microsoft.com>.

## See also

[Trace an item or raw material in inventory, production, and sales](trace-an-item-or-raw-material-in-inventory-production-and-sales.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

