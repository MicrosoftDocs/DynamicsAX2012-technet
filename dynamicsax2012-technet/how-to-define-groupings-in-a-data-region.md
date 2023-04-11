---
title: 'How to: Define Groupings in a Data Region'
TOCTitle: 'How to: Define Groupings in a Data Region'
ms:assetid: abd03155-dd57-4b20-8c6c-0ca7449493e1
ms:mtpsurl: https://technet.microsoft.com/library/Cc635503(v=AX.60)
ms:contentKeyID: 28119558
author: tonyafehr
ms.date: 11/07/2012
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Framework.Design.Model.Reports.ChartGroupingDefinition
- Microsoft.Dynamics.Framework.Design.Model.Reports.ListGroupingDefinition
- Microsoft.Dynamics.Framework.Design.Model.Reports.MatrixColumnGroupingDefinition
- Microsoft.Dynamics.Framework.Design.Model.Reports.MatrixRowGroupingDefinition
- Microsoft.Dynamics.Framework.Design.Model.Reports.TableGroupingDefinition
---

# How to: Define Groupings in a Data Region 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can group fields to organize related information within a report data region. For example, you can create a grouping that groups data for salespersons according to the regions to which they are assigned or by the type of accounts that they handle. Groupings can be added to table, list, matrix, and chart data regions. For matrix data regions, the groupings are divided into column groupings and row groupings. For chart data regions, the groupings are divided into categories and series.

You can group fields at the dataset level so that groupings within a data region are automatically generated whenever the dataset is used in an auto design. You can also manually create groupings for a data region directly in an auto design. The following procedures describe how to define groupings for a data region.

### To define groupings within a dataset

1.  In Model Editor, expand the node for the report that you want to work with.

2.  Expand the **Datasets** node, and then expand the node for the dataset that contains the fields for which you want to define a grouping.

3.  Select a field to group by, and in the **Properties** window, do one of the following.
    
      - If the **Default Layout** property for the dataset is set to **Table**, **TopDownList**, or **HorizontalList**, set the **Field Type** property to **Grouping**.
    
      - If the **Default Layout** property for the dataset is set to **Matrix**, set the **Field Type** property to **Grouping**. Set the **Grouping Type** property to **Category** for a row grouping or to **Series** for a column grouping.
    
      - If the **Default Layout** property for the dataset is set to **ColumnChart**, **BarChart**, **LineChart**, **PieChart**, or **DoughnutChart**, set the **Field Type** property to **Grouping**. Set the **Grouping Type** to **Series** for a series or to **Category** for a category.

4.  Repeat the previous step for each field that you want to group by.
    
    When you use the dataset in a new or existing auto design, the groupings that you defined for the dataset will automatically appear for the data region in the design. To see this, drag the dataset onto the **Designs** node for the report, or drag it onto a node for an existing auto design.

### To define groupings within a report design

1.  In Model Editor, expand the node for the report that you want to work with.

2.  Expand the **Designs** node for the report.

3.  Locate the auto design that you want to modify, and then expand the node for the auto design to view its data regions.

4.  Locate the data region that contains the fields that you want to group by, and then expand the node for the data region.

5.  Expand the **Data** node to display the fields for the data region.

6.  To create a grouping, do one of the following.
    
      - For a list or table data region, drag the field that you want to group by from the **Data** node onto the **Groupings** node.
    
      - For a matrix data region, drag the field that you want to group by from the **Data** node onto the **Column Groupings** or **Row Groupings** node, depending upon whether it is a column or a row.
    
      - For a chart data region, drag the field that you want to group by from the **Data** node onto the **Categories** or **Series** node, depending upon whether it is a category or a series.
    

    > [!NOTE]
    > <P>You can also drag fields directly from a dataset that is located below the <STRONG>Datasets</STRONG> node onto the various grouping nodes for a data region in a report design. Each data region displays data from a single dataset. So, if you drag fields directly from a dataset, you must be sure to use the dataset that is assigned to the data region.</P>



7.  Repeat the previous step for each field that you want to group by.
    
    For more information about groupings and the layout of data regions, see [Report Data Region Overview](report-data-region-overview.md). After a grouping is defined, you can [add a drill down action](how-to-add-drill-down-and-drill-up-actions.md) or [display a document map](how-to-display-a-document-map.md) in the report based on the grouping.

## See also

[Report Data Region Overview](report-data-region-overview.md)

