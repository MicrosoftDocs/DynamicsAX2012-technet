---
title: Purchase cube (PurchCube) for Microsoft Dynamics AX 2012 and Microsoft Dynamics AX 2012 Feature Pack
TOCTitle: Purchase cube (PurchCube)
ms:assetid: 1faa890e-979e-461b-88b0-aae2145bc76b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh781066(v=AX.60)
ms:contentKeyID: 43894465
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Purchase cube (PurchCube) for Microsoft Dynamics AX 2012 and Microsoft Dynamics AX 2012 Feature Pack 


_**Applies To:** Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the Purchase cube to report on purchase transactions.

## Units of measure and reporting with the Purchase cube

When working with Microsoft SQL Server Reporting Services reports that display a quantity of an item, the appropriate unit of measure must be incorporated into the report to make sure that the quantity is correct, instead of just presenting a SUM value.

For example, the InventTrans.QTY field is expressed in the inventory unit of measure. The inventory unit of measure is stored in the InventTableModule table in Microsoft Dynamics AX for each item number. Each item number has three records with different values that represent the unit of measure (ModuleType): Sales, Inventory, and Purchase. For this purpose, use the UnitID where the ModuleType equals Inventory.

For the Quantity measure that uses the purchase unit of measure, slicing on the Units dimension separates the quantities by unit of measure.

## Configuration keys

The following configuration keys are required to use all features of the Purchase cube:

  - General ledger (LedgerBasic)

  - Trade (LogisticsBasic)

  - Charges (Markup)

  - Price/discount (PriceDisc)

  - Product dimension – size (EcoResProductSize)

  - Product dimension – color (EcoResProductColor)

  - Product dimension – configuration (Config)

## Tables and views

The Purchase cube uses data from the following tables and views:

  - InventBuyerGroup table

  - VendInvoiceJour table

  - InventTableExpanded view

  - LogisticsPostalAddressExpanded view

  - VendInvoiceTransExpanded view

  - VendPackingSlipTransExpanded view

  - VendTableCube view

## Measures

The Purchase cube includes the following measure groups.

## Vendors

This measure group is based on the VendTableCube view and includes the following measures.

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
<td><p>Vendors count</p></td>
<td><p>Not applicable</p></td>
<td><p>Count</p></td>
<td><p>Number of vendor accounts.</p></td>
<td><p>Currency</p>
<p>Company</p>
<p>Vendor</p>
<p>Warehouses</p>
<p>Vendor (vendor – invoice account)</p></td>
</tr>
</tbody>
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
<td><p>Number of released products in all organizations.</p></td>
<td><p>Currency</p>
<p>Company</p>
<p>Vendor</p>
<p>Released products</p>
<p>Buyer groups</p>
<p>Styles</p>
<p>Colors</p>
<p>Configurations</p>
<p>Sizes</p></td>
</tr>
</tbody>
</table>


## Vendor invoice lines

