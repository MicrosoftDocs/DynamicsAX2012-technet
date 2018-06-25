---
title: Advanced filtering and query options
TOCTitle: Advanced filtering and query options
ms:assetid: 1c6113f6-be13-462b-8df3-bef7d1424ae8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa569937(v=AX.60)
ms:contentKeyID: 36676372
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Advanced filtering and query options [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The following filtering and query options are available when you use embedded filters or queries.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Syntax</p></th>
<th><p>Character description</p></th>
<th><p>Description</p></th>
<th><p>Example</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Value</p></td>
<td><p>Equal to the value entered.</p></td>
<td><p>Type the value to find.</p></td>
<td><p>Smith finds &quot;Smith&quot;.</p></td>
</tr>
<tr class="even">
<td><p>!value</p>
<p>(exclamation mark)</p></td>
<td><p>Not equal to the value entered.</p></td>
<td><p>Type an exclamation mark in front of the value to exclude.</p></td>
<td><p>!Smith finds all values except &quot;Smith&quot;.</p></td>
</tr>
<tr class="odd">
<td><p>From-value..To-value</p>
<p>(double period)</p></td>
<td><p>Between the two values entered separated by double periods.</p></td>
<td><p>Type the From value, then two periods, and then the To value.</p></td>
<td><p>1..10 finds all values from 1 through 10.</p>
<p>However, in a string field A..C finds all values starting with &quot;A&quot; and &quot;B&quot; and values exactly equal to &quot;C.&quot; For example, &quot;Ca&quot; will not be found.</p>
<p>To find all values from &quot;A*&quot; through &quot;C*&quot;, write A..D.</p></td>
</tr>
<tr class="even">
<td><p>..value</p>
<p>(double period)</p></td>
<td><p>Less than or equal to the value entered.</p></td>
<td><p>Type the two periods and then the value.</p></td>
<td><p>..1000 finds any number less than or equal to 1000, for example &quot;100&quot;, &quot;999,95&quot;, and 1,000.</p></td>
</tr>
<tr class="odd">
<td><p>Value..</p>
<p>(double period)</p></td>
<td><p>Greater than or equal to the value entered.</p></td>
<td><p>Type the value and then the two periods.</p></td>
<td><p>1000.. finds any number greater than or equal to 1000, for example &quot;1,000&quot;, &quot;1,000.01&quot;, and &quot;1,000,000&quot;.</p></td>
</tr>
<tr class="even">
<td><p>&gt;value</p>
<p>(greater than)</p></td>
<td><p>Greater than the value entered.</p></td>
<td><p>Type a greater than sign (&gt;) and then the value.</p></td>
<td><p>&gt;1000 finds any number greater than 1000, for example &quot;1000.01&quot;, &quot;20,000&quot;, and &quot;1,000,000&quot;.</p></td>
</tr>
<tr class="odd">
<td><p>&lt;value</p>
<p>(less than)</p></td>
<td><p>Less than the value entered.</p></td>
<td><p>Type a less than sign (&lt;) and then the value.</p></td>
<td><p>&lt;1000 finds any number less than 1000, for example &quot;999.99&quot;, &quot;1&quot;, and &quot;-200&quot;.</p></td>
</tr>
<tr class="even">
<td><p>value*</p>
<p>(asterisk)</p></td>
<td><p>Starting with the value entered.</p></td>
<td><p>Type the starting value and then an asterisk.</p></td>
<td><p>S* finds any string that starts with S, such as &quot;Stockholm&quot;, &quot;Sydney&quot;, and &quot;San Francisco.&quot;</p></td>
</tr>
<tr class="odd">
<td><p>*value</p>
<p>(asterisk)</p></td>
<td><p>Ending with the value entered.</p></td>
<td><p>Type an asterisk and then the ending value.</p></td>
<td><p>*east finds any string that ends with east, such as &quot;Northeast&quot; and &quot;Southeast.&quot;</p></td>
</tr>
<tr class="even">
<td><p>*value*</p>
<p>(asterisk)</p></td>
<td><p>Contains the value entered.</p></td>
<td><p>Type an asterisk, then a value, and then another asterisk.</p></td>
<td><p>*th* finds any string that contains &quot;th,&quot; such as &quot;Northeast&quot; and &quot;Southeast.&quot;</p></td>
</tr>
<tr class="odd">
<td><p>?</p>
<p>(question mark)</p></td>
<td><p>Having one or more unknown characters</p></td>
<td><p>Type a question mark at the position of the unknown character in the value.</p></td>
<td><p>Sm?th finds &quot;Smith&quot; and &quot;Smyth&quot;</p></td>
</tr>
<tr class="even">
<td><p>value,value</p>
<p>(comma)</p></td>
<td><p>Matching the values entered separated by commas.</p></td>
<td><p>Type all your criteria separated by commas.</p></td>
<td><p>A, D, F, G finds exactly &quot;A&quot;, &quot;D&quot;, &quot;F&quot; and &quot;G&quot;.</p>
<p>10, 20, 30, 100 finds exactly &quot;10, 20, 30, 100&quot;.</p></td>
</tr>
<tr class="odd">
<td><p>(SQL Statement)</p>
<p>(SQL statement between parenthesis)</p></td>
<td><p>Matching a defined query</p></td>
<td><p>Type a query as an SQL statement between parentheses.</p></td>
<td><p>(data source.Fieldname != &quot;A&quot;)</p></td>
</tr>
<tr class="even">
<td><p>T</p></td>
<td><p>Today’s date</p></td>
<td><p>Type “T”</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>(methodName(parameters))</p>
<p>(SysQueryRanget Util method between parenthesis)</p></td>
<td><p>Matching the value or range of values specified by the parameters of the SysQueryRangeUtil method</p></td>
<td><p>Type a SysQueryRangeUtil method with parameters that specify the value or range of values. For more information, see <a href="https://technet.microsoft.com/en-us/library/gg964746(v=ax.60)">SysQueryRangeUtil</a>.</p></td>
<td><p></p>
<ol>
<li><p>Click <strong>Accounts receivable</strong> &gt; <strong>Common</strong> &gt; <strong>Customer invoices</strong> &gt; <strong>Open customer invoices</strong>.</p></li>
<li><p>Press CTRL+F3 to open the <strong>Inquiry</strong> form.</p></li>
<li><p>On the <strong>Range</strong> tab, click <strong>Add</strong>.</p></li>
<li><p>In the <strong>Table</strong> field, select <strong>Open customer transactions</strong>.</p></li>
<li><p>In the <strong>Field</strong> field, select <strong>Due date</strong>.</p></li>
<li><p>In the <strong>Criteria</strong> field, enter the following:</p>
<p>(yearRange(-2,0))</p></li>
<li><p>Click <strong>OK</strong>. The list page is updated to list the invoices that match the criteria. For this specific example, invoices that were due in the previous two years are listed in the list page.</p></li>
</ol>
<p>The following are additional examples of SysQueryRangeUtil methods with Parameters:</p>
<ul>
<li><p>Yesterday – Enter “(Day(-1))”</p></li>
<li><p>Today – Enter “(Day(0))”</p></li>
<li><p>Tomorrow – Enter “(Day(1))”</p></li>
<li><p>Last 30 days – Enter “(DayRange(-30,0))</p></li>
<li><p>Previous 30 days and future 30 days– Enter “(DayRange(-30,30))”</p></li>
</ul></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

