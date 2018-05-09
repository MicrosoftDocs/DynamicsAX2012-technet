---
title: (AUT) EDIFACT-DIRDEB (AT) report (CustOutAttendingNoteAT_EDIFACT)
TOCTitle: (AUT) EDIFACT-DIRDEB (AT) report (CustOutAttendingNoteAT_EDIFACT)
ms:assetid: 77d5ca92-f986-48ab-acc6-94af2d3cc6b8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh335156(v=AX.60)
ms:contentKeyID: 36687368
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.CustOutAttendingNoteAT_EDIFACT
---

# (AUT) EDIFACT-DIRDEB (AT) report (CustOutAttendingNoteAT\_EDIFACT) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **EDIFACT-DIRDEB (AT)** report is used to print an attending note for electronic payments when a payment file is exported. This report is generated while posting the export information from a customer payment journal into an electronic payment file. A specific file format, **EDIFACT-DIRDEB (AT)**, is used for the file export. This report is typically used by credit managers and collections managers.

Before you print this report, you must set up a payment method with **EDIFACT-DIRDEB (AT)** as the export format in the **Methods of payment - customers** form.


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
<td><p>The bank account that is used to generate the payment transaction details.</p></td>
</tr>
<tr class="even">
<td><p><strong>Main account/customer number</strong></p></td>
<td><p>Enter the main account or the customer number of the company for which the report is generated.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Processing date</strong></p></td>
<td><p>Enter the processing date.</p></td>
</tr>
<tr class="even">
<td><p><strong>Bank ID</strong></p></td>
<td><p>Enter the identification number of the bank that is the recipient of the interchange.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Interchange reference number</strong></p></td>
<td><p>Enter the interchange reference number.</p></td>
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
<td><p>Enter the name of the contact.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Department</strong></p></td>
<td><p>Enter the department details.</p></td>
</tr>
<tr class="even">
<td><p><strong>Telephone</strong></p></td>
<td><p>Enter the telephone number.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Payment advice from quantity of invoices</strong></p></td>
<td><p>Enter the number of invoices for which the payment advice must be printed.</p></td>
</tr>
<tr class="even">
<td><p><strong>File name</strong></p></td>
<td><p>Enter the file name and path of the file where the information is exported.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Control report</strong></p></td>
<td><p>Select this check box to print the control report details.</p></td>
</tr>
<tr class="even">
<td><p><strong>Attending note</strong></p></td>
<td><p>Select this check box to print the attending note details.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Data medium number</strong></p></td>
<td><p>Enter the data medium number for the data that accompanies the note.</p></td>
</tr>
<tr class="even">
<td><p><strong>Tape number</strong></p></td>
<td><p>Enter the tape or diskette number for the data that accompanies the note.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Bank transaction type</strong></p></td>
<td><p>Select the bank transaction type for the data that accompanies the note.</p></td>
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
<td><p>CustOutAttendingNoteAT_EDIFACT</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\CustOutAttendingNoteAT_EDIFACT</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>CustOutAttendingNoteReportAT_EDIFACT</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts receivable</strong> &gt; <strong>Journals</strong> &gt; <strong>Payments</strong> &gt; <strong>Payment journal</strong>. Click <strong>Lines</strong>. In the <strong>Journal voucher</strong> form, click <strong>Functions</strong> &gt; <strong>Generate payments</strong>. In the <strong>Generate payments</strong> form, in the <strong>Export format</strong> field, select the method of payment that uses the <strong>EDIFACT-DIRDEB (AT)</strong> export format, and then click <strong>OK</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - CustOutAttendingNoteATTmp\_EDIFACT table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for CustOutAttendingNoteATDP_EDIFACT.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

