---
title: Retail cube (RetailCube) for Microsoft Dynamics AX 2012 R2 and R3
TOCTitle: Retail cube (RetailCube)
ms:assetid: 00ac6d6e-dc7d-4045-a7df-8cbe07ad1a30
ms:mtpsurl: https://technet.microsoft.com/library/JJ710379(v=AX.60)
ms:contentKeyID: 49384272
author: tonyafehr
ms.date: 07/23/2014
mtps_version: v=AX.60
---

# Retail cube (RetailCube) for Microsoft Dynamics AX 2012 R2 and R3 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The Retail cube for Microsoft Dynamics AX is used to help manage a chain of stores so that your business can improve service, manage growth, reach customers, and streamline efficiencies. This article provides details about the cube.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><img src="images/JJ710380.TopicIcons_Reference(AX.60).png" title="Reference" alt="Reference" />
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


## Deployment

The Retail cube is included in the Dynamics AX project. For information about how deploy the Dynamics AX project—and the cubes that it contains—see [Deploy the default cubes](deploy-the-default-cubes.md).

## Configuration keys

The following configuration keys are required to use all features of the Retail cube:

  - Retail Headquarters (RetailHeadquarters)

## Tables and views

The Retail cube uses data from the following tables and views:

  - InventSite table

  - MCRSourceCodeSetup table

  - RetailHour table

  - RetailTenderTypeTable table

  - CustPackingSlipTransExpanded view

  - CustTableCube view

  - InventTableExpanded view

  - MCRSourceSalesSummary view

  - PdsRebateExpanded view

  - RetailCategoryExpanded view

  - RetailChannelView view

  - RetailCustInvoiceJourView view

  - RetailCustInvoiceTransExpanded view

  - RetailInventValueCube view

  - RetailOMHierarchyView view

  - RetailTerminalView view

  - RetailTransactionDiscountTransView view

  - RetailTransactionPaymentTransView view

  - RetailTransactionSalesTransView view

  - RetailTransactionTableView view

  - RetailTransactionTaxTransView view

  - SalesLineExpanded view


> [!NOTE]
> <P>The MCRSourceCodeSetup table and the MCRSourceSalesSummary and PdsRebateExpanded views are used with this cube only in Microsoft Dynamics AX 2012 R3.</P>



## Measures

The Retail cube includes the following measure groups.

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
<p>Worker</p></td>
</tr>
</tbody>
</table>


## Retail transaction discounts

This measure group is based on the RetailTransactionDiscountTransView view and includes the following measures.

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
    <th colspan="1"> <p>
   
	 Description
  </p> </th>
    <th> <p>
   
	 Associated dimensions
  </p> </th>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Retail transaction discounts count
  </p> </td>
    <td colspan="1"> <p>
   
	 Not applicable
  </p> </td>
    <td colspan="1"> <p>
   
	 Count
  </p> </td>
    <td colspan="1"> <p>
   
	 The number of transaction discounts.
  </p> </td>
    <td rowspan="2"> <p>
   
	 Company
  </p> <p>
   
	 Hour of day
  </p> <p>
   
	 Customer
  </p> <p>
   
	 Released products
  </p> <p>
   
	 Retail channel
  </p> <p>
   
	 POS terminal
  </p> <p>
   
	 Worker
  </p> <p>
   
	 Date
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Cash discount amount
  </p> </td>
    <td colspan="1"> <p>
   
	 RetailTransactionDiscountTransView.Amount
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 The amount of cash discount.
  </p> </td>
  </tr>
</table>


## Retail transaction payments

