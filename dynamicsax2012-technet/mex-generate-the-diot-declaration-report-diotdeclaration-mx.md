---
title: (MEX) Generate the DIOT declaration report (DIOTDeclaration_MX)
TOCTitle: (MEX) Generate the DIOT declaration report (DIOTDeclaration_MX)
ms:assetid: 0c8a571c-2452-4d8c-8532-df96ec37feab
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh335132(v=AX.60)
ms:contentKeyID: 36687341
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.DIOTDeclaration_MX
---

# (MEX) Generate the DIOT declaration report (DIOTDeclaration\_MX) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Generate DIOT declaration** form generates a Declaración Informativa de Operaciones con Terceros (DIOT). The DIOT includes information about vendor transactions. VAT transaction details are also included as field concepts in the DIOT. Collections managers, accounts receivable clerks, accounts receivable managers, accountants, accounting managers, accounting supervisors, sales clerks, sales managers, and accounts payable clerks generate a DIOT to get information about the status of sales tax transactions.

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
<td><p>Select or enter the starting date of the reporting period.</p></td>
</tr>
<tr class="even">
<td><p><strong>To date</strong></p></td>
<td><p>Select or enter the ending date of the reporting period.</p></td>
</tr>
<tr class="odd">
<td><p><strong>DIOT report type</strong></p></td>
<td><p>Select one of the following options to indicate the type for the DIOT:</p>
<p><strong>1: consolidated</strong> – Summarizes the vendor transactions that are created for a specific Registro Federal de Contribuyentes (RFC) number or registration ID.</p>
<p><strong>2: detailed</strong> – Generates a detailed report that contains the information about all vendor transactions. Each line in the report represents a transaction.</p></td>
</tr>
<tr class="even">
<td><p><strong>Include transactions</strong></p></td>
<td><p>Select one of the following options to indicate the type of vendor invoice transactions to include in the report:</p>
<ul>
<li><p><strong>Open</strong> – Include transactions that have not been settled. In other words, transactions that have a current balance that is not equal to zero.</p></li>
<li><p><strong>Closed</strong> – Include transactions that have been settled. In other words, transactions that have a current balance that is equal to zero.</p></li>
<li><p><strong>All</strong> – Include all transactions.</p>
<div>

> [!NOTE]
> <P>This control is not available in versions of Microsoft Dynamics AX 2012 prior to cumulative update 6 for AX 2012 R2.</P>


</div></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>File name</strong></p></td>
<td><p>Specify the path and file name for the DIOT.</p></td>
</tr>
<tr class="even">
<td><p><strong>Generate file</strong></p></td>
<td><p>Select this check box to generate the DIOT as a text file.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Percentage of global vendor operations</strong></p></td>
<td><p>Enter the percentage of total transactions that are considered global vendor transactions.</p></td>
</tr>
<tr class="even">
<td><p><strong>Upper limit</strong></p></td>
<td><p>Enter the maximum transaction amount for a global vendor.</p></td>
</tr>
</tbody>
</table>


## How to work with reports

The following topics explain how to print a report and how to filter and sort the data on a report.

  - [Print or email a report](print-or-email-a-report.md)

  - [Filter the data on a report](filter-the-data-on-a-report.md)

  - [Sort the data on a report](sort-the-data-on-a-report.md)

## Details about this report

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
<td><p>DIOTDeclaration_MX</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports/Reports/DIOTDeclarationReport_MX</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>DIOTDeclarationReport_MX</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>Mexican tax reports</strong> &gt; <strong>Generate DIOT declaration</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - DIOTDeclarationTmp\_MX table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the DiotDeclarationDP_MX.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[(MEX) Generate a DIOT](mex-generate-a-diot.md)

[(MEX) Set up DIOT parameters](mex-set-up-diot-parameters.md)

[(MEX) Set up DIOT declaration (form)](https://technet.microsoft.com/en-us/library/hh242543\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

