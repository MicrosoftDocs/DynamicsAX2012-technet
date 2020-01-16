---
title: Analytics in Microsoft Dynamics AX
TOCTitle: Analytics
ms:assetid: 8f284ccb-628f-4e84-b82c-3e0c032ad80f
ms:mtpsurl: https://technet.microsoft.com/library/Ee873272(v=AX.60)
ms:contentKeyID: 28119398
author: Khairunj
ms.date: 06/11/2014
mtps_version: v=AX.60
---

# Analytics in Microsoft Dynamics AX 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Microsoft Dynamics AX provides online analytical processing (OLAP) functionality through the use of cubes. These cubes, built on the Microsoft SQL Server Analysis Services platform, enable you to analyze large amounts of data and identify trends that you might not otherwise discover when viewing data on traditional reports.

Microsoft Dynamics AX includes default cubes that you can use in your Microsoft Dynamics AX implementation. This article guides you through the process of installing, deploying, and using these cubes. This article also provides information about how to customize the default cubes and create new ones.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><img src="images/Gg723980.TopicIcon_Lifecycle(AX.60).png" title="Lifecycle" alt="Lifecycle" />
<p>Get started</p>
<p>Install and deploy</p>
<p>Configure</p>
<p>Extend</p>
<p>Use</p>
<p>Troubleshoot</p>
<p>View technical reference</p></td>
<td><img src="images/Dn507140.TopicIcons_Resources(AX.60).png" title="Resources" alt="Resources" />
<p><a href="http://blogs.msdn.com/b/dynamicsaxbi/">Microsoft Dynamics AX Business Intelligence (blog)</a></p>
<p><a href="http://www.youtube.com/user/dynamicsaxbi">Microsoft Dynamics AX BI videos channel (videos)</a></p>


</td>
</tr>
</tbody>
</table>


![Get started](images/Gg723980.LessColor_GetStarted(AX.60).png "Get started")

A cube is a multidimensional structure that contains dimensions and measures. Dimensions define the structure of the cube, while measures provide the numerical values of interest to the end user. Cell positions in the cube are defined by the intersection of dimension members, and the measure values are aggregated to provide the values in the cells.

The following table lists tasks you can complete to learn more about cubes and how you can use them in your Microsoft Dynamics AX implementation.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Details</p></th>
<th><p>Resources</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Learn what’s new</p></td>
<td><p>Several features have been added to Microsoft Dynamics AX 2012 and Microsoft Dynamics AX 2012 R2 to help you install, deploy, and use cubes.</p>
<p>For example, the Analysis Services project wizard, introduced in Microsoft Dynamics AX 2012, makes it easier to create, update, configure, and deploy Analysis Services projects. The wizard performs many of the tasks that you would otherwise need to perform manually.</p></td>
<td><p><a href="what-s-new-analytics.md">What's new: Analytics</a></p></td>
</tr>
<tr class="even">
<td><p>Learn about cubes</p></td>
<td><p>You can use cubes to analyze data in Microsoft Dynamics AX that is otherwise too complex.</p>
<p>A cube consists of a set of measures and dimension attributes. For Microsoft Dynamics AX analysis cubes, measures and dimensions are defined in the Application Object Tree (AOT). A perspective is used to identify the tables and views that contain the measures and dimensions.</p>
<p>A cube contains a snapshot of data that is refreshed (or processed) based on your specifications. After cubes are deployed and processed, you can access the data and display it in reports and key performance indicators (KPIs).</p></td>
<td><p><a href="cube-overview.md">Cube overview</a></p>
<p><a href="analytics-architecture.md">Analytics architecture</a></p></td>
</tr>
<tr class="odd">
<td><p>Plan your implementation</p></td>
<td><p>Before you implement cubes in your Microsoft Dynamics AX environment, there are many things you should consider. For example, you must determine how Analysis Services will fit within your system topology, decide which roles should have access to each cube, and select the tools you want to use to access and display data from the cubes.</p></td>
<td><p><a href="analytics-architecture.md">Analytics architecture</a></p>
<p><a href="planning-considerations-for-analytics.md">Planning considerations for analytics</a></p>
<p><a href="tools-used-for-analytics.md">Tools used for analytics</a></p>
<p><a href="http://www.microsoft.com/en-us/download/details.aspx?id=38410">Business Intelligence Capabilities and Tools white paper</a></p></td>
</tr>
</tbody>
</table>


