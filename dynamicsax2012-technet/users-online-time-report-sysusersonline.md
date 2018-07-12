---
title: Users online time report (SysUsersOnline)
TOCTitle: Users online time report (SysUsersOnline)
ms:assetid: bcfaf9cf-3758-4192-bc78-7635fb30f650
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa556946(v=AX.60)
ms:contentKeyID: 36687380
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.SysUsersOnline
---

# Users online time report (SysUsersOnline) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Click **System administration** \> **Reports** \> **Security** \> **Online time**.

This report shows logon times, logoff times, and total hours logged on to Microsoft Dynamics AX for individual users.

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
<td><p><strong>User ID</strong></p></td>
<td><p>The identifier for the user.</p></td>
</tr>
<tr class="even">
<td><p><strong>Created date and time</strong></p></td>
<td><p>The date and time when the record was created.</p></td>
</tr>
<tr class="odd">
<td><p><strong>User name</strong></p></td>
<td><p>The user's full name.</p></td>
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
<td><p>SysUsersOnline</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\SysUsersOnline</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>SysUsersOnlineReport</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>System administration</strong> &gt; <strong>Reports</strong> &gt; <strong>Security</strong> &gt; <strong>Online time</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - SysUserLog

  - UserInfo

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


