---
title: "What's new: Inventory and warehouse management features"
TOCTitle: Inventory and warehouse management features
ms:assetid: 6ccdf51b-3fb1-410b-8c7f-3e9446466a25
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn527141(v=AX.60)
ms:contentKeyID: 59623270
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# What's new: Inventory and warehouse management features 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

We have changed and added functionality in the [Inventory management](inventory-management.md) area for Microsoft Dynamics AX 2012. For more information, see the tables that apply to your version of the product.


> [!NOTE]
> <P>Microsoft Dynamics AX 2012 R3 includes new Warehouse and Transportation management modules that are enabled by a single configuration key, along with the previously released Warehouse management II module. Users should enable the configuration key for <STRONG>ONLY ONE</STRONG> of these modules, but not both, in a single-instance, single-partition deployment. Although technically feasible, enabling the configuration keys for both of these modules in a single-instance, single-partition deployment is not supported by Microsoft.&nbsp;</P>



## What’s new in AX 2012

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Updated Inventory management pages for Enterprise Portal for Microsoft Dynamics AX</p></td>
<td><p>The existing Inventory management pages in Enterprise Portal have been redesigned, and the new look is consistent with the new features in the Microsoft Dynamics AX client. These features include Action Panes, preview panes, and FactBoxes. The following pages have been updated:</p>
<ul>
<li><p>EPInventOnhand</p></li>
<li><p>EPInventOnhandInfo</p></li>
<li><p>EPInventTableInfo</p></li>
<li><p>EPInventTableList</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Enhancements to Quality management</p></td>
<td><p>Quality management has been enhanced as follows:</p>
<ul>
<li><p>Updates can now be blocked for an order while the related items are going through quality inspection.</p></li>
<li><p>The quality inspection process can be started automatically when items are registered in a warehouse.</p></li>
</ul>
<p>A higher level of differentiation can now be applied to items that go through quality inspection. Therefore, individual batches of items, and items that have different combinations of dimensions, can be inspected separately.</p>
<p>For more information, see <a href="test-products-and-quality-management-overview.md">Test products and quality management overview</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Handling the arrival of products that are not stocked</p></td>
<td><p>Even if unstocked products are not accounted for in inventory, arrivals can be listed and processed in the <strong>Arrival overview</strong> form. The <strong>Direct registration details</strong> tab on the form allows you to view information about arrival lines that constitute a direct registration. These arrivals include products that do not have a product number and arrivals where the products are not stocked.</p>
<p>Incoming orders for stocked items are identified by InventTrans transactions. However, products that are not stocked do not generate InventTrans transactions and cannot be tracked in inventory. Ordered quantities of products that are not stocked are identified by a signal for expected receipts, the inbound order. The inbound order covers both inventory transactions for stocked items that have an <strong>Ordered</strong> status and orders for products that are not stocked.</p>
<p>The following changes are also introduced:</p>
<ul>
<li><p>Support for intercompany trade of products that are not stocked</p></li>
<li><p>Support for sales and purchase returns of products that are not stocked</p></li>
<li><p>Update of various reports to correctly handle order lines that do not contain references to products</p></li>
</ul>
<p>For more detailed information about changes to the InventTrans table, see the white paper <a href="http://go.microsoft.com/fwlink/?linkid=213131%26clcid=0x409">Implementing InventTrans Refactoring for Microsoft Dynamics AX 2012 Applications</a>.</p></td>
</tr>
<tr class="even">
<td><p>QMS enhancements in Inventory management</p></td>
<td><p>The inventory-based aspects of the existing quality management feature have been enhanced.</p>
<p>For the existing quality management feature, users can only register data, and the goal is a process-oriented approach to quality management.</p>
<p><strong>Inventory blocking</strong></p>
<p>Inventory blocking enables both automatic blocking of inventory in an inbound quality management process and also manual blocking of on-hand inventory.</p>
<p><strong>Enhancements for quality test areas</strong></p>
<p>Operators can associate an inspection area with the existing warehouse layout, so that they can identify a location for inventory in the quality management process.</p>
<p>For more information, see <a href="about-inventory-blocking.md">About inventory blocking</a> and <a href="test-products-and-quality-management-overview.md">Test products and quality management overview</a>.</p></td>
</tr>
<tr class="odd">
<td><p>New report that identifies potential conflicts in transactions</p></td>
<td><p>A new report, <strong>Potential conflicts - Inventory and General ledger</strong>, validates whether transactions from Inventory management and General ledger match the parameter settings in Accounts payable, Accounts receivable, Production information management, and Inventory. The report can be used to view a list of any transactions that violate one or more rules. For each violation, a corrective action is suggested.</p>
<p>This functionality was developed for AX 2012 but is available for Microsoft Dynamics AX 2009. For more information, see the white paper <a href="http://www.microsoft.com/en-us/download/details.aspx?id=16245">Microsoft Dynamics AX Inventory Reconciliation and Reporting</a>. For additional helpful information, see the following blog post on the Dynamics AX in the field blog on MSDN: <a href="http://blogs.msdn.com/b/axinthefield/archive/2011/04/22/reconciling-inventory-to-gl-in-dynamics-ax.aspx">Reconciling Inventory to GL in Dynamics AX</a>.</p></td>
</tr>
<tr class="even">
<td><p>Report framework for configuring inventory value reports</p></td>
<td><p>Reports that track inventory movements or reconcile inventories with General ledger can now be configured and saved.</p>
<p>The reports are created in a new report framework that you can use to save a set of unique report configurations. After a report configuration is created, the report can be run at any time without requiring additional configuration.</p>
<p>Reports can be configured for the following purposes:</p>
<ul>
<li><p><strong>Internal auditing</strong> – The report shows the inventory value by physical quantity, financial quantity, and value.</p></li>
<li><p><strong>External auditing</strong> – The report shows the inventory value by quantity and value, and no distinction is made between physical and financial values.</p></li>
<li><p><strong>Reconciliation with General ledger</strong> – The report shows the current inventory of work in process (WIP) and includes the following resource types: material, labor, and indirect costs.</p></li>
</ul>
<p>For more information about the reporting framework, see <a href="reporting-in-microsoft-dynamics-ax.md">Reporting in Microsoft Dynamics AX</a>.</p></td>
</tr>
</tbody>
</table>


