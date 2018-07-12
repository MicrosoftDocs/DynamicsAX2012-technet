---
title: (RUS) Print journal report (LedgerTransPreview_RU)
TOCTitle: (RUS) Print journal report (LedgerTransPreview_RU)
ms:assetid: 694430fc-367f-4313-baaa-d33594eebb60
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn126095(v=AX.60)
ms:contentKeyID: 52075230
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.LedgerTransPreview_RU
---

# (RUS) Print journal report (LedgerTransPreview\_RU) 


_**Applies To:** Microsoft Dynamics AX 2012 R2_

The Print journal report displays the ledger transactions that are generated after a journal is posted. Before a journal is posted, accountants generate this report to preview the ledger transactions.

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
<td><p><strong>Main accounts only</strong></p></td>
<td><p>Select this check box to display only the main accounts on the report. Clear this check box to display the main accounts and financial dimensions on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Journal lines</strong></p></td>
<td><p>Select this check box to display the batch journal lines for the journal lines that are included on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Ledger transactions</strong></p></td>
<td><p>Select this check box to display the ledger journal transactions on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Crediting</strong></p></td>
<td><p>The type of transactions that are included on the report. <strong>Yes</strong> is displayed for credit transactions. <strong>No</strong> is displayed for debit transactions.</p>
<div>

> [!NOTE]
> <P>If the <STRONG>Use corresponding mechanism</STRONG> check box is selected in the <STRONG>General ledger parameters</STRONG> form, <STRONG>No</STRONG> is displayed in this field by default.</P>


</div></td>
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
<td><p>LedgerTransPreview_RU</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\LedgerTransPreview_RU</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>LedgerTransPreview_RU</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Use the Print journal report to preview and print the ledger transactions before you post the journals. You can open the <strong>Preview journal transactions</strong> form from the <strong>Post</strong> button that is available in several journals. For example, you can access the <strong>Preview journal transactions</strong> form and generate the Print journal report by using the following path:</p>
<p>Click <strong>Accounts payable</strong> &gt; <strong>Journals</strong> &gt; <strong>Payments</strong> &gt; <strong>Payment journal</strong>. Select a journal that is not posted, and then click <strong>Post</strong> &gt; <strong>Preview journal transactions</strong>. In the <strong>Preview journal transactions</strong> form, click <strong>Print</strong> &gt; <strong>Print journal</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data on this report comes from

The data on this report comes from the following sources:

  - LedgerTransPreviewTmp\_RU table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the LedgerTransStatementDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[(RUS) Preview journal transactions (form)](https://technet.microsoft.com/en-us/library/jj853173\(v=ax.60\))

[(RUS) Journal header (modified form)](https://technet.microsoft.com/en-us/library/jj911370\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

