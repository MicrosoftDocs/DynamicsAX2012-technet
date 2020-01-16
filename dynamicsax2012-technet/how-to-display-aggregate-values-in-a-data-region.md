---
title: 'How to: Display Aggregate Values in a Data Region'
TOCTitle: 'How to: Display Aggregate Values in a Data Region'
ms:assetid: 6600de34-dbda-4381-8413-02d55aedd6d7
ms:mtpsurl: https://technet.microsoft.com/library/Cc592216(v=AX.60)
ms:contentKeyID: 28119370
author: Khairunj
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# How to: Display Aggregate Values in a Data Region 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

There are several aggregate functions, such as Count, Sum, Min, and Max, that are used to calculate aggregate values for a data region in a report. For a complete list of functions and their descriptions, see [Aggregate Functions](aggregate-functions.md). The following table describes how aggregate values display in the various data region types.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Data region</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Table and list data regions</p></td>
<td><p>You can display grand total aggregate values in a summary section at the bottom of the list or table data region. For a grouping in a list or table data region, you can display aggregate values as subtotals in group headers or group footers.</p></td>
</tr>
<tr class="even">
<td><p>Matrix data regions</p></td>
<td><p>You can display aggregate values for row and column groupings in a matrix data region. For a row grouping, aggregate values are displayed as subtotals in a row within the matrix. For a column grouping, aggregate values are displayed as subtotals in a column within the matrix.</p></td>
</tr>
<tr class="odd">
<td><p>Chart data regions</p></td>
<td><p>For chart data regions, aggregate values display as data in a chart. For example, if you want your chart to display a breakout of the total amount of customer transactions per customer group, you can use the Sum aggregate function to calculate a single value for each customer group.</p>
<p>The data that displays the in chart can also be aggregated in the dataset query. In that case, it may not be necessary to assign an aggregate function to a field.</p></td>
</tr>
</tbody>
</table>


You can assign an aggregate function to a field within a dataset or within a report design. If a dataset is used in more than one report design and the same aggregate function is needed for each design, it is best to assign the aggregate function to the field in the dataset. If a different aggregate function is needed for the field in each of the report designs, then it is best to assign the aggregate function within the report designs. The following procedures explain how to assign an aggregate function to a field and how to display grand totals and subtotals in data regions.

### To assign an aggregate function to a field in a dataset

1.  In Model Editor, expand the node for the dataset that contains the field that you want to assign an aggregate function to.

2.  Select the field.

3.  In the **Properties** window, select an aggregate function from the drop-down menu for the **Aggregate Function** property.

### To assign an aggregate function to a field in a report design

1.  In Model Editor, expand the node for the report that you want to work with.

2.  Expand the **Designs** node for the report, and then expand the node for auto design.

3.  Expand the node for the data region, and then expand the **Data** node.

4.  Select the field that you want to add an aggregate function to.

5.  In the **Properties** window, expand the **Aggregation** node.

6.  Select an aggregate function from the drop-down menu for the **Aggregate Function** property.

### To display grand totals in list and table data regions

1.  In Model Editor, expand the node for the table or list data region, and then expand the **Data** node.

2.  Select the field for which you want to display a grand total.

3.  In the **Properties** window, expand the **Aggregation** node.

4.  Select an aggregate function for the **Aggregate Function** property, specify a caption to display using the **Grand Total Caption** property, and set the **Render Grand Total** property to **True**.

### To display subtotals for groupings in list and table data regions

1.  In Model Editor, expand the node for the table or list data region, and then expand the **Groupings** node.

2.  Select the node for the grouping.

3.  In the **Properties** window, expand the **Instance Aggregates** node.

4.  Set the **Render Location** property to **GroupFooter** or **GroupHeader** depending upon where you want the subtotal to display. For footer aggregates, specify a caption using the **Footer Aggregates Line Label** property.

### To display subtotals for row or category groupings in matrix data regions

1.  In Model Editor, expand the node for the matrix data region, and then expand the **Row Groupings** or **Column Groupings** node depending upon the grouping type.

2.  Select the node for the row or column grouping.

3.  In the **Properties** window, set the **Display Subtotals** property to **True**.

## See also

[Aggregate Functions](aggregate-functions.md)

