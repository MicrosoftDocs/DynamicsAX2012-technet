---
title: About formula designer functionality
TOCTitle: About formula designer functionality
ms:assetid: 57d9a4eb-56b4-4aa4-9b6a-2fa4c51b58c6
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh208971(v=AX.60)
ms:contentKeyID: 36057335
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# About formula designer functionality 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Formula designer** form to design and work with formula tree structures. The designer graphically displays the formula structure. You can select different configurations and decide what information to display on the nodes of the tree.


> [!IMPORTANT]
> <P>If you access the designer from the formula, it does not display route information, because the formula is not yet linked to a specific, finished item.</P>



## Use the Designer tab

The **Designer** tab contains the following functionality:

  - A functions pane on the left part of the form that enables you to perform tasks such as to modify a formula version and to add formula items

  - A designer window that displays the tree structure of the formula

  - Current route information for the formula

  - A list of items
    

    > [!NOTE]
    > <P>A site must be specified on the <STRONG>Setup</STRONG> tab. It must use either the default setting or one that you select. If the <STRONG>Site</STRONG> field is cleared, the tree does not display. If there are sub-formulas that use other sites, these do not display inside the tree. The tree displays only the information for one site at a time.</P>



The following table shows the actions that you can perform for each function in the icon pane.

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Function</p></th>
<th><p>Drag-and-drop</p></th>
<th><p>Click icon</p></th>
<th><p>Right-click</p></th>
<th><p>Double-click</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Access information for the lines</p></td>
<td><p>----</p></td>
<td><p>----</p></td>
<td><p>Line or formula</p></td>
<td><p>----</p></td>
</tr>
<tr class="even">
<td><p>Add item</p></td>
<td><p>Formula</p></td>
<td><p>Calculation</p></td>
<td><p>----</p></td>
<td><p>Item</p></td>
</tr>
<tr class="odd">
<td><p>Formula calculation</p></td>
<td><p>----</p></td>
<td><p>Calculation</p></td>
<td><p>Formula</p></td>
<td><p>----</p></td>
</tr>
<tr class="even">
<td><p>Check Formula</p></td>
<td><p>----</p></td>
<td><p>----</p></td>
<td><p>Formula</p></td>
<td><p>----</p></td>
</tr>
<tr class="odd">
<td><p>Configuration (create/select)</p></td>
<td><p>----</p></td>
<td><p>----</p></td>
<td><p>Configurable formula</p></td>
<td><p>----</p></td>
</tr>
<tr class="even">
<td><p>Configurations included in (view)</p></td>
<td><p>----</p></td>
<td><p>----</p></td>
<td><p>Configurable formula</p></td>
<td><p>----</p></td>
</tr>
<tr class="odd">
<td><p>Configure</p></td>
<td><p>----</p></td>
<td><p>----</p></td>
<td><p>Configurable formula</p></td>
<td><p>----</p></td>
</tr>
<tr class="even">
<td><p>Copy lines within tree</p></td>
<td><p>Copy to location. Press CTRL, and drag-and-drop</p></td>
<td><p>----</p></td>
<td><p>----</p></td>
<td><p>----</p></td>
</tr>
<tr class="odd">
<td><p>Create/Edit Formula versions</p></td>
<td><p>----</p></td>
<td><p>Formula versions</p></td>
<td><p>Formula</p></td>
<td><p>----</p></td>
</tr>
<tr class="even">
<td><p>Create/Edit route versions</p></td>
<td><p>----</p></td>
<td><p>Route versions</p></td>
<td><p>Formula</p></td>
<td><p>----</p></td>
</tr>
<tr class="odd">
<td><p>Delete</p></td>
<td><p>----</p></td>
<td><p>Delete record</p></td>
<td><p>Line or formula</p></td>
<td><p>----</p></td>
</tr>
<tr class="even">
<td><p>Edit line</p></td>
<td><p>----</p></td>
<td><p>Edit</p></td>
<td><p>Line or formula</p></td>
<td><p>Line</p></td>
</tr>
<tr class="odd">
<td><p>Link to operation</p></td>
<td><p>Operation number</p></td>
<td><p>----</p></td>
<td><p>----</p></td>
<td><p>Line - insert operation number</p></td>
</tr>
<tr class="even">
<td><p>Lock/Unlock route</p></td>
<td><p>----</p></td>
<td><p>----</p></td>
<td><p>Line or formula</p></td>
<td><p>----</p></td>
</tr>
<tr class="odd">
<td><p>Move lines within tree</p></td>
<td><p>New locations</p></td>
<td><p>----</p></td>
<td><p>----</p></td>
<td><p>----</p></td>
</tr>
<tr class="even">
<td><p>Print Formula</p></td>
<td><p>----</p></td>
<td><p>Print</p></td>
<td><p>Formula</p></td>
<td><p>----</p></td>
</tr>
<tr class="odd">
<td><p>Reload Formula</p></td>
<td><p>----</p></td>
<td><p>----</p></td>
<td><p>Formula</p></td>
<td><p>----</p></td>
</tr>
<tr class="even">
<td><p>Reload route</p></td>
<td><p>----</p></td>
<td><p>----</p></td>
<td><p>Formula</p></td>
<td><p>----</p></td>
</tr>
<tr class="odd">
<td><p>Remove link to operation</p></td>
<td><p>----</p></td>
<td><p>----</p></td>
<td><p>Line or formula</p></td>
<td><p>Line - Delete operation number</p></td>
</tr>
</tbody>
</table>


## Use the Setup tab

Use the **Setup** tab to customize the information that is shown on the **Designer** form.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Field group</p></th>
<th><p>Field</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Search criteria</strong></p></td>
<td><p><strong>Display principle</strong></p></td>
<td><p>Select the version-display principle that applies to the current formula structure and the current route.</p>
<ul>
<li><p>When the principle is set to <strong>Active</strong> or <strong>Selected/Active</strong>, the valid formula or route version for this date is found.</p></li>
<li><p>The date is also used to find valid formula lines if <strong>Show valid only</strong> is selected.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>----</p></td>
<td><p><strong>Version date</strong></p></td>
<td><p>Enter the version date for the formula and route. The version is used to identify which formula version to use on a specific date, as determined by the version dates in the formula-version setup.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Lines</strong></p></td>
<td><p><strong>Show valid only</strong></p></td>
<td><p>When the check box is selected, only formula lines that have valid dates are displayed in the tree structure. To open the <strong>Edit formula line</strong> form and view the validity dates for the formula line, right-click or double-click the line.</p></td>
</tr>
<tr class="even">
<td><p><strong>Formula</strong></p></td>
<td><p>All check-box fields</p></td>
<td><p>Select the criteria to display in the tree structure. The designer displays the selected criteria at the bottom of both tabs.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Route</strong></p></td>
<td><p>All check-box fields</p></td>
<td><p>Select the criteria to display for the routes.</p></td>
</tr>
</tbody>
</table>


## See also

[Formula designer (form)](https://technet.microsoft.com/en-us/library/hh242746\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

