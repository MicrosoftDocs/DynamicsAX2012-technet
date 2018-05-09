---
title: Parameters Overview
TOCTitle: Parameters Overview
ms:assetid: 623870c9-36fe-4d40-83bd-662575d31005
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh528478(v=AX.60)
ms:contentKeyID: 37835168
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# Parameters Overview 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Parameters are used to filter the data that is displayed in a report, connect related reports together, and control report presentation. For example, you can write an expression to change the font based on a parameter that was passed to the report. This topic provides guidance about how to define parameters in a report model, the types of parameters that you can use in a Microsoft Dynamics AX report, and information about how to group and order report parameters.

## Parameters in a Report Model

You can use Model Editor to define a report. Model Editor is a tool provided by the Visual Studio tools for Microsoft Dynamics AX. You will see two kinds of parameters in Model Editor as shown in the following illustration:

![Model Editor Screenshot with Parameters](images/Hh528478.DatasetandReportParametersinaReport(AX.60).png "Model Editor Screenshot with Parameters")

You can add a dataset to a report to bind the report to data. A dataset can be bound to a query, business logic, report data provider, AX enum provider, or an OLAP data source. For more information, see [Guidance for Choosing the Data Source Type](guidance-for-choosing-the-data-source-type.md). When you add the dataset, dataset parameters are added to the report model. The dataset parameters are in the **Parameters** node under the dataset. Dataset parameters are the parameters that are generated for that dataset. You do not have to modify the dataset parameters unless you have to modify the report parameter that the dataset parameter is referencing. Report parameters are in the Parameters node at the report level. Report parameters are the parameters that the end user of the report sees when they run the report. Some report parameters are created by the reporting framework, such as a report parameter for each dataset parameter and the system parameters. Also, you can manually define report parameters.

Dataset parameters become relevant in a scenario where you reference the same report parameters from multiple dataset parameters. When you define a dataset, the applicable dataset parameters are generated for the report. Each dataset parameter references a report parameter in the **Report parameter** property. If you define a report that has more than one dataset that references the same field, then you may want to configure the dataset parameters to reference the same report parameter.

For example, assume you have two datasets, each bound to a different query with a range set on the InvoiceID field. In Model Editor, two dataset parameters and two report parameters are generated for the two datasets as shown in the following screen shot.

![Model Editor Screenshot Illustrating Parameters](images/Hh528478.ParametersInAReport(AX.60).png "Model Editor Screenshot Illustrating Parameters")

The end-user of the report will be prompted two times for the InvoiceID parameter. You can delete one of the report parameters for InvoiceID and set the **Report parameter** property for both dataset parameters for InvoiceID to the remaining InvoiceID report parameter. The report that is generated would prompt the user for the value of the range and filter data from both datasets based on the single report parameter value. For more information see [Walkthrough: Referencing a Report Parameter from Multiple Datasets in a Precision Design Report](walkthrough-referencing-a-report-parameter-from-multiple-datasets-in-a-precision-design-report.md).

## Types of Parameters

Parameters are static unless you explicitly make them dynamic.

  - Static parameters are bound to a dataset and let the end user filter report data based on the fields you defined as report parameters. For more information, see [How to: Define a Report Parameter](how-to-define-a-report-parameter.md).

  - Dynamic parameters allow the end user of the report to add more filters based on any of the fields from the report data. For more information, see [How to: Define a Report with Dynamic Filters](how-to-define-a-report-with-dynamic-filters.md).

