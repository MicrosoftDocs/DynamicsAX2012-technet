---
title: (SAU) Provisions and reservations report (LedgerProvisions_SA)
TOCTitle: (SAU) Provisions and reservations report (LedgerProvisions_SA)
ms:assetid: 2230af1a-1502-4194-8804-7b263710370d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh371725(v=AX.60)
ms:contentKeyID: 36814938
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- reservations
- SSRS_Reports.Reports.LedgerProvisions_SA
- (SAU)
- Provisions
- Provisions and reservations report
---

# (SAU) Provisions and reservations report (LedgerProvisions\_SA) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Provisions and reservations** report displays a summary of all provisions and reservations. This report includes information such as the opening balance, other additions, other deductions, and closing balance for a ledger account.

This report must be submitted to the Department of Zakat and Income Tax (DZIT) by legal entities operating in Saudi Arabia. Legal entities must generate and submit this report along with 13 other Zakat reports, their balance sheet, and their profit-and-loss statement to the DZIT within a month of the end of the fiscal year. For more information about the other Zakat reports, see [(SAU) About Zakat reporting](sau-about-zakat-reporting.md).


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
<td><p>Enter the fiscal year for which to generate the report.</p></td>
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
<td><p>LedgerProvisions_SA</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ LedgerProvisions_SA</p></td>
</tr>
<tr class="odd">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Periodic</strong> &gt; <strong>Zakat</strong> &gt; <strong>Zakat reports</strong>. In the <strong>Select</strong> field, select the line with the <strong>Zakat report type</strong> as <strong>Provisions and reservations</strong>, and then click <strong>Print</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - LedgerProvisionsTmp\_SA table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the LedgerProvisionsDP_SA.processReport class.</P>



  - LedgerZakatHeaderTmp\_SA table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the LedgerZakatHeaderDP_SA.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[About fixed asset reserves](about-fixed-asset-reserves.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

