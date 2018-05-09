---
title: 'Deprecated: LedgerPeriod form and table'
TOCTitle: LedgerPeriod form and table
ms:assetid: 63fd0666-2b75-4698-8ed3-b58988c91286
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn527130(v=AX.60)
ms:contentKeyID: 59623259
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Deprecated: LedgerPeriod form and table 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX 2009, the LedgerPeriod table and form are used to create and maintain the fiscal periods for a company.

## Overview

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Item</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Reason for deprecation</p></td>
<td><p>Global organizations operate as different legal entities in different geographical areas. However, they share a lot of data, such as charts of accounts, currencies, exchange rates, and calendars. Defining this reference and master data once and sharing it across legal entities reduces the cost of maintaining such data across the organization. However, ledger periods, and the associated AssetCalendar tables, did not provide sufficient support for this scenario and have been replaced with more robust shared fiscal calendars. The following tables have been deprecated:</p>
<ul>
<li><p>AssetCalendar</p></li>
<li><p>AssetCalendarPeriod</p></li>
<li><p>AssetCalendarYear</p></li>
<li><p>LedgerPeriod</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Replaced by another feature</p></td>
<td><p>Yes. The feature is no longer available and has been replaced with shared fiscal calendars.</p>
<p>For more information, see <a href="about-fiscal-calendars-fiscal-years-and-periods.md">About fiscal calendars, fiscal years, and periods</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Modules affected</p></td>
<td><p>All</p></td>
</tr>
<tr class="even">
<td><p>Changes to installation</p></td>
<td><p>This change does not affect application installation.</p></td>
</tr>
<tr class="odd">
<td><p>Changes to upgrade</p></td>
<td><p>Existing ledger periods and fixed asset calendars are upgraded to the new fiscal calendars. There is a pre-upgrade step where the user can rename the fiscal calendars.</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

