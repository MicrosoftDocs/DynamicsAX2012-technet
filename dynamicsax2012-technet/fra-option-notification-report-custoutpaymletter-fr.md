---
title: (FRA) Option/Notification report (CustOutPaymLetter_FR)
TOCTitle: (FRA) Option/Notification report (CustOutPaymLetter_FR)
ms:assetid: 07180101-538e-4daf-a4b3-0ddc8c9fec8e
ms:mtpsurl: https://technet.microsoft.com/library/Hh456292(v=AX.60)
ms:contentKeyID: 36997718
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.CustOutPaymLetter_FR
---

# (FRA) Option/Notification report (CustOutPaymLetter\_FR) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Option/Notification** report displays and prints a list of direct debit payments that are made from a specific customer account. This report is printed based on the customer’s request. This report is used to review payments that are made by using the **cfonb - prélèvements (fr)** export format. This report is typically used by accounts clerks to maintain customer payments.

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
<td><p>Select the file name of the report file and path where the report is saved.</p></td>
</tr>
<tr class="even">
<td><p><strong>Payment date</strong></p></td>
<td><p>Enter the date of the payments for which the customer requested the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Control report</strong></p></td>
<td><p>Select this check box to print a control report for the report file.</p></td>
</tr>
<tr class="even">
<td><p><strong>Payment advice</strong></p></td>
<td><p>Select this check box to print payment advice for the payments.</p></td>
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
<td><p>CustOutPaymLetter_FR</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\CustOutPaymLetter_FR</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>CustOutPaymLetterFR</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts receivable</strong> &gt; <strong>Journals</strong> &gt; <strong>Payments</strong> &gt; <strong>Payment journal</strong>. Click <strong>Lines</strong> to open the <strong>Journal voucher</strong> form. Click <strong>Functions</strong> &gt; <strong>Generate payments</strong>. In the <strong>Export format</strong> field, select <strong>cfonb - prélèvements (fr)</strong>, and then click <strong>OK</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - CustVendOutTmp table

  - TmpAccountSum table

  - 
    

    > [!NOTE]
    > <P>To find out where the data in the temp tables comes from, view the cross-references for the CustOutPaymControlDP.processReport class</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


