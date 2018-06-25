---
title: Controls Used to Render Report Parameters
TOCTitle: Controls Used to Render Report Parameters
ms:assetid: 6165449b-a0b6-42f0-aa16-55c33b12a002
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Cc591432(v=AX.60)
ms:contentKeyID: 28119365
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# Controls Used to Render Report Parameters [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

How you define a report parameter determines what a user sees when the parameter displays in the report. For more information about defining report parameters, see [How to: Define a Report Parameter](how-to-define-a-report-parameter.md).

The following table summarizes the controls used to render report parameters in a report. The **Option** column in this table refers to the option that was chosen for the **Values** property when the report parameter was defined in the model.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Option</p></th>
<th><p>Data type</p></th>
<th><p>Control rendered to the user</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>From Dataset</strong></p>
<p>- or -</p>
<p><strong>Non-queried</strong> (with available values specified)</p></td>
<td><p>All data types</p></td>
<td><p>If the <strong>Multi Value</strong> property is set to <strong>False</strong>, a drop-down list displays. If the <strong>Multi Value</strong> property is set to <strong>True</strong>, a check list displays. A check list displays a check box on the left side of each item allowing the user to select more than one item.</p></td>
</tr>
<tr class="even">
<td><p><strong>Null</strong></p>
<p>- or -</p>
<p><strong>Non-queried</strong> (with no available values specified)</p></td>
<td><p>System.Boolean</p></td>
<td><p>A check box.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Null</strong></p>
<p>- or -</p>
<p><strong>Non-queried</strong> (with no available values specified)</p></td>
<td><p>System.DateTime</p></td>
<td><p>A drop-down list that displays a calendar from which users can select a date.</p></td>
</tr>
<tr class="even">
<td><p><strong>Null</strong></p>
<p>- or -</p>
<p><strong>Non-queried</strong> (with no available values specified)</p></td>
<td><p>All data types, except System.Boolean and System.DateTime</p></td>
<td><p>A text box that only permits the user to enter a value of the specified data type.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Parameter</strong></p>
<p></p></td>
<td><p>All data types</p></td>
<td><p>References the value of another parameter. No control is displayed to the user.</p></td>
</tr>
</tbody>
</table>


When the **Nullable** property for a report parameter is set to **True**, a check box will display next to the control for the report parameter. When this check box is selected, the control for the report parameter is disabled.

## See also

[How to: Define a Report Parameter](how-to-define-a-report-parameter.md)