## What’s new in Microsoft Dynamics AX 2012 Feature Pack

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Style as a product dimension</p></td>
<td><p>This feature adds support for an additional product dimension, style. You set up and use the new dimension just as you set up and use the existing product dimensions, color and size.</p>
<p>For more information, see <a href="about-product-dimensions.md">About product dimensions</a>.</p></td>
</tr>
<tr class="even">
<td><p>Moving average inventory valuation method</p></td>
<td><p>You can now select moving average, a perpetual cost method, as the inventory valuation method for products. The moving average valuation method allows for backdated purchase orders and sales orders, valuation of produced products, negative inventory, proportional capitalization of variances after the product invoice has been posted, and updated inventory cost for each transaction that is posted. The calculations for the inventory close and recalculation processes do not include products that are valued by moving average.</p>
<p>For more information, see <a href="about-moving-average.md">About moving average</a>. Additionally, the MSDAX Support team blog has an informative blog post about the moving average inventory valuation method <a href="http://blogs.msdn.com/b/axsupport/archive/2012/10/13/answers-to-common-questions-about-moving-average-costing-in-microsoft-dynamics-ax-2012.aspx">Answers to common questions about moving average costing in Microsoft Dynamics AX 2012</a>.</p></td>
</tr>
</tbody>
</table>


## What’s new in Microsoft Dynamics AX 2012 R2

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Performance enhancements for Inventory close</p></td>
<td><p>The performance of the Inventory close and Recalculation batch jobs has been significantly improved. The improvement is based on the following changes in the way that the batch jobs use the batch framework in Microsoft Dynamics AX:</p>
<ul>
<li><p>The logic that is associated with batch helpers for inventory closing has been redefined, and the new logic uses parallel processing from the batch framework much more efficiently than the original logic.</p></li>
<li><p>A new parameter has been introduced that lets you specify the maximum number of items that can be processed at the same time by an inventory closing batch helper.</p></li>
</ul>
<p>Because of the change, the process flow is more efficient, and performance is enhanced. Additionally, insight and traceability of the current stage of the Inventory close and Recalculation jobs are improved when these jobs are run in a batch.</p>
<p>For more information, see the white paper <a href="http://www.microsoft.com/en-us/download/details.aspx?id=35514">Inventory Close Performance Enhancements</a>.</p></td>
</tr>
</tbody>
</table>


