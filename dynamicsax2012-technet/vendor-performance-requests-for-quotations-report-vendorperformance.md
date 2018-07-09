---
title: Vendor performance - requests for quotations report (VendorPerformance)
TOCTitle: Vendor performance - requests for quotations report (VendorPerformance)
ms:assetid: feef6e40-2c4c-4222-8c0b-d7ad3ceec778
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh433528(v=AX.60)
ms:contentKeyID: 36941314
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.VendorPerformance
---

# Vendor performance - requests for quotations report (VendorPerformance) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to view the statistics for requests for quotation (RFQ) replies from vendors that have successfully led to purchases. You can view the success rate by vendor.

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
<td><p><strong>From vendor</strong></p></td>
<td><p>Select a vendor account to specify the range of vendors to include on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>From date</strong></p></td>
<td><p>Select a starting date to specify which RFQs to include on the report. This is the date when the RFQ journals were created.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Success rate</strong></p></td>
<td><p>Select this check box to view how many vendor replies have been accepted compared to the number of RFQ lines that were sent to the vendor within the specified period of time.</p></td>
</tr>
<tr class="even">
<td><p><strong>Vendor importance</strong></p></td>
<td><p>Select this check box to view how many vendor replies were accepted compared to the total number of accepted replies within the specified period of time.</p></td>
</tr>
<tr class="odd">
<td><p><strong>To date</strong></p></td>
<td><p>Select an ending date to specify which RFQs to include on the report. This is the date when the RFQ journals were created.</p></td>
</tr>
<tr class="even">
<td><p><strong>To vendor</strong></p></td>
<td><p>Select a vendor account to specify the range of vendors to include on the report.</p></td>
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
<td><p>VendorPerformance</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\VendorPerformance</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>PurchRFQVendPerformance</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Procurement and sourcing</strong> &gt; <strong>Reports</strong> &gt; <strong>Statistics</strong> &gt; <strong>Request for quotation</strong> &gt; <strong>Vendor performance</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - PurchRFQVendorPerformanceTmp


> [!NOTE]
> <P>To determine where the data in the temp table comes from, view the cross-references for the PurchRFQVendPerformanceDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