This section references report names as examples. For information about how to access the reports in Visual Studio tools for Microsoft Dynamics AX, see [How to: Access a Report for Edit](how-to-access-a-report-for-edit.md). The following table describes how adding datasets bound to various data source types will create different types of parameters:

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Dataset parameter</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Query parameter</p></td>
<td><p>You create a query parameter when you add a dataset that is bound to an AOT query with a range. A dataset parameter and report parameter are created in the report model for each range set in the AOT query. When you create a query in the AOT, the query is defined by using the SysQuery class. Enterprise Portal (EP) cannot process reports that use SysQuery parameters so <a href="https://technet.microsoft.com/en-us/library/hh330284(v=ax.60)">the parameters must be added explicitly for EP</a>.</p>
<p>The following list describes how setting the <strong>Dynamic Filters</strong> property is used to indicate whether the query parameters should be static or dynamic.</p>
<ul>
<li><p>A static range parameter is created in the report model when you bind a dataset to a query that has a range specified, and the <strong>Dynamic Filters</strong> property on the dataset is set to <strong>False</strong>. A dataset parameter and report parameter are created in the report model for each query range. The parameters are named the same as the field that the range is based on for the AOT query. The end-user will be prompted to provide a value for the parameter to filter the report based on the range, but they will not be able to add more fields to filter on. The ProjBeginningBalances report contains examples of static range parameters. The ProjBeginningBalancesCostSalesDS dataset is bound to the ProjBeginningBalancesCostSales query and the <strong>Dynamic Filters</strong> property is set to <strong>False</strong>. The query has a range set on the <strong>Voucher</strong> field. A static range parameter called <strong>Voucher</strong> was generated when the dataset was added to the report model.</p></li>
<li><p>A dynamic range parameter is created in the report model when you bind a dataset to a query that has a range specified, and the <strong>Dynamic Filters</strong> property on the dataset is set to <strong>True</strong>. One dataset parameter that references a report parameter is created to pass any of the filters to Reporting Services that the end-user adds. The naming convention for the dataset parameter and report parameter is <strong>[DatasetName]_DynamicParameter</strong>. Most of the reports that are included with Microsoft Dynamics AX that are bound to a query also have the <strong>Dynamic Filters</strong> property set to <strong>True</strong> and a dynamic parameter was added for them. An example of a dynamic range parameter can be found in the AssetAcquisition report.</p></li>
</ul>
<p>For more information, see <a href="using-queries-to-access-report-data.md">Using Queries to Access Report Data</a>.</p></td>
</tr>
<tr class="even">
<td><p>Business logic parameter</p></td>
<td><p>You define a business logic parameter in a data method by using C# or Visual Basic. The parameters specified in the data method signature are reflected in the report model when you build the solution that contains the data method. The following list describes the common scenarios to use a data method as a source of report data:</p>
<ul>
<li><p>You want to perform processing logic on report data after it is retrieved from a source other than Microsoft Dynamics AX.</p></li>
<li><p>You want to use web services to access report data that is from a source other than Microsoft Dynamics AX.</p></li>
</ul>
<p>You can use a dataset bound to a data method when the report data is something other than Microsoft Dynamics AX. Therefore, you will not find examples of these types of reports included with Microsoft Dynamics AX. For more information, see <a href="using-business-logic-in-report-data-methods-to-access-report-data.md">Using Business Logic in Report Data Methods to Access Report Data</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Report data provider (RDP) parameter</p></td>
<td><p>An RDP class is an X++ class that is used to access and process data for a report. You would use an RDP class when the following conditions are true:</p>
<ul>
<li><p>You cannot query directly for the data that you want to display on a report.</p></li>
<li><p>The data to be processed and displayed is from Microsoft Dynamics AX.</p></li>
</ul>
<p>You define the parameters that an RDP class references in a data contract class. Many of the reports that are included with Microsoft Dynamics AX are bound to an RDP class. For an example, see the AgreementConfirmation report and the many parameters defined for the AgreementConfirmation report in the AgreementConfirmationRDPContract class. For more information, see <a href="using-report-data-provider-classes-to-access-report-data.md">Using Report Data Provider Classes to Access Report Data</a>.</p></td>
</tr>
<tr class="even">
<td><p>AX enum provider parameter</p></td>
<td><p>You can expose enum types on a report in a friendly drop-down list. For example, if you create a report to show data based on the BankAccountType enumeration, the end user would see a <strong>Bank account type</strong> parameter and select whether <strong>Checking</strong> or <strong>Savings</strong> data should display on the report. One option is to create a range on a query to expose an enum parameter in the Microsoft Dynamics AX client. However, if you want the report to be run from Enterprise Portal, you must use an AX Enum Provider to define the parameter. For more information, see <a href="using-ax-enum-provider-to-access-report-data.md">Using AX Enum Provider to Access Report Data</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Online analytical processing (OLAP) parameter</p></td>
<td><p>You can access multi-dimensional analytical data on a report when you bind a dataset to an OLAP data source. The WorkflowPerformance report contains examples of OLAP parameters. For example, the <strong>Module</strong> parameter was defined as an attribute in the Workflow cube and the values that the end-user sees in the parameter drop-down list are members of the <strong>Module</strong> attribute.</p></td>
</tr>
</tbody>
</table>


