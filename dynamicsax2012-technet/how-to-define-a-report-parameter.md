---
title: 'How to: Define a Report Parameter'
TOCTitle: 'How to: Define a Report Parameter'
ms:assetid: 2cf31596-dba8-4d46-95f6-5ed591cf45de
ms:mtpsurl: https://technet.microsoft.com/library/Cc586123(v=AX.60)
ms:contentKeyID: 28119327
author: Khairunj
ms.date: 04/17/2013
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Framework.Design.Model.Reports.ReportParametersDefinition
---

# How to: Define a Report Parameter 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Parameters are used to specify the data to use in a report, connect related reports together, and control report presentation. This topic contains a section that describes the different kinds of report parameters that can be used on Microsoft Dynamics AX reports.

Report parameters are used to enable interactive, client-side data filtering in a report. In this case, you must manually define a parameter, and then use it to define an expression for a report filter. Since filters are applied on the client, there is no round tripping required.

The following procedures explain how to manually define a report parameter and use it in a filter.

### To manually define a report parameter

1.  In Model Editor, expand the node for the report that you want to work with.

2.  Right-click the **Parameters** node, point to **Add**, and then click **Parameter**. A node for the parameter displays.

3.  Select the node for the parameter.

4.  In the **Properties** window, specify property values for the parameter.
    
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
    <td><p><strong>Allow Blank</strong></p></td>
    <td><p>Indicates whether the parameter is allowed to be blank.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Data Type</strong></p></td>
    <td><p>The data type of the parameter, such as DateTime.</p>
    <div class="alert">

    > [!NOTE]
    > <P>If a parameter is the DateTime Data Type, the Microsoft Dynamics AX client treats the parameter as coordinated universal time (UTC) and any default value from Reporting Services will be converted to the local user time zone. When you preview a report with a DateTime parameter, the time format displays as an Integer Data Type in Visual Studio preview. The report will render correctly as a DateTime Data Type in the Microsoft Dynamics AX client.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Default Value</strong></p></td>
    <td><p>A default value for the parameter.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Multi Value</strong></p></td>
    <td><p>Set the property to <strong>True</strong> in the following scenarios:</p>
    <ul>
    <li><p>The parameter is allowed to have multiple values.</p></li>
    <li><p>The parameter is static and represents a range on a query.</p></li>
    </ul>
    <div class="alert">

    > [!NOTE]
    > <P>The ‘;’ is not supported by the <STRONG>MSDAX</STRONG> client to mean <STRONG>Multi Value</STRONG>. If you set the <STRONG>Multi Value</STRONG> property to <STRONG>True</STRONG> and the end user of the report provides values like <STRONG>1;2;3</STRONG> then the client will only use <STRONG>1</STRONG> as the value.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Name</strong></p></td>
    <td><p>The name of the parameter in the model.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Nullable</strong></p></td>
    <td><p>Indicates whether the value of a parameter can be null. If the <strong>Nullable</strong> property is set to <strong>True</strong>, a null value indicator check box displays next to the control that is generated for the parameter.</p>
    <div class="alert">

    > [!NOTE]
    > <P>The Reporting Framework does not provide support for indicating that an Integer, Float, or String parameter is a NULL value.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Prompt String</strong></p></td>
    <td><p>The text that displays in the user interface when a user is prompted to enter a value for the parameter.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Values</strong></p></td>
    <td><p>Indicates how values are supplied for a parameter. Click the ellipsis button (...) to display a dialog box with the following options.</p>
    <ul>
    <li><p><strong>From Dataset</strong> - Use this option to display a set of values from a particular dataset. Select a dataset from the drop-down list for the <strong>Dataset</strong> property, and then select a <strong>Label Field</strong> and a <strong>Value Field</strong> from the corresponding drop-down lists. The <strong>Label Field</strong> value displays to the end user. The <strong>Value Field</strong> value is used in filters or passed back to a query parameter when this parameter is used by a dataset.</p></li>
    <li><p><strong>Non-queried</strong> - Use this option to display a set of unbound values that are not from a dataset. Provide a set of value/label pairs in the table for each item that you want to include as an available value. Unbound values must be a String type because they are entered and stored as text. You can leave the table blank and not specify any value/label pairs. However, if you do this, you will not be allowed to specify a default value for the parameter using the <strong>Default Value</strong> property since the default value must come from the set of available values. In this case, it is recommended that you use the <strong>Null</strong> option.</p></li>
    <li><p><strong>Null</strong> - Use this option if you want to allow unrestricted values for the parameter (restricted only by the data type). You can specify a default value for the parameter using the <strong>Default Value</strong> property.</p></li>
    </ul></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Visibility</strong></p></td>
    <td><p>Indicates whether the parameter is displayed to the user.</p></td>
    </tr>
    </tbody>
    </table>
    
    The property values that you specify for a parameter in the **Properties** window determine what a user sees when the parameter displays in a report. For more information about the controls used to render parameters in a report, see [Controls Used to Render Report Parameters](controls-used-to-render-report-parameters.md).

### To use a report parameter in a filter

1.  In Model Editor, expand the **Designs** node for the report.

2.  Expand the node for the design that you want to add a filter to.

3.  Right-click the **Filters** node, and then click **Add Filter**. A node for the filter displays.

4.  Select the node for the filter.

