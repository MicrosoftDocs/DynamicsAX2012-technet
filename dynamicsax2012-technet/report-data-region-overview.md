---
title: Report Data Region Overview
TOCTitle: Report Data Region Overview
ms:assetid: 9e10aca4-354c-4834-ad0d-5ab49ffb2613
ms:mtpsurl: https://technet.microsoft.com/library/Cc615429(v=AX.60)
ms:contentKeyID: 28119554
author: tonyafehr
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# Report Data Region Overview 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A data region is an area within a report that displays data. Data can be displayed in table, list, matrix, or chart formats. Each data region is associated with a single dataset. However, a dataset can be associated with more than one data region. This topic describes each of the data regions types that you can add to a report.

## List Data Regions

List data regions display data in a basic list format. You can use a top-down list that displays the data vertically, or you can use a horizontal list that displays the data horizontally. At design time, you can easily switch between these two formats. The following illustration shows an example of data displayed in a top-down list.

![Top down list](images/Cc615429.VSReportsTopDownList(AX.60).gif "Top down list")

The following illustration shows the same data displayed in a horizontal list.

![Horizontal list](images/Cc615429.VSReportsHorizontalList(AX.60).gif "Horizontal list")

At design time, there are several options for modifying the look and feel of a list data region. For example, you can define groupings to group data. You can add interactive drill-down navigation that allows users to expand or collapse grouped data. You can define sort orders to sort data, and parameters and filters to filter data. You can modify the appearance of a list data region by modifying the settings in its layout and style templates. For example, you can modify colors, lines, and fonts.

## Table Data Regions

A table data region displays data in a table format with columns and rows. The columns in a table data region are static. That is, the number of columns in a table data region does not change at runtime. The following illustration shows data displayed in a table data region.

![Table](images/Cc615429.VSReportsTable(AX.60).gif "Table")

At design time, there are several options for modifying the look and feel of a table data region. For example, you can define groupings to group data. You can add interactive drill-down navigation that allows users to expand or collapse grouped data. You can define sort orders to sort data, and parameters and filters to filter data. You can modify the appearance of a table data region by modifying the settings in its layout and style templates. For example, you can modify colors, lines, and fonts.

## Matrix Data Regions

A matrix data region displays data in a two-dimensional grid of columns and rows that intersect at specific data points. Unlike a table, which has a static set of columns, the number of matrix columns can dynamically increase to accommodate the data that is returned. When defining a matrix data region, you can specify column and row groupings. The data that appears in the detail cells are aggregates based on the intersections of columns and rows. The following illustration shows a matrix data region with two row groupings, customer category and account, and one column grouping for the date.

![Matrix](images/Cc615429.VSReportsMatrix(AX.60).gif "Matrix")

You can add interactive drill-down navigation features to enable users to view and analyze aggregated data at different levels of detail. In addition, you can define parameters and filters to filter data. You can modify the appearance of a matrix data region by modifying the settings in its layout and style templates. For example, you can modify colors, lines, and fonts.

## Chart Data Regions

A chart data region allows you to display a graphical representation of your data. Displaying data in a chart makes it easy for users to see comparisons, patterns, and trends in the data. You can create column, bar, line, pie, and doughnut charts.

You control the appearance of a chart. For example, when creating a chart, you can choose whether to display the chart in your report as a two or three-dimensional chart. In addition, you can modify the appearance of a chart by modifying the settings in its layout and style templates. For example, you can modify colors, lines, and fonts.

### Column, Bar, and Line Charts (XY Charts)

