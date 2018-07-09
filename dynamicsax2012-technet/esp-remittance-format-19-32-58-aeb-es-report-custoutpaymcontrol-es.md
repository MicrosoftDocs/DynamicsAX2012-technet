---
title: (ESP) Remittance Format 19,32 & 58 AEB (ES) report (CustOutPaymControl_ES)
TOCTitle: (ESP) Remittance Format 19,32 & 58 AEB (ES) report (CustOutPaymControl_ES)
ms:assetid: dcb1e7d3-d34d-4b12-ade4-ed93f981bd0a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh524743(v=AX.60)
ms:contentKeyID: 37072039
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Print
- report
- SSRS_Reports.Reports.CustOutPaymControl_ES
- (ESP)
---

# (ESP) Remittance Format 19,32 & 58 AEB (ES) report (CustOutPaymControl\_ES) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Remittance Format 19,32 & 58 AEB(ES)** report displays and prints the details of customer payments that are remitted to the bank. You can sort the details of the remitted customer payments based on the export format that you select in the **Remittance export formats** field:

  - If you select **Format 32**, specify whether to attach physical drafts to the remittance file in the **Are the physical drafts attached?** field, and select which type of document to attach to the remittance file in the **Document type** field.

  - If you select **Format 19 proc. 1** or **Format 19 Proc. 2**, enter the date on which payment is requested in the **Date of payment** field.

This report is generated and used by accounts receivable payments clerks and accounts payable payments clerks to maintain customer payments.


> [!NOTE]
> <P>(ESP) This report is available only to legal entities whose primary address is in Spain.</P>



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
<td><p><strong>Remittance export formats</strong></p></td>
<td><p>Select the remittance export format from the following options:</p>
<ul>
<li><p><strong>Format 19 proc. 1</strong> – Direct debits that use the <strong>Format 19 proc. 1</strong> remittance export format are included in the report.</p></li>
<li><p><strong>Format 19 Proc. 2</strong> – Direct debits that use the <strong>Format 19 Proc. 2</strong> remittance export format are included in the report.</p></li>
<li><p><strong>Format 58</strong> –Advanced payments that use the <strong>Format 58</strong> remittance export format are included in the report.</p></li>
<li><p><strong>Format 32</strong> – Remittance payments that use the <strong>Format 32</strong> remittance export format are included in the report.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Are the physical drafts attached?</strong></p></td>
<td><p>Select this check box when a paper document, such as a bill of exchange, receipt, or promissory note, is attached to the remittance file.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Document type</strong></p></td>
<td><p>Select the document type to attach to the remittance file from the following options:</p>
<ul>
<li><p><strong>Bill of exchange</strong> – The document is a bill of exchange.</p></li>
<li><p><strong>Receipt</strong> – The document is a receipt.</p></li>
<li><p><strong>Pagara</strong> – The document is a promissory note.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Date of payment</strong></p></td>
<td><p>Select the date on which the payment is requested.</p></td>
</tr>
<tr class="odd">
<td><p><strong>File name</strong></p></td>
<td><p>Select the file name and file path of the payment file.</p></td>
</tr>
<tr class="even">
<td><p><strong>Control report</strong></p></td>
<td><p>Select this check box to print the control report.</p></td>
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
<td><p>CustOutPaymControl_ES</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\CustOutPaymControl_ES</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>CustOutPaymControl_ES</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts receivable</strong> &gt; <strong>Journals</strong> &gt; <strong>Bill of exchange</strong> &gt; <strong>Remittance journal</strong>. Select a journal name, and then click <strong>Lines</strong>. In the <strong>Journal voucher</strong> form, select a transaction, and then click <strong>Functions</strong> &gt; <strong>Generate remittance</strong>. In the <strong>Remittance format</strong> field, select <strong>Remittance Format 19,32 &amp; 58 AEB(ES)</strong>, and then click <strong>Dialog</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - CustVendOutTmp table

  - TmpAccountSum table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the CustOutPaymControlDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

