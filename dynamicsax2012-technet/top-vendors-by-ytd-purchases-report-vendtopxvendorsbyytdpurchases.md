---
title: Top vendors by YTD purchases report (VendTopXVendorsByYTDPurchases)
TOCTitle: Top vendors by YTD purchases report (VendTopXVendorsByYTDPurchases)
ms:assetid: 299c04d5-6945-455e-87c9-4d0040744e21
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh433487(v=AX.60)
ms:contentKeyID: 36941247
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.VendTopXVendorsByYTDPurchases
---

# Top vendors by YTD purchases report (VendTopXVendorsByYTDPurchases) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to view purchases from vendors during a fiscal period. You can filter the report to display only purchases by a specific legal entity of your organization.

## How to filter the data on this report

When you generate this report, the following default parameters are displayed. You can use these parameters to filter the data that will be displayed on the report. For more information, see [Filter the data on a report](filter-the-data-on-a-report.md).

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Field</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Company:</strong></p></td>
<td><p>Select a legal entity. Only the vendors for the selected legal entity are displayed on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Year:</strong></p></td>
<td><p>Select the start date for a fiscal period. Only vendor transactions during the fiscal period are displayed on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Number of records:</strong></p></td>
<td><p>Enter the maximum number of vendor records to display on the report. The value you select must be an integer.</p></td>
</tr>
</tbody>
</table>


## How to work with reports

The following topics explain how to print a report and how to filter and sort the data on a report.

  - [Print or email a report](print-or-email-a-report.md)

  - [Filter the data on a report](filter-the-data-on-a-report.md)

  - [Sort the data on a report](sort-the-data-on-a-report.md)

## Details of this report

The following table explains where to find the report in the Application Object Tree (AOT) and how to navigate to the report in the Microsoft Dynamics AX client.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Detail</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Name of report in the AOT</p></td>
<td><p>VendTopXVendorsbyYTDPurchases</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\VendTopXVendorsByYTDPurchases</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>VendTopXVendorsbyYTDPurchases</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Procurement and sourcing</strong> &gt; <strong>Reports</strong> &gt; <strong>Statistics</strong> &gt; <strong>Vendor</strong> &gt; <strong>Top vendors by YTD purchases</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - DynamicsAXOLAP cube

  - BICOMPANYVIEW table

  - LEDGERPERIODDATEDIMENSIONVIEW table

  - VENDTABLECUBE table

  - VENDTRANSTOTALPURCHASES table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


