---
title: Purchase cube (PurchCube) for Microsoft Dynamics AX 2012 R2 and R3
TOCTitle: Purchase cube (PurchCube)
ms:assetid: 5a95613f-8337-455f-bd44-04bfc4bf94e2
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ710389(v=AX.60)
ms:contentKeyID: 49384281
ms.date: 07/23/2014
mtps_version: v=AX.60
---

# Purchase cube (PurchCube) for Microsoft Dynamics AX 2012 R2 and R3 [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The Purchase cube for Microsoft Dynamics AX is used to report on purchase transactions. This article provides details about the cube.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><img src="images/JJ710380.TopicIcons_Reference(AX.60).png" title="Reference" alt="Reference" />
<p>Units of measure and reporting with the Purchase cube</p>
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


## Units of measure and reporting with the Purchase cube

When working with Microsoft SQL Server Reporting Services reports that display a quantity of an item, the appropriate unit of measure must be incorporated into the report to make sure that the quantity is correct, instead of just presenting a SUM value.

For the Quantity measures in the purchase unit of measure, slicing on the Purchase Units dimension separates the quantities by unit of measure. Quantity measures in inventory unit of measure can be sliced by the Unit dimension, which represents the inventory unit.

## Deployment

The Purchase cube is included in the Dynamics AX project. For information about how deploy the Dynamics AX project—and the cubes that it contains—see [Deploy the default cubes](deploy-the-default-cubes.md).

## Configuration keys

The following configuration keys are required to use all features of the Purchase cube:

  - General ledger (LedgerBasic)

  - Trade (LogisticsBasic)

## Tables and views

The Purchase cube uses data from the following tables and views:

  - DlvMode table

  - InventBuyerGroup table

  - VendInvoiceJour table

  - InventTableExpanded view

  - PurchLineExpanded view

  - TAMVendRebateExpanded view

  - VendInvoiceTransExpanded view

  - VendPackingSlipTransStage view

  - VendTableCube view


> [!NOTE]
> <P>The TAMVendRebateExpanded view is used with this cube only in Microsoft Dynamics AX 2012 R3.</P>



## Measures

The Purchase cube includes the following measure groups.

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
<td><p>The number of released products in all organizations.</p></td>
<td><p>Currency</p>
<p>Company</p>
<p>Released products</p>
<p>Buyer groups</p>
<p>Vendor</p>
<p>Styles</p>
<p>Colors</p>
<p>Configurations</p>
<p>Sizes</p></td>
</tr>
</tbody>
</table>


## Purchase lines

This measure group is based on the PurchLineExpanded view and includes the measures in the following table.

From the measures it is possible to read the cycle time in calendar days that it takes for a purchase to be fulfilled. The measure is based on events on a purchase line. The events on a purchase line included in this context are:

  - Confirming the purchase order the first time; the delivery date on the purchase line is the requested date

  - Adding the confirmed delivery date after the purchase order has been confirmed

  - Registering the first product receipt (fully received or partially received)

  - Registering the last product receipt (first product receipt = last product receipt if there is only one)

