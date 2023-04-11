---
title: "What's new: Analytics"
TOCTitle: Analytics
ms:assetid: 1b492ede-79e7-442b-a7c6-a4536cca7254
ms:mtpsurl: https://technet.microsoft.com/library/Dn507140(v=AX.60)
ms:contentKeyID: 59623245
author: tonyafehr
ms.date: 09/10/2014
mtps_version: v=AX.60
---

# What's new: Analytics 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This article describes the new features for online analytical processing (OLAP) in Microsoft Dynamics AX.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><img src="images/Dn507140.TopicIcons_WhatsNew(AX.60).png" title="What&#39;s new" alt="What&#39;s new" />
<p>New features in Microsoft Dynamics AX 2012 R3</p>
<p>New features in cumulative update 7 for Microsoft Dynamics AX 2012 R2</p>
<p>New features in Microsoft Dynamics AX 2012 R2</p>
<p>New features in Microsoft Dynamics AX 2012</p></td>
<td><img src="images/Dn507140.TopicIcons_Resources(AX.60).png" title="Resources" alt="Resources" />
<p><a href="ncdf/new-changed-and-deprecated-features-for-ax-2012.md">New, Changed, and Deprecated Features for AX 2012</a> (articles)</p>
<p><a href="what-s-new-reporting.md">What's new: Reporting</a> (article)</p></td>
</tr>
</tbody>
</table>


## New features in Microsoft Dynamics AX 2012 R3

The following features have been added in AX 2012 R3.

## New cubes

Microsoft Dynamics AX provides cubes that you can use to analyze your business data. The following table lists the Microsoft SQL Server Analysis Services projects that are provided with AX 2012 R3, and the cubes that are included with each project. The cubes that are new in AX 2012 R3 are followed by an asterisk (\*).

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Analysis Services project</p></th>
<th><p>Cubes that are included in project</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Demand Forecast</p></td>
<td><p>Demand forecast cube*</p></td>
</tr>
<tr class="even">
<td><p>Demand Forecast Accuracy</p></td>
<td><p>Demand forecast accuracy cube*</p></td>
</tr>
<tr class="odd">
<td><p>Dynamics AX</p></td>
<td><p>Accounts payable cube</p>
<p>Accounts receivable cube</p>
<p>Budget control cube</p>
<p>Budget plan cube</p>
<p>Environmental sustainability cube</p>
<p>Expense management cube</p>
<p>General ledger cube</p>
<p>Human resources cube</p>
<p>Inventory value cube</p>
<p>Payroll cube</p>
<p>Production cube</p>
<p>Profit tax totals cube</p>
<p>Project accounting cube</p>
<p>Purchase cube</p>
<p>Retail cube</p>
<p>Sales and marketing cube</p>
<p>Sales cube</p>
<p>Trade allowance management cube*</p>
<p>Workflow cube</p></td>
</tr>
</tbody>
</table>


For more information about the cubes, see [Cube and KPI reference for Microsoft Dynamics AX 2012 R2 and R3](cube-and-kpi-reference-for-microsoft-dynamics-ax-2012-r2-and-r3.md).

## New features in cumulative update 7 for Microsoft Dynamics AX 2012 R2

The following features have been added in cumulative update 7.

## New cubes

Microsoft Dynamics AX provides cubes that you can use to analyze your business data. The following cubes are included with cumulative update 7. The cubes that are new in this version are followed by an asterisk (\*).

  - Accounts payable cube

  - Accounts receivable cube

  - Budget control cube

  - Budget plan cube

  - Environmental sustainability cube

  - Expense management cube

  - General ledger cube

  - Human resources cube\*

  - Inventory value cube

  - Payroll cube\*

  - Production cube

  - Profit tax totals cube

  - Project accounting cube

  - Purchase cube

  - Retail cube

  - Sales and marketing cube

  - Sales cube

  - Workflow cube