Dataset parameters are bound to a specific report parameter. A report parameter is created for each dataset parameter. The report parameters are the parameters that are displayed on a report. The following table describes report parameter types that can be created in addition to the report parameters that correspond to each dataset parameter:

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Report parameter</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Filter parameter</p></td>
<td><p>To add a filter parameter, you add a report parameter, add a report filter in an auto design report, and then set the filter <strong>Expression</strong> property to the report parameter. This prompts the end user of the report to provide a parameter value that will be used to filter the report data. These parameters enable interactive, client-side data filtering in a report. Since filters are applied on the client, there is no round-tripping required that results in a performance improvement to the report. For more information, see <a href="how-to-define-a-report-filter.md">How to: Define a Report Filter</a>.</p></td>
</tr>
<tr class="even">
<td><p>System parameter</p></td>
<td><p>System parameters are added to the report model when you add a dataset to the report. System parameters are based on metadata for the company name, user context, language, and report context. System parameters are prefixed with <strong>AX_</strong>, for example, AX_CompanyName. The system parameters are internal parameters, not visible to the end-user, and primarily used by the reporting framework except for the following exceptions:</p>
<ul>
<li><p>AX_CompanyName – to control the company as a parameter, make the parameter visible. For more information, see <a href="how-to-create-a-company-parameter-in-a-report.md">How to: Create a Company Parameter in a Report</a>.</p></li>
<li><p>AX_RenderingCulture – to control the rendering culture as a parameter, make the parameter visible to let the end user of the report to select a culture, for example <strong>EN-US</strong>.</p></li>
<li><p>AX_ReportContext – to determine which type of client the report is running on, for generating the correct drill through. For more information, see <a href="how-to-add-a-url-drill-through-action-on-a-report.md">How to: Add a URL Drill Through Action on a Report</a>.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Additional ways to define parameter drop-down values:</p></td>
<td><ul>
<li><p>Unbound parameter – You can display a set of values as a report parameter that is not from a dataset. You provide a set of value/label pairs for each item that you want to include as an available value. For more information, see <a href="how-to-define-a-report-parameter.md">How to: Define a Report Parameter</a>.</p></li>
<li><p>Cascading parameter – Cascading parameters provide a way to manage large amounts of report data. You can define a set of related parameters so that the list of values for one parameter depends on the value chosen in another parameter. For example, the first parameter is independent and might present a list of product categories. When the user selects a category, the second parameter depends on the value of the first parameter. Its values are updated with a list of subcategories in the chosen category. When the user views the report, the values for both the category and subcategory parameters are used to filter the report data.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Grouping and Ordering Parameters

You can control the grouping and ordering of report parameters on a report. You can use either a data contract class or Model Editor to do this.

You use X++ code editor and a data contract class to define the grouping and order of report parameters when you want to maintain consistent formatting when you reuse the data contract in another report. You define a data contract class in the X++ code editor for a dataset that is bound to a report data provider (RDP) class. You can specify one or more groups of report parameters, the order of the groups, and the order in which the report parameters appear in a print dialog box. For more information, see [How to: Group and Order Report Parameters by Using a Data Contract Class](how-to-group-and-order-report-parameters-by-using-a-data-contract-class.md).

You use Model Editor to define the grouping and order of report parameters when the scenario is complex, such as when you want to use multiple nested groups. The order that the report parameters are listed in a group is the order that the end user will see them on the report. This makes the grouping and order in Model Editor easy to see as you define the report.. The grouping and order of report parameters that you specify in Model Editor take precedence over the grouping and order that you defined in the data contract. For more information, see [How to: Group and Order Report Parameters by Using Visual Studio](how-to-group-and-order-report-parameters-by-using-visual-studio.md).

## See also

[Working with Parameters](working-with-parameters.md)

