---
title: Sales cube (SalesCube) for Microsoft Dynamics AX 2012 and Microsoft Dynamics AX 2012 Feature Pack
TOCTitle: Sales cube (SalesCube)
ms:assetid: 5dd56146-0d2a-4e94-a2a7-39495a7e4418
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh781068(v=AX.60)
ms:contentKeyID: 43894468
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Sales cube (SalesCube) for Microsoft Dynamics AX 2012 and Microsoft Dynamics AX 2012 Feature Pack 


_**Applies To:** Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the Sales cube to report on sales transactions, specifically with regard to posting sales order invoices and sales order packing slips.

## Units of measure and reporting with the Sales cube

When working with Microsoft SQL Server Reporting Services reports that display a quantity of an item, the appropriate unit of measure must be incorporated into the report to make sure that the quantity is correct, instead of just presenting a SUM value.

For example, the InventTrans.QTY field is expressed in the inventory unit of measure. The inventory unit of measure is stored in the InventTableModule table in Microsoft Dynamics AX for each item number. Each item number has three records with different values that represent the unit of measure (ModuleType): Sales, Inventory, and Purchase. For this purpose, use the UnitID where the ModuleType equals Inventory.

For the Quantity measure that uses the sales order unit of measure, slicing on the Units dimension separates the quantities by unit of measure.

## Configuration keys

The following configuration keys are required to use all features of the Sales cube:

  - General ledger (LedgerBasic)

  - Trade (LogisticsBasic)

  - Charges (Markup)

  - Commission (Commission)

  - Price/discount (PriceDisc)

  - Retail headquarters (RetailHeadquarters)

  - Product dimension – size (EcoResProductSize)

  - Product dimension – color (EcoResProductColor)

  - Product dimension – configuration (Config)

## Tables and views

The Sales cube uses data from the following tables and views:

  - CustInvoiceJour table

  - RetailHour table

  - CustInvoiceTransExpanded view

  - CustPackingSlipTransExpanded view

  - CustTableCube view

  - InventTableExpanded view

  - LogisticsPostalAddressExpanded view

  - RetailCategoryExpanded view

  - RetailChannelView view

  - RetailOMHierarchyView view

  - RetailTerminalView view

## Measures

The Sales cube includes the following measure groups.

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
   
	 Geographic location
  </p> <p>
   
	 Hour of day
  </p> <p>
   
	 Retail channel
  </p> <p>
   
	 POS terminal
  </p> <p>
   
	 Customer
  </p> <p>
   
	 Warehouses
  </p> <p>
   
	 Worker
  </p> <p>
   
	 Customer invoices
  </p> <p>
   
	 Customer (customer – invoice account)
  </p> <p>
   
	 Date
  </p> <p>
   
	 Date (due date)
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
   
	 The miscellaneous charges, such as transportation fees, that are allocated to the order, in the accounting currency. 
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
   
	 The total discount, in the accounting currency, that is given on the order. The line discount is not included. 
  </p> </td>
  </tr>
</table>


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
   
	 Released products
  </p> <p>
   
	 Geographic location
  </p> <p>
   
	 Retail category
  </p> <p>
   
	 Customer
  </p> <p>
   
	 Warehouses
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
   
	 Units
  </p> <p>
   
	 Customer packing slip lines
  </p> <p>
   
	 Customer (customer invoice account)
  </p> <p>
   
	 Date
  </p> <p>
   
	 Sales category (sales category – historic)
  </p> <p>
   
	 Geographic location (delivery location)
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
   
	 Quantity of items per packing slip line in storage unit of measure. 
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
   
	 Number of days (per packing slip line) from the confirmed ship date to the packing slip date.
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
   
	 Number of days (per packing slip line) from the requested ship date to the packing slip date.
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
   
	 Quantity of items per packing slip line in sold unit of measure. 
  </p> </td>
  </tr>
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
   
	 Number of invoice transactions, also known as invoice lines. 
  </p> </td>
    <td rowspan="9"> <p>
   
	 Currency
  </p> <p>
   
	 Company
  </p> <p>
   
	 Released products
  </p> <p>
   
	 Geographic location
  </p> <p>
   
	 Hour of day
  </p> <p>
   
	 Retail category
  </p> <p>
   
	 Retail channel
  </p> <p>
   
	 Organization unit
  </p> <p>
   
	 POS terminal
  </p> <p>
   
	 Customer
  </p> <p>
   
	 Warehouses
  </p> <p>
   
	 Worker
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
   
	 Units
  </p> <p>
   
	 Customer invoice transaction
  </p> <p>
   
	 Customer (customer – invoice account)
  </p> <p>
   
	 Date
  </p> <p>
   
	 Date (exchange rate date)
  </p> <p>
   
	 Sales category (sales category – historic)
  </p> <p>
   
	 Geographic location (delivery location)
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
   
	 Commission allocated per invoiced sales line. 
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
   
	 Quantity invoiced per sold unit of measure. 
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
   
	 Quantity that is delivered with the invoice.
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
   
	 Invoiced tax amount per line. 
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
   
	 The cost of goods sold (COGS) for the particular invoiced items.
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
   
	 Quantity invoiced per storage unit of measure. 
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
   
	 Invoiced amount per line, in the accounting currency, excluding tax. 
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


## Calculated measures

The Sales cube contains the following calculated measures.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Calculated measure</p></th>
<th><p>Aggregation</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Average days late (requested ship date)</p></td>
<td><p>Average</p></td>
<td><p>The <strong>Days late requested ship date</strong> measure divided by the number of all packing slip lines.</p>
<div>

> [!NOTE]
> <P>To view the average of the delayed days for only delayed packing slips, slice by the <STRONG>Customer packing slip lines.Delayed requested ship date</STRONG> dimension and view the delayed packing slips.</P>


</div></td>
</tr>
<tr class="even">
<td><p>Average days late (confirmed ship date)</p></td>
<td><p>Average</p></td>
<td><p>The <strong>Days late confirmed ship date</strong> measure divided by the number of all packing slip lines.</p>
<div>

> [!NOTE]
> <P>To view the average of the delayed days for only delayed packing slips, slice by the <STRONG>Customer packing slip lines.Delayed confirmed ship date</STRONG> dimension and view the delayed packing slips.</P>


</div></td>
</tr>
<tr class="odd">
<td><p>Gross profit margin</p></td>
<td><p>Sum</p></td>
<td><p>Gross profit margin is the <strong>Sales amount</strong> – <strong>COGS</strong> – <strong>Sales tax</strong>.</p></td>
</tr>
<tr class="even">
<td><p>Gross profit margin percentage</p></td>
<td><p>Average</p></td>
<td><p>Gross profit margin percentage is <strong>Gross profit margin</strong> divided by <strong>Sales amount</strong>.</p></td>
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

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

