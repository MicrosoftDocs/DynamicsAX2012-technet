---
title: Report Sections (MorphX Reporting Tools)
TOCTitle: Report Sections
ms:assetid: bd9992d1-caf7-418a-a642-c0442932bb19
ms:mtpsurl: https://technet.microsoft.com/library/Aa862247(v=AX.60)
ms:contentKeyID: 35290332
author: tonyafehr
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# Report Sections (MorphX Reporting Tools) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Sections determine the layout of a report in MorphX. Sections can be defined by a report template or directly in the custom design in your report. All the sections can be repeated.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Section</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Prolog</p></td>
<td><p>Appears at the beginning of a report.</p>
<p>Use this section to display items such as a logo, a report title, or the current date. The prolog is printed before the page header on the first page of the report.</p></td>
</tr>
<tr class="even">
<td><p>PageHeader</p></td>
<td><p>Appears at the top of every page in a report.</p></td>
</tr>
<tr class="odd">
<td><p>Header</p></td>
<td><p>Only available for generated designs. Appears at the beginning of a new group of records. Use it to display items such as a group name.</p></td>
</tr>
<tr class="even">
<td><p>SectionGroup</p></td>
<td><p>Only available for generated designs. Appears in the middle of a report.</p>
<p>A section group can contain a Header, Body, or a Footer section.</p>
<p>The structure of data sources is reflected in the structure of the section groups.</p></td>
</tr>
<tr class="odd">
<td><p>Body</p></td>
<td><p>Appears in the middle of the report.</p>
<p>A body section contains controls or a SectionGroup. The controls show information from fields in the data sources (tables), or information provided by display methods.</p></td>
</tr>
<tr class="even">
<td><p>Footer</p></td>
<td><p>Only available for generated designs. Appears at the end of a group of records.</p>
<p>Use it to display items such as sub totals.</p></td>
</tr>
<tr class="odd">
<td><p>PageFooter</p></td>
<td><p>Appears at the bottom of every page in a report.</p>
<p>Use it to display items such as page numbers.</p></td>
</tr>
<tr class="even">
<td><p>Epilog</p></td>
<td><p>Appears at the end of the report.</p>
<p>Use it to display items such as a logo. The epilog is printed just after the page footer on the last page in a report.</p></td>
</tr>
<tr class="odd">
<td><p>ProgrammableSection</p></td>
<td><p>Use programmable sections to add any kind of customized information.</p>
<p>To activate a programmable section, activate it explicitly with an element.execute( Number ) statement. The Number must be specified in the ControlNumber property for the design section.</p></td>
</tr>
</tbody>
</table>


For information about modifying the printing of report sections, see [How to: Modify Report Sections by Using X++ (MorphX Reporting Tools)](how-to-modify-report-sections-by-using-x-morphx-reporting-tools.md).

## See also

[Walkthrough: Creating Reports in the AOT (MorphX Reporting Tools)](walkthrough-creating-reports-in-the-aot-morphx-reporting-tools.md)

