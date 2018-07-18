---
title: (THA) Withholding tax report (TaxWithholdReport_TH)
TOCTitle: (THA) Withholding tax report (TaxWithholdReport_TH)
ms:assetid: 2c14b810-3af7-4e86-91ac-d1aaee31e5fd
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh352244(v=AX.60)
ms:contentKeyID: 36687869
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Individual
- SSRS_Reports.Reports.TaxWithholdReport_TH
- Tax
- Domestic
- Foreign
- Withholding tax
---

# (THA) Withholding tax report (TaxWithholdReport\_TH) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Withholding tax reports in Thailand must be generated and submitted to the Revenue Department of Thailand. Withholding tax reports can be printed in the following formats:

  - **Withholding tax (domestic)** – This report prints the withholding tax transactions of domestic vendors for a specified date range.

  - **Withholding tax (foreign)** – This report prints the withholding tax transactions of foreign vendors for a specified date range.

  - **Withholding tax (individual)** – This report prints the withholding tax transactions for individuals for a specified date range.

Withholding tax reports are typically used by accounting managers, accounts payable coordinators, and accountants to inquire into the status of sales tax transactions.


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
<td><p><strong>From date</strong></p></td>
<td><p>Select the starting date of the reporting period.</p></td>
</tr>
<tr class="even">
<td><p><strong>To date</strong></p></td>
<td><p>Select the ending date of the reporting period.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Date</strong></p></td>
<td><p>The date when the withholding tax transaction was posted.</p></td>
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
<td><p>TaxWithholdReport_TH</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\TaxWithholdReport_TH</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>TaxWithholdReportDomestic_TH</p>
<p>TaxWithholdReportForeign_TH</p>
<p>TaxWithholdReportIndividual_TH</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>External</strong> &gt; <strong>Withholding tax</strong> &gt; <strong>Withholding tax (domestic)</strong>.</p>
<p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>External</strong> &gt; <strong>Withholding tax</strong> &gt; <strong>Withholding tax (foreign)</strong>.</p>
<p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>External</strong> &gt; <strong>Withholding tax</strong> &gt; <strong>Withholding tax (individual)</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - DirPartyPostalAddressView table

  - TaxWithholdTrans table

  - VendTable table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