Back to top

![Install and deploy](images/Ee873263.LessColor_InstallAndDeploy(AX.60).png "Install and deploy")

Complete the tasks in the following table to integrate Microsoft Dynamics AX and Analysis Services and to deploy the cubes that are included with Microsoft Dynamics AX.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Details</p></th>
<th><p>Resources</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Verify permissions</p></td>
<td><p>To integrate Microsoft Dynamics AX and Analysis Services, you must run the Microsoft Dynamics AX Setup wizard and select the <strong>Analysis Services configuration</strong> option. Verify that you have the required permissions to run the wizard.</p></td>
<td><p><a href="verify-that-you-have-the-required-permissions-for-installation.md">Verify that you have the required permissions for installation</a></p></td>
</tr>
<tr class="even">
<td><p>Create a domain account</p></td>
<td><p>Create a domain account to run the Analysis Services service.</p></td>
<td><p><a href="create-service-accounts.md">Create service accounts</a></p></td>
</tr>
<tr class="odd">
<td><p>Assign the Business Connector proxy account to the Analysis Services server administrator role</p></td>
<td><p>The proxy account for Business Connector must be assigned to the server administrator role in Analysis Services. To do this, follow these steps:</p>
<ol>
<li><p>Open Microsoft SQL Server Management Studio and connect to your Analysis Services instance.</p></li>
<li><p>In the tree view, right-click the Analysis Services instance, and then click <strong>Properties</strong>. The <strong>Analysis Services Properties</strong> window is displayed.</p></li>
<li><p>In the <strong>Select a page</strong> area, click <strong>Security</strong>.</p></li>
<li><p>Click <strong>Add</strong>. The <strong>Select Users or Groups</strong> form is displayed.</p></li>
<li><p>Enter the Business Connector proxy account in the following format: [DomainName]\[UserName]. Click <strong>OK</strong>.</p></li>
</ol></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Install prerequisites</p></td>
<td><p>On the computer where Analysis Services is installed, or where you plan to install Analysis Services, run the Microsoft Dynamics AX prerequisite validation utility to verify that system requirements have been met.</p></td>
<td><p><a href="check-prerequisites.md">Check prerequisites</a></p>
<p><a href="http://go.microsoft.com/fwlink/?linkid=165377">System requirements</a></p></td>
</tr>
<tr class="odd">
<td><p>Run the Microsoft Dynamics AX Setup wizard</p></td>
<td><p>Run the Microsoft Dynamics AX Setup wizard and select the <strong>Analysis Services configuration</strong> option. This option configures Analysis Services so that it can be used with Microsoft Dynamics AX.</p></td>
<td><p><a href="configure-analysis-services-by-running-setup.md">Configure Analysis Services by running Setup</a></p></td>
</tr>
<tr class="even">
<td><p>Install SQL Server Shared Management Objects</p></td>
<td><p>You must install the Shared Management Objects for Microsoft SQL Server on Microsoft Dynamics AX client computers that you plan to use to complete the following tasks:</p>
<ul>
<li><p>Run the <strong>SQL Server Analysis Services project wizard</strong>.</p></li>
<li><p>Use the <strong>Analysis servers</strong> form.</p></li>
</ul>
<p>Download the Shared Management Objects for the version of SQL Server that you are using. You can download the Shared Management Objects from one of the following web pages:</p>
<ul>
<li><p><a href="http://www.microsoft.com/en-us/download/details.aspx?id=16978">SQL Server 2008 R2 Feature Pack page</a></p></li>
<li><p><a href="http://www.microsoft.com/en-us/download/details.aspx?id=29065">SQL Server 2012 Feature Pack page</a></p></li>
</ul></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Select a system currency and an exchange rate type</p></td>
<td><p>When Analysis Services generates monetary amounts in a cube, the amounts are calculated by using the system currency and exchange rate type. Follow these steps to select a system currency and an exchange rate type.</p>
<ol>
<li><p>Open the Microsoft Dynamics AX client.</p></li>
<li><p>Click <strong>System administration</strong> &gt; <strong>Setup</strong> &gt; <strong>System parameters</strong>.</p></li>
<li><p>From the <strong>System currency</strong> list, select a currency.</p></li>
<li><p>From the <strong>System exchange rate type</strong> list, select an exchange rate type.</p></li>
</ol></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Deploy default cubes</p></td>
<td><p>Use the Analysis Services project wizard or Windows PowerShell to deploy the Analysis Services project that contains the default cubes. You must deploy and process these cubes to use the reports and KPIs that are based on them.</p></td>
<td><p><a href="deploy-the-default-cubes.md">Deploy the default cubes</a></p></td>
</tr>
<tr class="odd">
<td><p>Upgrade cubes</p></td>
<td><p>When you upgrade from one version of Microsoft Dynamics AX to another, sometimes you can upgrade your cubes by using the Analysis Services project wizard. Other times, you must create new ones.</p></td>
<td><p><a href="how-to-upgrade-microsoft-dynamics-ax-cubes.md">How to: Upgrade Microsoft Dynamics AX cubes</a></p></td>
</tr>
</tbody>
</table>