This measure group is based on the VendInvoiceTransExpanded view and includes the following measures.

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
   
	 Vendor invoice lines count
  </p> </td>
    <td> <p>
   
	 Not applicable
  </p> </td>
    <td> <p>
   
	 Count
  </p> </td>
    <td> <p>
   
	 Number of invoiced purchase lines that has been posted. Every partial invoice of a purchase line counts as one.
  </p> </td>
    <td rowspan="7"> <p>
   
	 Currency
  </p> <p>
   
	 Company
  </p> <p>
   
	 Vendor
  </p> <p>
   
	 Released products
  </p> <p>
   
	 Buyer groups
  </p> <p>
   
	 Warehouses
  </p> <p>
   
	 Procurement category
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
   
	 Vendor invoice lines
  </p> <p>
   
	 Date
  </p> <p>
   
	 Vendor (vendor – invoice account)
  </p> <p>
   
	 Date (exchange rate date)
  </p> <p>
   
	 Procurement category - historic
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Purchase and return quantity – purchase unit
  </p> </td>
    <td> <p>
   
	 VendInvoiceTransExpanded.Qty
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 Number of items that has been purchased or returned in a unit of measure used on the purchase order. Use the <strong xmlns="http://www.w3.org/1999/xhtml">Units</strong> dimension to identify the unit of measure. A returned quantity appears as a negative number. 
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Purchase quantity – inventory unit
  </p> </td>
    <td> <p>
   
	 VendInvoiceTransExpanded.PurchaseQty
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 Number of items that has been purchased, in an inventory unit of measure, where items appear as a positive value on the purchase order. 
  </p> <div><table><tr><th align="left"><img runat="server" AltText="Note" src="https://technet.microsoft.com/en-us/Hh781066.alert_note(AX.60).gif" title="Note" alt="Note" /><strong>Note </strong></th></tr><tr><td> <p>
   
	 The <strong xmlns="http://www.w3.org/1999/xhtml">Units</strong> dimension should not be used on this measure because it uses the purchase units and not inventory units.
  </p> </td></tr></table></div></td>
  </tr>
  <tr>
    <td> <p>
   
	 Vendor invoice line amount returns not included – accounting currency
  </p> </td>
    <td> <p>
   
	 VendInvoiceTransExpanded.PurchaseAmountMST
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 Invoiced amount of the purchased items where items appear as a positive quantity on the purchase order. 
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Return quantity – inventory unit
  </p> </td>
    <td> <p>
   
	 VendInvoiceTransExpanded.ReturnQty
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 Number of items that has been returned to the vendor in an inventory unit of measure (or appears as a negative quantity on the invoiced purchase order). 
  </p> <div><table><tr><th align="left"><img runat="server" AltText="Note" src="https://technet.microsoft.com/en-us/Hh781066.alert_note(AX.60).gif" title="Note" alt="Note" /><strong>Note </strong></th></tr><tr><td> <p>
   
	 The <strong xmlns="http://www.w3.org/1999/xhtml">Units</strong> dimension should not be used on this measure because it uses the purchase units and not inventory units.
  </p> </td></tr></table></div></td>
  </tr>
  <tr>
    <td> <p>
   
	 Vendor invoice line amount returns – accounting currency
  </p> </td>
    <td> <p>
   
	 VendInvoiceTransExpanded.ReturnAmountMST
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 Invoiced amount of the returned items where items appear as a negative quantity on the purchase order. 
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Vendor invoice line amount – accounting currency
  </p> </td>
    <td> <p>
   
	 VendInvoiceTransExpanded.LineAmountMST
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 Invoiced amount per line, in the company currency. 
  </p> </td>
  </tr>
</table>


## Product receipt lines

This measure group is based on the VendPackingSlipTransExpanded view and includes the following measures.

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
   
	 Product receipt lines count
  </p> </td>
    <td> <p>
   
	 Not applicable
  </p> </td>
    <td> <p>
   
	 Count
  </p> </td>
    <td> <p>
   
	 The number of product receipt lines. 
  </p> </td>
    <td rowspan="4"> <p>
   
	 Company
  </p> <p>
   
	 Vendor
  </p> <p>
   
	 Released products
  </p> <p>
   
	 Warehouses
  </p> <p>
   
	 Worker
  </p> <p>
   
	 Procurement category
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
   
	 Product receipt lines
  </p> <p>
   
	 Date
  </p> <p>
   
	 Vendor (vendor – invoice account)
  </p> <p>
   
	 Procurement category
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Days late
  </p> </td>
    <td> <p>
   
	 VendPackingSlipTransExpanded.DaysDelayed
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 Number of days that the product receipt is delayed seen as the difference between the product receipt date that is given when posting the product receipt (date-physical) and the actual expected date. 
  </p> <p>
   
	 If the product receipt is posted before the expected date, then the days late is 0. 
  </p> <p>
   
	 The measure can be sliced by the attribute <strong xmlns="http://www.w3.org/1999/xhtml">Delayed</strong> on the <strong xmlns="http://www.w3.org/1999/xhtml">Product receipt lines</strong> dimension; this separates the product receipts in delayed and not delayed.
  </p> <p>
   
	 This measure is used for the <strong xmlns="http://www.w3.org/1999/xhtml">Average days late</strong> calculated measure.
  </p> <p>
   
	 The expected date is the <strong xmlns="http://www.w3.org/1999/xhtml">Confirmed delivery date</strong> that is given on the purchase order line. 
  </p> <div><table><tr><th align="left"><img runat="server" AltText="Note" src="https://technet.microsoft.com/en-us/Hh781066.alert_note(AX.60).gif" title="Note" alt="Note" /><strong>Note </strong></th></tr><tr><td> <p>
   
	 If the <strong xmlns="http://www.w3.org/1999/xhtml">Confirmed delivery date</strong> on the purchase order line is blank, then the measure is calculated as if the date is January 1, 1900. 
  </p> </td></tr></table></div></td>
  </tr>
  <tr>
    <td> <p>
   
	 Product receipt lines amount – accounting currency
  </p> </td>
    <td> <p>
   
	 VendPackingSlipTransExpanded.ValueMST
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 Cost of the items, which appears only after the invoice is posted. For product receipts that have been posted, the value is 0 (zero) until the corresponding invoice is posted. 
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Product receipt lines quantity – inventory unit
  </p> </td>
    <td> <p>
   
	 VendPackingSlipTransExpanded.InventQty
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 Number of items received on a product receipt, in an inventory unit of measure.
  </p> <div><table><tr><th align="left"><img runat="server" AltText="Note" src="https://technet.microsoft.com/en-us/Hh781066.alert_note(AX.60).gif" title="Note" alt="Note" /><strong>Note </strong></th></tr><tr><td> <p>
   
	 The <strong xmlns="http://www.w3.org/1999/xhtml">Units</strong> dimension should not be used on this measure since it uses the purchase units and not inventory units.
  </p> </td></tr></table></div></td>
  </tr>