This measure group is based on the RetailTransactionPaymentTransView view and includes the following measures.

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
    <th colspan="1"> <p>
   
	 Description
  </p> </th>
    <th> <p>
   
	 Associated dimensions
  </p> </th>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Retail transaction payments count
  </p> </td>
    <td colspan="1"> <p>
   
	 Not applicable
  </p> </td>
    <td colspan="1"> <p>
   
	 Count
  </p> </td>
    <td colspan="1"> <p>
   
	 The number of retail transaction payments.
  </p> </td>
    <td rowspan="5"> <p>
   
	 Currency
  </p> <p>
   
	 Company
  </p> <p>
   
	 Hour of day
  </p> <p>
   
	 Payment methods
  </p> <p>
   
	 Customer
  </p> <p>
   
	 POS terminal
  </p> <p>
   
	 Retail channel
  </p> <p>
   
	 Worker
  </p> <p>
   
	 Retail transaction payments
  </p> <p>
   
	 Date
  </p> <p>
   
	 Date (exchange rate date)
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Payment amount in transaction currency
  </p> </td>
    <td colspan="1"> <p>
   
	 RetailTransactionPaymentTransView.AmountCur
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 The total transaction amount in the transaction currency.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Payment amount
  </p> </td>
    <td> <p>
   
	 RetailTransactionPaymentTransView.AmountMST
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total transaction amount.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Tendered
  </p> </td>
    <td> <p>
   
	 RetailTransactionPaymentTransView.AmountTendered
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total amount tendered.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Quantity
  </p> </td>
    <td> <p>
   
	 RetailTransactionPaymentTransView.Qty
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total quantity value of all products.
  </p> </td>
  </tr>
</table>


## Retail transaction lines

This measure group is based on the RetailTransactionSalesTransView view and includes the following measures.

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
    <th colspan="1"> <p>
   
	 Description
  </p> </th>
    <th> <p>
   
	 Associated dimensions
  </p> </th>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Retail transaction lines count
  </p> </td>
    <td colspan="1"> <p>
   
	 Not applicable
  </p> </td>
    <td colspan="1"> <p>
   
	 Count
  </p> </td>
    <td colspan="1"> <p>
   
	 The total number of transaction lines.
  </p> </td>
    <td rowspan="14"> <p>
   
	 Currency
  </p> <p>
   
	 Company
  </p> <p>
   
	 Sites
  </p> <p>
   
	 Released products
  </p> <p>
   
	 Hour of day
  </p> <p>
   
	 Customer
  </p> <p>
   
	 POS terminal
  </p> <p>
   
	 Retail category
  </p> <p>
   
	 Retail channel
  </p> <p>
   
	 Warehouses
  </p> <p>
   
	 Worker
  </p> <p>
   
	 Retail transaction lines
  </p> <p>
   
	 Date
  </p> <p>
   
	 Date (exchange rate date)
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Discount percentage
  </p> </td>
    <td colspan="1"> <p>
   
	 RetailTransactionSalesTransView.TotalDiscPct
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 The total discount points.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Unit quantity
  </p> </td>
    <td> <p>
   
	 RetailTransactionSalesTransView.UnitQty
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total unit quantity.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Cost amount
  </p> </td>
    <td> <p>
   
	 RetailTransactionSalesTransView.CostAmount
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total cost amount.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Customer discount
  </p> </td>
    <td> <p>
   
	 RetailTransactionSalesTransView.CustDiscAmount
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total customer discount.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Discount amount
  </p> </td>
    <td> <p>
   
	 RetailTransactionSalesTransView.DiscAmount
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total discount amount.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Line discount amount
  </p> </td>
    <td> <p>
   
	 RetailTransactionSalesTransView.LineDscAmount
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total line discount amount.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Net amount
  </p> </td>
    <td> <p>
   
	 RetailTransactionSalesTransView.NetAmount
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total net amount.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Net amount including tax
  </p> </td>
    <td> <p>
   
	 RetailTransactionSalesTransView.NetAmountInclTax
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total net amount including tax.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Net price
  </p> </td>
    <td> <p>
   
	 RetailTransactionSalesTransView.NetPrice
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total net price.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Periodic discount amount
  </p> </td>
    <td> <p>
   
	 RetailTransactionSalesTransView.PeriodicDiscAmount
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total periodic discount amount.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Price
  </p> </td>
    <td> <p>
   
	 RetailTransactionSalesTransView.Price
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total price.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Sales transactions quantity
  </p> </td>
    <td> <p>
   
	 RetailTransactionSalesTransView.Qty
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total transaction quantity.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Return quantity
  </p> </td>
    <td> <p>
   
	 RetailTransactionSalesTransView.ReturnQty
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total return quantity.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Total discount amount
  </p> </td>
    <td> <p>
   
	 RetailTransactionSalesTransView.TotalDiscAmount
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total discount amount.
  </p> </td>
    <td rowspan="4"> <p></p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Rounded amount
  </p> </td>
    <td> <p>
   
	 RetailTransactionSalesTransView.TotalRoundedAmount
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total rounded amount.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Unit price
  </p> </td>
    <td> <p>
   
	 RetailTransactionSalesTransView.UnitPrice
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total unit price.
  </p> </td>
  </tr>
