---
title: (ITA) Pagamento Fornitori (IT) report (VendOutPaymControl_IT)
TOCTitle: (ITA) Pagamento Fornitori (IT) report (VendOutPaymControl_IT)
ms:assetid: ab06e8c7-9ed9-4e71-85ab-044ff9261817
ms:mtpsurl: https://technet.microsoft.com/library/Hh456298(v=AX.60)
ms:contentKeyID: 36997724
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.VendOutPaymControl_IT
- (ITA)
- Menu_Items.Output.VendOutPaymControl_IT
- Print report
---

# (ITA) Pagamento Fornitori (IT) report (VendOutPaymControl\_IT) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Pagamento Fornitori (IT)** report is used to print bank remittance files for vendor payments. This report is typically used by chief financial officers, accounting managers, accountants, financial controllers, accounting clerks, and accounting supervisors to maintain vendor payments.

Before you print this report, you must set up a method of payment that uses the **Pagamento Fornitori (IT)** export format in the **Methods of payment - vendors** form.


> [!NOTE]
> <P>(ITA) This report is available only to legal entities whose primary address is in Italy.</P>



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
<td><p>Enter the name and path of the file where the vendor payments details are exported.</p></td>
</tr>
<tr class="even">
<td><p><strong>Creation date</strong></p></td>
<td><p>Select or enter the date when the payment file is created.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Default date</strong></p></td>
<td><p>Select or enter the default value date of the payment file. The value date is the date by which the payment file must be remitted to be eligible for a discount. If the default value date is blank, the document date of the transaction is displayed in the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Control report</strong></p></td>
<td><p>Select this check box to print the bank remittance control report.</p></td>
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
<td><p>VendOutPaymControl_IT</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\VendOutPaymControl_IT</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>VendOutPaymControl_IT</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Journals</strong> &gt; <strong>Payments</strong> &gt; <strong>Payment journal</strong>. Select a journal name, and then click <strong>Lines</strong>. Click <strong>Functions</strong> &gt; <strong>Generate payments</strong>. In the <strong>Method of payment</strong> field, select the method of payment that uses the <strong>Pagamento Fornitori (IT)</strong> export format. In the <strong>Bank account</strong> field, select a bank account, and then click <strong>Dialog</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - TmpAccountSum table

  - CustVendOutTmp table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the VendOutPaymControlDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


