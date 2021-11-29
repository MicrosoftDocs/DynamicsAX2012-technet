---
title: Sales cube (SalesCube) for Microsoft Dynamics AX 2012 R2 and R3
TOCTitle: Sales cube (SalesCube)
ms:assetid: a213238a-108a-4818-ae79-86884d446ccb
ms:mtpsurl: https://technet.microsoft.com/library/JJ710394(v=AX.60)
ms:contentKeyID: 49384286
author: Khairunj
ms.date: 07/23/2014
mtps_version: v=AX.60
---

# Sales cube (SalesCube) for Microsoft Dynamics AX 2012 R2 and R3 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The Sales cube for Microsoft Dynamics AX is used to report on shipped and invoiced sales order lines. This article provides details about the cube.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><img src="images/JJ710380.TopicIcons_Reference(AX.60).png" title="Reference" alt="Reference" />
<p>Units of measure and reporting with the Sales cube</p>
<p>Deployment</p>
<p>Configuration keys</p>
<p>Tables and views</p>
<p>Measures</p>
<p>Calculated measures</p>
<p>Key performance indicators</p>
<p>Security</p></td>
<td><img src="images/Dn507140.TopicIcons_Resources(AX.60).png" title="Resources" alt="Resources" />
<p><a href="analytics-in-microsoft-dynamics-ax.md">Analytics in Microsoft Dynamics AX</a></p>
<p><a href="cube-and-kpi-reference-for-microsoft-dynamics-ax-2012-r2-and-r3.md">Cube and KPI reference for Microsoft Dynamics AX 2012 R2 and R3</a></p>
<p><a href="cube-and-kpi-reference-for-microsoft-dynamics-ax-2012-and-microsoft-dynamics-ax-2012-feature-pack.md">Cube and KPI reference for Microsoft Dynamics AX 2012 and Microsoft Dynamics AX 2012 Feature Pack</a></p></td>
</tr>
</tbody>
</table>


## Units of measure and reporting with the Sales cube

When working with Microsoft SQL Server Reporting Services reports that display a quantity of an item, the appropriate unit of measure must be incorporated into the report to make sure that the quantity is correct, instead of just presenting a SUM value.

For example, the InventTrans.QTY field is expressed in the inventory unit of measure. The inventory unit of measure is stored in the InventTableModule table in Microsoft Dynamics AX for each item number. Each item number has three records with different values that represent the unit of measure (ModuleType): Sales, Inventory, and Purchase. For this purpose, use the UnitID where the ModuleType equals Inventory.

For the Quantity measure that uses the sales order unit of measure, slicing on the Units dimension separates the quantities by unit of measure.

## Deployment

The Sales cube is included in the Dynamics AX project. For information about how deploy the Dynamics AX project—and the cubes that it contains—see [Deploy the default cubes](deploy-the-default-cubes.md).

## Configuration keys

The following configuration keys are required to use all features of the Sales cube:

  - General ledger (LedgerBasic)

  - Trade (LogisticsBasic)

  - Charges (Markup)

  - Commission (Commission)

  - Price/discount (PriceDisc)

  - Retail headquarters (RetailHeadquarters)

## Tables and views

The Sales cube uses data from the following tables and views:

  - CustInvoiceJour table

  - MCRSourceCodeSetup table

  - RetailHour table

  - CustInvoiceTransExpanded view

  - CustPackingSlipTransExpanded view

  - CustTableCube view

  - InventTableExpanded view

  - MCRSourceSalesSummary view

  - PdsRebateExpanded view

  - RetailCategoryExpanded view

  - RetailChannelView view

  - RetailOMHierarchyView view

  - RetailTerminalView view

  - SalesLineExpanded view


> [!NOTE]
> <P>The MCRSourceCodeSetup table and the MCRSourceSalesSummary and PdsRebateExpanded views are used with this cube only in Microsoft Dynamics AX 2012 R3.</P>



## Measures

The Sales cube includes the following measure groups.

