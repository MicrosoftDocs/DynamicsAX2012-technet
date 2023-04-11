---
title: (AUT) EDIFACT-DIRDEB (AT) report (CustOutPaymAdviceAT_EDIFACT)
TOCTitle: (AUT) EDIFACT-DIRDEB (AT) report (CustOutPaymAdviceAT_EDIFACT)
ms:assetid: 374ea3be-bf60-434a-bacd-72f5d0559c67
ms:mtpsurl: https://technet.microsoft.com/library/Hh496416(v=AX.60)
ms:contentKeyID: 37071993
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.CustOutPaymAdviceAT_EDIFACT
---

# (AUT) EDIFACT-DIRDEB (AT) report (CustOutPaymAdviceAT\_EDIFACT) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **EDIFACT-DIRDEB (AT)** report prints the payment advice for electronic customer payments. The payment advice includes the actual payment and the invoice amount that has been paid. This report is printed when you generate an electronic payment file that uses the **EDIFACT-DIRDEB (AT)** payment format and is typically used by accounts receivable payments clerks to maintain customer payments.

Before you print this report, you must set up a method of payment with **EDIFACT-DIRDEB (AT)** as the export format in the **Methods of payment - customers** form.


> [!NOTE]
> <P>(AUT) This report is available only to legal entities whose primary address is in Austria.</P>



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
<td><p>The bank account number that is selected in the <strong>Generate payments</strong> form.</p></td>
</tr>
<tr class="even">
<td><p><strong>Main account/customer number</strong></p></td>
<td><p>Enter the main account number or the customer number of the legal entity as specified by the bank.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Processing date</strong></p></td>
<td><p>Select the date of the customer payment.</p></td>
</tr>
<tr class="even">
<td><p><strong>Bank ID</strong></p></td>
<td><p>Enter the identification code of the vendor’s bank.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Interchange reference number</strong></p></td>
<td><p>Enter the reference number of the interchange.</p></td>
</tr>
<tr class="even">
<td><p><strong>Priority payments</strong></p></td>
<td><p>Select this check box to include priority payments in the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Own segments for name and address</strong></p></td>
<td><p>Select this check box to separate the segments for name and address details.</p></td>
</tr>
<tr class="even">
<td><p><strong>Contact</strong></p></td>
<td><p>Enter the name of the contact person from your company.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Department</strong></p></td>
<td><p>Enter the name of the department where the contact person works.</p></td>
</tr>
<tr class="even">
<td><p><strong>Telephone</strong></p></td>
<td><p>Enter the telephone number of the contact person.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Payment advice from quantity of invoices</strong></p></td>
<td><p>Enter the minimum number of invoices that must be included before the payment advice is generated and printed.</p></td>
</tr>
<tr class="even">
<td><p><strong>File name</strong></p></td>
<td><p>Select the file name and path where the payment advice report is stored.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Control report</strong></p></td>
<td><p>Select this check box to print the control report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Attending note</strong></p></td>
<td><p>Select this check box to print the attending note details.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Data medium number</strong></p></td>
<td><p>Enter the data medium number for the data that accompanies the note. This is a batch number that can be used to identify the generated file.</p></td>
</tr>
<tr class="even">
<td><p><strong>Tape number</strong></p></td>
<td><p>Enter the tape number or diskette number for the data that accompanies the note. This is a number that can be used to identify the file if it is submitted in a non-electronic, physical medium.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Bank transaction type</strong></p></td>
<td><p>Select the bank transaction type.</p></td>
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
<td><p>CustOutPaymAdviceAT_EDIFACT</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\CustOutPaymAdviceAT_EDIFACT</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>CustOutPaymAdviceReportAT_EDIFACT</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts receivable</strong> &gt; <strong>Journals</strong> &gt; <strong>Payments</strong> &gt; <strong>Payment journal</strong>. Click <strong>Lines</strong>. In the <strong>Journal voucher</strong> form, click <strong>Functions</strong> &gt; <strong>Generate payments</strong>. In the <strong>Generate payments</strong> form, in the <strong>Export format</strong> field, select <strong>EDIFACT-DIRDEB (AT)</strong>. In the <strong>Bank account</strong> field, select a bank account, and then click <strong>Dialog</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - CustVendOutTmp table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the CustOutPaymAdviceDP_ATEDIFACT.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[Bank transaction type (form)](https://technet.microsoft.com/library/aa619635\(v=ax.60\))

  


