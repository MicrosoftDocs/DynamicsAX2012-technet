---
title: 'How to: Define a Sorted Data Region'
TOCTitle: 'How to: Define a Sorted Data Region'
ms:assetid: 5922c178-4c94-4dda-a3a1-f4a7e41e177e
ms:mtpsurl: https://technet.microsoft.com/library/Cc554426(v=AX.60)
ms:contentKeyID: 28119361
author: Khairunj
ms.date: 11/07/2012
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Framework.Design.Model.Reports.SortDefinition
---

# How to: Define a Sorted Data Region 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can control the order in which data appears within a report data region by defining a sort order. A specific sort order is set when the report is built. For example, you might want to display customer data alphabetically by last name or numerically by account number.

Defining a static sort order is different from interactive sorting where the sort order can be changed at runtime. Using interactive sorting, you can sort by column A and then later by column B. For more information on interactive sorting, see [How to: Define Interactive Sort on Fields in a Data Region](how-to-define-interactive-sort-on-fields-in-a-data-region.md).

The following procedure explains how to set the static sort for data in a data region.

### To sort data in a data region

1.  In Model Editor, expand the node for the report that you want to work with.

2.  Expand the **Designs** node for the report.

3.  Locate the node for the auto design that you want to modify, and then expand the node for the design.

4.  Expand the node for the data region that contains the data that you want to sort.

5.  To define a sort order, do one of the following:
    
      - To define a sort order outside a grouping, right-click the **Sorting** node, and then click **Add Sort**.
    
      - To define a sort order within a grouping (grouping, row grouping, column grouping, category or series) expand the node for the grouping, right-click the **Sorting** node, and then click **Add Sort**.
    
    In either case, a node for the sort order displays in Model Editor.

6.  Select the node for the sort order.

7.  In the **Properties** window, specify values for the following properties.
    
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
    <td><p><strong>Name</strong></p></td>
    <td><p>A name for the sort order.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Sort By</strong></p></td>
    <td><p>An expression that is used to identify the data that is to be sorted. You can select an item from the drop-down list or click <strong>&lt;Expression…&gt;</strong> to display the <strong>Edit Expression</strong> dialog box where you can create an expression. For information about creating expressions, see <a href="http://go.microsoft.com/fwlink/?linkid=106936">Expression Examples in Reporting Services</a>.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Sort Order</strong></p></td>
    <td><p>The order in which to sort the data. You can sort in <strong>Ascending</strong> or <strong>Descending</strong> order.</p></td>
    </tr>
    </tbody>
    </table>


8.  To preview the layout of the report, right-click the node for the design, and then click **Preview**.
    
    The **Preview** window has two tabs: a **Parameters** tab and a **Report** tab. The **Parameters** tab lists the parameters that have been defined for the report. If the **Dynamics Filters** property on the dataset is set to True, you can filter on any fields in the underlying tables that the query is based on. For more information about parameters, see [How to: Define a Report Parameter](how-to-define-a-report-parameter.md). The **Report** tab displays the report. Any errors that are encountered are displayed in the **Error List** window.

## See also

[How to: Define Groupings in a Data Region](how-to-define-groupings-in-a-data-region.md)

[Expressions Example in Reporting Services](http://go.microsoft.com/fwlink/?linkid=106936)

