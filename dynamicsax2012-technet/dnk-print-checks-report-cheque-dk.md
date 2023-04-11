---
title: (DNK) Print checks report (Cheque_DK)
TOCTitle: (DNK) Print checks report (Cheque_DK)
ms:assetid: 6856258d-67b9-4e30-abf1-6bdd19ea422c
ms:mtpsurl: https://technet.microsoft.com/library/Hh352255(v=AX.60)
ms:contentKeyID: 36687881
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.Cheque_DK
---

# (DNK) Print checks report (Cheque\_DK) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Print checks** report is used to print checks for vendor payments. This report is typically used by credit managers and collections managers.


> [!NOTE]
> <P>(DNK) This report is available only to legal entities whose primary address is in Denmark.</P>



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
<td><p>Cheque_DK</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\Cheque_DK</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>Cheque_DK</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Journals</strong> &gt; <strong>Payments</strong> &gt; <strong>Payment journal</strong>. Select a journal, and then click <strong>Lines</strong>. In the <strong>Journal voucher</strong> form, select a transaction, and then click <strong>Functions</strong> &gt; <strong>Generate payments</strong>. In the <strong>Generate payments</strong> form, in the <strong>Export format</strong> field, select <strong>Check</strong>. Then, in the <strong>Bank account</strong> field, select a bank account that is affected by the payment transaction. Click <strong>Dialog</strong>. In the <strong>Payment by check</strong> form, click <strong>OK</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - ChequeTmp table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the ChequeDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


