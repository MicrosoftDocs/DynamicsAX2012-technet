---
title: Total outstanding debt by period chart report (OustandingDebtByPeriod)
TOCTitle: Total outstanding debt by period chart report (OustandingDebtByPeriod)
ms:assetid: b2f2b23d-b137-46e6-a382-ff0995feb46b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh692475(v=AX.60)
ms:contentKeyID: 41702372
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.OutstandingDebtByPeriod
---

# Total outstanding debt by period chart report (OustandingDebtByPeriod) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This chart report displays the total outstanding debt by period, in a graphical format. This chart report is intended for treasurers.


> [!NOTE]
> <P>This report is designed for use on Role Centers.</P>



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
<td><p>OutstandingDebtByPeriod</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>\SSRS Reports\Reports\OutstandingDebtByPeriod</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>TreasurerOutstandingDebtByPeriod</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>This report is available on the Treasurer Role Center.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - DynamicsAXOLAP cube

  - BICOMPANYVIEW table

  - GENERALJOURNALCUBE table

  - LEDGERPERIODDATEDIMENSIONVIEW table

  - MAINACCOUNTCUBE table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

