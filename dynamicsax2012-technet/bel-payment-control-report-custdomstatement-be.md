---
title: (BEL) Payment control report (CustDomStatement_BE)
TOCTitle: (BEL) Payment control report (CustDomStatement_BE)
ms:assetid: 8e13b20f-e9e7-48a8-80ba-eaa48211f383
ms:mtpsurl: https://technet.microsoft.com/library/Hh692468(v=AX.60)
ms:contentKeyID: 41702365
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.CustDomStatement_BE
---

# (BEL) Payment control report (CustDomStatement\_BE) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Payment control** report is used to print payment advice for direct debits. This payment advice is submitted along with the Dom80 electronic payment file to the bank. This report is typically used by accountants and accounts receivable payments clerks.


> [!NOTE]
> <P>(BEL) This report is available only to legal entities whose primary address is in Belgium.</P>



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
<td><p>CustDomStatement_BE</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\CustDomStatement_BE</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>CustOutPaymControl_BE_DOM</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts receivable</strong> &gt; <strong>Journals</strong> &gt; <strong>Payments</strong> &gt; <strong>Payment journal</strong>. Select a journal name, and then click <strong>Lines</strong>. In the <strong>Journal voucher</strong> form, select a transaction, and then click <strong>Functions</strong> &gt; <strong>Generate payments</strong>. In the <strong>Method of payment</strong> field, select the method of payment that uses the <strong>dom 80 (be)</strong> export format. In the <strong>Bank account</strong> field, select a bank account, and then click <strong>OK</strong>. In the <strong>File name</strong> field, specify the name and path of the file where the payment details are exported, and then click <strong>OK</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - CustDomStatementTmp\_BE table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the CustDomStatementDP_BE.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


