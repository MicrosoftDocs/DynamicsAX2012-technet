---
title: Vendors report (Vend)
TOCTitle: Vendors report (Vend)
ms:assetid: 6d182cc2-bb7f-4d88-b6fd-666629b3f77f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa596416(v=AX.60)
ms:contentKeyID: 36941270
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.Vend
---

# Vendors report (Vend) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to view information about a vendor or a group of vendors.

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
<td><p>Click <strong>Select</strong>. In the <strong>VendorListBasic</strong> form, in the <strong>Criteria</strong> field, select a vendor account to display on the report. To add another vendor, click <strong>Add</strong>. If you do not select a vendor account, all vendor accounts are displayed on the report.</p></td>
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
<td><p>Vend</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\Vend</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>Vend</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Reports</strong> &gt; <strong>Vendors</strong> &gt; <strong>Vendors</strong>.</p>
<p>–or–</p>
<p>Click <strong>Procurement and sourcing</strong> &gt; <strong>Reports</strong> &gt; <strong>Vendors</strong> &gt; <strong>Vendors</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - VendorListBasicDP.processReport

  - VENDORLISTBASICTMP table

  - VendTable


> [!NOTE]
> <P>To determine where the data in the temp table comes from, view the cross-references for the VendorListBasicDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