## Customer packing slip lines

This measure group is based on the CustPackingSlipTransExpanded view and includes the following measures.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th> <p>
   
	 Measure
  </p> </th>
    <th> <p>
   
	 Measure field name
  </p> </th>
    <th> <p>
   
	 Aggregation
  </p> </th>
    <th> <p>
   
	 Description
  </p> </th>
    <th> <p>
   
	 Associated dimensions
  </p> </th>
  </tr>
  <tr>
    <td> <p>
   
	 Customer packing slip lines count
  </p> </td>
    <td> <p>
   
	 Not applicable
  </p> </td>
    <td> <p>
   
	 Count
  </p> </td>
    <td> <p>
   
	 The number of packing slip lines. 
  </p> </td>
    <td rowspan="5"> <p>
   
	 Company
  </p> <p>
   
	 Units
  </p> <p>
   
	 Released products
  </p> <p>
   
	 Customer
  </p> <p>
   
	 Retail category
  </p> <p>
   
	 Warehouses
  </p> <p>
   
	 Geographic location
  </p> <p>
   
	 Sales category
  </p> <p>
   
	 Styles
  </p> <p>
   
	 Colors
  </p> <p>
   
	 Configurations
  </p> <p>
   
	 Sizes
  </p> <p>
   
	 Customer packing slip lines
  </p> <p>
   
	 Date
  </p> <p>
   
	 Customer (customer - invoice account)
  </p> <p>
   
	 Sales category (sales category – historic)
  </p> <p>
   
	 Geographic location (delivery location)
  </p> <p>
   
	 Units (sales units)
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Packing slip quantity – inventory unit
  </p> </td>
    <td> <p>
   
	 CustPackingSlipTransExpanded.InventQty
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The quantity per packing slip line, in storage unit of measure. 
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Days late confirmed ship date
  </p> </td>
    <td> <p>
   
	 CustPackingSlipTransExpanded.DaysDelayedConfirmedDate
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The number of days (per packing slip line) from the confirmed ship date to the packing slip date.
  </p> <p>
   
	 If the packing slip date is before the confirmed ship date (that is—it is not delayed), the measure is 0.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Days late requested ship date
  </p> </td>
    <td> <p>
   
	 CustPackingSlipTransExpanded.DaysDelayedRequestedDate
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The number of days (per packing slip line) from the requested ship date to the packing slip date.
  </p> <p>
   
	 If the packing slip date is before the requested ship date (that is—it is not delayed), the measure is 0.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Packing slip quantity – sales unit
  </p> </td>
    <td> <p>
   
	 CustPackingSlipTransExpanded.Qty
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The quantity per packing slip line, in sold unit of measure. 
  </p> </td>
  </tr>
</table>


## Released products

This measure group is based on the InventTableExpanded view and includes the following measures.

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Measure</p></th>
<th><p>Measure field name</p></th>
<th><p>Aggregation</p></th>
<th><p>Description</p></th>
<th><p>Associated dimensions</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Released products count</p></td>
<td><p>Not applicable</p></td>
<td><p>Count</p></td>
<td><p>The number of released products.</p></td>
<td><p>Currency</p>
<p>Company</p>
<p>Released products</p>
<p>Styles</p>
<p>Colors</p>
<p>Configurations</p>
<p>Sizes</p></td>
</tr>
</tbody>
</table>


## Customers

This measure group is based on the CustTableCube view and includes the following measures.

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Measure</p></th>
<th><p>Measure field name</p></th>
<th><p>Aggregation</p></th>
<th><p>Description</p></th>
<th><p>Associated dimensions</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Customers count</p></td>
<td><p>Not applicable</p></td>
<td><p>Count</p></td>
<td><p>The number of customer records.</p></td>
<td><p>Currency</p>
<p>Company</p>
<p>Customer</p>
<p>Warehouses</p>
<p>Worker</p>
<p>Customer (customer – invoice account)</p></td>
</tr>
</tbody>
</table>


## Sales order lines

