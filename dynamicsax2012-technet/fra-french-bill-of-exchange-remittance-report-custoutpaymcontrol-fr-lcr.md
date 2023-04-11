---
title: (FRA) French bill of exchange remittance report (CustOutPaymControl_FR_LCR)
TOCTitle: (FRA) French bill of exchange remittance report (CustOutPaymControl_FR_LCR)
ms:assetid: 64c4c673-59f3-4a2b-ac11-9156b4c73c17
ms:mtpsurl: https://technet.microsoft.com/library/Hh456293(v=AX.60)
ms:contentKeyID: 36997719
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Print
- report
- SSRS_Reports.Reports.CustOutPaymControl_FR_LCR
- (FRA)
---

# (FRA) French bill of exchange remittance report (CustOutPaymControl\_FR\_LCR) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The French bill of exchange remittance report displays details about remitted bills of exchange. The report includes information about your bank account, legal entity, and remittance type. It also provides a list of customer transactions that are affected by the bill of exchange. The report is printed when you generate a bill of exchange remittance file and the **Control report** check box is selected in the **French bill of exchange remittance** dialog box. This report is used by accounts receivable clerks and accounts payable clerks to maintain customer payments.


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
<td><p><strong>Remittance date</strong></p></td>
<td><p>Enter the date when the bill of exchange is remitted.</p></td>
</tr>
<tr class="even">
<td><p><strong>Discount type</strong></p></td>
<td><p>Select <strong>Discount</strong> or <strong>Value discount</strong> as the type of discount that is remitted.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Value date</strong></p></td>
<td><p>If you select <strong>Discount</strong> in the <strong>Discount type</strong> field, then select a discount value date in the <strong>Value date</strong> field.</p></td>
</tr>
<tr class="even">
<td><p><strong>File name</strong></p></td>
<td><p>Select or enter the path and file name of the remittance file.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Control report</strong></p></td>
<td><p>Select this check box to print a control report for the remittance file that is generated.</p></td>
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
<td><p>CustOutPaymControl_FR_LCR</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\CustOutPaymControl_FR_LCR</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>CustOutPaymControl_FR_LCR</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts receivable</strong> &gt; <strong>Journals</strong> &gt; <strong>Bill of exchange</strong> &gt; <strong>Remittance journal</strong>. Select a journal name, and then click <strong>Lines</strong>. In the <strong>Journal voucher</strong> form, select a transaction, and then click <strong>Functions</strong> &gt; <strong>Generate remittance</strong>. In the <strong>Remittance format</strong> field, select <strong>French bill of exchange remittance</strong>, and then click <strong>Dialog</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - CustVendOutTmp table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the CustOutPaymControlDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


