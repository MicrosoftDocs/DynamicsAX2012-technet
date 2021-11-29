---
title: 'How to: Create an Auto Design for a Report'
TOCTitle: 'How to: Create an Auto Design for a Report'
ms:assetid: f72b49db-e2ec-47e0-b5d5-27e307c1fecc
ms:mtpsurl: https://technet.microsoft.com/library/Cc624233(v=AX.60)
ms:contentKeyID: 28119620
author: Khairunj
ms.date: 11/07/2012
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Framework.Design.Model.Reports.AutoDesignDefinition
---

# How to: Create an Auto Design for a Report 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

An auto design is a report design that has a layout that is automatically generated based on the data for the report. You can use auto designs for most common reports. The following procedure explains how to create an auto design.

### To create an auto design for a report

1.  In Model Editor, expand the node for the report that you want to work with. If the report does not already exist in the model, you will need to add a report. For more information, see [How to: Add or Delete a Report](how-to-add-or-delete-a-report.md).

2.  Add datasets to the report as necessary. A report must have at least one dataset. For more information, see [How to: Define a Report Dataset](how-to-define-a-report-dataset.md).

3.  To create an auto design, do one of the following.
    
      - Drag the dataset that contains the data that you want to display in the report onto the **Designs** node.
    
    \- or -
    
    1.  Right-click the **Designs** node for the report, point to **Add**, and then click **Auto Design**.
    
    2.  Right-click the node for the design, point to **Add**, and then click the data region type that you want to add. For information about the types of data regions that can be displayed in a report, see [Report Data Region Overview](report-data-region-overview.md).
    
    3.  Select the node for the data region.
    
    4.  In the **Properties** window, specify a dataset for the **DataSet** property.
    
    5.  Use the following description of auto design properties to provide additional detail for the auto design of the report:
        
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
        <td><p>Disable Individual Transformations</p></td>
        <td><p>Specifies which transformations to enable by setting the property value to <strong>True</strong> or <strong>False</strong>.</p></td>
        </tr>
        <tr class="even">
        <td><p>Disable Runtime Transformation</p></td>
        <td><p>Specifies whether to enable transformations at runtime by setting the property value to <strong>True</strong> or <strong>False</strong>.</p></td>
        </tr>
        <tr class="odd">
        <td><p>InteractiveSize</p></td>
        <td><p>Specifies the interactive height and width of the report. Interactive size is used by the HTML rendering extension to establish the occurrence of page breaks based on a physical measurement.</p></td>
        </tr>
        <tr class="even">
        <td><p>LayoutTemplate</p></td>
        <td><p>Specifies the general and style settings for a report.</p></td>
        </tr>
        <tr class="odd">
        <td><p>Margins</p></td>
        <td><p>Specifies the report margins.</p>
        <p>When you set these properties to <strong>Auto</strong>, the default values stored in the UserInfo system table are used.</p></td>
        </tr>
        <tr class="even">
        <td><p>Name</p></td>
        <td><p>Specifies the name of the auto design.</p></td>
        </tr>
        <tr class="odd">
        <td><p>Page Size</p></td>
        <td><p>Specifies the report page size.</p></td>
        </tr>
        <tr class="even">
        <td><p>Render Parameters</p></td>
        <td><p>Set to <strong>True</strong> to debug report parameters; otherwise <strong>False</strong>.</p></td>
        </tr>
        <tr class="odd">
        <td><p>Size To Fit Strategy</p></td>
        <td><p>Specifies properties to control the fit of the report on a page regarding indentation and the flow layout.</p></td>
        </tr>
        <tr class="even">
        <td><p>Title</p></td>
        <td><p>Specifies the title of the report design.</p></td>
        </tr>
        </tbody>
        </table>


4.  Apply report layout and style templates to the auto design report. For more information, see [How to: Apply a Layout or Style Template](how-to-apply-a-layout-or-style-template.md).

5.  To preview the layout of the report, right-click the node for the design, and then click **Preview**.
    
    The **Preview** window has two tabs: a **Parameters** tab and a **Report** tab. The **Parameters** tab lists the parameters that have been defined for the report. If the **Dynamics Filters** property on the dataset is set to True, you can filter on any fields in the underlying tables that the query is based on. For more information about parameters, see [How to: Define a Report Parameter](how-to-define-a-report-parameter.md). The **Report** tab displays the report. Any errors that are encountered are displayed in the **Error List** window.

## See also

[Creating Reports Overview](creating-reports-overview.md)

[How to: Create a Precision Design for a Report](how-to-create-a-precision-design-for-a-report.md)

