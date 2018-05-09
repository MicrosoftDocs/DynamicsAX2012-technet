---
title: (DNK) Betalingsservice Basis-returformat (DK) report (CustPaymReconciliationPrint_DK_BS)
TOCTitle: (DNK) Betalingsservice Basis-returformat (DK) report (CustPaymReconciliationPrint_DK_BS)
ms:assetid: 625e4351-ae86-4301-b732-9e71dcecdc0b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh433497(v=AX.60)
ms:contentKeyID: 36941264
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.CustPaymReconciliationPrint_DK_BS
---

# (DNK) Betalingsservice Basis-returformat (DK) report (CustPaymReconciliationPrint\_DK\_BS) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Betalingsservice Basis-returformat (DK)** report prints the payments that are received by using the Payment Business Services (PBS) mode of payment. This report is typically used by chief executive officers, chief financial officers, compliance managers, accounting managers, and accountants to review the status of invoice processes and cash processes.

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
<td><p>Enter the name and path of the file where the customer payment return details are imported.</p></td>
</tr>
<tr class="even">
<td><p><strong>Print</strong></p></td>
<td><p>Select this check box to print the report.</p></td>
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
<td><p>CustPaymReconciliationPrint_DK_BS</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\CustPaymReconciliationPrint_DK_BS</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>CustPaymReconciliationPrint_DK_BS</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts receivable</strong> &gt; <strong>Journals</strong> &gt; <strong>Payments</strong> &gt; <strong>Payment transfers</strong>. Select a payment transfer transaction, and then click <strong>Return file - customer</strong>. In the <strong>Load diskette with payments</strong> form, in the <strong>Method of payment</strong> field, select a method of payment that uses the <strong>Betalingsservice Basis-returformat (DK)</strong> payment return format, and then click <strong>OK</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - CustPaymReconciliationPrint\_DK\_BSTmp table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the CustPaymReconciliationPrintDP_DK_BS.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

