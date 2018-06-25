---
title: About BOM designer functionality
TOCTitle: About BOM designer functionality
ms:assetid: d0ec2f9b-052e-472b-b9b4-c2cac8ac4187
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa551020(v=AX.60)
ms:contentKeyID: 36059492
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# About BOM designer functionality [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Designer** form to design and work with bill-of-material (BOM) tree structures. The designer graphically displays the BOM structure. You can select different configurations and decide what information you want to display on the lines of the tree.


> [!NOTE]
> <P>If you access the designer from the BOM, it does not display route information, because the BOM is not yet linked to a specific, finished item.</P>



The following sections provide descriptions of functionality in the tabs of this form.

## Use the Designer tab

The **Designer** tab contains the following functionality:

  - A functions pane on the left part of the form that enables you to perform tasks such as editing a BOM version and adding BOM items

  - A designer window that displays the BOM's tree structure

  - Current route information for the BOM

  - An item list

The following table shows the actions you can perform for each function in the icon pane.

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
<td><p>Line or BOM</p></td>
<td><p>----</p></td>
</tr>
<tr class="even">
<td><p>Add item</p></td>
<td><p>BOM</p></td>
<td><p>Calculation</p></td>
<td><p>----</p></td>
<td><p>Item</p></td>
</tr>
<tr class="odd">
<td><p>BOM calculation</p></td>
<td><p>----</p></td>
<td><p>Calculation</p></td>
<td><p>BOM</p></td>
<td><p>----</p></td>
</tr>
<tr class="even">
<td><p>Check BOM</p></td>
<td><p>----</p></td>
<td><p>----</p></td>
<td><p>BOM</p></td>
<td><p>----</p></td>
</tr>
<tr class="odd">
<td><p>Configuration (create/select)</p></td>
<td><p>----</p></td>
<td><p>----</p></td>
<td><p>Configurable BOM</p></td>
<td><p>----</p></td>
</tr>
<tr class="even">
<td><p>Configurations included in (view)</p></td>
<td><p>----</p></td>
<td><p>----</p></td>
<td><p>Configurable BOM</p></td>
<td><p>----</p></td>
</tr>
<tr class="odd">
<td><p>Configure</p></td>
<td><p>----</p></td>
<td><p>----</p></td>
<td><p>Configurable BOM</p></td>
<td><p>----</p></td>
</tr>
<tr class="even">
<td><p>Copy lines within tree</p></td>
<td><p>Copy to location (Press CTRL, and drag-and-drop)</p></td>
<td><p>----</p></td>
<td><p>----</p></td>
<td><p>----</p></td>
</tr>
<tr class="odd">
<td><p>Create/Edit BOM versions</p></td>
<td><p>----</p></td>
<td><p>BOM versions</p></td>
<td><p>BOM</p></td>
<td><p>----</p></td>
</tr>
<tr class="even">
<td><p>Create/Edit route versions</p></td>
<td><p>----</p></td>
<td><p>Route versions</p></td>
<td><p>BOM</p></td>
<td><p>----</p></td>
</tr>
<tr class="odd">
<td><p>Delete</p></td>
<td><p>----</p></td>
<td><p>Delete record</p></td>
<td><p>Line or BOM</p></td>
<td><p>----</p></td>
</tr>
<tr class="even">
<td><p>Edit line</p></td>
<td><p>----</p></td>
<td><p>Edit</p></td>
<td><p>Line or BOM</p></td>
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
<td><p>Line or BOM</p></td>
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
<td><p>Print BOM</p></td>
<td><p>----</p></td>
<td><p>Print</p></td>
<td><p>BOM</p></td>
<td><p>----</p></td>
</tr>
<tr class="odd">
<td><p>Reload BOM</p></td>
<td><p>----</p></td>
<td><p>----</p></td>
<td><p>BOM</p></td>
<td><p>----</p></td>
</tr>
<tr class="even">
<td><p>Reload route</p></td>
<td><p>----</p></td>
<td><p>----</p></td>
<td><p>BOM</p></td>
<td><p>----</p></td>
</tr>
<tr class="odd">
<td><p>Remove link to operation</p></td>
<td><p>----</p></td>
<td><p>----</p></td>
<td><p>Line or BOM</p></td>
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
<td><p>Select the version-display principle that applies to the current BOM structure and the current route.</p>
<ul>
<li><p>When the principle is set to <strong>Active</strong> or <strong>Selected/Active</strong>, the valid BOM or route version for this date is found.</p></li>
<li><p>The date is also used to find valid BOM lines if <strong>Show valid only</strong> is selected.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>----</p></td>
<td><p><strong>Version date</strong></p></td>
<td><p>Enter the version date for the BOM and route. The version is used to identify which BOM version to use on a specific date, as determined by the version dates in the BOM-version setup.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Lines</strong></p></td>
<td><p><strong>Show valid only</strong></p></td>
<td><p>When the check box is selected, only BOM lines that have valid dates are displayed in the tree structure. You can right-click or double-click the line to open the <strong>Edit BOM line</strong> form and see the validity dates for the BOM line.</p></td>
</tr>
<tr class="even">
<td><p><strong>BOM</strong></p></td>
<td><p>All check-box fields</p></td>
<td><p>Select the criteria that you want to display in the tree structure. The designer displays the selected criteria at the bottom of both tabs.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Route</strong></p></td>
<td><p>All check-box fields</p></td>
<td><p>Select the criteria that you want to display for the routes.</p></td>
</tr>
</tbody>
</table>


## See also

[BOM designer (form)](https://technet.microsoft.com/en-us/library/aa583042\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

