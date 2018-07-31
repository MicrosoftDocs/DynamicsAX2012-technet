---
title: Purchase agreement certification compliance report (Public sector) (PurchAgreementCertificationCompliance)
TOCTitle: Purchase agreement certification compliance report (Public sector) (PurchAgreementCertificationCompliance)
ms:assetid: 4af3dba2-8292-47e4-9537-76963b288a56
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh334479(v=AX.60)
ms:contentKeyID: 36676464
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- public sector
- purchase agreement
- SSRS_Reports.Reports.PurchAgreementCertificationCompliance
- vendor certification
- certification compliance
- purchase agreement certification compliance
- vendor certification compliance report
- vendor certification report
- vendor compliance
- vendor compliance report
---

# Purchase agreement certification compliance report (Public sector) (PurchAgreementCertificationCompliance) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Purchase agreement certification compliance** report to identify purchase agreements that have vendors and subcontractors who have not submitted required certification information or whose certification is nearing its expiration date.

This form is available only if the **Public Sector** configuration key is selected.

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
<td><p><strong>Purchase agreement classification</strong></p></td>
<td><p>Enter the classification to include in the report, or leave it blank to include all classifications.</p></td>
</tr>
<tr class="even">
<td><p><strong>Certification type</strong></p></td>
<td><p>Enter the certification type to include in the report, or leave it blank to include all types.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Generate report on expired certificates per date indicated</strong></p></td>
<td><p>Select this check box to limit the report to in-process certifications for which the documentation is past due.</p></td>
</tr>
<tr class="even">
<td><p><strong>Certifications past due</strong></p></td>
<td><p>To limit the report to certifications that have expired or will expire before a specific date, select the check box and enter the date.</p></td>
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
<td><p>PurchAgreementCertificationCompliance</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports \ Reports \ PurchAgreementCertificationCompliance</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>PurchAgreementCertificationCompliance</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Reports</strong> &gt; <strong>Purchase agreements</strong> &gt; <strong>Purchase agreement certification compliance</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - VendCertType

  - VendCertification

  - PurchAgreementCertification

  - VendTable

  - DirPartyTable

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


