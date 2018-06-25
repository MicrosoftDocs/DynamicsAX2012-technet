---
title: 'How to: Add or Delete Fields in a Data Region'
TOCTitle: 'How to: Add or Delete Fields in a Data Region'
ms:assetid: 5b2479fd-23ca-40e4-9c7a-56bc6c345f00
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Cc598701(v=AX.60)
ms:contentKeyID: 28119362
ms.date: 11/07/2012
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Framework.Design.Model.Reports.ChartDataDefinition
- Microsoft.Dynamics.Framework.Design.Model.Reports.ListFieldDataDefinition
- Microsoft.Dynamics.Framework.Design.Model.Reports.ListFieldGroupDefinition
- Microsoft.Dynamics.Framework.Design.Model.Reports.MatrixDataDefinition
- Microsoft.Dynamics.Framework.Design.Model.Reports.TableDetailDataDefinition
---

# How to: Add or Delete Fields in a Data Region [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can add or delete fields for a data region in an auto design report. Each data region has a single underlying dataset. If you add a field to a data region, the field must be from the same dataset as the other fields in the data region. The following procedure explains how to add or delete fields in a data region within an auto design.

### To add a field to a data region within an auto design

1.  In Model Editor, expand the node for the data region that you want to add a field to.

2.  To add a field, do one of the following:
    
      - Drag the field from the dataset, which is located under the **Datasets** node, onto the **Data** node for the data region.
    
    \- or -
    
    1.  Right-click the **Data** node for the data region, point to **Add**, and then click **Field**.
    
    2.  Select the node for the field.
    
    3.  In the **Properties** window, specify the following properties.
        
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
        <td><p><strong>Expression</strong></p></td>
        <td><p>An expression that identifies the data to be displayed. From the drop-down list, select an expression that identifies the field you want to display or click <strong>&lt;Expression…&gt;</strong> to display the <strong>Edit Expression</strong> dialog box where you can create an expression. For information about creating expressions, see <a href="http://go.microsoft.com/fwlink/?linkid=106936">Expression Examples in Reporting Services</a>.</p></td>
        </tr>
        <tr class="even">
        <td><p><strong>Name</strong></p></td>
        <td><p>The name of the field.</p></td>
        </tr>
        </tbody>
        </table>
    
    A data region displays fields from only one dataset. To identify the dataset that is assigned to a data region, select the data region in Model Editor and view the **DataSet** property in the **Properties** window.

### To delete a field for a data region within an auto design

1.  In Model Editor, expand the node for the data region that contains the field you want to delete.

2.  Expand the **Data** node.

3.  Right-click the field you want to delete, and then click **Delete**.
    
    When you delete a field in a data region, it is deleted from the selected data region only. It is not deleted from the dataset or any other data regions that display the field.

## See also

[How to: Define Groupings in a Data Region](how-to-define-groupings-in-a-data-region.md)