Back to top

![Configure](images/Gg723980.LessColor_Configure(AX.60).png "Configure")

After you have deployed cubes, complete the tasks, listed in the following table, to configure them for use.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Details</p></th>
<th><p>Resources</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Update the OLAP data source</p></td>
<td><div class="alert">

> [!NOTE]
> <P>If you are using Microsoft Dynamics AX 2012 R2 or later, this task does not apply to you.</P>


</div>
<p>By default, the cubes that are provided with Microsoft Dynamics AX are stored in an Analysis Services database named <em>Dynamics AX</em>. If you entered a custom name for this database when you deployed the cubes, you must update the data source that is used to connect to that database.</p></td>
<td><p><a href="update-the-olap-data-source.md">Update the OLAP data source</a></p></td>
</tr>
<tr class="even">
<td><p>Configure the default cubes</p></td>
<td><p>Configure the cubes based on the changes that you have made to the Microsoft Dynamics AX configuration or license keys.</p></td>
<td><p><a href="configure-an-existing-sql-server-analysis-services-project.md">Configure an Existing SQL Server Analysis Services Project</a></p></td>
</tr>
<tr class="odd">
<td><p>Configure security</p></td>
<td><p>Security for analysis cubes is set up independently from security for Microsoft Dynamics AX. To grant users access to cubes, you must assign the users to database roles in Analysis Services.</p>
<p>The members of an Analysis Services role have permission to view all data in the cubes that the role has access to. To help restrict a role’s access to specific dimensions and cells in a cube, you can perform customizations.</p></td>
<td><p><a href="security-and-protection-for-analytics.md">Security and protection for analytics</a></p>
<p><a href="grant-users-access-to-cubes.md">Grant users access to cubes</a></p>
<p><a href="default-analysis-services-roles.md">Default Analysis Services roles</a></p>
<p><a href="scenario-help-prevent-employees-of-one-company-from-viewing-cube-data-for-another-company.md">Scenario: Help prevent employees of one company from viewing cube data for another company</a></p>
<p><a href="scenario-help-secure-cube-data-so-that-managers-see-only-the-data-for-their-own-team.md">Scenario: Help secure cube data so that managers see only the data for their own team</a></p>
<p><a href="scenario-mapping-security-in-microsoft-dynamics-ax-to-analysis-services.md">Scenario: Mapping security in Microsoft Dynamics AX to Analysis Services</a></p></td>
</tr>
<tr class="even">
<td><p>Automate the processing of cubes</p></td>
<td><p>When a cube is processed, the data in the cube is updated with data from the online transaction processing (OLTP) database. Analysis Services provides several options that you can use to automate the processing of cubes.</p></td>
<td><p><a href="automate-the-processing-of-cubes.md">Automate the processing of cubes</a></p></td>
</tr>
<tr class="odd">
<td><p>Create new date dimensions for cubes</p></td>
<td><p>Microsoft Dynamics AX provides a default calendar definition called the Date dimension. You can modify this calendar definition, but changes you make to the Date dimension will affect all cubes that use the Date dimension. Instead you may want to create a new date dimension.</p></td>
<td><p><a href="how-to-create-a-date-dimension-for-a-cube.md">How to: Create a Date Dimension for a Cube</a></p></td>
</tr>
<tr class="even">
<td><p>Add financial dimensions to cubes</p></td>
<td><p>Financial dimensions in Microsoft Dynamics AX help you analyze finance data. You can add financial dimensions to an Analysis Services project. The MainAccount financial dimension is included with Microsoft Dynamics AX, but you can include other financial dimensions in your Analysis Services project if you define additional financial dimensions.</p></td>
<td><p><a href="how-to-add-a-financial-dimension-to-a-cube.md">How to: Add a Financial Dimension to a Cube</a></p></td>
</tr>
</tbody>
</table>


