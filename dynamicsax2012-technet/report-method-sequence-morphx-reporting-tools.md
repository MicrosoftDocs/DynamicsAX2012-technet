---
title: Report Method Sequence (MorphX Reporting Tools)
TOCTitle: Report Method Sequence
ms:assetid: 80c72a15-fff1-4430-bc35-497a3012dfe9
ms:mtpsurl: https://technet.microsoft.com/library/Aa642980(v=AX.60)
ms:contentKeyID: 35290302
author: tonyafehr
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# Report Method Sequence (MorphX Reporting Tools) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you open a report, the following methods are called in the order that they appear in the table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Method</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>init</p></td>
<td><p>Initializes the report and its objects. This is the earliest method that can be overridden among those executed when a report is constructed and run.</p>
<p>Override this method to add initialization tasks, such as the following:</p>
<ul>
<li><p>Validation of the argument objects received</p></li>
<li><p>Initialization of supporting classes</p></li>
<li><p>Dynamic changes to the design</p></li>
</ul>
<p>If your changes require access to the objects of the report, add your code after the super() call.</p>
<div class="alert">

> [!WARNING]
> <P>Do not delete the super() call from this method. The super() call initializes all the objects of the report.</P>


</div></td>
</tr>
<tr class="even">
<td><p>run</p></td>
<td><p>Runs the report. This method is executed when the user clicks <strong>OK</strong> on the preliminary specification dialog box of the report (which enables the user to select where to send the report, and so on).</p>
<p>The default version of this method does the following in the sequence shown:</p>
<ol>
<li><p>Calls prompt.</p></li>
<li><p>Creates a basic design if it does not already exist.</p></li>
<li><p>Arranges the fields.</p></li>
<li><p>Calls fetch.</p></li>
<li><p>Calls print.</p></li>
</ol></td>
</tr>
<tr class="odd">
<td><p>prompt</p></td>
<td><p>Prompts the user to select a print medium and other information.</p>
<p>Available mediums include paper, the screen, a print archive, .rtf, HTML, ASCII, .pdf, and text (UTF-8).</p>
<p>To disable the print medium selection, override the method, and then remove the call to super().</p>
<div class="alert">

> [!WARNING]
> <P>Do not mistake this method for the method of the same name on a query.</P>


</div></td>
</tr>
<tr class="even">
<td><p>fetch</p></td>
<td><p>Fetches records from the database. The fetch method instantiates a query, opens the query prompt, and then fetches the records.</p>
<p>During the execution of the fetch method, the next and get methods are executed in pairs on the query of the report. The send, the header and/or footer methods, and the progressInfo method are then executed. The cycle continues with calls to next, get, and so on, until all the data has been fetched.</p>
<p>The following are reasons for overriding the fetch method:</p>
<ul>
<li><p>The report is not based on a query.</p></li>
<li><p>Some of the fetched data must be processed (this can also be done on the send method).</p></li>
<li><p>The report is based on a temporary table.</p></li>
</ul>
<p>For more information, see <a href="how-to-override-the-fetch-method-to-filter-data-for-reports-morphx-reporting-tools.md">How to: Override the fetch Method to Filter Data for Reports (MorphX Reporting Tools)</a>.</p></td>
</tr>
<tr class="odd">
<td><p>print</p></td>
<td><p>Prints the report to the selected print medium, such as a printer, file, or screen.</p></td>
</tr>
</tbody>
</table>


## See also

[Report Methods (MorphX Reporting Tools)](report-methods-morphx-reporting-tools.md)