Only purchase order lines where the products are received by products receipts and have status received or invoiced are included in the cube measures.

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
   
	 Purchase lines count
  </p> </td>
    <td> <p>
   
	 Not applicable
  </p> </td>
    <td> <p>
   
	 Count
  </p> </td>
    <td> <p>
   
	 The number of purchase lines that are included in the measures in the measure group. This includes lines where the products are received by products receipts and have status Received or Invoiced.
  </p> </td>
    <td rowspan="8"> <p>
   
	 Currency
  </p> <p>
   
	 Company
  </p> <p>
   
	 Units
  </p> <p>
   
	 Released products
  </p> <p>
   
	 Mode of delivery
  </p> <p>
   
	 Vendor
  </p> <p>
   
	 Warehouses
  </p> <p>
   
	 Procurement category
  </p> <p>
   
	 Colors
  </p> <p>
   
	 Configurations
  </p> <p>
   
	 Sizes
  </p> <p>
   
	 Purchase lines
  </p> <p>
   
	 Date (date of first purchase order confirmation)
  </p> <p>
   
	 Date (requested delivery date on first confirmation)
  </p> <p>
   
	 Date (receipt date of last delivery)
  </p> <p>
   
	 Procurement category (procurement category – historic)
  </p> <p>
   
	 Units (purchase units)
  </p> <p></p> <p></p> <p></p> <p></p> <p></p> <p></p> <p></p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Purchase line total days from first confirmation to received
  </p> </td>
    <td> <p>
   
	 PurchLineExpanded.DaysConfirmedToReceived
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total number of days on all purchase lines from the date where the first confirmation happened to the date where the last product receipt was registered (product receipt date).
  </p> <p>
   
	 This measure is primarily used to generate the corresponding average calculated measure.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Purchase line total days from first requested delivery date to received
  </p> </td>
    <td> <p>
   
	 PurchLineExpanded.DaysExpectedToReceived
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total number of days on all purchase lines from the delivery date requested on the first confirmation to the date where the last product receipt was registered (product receipt date).
  </p> <p>
   
	 This measure is primarily used to generate the corresponding average calculated measure.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Purchase line total number of product receipts
  </p> </td>
    <td> <p>
   
	 PurchLineExpanded.CountProductReceipts
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total number of product receipts that have been registered on the purchase lines.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Purchase line total number of confirmations by purchase line
  </p> </td>
    <td> <p>
   
	 PurchLineExpanded.CountPurchaseConfirmations
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total number of confirmations of the purchase order that the purchase line is related to. This indicates how many changes there have been in the purchase order lifecycle. Note that the number is per purchase line. For example, if there are 2 purchase lines on a purchase order and the purchase order has been confirmed 2 times then the measure shows 4.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Purchase line total days from first confirmation to first receipt
  </p> </td>
    <td> <p>
   
	 PurchLineExpanded.DaysConfirmedToFirstReceived
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total number of days on all purchase lines from the date where the first confirmation happened to the date where the first product receipt was registered (product receipt date).
  </p> <p>
   
	 This measure is primarily used to generate the corresponding average calculated measure.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Purchase line total days from first receipt to received
  </p> </td>
    <td> <p>
   
	 PurchLineExpanded.DaysPartialToFullReceipt
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total number of days on all purchase lines from the date where the first product receipt was registered to the date where the last product receipt was registered (product receipt date).
  </p> <p>
   
	 This measure is primarily used to generate the corresponding average calculated measure.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Purchase line total days from first confirmation to delivery date is confirmed
  </p> </td>
    <td> <p>
   
	 PurchLineExpanded.DaysConfirmedToFirstResponse
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total number of days on all purchase lines from the date where the first confirmation happened to the date where the confirmed delivery date is added to the purchase line.
  </p> <p>
   
	 This measure is primarily used to generate the corresponding average calculated measure.
  </p> </td>
  </tr>
</table>


## Product receipt lines

