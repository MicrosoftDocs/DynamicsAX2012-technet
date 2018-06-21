---
title: (DEU) Import account statement (transactions) report (LedgerInAccountStatementDE_DTAUS)
TOCTitle: (DEU) Import account statement (transactions) report (LedgerInAccountStatementDE_DTAUS)
ms:assetid: 5c877272-45e8-4f3c-a7ca-44e4d98b6f72
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh496436(v=AX.60)
ms:contentKeyID: 37072018
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.LedgerInAccountStatementDE_DTAUS
- DEU
---

# (DEU) Import account statement (transactions) report (LedgerInAccountStatementDE\_DTAUS) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Import account statement (transactions)** report is used to import bank account statements for transactions in the general journal. This report is typically used by accountants and accounting supervisors to maintain general journals and ledger transactions.

Before you print this report, you must set up a method of import that uses the **DTAUS (DE)** import format in the **Methods of importing account statements** form.


> [!NOTE]
> <P>(DEU) This report is available only to legal entities whose primary address is in Germany.</P>



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
<td><p><strong>Bridging account</strong></p></td>
<td><p>The account that was specified for the bridging posting. This is a temporary account that can be used for payment transfers.</p></td>
</tr>
<tr class="even">
<td><p><strong>File name</strong></p></td>
<td><p>Enter the name and path of the accounting statement file that is to be imported.</p></td>
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
<td><p>LedgerInAccountStatementDE_DTAUS</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\LedgerInAccountStatementDE_DTAUS</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>LedgerInAccountStatementDE_DTAUS</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Journals</strong> &gt; <strong>General journal</strong>. Select a journal, and then click <strong>Lines</strong>. In the <strong>Journal voucher</strong> form, select a transaction, and then click <strong>Functions</strong> &gt; <strong>Import account statement (transactions)</strong>. In the <strong>Method of import</strong> field, select the method of import that uses the <strong>DTAUS (DE)</strong> import format, and then click <strong>OK</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - LedgerInAccountStatementTmpDE\_DTAUS table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the LedgerInAccountStatementDPDE_DTAUS.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

