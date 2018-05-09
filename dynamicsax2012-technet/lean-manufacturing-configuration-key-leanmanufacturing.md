---
title: Lean manufacturing configuration key (LeanManufacturing)
TOCTitle: Lean manufacturing configuration key (LeanManufacturing)
ms:assetid: 8b4de806-056e-4a44-8537-c13574828f3c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh500662(v=AX.60)
ms:contentKeyID: 37822135
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Lean manufacturing configuration key (LeanManufacturing) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Lean manufacturing** configuration key controls access to forms and functions that are used in Microsoft Dynamics AX lean manufacturing. If this configuration key is enabled, you can use the following feature sets:

  - Modeling a lean organization by using production flows and activities

  - Implementing a lean pull system by using kanbans

  - Planning and scheduling kanban jobs by using kanban boards

  - Costing for lean manufacturing


> [!NOTE]
> <P>Enabling this configuration key affects Microsoft Dynamics AX performance. Enable this key only if the associated features and functionality are necessary in your implementation.</P>



You cannot enable or disable this key in the **License configuration** form.

## Forms enabled by the configuration key

The following forms are available when the configuration key is enabled.

## Inventory management forms

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Form</p></th>
<th><p>For more information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Variances</strong></p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


## Production control forms

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Form</p></th>
<th><p>For more information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Production flow activities</strong></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh208824(v=ax.60)">Production flow activities (form)</a></p></td>
</tr>
<tr class="even">
<td><p><strong>Add existing plan activity</strong></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh209519(v=ax.60)">Add existing activity (class form)</a></p></td>
</tr>
<tr class="odd">
<td><p><strong>Create activity relation</strong></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh209655(v=ax.60)">Create activity relation (form)</a></p></td>
</tr>
<tr class="even">
<td><p><strong>Backflush costing calculation</strong></p></td>
<td><p>Use this form to cost production flows. Click <strong>Production control</strong> &gt; <strong>Periodic</strong> &gt; <strong>Lean manufacturing</strong> &gt; <strong>Backflush costing calculation</strong>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>BOM version</strong></p></td>
<td><p>Use this form to assign an alternative BOM (bill of material) version to a kanban. Click <strong>Production control</strong> &gt; <strong>Setup</strong> &gt; <strong>Lean manufacturing</strong> &gt; <strong>Kanban rules</strong>. On the <strong>Kanbans</strong> FastTab, click <strong>Details</strong>. On the <strong>Action Pane</strong>, on the <strong>Setup</strong> tab, click <strong>Assign</strong>, and then click <strong>BOM version</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Work cell</strong></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh209489(v=ax.60)">Work cell filter (form)</a></p></td>
</tr>
<tr class="odd">
<td><p><strong>Choose kanban flow</strong></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh227439(v=ax.60)">Choose kanban flows (form)</a></p></td>
</tr>
<tr class="even">
<td><p><strong>Circulating cards</strong></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh242877(v=ax.60)">Circulating cards (form)</a></p></td>
</tr>
<tr class="odd">
<td><p><strong>Create new plan activity</strong></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh227522(v=ax.60)">Create new plan activity (form)</a></p></td>
</tr>
<tr class="even">
<td><p><strong>Cycle time history</strong></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh227651(v=ax.60)">Cycle time history (form)</a></p></td>
</tr>
<tr class="odd">
<td><p><strong>Default production flow</strong></p></td>
<td><p>Use this form to set up default production flows. This information is used in the BOM calculation. Click <strong>Production control</strong> &gt; <strong>Setup</strong> &gt; <strong>Lean manufacturing</strong> &gt; <strong>Default production flow</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Production flow version details</strong></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh209606(v=ax.60)">Production flow version details (form)</a></p></td>
</tr>
<tr class="odd">
<td><p><strong>Activity details</strong></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh527164(v=ax.60)">Activity details (form)</a></p></td>
</tr>
<tr class="even">
<td><p><strong>Filter kanban rules</strong></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh334509(v=ax.60)">Filter kanban rules (form)</a></p></td>
</tr>
<tr class="odd">
<td><p><strong>Job list - limit display</strong></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh781088(v=ax.60)">Job list - limit display (form)</a></p></td>
</tr>
<tr class="even">
<td><p><strong>Kanban board for process jobs</strong></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh781101(v=ax.60)">Kanban board for process jobs (form)</a></p>
<p><a href="https://technet.microsoft.com/en-us/library/hh209489(v=ax.60)">Work cell filter (form)</a></p></td>
</tr>
<tr class="odd">
<td><p><strong>Kanban board for transfer jobs</strong></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh781100(v=ax.60)">Kanban board for transfer jobs (form)</a></p>
<p><a href="https://technet.microsoft.com/en-us/library/hh209576(v=ax.60)">Filter transfer kanban jobs (form)</a></p>
<p></p></td>
</tr>
<tr class="even">
<td><p><strong>Kanban quantity calculation policies</strong></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh527163(v=ax.60)">Kanban quantity calculation policies (form)</a></p></td>
</tr>
<tr class="odd">
<td><p><strong>Kanban quantity calculation</strong></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh597101(v=ax.60)">Kanban quantity calculation (form)</a></p></td>
</tr>
<tr class="even">
<td><p><strong>Kanban rules</strong></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh227370(v=ax.60)">Kanban rules (form)</a></p></td>
</tr>
<tr class="odd">
<td><p><strong>Kanban schedule board</strong></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh597153(v=ax.60)">Kanban schedule board (form)</a></p>
<p><a href="https://technet.microsoft.com/en-us/library/hh209489(v=ax.60)">Work cell filter (form)</a></p></td>
</tr>
<tr class="even">
<td><p><strong>Kanban</strong></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh242799(v=ax.60)">Kanban (form)</a></p></td>
</tr>
<tr class="odd">
<td><p><strong>Lean schedule group items</strong></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh209622(v=ax.60)">Lean schedule items (form)</a></p></td>
</tr>
<tr class="even">
<td><p><strong>Lean schedule groups</strong></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh208792(v=ax.60)">Lean schedule groups (form)</a></p></td>
</tr>
<tr class="odd">
<td><p><strong>New service activity</strong></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh803025(v=ax.60)">Add subcontracting service to activity (form)</a></p></td>
</tr>
<tr class="even">
<td><p><strong>The number of planning periods</strong></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh597348(v=ax.60)">Number of planning periods (form)</a></p></td>
</tr>
<tr class="odd">
<td><p><strong>Pegging tree overview</strong></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh694720(v=ax.60)">Pegging tree overview (form)</a></p></td>
</tr>
<tr class="even">
<td><p><strong>Production flow models</strong></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh209069(v=ax.60)">Production flow model (form)</a></p></td>
</tr>
<tr class="odd">
<td><p><strong>Production flows</strong></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh208997(v=ax.60)">Production flows (form)</a></p></td>
</tr>
<tr class="even">
<td><p><strong>Refresh cycle</strong></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh209591(v=ax.60)">Refresh cycle (form)</a></p></td>
</tr>
<tr class="odd">
<td><p><strong>Service activity details</strong></p></td>
<td><p>Use this form to view detailed information about the subcontracted service. Click <strong>Production control</strong> &gt; <strong>Setup</strong> &gt; <strong>Lean manufacturing</strong> &gt; <strong>Production flows</strong>. On the <strong>Versions</strong> tab, click <strong>Activities</strong>. Click <strong>Details</strong>, and then, on the <strong>Service terms</strong> FastTab, click <strong>Details</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Time buckets setup</strong></p></td>
<td><p>Use this form to set up time buckets that are used in costing. Click <strong>Production control</strong> &gt; <strong>Periodic</strong> &gt; <strong>Lean manufacturing</strong> &gt; <strong>Backflush costing calculation</strong>. Click <strong>Time buckets setup</strong>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Unused quantity</strong></p></td>
<td><p>Use this form to view the quantities that are still WIP (work in process). Click <strong>Production control</strong> &gt; <strong>Periodic</strong> &gt; <strong>Lean manufacturing</strong> &gt; <strong>Backflush costing calculation</strong>. Click <strong>Unused quantity</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Use alternative kanban rule</strong></p></td>
<td><p>Use this wizard to select an alternative kanban rule to fulfill a kanban. Click <strong>Production control</strong> &gt; <strong>Setup</strong> &gt; <strong>Lean manufacturing</strong> &gt; <strong>Kanban rules</strong>. On the <strong>Kanbans</strong> FastTab, click <strong>Details</strong>. On the <strong>Action Pane</strong>, on the <strong>Setup</strong> tab, click <strong>Assign</strong>, and then click <strong>Use alternative kanban rule</strong>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>View cards</strong></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh242877(v=ax.60)">Circulating cards (form)</a></p></td>
</tr>
<tr class="even">
<td><p><strong>View kanban flow</strong></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh208682(v=ax.60)">Kanban flow (form)</a></p></td>
</tr>
</tbody>
</table>


## Additional information about this configuration key

The following table provides information about how this configuration key relates to other configuration keys and license codes.

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
<td><p>License code</p></td>
<td><p><strong>Lean manufacturing</strong></p></td>
</tr>
<tr class="even">
<td><p>Parent key</p></td>
<td><p>None</p></td>
</tr>
<tr class="odd">
<td><p>Child keys</p></td>
<td><p>None</p></td>
</tr>
</tbody>
</table>


For more information about how license codes and configuration keys work together, see [About license codes and configuration keys](https://technet.microsoft.com/en-us/library/aa548653\(v=ax.60\)).

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