This measure group is based on the VendPackingSlipTransStage view and includes the following measures.

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
    <td rowspan="5"> <p>
   
	 Company
  </p> <p>
   
	 Units
  </p> <p>
   
	 Released products
  </p> <p>
   
	 Buyer groups
  </p> <p>
   
	 Vendor
  </p> <p>
   
	 Warehouses
  </p> <p>
   
	 Procurement category
  </p> <p>
   
	 Worker
  </p> <p>
   
	 Colors
  </p> <p>
   
	 Configurations
  </p> <p>
   
	 Sizes
  </p> <p>
   
	 Product receipt lines
  </p> <p>
   
	 Date (expected delivery date)
  </p> <p>
   
	 Vendor (vendor – invoice account)
  </p> <p>
   
	 Date
  </p> <p>
   
	 Procurement category (procurement category – historic)
  </p> <p>
   
	 Units (purchase units)
  </p> <p></p> <p></p> <p></p> <p></p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Days late
  </p> </td>
    <td> <p>
   
	 VendPackingSlipTransStage.DaysDelayed
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The number of days that the product receipt is delayed seen as the difference between the product receipt date that is given when posting the product receipt (date-physical) and the actual expected date.
  </p> <p>
   
	 The measure has a value if the product receipt is posted after the expected date.
  </p> <p>
   
	 The expected date is the Confirmed delivery date that is given on the purchase order line. 
  </p> <p>
   
	 If the <strong>Confirmed delivery date</strong> on the purchase order line is blank, then the measure is calculated as if the date is January 1, 1900.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Days early
  </p> </td>
    <td> <p>
   
	 VendPackingSlipTransStage.DaysEarly
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The number of days that the product receipt is early, seen as the difference between the product receipt date that is given when posting the product receipt (date-physical) and the actual expected date.
  </p> <p>
   
	 The measure has a value when the product receipt is posted before the expected date. 
  </p> <p>
   
	 The expected date is the <strong>Confirmed delivery date</strong> that is given on the purchase order line.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Product receipt lines quantity - inventory unit
  </p> </td>
    <td> <p>
   
	 VendPackingSlipTransStage.InventQty
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The number of items received on a product receipt, in an inventory unit of measure.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Product receipt lines amount - accounting currency
  </p> </td>
    <td> <p>
   
	 VendPackingSlipTransStage.ValueMST
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The cost of the items, which appears only after the invoice is posted. For product receipts that have been posted, the value is 0 (zero) until the corresponding invoice is posted. 
  </p> </td>
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
   
	 Mode of delivery
  </p> <p>
   
	 Buyer groups
  </p> <p>
   
	 Vendor
  </p> <p>
   
	 Vendor invoice journal
  </p> <p>
   
	 Vendor (vendor – invoice account)
  </p> <p>
   
	 Date
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
<td><p>The number of vendor accounts.</p></td>
<td><p>Currency</p>
<p>Company</p>
<p>Vendor</p>
<p>Warehouses</p>
<p>Vendor (vendor – invoice account)</p></td>
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
   
	 The number of invoiced purchase lines that has been posted. Every partial invoice of a purchase line counts as one.
  </p> </td>
    <td rowspan="7"> <p>
   
	 Currency
  </p> <p>
   
	 Company
  </p> <p>
   
	 Units
  </p> <p>
   
	 Released products
  </p> <p>
   
	 Buyer groups
  </p> <p>
   
	 Vendor
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
   
	 Vendor invoice lines
  </p> <p>
   
	 Vendor (vendor – invoice account)
  </p> <p>
   
	 Date
  </p> <p>
   
	 Date (exchange rate date)
  </p> <p>
   
	 Procurement category (procurement category – historic)
  </p> <p>
   
	 Units (purchase units)
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
   
	 The number of items that has been purchased or returned in a unit of measure used on the purchase order. Use the Purchase Units dimension to identify the unit of measure. A returned quantity appears as a negative number. 
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
   
	 The number of items that has been purchased, in an inventory unit of measure, where items appear as a positive value on the purchase order. 
  </p> <div class="alert"><table><tr><th align="left"><img runat="server" AltText="Note" src="https://technet.microsoft.com/en-us/JJ710389.alert_note(AX.60).gif" title="Note" alt="Note" /><strong>Note </strong></th></tr><tr><td> <p>
   
	 Use the Unit dimension to slice for inventory units.
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
   
	 The invoiced amount of the purchased items where items appear as a positive quantity on the purchase order. 
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
   
	 The number of items that has been returned to the vendor in an inventory unit of measure (or appears as a negative quantity on the invoiced purchase order). 
  </p> <div class="alert"><table><tr><th align="left"><img runat="server" AltText="Note" src="https://technet.microsoft.com/en-us/JJ710389.alert_note(AX.60).gif" title="Note" alt="Note" /><strong>Note </strong></th></tr><tr><td> <p>
   
	 Use the Unit dimension to slice for inventory units.
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
   
	 The invoiced amount of the returned items where items appear as a negative quantity on the purchase order. 
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
   
	 The invoiced amount per line, in the company currency. 
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


## Vendor Rebate

This measure group is based on the TAMVendRebateExpanded view and includes the following measures.


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
<td><p>Vendor rebate count</p></td>
<td><p>Not applicable</p></td>
<td><p>Count</p></td>
<td><p>Total number of Open and Approved rebate claims.</p></td>
<td><p>Currency</p>
<p>Company</p>
<p>Released Products</p>
<p>Vendor</p>
<p>Vendor Rebate</p>
<p>Date (Calculation date – Date)</p></td>
</tr>
<tr class="even">
<td><p>Vendor rebate amount</p></td>
<td><p>TAMVendRebateExpanded.StartingRebateAmt</p></td>
<td><p>Sum</p></td>
<td><p>Total dollar value of Open and Approved rebate claims.</p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


