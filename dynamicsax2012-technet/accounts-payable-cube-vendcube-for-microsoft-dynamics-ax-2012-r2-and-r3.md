---
title: Accounts payable cube (VendCube) for Microsoft Dynamics AX 2012 R2 and R3
TOCTitle: Accounts payable cube (VendCube)
ms:assetid: cb3330ff-1771-469a-9ab8-94511ad1cc88
ms:mtpsurl: https://technet.microsoft.com/library/JJ710396(v=AX.60)
ms:contentKeyID: 49384288
author: Khairunj
ms.author: daxcpft
ms.date: 07/23/2014
mtps_version: v=AX.60
---

# Accounts payable cube (VendCube) for Microsoft Dynamics AX 2012 R2 and R3 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The Accounts payable cube for Microsoft Dynamics AX is used to report on purchase transactions. This article provides details about the cube.

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

The Accounts payable cube is included in the Dynamics AX project. For information about how deploy the Dynamics AX project—and the cubes that it contains—see [Deploy the default cubes](deploy-the-default-cubes.md).

## Configuration keys

The following configuration keys are required to use all features of the Accounts payable cube:

  - General ledger (LedgerBasic)

## Tables and views

The Accounts payable cube uses data from the following tables and views:

  - VendPaymModeTable table

  - VendTransCube view

  - VendTransOpenCube view

  - VendTransTotalPurchasesCube view

## Measures

The Accounts payable cube includes the following measure groups.

## Open vendor transactions

This measure group is based on the VendTransOpenCube view and includes the following measures.

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
<td><p>Accounts payable open amount – accounting currency</p></td>
<td><p>VendTransOpenCube.AmountMST</p></td>
<td><p>Sum</p></td>
<td><p>The total open vendor transaction amount, in accounting currency.</p></td>
<td><p>Company</p>
<p>Vendor</p>
<p>Date (transaction date)</p>
<p>Date (due date)</p>
<p>Date (exchange rate date)</p>
<p>Fiscal period date (transaction date – fiscal calendar)</p>
<p>Fiscal period date (due date – fiscal calendar)</p>
<p>Date (cash discount date)</p>
<p>Fiscal period date (cash discount date – fiscal calendar)</p></td>
</tr>
</tbody>
</table>


## Vendor transactions

This measure group is based on the VendTransCube view and includes the following measures.

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
   
	 Accounts payable amount – transaction currency
  </p> </td>
    <td colspan="1"> <p>
   
	 VendTransCube.AmountCur
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 The total vendor transaction amount, in transaction currency.
  </p> </td>
    <td rowspan="4"> <p>
   
	 Currency
  </p> <p>
   
	 Company
  </p> <p>
   
	 Vendor
  </p> <p>
   
	 Methods of payment - vendor
  </p> <p>
   
	 Vendor transaction
  </p> <p>
   
	 Date (transaction date)
  </p> <p>
   
	 Date (due date)
  </p> <p>
   
	 Date (last settlement date)
  </p> <p>
   
	 Date (closed date)
  </p> <p>
   
	 Date (document date)
  </p> <p>
   
	 Date (approved date)
  </p> <p>
   
	 Date (exchange rate date)
  </p> <p>
   
	 Fiscal period date (last settlement date – fiscal calendar)
  </p> <p>
   
	 Fiscal period date (closed date – fiscal calendar)
  </p> <p>
   
	 Fiscal period date (transaction date – fiscal calendar)
  </p> <p>
   
	 Fiscal period date (document date – fiscal calendar)
  </p> <p>
   
	 Fiscal period date (approved date – fiscal calendar)
  </p> <p>
   
	 Fiscal period date (due date – fiscal calendar)
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Accounts payable settled amount – transaction currency
  </p> </td>
    <td> <p>
   
	 VendTransCube.SettleAmountCur
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total amount of vendor transactions that have been settled, in transaction currency.
  </p> </td>
  </tr>
  <tr>
    <td colspan="1"> <p>
   
	 Accounts payable amount – accounting currency
  </p> </td>
    <td colspan="1"> <p>
   
	 VendTransCube.AmountMST
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 The total vendor transaction amount, in accounting currency.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Accounts payable settled amount – accounting currency
  </p> </td>
    <td> <p>
   
	 VendTransCube.SettleAmountMST
  </p> </td>
    <td> <p>
   
	 Sum
  </p> </td>
    <td> <p>
   
	 The total amount of vendor transactions that have been settled, in accounting currency.
  </p> </td>
  </tr>
</table>


## Total vendor purchases

This measure group is based on the VendTransTotalPurchasesCube view and includes the following measures.

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
   
	 Accounts payable total – accounting currency
  </p> </td>
    <td colspan="1"> <p>
   
	 VendTransTotalPurchasesCube.AmountMST
  </p> </td>
    <td colspan="1"> <p>
   
	 Sum
  </p> </td>
    <td colspan="1"> <p>
   
	 The total purchases amount, in accounting currency.
  </p> </td>
    <td rowspan="4"> <p>
   
	 Currency
  </p> <p>
   
	 Company
  </p> <p>
   
	 Vendor
  </p> <p>
   
	 Methods of payment - vendor
  </p> <p>
   
	 Total vendor purchases
  </p> <p>
   
	 Date (transaction date)
  </p> <p>
   
	 Date (due date)
  </p> <p>
   
	 Date (last settlement date)
  </p> <p>
   
	 Date (closed date)
  </p> <p>
   
	 Date (document date)
  </p> <p>
   
	 Date (approved date)
  </p> <p>
   
	 Date (exchange rate date)
  </p> <p>
   
	 Fiscal period date (last settlement date – fiscal calendar)
  </p> <p>
   
	 Fiscal period date (closed date – fiscal calendar)
  </p> <p>
   
	 Fiscal period date (transaction date – fiscal calendar)
  </p> <p>
   
	 Fiscal period date (document date – fiscal calendar)
  </p> <p>
   
	 Fiscal period date (approved date – fiscal calendar)
  </p> <p>
   
	 Fiscal period date (due date – fiscal calendar)
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

The Accounts payable cube does not include any calculated measures.

## Key performance indicators

The Accounts payable cube does not include any key performance indicators (KPIs).

## Security

The Accounts payable cube can be accessed by users assigned to the following Microsoft SQL Server Analysis Services roles.

  - Accountant

  - Accounting manager

  - Accounting supervisor

  - Accounts payable centralized payments clerk

  - Accounts payable clerk

  - Accounts payable manager

  - Accounts payable payments clerk

  - Accounts receivable manager

  - Chief executive officer

  - Chief financial officer

  - Compliance manager

  - Financial controller

  - Purchasing manager

  - Treasurer

  


