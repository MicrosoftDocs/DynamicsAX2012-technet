---
title: (MEX) Provisional ISR payment report (ISRDetailedDeclaration_MX)
TOCTitle: (MEX) Provisional ISR payment report (ISRDetailedDeclaration_MX)
ms:assetid: 534a28a6-3312-489a-b93c-3548a6fbfe27
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh433493(v=AX.60)
ms:contentKeyID: 36941254
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- ISR
- SSRS_Reports.Reports.ISRDetailedDeclaration_MX
- MEX
---

# (MEX) Provisional ISR payment report (ISRDetailedDeclaration\_MX) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Provisional ISR payment report** displays the details of ledger transactions for each main account and Impuesto sobre la renta (ISR) report concept. The ISR report concept is a method based on which the ISR provisional payment is calculated. This report is used to verify the ledger transactions before you print a summary of ISR provisional payments. This report is typically used by chief executive officers, chief financial officers, compliance managers, accountants, accounting supervisors, financial controllers, and clerks to inquire into the status of the ledger transactions.

In the **Type of report** field, you must select **Details** to print the details of ledger transactions for each main account and ISR report concept in the **Provisional ISR payment report**.


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
<td><p><strong>Months</strong></p></td>
<td><p>Enter the number of months for the report. For example, if you enter 3, ledger transactions from the previous three months, starting on the day the report is generated, are included in the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Year</strong></p></td>
<td><p>Enter the year for the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Utility ratio</strong></p></td>
<td><p>Enter the utility ratio amount for the ISR provisional payment calculation.</p></td>
</tr>
<tr class="even">
<td><p><strong>Type of report</strong></p></td>
<td><p>Select the type of ISR report from the following options:</p>
<ul>
<li><p><strong>Details</strong> – Generate a detailed report with ledger transactions for each main account and ISR report concept.</p></li>
<li><p><strong>Summary</strong> – Generate the ISR report with a summary of ISR provisional payments.</p></li>
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
<td><p>ISRDetailedDeclaration_MX</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ISRDetailedDeclaration_MX</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>ISRDEtailedDeclaration_MX</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>External</strong> &gt; <strong>ISR reports</strong>. In the <strong>Months</strong>, <strong>Year</strong>, and <strong>Utility ratio</strong> fields, enter the number of months, year, and utility ratio. In the <strong>Type of report</strong> field, select <strong>Details</strong>, and then click <strong>OK</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - ISRDetailedDeclarationTmp\_MX table


> [!NOTE]
> <P>To find out where the data in the temp table comes from, view the cross-references for the ISRDetailedDeclarationDP_MX.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[(MEX) Generate an ISR provisional payment report](mex-generate-an-isr-provisional-payment-report.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

