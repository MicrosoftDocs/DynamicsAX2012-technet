---
title: (BEL) Statement print report (BankCodaDetails)
TOCTitle: (BEL) Statement print report (BankCodaDetails)
ms:assetid: c856f3be-60bb-4801-b24a-aecaa2825807
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh335167(v=AX.60)
ms:contentKeyID: 36687381
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- print
- Statement
- report
- SSRS_Reports.Reports.BankCodaDetails
---

# (BEL) Statement print report (BankCodaDetails) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Statement print** report displays the details of an imported coded statement of account (CODA) statement in a standard format. This report is typically used by accountants, treasurers, chief financial officers, accounts receivable managers, accounting managers, accounting supervisors, accounts payable managers, and financial controllers.


> [!NOTE]
> <P>(BEL) This report is available only to legal entities whose primary address is in Belgium.</P>



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
<td><p><strong>Bank statement</strong></p></td>
<td><p>The CODA bank statement number.</p></td>
</tr>
<tr class="even">
<td><p><strong>Bank statement date</strong></p></td>
<td><p>The date of the CODA bank statement.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Bank account</strong></p></td>
<td><p>The bank account number for which the CODA bank statement is imported.</p></td>
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
<td><p>BankCodaDetails</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\BankCodaDetails</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>BankCodaDetails</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Cash and bank management</strong> &gt; <strong>Common</strong> &gt; <strong>Bank accounts</strong>. Select a bank account, and then click <strong>CODA</strong>. In the <strong>Bank statement</strong> form, select a bank account, and then click <strong>CODA</strong> &gt; <strong>Statement print</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - BankCodaDetailsTmp table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the BankCodaDetailsDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[(BEL) About CIS](bel-about-cis.md)

[(BEL) Download bank statement files using CIS](bel-download-bank-statement-files-using-cis.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