Column, bar, and line charts are commonly referred to as *XY charts*. At design time, you can switch between related chart types. For example, you can create a column chart and then later change it to a bar or line chart. When defining a column, bar, or line chart in a model, you must identify the data that displays in the chart as well as categories and series. The following table provides a description of these concepts.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Chart area</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Category</p></td>
<td><p>Categories are used to group data within a chart. For example, you can create a chart to display sales by customer group. In this case, the customer group would be a category. A chart must have at least one category.</p>
<p>Categories provide the labels for chart elements. In column and line charts, category labels are placed on the horizontal axis. In a bar chart, category labels are placed on the vertical axis. One label displays for each category.</p>
<p>When you define multiple categories, a category is nested within another category. For example, in a column chart that displays products by model, the first category would be model, and the second category would be product. The column chart would then display groupings of products by model on the horizontal axis.</p></td>
</tr>
<tr class="even">
<td><p>Data</p></td>
<td><p>The data fields represent the data that displays in the chart. You can specify more than one data field. However, the data types for the data fields must match since the values are all plotted using the same vertical axis. For example, you cannot have a data field that is formatted as currency plotted with a data field that is formatted as a percentage. These data fields each require a different vertical axis. When you design a chart data region, you must have at least one data field.</p>
<p>The values of the data fields determine the labels for chart elements. In a column and line chart, labels are placed on the vertical axis. In a bar chart, the labels are placed on the horizontal axis.</p></td>
</tr>
<tr class="odd">
<td><p>Series</p></td>
<td><p>A series is used to add an additional dimension to the data in your report. For example, in a chart that displays sales by customer group, you can define a series in order to display the sales by year for each customer category. You are not required to define a series; it is optional when designing a column, bar, or line chart.</p></td>
</tr>
</tbody>
</table>


A column chart displays data as sets of vertical columns. The following example shows a two-dimensional column chart, with one category based on the customer group and one series based on the year. The data that displays is the total amount of transactions.

![Column chart](images/Cc615429.VSReportsChartCategoryAndSeries(AX.60).gif "Column chart")

A bar chart displays data as sets of horizontal bars. The following illustration shows a bar chart with the same data as the previous example.

![Bar chart](images/Cc615429.VSReportsBarChart(AX.60).gif "Bar chart")

A line chart displays a set of points connected by a line. The following illustration shows a line chart that displays customer transaction data over a period of time. In this chart, gridlines are displayed along with the data.

![Line chart](images/Cc615429.VSReportsLineChart(AX.60).gif "Line chart")

### Pie and Doughnut Charts

Pie and doughnut charts display data as percentages of the whole. When defining pie and doughnut charts, you must specify the data that displays in the chart as well as one or more series. The following table provides a description of these concepts.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Chart area</p></th>
<th><p>Definition</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Series</p></td>
<td><p>A series identifies the slices that appear in a pie or doughnut chart.</p></td>
</tr>
<tr class="even">
<td><p>Data</p></td>
<td><p>A data field represents the data that displays in a pie or doughnut chart. The size of a slice in the chart is determined by this value.</p></td>
</tr>
</tbody>
</table>


There are several ways to display a pie or doughnut chart. You can display it in standard format or in exploded format. When a pie or doughnut chart displays in exploded format, the slices are moved away from the center. This results in spaces between the slices. The following illustration shows an example of an exploded pie chart.

![Exploded pie chart](images/Cc615429.VSReportsExplodedPieChart(AX.60).gif "Exploded pie chart")

At design time, you can switch between pie and doughnut chart types. You can also switch between a two-dimensional and three-dimensional display of the chart. The following illustration shows the same data displayed in a three-dimensional doughnut chart.

![Three dimensional doughnut chart](images/Cc615429.VSReports3DDoughnutChart(AX.60).gif "Three dimensional doughnut chart")


> [!NOTE]
> <P>If you have a non-numeric field in the data category, the preview will display an empty report.</P>



## See also

[How to: Add a Data Region to a Report](how-to-add-a-data-region-to-a-report.md)

[How to: Add or Delete Fields in a Data Region](how-to-add-or-delete-fields-in-a-data-region.md)

[How to: Define a Sorted Data Region](how-to-define-a-sorted-data-region.md)

[How to: Define Groupings in a Data Region](how-to-define-groupings-in-a-data-region.md)

[How to: Display Aggregate Values in a Data Region](how-to-display-aggregate-values-in-a-data-region.md)

