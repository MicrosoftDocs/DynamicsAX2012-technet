---
title: (ITA) Withholding tax - certification report (TaxWithholdCertification_IT)
TOCTitle: (ITA) Withholding tax - certification report (TaxWithholdCertification_IT)
ms:assetid: eb8c01be-e35d-44a9-9278-50fa92ae7882
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh335171(v=AX.60)
ms:contentKeyID: 36687387
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.TaxWithholdCertification_IT
---

# (ITA) Withholding tax - certification report (TaxWithholdCertification\_IT) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Withholding tax - certification** report is used to print an Italian certification report in the withholding tax currency. The report is intended to be sent to the vendor with the withholding tax data for the specified period. This report is used to inquire into the status of sales tax transactions. This report is typically used by collections managers, accounts receivable clerks, accounts receivable managers, accountants, accounting managers, accounting supervisors, sales clerks, sales managers, and accounts payable clerks.


> [!NOTE]
> <P>(ITA) This report is available only to legal entities whose primary address is in Italy.</P>



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
<td><p>Select the range of vendor accounts to include in the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Payment date</strong></p></td>
<td><p>Enter the starting and ending payment dates.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Competence date</strong></p></td>
<td><p>Enter the starting and ending competence dates. The <strong>Competence date</strong> field on invoices or credit notes is filled in with the document date, but can be overwritten. Use this field to assign the withholding tax to the correct sales tax settlement period.</p></td>
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
<td><p>TaxWithholdCertification_IT</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\TaxWithholdCertification_IT</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>TaxWithholdCertificationIT</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>External</strong> &gt; <strong>Withholding tax - certification</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - TaxWithholdCertificationTmp\_IT Table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the TaxWithholdYearlyReportDP_IT.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

