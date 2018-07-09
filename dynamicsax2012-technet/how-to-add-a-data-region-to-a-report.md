---
title: 'How to: Add a Data Region to a Report'
TOCTitle: 'How to: Add a Data Region to a Report'
ms:assetid: 1f78ad21-1c42-44c8-8289-18c0a007cb4a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Cc584561(v=AX.60)
ms:contentKeyID: 28119318
ms.date: 11/07/2012
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Framework.Design.Model.Reports.ListDefinition
- Microsoft.Dynamics.Framework.Design.Model.Reports.MatrixDefinition
- Microsoft.Dynamics.Framework.Design.Model.Reports.PieDoughnutChartDefinition
- Microsoft.Dynamics.Framework.Design.Model.Reports.TableDefinition
- Microsoft.Dynamics.Framework.Design.Model.Reports.XYChartDefinition
---

# How to: Add a Data Region to a Report [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A data region is a section within a report that displays data from a dataset. There are several ways to add a data region to an auto design report. You can add a data region simply by dragging a dataset onto a report design. Or, you can add a data region manually. The following procedures explain how to add a data region to an auto design report.


> [!NOTE]
> <P>Before adding a data region to a report, be sure that you have defined a dataset that contains the data that you want to display within the data region. For more information, see <A href="how-to-define-a-report-dataset.md">How to: Define a Report Dataset</A>.</P>



### To add a data region using drag-and-drop

1.  In Model Editor, expand the node for the report that you want to work with.

2.  Expand the **Datasets** node.

3.  Select the dataset that contains the data that you want to display.

4.  In the **Properties** window, specify a value for the **Default Layout** property if you have not done so already.
    
    The **Default Layout** property determines how the data is displayed in a data region in an auto design. For example, you can specify **TopDownList** to indicate that the data should be displayed in a vertical list. For more information about available options, see [Report Data Region Overview](report-data-region-overview.md).

5.  In Model Editor, do one of the following:
    
      - To create a new auto design, drag the dataset onto the **Designs** node for the report.
    
      - To add the data region to an existing auto design, drag the dataset onto the node for the auto design.
    
    In both cases, a node for the data region displays below the design node.

6.  Select the node for the data region.

7.  In the **Properties** window, specify a style template for the data region using the **Style Template** property. For more information, see [How to: Apply a Layout or Style Template](how-to-apply-a-layout-or-style-template.md).
    

    > [!NOTE]
    > <P>If you are defining a matrix data region, be sure to define row and column groupings as necessary. If you are defining a chart data region, be sure to define the categories and series as necessary. For more information about the data region types, see <A href="report-data-region-overview.md">Report Data Region Overview</A>.</P>



8.  To preview the layout of the report, right-click the node for the design, and then click **Preview**.
    
    The **Preview** window has two tabs: a **Parameters** tab and a **Report** tab. The **Parameters** tab lists the parameters that have been defined for the report. If the **Dynamics Filters** property on the dataset is set to True, you can filter on any fields in the underlying tables that the query is based on. For more information about parameters, see [How to: Define a Report Parameter](how-to-define-a-report-parameter.md). The **Report** tab displays the report. Any errors that are encountered are displayed in the **Error List** window.

### To manually add a data region

1.  In Model Editor, expand the node for the report that you want to work with, and then expand the **Designs** node.

2.  Right-click the auto design that you want to add a data region to, point to **Add**, and then select a data region type. Choose from: **List**, **Matrix**, **Pie or Doughnut Chart**, **Table**, or **XY Chart**. For more information, see [Report Data Region Overview](report-data-region-overview.md).

3.  Select the node for the data region.

4.  In the **Properties** window, specify a dataset for the data region using the **DataSet** property, and specify a style template for the data region using the **Style Template** property.

5.  To preview the layout of the report, right-click the node for the design, and then click **Preview**.
    
    The **Preview** window has two tabs: a **Parameters** tab and a **Report** tab. The **Parameters** tab lists the parameters that have been defined for the report. If the **Dynamics Filters** property on the dataset is set to True, you can filter on any fields in the underlying tables that the query is based on. For more information about parameters, see [How to: Define a Report Parameter](how-to-define-a-report-parameter.md). The **Report** tab displays the report. Any errors that are encountered are displayed in the **Error List** window.

## See also

[Report Data Overview](report-data-overview.md)

[How to: Create an Auto Design for a Report](how-to-create-an-auto-design-for-a-report.md)

[How to: Define a Sorted Data Region](how-to-define-a-sorted-data-region.md)

[How to: Define Groupings in a Data Region](how-to-define-groupings-in-a-data-region.md)

[How to: Display Aggregate Values in a Data Region](how-to-display-aggregate-values-in-a-data-region.md)

