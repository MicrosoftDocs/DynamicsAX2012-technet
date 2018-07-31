---
title: (THA) Withholding tax (Por Ngor Dor) report (TaxWithholdReportPND_TH)
TOCTitle: (THA) Withholding tax (Por Ngor Dor) report (TaxWithholdReportPND_TH)
ms:assetid: f016c4f5-2798-46a5-b28e-91c63482279c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh352295(v=AX.60)
ms:contentKeyID: 36687923
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.TaxWithholdReportPND_TH
- (THA)
- Por Ngor Dor
- Withholding tax report
---

# (THA) Withholding tax (Por Ngor Dor) report (TaxWithholdReportPND\_TH) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Withholding tax (Por Ngor Dor) report must be generated every month for withholding tax transactions. You can print this report in the following formats:

  - **Withholding tax (Por Ngor Dor 2)** – This report is printed for withholding tax returns for personal income.

  - **Withholding tax (Por Ngor Dor 3)** – This report is printed for withholding tax returns for individual vendors.

  - **Withholding tax (Por Ngor Dor 53)** – This report is printed for withholding tax returns for vendor organizations.

The Por Ngor Dor (PND) report that you generate can be based on the combination of withholding tax vendor type and item withholding tax groups that are set up in the **Withholding tax report setup** form. This report is typically used by accounting managers, accounts payable coordinators, and accountants to inquire into the status of sales tax transactions.


> [!NOTE]
> <P>(THA) This report is available only to legal entities whose primary address is in Thailand.</P>



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
<td><p><strong>To date</strong></p></td>
<td><p>Select the ending date for the reporting period.</p></td>
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
<td><p>TaxWithholdReportPND_TH</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\TaxWithholdReportPND_TH</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>TaxWithholdReportPND2_TH</p>
<p>TaxWithholdReportPND3_TH</p>
<p>TaxWithholdReportPND53_TH</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>External</strong> &gt; <strong>Withholding tax</strong> &gt; <strong>Withholding tax (Por Ngor Dor 2)</strong>.</p>
<p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>External</strong> &gt; <strong>Withholding tax</strong> &gt; <strong>Withholding tax (Por Ngor Dor 3)</strong>.</p>
<p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>External</strong> &gt; <strong>Withholding tax</strong> &gt; <strong>Withholding tax (Por Ngor Dor 53)</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - TaxWithholdReportPNDTmp\_TH table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the TaxWithholdReportPNDDP_TH.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[(THA) Withholding tax report setup (form)](https://technet.microsoft.com/en-us/library/hh227536\(v=ax.60\))

  