</table>


## Retail transactions

This measure group is based on the RetailTransactionTableView view and includes the following measures.

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
    <th colspan="1"> <p>
   
	 Description
  </p> </th>
    <th> <p>
   
	 Associated dimensions
  </p> </th>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Retail transactions count
  </p> </td>
    <td colspan="1"> <p>
   
	 Not applicable
  </p> </td>
    <td colspan="1"> <p>
   
	 Count
  </p> </td>
    <td colspan="1"> <p>
   
	 The number of transactions.
  </p> </td>
    <td rowspan="17"> <p>
   
	 Currency
  </p> <p>
   
	 Company
  </p> <p>
   
	 Sites
  </p> <p>
   
	 Hour of day
  </p> <p>
   
	 Customer
  </p> <p>
   
	 POS terminal
  </p> <p>
   
	 Retail channel
  </p> <p>
   
	 Warehouses
  </p> <p>
   
	 Worker
  </p> <p>
   
	 Retail transactions
  </p> <p>
   
	 POS terminal (POS terminal – register number)
  </p> <p>
   
	 POS terminal (POS terminal – register number 1)
  </p> <p>
   
	 Date
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Customer account
  </p> </td>
    <td colspan="1"> <p>
   
	 RetailTransactionTableView.CustAccount
  </p> </td>
    <td colspan="1"> <p>
   
	 DistinctCount
  </p> </td>
    <td colspan="1"> <p>
   
	 The number of customers.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Number of invoices
  </p> </td>
    <td> <p>
   
	 RetailTransactionTableView.NumberOfInvoices
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total number of invoices.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Number of product lines
  </p> </td>
    <td> <p>
   
	 RetailTransactionTableView.NumberOfItemLines
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total number of product lines.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Number of products
  </p> </td>
    <td> <p>
   
	 RetailTransactionTableView.NumberOfItems
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total number of items.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Number of payment lines
  </p> </td>
    <td> <p>
   
	 RetailTransactionTableView.NumberOfPaymentLines
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total number of payment lines.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Amount to account
  </p> </td>
    <td> <p>
   
	 RetailTransactionTableView.AmountToAccount
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total amount owed on account.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Retail transaction cost amount
  </p> </td>
    <td> <p>
   
	 RetailTransactionTableView.CostAmount
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total cost amount.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Retail transaction customer discount
  </p> </td>
    <td> <p>
   
	 RetailTransactionTableView.CustDiscAmount
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total discount amount.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Retail transaction discount amount
  </p> </td>
    <td> <p>
   
	 RetailTransactionTableView.DiscAmount
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total discount amount.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Gross amount
  </p> </td>
    <td> <p>
   
	 RetailTransactionTableView.GrossAmount
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total gross amount.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Retail transaction net amount
  </p> </td>
    <td> <p>
   
	 RetailTransactionTableView.NetAmount
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total net amount.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Retail transactions payment amount
  </p> </td>
    <td> <p>
   
	 RetailTransactionTableView.PaymentAmount
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total payment amount.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Retail transactions rounded amount
  </p> </td>
    <td> <p>
   
	 RetailTransactionTableView.RoundedAmount
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total rounded amount.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Sales invoice amount
  </p> </td>
    <td> <p>
   
	 RetailTransactionTableView.SalesInvoiceAmount
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total invoice amount.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Sales order amount
  </p> </td>
    <td> <p>
   
	 RetailTransactionTableView.SalesOrderAmount
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total sales order amount.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Retail transaction total discount amount
  </p> </td>
    <td> <p>
   
	 RetailTransactionTableView.TotalDiscAmount
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total discount amount.
  </p> </td>
  </tr>
</table>


## Retail transaction taxes