## What’s new in cumulative update 6 for Microsoft Dynamics AX 2012

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Trace items and raw materials in inventory, production, and sales transactions.</p></td>
<td><p>You can use the item tracing features to gain visibility into the source and destination of items throughout the supply chain. Manufacturers can trace raw materials and ingredients from receipt, to production, to the sale and transportation of the finished product. Item tracing can help manufacturers comply with regulatory requirements, and helps quality officers and production managers analyze and take action to address variances in the quality of materials.</p>
<p>This functionality provides the following key benefits:</p>
<ul>
<li><p>“One up – one down” tracing for items and batches, and a foundation for cumulative tracing</p></li>
<li><p>Mock recalls, which are a regulatory requirement for manufacturers in certain industries</p></li>
<li><p>Proactive management of product safety</p></li>
<li><p>An overview of any kind of impact in the supply chain</p></li>
<li><p>Enhanced brand protection by enabling manufacturers to demonstrate solid processes for handling defects</p></li>
</ul>
<p>The item tracing features use the strong integration between tracking dimensions and business logic, and the transactions that already exist in Microsoft Dynamics AX.</p>
<p>For more information, see <a href="about-tracing-items-and-raw-materials-in-inventory-production-and-sales.md">About tracing items and raw materials in inventory, production, and sales</a>.</p></td>
</tr>
</tbody>
</table>


## What’s new in cumulative update 7 for Microsoft Dynamics AX 2012 R2

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Performance improvements for on-hand inventory transactions</p></td>
<td><p>The On-hand entries cleanup batch job lets you delete unused entries for serialized on-hand inventory. The batch job deletes on-hand inventory entries that are assigned to a tracking dimension, that contain the value 0 (zero) for all quantities and costs, and that are marked as closed. You can also specify the length of time, in days, that the entries must be unchanged before they are deleted. Entries that are not assigned to a tracking dimension are not deleted. This feature can help improve the performance of queries for on-hand inventory.</p>
<p>For more information, see <a href="clean-up-closed-and-unused-on-hand-inventory-transactions.md">Clean up closed and unused on-hand inventory transactions</a>.</p></td>
</tr>
<tr class="even">
<td><p>Batch merge to combine batches in inventory</p></td>
<td><p>Batch handling features make it easy to combine two or more inventory batches into a new or existing batch. The batch merge functionality can also help you manage the shelf life and vendor batch details for merged batches.</p>
<p>When the source batches are selected, and the details for the merged batch are specified, you can review the information before you post it. You can also transfer the batch merge to an inventory journal for approval. Inventory can then be reserved or posted directly from the inventory journal. When you post a batch merge, the system creates or updates the selected destination batch, and adjusts the inventory for the source batches and the merged batch.</p>
<p>For more information, see <a href="about-batch-merges-in-inventory.md">About batch merges in inventory</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Role Center for costing and inventory valuation</p></td>
<td><p>The cost controller’s Role Center provides information about costing and inventory valuation. The Role Center includes two cues that can help cost controllers with the daily maintenance of system configurations.</p>
<p>You can request the status of inventory, inventory accuracy per item group, and inventory aging in a series of diagrams. Furthermore, a business overview can help you identify products that have low performance.</p></td>
</tr>
</tbody>
</table>


## What’s new in Microsoft Dynamics AX 2012 R3

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Compare item prices</p></td>
<td><p>The <strong>Compare item prices</strong> report enables you to compare the prices in a costing version to the pending prices in another costing version or to the active prices as per an effective date. For standard costs, the report compares the aggregate level and the cost rollup level.</p>
<ul>
<li><p>At the aggregate level, the report compares the total aggregated cost per item, item variant, and site.</p></li>
<li><p>At the cost rollup level, the report compares the cost rollup for each cost group per item, item variant, and site.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>BOM journal posting</p></td>
<td><p>The posting routine in the <strong>BOM journal</strong> is redesigned and enhanced. When you post a BOM journal, you post the journal to inventory profit and loss accounts instead of production WIP accounts. This way, the imbalance expires and does not remain on the WIP account. For actual costs, a negative BOM journal leaves a balance on the WIP account. This imbalance is posted to general ledger as profit and loss.</p></td>
</tr>
<tr class="odd">
<td><p>Inventory aging report</p></td>
<td><p>The <strong>Inventory aging</strong> report displays the on-hand quantity, inventory value, and the related aging periods for a selected item or an item group. You can use the report parameters to filter the data that will be displayed in the report.</p></td>
</tr>
</tbody>
</table>

  


