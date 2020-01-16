---
title: (DEU) DTAZV (DE) report (VendOutPaymControl_DEDTAZV)
TOCTitle: (DEU) DTAZV (DE) report (VendOutPaymControl_DEDTAZV)
ms:assetid: dc8f00dc-70e9-4da5-b753-c99b8ec9b085
ms:mtpsurl: https://technet.microsoft.com/library/Hh524742(v=AX.60)
ms:contentKeyID: 37072038
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- report
- SSRS_Reports.Reports.VendOutPaymControl_DEDTAZV
- Payment control
---

# (DEU) DTAZV (DE) report (VendOutPaymControl\_DEDTAZV) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **DTAZV (DE)** report is a control report that displays the details of the vendor payments that are made by using the **DTAZV (DE)** export format. This report is used by the accounts clerks, accounting managers, and financial controllers to inquire into the status of vendor payments and to maintain vendor payments.


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
<td><p><strong>Bank account</strong></p></td>
<td><p>The bank account number selected in the <strong>Generate payments</strong> form.</p></td>
</tr>
<tr class="even">
<td><p><strong>Main account/customer number</strong></p></td>
<td><p>Enter the main account number or the customer number of the company as specified by the bank.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Sequence number</strong></p></td>
<td><p>Enter the sequence number ID that is attached to the file.</p></td>
</tr>
<tr class="even">
<td><p><strong>Processing date</strong></p></td>
<td><p>Select the date of the vendor payments.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Covering letter from quantity of invoices</strong></p></td>
<td><p>Enter the minimum quantity of invoices required to print a cover letter.</p></td>
</tr>
<tr class="even">
<td><p><strong>File name</strong></p></td>
<td><p>Enter the file name and path of the file where the payment details are exported.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Control report</strong></p></td>
<td><p>Select this check box to print the control report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Attending note</strong></p></td>
<td><p>Select this check box to print the attending note.</p></td>
</tr>
<tr class="odd">
<td><p><strong>EU standard transfer</strong></p></td>
<td><p>Select this check box to print cross-border bank transfer transactions that are made in euros.</p></td>
</tr>
<tr class="even">
<td><p><strong>Express transfer in Euro</strong></p></td>
<td><p>Select this check box to print express transfer transactions in euros that are processed on the day that the transfer is requested.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Euro counter-value payment</strong></p></td>
<td><p>Select this check box to print bank transfer transactions in euros that must be converted to the currency of the recipient of the remittance.</p></td>
</tr>
<tr class="even">
<td><p><strong>Foreign payment</strong></p></td>
<td><p>Select this check box to print foreign bank transfer transactions.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Central bank message</strong></p></td>
<td><p>Select this check box to transfer message data to the central bank.</p></td>
</tr>
<tr class="even">
<td><p><strong>Notification for EU standard transfer</strong></p></td>
<td><p>Select this check box to send cross-border bank transfer notifications to the central bank.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Federal state number</strong></p></td>
<td><p>Enter the federal state number for the central bank message.</p></td>
</tr>
<tr class="even">
<td><p><strong>Company number</strong></p></td>
<td><p>Enter the company number for the central bank message.</p></td>
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
<td><p>VendOutPaymControl_DEDTAZV</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\VendOutPaymControl_DEDTAZV</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>VendOutPaymControl_DEDTAZV</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Journals</strong> &gt; <strong>Payments</strong> &gt; <strong>Payment journal</strong>. Select a journal name, and then click <strong>Lines</strong>. In the <strong>Journal voucher</strong> form, select a transaction, and then click <strong>Functions</strong> &gt; <strong>Generate payments</strong>. In the <strong>Export format</strong> field, select <strong>DTAZV (DE)</strong>. In the <strong>Bank account</strong> field, select a bank account, and then click <strong>Dialog</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - CustVendOutTmp table

  - TmpAccountSum table
    

    > [!NOTE]
    > <P>To find out where the data in the temp tables come from, view the cross-references for the VendOutPaymControlDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