This measure group is based on the RetailTransactionTaxTransView view and includes the following measures.

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
    <th colspan="1"> <p>
   
	 Description
  </p> </th>
    <th> <p>
   
	 Associated dimensions
  </p> </th>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Retail transaction taxes count
  </p> </td>
    <td colspan="1"> <p>
   
	 Not applicable
  </p> </td>
    <td colspan="1"> <p>
   
	 Count
  </p> </td>
    <td colspan="1"> <p>
   
	 The number of transaction tax lines.
  </p> </td>
    <td rowspan="2"> <p>
   
	 Company
  </p> <p>
   
	 Hour of day
  </p> <p>
   
	 Customer
  </p> <p>
   
	 POS terminal
  </p> <p>
   
	 Retail channel
  </p> <p>
   
	 Worker
  </p> <p>
   
	 Date
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Tax amount
  </p> </td>
    <td colspan="1"> <p>
   
	 RetailTransactionTaxTransView.Amount
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 The total tax amount.
  </p> </td>
  </tr>
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
<p>Colors</p>
<p>Configurations</p>
<p>Sizes</p>
<p>Projects</p>
<p>Sales order lines</p>
<p>Date (confirmed ship date on 1st packing slip)</p>
<p>Date (requested ship date on 1st packing slip)</p>
<p>Sales category (sales category – historic)</p>
<p>Units (sales units)</p></td>
</tr>
</tbody>
</table>


## Retail channel

This measure group is based on the RetailChannelView view in Microsoft Dynamics AX 2012 R3 and on the RetailInventValueCube view in prior releases. It includes the following measures.

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
    <th colspan="1"> <p>
   
	 Description
  </p> </th>
    <th> <p>
   
	 Associated dimensions
  </p> </th>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Retail channel count
  </p> </td>
    <td colspan="1"> <p>
   
	 Not applicable
  </p> </td>
    <td colspan="1"> <p>
   
	 Count
  </p> </td>
    <td colspan="1"> <p>
   
	 The number of retail channels.
  </p> </td>
    <td rowspan="2"> <p>
   
	 Retail channel
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Store area
  </p> </td>
    <td colspan="1"> <p>
   
	 In Microsoft Dynamics AX 2012 R3, RetailChannelView.StoreArea.
  </p> <p>
   
	 In prior releases, RetailInventValueCube.StoreArea.
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 The total unit of area.
  </p> </td>
  </tr>
</table>


## Customer invoice lines

This measure group is based on the RetailCustInvoiceTransExpanded view in Microsoft Dynamics AX 2012 R3 and on the CustInvoiceTransExpanded view in prior releases. It includes the following measures.

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
   
	 Sites
  </p> <p>
   
	 Released products
  </p> <p>
   
	 Hour of day
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
   
	 Worker
  </p> <p>
   
	 Styles
  </p> <p>
   
	 Colors
  </p> <p>
   
	 Configurations
  </p> <p>
   
	 Fiscal period date
  </p> <p>
   
	 Retail customer invoice transaction
  </p> <p>
   
	 Date
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
   
	 Commission line amount – accounting currency
  </p> </td>
    <td> <p>
   
	 In Microsoft Dynamics AX 2012 R3, RetailCustInvoiceTransExpanded.CommissAmountMST. 
  </p> <p>
   
	 In prior releases, CustInvoiceTransExpanded.CommissAmountMST.
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
   
	 In Microsoft Dynamics AX 2012 R3, RetailCustInvoiceTransExpanded.Qty. 
  </p> <p>
   
	 In prior releases, CustInvoiceTransExpanded.Qty.
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
   
	 In Microsoft Dynamics AX 2012 R3, RetailCustInvoiceTransExpanded.QtyPhysical. 
  </p> <p>
   
	 In prior releases, CustInvoiceTransExpanded.QtyPhysical.
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
   
	 In Microsoft Dynamics AX 2012 R3, RetailCustInvoiceTransExpanded.TaxAmountMST. 
  </p> <p>
   
	 In prior releases, CustInvoiceTransExpanded.TaxAmountMST.
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
   
	 In Microsoft Dynamics AX 2012 R3, RetailCustInvoiceTransExpanded.COGS. 
  </p> <p>
   
	 In prior releases, CustInvoiceTransExpanded.COGS.
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
   
	 In Microsoft Dynamics AX 2012 R3, RetailCustInvoiceTransExpanded.InventQty. 
  </p> <p>
   
	 In prior releases, CustInvoiceTransExpanded.InventQty.
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
   
	 In Microsoft Dynamics AX 2012 R3, RetailCustInvoiceTransExpanded.LineAmountMST. 
  </p> <p>
   
	 In prior releases, CustInvoiceTransExpanded.LineAmountMST.
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
   
	 In Microsoft Dynamics AX 2012 R3, RetailCustInvoiceTransExpanded.LineAmountTaxMST. 
  </p> <p>
   
	 In prior releases, CustInvoiceTransExpanded.LineAmountTaxMST.
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