Back to top

![Extend](images/Gg723980.LessColor_Extend(AX.60).png "Extend")

The Business Intelligence infrastructure enables you to generate Unified Dimensional Models (UDMs) by using metadata from the Microsoft Dynamics AX relational data model. You can specify measures and dimensions in the AOT to define an analysis cube. You can create, update, deploy, and configure Analysis Services projects by using the Analysis Services project wizard. You can browse cubes, dimensions, and data source views in SQL Server Business Intelligence Development Studio (BIDS). You can also create or modify dimension usage, key performance indicators (KPIs), and organization hierarchies in BIDS.

## Model analysis cubes

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Details</p></th>
<th><p>Resources</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Create a perspective</p></td>
<td><p>You model a perspective in the AOT. You use a perspective to identify the tables and views that contain the dimension attributes and measures for a cube.</p></td>
<td><p><a href="create-a-perspective-for-a-cube.md">Create a perspective for a cube</a></p>
<p><a href="business-intelligence-properties.md">Business Intelligence Properties</a></p>
<p><a href="walkthrough-creating-a-cube.md">Walkthrough: Creating a cube</a></p></td>
</tr>
<tr class="even">
<td><p>Specify measures</p></td>
<td><p>Measures are numeric values like ‘sales’.</p>
<p>Specify measures at different levels and on different elements using the Business Intelligence properties that appear in the Properties sheet.</p></td>
<td><p><a href="how-to-specify-measures-for-a-cube.md">How to: Specify Measures for a Cube</a></p></td>
</tr>
<tr class="odd">
<td><p>Create dimensions</p></td>
<td><p>Dimensions are the context that help the consumer of measures understand the meaning of those measures, like customer, product, or date.</p>
<p>Specify dimensions at different levels and on different elements using the Business Intelligence properties that appear in the Properties sheet.</p></td>
<td><p><a href="how-to-specify-dimensions-and-attributes-for-a-cube.md">How to: Specify Dimensions and Attributes for a Cube</a></p></td>
</tr>
<tr class="even">
<td><p>Create a hierarchy</p></td>
<td><p>You can define an organization hierarchy to establish a relationship between legal entities. You can use organization hierarchies in cubes to analyze data across virtual companies. If a change is made to the organizational hierarchy, the changes are reflected automatically when cubes are processed.</p></td>
<td><p>How to: Include a Hierarchy in a Cube</p></td>
</tr>
</tbody>
</table>


Back to top