For more information about the cubes, see [Cube and KPI reference for Microsoft Dynamics AX 2012 R2 and R3](cube-and-kpi-reference-for-microsoft-dynamics-ax-2012-r2-and-r3.md).

## New features in Microsoft Dynamics AX 2012 R2

The following features have been added in AX 2012 R2.

## New cubes

Microsoft Dynamics AX provides cubes that you can use to analyze your business data. The following cubes are included with AX 2012 R2. The cubes that are new in this version are followed by an asterisk (\*).

  - Accounts payable cube

  - Accounts receivable cube

  - Budget control cube\*

  - Budget plan cube\*

  - Environmental sustainability cube

  - Expense management cube

  - General ledger cube

  - Inventory value cube\*

  - Production cube

  - Profit tax totals cube\*

  - Project accounting cube

  - Purchase cube

  - Retail cube\*

  - Sales and marketing cube\*

  - Sales cube

  - Workflow cube

For more information about the cubes, see [Cube and KPI reference for Microsoft Dynamics AX 2012 R2 and R3](cube-and-kpi-reference-for-microsoft-dynamics-ax-2012-r2-and-r3.md).

## Windows PowerShell commands for cube deployment

If you are using AX 2012 R2, you can use Windows PowerShell commands to deploy the default cubes that are included with Microsoft Dynamics AX. For more information, see [Deploy the default cubes](deploy-the-default-cubes.md).

## Support for Power View

Power View is a tool that you can use to create highly interactive, custom reports. For example, assume that you want to create a report that shows sales amounts for your retail stores. In this case, you can open Power View, connect to the Retail cube, select the fields to display on the report, and display the report on a Role Center page in Microsoft Dynamics AX.


> [!NOTE]
> <P>If Analysis Services and Enterprise Portal are installed on different computers, you must use Kerberos security to create Power View reports.</P>



For more information about how to create Power View reports, see [Create a report by using Power View to connect to a cube](create-a-report-by-using-power-view-to-connect-to-a-cube.md).

## Support for data partitions

An AX 2012 R2 installation might consist of multiple data partitions. You must deploy cubes for each partition in your installation.

For example, assume that you have two partitions, *Partition 1* and *Partition 2*. To deploy the cubes that are included with Microsoft Dynamics AX for both of these partitions, follow these steps.

1.  Start the Microsoft SQL Server Analysis Services Project wizard.

2.  Select the default Analysis Services project, which is named *Dynamics AX*.

3.  Deploy the project for each partition in your installation by selecting the partitions. In this example, you select *Partition 1* and *Partition 2*.

4.  Complete the wizard.

5.  Open SQL Server Management Studio, and connect to the Analysis Services instance. There are now a database and cubes for each partition.

For more information about data partitions, see [Data partitioning architecture](data-partitioning-architecture.md). For more information about how to deploy cubes for each partition, see [Deploy the default cubes](deploy-the-default-cubes.md).

## Improvements to the Business Overview web part

Business Overview web parts, which are used on Role Center pages, can display financial indicators or key performance indicators (KPIs).

  - A financial indicator is a data calculation across various time periods. An indicator represents a measure in an OLAP cube.

  - A KPI is a business metric, such as the total revenue, gross profit margin, or current ratio. A KPI can help you track your organization’s progress toward a performance goal.

