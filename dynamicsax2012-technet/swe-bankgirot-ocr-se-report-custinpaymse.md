---
title: (SWE) Bankgirot OCR (SE) report (CustInPaymSE)
TOCTitle: (SWE) Bankgirot OCR (SE) report (CustInPaymSE)
ms:assetid: 8b17bf4d-a43b-4ad4-b289-65a5cb016bd0
ms:mtpsurl: https://technet.microsoft.com/library/Hh352281(v=AX.60)
ms:contentKeyID: 36687907
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.CustInPaymSE
---

# (SWE) Bankgirot OCR (SE) report (CustInPaymSE) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Bankgirot OCR (SE)** report is used to print the details of import payments. The details that are included in the report depend on the import format that is specified as the method of payment. This report is typically used by accountants and accounting managers to maintain customer payment details.


> [!NOTE]
> <P>(SWE) This report is available only to legal entities whose primary address is in Sweden.</P>



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
<td><p><strong>Bank account</strong></p></td>
<td><p>The bank account that is used to import the payments.</p></td>
</tr>
<tr class="even">
<td><p><strong>File name</strong></p></td>
<td><p>Enter the file path and file name of the file that is used to import the payments.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Import incorrect records</strong></p></td>
<td><p>Select this check box to include records that are incorrect when payments are imported.</p></td>
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
<td><p>CustInPaymSE</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\CustInPaymSE</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>CustInPaymSE</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts receivable</strong> &gt; <strong>Journals</strong> &gt; <strong>Payments</strong> &gt; <strong>Payment journal</strong>. Click <strong>Lines</strong>. In the <strong>Journal voucher</strong> form, click <strong>Functions</strong> &gt; <strong>Import payments</strong>. In the <strong>Load diskette with payments</strong> form, in the <strong>Method of payment</strong> field, select the method of payment with the <strong>Bankgirot OCR (SE)</strong> import format, and then click <strong>OK</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - CustInPaymTmpSE table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for CustInPaymDPSE.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


