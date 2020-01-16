---
title: 'How to: Specify a Chart Axis Start Value'
TOCTitle: 'How to: Specify a Chart Axis Start Value'
ms:assetid: 0075267a-5e53-420b-b04d-9677709fb005
ms:mtpsurl: https://technet.microsoft.com/library/Gg731891(v=AX.60)
ms:contentKeyID: 35132807
author: Khairunj
ms.date: 05/01/2014
mtps_version: v=AX.60
---

# How to: Specify a Chart Axis Start Value 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic provides the steps to specify the chart axis start value in a column chart report. Column chart types have two axes that are used to categorize and display data relationships called the **Value Axis** and the **Category Axis**. The axes are shown in the following illustration. You can format axes by using the Properties window to change values for the axis title, interval, minimum, and maximum chart axis value.

![ColumnChart with Value and Category Labeled](images/Gg731891.ChartColumn(AX.60).png "ColumnChart with Value and Category Labeled")

For the complete steps to create a column chart report, see [Walkthrough: Using AX Enum Provider in a Column Chart Report](walkthrough-using-ax-enum-provider-in-a-column-chart-report.md).

## Setting a chart axis start value

### To set a chart axis start value

1.  From AOT or Application Explorer, open a [report for edit](how-to-access-a-report-for-edit.md) for which you want to set the chart axis start value. The axis value applies to auto design reports created from a dataset where the **Default Layout** in the Properties window is set to **ColumnChart**, **BarChart**, or **LineChart**.

2.  In Model Editor, expand the auto design, and then select the XYChart data region.

3.  In the Properties window, set the **Category Axis Data Scale Minimum** property or the **Value Axis Data Scale Minimum** property to specify the chart axis start value.

4.  Click **Preview** to preview the report.

The following table describes the properties related to axes.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Property</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Category Axis Data Scale Maximum</strong></p></td>
<td><p>The maximum value that should be used for the category axis data scale.</p></td>
</tr>
<tr class="even">
<td><p><strong>Category Axis Data Scale Minimum</strong></p></td>
<td><p>The minimum value that should be used for the category axis data scale.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Category Axis Interval</strong></p></td>
<td><p>The interval between gridlines, tick marks, and labels. When set to 0, the axis interval will default based on the report data.</p></td>
</tr>
<tr class="even">
<td><p><strong>Category Axis Title</strong></p></td>
<td><p>The title of the category axis.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Value Axis Data Scale Maximum</strong></p></td>
<td><p>The maximum value that should be used for the value axis data scale.</p></td>
</tr>
<tr class="even">
<td><p><strong>Value Axis Data Scale Minimum</strong></p></td>
<td><p>The minimum value that should be used for the value axis data scale.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Value Axis Interval</strong></p></td>
<td><p>The interval between gridlines, tick marks, and labels. When set to 0, the axis interval will default based on the report data.</p></td>
</tr>
<tr class="even">
<td><p><strong>Value Axis Title</strong></p></td>
<td><p>The title of the value axis.</p></td>
</tr>
</tbody>
</table>


## See also

[Adding Interactive Features to Reports](adding-interactive-features-to-reports.md)

[Working with Data Regions](working-with-data-regions.md)

  


