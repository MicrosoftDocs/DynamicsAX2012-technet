---
title: (BEL) Belgian sales tax reporting report (TaxReport_BE)
TOCTitle: (BEL) Belgian sales tax reporting report (TaxReport_BE)
ms:assetid: 93cfa6f6-72b1-4731-856a-83d904622d22
ms:mtpsurl: https://technet.microsoft.com/library/Hh527154(v=AX.60)
ms:contentKeyID: 37823205
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- tax report
- SSRS_Reports.Reports.TaxReport_BE
- sales tax
- TaxReport_BE
- (BEL)
- sales tax report
- Sales tax reporting report
---

# (BEL) Belgian sales tax reporting report (TaxReport\_BE) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Belgian sales tax reporting** report displays information related to sales tax payments and prints the information in the Belgian layout. This report is generated for a settlement period that is set up in the **Sales tax settlement periods** form, according to the setup of the sales tax reporting codes in the **Sales tax reporting codes** form. This report is typically used by accountants, accounting managers, accounting supervisors, and financial controllers to inquire into the status of sales tax transactions.


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
<td><p>TaxReport_BE</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\TaxReport_BE</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>TaxReport_BE</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>External</strong> &gt; <strong>Sales tax payments</strong>. Select a sales tax payment transaction, and then click <strong>Belgian sales tax reporting</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - TaxReportTmp\_BE table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the TaxReportDP_BE.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[(BEL) Additional sales tax report boxes (form)](https://technet.microsoft.com/library/aa599851\(v=ax.60\))

[Sales tax settlement periods (form)](https://technet.microsoft.com/library/aa633944\(v=ax.60\))

  


