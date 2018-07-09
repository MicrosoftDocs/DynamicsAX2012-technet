---
title: About parameters for time and attendance
TOCTitle: About parameters for time and attendance
ms:assetid: 043f61f0-67f8-4f38-a1b7-d98e949ca0cf
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa569708(v=AX.60)
ms:contentKeyID: 36055945
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# About parameters for time and attendance [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic includes general information about the parameters that you must set before you can use time and attendance with **Human resources**. For more detailed information about specific time and attendance parameters, see [Time and attendance parameters (form)](https://technet.microsoft.com/en-us/library/aa634266\(v=ax.60\)).

The parameters are divided into the following categories:

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
<td><p><strong>General</strong></p></td>
<td><p>General parameters primarily include the settings for basic registration, such as refresh rates for registration forms and dimensions for absence registration.</p></td>
</tr>
<tr class="even">
<td><p><strong>Project</strong></p></td>
<td><p>If workers register on projects, you must specify which project journals to use and whether cost categories are applied when registrations are posted. Dimension control for project posting is also specified in this section.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Indirect activities</strong></p></td>
<td><p>Specify an indirect activities journal, cost category usage, and dimension control for indirect activities.</p></td>
</tr>
<tr class="even">
<td><p><strong>Cost price</strong></p></td>
<td><p>If workers’ time registrations are based on actual pay (real cost), specify which pay categories should be included in cost prices.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Payroll</strong></p></td>
<td><p>Select an export file that contains payroll information, which can be used in an external payroll system.</p></td>
</tr>
<tr class="even">
<td><p><strong>Display options</strong></p></td>
<td><p>Select configurations for the <strong>Electronic timecard</strong>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Number sequences</strong></p></td>
<td><p>Set up basic number sequences used in time and attendance.</p>
<div class="alert">

> [!NOTE]
> <P>If you use job scheduling in production, the number sequence code for job identification in time and attendance must be the same as the job identification number sequence code in the <STRONG>Number sequences</STRONG> form. (Click <STRONG>Organization administration</STRONG> &gt; <STRONG>Common</STRONG> &gt; <STRONG>Number sequences</STRONG> &gt; <STRONG>Number sequences</STRONG>.)</P>


</div></td>
</tr>
</tbody>
</table>



> [!NOTE]
> <P>All parameters regarding integration to <STRONG>Production control</STRONG> are located in the <STRONG>Production parameters</STRONG> form.</P>


  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