This measure group is based on the SalesLineExpanded view and includes the following measures.

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Measure</p></th>
<th><p>Measure field name</p></th>
<th><p>Aggregation</p></th>
<th><p>Description</p></th>
<th><p>Associated dimensions</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Sales order lines count</p></td>
<td><p>Not applicable</p></td>
<td><p>Count</p></td>
<td><p>The number of sales order lines.</p></td>
<td><p>Company</p>
<p>Units</p>
<p>Released products</p>
<p>Customer</p>
<p>Retail category</p>
<p>Warehouses</p>
<p>Sales category</p>
<p>Colors</p>
<p>Configurations</p>
<p>Sizes</p>
<p>Sales order lines</p>
<p>Date (confirmed ship date on 1st packing slip)</p>
<p>Date (requested ship date on 1st packing slip)</p>
<p>Sales category (sales category – historic)</p>
<p>Units (sales units)</p></td>
</tr>
</tbody>
</table>


## Customer invoice lines

This measure group is based on the CustInvoiceTransExpanded view and includes the following measures.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th> <p>
   
	 Measure
  </p> </th>
    <th> <p>
   
	 Measure field name
  </p> </th>
    <th> <p>
   
	 Aggregation
  </p> </th>
    <th> <p>
   
	 Description
  </p> </th>
    <th> <p>
   
	 Associated dimensions
  </p> </th>
  </tr>
  <tr>
    <td> <p>
   
	 Customer invoice lines count
  </p> </td>
    <td> <p>
   
	 Not applicable
  </p> </td>
    <td> <p>
   
	 Count
  </p> </td>
    <td> <p>
   
	 The number of invoice transactions, also known as invoice lines. 
  </p> </td>
    <td rowspan="9"> <p>
   
	 Currency
  </p> <p>
   
	 Company
  </p> <p>
   
	 Units
  </p> <p>
   
	 Released products
  </p> <p>
   
	 Customer
  </p> <p>
   
	 POS terminal
  </p> <p>
   
	 Retail category
  </p> <p>
   
	 Retail channel
  </p> <p>
   
	 Organization unit
  </p> <p>
   
	 Warehouses
  </p> <p>
   
	 Geographic location
  </p> <p>
   
	 Sales category
  </p> <p>
   
	 Worker
  </p> <p>
   
	 Styles
  </p> <p>
   
	 Colors
  </p> <p>
   
	 Configurations
  </p> <p>
   
	 Sizes
  </p> <p>
   
	 Customer invoice transaction
  </p> <p>
   
	 Date
  </p> <p>
   
	 Date (due date)
  </p> <p>
   
	 Customer (customer – invoice account)
  </p> <p>
   
	 Date (exchange rate date)
  </p> <p>
   
	 Sales category (sales category – historic)
  </p> <p>
   
	 Geographic location (delivery location)
  </p> <p>
   
	 Units (sales units)
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Commision line amount – accounting currency
  </p> </td>
    <td> <p>
   
	 CustInvoiceTransExpanded.CommishAmountMST
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The commission allocated per invoiced line. 
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Customer invoice quantity – sales unit
  </p> </td>
    <td> <p>
   
	 CustInvoiceTransExpanded.Qty
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The quantity invoiced per sold unit of measure. 
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Quantity delivered without packing slip – sales unit
  </p> </td>
    <td> <p>
   
	 CustInvoiceTransExpanded.QtyPhysical
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The quantity that is delivered directly with the invoice without a preceding packing slip.
  </p> <p>
   
	 This quantity is 0 (zero) if a packing slip has been created for the item. If no packing slip has been created, this field contains the quantity sold in selling unit of measure.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Sales tax line amount – accounting currency
  </p> </td>
    <td> <p>
   
	 CustInvoiceTransExpanded.TaxAmountMST
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The invoiced tax amount per invoice line. 
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Cost of goods sold – accounting currency
  </p> </td>
    <td> <p>
   
	 CustInvoiceTransExpanded.COGS
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The cost of goods sold (COGS) for the particular invoiced item.
  </p> <p>
   
	 The COGS value is based on the corresponding inventory transaction. This measure may need an inventory closing where a potential adjustment may occur.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Customer invoice quantity – inventory unit
  </p> </td>
    <td> <p>
   
	 CustInvoiceTransExpanded.InventQty
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The quantity invoiced per storage unit of measure. 
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Customer invoice line amount – accounting currency
  </p> </td>
    <td> <p>
   
	 CustInvoiceTransExpanded.LineAmountMST
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The invoiced amount per line, in the accounting currency, excluding tax. 
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Sales tax included in customer invoice line amount – accounting currency
  </p> </td>
    <td> <p>
   
	 CustInvoiceTransExpanded.LineAmountTaxMST
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The value in this field is the same as the TaxAmountMST whenever the tax is included in the price on the invoice. 
  </p> <p>
   
	 The value in this field is 0 (zero) if the price on the invoice does not include tax. 
  </p> </td>
  </tr>