The following enhancements have been made to the way that you display indicators and KPIs in the Business Overview web part in AX 2012 R2.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Feature</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>You can apply multiple filters to indicators and KPIs.</p></td>
<td><p>For example, assume that you have selected to display your organization’s sales total. You can filter this KPI so that it displays only the sales that were made in 2012 by a specific salesperson. In this case, the filters resemble the following filters:</p>
<ul>
<li><p><strong>Filter 1:</strong> Year = 2012</p></li>
<li><p><strong>Filter 2:</strong> Salesperson Name = Kim Ackers</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>You can filter by relative dates or actual values.</p></td>
<td><p>For example, assume that you have selected to display your organization’s sales total. If you want to filter this KPI by a relative date, you can display only the sales that were made last year, last month, or last quarter. If you want to filter this KPI by an actual value, you can display only the sales where Year = 2012.</p></td>
</tr>
<tr class="odd">
<td><p>You can split the data.</p></td>
<td><p>You can display the individual elements that the whole indicator or KPI is made of. For example, assume that you have selected to display your organization’s sales total. You can split the sales total by salesperson to display the sales totals of all salespeople, or you can split the sales total by region to display the sales totals of each region.</p>
<p>You can also filter the list of elements. For example, assume that you can display only the top 10 salespeople or the 10 regions where the fewest sales were made. Alternatively, you can filter out the regions where no sales occurred.</p></td>
</tr>
<tr class="even">
<td><p>You can link to menu items or URLs.</p></td>
<td><p>You can format the name of the indicator or KPI as a hyperlink. The hyperlink can direct users to the following items:</p>
<ul>
<li><p>A menu item in the Microsoft Dynamics AX client</p></li>
<li><p>A menu item in Enterprise Portal for Microsoft Dynamics AX</p></li>
<li><p>A URL</p></li>
</ul></td>
</tr>
</tbody>
</table>


For more information about how to use the Business Overview web part, see [Manage business overview information](manage-business-overview-information.md).

## Upgrade information

The instructions for upgrading cubes vary, depending on the version of Microsoft Dynamics AX that you are upgrading from. The following table describes upgrade scenarios.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Scenario</p></th>
<th><p>How to upgrade</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>You are upgrading from Microsoft Dynamics AX 2009 to any version of Microsoft Dynamics AX 2012.</p></td>
<td><p>When you upgrade, you must create new cubes to display the information that your old cubes displayed. For more information, see <a href="how-to-upgrade-microsoft-dynamics-ax-cubes.md">How to: Upgrade Microsoft Dynamics AX cubes</a>.</p></td>
</tr>
<tr class="even">
<td><p>You are upgrading from the initial release of Microsoft Dynamics AX 2012 or Microsoft Dynamics AX 2012 Feature Pack to Microsoft Dynamics AX 2012 R2.</p></td>
<td><p>When you upgrade, use the Analysis Services Project wizard to upgrade the cubes. For more information, see <a href="how-to-upgrade-microsoft-dynamics-ax-cubes.md">How to: Upgrade Microsoft Dynamics AX cubes</a>.</p></td>
</tr>
</tbody>
</table>


## New features in Microsoft Dynamics AX 2012

The following features have been added in AX 2012.

## New cubes

Microsoft Dynamics AX provides cubes you can use to analyze your business data. The following cubes are included with the initial release of AX 2012. The cubes that are new in this version are followed by an asterisk (\*).

  - Accounts payable cube

  - Accounts receivable cube

  - Customer relationship management cube

  - Environmental sustainability cube\*

  - Expense management cube

  - General ledger cube

  - Production cube

  - Project accounting cube

  - Purchase cube

  - Sales cube

  - Workflow cube\*

For more information about the cubes, see [Cube and KPI reference for Microsoft Dynamics AX 2012 and Microsoft Dynamics AX 2012 Feature Pack](cube-and-kpi-reference-for-microsoft-dynamics-ax-2012-and-microsoft-dynamics-ax-2012-feature-pack.md).

## Cube deployment