## Work with Analysis Services projects

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Details</p></th>
<th><p>Resources</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Deploy a project</p></td>
<td><p>Deploying an Analysis Services project creates the defined objects in an instance of Analysis Services. Processing the objects in an instance of Analysis Services extracts and then maps data from the data sources defined in the project into the cube objects.</p>
<p>After the cube and dimensions are processed, you can view the data for the objects in the project.</p></td>
<td><p><a href="how-to-deploy-an-existing-sql-server-analysis-services-project.md">Deploy an Existing SQL Server Analysis Services Project</a></p></td>
</tr>
<tr class="even">
<td><p>Configure a project</p></td>
<td><p>If you deploy the default cubes before you modify your license configuration in Microsoft Dynamics AX, you must update the cubes that you deployed by using the Analysis Services project wizard.</p></td>
<td><p><a href="configure-an-existing-sql-server-analysis-services-project.md">Configure an Existing SQL Server Analysis Services Project</a></p>
<p><a href="http://www.youtube.com/watch?v=s6kmwff4qf0">Configure cubes (video)</a></p></td>
</tr>
<tr class="odd">
<td><p>Update a project</p></td>
<td><p>You can update an Analysis Services project without overwriting the core dimensional model object definitions, such as dimensions, dimension attributes, measure groups, measures, and cubes. For example, you can update an Analysis Services project to add new language translations for tables and fields that are referenced by a deployed cube or to update the cube enumeration list.</p>
<p>You can also add new attributes and measures to a perspective and then update a deployed cube by using the Analysis Services project wizard.</p></td>
<td><p><a href="how-to-update-an-existing-sql-server-analysis-services-project.md">Update an Existing SQL Server Analysis Services Project</a></p>
<p><a href="walkthrough-customizing-a-default-cube.md">Walkthrough: Customizing a Default Cube</a></p>
<p><a href="http://www.youtube.com/watch?v=fkx4azj1hn8">Update a cube (video)</a></p>
<p><a href="http://www.youtube.com/watch?v=-gcn3ydrt3m">Update default cubes (video)</a></p></td>
</tr>
<tr class="even">
<td><p>Create a new project</p></td>
<td><p>After you create perspectives that identify the tables and views that contain the measures and dimensions for your cubes, you can generate an Analysis Services project so that you can work with the cubes in SQL Server Business Intelligence Development Studio (BIDS).</p></td>
<td><p><a href="create-a-new-sql-server-analysis-services-project.md">Create a New SQL Server Analysis Services Project</a></p>
<p><a href="walkthrough-creating-a-cube.md">Walkthrough: Creating a cube</a></p>
<p><a href="http://www.youtube.com/watch?v=latzrx75_94">Create a cube (video)</a></p></td>
</tr>
<tr class="odd">
<td><p>Import a project into the AOT</p></td>
<td><p>If you have multiple partitions in Microsoft Dynamics AX, you may want to use Power View to analyze cube data in multiple partitions. Because financial dimensions and calendars may vary between different partitions, in each partition you must provide cubes that contain financial dimensions that are specific to that partition. You can then modify and deploy each partition-specific Analysis Services project.</p></td>
<td><p><a href="import-a-sql-server-analysis-services-project-into-the-aot.md">Import a SQL Server Analysis Services Project into the AOT</a></p></td>
</tr>
</tbody>
</table>


Back to top

![Use](images/Gg723980.LessColor_Use(AX.60).png "Use")

The following tables provide information about how you can use the data from cubes.

## Access cube data in reports

