---
title: (MEX) Purchase tax report (TaxVATDetailedReport_MX)
TOCTitle: (MEX) Purchase tax report (TaxVATDetailedReport_MX)
ms:assetid: b62e4aba-6e09-48a2-99b2-3b37a0fd82d4
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh335165(v=AX.60)
ms:contentKeyID: 36687378
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.TaxVatDetailedReport_MX
---

# (MEX) Purchase tax report (TaxVATDetailedReport\_MX) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Purchase tax report** is used to print the details of all purchase transactions that have realized or unrealized VAT. This report is used to inquire into the status of sales tax transactions. This report is typically used by collections managers, accounts receivable clerks, accounts receivable managers, accountants, accounting managers, accounting supervisors, sales clerks, sales managers, and accounts payable clerks.


> [!NOTE]
> <P>(MEX) This report is available only to legal entities whose primary address is in Mexico.</P>



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
<td><p><strong>AX_CompanyName</strong></p></td>
<td><p>Enter the name of the company.</p></td>
</tr>
<tr class="even">
<td><p><strong>From date</strong></p></td>
<td><p>Select or enter the starting date to report the ledger transactions based on the posting date.</p></td>
</tr>
<tr class="odd">
<td><p><strong>To date</strong></p></td>
<td><p>Select or enter the ending date to report the ledger transactions based on the posting date.</p></td>
</tr>
<tr class="even">
<td><p><strong>From category tax report</strong></p></td>
<td><p>Select the code for the first tax report category that you want to include in the tax report. Tax report categories that come after this code are included in the tax report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>To category tax report</strong></p></td>
<td><p>Select the code for the last tax report category that you want to include in the tax report. Tax report categories that precede this code are included in the tax report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Type of report</strong></p></td>
<td><p>Select the type of report that you want to generate:</p>
<ul>
<li><p><strong>Both</strong> – Both realized and unrealized VAT purchase transactions are printed.</p></li>
<li><p><strong>Realized</strong> – Only realized VAT purchase transactions are printed.</p></li>
<li><p><strong>Unrealized</strong> – Only unrealized VAT purchase transactions are printed.</p></li>
</ul></td>
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
<td><p>TaxVATDetailedReport_MX</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\TaxVATDetailedReport_MX</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>TaxVatPurchReport_MX</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>Mexican tax reports</strong> &gt; <strong>Purchase tax</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - TaxVatDetailedReportTmp\_MX table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the TaxVatReportDetailedDP_MX.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[(MEX) Generate the purchase tax report](mex-generate-the-purchase-tax-report.md)

[(MEX) Generate the purchase tax report](mex-generate-the-purchase-tax-report.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