The process for deploying the default Analysis Services cubes that are included with Microsoft Dynamics AX has changed in the following ways.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Feature</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>The Setup wizard has changed.</p></td>
<td><p>To deploy the default cubes that were included with AX 2009, you had to install the analysis extensions when you ran the Setup wizard. In AX 2012, the Setup wizard has been changed. The Setup wizard no longer includes an option for installing the analysis extensions.</p>
<p>When you run the Setup wizard, you can select the <strong>Analysis Services configuration</strong> option. When you select this option, the Setup wizard performs the following actions:</p>
<ul>
<li><p>Verifies that prerequisite software has been installed on the server that runs Analysis Services. For more information about the prerequisite software, see the <a href="https://go.microsoft.com/fwlink/?linkid=165377">system requirements</a>.</p></li>
<li><p>Prompts you to specify the domain accounts that will be used to process cubes. The Setup wizard gives these accounts read access to the online transaction processing (OLTP) database for Microsoft Dynamics AX.</p></li>
</ul>
<p>The Setup wizard does not deploy the default cubes that are included with AX 2012. To deploy the cubes, you must run the Analysis Services Project wizard.</p></td>
</tr>
<tr class="even">
<td><p>The Analysis Services Project wizard has been added.</p></td>
<td><p>The Analysis Services Project wizard has been added to AX 2012. Use this wizard to deploy and configure cubes. For more information, see the next section in this topic.</p></td>
</tr>
</tbody>
</table>


## Analysis Services Project wizard

The Analysis Services Project wizard has been added to AX 2012. This wizard makes it easier to deploy and configure cubes. The following table explains when you should use the Analysis Services Project wizard.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Description</p></th>
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Deploy default cubes.</p></td>
<td><p>Use the Analysis Services Project wizard to deploy an Analysis Services project and the cubes that the project contains.</p></td>
<td><p><a href="how-to-deploy-an-existing-sql-server-analysis-services-project.md">Deploy an Existing SQL Server Analysis Services Project</a></p></td>
</tr>
<tr class="even">
<td><p>Configure an Analysis Services project after you change the Microsoft Dynamics AX configuration.</p></td>
<td><p>Use the Analysis Services Project wizard to remove measures, dimensions, and KPIs that you do not have access to, according to the license and configuration keys in Microsoft Dynamics AX.</p></td>
<td><p><a href="configure-an-existing-sql-server-analysis-services-project.md">Configure an Existing SQL Server Analysis Services Project</a></p></td>
</tr>
<tr class="odd">
<td><p>Update an existing Analysis Services project.</p></td>
<td><p>Use the Analysis Services Project wizard to update an Analysis Services project as follows:</p>
<ul>
<li><p>Add or remove dimensions.</p></li>
<li><p>Add, remove, or update the calendars that are used as date dimensions.</p></li>
<li><p>Add or remove label translations.</p></li>
<li><p>Add or remove currency conversion.</p></li>
</ul></td>
<td><p><a href="how-to-update-an-existing-sql-server-analysis-services-project.md">Update an Existing SQL Server Analysis Services Project</a></p></td>
</tr>
<tr class="even">
<td><p>Create an Analysis Services project.</p></td>
<td><p>Use the Analysis Services Project wizard to create an Analysis Services project.</p></td>
<td><p><a href="create-a-new-sql-server-analysis-services-project.md">Create a New SQL Server Analysis Services Project</a></p></td>
</tr>
</tbody>
</table>


## Ability to use views to model data in perspectives

In AX 2012, you can now use both tables *and views* to model data in perspectives. Modeling data by using tables and views makes it easier to customize cubes. For more information, see [Create a perspective for a cube](create-a-perspective-for-a-cube.md).

## Date dimensions

In AX 2012, you can add date dimensions to your cubes. This means you can now examine the data in a cube by using different periods, such as months, quarters, or weeks.

To add date dimensions to your cubes, follow these steps.

1.  Use the **Date dimensions** form to specify the date dimensions that are used to examine the data in a cube. For more information, see [How to: Create a Date Dimension for a Cube](how-to-create-a-date-dimension-for-a-cube.md).

2.  Run the Analysis Services Project wizard to add the date dimensions to your cube. For more information, see [Update an Existing SQL Server Analysis Services Project](how-to-update-an-existing-sql-server-analysis-services-project.md).

## Upgrade information

If you are upgrading from AX 2009 to AX 2012, you must create new cubes to display the information that your old cubes used to display. For more information, see [How to: Upgrade Microsoft Dynamics AX cubes](how-to-upgrade-microsoft-dynamics-ax-cubes.md).

  