You can use Visual Studio or SQL Server Report Builder to create a report that uses an Analysis Services cube as a data source.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Details</p></th>
<th><p>Resources</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Display cube data in an SSRS report</p></td>
<td><p>You can use a cube as the data source in an SSRS report. Create a reporting project, define an Analysis Services data source, and then create a report that uses that data source.</p></td>
<td><p><a href="walkthrough-displaying-cube-data-in-a-report.md">Walkthrough: Displaying Cube Data in a Report</a></p></td>
</tr>
<tr class="even">
<td><p>Display cube data in a chart control</p></td>
<td><p>A chart control is a user control option to display chart data in Enterprise Portal. A chart control can display data from a report data provider (RDP) class or from a cube. You can use the features in Microsoft Dynamics AX to create and deploy a chart control for Enterprise Portal that displays cube data.</p></td>
<td><p><a href="walkthrough-creating-a-chart-control-with-data-from-an-analysis-services-cube.md">Walkthrough: Creating a Chart Control with Data from an Analysis Services Cube</a></p></td>
</tr>
<tr class="odd">
<td><p>Create a report by using SQL Server Report Builder</p></td>
<td><p>You can use Report Builder, which is a component of Reporting Services, to create a custom report that uses a cube as a data source.</p></td>
<td><p><a href="create-a-report-by-using-sql-server-report-builder-to-connect-to-a-cube.md">Create a report by using SQL Server Report Builder to connect to a cube</a></p></td>
</tr>
</tbody>
</table>


Back to top

## Access cube data by using KPIs

A key performance indicator (KPI) is a collection of calculations used to measure business success. KPIs are used as dashboard metrics that can be displayed in Business Overview web parts in Role Centers to give you quick high-level insight.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Details</p></th>
<th><p>Resources</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Create a KPI</p></td>
<td><p>After you generate a cube, you can use Cube Designer in BIDS (SQL Server Data Tools) to create KPIs.</p>
<p>The calculations that make up a KPI are a combination of Multidimensional Expressions (MDX) and calculated members that are added using Cube Designer. A KPI generally consists of the value achieved, a goal, a status value, and the trend.</p></td>
<td><p><a href="walkthrough-defining-kpis-for-a-cube.md">Walkthrough: Defining KPIs for a Cube</a></p>
<p><a href="http://www.youtube.com/watch?v=-gcn3ydrt3m">Modify a KPI in a default cube (video)</a></p></td>
</tr>
<tr class="even">
<td><p>Display a KPI in a Role Center</p></td>
<td><p>You can display KPIs in reports or in a web part on your Role Center page in Microsoft Dynamics AX or Enterprise Portal.</p>
<p>You can access KPIs that are in the default Analysis Services database from Enterprise Portal. If you have more than one Analysis Services database, you must create an ODC file to access KPIs that are in additional Analysis Services databases from Enterprise Portal.</p></td>
<td><p><a href="walkthrough-displaying-kpis-in-a-role-center.md">Walkthrough: Displaying KPIs in a Role Center</a></p>
<p><a href="how-to-create-an-odc-file-for-a-business-overview-web-part.md">How to: Create an ODC file for a Business Overview Web Part</a></p>
<p><a href="manage-kpis.md">Manage KPIs</a></p></td>
</tr>
</tbody>
</table>


Back to top

## Access data by using Microsoft Excel and Power BI for Office 365

You can use Excel to import cube data and create a pivot table.