5.  In the **Properties** window, specify the following properties.
    
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
    <td><p>An expression for the filter. From the drop-down list, choose a valid field for the filter to create a simple expression, or choose <strong>&lt;Expression…&gt;</strong> to open the <strong>Edit Expression</strong> dialog box to create a more complex expression.</p></td>
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
    <td><p>The parameter or an expression that contains the parameter. Choose <strong>&lt;Expression…&gt;</strong> from the drop-down list to create a complex expression. For information about creating expressions, see <a href="https://go.microsoft.com/fwlink/?linkid=106936">Expression Examples in Reporting Services</a>.</p></td>
    </tr>
    </tbody>
    </table>


6.  To preview the layout of the report, right-click the node for the design, and then click **Preview**. The parameters display when you select the **Parameters** tab in the **Preview** window.


> [!NOTE]
> <P>If the report is bound to a query with a range and a default value is specified, the report could be filtered by a multivalued parameter. To avoid this, you have the following options:</P>
> <UL>
> <LI>
> <P>Mark the query range parameter as internal in the report design to prevent duplicating the filter.</P>
> <LI>
> <P>Override the single filter using a report data provider (RDP) class.</P>
> <LI>
> <P>Avoid using queries that contain a predefined query range in reports.</P></LI></UL>



There are many types of report parameters. Use the following table to decide which is best suited for your report. The following table describes how parameters are created, how that affects a report, and any special considerations:

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Type of parameter</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>SysQuery parameters</p></td>
<td><p>SysQuery parameters are generated from a query that is created in the AOT. If you use a parameterized query in a dataset, a report parameter is generated for each parameter in the query. Applying user-selected parameter values require round-tripping the parameterized query to the server during the data retrieval process.</p>
<p>Queries created in the AOT are defined by using the SysQuery class. Reports that are accessed from Enterprise Portal cannot use SysQuery parameters.</p>
<p>A static range parameter is generated if a query has a range specified, and the <strong>Dynamic Filters</strong> property on the dataset is set to <strong>False</strong>. A static range parameter is based on the query range, and is generated for a report bound to the query.</p>
<p>A dynamic range parameter is generated if a query has a range specified, and the <strong>Dynamic Filters</strong> property on the dataset is set to <strong>True</strong>. A dynamic range parameter is based on the query range generated for a report bound to the query. The generated parameter will be named with a suffix of <strong>_DynamicParameter</strong>.</p></td>
</tr>
<tr class="even">
<td><p>System parameters</p></td>
<td><p>These parameters are generated based on metadata for the company name, user context, language, and report context. These parameters are prefixed with <strong>AX_</strong>, for example, AX_CompanyName.</p></td>
</tr>
<tr class="odd">
<td><p>Filter parameters</p></td>
<td><p>These parameters enable interactive, client-side data filtering in a report. In this case, you must manually define a parameter, and then use it to define an expression for a report filter. Since filters are applied on the client, there is no round-tripping required. For more information, see <a href="how-to-define-a-report-filter.md">How to: Define a Report Filter</a>.</p></td>
</tr>
<tr class="even">
<td><p>Static parameters</p></td>
<td><p>These parameters are bound to a dataset and let the user select report data.</p></td>
</tr>
<tr class="odd">
<td><p>Unbound parameters</p></td>
<td><p>These parameters display a set of values that are not from a dataset. You provide a set of value/label pairs in the table for each item that you want to include as an available value.</p></td>
</tr>
<tr class="even">
<td><p>Business logic parameters</p></td>
<td><p>These parameters are generated when the dataset is bound to a data method. For more information, see <a href="using-business-logic-in-report-data-methods-to-access-report-data.md">Using Business Logic in Report Data Methods to Access Report Data</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Report data provider (RDP) parameters</p></td>
<td><p>These parameters are generated for an RDP data contract as a static parameter. RDP parameters are defined in Controller classes. Enterprise Portal does not support the Controller class. For more information, see <a href="how-to-use-a-report-data-provider-class-in-a-report.md">How to: Use a Report Data Provider Class in a Report</a>.</p></td>
</tr>
<tr class="even">
<td><p>Enum parameters</p></td>
<td><p>These parameters expose enum types on a report in a friendly drop-down list. You can create a range on a query to expose an enum parameter in the Microsoft Dynamics AX client. However, if you want the report to be run from Enterprise Portal, you must use an AX Enum Provider to define the parameter. For more information, see <a href="how-to-use-an-enum-as-a-report-parameter.md">How to: Use an Enum as a Report Parameter</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Online analytical processing (OLAP) parameters</p></td>
<td><p>These parameters are used in OLAP reports where you provide the parameter selection into a Multidimensional Expression (MDX) query that generates an OLAP dataset. For more information, see <a href="parameters-overview.md">Parameters Overview</a>.</p></td>
</tr>
<tr class="even">
<td><p>Cascading parameters</p></td>
<td><p>Cascading parameters provide a way of managing large amounts of report data. You can define a set of related parameters so that the list of values for one parameter depends on the value chosen in another parameter. For example, the first parameter is independent and might present a list of product categories. When the user selects a category, the second parameter depends on the value of the first parameter. Its values are updated with a list of subcategories in the chosen category. When the user views the report, the values for both the category and subcategory parameters are used to filter report data.</p></td>
</tr>
</tbody>
</table>


## See also

[How to: Define a Report Filter](how-to-define-a-report-filter.md)

[Controls Used to Render Report Parameters](controls-used-to-render-report-parameters.md)

[Expression Examples in Reporting Services](https://go.microsoft.com/fwlink/?linkid=106936)

