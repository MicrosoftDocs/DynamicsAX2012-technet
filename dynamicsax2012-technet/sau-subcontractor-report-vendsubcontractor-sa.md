---
title: (SAU) Subcontractor report (VendSubContractor_SA)
TOCTitle: (SAU) Subcontractor report (VendSubContractor_SA)
ms:assetid: f2a0f051-1c60-4fa9-a491-d6b0499a43e4
ms:mtpsurl: https://technet.microsoft.com/library/Hh352297(v=AX.60)
ms:contentKeyID: 36687925
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.VendSubContractor_SA
- (SAU)
- Subcontractor
- Subcontractor report
---

# (SAU) Subcontractor report (VendSubContractor\_SA) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Subcontractor** report displays a summary of all subcontractor transaction details and includes the subcontractor name and address, contract value, Zakat file number, organization number, and total amounts of transactions. This report is typically used by accountants, collections managers, clerks, and sales managers.

This report must be submitted to the Department of Zakat and Income Tax (DZIT) by legal entities operating in Saudi Arabia. Legal entities must generate and submit this report along with 13 other Zakat reports, their balance sheet, and their profit-and-loss statement to DZIT within a month of the end of the fiscal year. For more information about the other Zakat reports, see [(SAU) About Zakat reporting](sau-about-zakat-reporting.md).


> [!NOTE]
> <P>(SAU) This report is available only to legal entities whose primary address is in Saudi Arabia.</P>



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
<td><p><strong>Fiscal year</strong></p></td>
<td><p>Enter the fiscal year that you want to generate the <strong>Subcontractor</strong> report for.</p></td>
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
<td><p>VendSubContractor_SA</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\VendSubcontractor_SA</p></td>
</tr>
<tr class="odd">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Periodic</strong> &gt; <strong>Zakat</strong> &gt; <strong>Zakat reports</strong>. In the <strong>Select</strong> field, select the line with the <strong>Zakat report type</strong> as <strong>Subcontractor</strong>, and then click <strong>Print</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - LedgerZakatHeaderTmp\_SA table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the LedgerZakatHeaderDP_SA.processReport class.</P>



  - VendSubcontractorZakatTmp\_SA table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the VendSubcontractorDP_SA.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