Power BI for Office 365 is a self-service BI solution delivered through Excel and Office 365 that provides data discovery, analysis, and visualization capabilities to offer business insights from data in Excel. You can collaborate with others by sharing reports and data sets in Office 365.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Details</p></th>
<th><p>Resources</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Create a report by using Excel</p></td>
<td><p>You can use Microsoft Excel to connect to a cube and create pivot tables and pivot charts.</p></td>
<td><p><a href="create-a-report-by-using-the-excel-data-connection-wizard-to-connect-to-a-cube.md">Create a report by using the Excel data connection wizard to connect to a cube</a></p>
<p><a href="walkthrough-analyzing-cube-data-in-excel.md">Walkthrough: Analyzing Cube Data in Excel</a></p>
<p><a href="http://www.youtube.com/watch?v=nhbdghsyvem">View cube data in Excel (video)</a></p></td>
</tr>
<tr class="even">
<td><p>Create a PowerPivot data mash-up</p></td>
<td><p>You can use Microsoft Dynamics AX 2012 R2 or later and Microsoft Office Excel with PowerPivot to combine data from multiple sources for analysis.</p></td>
<td><p><a href="walkthrough-creating-a-powerpivot-data-mash-up.md">Walkthrough: Creating a PowerPivot Data Mash-up</a></p></td>
</tr>
<tr class="odd">
<td><p>Create a report by using Power View</p></td>
<td><p>Power View is a tool that you can use to create highly-interactive, ad-hoc reports that can use cubes as a data source. To create the report, you create a data source to connect to a cube. Then you can create the Power View report by selecting the fields that you want to display on the report.</p></td>
<td><p><a href="create-a-report-by-using-power-view-to-connect-to-a-cube.md">Create a report by using Power View to connect to a cube</a></p></td>
</tr>
<tr class="even">
<td><p>Create an Analyze Data button on a list page to analyze cube data</p></td>
<td><p>You can use Power View to create interactive ad-hoc reports in Microsoft Dynamics AX. Several list pages have an Analyze Data button that launches the Power View report designer. The Power View report designer connects to a cube and allows you to drag and drop fields for quick analysis.</p></td>
<td><p><a href="walkthrough-creating-an-analyze-data-button-on-a-list-page.md">Walkthrough: Creating an Analyze Data Button on a List Page</a></p>
<p><a href="how-to-create-a-role-center.md">How to: Create a Role Center</a></p></td>
</tr>
<tr class="odd">
<td><p>Create a data mash-up by using Power Query and share it to a BI sites portal</p></td>
<td><p>Power Query provides a familiar and intuitive experience for finding and connect to data from within Excel. You can use it to combine and transform data so that it can be analyzed and visualized for deeper insight. Power Query supports a wide variety of data sources including relational, structured and semi-structured, OData, from the Web, Hadoop, as well as Data Search capabilities that provide users with a search experience for data, returning relevant data sets from across the enterprise and from external sources.</p>
<p>In this walkthrough, you create an OData feed to import Microsoft Dynamics AX data and then combine that data with information from Wikipedia.</p></td>
<td><p><a href="walkthrough-creating-a-data-mash-up-by-using-power-query.md">Walkthrough: Creating a data mash-up by using Power Query</a></p></td>
</tr>
</tbody>
</table>


Back to top

![Troubleshoot](images/Gg723980.LessColor_Troubleshoot(AX.60).png "Troubleshoot")

Complete the follow tasks to troubleshoot issues that you may encounter when you work with cubes.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Details</p></th>
<th><p>Resources</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Troubleshoot setup</p></td>
<td><p>Find possible solutions to common issues that may occur when you run the Microsoft Dynamics AX Setup wizard to configure Analysis Services.</p></td>
<td><p><a href="troubleshoot-issues-when-running-the-setup-wizard-to-configure-analysis-services.md">Troubleshoot issues when running the Setup wizard to configure Analysis Services</a></p></td>
</tr>
<tr class="even">
<td><p>Troubleshoot cubes and KPIs</p></td>
<td><p>Find possible solutions to common issues that may occur when you work with cubes and KPIs.</p></td>
<td><p><a href="troubleshoot-issues-with-cubes-and-key-performance-indicators-kpis.md">Troubleshoot issues with cubes and key performance indicators (KPIs)</a></p></td>
</tr>
</tbody>
</table>


Back to top

![View technical reference](images/Gg723980.LessColor_ViewTechRef(AX.60).png "View technical reference")

The following table provides links to technical reference information for cubes.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Details</p></th>
<th><p>Resources</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>View cube and KPI reference content</p></td>
<td><p>View detailed information about the measures, associated dimensions, and KPIs in each cube.</p></td>
<td><p><a href="cube-and-kpi-reference-for-microsoft-dynamics-ax-2012-and-microsoft-dynamics-ax-2012-feature-pack.md">Cube and KPI reference for Microsoft Dynamics AX 2012 and Microsoft Dynamics AX 2012 Feature Pack</a></p>
<p><a href="cube-and-kpi-reference-for-microsoft-dynamics-ax-2012-r2-and-r3.md">Cube and KPI reference for Microsoft Dynamics AX 2012 R2 and R3</a></p></td>
</tr>
</tbody>
</table>


Back to top

  


