---
title: (NLD) Instruction letter report (CustVendOutPaymNL)
TOCTitle: (NLD) Instruction letter report (CustVendOutPaymNL)
ms:assetid: 39a9177b-3c62-47d1-9bfd-63af73d0cb45
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh692462(v=AX.60)
ms:contentKeyID: 41702358
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Instruction
- SSRS_Reports.Reports.CustVendOutPaymNL
- Letter
- NLD
---

# (NLD) Instruction letter report (CustVendOutPaymNL) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Instruction letter** report is used to print payment advice for direct debits that use the **NL - ClieOp03 Incasso** export format. This payment advice is submitted to the bank along with the ClieOp3 Incasso payment file. This report is typically used by accountants and accounts receivable payments clerks.


> [!NOTE]
> <P>You must select the <STRONG>Attending note</STRONG> check box in the <STRONG>NL - ClieOp03 Incasso</STRONG> form to generate the <STRONG>Instruction letter</STRONG> report.</P>




> [!NOTE]
> <P>(NLD) This report is available only to legal entities whose primary address is in the Netherlands.</P>



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
<td><p><strong>Fixed description</strong></p></td>
<td><p>The description of the transactions to be included in the ClieOp3 Incasso payment file.</p></td>
</tr>
<tr class="even">
<td><p><strong>Processing date</strong></p></td>
<td><p>The date on which the bank must process the direct debit transactions.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Directory</strong></p></td>
<td><p>Select or enter a location to export the payment file.</p></td>
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
<td><p>CustVendOutPaymNL</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\CustVendOutPaymNL</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>CustVendOutPaymNL_InstructionLetter</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts receivable</strong> &gt; <strong>Journals</strong> &gt; <strong>Payments</strong> &gt; <strong>Payment journal</strong>. Select a journal, and then click <strong>Lines</strong>. Create payment lines with payment specifications. Click <strong>Functions</strong> &gt; <strong>Generate payments</strong>. In the <strong>Generate payments</strong> form, in the <strong>Method of payment</strong> field, select the method of payment that uses the <strong>NL - ClieOp03 Incasso</strong> export format. In the <strong>Bank account</strong> field, select a bank account, and then click <strong>Dialog</strong>. In the <strong>NL - ClieOp03 Incasso</strong> form, enter the required details, and then click <strong>OK</strong> to return to the <strong>Generate payments</strong> form. Click <strong>OK</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - TmpCustVendOutPaymBatch table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the CustVendOutPaymNLDP_InstrLetter.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[Journal voucher - Customer payment journal (form)](https://technet.microsoft.com/en-us/library/aa556141\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