</table>


## Customer invoices

This measure group is based on the CustInvoiceJour table and includes the following measures.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th> <p>
   
	 Measure
  </p> </th>
    <th> <p>
   
	 Measure field name
  </p> </th>
    <th> <p>
   
	 Aggregation
  </p> </th>
    <th> <p>
   
	 Description
  </p> </th>
    <th> <p>
   
	 Associated dimenisons
  </p> </th>
  </tr>
  <tr>
    <td> <p>
   
	 Customer invoices count
  </p> </td>
    <td> <p>
   
	 Not applicable
  </p> </td>
    <td> <p>
   
	 Count
  </p> </td>
    <td> <p>
   
	 The number of invoices. 
  </p> </td>
    <td rowspan="4"> <p>
   
	 Currency
  </p> <p>
   
	 Company
  </p> <p>
   
	 Customer
  </p> <p>
   
	 Warehouses
  </p> <p>
   
	 Geographic location
  </p> <p>
   
	 Worker
  </p> <p>
   
	 Customer invoices
  </p> <p>
   
	 Date
  </p> <p>
   
	 Date (due date)
  </p> <p>
   
	 Customer (customer – invoice account)
  </p> <p>
   
	 Geographic location (delivery location)
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Customer invoice amount – accounting currency
  </p> </td>
    <td> <p>
   
	 CustInvoiceJour.InvoiceAmountMST
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The invoiced amounts, in the accounting currency.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Customer invoice charges – accounting currency
  </p> </td>
    <td> <p>
   
	 CustInvoiceJour.SumMarkupMST
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The charges, such as transportation fees, that are allocated to the invoice header, in the accounting currency. 
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Customer invoice discount – accounting currency
  </p> </td>
    <td> <p>
   
	 CustInvoiceJour.EndDiscMST
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total discount, in the accounting currency, that is given on the invoice. The line discount is not included. 
  </p> </td>
  </tr>
</table>


## Exchange rates by day

This measure group is based on the BIExchangeRateView view and includes the following measures.

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Measure</p></th>
<th><p>Measure field name</p></th>
<th><p>Aggregation</p></th>
<th><p>Description</p></th>
<th><p>Associated dimensions</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Exchange rate</p></td>
<td><p>BIExchangeRateView.CrossRate</p></td>
<td><p>Max</p></td>
<td><p>The exchange rate.</p></td>
<td><p>Currency</p>
<p>Date (exchange rate date)</p>
<p>Analysis currency</p></td>
</tr>
</tbody>
</table>


## Sales rebate

This measure group is based on the PDSRebateExpanded view and includes the following measures.


> [!NOTE]
> <P>This measure group is available only in Microsoft Dynamics AX 2012 R3.</P>