## Inventory value

This measure group is based on the RetailInventValueCube view and includes the following measures.

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
    <th colspan="1"> <p>
   
	 Description
  </p> </th>
    <th> <p>
   
	 Associated dimensions
  </p> </th>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Net amount change
  </p> </td>
    <td colspan="1"> <p>
   
	 RetailInventValueCube.Amount
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 The sum of transactions between two periods, in monetary value.
  </p> </td>
    <td rowspan="2"> <p>
   
	 Company
  </p> <p>
   
	 Sites
  </p> <p>
   
	 Released products
  </p> <p>
   
	 Retail category
  </p> <p>
   
	 Styles
  </p> <p>
   
	 Colors
  </p> <p>
   
	 Configurations
  </p> <p>
   
	 Sizes
  </p> <p>
   
	 Fiscal period date
  </p> <p>
   
	 Retail inventory value
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Net quantity change
  </p> </td>
    <td colspan="1"> <p>
   
	 RetailInventValueCube.Qty
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 The sum of transactions between two periods, disregarding the unit of measure.
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
<td><p>Count of rebate given or applied.</p></td>
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
<td><p>Corrected rebate amount</p></td>
<td><p>PDSRebateExpanded.PDSCorrectedRebateAmt</p></td>
<td><p>Sum</p></td>
<td><p>Corrected rebate amount associated with a sales line, invoice or ledger account.</p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


## Calculated measures

