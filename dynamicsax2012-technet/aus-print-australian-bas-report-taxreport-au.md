---
title: (AUS) Print Australian BAS report (TaxReport_AU)
TOCTitle: (AUS) Print Australian BAS report (TaxReport_AU)
ms:assetid: e6e0a718-6bfa-4291-807a-995a088270c3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa558463(v=AX.60)
ms:contentKeyID: 36687386
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- report
- SSRS_Reports.Reports.TaxReport_AU
- TaxReport_AU
- (AUS)
- Australian
- BAS
- Business activity statement
---

# (AUS) Print Australian BAS report (TaxReport\_AU) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Print Australian BAS** report is used to create an electronic tax declaration report known as a Business Activity Statement. This report is typically used by accountants, accounting managers, and accounting supervisors.


> [!NOTE]
> <P>(AUS) This report is available only to legal entities whose primary address is in Australia.</P>



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
<td><p>TaxReport_AU</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\TaxReport_AU</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>TaxReport_AU</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>External</strong> &gt; <strong>Sales tax payments</strong>. Select a sales tax payment transaction, and then click <strong>Print Australian BAS</strong>.</p>
<p>–or–</p>
<p>Click <strong>General ledger</strong> &gt; <strong>Periodic</strong> &gt; <strong>Sales tax payments</strong> &gt; <strong>Additional BAS report boxes</strong>. Select the settlement period and other details, and then click <strong>Print Australian BAS</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - TaxReportTmp\_AU table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the TaxReportDP_AU.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[(AUS) Additional BAS report boxes (form)](https://technet.microsoft.com/en-us/library/aa584353\(v=ax.60\))

[(AUS) Australian BAS (form)](https://technet.microsoft.com/en-us/library/aa634554\(v=ax.60\))

[Sales tax payment (class form)](https://technet.microsoft.com/en-us/library/aa598539\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