<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Measure</p></th>
<th><p>Measure field name</p></th>
<th><p>Aggregation</p></th>
<th><p>Description</p></th>
<th><p>Associated dimensions</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Sales rebate count</p></td>
<td><p>Not applicable</p></td>
<td><p>Count</p></td>
<td><p>Total number of Open and Approved rebate claims.</p></td>
<td><p>Currency</p>
<p>Company</p>
<p>Customer</p>
<p>Released products</p>
<p>Sales rebate</p>
<p>Worker</p>
<p>Date (Process date – Date)</p>
<p>Date (Calculation date – Date)</p></td>
</tr>
<tr class="even">
<td><p>Starting rebate amount</p></td>
<td><p>PDSRebateExpanded.PDSStartingRebateAmt</p></td>
<td><p>Sum</p></td>
<td><p>Total dollar value of Open and Approved rebate claims.</p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


## Calculated measures

The Sales cube contains the following calculated measures.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Calculated measure</p></th>
<th><p>Aggregation</p></th>
<th><p>Associated measure group</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>All sales order lines</p></td>
<td><p>Sum</p></td>
<td><p>Sales order lines</p></td>
<td><p>All sales order lines that have a status of delivered or invoiced, and have at least one packing slip.</p></td>
</tr>
<tr class="even">
<td><p>% Sales order lines shipped in full</p></td>
<td><p>Sum</p></td>
<td><p>Sales order lines</p></td>
<td><p>The percent shipped in full of sales order lines with at least one related packing slip and not of status <strong>Open order</strong>.</p></td>
</tr>
<tr class="odd">
<td><p>% Sales order lines not shipped in full</p></td>
<td><p>Sum</p></td>
<td><p>Sales order lines</p></td>
<td><p>The percent not shipped in full of sales order lines with at least one related packing slip and not of status <strong>Open order</strong>.</p></td>
</tr>
<tr class="even">
<td><p>Average days late (confirmed ship date)</p></td>
<td><p>Average</p></td>
<td><p>Customer packing slip lines</p></td>
<td><p>The average difference from the confirmed ship date to the packing slip receipt date.</p></td>
</tr>
<tr class="odd">
<td><p>Average days late (requested ship date)</p></td>
<td><p>Average</p></td>
<td><p>Customer packing slip lines</p></td>
<td><p>The average difference from the requested ship date to the packing slip receipt date.</p></td>
</tr>
<tr class="even">
<td><p>Customer contribution margin - accounting currency</p></td>
<td><p>Sum</p></td>
<td><p>Customer invoice lines</p></td>
<td><p>The amount remaining after unit variable costs has been deducted from the unit revenue.</p></td>
</tr>
<tr class="odd">
<td><p>Customer contribution margin percentage</p></td>
<td><p>Average</p></td>
<td><p>Customer invoice lines</p></td>
<td><p>The contribution margin divided by total revenue, expressed as a percentage.</p></td>
</tr>
<tr class="even">
<td><p>Gross profit margin</p></td>
<td><p>Sum</p></td>
<td><p>Undefined</p></td>
<td><p>The amount remaining after the cost of goods sold (COGS) has been deducted from the total sales for an item or a given quantity of inventory.</p></td>
</tr>
<tr class="odd">
<td><p>Gross profit margin percentage</p></td>
<td><p>Average</p></td>
<td><p>Undefined</p></td>
<td><p>The gross profit margin divided by the total sales revenue, expressed as a percentage. The gross profit margin represents the percent of total sales revenue that a retailer retains after incurring the direct costs associated with producing the goods and services sold. The higher the percentage, the more the retailer retains on each dollar of sales to service its other costs and obligations.</p></td>
</tr>
</tbody>
</table>


## Key performance indicators

The Sales cube does not include any key performance indicators (KPIs).

## Security

The Sales cube can be accessed by users assigned to the following Microsoft SQL Server Analysis Services roles.

  - Accounting manager

  - Accounts receivable manager

  - Chief executive officer

  - Chief financial officer

  - Compliance manager

  - Financial controller

  - Retail merchandising manager

  - Retail operations manager

  - Retail store manager

  - Sales manager

  - Warehouse manager

  


