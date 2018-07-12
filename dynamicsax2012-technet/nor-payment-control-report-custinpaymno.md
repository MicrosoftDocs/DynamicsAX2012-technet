---
title: (NOR) Payment control report (CustInPaymNO)
TOCTitle: (NOR) Payment control report (CustInPaymNO)
ms:assetid: 7dbf6978-4442-46d5-96e4-54f1cbf1b273
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh335157(v=AX.60)
ms:contentKeyID: 36687369
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.CustInPaymNO
---

# (NOR) Payment control report (CustInPaymNO) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Payment control** report is used to print the details of import payments. The details that are included in the report depend on the import format that is specified as the method of payment in the **Methods of payment - customers** form:

  - **OCR+AG innlesning (NO)** – Print the report in the payment ID import format.

  - **eGiro Innbetaling Pluss (NO)** – Print the report in the eGiro (CREMUL) import format.

  - **BBS eFaktura, AG, OCR, DirRem (NO)** – Print the report in the eInvoice report format.

This report is typically used by accounts receivable clerks to maintain customer payment details.


> [!NOTE]
> <P>(NOR) This report is available only to legal entities whose primary address is in Norway.</P>



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
<td><p><strong>File name</strong></p></td>
<td><p>Enter the file path and file name that are used to import the payment.</p></td>
</tr>
<tr class="even">
<td><p><strong>Summing of bank transactions</strong></p></td>
<td><p>Select this check box to add up bank transactions.</p>
<div class="alert">

> [!NOTE]
> <P>This control is available only when the <STRONG>OCR+AG innlesning (NO)</STRONG> import format is selected as the method of payment.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>Error account customer</strong></p></td>
<td><p>Select the details of the invalid customer account that are relevant to the import.</p>
<div class="alert">

> [!NOTE]
> <P>This control is available only when the <STRONG>BBS eFaktura, AG, OCR, DirRem (NO)</STRONG> or <STRONG>OCR+AG innlesning (NO)</STRONG> import format is selected as the method of payment.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Amount control</strong></p></td>
<td><p>Select this check box to control the customer payment amount that can be imported.</p>
<div class="alert">

> [!NOTE]
> <P>This control is available only when the <STRONG>BBS eFaktura, AG, OCR, DirRem (NO)</STRONG> or <STRONG>OCR+AG innlesning (NO)</STRONG> import format is selected as the method of payment.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>Approve underpayments</strong></p></td>
<td><p>Select this check box to approve the underpayment transactions.</p>
<div class="alert">

> [!NOTE]
> <P>This control is available only when the <STRONG>OCR+AG innlesning (NO)</STRONG> import format is selected as the method of payment.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Method of payment</strong></p></td>
<td><p>Select the method of payment that corresponds to the new or modified AvtaleGiro agreements.</p>
<div class="alert">

> [!NOTE]
> <P>This control is available only when the <STRONG>OCR+AG innlesning (NO)</STRONG> import format is selected as the method of payment.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>Payment specification with warning</strong></p></td>
<td><p>Enter the message to be displayed with a warning when an error occurs in the payment specification.</p>
<div class="alert">

> [!NOTE]
> <P>This control is available only when the <STRONG>OCR+AG innlesning (NO)</STRONG> import format is selected as the method of payment.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Payment specification without warning</strong></p></td>
<td><p>Enter the message to be displayed without a warning when an error occurs in the payment specification.</p>
<div class="alert">

> [!NOTE]
> <P>This control is available only when the <STRONG>OCR+AG innlesning (NO)</STRONG> import format is selected as the method of payment.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>Method of payment</strong></p></td>
<td><p>Select the method of payment that corresponds to the deleted AvtaleGiro agreements.</p>
<div class="alert">

> [!NOTE]
> <P>This control is available only when the <STRONG>OCR+AG innlesning (NO)</STRONG> import format is selected as the method of payment.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Payment specification</strong></p></td>
<td><p>Enter the payment specification for deleted AvtaleGiro agreements.</p>
<div class="alert">

> [!NOTE]
> <P>This control is available only when the <STRONG>OCR+AG innlesning (NO)</STRONG> import format is selected as the method of payment.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>Sender ID</strong></p></td>
<td><p>Enter the identification number of the sender.</p>
<div class="alert">

> [!NOTE]
> <P>This control is available only when the <STRONG>BBS eFaktura, AG, OCR, DirRem (NO)</STRONG> import format is selected as the method of payment.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Delete empty journal</strong></p></td>
<td><p>Select this check box to delete the empty journal so that validated payments can be renumbered.</p>
<div class="alert">

> [!NOTE]
> <P>This control is available only when the <STRONG>BBS eFaktura, AG, OCR, DirRem (NO)</STRONG> import format is selected as the method of payment.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>Direct debit</strong></p></td>
<td><p>Select the direct debit that is related to the integration type.</p>
<div class="alert">

> [!NOTE]
> <P>This control is available only when the <STRONG>BBS eFaktura, AG, OCR, DirRem (NO)</STRONG> import format is selected as the method of payment.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>e-invoice</strong></p></td>
<td><p>Select the e-invoice that is related to the integration type.</p>
<div class="alert">

> [!NOTE]
> <P>This control is available only when the <STRONG>BBS eFaktura, AG, OCR, DirRem (NO)</STRONG> import format is selected as the method of payment.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>Print import file</strong></p></td>
<td><p>Select this check box to print the import file.</p></td>
</tr>
<tr class="even">
<td><p><strong>Print payment lines</strong></p></td>
<td><p>Select this check box to print payment lines.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Archive the file</strong></p></td>
<td><p>Select this check box to archive the file that contains the details of the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Analyze the file</strong></p></td>
<td><p>Select this check box to analyze the file that contains the details of the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Customer bank account test.</strong></p></td>
<td><p>Select this check box to test customer bank accounts.</p></td>
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
<td><p>CustInPaymNO</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\CustInPaymNO</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>CustInPaymNO</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts receivable</strong> &gt; <strong>Journals</strong> &gt; <strong>Payments</strong> &gt; <strong>Payment journal</strong>. Click <strong>Lines</strong>. In the <strong>Journal voucher</strong> form, click <strong>Functions</strong> &gt; <strong>Import payments</strong>. In the <strong>Load diskette with payments</strong> form, in the <strong>Method of payment</strong> field, select the method of payment with the attached import format in which to print the report, and then click <strong>OK</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - CustInPaymTmpNO table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for CustInPaymDPNO.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