The Retail cube contains the following calculated measures.

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
<td><p>The sales order lines that have a status of delivered or invoiced, and have at least one packing slip.</p></td>
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
<td><p>Beginning quantity</p></td>
<td><p>Sum</p></td>
<td><p>Inventory value</p></td>
<td><p>The balance as of period start, disregarding the unit of measure.</p></td>
</tr>
<tr class="odd">
<td><p>Ending quantity</p></td>
<td><p>Sum</p></td>
<td><p>Inventory value</p></td>
<td><p>The balance as of period end, disregarding the unit of measure.</p></td>
</tr>
<tr class="even">
<td><p>Net issues quantity</p></td>
<td><p>Sum</p></td>
<td><p>Inventory value</p></td>
<td><p>The sum of issue transactions holding an <strong>InventTransType</strong> specified in the <strong>Issue transaction</strong> field, disregarding the unit of measure.</p></td>
</tr>
<tr class="odd">
<td><p>Beginning amount</p></td>
<td><p>Sum</p></td>
<td><p>Inventory value</p></td>
<td><p>The balance as of period start, in monetary value.</p></td>
</tr>
<tr class="even">
<td><p>Ending amount</p></td>
<td><p>Sum</p></td>
<td><p>Inventory value</p></td>
<td><p>The balance as of period end, in monetary value.</p></td>
</tr>
<tr class="odd">
<td><p>Net issues amount</p></td>
<td><p>Sum</p></td>
<td><p>Inventory value</p></td>
<td><p>The sum of issue transactions holding an <strong>InventTransType</strong> specified in the <strong>Issue transaction</strong> field, in monetary value.</p></td>
</tr>
<tr class="even">
<td><p>Days to date</p></td>
<td><p>Sum</p></td>
<td><p>Undefined</p></td>
<td><p>The number of days between periods.</p></td>
</tr>
<tr class="odd">
<td><p>Products with transactions quantity</p></td>
<td><p>Sum</p></td>
<td><p>Not applicable</p></td>
<td><p>The products that hold an ending balance of type <strong>Quantity</strong>.</p></td>
</tr>
<tr class="even">
<td><p>Product rank quantity</p></td>
<td><p>Sum</p></td>
<td><p>Inventory value</p></td>
<td><p>The numeric ranking of products based on quantity.</p></td>
</tr>
<tr class="odd">
<td><p>Cumulative quantity</p></td>
<td><p>Sum</p></td>
<td><p>Inventory value</p></td>
<td><p>The cumulative quantity value of product N.</p></td>
</tr>
<tr class="even">
<td><p>Cumulative quantity previous</p></td>
<td><p>Sum</p></td>
<td><p>Undefined</p></td>
<td><p>The cumulative quantity value of product N-1.</p></td>
</tr>
<tr class="odd">
<td><p>Total quantity</p></td>
<td><p>Sum</p></td>
<td><p>Inventory value</p></td>
<td><p>The total quantity value of all products.</p></td>
</tr>
<tr class="even">
<td><p>Cumulative % of the total quantity</p></td>
<td><p>Sum</p></td>
<td><p>Inventory value</p></td>
<td><p>The cumulative percentage of the total quantity of product N.</p></td>
</tr>
<tr class="odd">
<td><p>Cumulative % of the total quantity previous</p></td>
<td><p>Sum</p></td>
<td><p>Inventory value</p></td>
<td><p>The cumulative percentage of the total quantity of product N-1.</p></td>
</tr>
<tr class="even">
<td><p>ABC category quantity</p></td>
<td><p>Sum</p></td>
<td><p>Inventory value</p></td>
<td><p>The ABC classification of the product based on quantity measurement (C:80%, B:15%, A:5%).</p></td>
</tr>
<tr class="odd">
<td><p>Products with transactions amount</p></td>
<td><p>Sum</p></td>
<td><p>Not applicable</p></td>
<td><p>The products that hold an ending balance of type <strong>Amount</strong>.</p></td>
</tr>
<tr class="even">
<td><p>Product rank amount</p></td>
<td><p>Sum</p></td>
<td><p>Inventory value</p></td>
<td><p>The numeric ranking of products based on quantity.</p></td>
</tr>
<tr class="odd">
<td><p>Cumulative amount</p></td>
<td><p>Sum</p></td>
<td><p>Inventory value</p></td>
<td><p>The cumulative amount of product N.</p></td>
</tr>
<tr class="even">
<td><p>Cumulative amount previous</p></td>
<td><p>Sum</p></td>
<td><p>Undefined</p></td>
<td><p>The cumulative amount of product N-1.</p></td>
</tr>
<tr class="odd">
<td><p>Total amount</p></td>
<td><p>Sum</p></td>
<td><p>Inventory value</p></td>
<td><p>The total amount of all products.</p></td>
</tr>
<tr class="even">
<td><p>Cumulative % of the total amount</p></td>
<td><p>Sum</p></td>
<td><p>Inventory value</p></td>
<td><p>The cumulative percentage of the total amount of product N.</p></td>
</tr>
<tr class="odd">
<td><p>Cumulative % of the total amount previous</p></td>
<td><p>Sum</p></td>
<td><p>Undefined</p></td>
<td><p>The cumulative percentage of the total amount of product N-1.</p></td>
</tr>
<tr class="even">
<td><p>ABC category amount</p></td>
<td><p>Sum</p></td>
<td><p>Inventory value</p></td>
<td><p>The ABC classification of the product based on amount measurement (C:80%, B:15%, A:5%).</p></td>
</tr>
<tr class="odd">
<td><p>Inventory turn quantity</p></td>
<td><p>Sum</p></td>
<td><p>Inventory value</p></td>
<td><p>This value is calculated as: Net issues quantity / ((Beginning quantity + Ending quantity) / 2)</p></td>
</tr>
<tr class="even">
<td><p>Inventory turn amount</p></td>
<td><p>Sum</p></td>
<td><p>Inventory value</p></td>
<td><p>This value is calculated as: Net issues amount / ((Beginning amount + Ending amount) / 2)</p></td>
</tr>
<tr class="odd">
<td><p>Gross margin return on inventory investment</p></td>
<td><p>Sum</p></td>
<td><p>Inventory value</p></td>
<td><p>Indicates how much gross margin a retailer gets back for each dollar invested in inventory. This value is calculated as: (Sales / Average inventory at cost) * Gross margin percentage</p></td>
</tr>
<tr class="even">
<td><p>Sell through rate</p></td>
<td><p>Sum</p></td>
<td><p>Inventory value</p></td>
<td><p>This value is calculated as: Net issues quantity / [Measures].[Beginning quantity]</p></td>
</tr>
<tr class="odd">
<td><p>Unit cost</p></td>
<td><p>Sum</p></td>
<td><p>Inventory value</p></td>
<td><p>This value is calculated as: Ending amount / Ending quantity</p></td>
</tr>
<tr class="even">
<td><p>Rank</p></td>
<td><p>Sum</p></td>
<td><p>Inventory value</p></td>
<td><p>The numeric ranking of products based on quantity.</p></td>
</tr>
<tr class="odd">
<td><p>Issue transactions</p></td>
<td><p>Sum</p></td>
<td><p>Not applicable</p></td>
<td><p>This value is used to filter <strong>InventTransType</strong> of type <strong>Sales</strong>, <strong>ProdLine</strong>, <strong>Project</strong>, <strong>Asset</strong>, <strong>KanbanJobPickingList</strong>, <strong>KanbanJobWIP</strong>, and <strong>KanbanEmptied</strong>.</p></td>
</tr>
<tr class="even">
<td><p>Returns</p></td>
<td><p>Sum</p></td>
<td><p>Retail transactions</p></td>
<td><p>The amount of total returns.</p></td>
</tr>
<tr class="odd">
<td><p>Gross profit margin</p></td>
<td><p>Sum</p></td>
<td><p>Customer invoice lines</p></td>
<td><p>The amount remaining after the cost of goods sold (COGS) has been deducted from the total sales for an item or a given quantity of inventory.</p></td>
</tr>
<tr class="even">
<td><p>Gross profit margin percentage</p></td>
<td><p>Sum</p></td>
<td><p>Customer invoice lines</p></td>
<td><p>Gross profit margin divided by the total sales revenue, expressed as a percentage. The gross profit margin represents the percent of total sales revenue that a retailer retains after incurring the direct costs associated with producing the goods and services sold. The higher the percentage, the more the retailer retains on each dollar of sales to service its other costs and obligations.</p></td>
</tr>
<tr class="odd">
<td><p>Average ticket</p></td>
<td><p>Average</p></td>
<td><p>Retail transactions</p></td>
<td><p>The average amount of a retail transaction.</p></td>
</tr>
<tr class="even">
<td><p>Average number of items per transaction</p></td>
<td><p>Average</p></td>
<td><p>Retail transactions</p></td>
<td><p>The average number of items per retail transaction.</p></td>
</tr>
<tr class="odd">
<td><p>Average number of payments per transaction</p></td>
<td><p>Average</p></td>
<td><p>Retail transactions</p></td>
<td><p>The average number of payments per transaction.</p></td>
</tr>
<tr class="even">
<td><p>Sales per unit area</p></td>
<td><p>Average</p></td>
<td><p>Retail transactions</p></td>
<td><p>The amount of sales per square foot or square meter.</p></td>
</tr>
</tbody>
</table>


