---
title: Table and table group reference
TOCTitle: Table and table group reference
ms:assetid: 0d41cc20-f60d-4b0e-8f5d-6dca9fb0d82a
ms:mtpsurl: https://technet.microsoft.com/library/Gg731855(v=AX.60)
ms:contentKeyID: 35132719
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Table and table group reference 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Table groups are defined by the TableGroup property of tables. You can use table groups to select sets of tables when you define a table definition group for export. You can also use table groups to manage which tables are stored in the cache.

There are approximately 7,900 tables in Microsoft Dynamics AX 2012 R3, organized into table groups.

## Spreadsheet of all tables and table groups

A spreadsheet that lists all core Microsoft Dynamics AX data tables is available from the Download Center: [Microsoft Dynamics AX 2012 Tables and Table Groups](https://go.microsoft.com/fwlink/?linkid=213812).

The spreadsheet lists the following information for each table, includes a pivot table, as well as a list of all the tables that were removed from AX 2012 between the initial release and AX 2012 R3.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Column</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Table name</p></td>
<td><p>AOT name of the table</p></td>
</tr>
<tr class="even">
<td><p>Table group</p></td>
<td><p>Associated table group</p></td>
</tr>
<tr class="odd">
<td><p>Table type</p></td>
<td><p>The TableType property of a table determines where the table is stored. The following options are available:</p>
<p>Regular – The table is stored in the Microsoft Dynamics AX database.</p>
<p>TempDB – The table is stored in the TempDB database. When you restart Application Object Server (AOS) or the database, all tables in the TempDB database are dropped and recreated.</p>
<p>InMemory – The table is held in memory only during the current Microsoft Dynamics AX session.</p></td>
</tr>
<tr class="even">
<td><p>System table</p></td>
<td><p>A system table is used by the Microsoft Dynamics AX system, not for customer data.</p></td>
</tr>
<tr class="odd">
<td><p>Visible</p></td>
<td><p>A table that can be seen in the AOT.</p></td>
</tr>
<tr class="even">
<td><p>Shared? (SaveDataPerCompany = No)</p></td>
<td><p>Shared tables are used by multiple companies. Tables that are not shared pertain to a single company.</p></td>
</tr>
<tr class="odd">
<td><p>Release table was added in</p></td>
<td><p>Lists the release in which a table was added was added to AX 2012.</p></td>
</tr>
</tbody>
</table>



> [!NOTE]
> <P>The workbook does not include Kernel tables because Kernel tables are not associated with table groups. Additionally, we do not recommend that you export or import Kernel tables.</P>
> <P>The workbook also does not include any DEL_ tables.</P>



## Types of table groups

The following table groups are available in Microsoft Dynamics AX:

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Table group</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Framework</strong></p></td>
<td><p>Tables that are used by the underlying Microsoft Dynamics AX frameworks, such as Application Integration Framework (AIF). These tables are created during installation and are not associated with configuration keys.</p></td>
</tr>
<tr class="even">
<td><p><strong>Group</strong></p></td>
<td><p>Tables that are used to categorize the tables in the Main table group.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Main</strong></p></td>
<td><p>Principal or master tables that contain data for central business objects. These tables typically hold static, base information.</p></td>
</tr>
<tr class="even">
<td><p><strong>Miscellaneous</strong></p></td>
<td><p>Tables that have not been otherwise categorized. Miscellaneous is the default table group for new tables.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Parameter</strong></p></td>
<td><p>Tables that contain parameters or setup information for tables in the Main table group.</p></td>
</tr>
<tr class="even">
<td><p><strong>Reference</strong></p></td>
<td><p>Tables that contain reference data.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Transaction, Transaction header, and Transaction line</strong></p></td>
<td><p>Tables that contain transaction data.</p>
<p>The tables in the Transaction header table group categorize the tables in the Transaction line table group.</p>
<p>There is a one-to-many relationship between a Transaction header table and Transaction line tables.</p></td>
</tr>
<tr class="even">
<td><p><strong>Worksheet, Worksheet header, and Worksheet line</strong></p></td>
<td><p>Tables that contain information that is validated and made into transactions.</p>
<p>Unlike the data that is contained in the tables in the Transaction table groups, data in the Worksheet table groups is temporary.</p></td>
</tr>
</tbody>
</table>


## See also

[Create definition groups for import and export](create-definition-groups-for-import-and-export.md)

  


