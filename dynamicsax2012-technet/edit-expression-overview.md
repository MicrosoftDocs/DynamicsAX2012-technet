---
title: Edit Expression Overview
TOCTitle: Edit Expression Overview
ms:assetid: 2d8ca49d-319b-4efa-b63b-ec8e69c062d8
ms:mtpsurl: https://technet.microsoft.com/library/Cc551700(v=AX.60)
ms:contentKeyID: 28119328
author: Khairunj
ms.date: 11/07/2012
mtps_version: v=AX.60
f1_keywords:
- DynamicsReportExpressionEditorHelp
---

# Edit Expression Overview 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You use expressions throughout a report definition to control content and format the data in a report. You can use the Edit Expression window to write and edit expressions for an auto design report in Model Editor. Expressions are written using Visual Basic.

When you define a precision design report in SQL Report Designer, you can use the Expression dialog box for Report Designer to write and edit expressions. The Edit Expression window is an extension of the Expression dialog box. This topic describes the Edit Expression window. For information about the Expression dialog box, see [Expression dialog box](https://go.microsoft.com/fwlink/?linkid=233067).

You can also change the expression text in the Property window. Use the Property window when you know the expression to type. Use the Edit Expression window when you need to build an expression by adding items from a list.

The Edit Expression window includes a code editor and a list of items that you can use in an expression. The code editor supports IntelliSense, statement completions, and syntax coloring so that you can easily detect syntax errors. The Edit Expression window is context-sensitive, so category items change depending on the report item that you are working with. For example, when you select the **Datasets** item, the list of datasets available for the report displays in the Edit Expression window. The Edit Expression window includes additional categories of items specific to Microsoft Dynamics AX reports. You can access the **Labels** category and the **Methods** category in the Edit Expression window but they are not available in the Expression dialog box as options. To add Labels or Methods to expressions in a precision design report, you must type the expression in the code editor of the Expression dialog box.

The following illustration is a screenshot of the Edit Expression window in Model Editor.

![Expression Editor](images/Cc551700.VSReportExpressionEditor(AX.60).gif "Expression Editor")

There are a couple ways to invoke the Edit Expression window window in Model Editor. Many of the properties in the **Properties** window for report elements include **\<Expression…\>** or **…** as an option in the drop-down menu. When you click **\<Expression…\>** or **…**, the Edit Expression window displays.

To invoke the Expression dialog box in a precision design report, right-click a report element, and then click **Expression**.

## Code Editor

When you open the Edit Expression window, the code editor displays the current expression for the element. If no expression exists, it will display an equal sign (=). When creating or editing an expression, you can select items from the various categories. Just select a category, select the item that you want to add to the expression, and then click **Paste**. You can also double-click an item to add it to an expression.

A wavy red underline indicates a syntax error. Hover over the underlined text to see the error message. When you have items followed by a punctuation separator, you will see a drop-down list of available properties, members, or methods. From the drop-down list, you can type the first few characters followed by a tab to automatically complete the selection.

## Categories

The following table describes the categories of items that can be used in an expression.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Constants</p></td>
<td><p>Displays a list of predefined values valid for the report element that are based on constants.</p>
<p>For example, a property based on color shows valid color names. For a property that is a Boolean data type, values are True and False.</p></td>
</tr>
<tr class="even">
<td><p>Globals</p></td>
<td><p>Displays a list of items in the global collection that can be used in an expression, such as <strong>ReportName</strong> and <strong>UserID</strong>.</p></td>
</tr>
<tr class="odd">
<td><p>Parameters</p></td>
<td><p>Displays a list of the report parameters that are defined in the report that can be used in an expression.</p>
<p>For example, if the report contained a report parameter for <strong>Region</strong>, you would see the <strong>Region</strong> parameter listed when you select the <strong>Parameters</strong> category. You could then set the <strong>Expression</strong> property for the <strong>Group on</strong> folder to group data based on the region parameter that was selected like =Parameters!Region.Value.</p></td>
</tr>
<tr class="even">
<td><p>Fields</p></td>
<td><p>Displays a list of fields that can be used in an expression. The list varies depending on the element that you are working with.</p></td>
</tr>
<tr class="odd">
<td><p>Datasets</p></td>
<td><p>Displays a list of datasets available for the report and lists the fields for each dataset.</p></td>
</tr>
<tr class="even">
<td><p>Labels</p></td>
<td><p>Displays a list of labels that are available for the report. This category is only available in the Model Editor version of the Edit Expression window.</p></td>
</tr>
<tr class="odd">
<td><p>Methods</p></td>
<td><p>Displays a list of data methods and built-in methods that are available for the report. This category is only available in the Model Editor version of the Edit Expression window.</p></td>
</tr>
<tr class="even">
<td><p>Operators</p></td>
<td><p>Displays the operators that you can include in a calculation or string manipulation.</p></td>
</tr>
<tr class="odd">
<td><p>Common Functions</p></td>
<td><p>Displays a list of functions that are commonly used in expressions.</p></td>
</tr>
</tbody>
</table>


## Expressions

Expressions can be simple or complex. A Simple expression contains a reference to a single dataset field, label, or parameter. For example, the expression for a dataset field appears as =Fields\!Name.Value. Simple expressions are created for you when you drag a field from a dataset onto a report design. You can also type them directly into the Property window for an **Expression** property or a property that has **\<Expression…\>** or **(…)** in the drop-down options. A Complex expression contains references to items such as datasets, fields, parameters, labels, data methods, and operands.

## Examples of Expressions

An expression begins with an equal sign (=). This section contains references to report examples. The following table describes some scenarios and examples of expression:

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Scenario</p></th>
<th><p>Description</p></th>
<th><p>Property value example</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Use an expression for a data element in a report design.</p></td>
<td><p>You can set the following properties for data to an expression:</p>
<ul>
<li><p><strong>Caption</strong> property to set the caption of the data item</p></li>
<li><p><strong>Expression</strong> property to set the value of the data item to a value</p></li>
<li><p><strong>Point Label</strong> property to set the label that should be used to display the point label values</p></li>
</ul></td>
<td><p>The following list provides an example of each of these properties set to an expression:</p>
<ul>
<li><p><strong>Caption</strong> =Labels!@SYS181459</p></li>
<li><p><strong>Expression</strong> to a simple expression like =Fields!SalesPerson.Value or a complex expression like =Sum(CDbl(Fields!Actual.Value))</p></li>
<li><p><strong>Point Label</strong> =Sum(CDbl(Fields!Actual.Value))</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Use an expression for a report parameter</p></td>
<td><p>You can set the following properties for a report parameter to an expression:</p>
<ul>
<li><p>Use the <strong>Values</strong> property to set the Value Label pair for a non-queried value.</p></li>
<li><p>Use the <strong>Default Value</strong> property to set a default value for the parameter</p></li>
</ul></td>
<td><p>The following list provides an example of each of these properties set to an expression:</p>
<ul>
<li><p>Set the <strong>Value</strong> property to <strong>1</strong> and set the <strong>Label</strong> property to =Today() then set a second <strong>Value</strong> property to 2 and set the <strong>Label</strong> property to =System.DateTime.today().addYears(-1)</p></li>
<li><p>If the parameter is a DateTime data type, then you could set the <strong>Default Value</strong> property to =Today()</p></li>
</ul></td>
</tr>
</tbody>
</table>


For additional examples of expressions, see [Expression Examples in Reporting Services](https://go.microsoft.com/fwlink/?linkid=106936).

## See also

[Working with Expressions](working-with-expressions.md)

[How to: Add a URL Drill Through Action on a Report](how-to-add-a-url-drill-through-action-on-a-report.md)

