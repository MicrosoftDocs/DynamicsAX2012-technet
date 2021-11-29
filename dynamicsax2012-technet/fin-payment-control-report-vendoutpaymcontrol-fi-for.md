---
title: (FIN) Payment control report (VendOutPaymControl_FI_FOR)
TOCTitle: (FIN) Payment control report (VendOutPaymControl_FI_FOR)
ms:assetid: 63a9e586-13df-409f-b5d5-18aa7c7282ee
ms:mtpsurl: https://technet.microsoft.com/library/Hh433498(v=AX.60)
ms:contentKeyID: 36941265
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Options
- report
- SSRS_Reports.Reports.VendOutPaymControl_FI_FOR
- (FIN)
---

# (FIN) Payment control report (VendOutPaymControl\_FI\_FOR) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Payment control** report displays the details of vendor payments that are made by using the **LUM2 (FI)** export format. This report is used to inquire into the status of vendor payments and to maintain vendor payments. This report is typically used by the accounts payable payments clerks, chief financial officers, accountants, accounting managers, accounting supervisors, and financial controllers.


> [!NOTE]
> <P>(FIN) This report is available only to legal entities whose primary address is in Finland.</P>



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
<td><p>VendOutPaymControl_FI_FOR</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\VendOutPaymControl_FI_FOR</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>VendOutPaymControl_FI_FOR</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Journals</strong> &gt; <strong>Payments</strong> &gt; <strong>Payment journal</strong>. Select a journal name, and then click <strong>Lines</strong>. In the <strong>Journal voucher</strong> form, select a transaction, and then click <strong>Functions</strong> &gt; <strong>Generate payments</strong>. In the <strong>Export format</strong> field, select <strong>LUM2 (FI)</strong>. In the <strong>Bank account</strong> field, select a bank account, and then click <strong>Dialog</strong>. In the <strong>Parameters for foreign payments</strong> form, click <strong>OK</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - CustVendOutTmp table

  - TmpAccountSum table
    

    > [!NOTE]
    > <P>To find out where the data in these temp tables comes from, view the cross-references for the VendOutPaymControlDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


