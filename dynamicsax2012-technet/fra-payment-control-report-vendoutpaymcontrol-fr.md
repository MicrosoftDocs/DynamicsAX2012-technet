---
title: (FRA) Payment control report (VendOutPaymControl_FR)
TOCTitle: (FRA) Payment control report (VendOutPaymControl_FR)
ms:assetid: 45ad9257-1a4c-477e-9c1e-a354870f033d
ms:mtpsurl: https://technet.microsoft.com/library/Hh433491(v=AX.60)
ms:contentKeyID: 36941252
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- report
- SSRS_Reports.Reports.VendOutPaymControl_FR
- (FRA)
- Payment control
---

# (FRA) Payment control report (VendOutPaymControl\_FR) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Payment control** report prints payment advice for vendor payments when you post a payment journal. This report is used to check vendor payment statuses and maintain vendor payments. This report is typically used by accountants, accounting managers, accounting supervisors, accounts payable centralized payments clerks, accounts payable clerks, accounts payable managers, accounts payable payments clerks, chief financial officers, and financial controllers.


> [!NOTE]
> <P>(FRA) This report is available only to legal entities whose primary address is in France.</P>



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
<td><p>Enter the file name and path where the <strong>Payment control</strong> report is stored.</p></td>
</tr>
<tr class="even">
<td><p><strong>Payment date</strong></p></td>
<td><p>Select the date when the vendor payment was made.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Control report</strong></p></td>
<td><p>Select this check box to print a control report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Payment advice</strong></p></td>
<td><p>Select this check box to print payment advice.</p></td>
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
<td><p>VendOutPaymControl_FR</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\VendOutPaymControl_FR</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>VendOutPaymControl_FR</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Journals</strong> &gt; <strong>Payments</strong> &gt; <strong>Payment journal</strong>. Click <strong>Lines</strong>. In the <strong>Journal voucher</strong> form, click <strong>Functions</strong> &gt; <strong>Generate payments</strong>. In the <strong>Generate payments</strong> form, in the <strong>Export format</strong> field, select <strong>cfonb - virements (fr)</strong>. In the <strong>Bank account</strong> field, select a bank account, and then click <strong>Dialog</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - CustVendOutTmp table

  - TmpAccountSum table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the VendOutPaymControlDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