## Key performance indicators

The following section describes the key performance indicators (KPIs) in the Retail cube.

## KPI calculations

The following table lists the KPIs that are associated with the Retail cube. You can use the information in the following table to help verify the information in your KPIs.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>KPI</p></th>
<th><p>Associated measure group</p></th>
<th><p>Calculation</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Days of inventory quantity</p></td>
<td><p>All</p></td>
<td><p>This value is calculated as: Ending quantity / (Net issues quantity / Days to date)</p></td>
</tr>
<tr class="even">
<td><p>Weeks of inventory quantity</p></td>
<td><p>All</p></td>
<td><p>This value is calculated as: Ending quantity / (Net issues quantity / (Days to date / 7))</p></td>
</tr>
<tr class="odd">
<td><p>Months of inventory quantity</p></td>
<td><p>All</p></td>
<td><p>This value is calculated as: Ending quantity / (Net issues quantity / (Days to date / 30 ))</p></td>
</tr>
<tr class="even">
<td><p>Inventory turn quantity</p></td>
<td><p>All</p></td>
<td><p>This value is calculated as: Net issues quantity / ((Beginning quantity + Ending quantity) / 2)</p></td>
</tr>
<tr class="odd">
<td><p>Days of inventory amount</p></td>
<td><p>All</p></td>
<td><p>This value is calculated as: Ending amount / (Net issues amount / Days to date)</p></td>
</tr>
<tr class="even">
<td><p>Weeks of inventory amount</p></td>
<td><p>All</p></td>
<td><p>This value is calculated as: Ending amount / (Net issues amount / (Days to date / 7 ))</p></td>
</tr>
<tr class="odd">
<td><p>Months of inventory amount</p></td>
<td><p>All</p></td>
<td><p>This value is calculated as: Ending amount / (Net issues amount / (Days to date / 30))</p></td>
</tr>
<tr class="even">
<td><p>Inventory turn amount</p></td>
<td><p>All</p></td>
<td><p>This value is calculated as: Net issues amount / ((Beginning amount + Ending amount) / 2)</p></td>
</tr>
<tr class="odd">
<td><p>Total sales</p></td>
<td><p>All</p></td>
<td><p>The total net amount.</p></td>
</tr>
<tr class="even">
<td><p>Total returns</p></td>
<td><p>Retail transaction</p></td>
<td><p>The amount of total returns.</p></td>
</tr>
<tr class="odd">
<td><p>Average ticket size</p></td>
<td><p>Retail transaction</p></td>
<td><p>This value is calculated as: Gross amount / Retail transactions count</p></td>
</tr>
<tr class="even">
<td><p>COGS</p></td>
<td><p>Customer invoice lines</p></td>
<td><p>The cost of goods sold (COGS) for the particular invoiced item. The COGS value is based on the corresponding inventory transaction. This measure may need an inventory closing where a potential adjustment may occur.</p></td>
</tr>
<tr class="odd">
<td><p>Gross margin</p></td>
<td><p>Customer invoice lines</p></td>
<td><p>The amount remaining after the cost of goods sold (COGS) has been deducted from the total sales for an item or a given quantity of inventory.</p></td>
</tr>
<tr class="even">
<td><p>Gross margin percentage</p></td>
<td><p>Customer invoice lines</p></td>
<td><p>The gross profit margin divided by the total sales revenue, expressed as a percentage. The gross profit margin represents the percent of total sales revenue that a retailer retains after incurring the direct costs associated with producing the goods and services sold. The higher the percentage, the more the retailer retains on each dollar of sales to service its other costs and obligations.</p></td>
</tr>
<tr class="odd">
<td><p>Sales by hour</p></td>
<td><p>Retail transaction lines</p></td>
<td><p>The average net amount of sales revenue by hour.</p></td>
</tr>
<tr class="even">
<td><p>Inventory turnover</p></td>
<td><p>Inventory value</p></td>
<td><p>This value is calculated as: Net issues amount / ((Beginning amount + Ending amount) / 2)</p></td>
</tr>
<tr class="odd">
<td><p>GMROII</p></td>
<td><p>Inventory value</p></td>
<td><p>Indicates how much gross margin a retailer gets back for each dollar invested in inventory. This value is calculated as: (Sales / Average inventory at cost) * Gross margin percentage</p></td>
</tr>
<tr class="even">
<td><p>Sales per unit area</p></td>
<td><p>Retail transaction lines</p></td>
<td><p>The amount of sales per square foot or square meter.</p></td>
</tr>
<tr class="odd">
<td><p>Total customers</p></td>
<td><p>Retail transactions</p></td>
<td><p>The number of customers.</p></td>
</tr>
</tbody>
</table>


## Role Centers

By default, the KPIs of the Retail cube are not displayed on Role Center pages. For information about how to add them to Role Center pages, see [Manage KPIs](manage-kpis.md).

## Security

The Retail cube can be accessed by users assigned to the following Microsoft SQL Server Analysis Services roles.

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

  


