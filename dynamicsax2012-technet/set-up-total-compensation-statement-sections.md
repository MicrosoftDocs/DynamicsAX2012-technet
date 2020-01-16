---
title: Set up total compensation statement sections
TOCTitle: Set up total compensation statement sections
ms:assetid: 293a3609-0729-4ce4-a58d-60968b3c2179
ms:mtpsurl: https://technet.microsoft.com/library/Dn887952(v=AX.60)
ms:contentKeyID: 63404229
author: Khairunj
ms.date: 11/19/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up total compensation statement sections 


This topic explains how to set up a total compensation statement. A total compensation statement is comprised of sections which contain compensation elements such as benefits, tax codes, and earning codes. To set up a total compensation statement, first create at least one total compensation statement section. Then add the compensation elements that you want to include on the statement into the sections. You can use the total compensation statement sections to organize the compensation elements into logical groups. Totals for each section will be included in the total compensation statement.

You can add any combination of compensation elements to each total compensation statement section. The three types of compensation elements that can be added to a total compensation statement section are:

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Compensation type</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Benefits</p></td>
<td><p>You can select any of the benefits that are set up in the system.</p></td>
</tr>
<tr class="even">
<td><p>Earnings</p></td>
<td><p>You can select any of the earnings codes and earnings groups that are set up in the system. Any earning codes with a Pay statement line source equal to “Fringe benefit recovery” will not be included in the total compensation statement.</p></td>
</tr>
<tr class="odd">
<td><p>Taxes</p></td>
<td><p>You can select any of the tax codes and any of the tax groups that are set up in the system.</p></td>
</tr>
</tbody>
</table>


While it is more likely that you’ll use this functionality to create total compensation statements, you could also create benefit statements or tax statements using this functionality.

## Prerequisites

The following table shows the prerequisites that must be in place before you start.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Version</p></td>
<td><p>Microsoft Dynamics AX 2012 R3 with Cumulative Update 8.</p></td>
</tr>
<tr class="even">
<td><p>Country/region</p></td>
<td><p>(USA) The primary address for the legal entity must be in the following countries/regions: United States.</p></td>
</tr>
<tr class="odd">
<td><p>Related configuration tasks</p></td>
<td><p><a href="set-up-benefits.md">Set up benefits</a></p>
<p><a href="worker-and-position-payroll-tasks.md">Worker and position payroll tasks</a></p>
<p><a href="tax-information-tasks.md">Tax information tasks</a></p></td>
</tr>
</tbody>
</table>


## 1\. Set up a total compensation section

Total compensation statement sections contain the compensation elements to be included on the total compensation statement. Before you can add compensation elements to a total compensation section, you must create the section. You can create any number of sections.

To set up a total compensation section, follow these steps:

1.  **Human resources** \> **Setup** \> **Compensation** \> **Total compensation statement sections**

2.  Click **New** to create a new total compensation statement section.

3.  In the **Statement section ID** field, enter a unique ID to identify the total compensation statement section.

4.  In the **Statement section name** field, enter a name for the total compensation statement section. The value entered will display as the section name on the total compensation statement.

## 2\. Manage the benefits that will appear on a total compensation statement

To add benefits to a total compensation section, follow these steps:

1.  **Human resources** \> **Setup** \> **Compensation** \> **Total compensation statement sections**

2.  Select an existing total compensation section or set up a new total compensation section.

3.  In the **Benefits** FastTab, click **Add** to open the **Select benefits to include in the statement section** window.

4.  Select one more benefit plans and click **Add**.

To remove benefits from a total compensation section, follow these steps:

1.  **Human resources** \> **Setup** \> **Compensation** \> **Total compensation statement sections**

2.  Select an existing total compensation section.

3.  In the **Benefits** FastTab, select one or more benefit plans from the list.

4.  Click **Remove**.

5.  Click **Yes** in the **Confirm deletion** dialog box.

## 3\. Manage the earnings that will appear on a total compensation statement

To add earnings to a total compensation section, follow these steps:

1.  **Human resources** \> **Setup** \> **Compensation** \> **Total compensation statement sections**

2.  Select an existing total compensation section or set up a new total compensation section.

3.  In the **Earnings** FastTab, click **Add earning code** to open the **Select earning codes to include in the statement section** window or click **Add earning group** to open the **Select earning groups to include in the statement section** window.

4.  Select one more earning codes or earning groups and click **Add**.

To remove earnings from a total compensation section, follow these steps:

1.  **Human resources** \> **Setup** \> **Compensation** \> **Total compensation statement sections**

2.  Select an existing total compensation section.

3.  In the **Earnings** FastTab, select any combination of earning codes and earning groups from the list.

4.  Click **Remove**.

5.  Click **Yes** in the **Confirm deletion** dialog box.

## 4\. Manage the taxes that will appear on a total compensation statement

To add taxes to a total compensation section, follow these steps:

1.  **Human resources** \> **Setup** \> **Compensation** \> **Total compensation statement sections**

2.  Select an existing total compensation section or set up a new total compensation section.

3.  In the **Taxes** FastTab, click **Add tax code** to open the **Select tax codes to include in the statement section** window or click **Add tax group** to open the **Select tax groups to include in the statement section** window.

4.  Select one more tax codes or tax groups and click **Add**.

To remove taxes from a total compensation section, follow these steps:

1.  **Human resources** \> **Setup** \> **Compensation** \> **Total compensation statement sections**

2.  Select an existing total compensation section.

3.  In the **Taxes** FastTab, select any combination of tax codes and tax groups from the list.

4.  Click **Remove**.

5.  Click **Yes** in the **Confirm deletion** dialog box.

## Next step

Once you have added all the benefits, earning codes, earning groups, tax codes, and tax groups to the total compensation statement sections you can print the total compensation statements. The total compensation statement will print based on payroll payment dates that fall within the selected date range. For more information, see Print total compensation statements.

## Related tasks

[Processing payroll](processing-payroll.md)

## Technical information for system administrators

If you don't have access to the pages that are used to complete this task, contact your system administrator and provide the information that is shown in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Configuration keys</strong></p></td>
<td><p>Payroll - USA</p>
<div class="alert">

> [!WARNING]
> <P>When you use Payroll, we highly recommend that you turn off the <STRONG>Payroll information</STRONG> configuration key under the <STRONG>Human resource I</STRONG> configuration key. The forms and tables that are enabled by that configuration key are not used by Payroll. If Payroll is installed and the configuration key is enabled, it might be difficult to make sure that your data is entered and tracked correctly.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Security roles and duties</strong></p></td>
<td><p>To set up total compensation statement sections, you must be a member of a security role that includes these duties:</p>
<ul>
<li><p><strong>Enable compensation process</strong></p></li>
<li><p><strong>Maintain pay statements</strong></p></li>
<li><p><strong>Set up payroll master data</strong></p></li>
</ul>
<p>To view total compensation statement sections, you must be a member of a security role that includes this duty:</p>
<ul>
<li><p><strong>Inquire into compensation process</strong></p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To set up total compensation statement sections, you must be a member of a security role that includes this privilege:</p>
<ul>
<li><p><strong>Create total compensation statement report sections</strong></p></li>
</ul>
<p>To view total compensation statement sections, you must be a member of a security role that includes this privilege:</p>
<ul>
<li><p><strong>View total compensation statement report sections</strong></p></li>
</ul></td>
</tr>
</tbody>
</table>

  


