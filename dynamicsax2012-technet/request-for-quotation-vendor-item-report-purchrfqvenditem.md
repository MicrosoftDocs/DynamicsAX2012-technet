---
title: Request for quotation vendor/item report (PurchRFQVendItem)
TOCTitle: Request for quotation vendor/item report (PurchRFQVendItem)
ms:assetid: d85811b6-d1f1-46eb-84b3-b3c066ec5893
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh433522(v=AX.60)
ms:contentKeyID: 36941305
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.PurchRFQVendItem
---

# Request for quotation vendor/item report (PurchRFQVendItem) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to view statistics about requests for quotations grouped by vendor, and then by item.

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
<td><p><strong>Vendor account</strong></p></td>
<td><p>Select a vendor account. Only the RFQs sent to this vendor are displayed on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Requester</strong></p></td>
<td><p>Select a requester name. Only the RFQs requested by this requester are displayed.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Expiration date</strong></p></td>
<td><p>Select an expiration date. Only the RFQs that expire on or before the selected date are displayed.</p></td>
</tr>
<tr class="even">
<td><p><strong>Highest status</strong></p></td>
<td><p>Select the highest RFQ status that you want to display on the report. For more information about RFQ statuses, see <a href="about-request-for-quotation-statuses.md">About request for quotation statuses</a>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Lowest status</strong></p></td>
<td><p>Select the lowest RFQ status that you want to display on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Buyer group</strong></p></td>
<td><p>Select the buyer group that you want to display on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Request for quotation</strong></p></td>
<td><p>Select a specific RFQ to display on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Item number</strong></p></td>
<td><p>Select an item. Only the RFQs that contain the selected line item are displayed on the report.</p></td>
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
<td><p>PurchRFQVendItem</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\PurchRFQVendItem</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>PurchRFQVendItem</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Procurement and sourcing</strong> &gt; <strong>Reports</strong> &gt; <strong>Statistics</strong> &gt; <strong>Request for quotation</strong> &gt; <strong>Request for quotation vendor/item</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - DirPerson table

  - HCMWORKER table

  - PURCHRFQLINE table

  - PURCHRFQREPLYLINE table

  - PURCHRFQTABLE

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[Request for quotation item/vendor report (PurchRFQItemVend)](request-for-quotation-item-vendor-report-purchrfqitemvend.md)

  