</table>


## Vendor invoice

This measure group is based on the VendInvoiceJour table and includes the following measures.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th colspan="1"> <p>
   
	 Measure
  </p> </th>
    <th colspan="1"> <p>
   
	 Measure field name
  </p> </th>
    <th colspan="1"> <p>
   
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
    <td colspan="1"> <p>
   
	 Vendor invoice count
  </p> </td>
    <td colspan="1"> <p>
   
	 Not applicable
  </p> </td>
    <td colspan="1"> <p>
   
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
   
	 Vendor
  </p> <p>
   
	 Buyer groups
  </p> <p>
   
	 Vendor invoice journal
  </p> <p>
   
	 Date
  </p> <p>
   
	 Vendor (vendor – invoice account)
  </p> <p>
   
	 Date (due date)
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Vendor invoice amount – accounting currency
  </p> </td>
    <td colspan="1"> <p>
   
	 VendInvoiceJour.InvoiceAmountMST
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The invoiced amounts, in the accounting currency.
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Vendor invoice charges amount – accounting currency
  </p> </td>
    <td colspan="1"> <p>
   
	 VendInvoiceJour.SumMarkupMST
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The miscellaneous charges, such as transportation fees, that are allocated to the order, in the accounting currency.
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Vendor invoice discount – accounting currency
  </p> </td>
    <td colspan="1"> <p>
   
	 VendInvoiceJour.EndDiscMST
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total discount, in the accounting currency, that is given on the order (the line discount is not included).
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


## Calculated measures

The Purchase cube contains the following calculated measures.

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
<td><p>Average days late</p></td>
<td><p>Average</p></td>
<td><p>The <strong>Days late</strong> measure divided by the number of all product receipt lines.</p>
<div>

> [!NOTE]
> <P>To view the average of the delayed days for delayed product receipts, slice by the <STRONG>Product receipt lines - delayed</STRONG> dimension and view the delayed product receipts.</P>


</div></td>
</tr>
</tbody>
</table>


## Key performance indicators

The Purchase cube does not include any key performance indicators (KPIs).

## Security

The Purchase cube can be accessed by users assigned to the following Microsoft SQL Server Analysis Services roles.

  - Accountant

  - Accounting manager

  - Accounting supervisor

  - Accounts payable centralized payments clerk

  - Accounts payable clerk

  - Accounts payable manager

  - Buying agent

  - Chief executive officer

  - Chief financial officer

  - Compliance manager

  - Financial controller

  - Project manager

  - Purchasing manager

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

