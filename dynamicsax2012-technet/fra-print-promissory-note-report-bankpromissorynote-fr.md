---
title: (FRA) Print promissory note report (BankPromissoryNote_FR)
TOCTitle: (FRA) Print promissory note report (BankPromissoryNote_FR)
ms:assetid: 5a94ae5b-9a0d-4c1c-b886-bd0bcb2161d5
ms:mtpsurl: https://technet.microsoft.com/library/Hh335151(v=AX.60)
ms:contentKeyID: 36687362
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.BankPromissoryNote_FR
- (FRA)
- Print promissory note
- Print promissory note report
---

# (FRA) Print promissory note report (BankPromissoryNote\_FR) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Print promissory note** report prints a list of promissory notes and details about the promissory notes that are generated for legal entities operating in France. This report is typically used by bookkeepers and accounting clerks.


> [!NOTE]
> <P>(FRA) This report is available only to legal entities whose primary address is in France.</P>



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
<td><p>BankPromissoryNote_FR</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\BankPromissoryNote_FR</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>BankPromissoryNote_FR</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Journals</strong> &gt; <strong>Promissory notes</strong> &gt; <strong>Draw promissory note journal</strong>. Click <strong>Lines</strong>. In the <strong>Journal voucher</strong> form, click <strong>Functions</strong> &gt; <strong>Generate payments</strong>. In the <strong>Generate payments</strong> form, in the <strong>Export format</strong> field, select <strong>Promissory note document</strong>, and then click <strong>OK</strong>. In the <strong>Promissory note document</strong> form, in the <strong>City</strong> field, enter the city in which the legal entity operates, and then click <strong>OK</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - BankPromissoryNoteTmp\_FR table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the BankPromissoryNoteDP_FR.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