## Calculated measures

The Purchase cube contains the following calculated measures.

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
<td><p>Average days late</p></td>
<td><p>Average</p></td>
<td><p>Product receipt lines</p></td>
<td><p>The average difference from expected delivery to actual product receipt for all late product receipts.</p></td>
</tr>
<tr class="even">
<td><p>Average days early</p></td>
<td><p>Average</p></td>
<td><p>Product receipt lines</p></td>
<td><p>The average difference from expected delivery to actual product receipt for all early product receipt.</p></td>
</tr>
<tr class="odd">
<td><p>Vendor performance on product receipts - percent late</p></td>
<td><p>Average</p></td>
<td><p>Product receipt lines</p></td>
<td><p>The percent of all product receipts where the product receipt lines are received late.</p>
<p></p></td>
</tr>
<tr class="even">
<td><p>Vendor performance on product receipts - percent on time</p></td>
<td><p>Average</p></td>
<td><p>Product receipt lines</p></td>
<td><p>The percent of all product receipts where the product receipt lines are received on time.</p></td>
</tr>
<tr class="odd">
<td><p>Vendor performance on product receipts - percent early</p></td>
<td><p>Average</p></td>
<td><p>Product receipt lines</p></td>
<td><p>The percent of all product receipts where the product receipt lines are received early.</p></td>
</tr>
<tr class="even">
<td><p>Purchase line average days from first confirmation to received</p></td>
<td><p>Average</p></td>
<td><p>Purchase lines</p></td>
<td><p>The average difference from first confirmation to the last product receipt registered.</p></td>
</tr>
<tr class="odd">
<td><p>Purchase line average days late from first requested delivery date to received</p></td>
<td><p>Average</p></td>
<td><p>Purchase lines</p></td>
<td><p>The average difference from the requested delivery date of first confirmation to the last product receipt registered for purchase lines with late receipt.</p></td>
</tr>
<tr class="even">
<td><p>Purchase line average days early from first requested delivery date to received</p></td>
<td><p>Average</p></td>
<td><p>Purchase lines</p></td>
<td><p>The average difference from the requested delivery date of first confirmation to the last product receipt registered for purchase lines with early receipt.</p></td>
</tr>
<tr class="odd">
<td><p>Purchase line average days from first confirmation to first receipt</p></td>
<td><p>Average</p></td>
<td><p>Purchase lines</p></td>
<td><p>The average difference from first confirmation to the first product receipt registered.</p></td>
</tr>
<tr class="even">
<td><p>Purchase line average days from first receipt to received</p></td>
<td><p>Average</p></td>
<td><p>Purchase lines</p></td>
<td><p>The average difference from the first product receipt registered to the last product receipt registered.</p></td>
</tr>
<tr class="odd">
<td><p>Purchase line average days from first confirmation to delivery date is confirmed</p></td>
<td><p>Average</p></td>
<td><p>Purchase lines</p></td>
<td><p>The average difference from first confirmation to addition of the confirmed delivery date to the purchase line.</p></td>
</tr>
<tr class="even">
<td><p>Purchase line average number of confirmations</p></td>
<td><p>Average</p></td>
<td><p>Purchase lines</p></td>
<td><p>The average number of confirmed purchase orders per related purchase line.</p></td>
</tr>
<tr class="odd">
<td><p>Purchase line average number of product receipts</p></td>
<td><p>Average</p></td>
<td><p>Purchase lines</p></td>
<td><p>The average number of product receipts registered on the purchase lines.</p></td>
</tr>
</tbody>
</table>


## Key performance indicators

The Purchase cube does not include any key performance indicators (KPIs).

## Security

The Purchase cube can be accessed by users assigned to the following Microsoft SQL Server Analysis Services roles.

  - Accountant

  - Accounting manager

  - Accounting payable manager

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

