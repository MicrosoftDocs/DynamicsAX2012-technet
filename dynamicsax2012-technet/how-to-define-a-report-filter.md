---
title: 'How to: Define a Report Filter'
TOCTitle: 'How to: Define a Report Filter'
ms:assetid: e591253b-3f0c-4391-b4fc-e434eb302be6
ms:mtpsurl: https://technet.microsoft.com/library/Cc640621(v=AX.60)
ms:contentKeyID: 28119605
author: tonyafehr
ms.date: 10/12/2013
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Framework.Design.Model.Reports.FilterDefinition
---

# How to: Define a Report Filter 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to define set ranges to filter data on a report. Filters are used to filter or restrict the data that is displayed in a report.

The **Dynamics Filter** property on the dataset determines how filters are created for a report. If the **Dynamics Filters** property on the dataset is set to **True**, the end user of the report will identify the ranges when they view the report. For more information, see [How to: Define a Report with Dynamic Filters](how-to-define-a-report-with-dynamic-filters.md). To manually define the set ranges to filter data on a report, verify the **Dynamics Filters** property on the dataset is set to **False** and follow these steps.

### To define a filter for a data region

1.  In Model Editor, expand the node for the report that you want to work with.

2.  Expand the **Designs** node for the report.

3.  Locate the auto design that you want to modify, and then expand the node for the auto design to view its data regions.

4.  Locate the data region for which you want to define a filter, and then expand the node for the data region.

5.  Right-click the **Filters** node, and then click **Add Filter**.

6.  Select the node for the filter.

7.  The following table shows the properties for a filter in the **Properties** window. Specify the following properties.
    
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
    <td><p>An expression for the filter. From the drop-down list, choose a field for the filter to create a simple expression. You can also choose <strong>&lt;Expression…&gt;</strong> to open the <strong>Edit Expression</strong> dialog box to create a more complex expression. For information about how to create expressions, see <a href="https://go.microsoft.com/fwlink/?linkid=106936">Expression Examples in Reporting Services</a>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Name</strong></p></td>
    <td><p>The name of the filter.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Operator</strong></p></td>
    <td><p>An operator for the filter expression.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Value</strong></p></td>
    <td><p>A value for the expression. You can type a value or use the drop-down list. From the drop-down list, choose <strong>&lt;Expression…&gt;</strong> to open the <strong>Edit Expression</strong> dialog box where you can create a complex expression.</p>
    <div class="alert">

    > [!NOTE]
    > <P>If you type the character "10" for the <STRONG>Value</STRONG> property, by default, this evaluates to the string "10". To compare a numeric expression with the number 10, use the expression syntax which starts with an equal sign: =10. If a filter expression contains a data type mismatch, you will see a runtime error when you are previewing the report.</P>


    </div></td>
    </tr>
    </tbody>
    </table>


8.  To preview the layout of the report, right-click the node for the design, and then click **Preview**.
    

    > [!NOTE]
    > <P>You can use a parameter in a filter. To do this, you must first define the parameter within the <STRONG>Parameters</STRONG> node for the report. For more information, see <A href="how-to-define-a-report-parameter.md">How to: Define a Report Parameter</A>. Once you have defined a parameter, you can use it when you define the filter expression. Parameters appear in the drop-down list for the <STRONG>Value</STRONG> and <STRONG>Expression</STRONG> properties.</P>



## See also

[How to: Define a Report Parameter](how-to-define-a-report-parameter.md)

[Controls Used to Render Report Parameters](controls-used-to-render-report-parameters.md)

[Walkthrough: Creating a Report with Parameters](walkthrough-creating-a-report-with-parameters.md)

