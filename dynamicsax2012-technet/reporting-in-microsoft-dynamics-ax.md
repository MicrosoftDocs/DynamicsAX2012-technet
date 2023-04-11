---
title: Reporting in Microsoft Dynamics AX
TOCTitle: Reporting
ms:assetid: 6728b08f-6618-4719-a333-ec7f5bec25c2
ms:mtpsurl: https://technet.microsoft.com/library/Ee873263(v=AX.60)
ms:contentKeyID: 28119371
author: tonyafehr
ms.date: 12/16/2015
mtps_version: v=AX.60
---

# Reporting in Microsoft Dynamics AX 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Microsoft SQL Server Reporting Services (SSRS) is the primary reporting platform for Microsoft Dynamics AX. The default, predefined reports that are provided with Microsoft Dynamics AX run on the Reporting Services platform.

This topic guides you through the process of installing, deploying, and using these reports. This topic also provides information about how to create custom reports.

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
<p><a href="https://blogs.msdn.com/b/dynamicsaxbi/">Microsoft Dynamics AX Business Intelligence</a> (blog)</p>
<p><a href="http://www.youtube.com/user/dynamicsaxbi">Microsoft Dynamics AX BI videos channel</a> (videos)</p>
<p><a href="analytics-in-microsoft-dynamics-ax.md">Analytics in Microsoft Dynamics AX</a> (articles)</p></td>
</tr>
</tbody>
</table>


![Get started](images/Gg723980.LessColor_GetStarted(AX.60).png "Get started")

The following table lists tasks that you can complete to learn more about Reporting Services and how it integrates with Microsoft Dynamics AX.

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
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Learn about the new reporting features of Microsoft Dynamics AX</p></td>
<td><p>Several features have been added to Microsoft Dynamics AX 2012 releases to help you install the Reporting Services extensions and deploy reports. For example:</p>
<ul>
<li><p><strong>In cumulative update 7 for Microsoft Dynamics AX 2012 R2:</strong> A Windows PowerShell command is available in cumulative update 7 for Microsoft Dynamics AX 2012 R2 that automates the process of integrating multiple Reporting Services instances with Microsoft Dynamics AX.</p></li>
<li><p><strong>In Microsoft Dynamics AX 2012 R2:</strong> Support for report servers that run in SharePoint integrated mode was added.</p></li>
</ul></td>
<td><p><a href="what-s-new-reporting.md">What's new: Reporting</a></p></td>
</tr>
<tr class="even">
<td><p>Become familiar with Reporting Services and plan your implementation</p></td>
<td><p>Reporting Services is the primary reporting platform for Microsoft Dynamics AX. The default, predefined reports that are provided with Microsoft Dynamics AX run on the Reporting Services platform.</p></td>
<td><p><a href="reporting-architecture.md">Reporting architecture</a></p>
<p><a href="overview-of-reporting-services.md">Overview of Reporting Services</a></p>
<p><a href="planning-for-reporting-in-microsoft-dynamics-ax.md">Planning for reporting in Microsoft Dynamics AX</a></p></td>
</tr>
<tr class="odd">
<td><p>Determine what other reporting tools you may want to use</p></td>
<td><p>Although Reporting Services is the primary reporting platform for Microsoft Dynamics AX, there are other reporting tools that you should use, as well. For example, we recommend that you use Management Reporter to create financial statements.</p></td>
<td><p><a href="types-of-reports.md">Types of reports</a></p>
<p><a href="https://www.microsoft.com/en-us/download/details.aspx?id=38410">Business Intelligence Capabilities and Tools white paper</a></p>
<p><a href="https://technet.microsoft.com/library/dn435963.aspx">Management Reporter for Microsoft Dynamics ERP</a></p></td>
</tr>
</tbody>
</table>


![Install and deploy](images/Ee873263.LessColor_InstallAndDeploy(AX.60).png "Install and deploy")

The following sections explain how to install and deploy reports and how to upgrade reports from Microsoft Dynamics AX 2009 to Microsoft Dynamics AX 2012.

## Install and deploy reports

Complete the tasks in the following table to integrate Microsoft Dynamics AX and Reporting Services and to deploy the reports that are included with Microsoft Dynamics AX.

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
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Verify permissions</p></td>
<td><p>To install the Reporting Services extensions, you must run the Microsoft Dynamics AX Setup wizard. Verify that you have the required permissions to run the wizard.</p></td>
<td><p><a href="verify-that-you-have-the-required-permissions-for-installation.md">Verify that you have the required permissions for installation</a></p></td>
</tr>
<tr class="even">
<td><p>Assign system service accounts to the appropriate Active Directory groups</p></td>
<td><p>Identify which accounts are used for the following purposes:</p>
<ul>
<li><p>The account used to run the Microsoft Dynamics AX Application Object Server (AOS)</p></li>
<li><p>The account used as the Business Connector proxy</p></li>
</ul>
<p>Assign the accounts listed above to the following Active Directory groups on the domain server:</p>
<ul>
<li><p>Windows Authorization Access group</p></li>
<li><p>Pre-Windows 2000 Compatibility Access group</p></li>
</ul></td>
<td></td>
</tr>
<tr class="odd">
<td><p>Install prerequisites</p></td>
<td><p>On the computer where Reporting Services is installed, or where you plan to install Reporting Services, run the prerequisite validation utility to verify that system requirements have been met.</p></td>
<td><p><a href="check-prerequisites.md">Check prerequisites</a></p>
<p><a href="https://go.microsoft.com/fwlink/?linkid=165377">System requirements</a></p></td>
</tr>
<tr class="even">
<td><p>Configure Reporting Services</p></td>
<td><p>Configure Reporting Services for use with Microsoft Dynamics AX. The steps you must follow vary depending on whether you installed Reporting Services in native mode or SharePoint integrated mode.</p></td>
<td><p><a href="before-you-install-the-reporting-services-extensions.md">Before you install the Reporting Services extensions</a></p></td>
</tr>
<tr class="odd">
<td><p>Install the Reporting Services extensions</p></td>
<td><p>Run the Microsoft Dynamics AX Setup wizard on your report server to install the Reporting Services extensions.</p></td>
<td><p><a href="install-the-reporting-services-extensions.md">Install the Reporting Services extensions</a></p></td>
</tr>
<tr class="even">
<td><p>Deploy reports</p></td>
<td><div class="alert">

> [!NOTE]
> <P>If you are using Microsoft Dynamics AX 2012 R2—and—Reporting Services is running in SharePoint integrated mode, then you must create a document library in SharePoint to store your reports. Complete this procedure before you deploy the default reports that are included with Microsoft Dynamics AX.</P>


</div>
<p>Microsoft Dynamics AX includes many default reports that you must deploy. If you did not deploy the reports when you installed the Reporting Services extensions, you can deploy them by using Windows PowerShell.</p></td>
<td><p><a href="create-a-document-library-to-store-reports.md">Create a document library to store reports</a></p>
<p><a href="deploy-the-default-reports.md">Deploy the default reports</a></p></td>
</tr>
<tr class="odd">
<td><p>Deploy language-specific versions of a report</p></td>
<td><p>Typically, when you deploy a report, one version of the report is deployed. This version can then be rendered automatically in every language that is supported by Microsoft Dynamics AX. However, you can configure Microsoft Dynamics AX so that language-specific versions of a report are deployed. A language-specific version of a report is rendered more quickly.</p></td>
<td><p><a href="deploy-language-specific-versions-of-a-report.md">Deploy language-specific versions of a report</a></p></td>
</tr>
<tr class="even">
<td><p>Integrate additional instances of Reporting Services—that run on the same computer—with Microsoft Dynamics AX</p></td>
<td><p>You can install multiple instances of Reporting Services on the same computer. In this kind of deployment environment, each instance of Reporting Services is connected to an independent Microsoft Dynamics AX installation. You may want to install multiple instances of Reporting Services on the same computer for the following reasons:</p>
<ul>
<li><p>To support development and production installations of Microsoft Dynamics AX</p></li>
<li><p>To support multiple production installations of Microsoft Dynamics AX</p></li>
</ul></td>
<td><p><a href="install-multiple-instances-of-reporting-services-on-the-same-computer-for-use-with-microsoft-dynamics-ax.md">Install multiple instances of Reporting Services on the same computer (for use with Microsoft Dynamics AX)</a></p></td>
</tr>
</tbody>
</table>


## Upgrade reports

The following table provides information about how to upgrade reports in Microsoft Dynamics AX.

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
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Upgrade reports</p></td>
<td><p>When you upgrade from Microsoft Dynamics AX 2009, existing reports are copied to the AX 2012 system, but they are not upgraded. AX 2012 provides hundreds of default, predefined reports that you can deploy and customize. We recommend that you use these reports as templates and customize them to meet your requirements.</p></td>
<td><p><a href="report-upgrade.md">Report Upgrade</a></p>
<p><a href="report-project-upgrade.md">Report Project Upgrade</a></p>
<p><a href="guidance-when-upgrading-reports.md">Guidance when Upgrading Reports</a></p>
<p><a href="mapping-microsoft-dynamics-ax-2009-reports-to-the-microsoft-dynamics-ax-2012-version.md">Mapping Microsoft Dynamics AX 2009 Reports to the Microsoft Dynamics AX 2012 Version</a></p>
<p><a href="deprecated-microsoft-dynamics-ax-2009-reports-in-microsoft-dynamics-ax-2012.md">Deprecated Microsoft Dynamics AX 2009 Reports in Microsoft Dynamics AX 2012</a></p></td>
</tr>
</tbody>
</table>


![Configure](images/Gg723980.LessColor_Configure(AX.60).png "Configure")

After you have deployed the reports, complete the following tasks to make them available to users.

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
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Grant users access to reports</p></td>
<td><p>Grant users access to reports. The steps you must follow vary depending on whether you installed Reporting Services in native mode or SharePoint integrated mode.</p></td>
<td><p><a href="grant-users-access-to-reports.md">Grant users access to reports</a></p></td>
</tr>
<tr class="even">
<td><p>Prepare the report server for use each day</p></td>
<td><p>Reporting Services periodically restarts, and each restart clears the Reporting Services cache. After the cache has been cleared, it may take some time for the next report that is run to display. To minimize the effect of Reporting Services restarts, a new class that is named SRSReportServerWarmup is included with cumulative update 7 for Microsoft Dynamics AX 2012 R2. When the SRSReportServerWarmup class runs, it prepares the report server for use.</p></td>
<td><p><a href="run-the-srsreportserverwarmup-class.md">Run the SRSReportServerWarmup class</a></p></td>
</tr>
</tbody>
</table>


![Extend](images/Gg723980.LessColor_Extend(AX.60).png "Extend")

You can use Microsoft Visual Studio to customize existing reports, develop new reports, and integrate those reports with Microsoft Dynamics AX.

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
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Customize a report which is defined in a model project included with Microsoft Dynamics AX.</p></td>
<td><p>Model projects in Microsoft Dynamics AX adhere to layered development in the MorphX development environment. This allows model projects to be customized, upgraded, and patched using the built-in layering support. You can see those changes applied in Microsoft Dynamics AX.</p></td>
<td><p><a href="walkthrough-customizing-existing-microsoft-dynamics-ax-reports.md">Walkthrough: Customizing Existing Microsoft Dynamics AX Reports</a></p></td>
</tr>
<tr class="even">
<td><p>Create a new auto-design reporting project and add it to the AOT.</p></td>
<td><p>To retrieve data for an auto-design reporting project you will use a query that is defined in the AOT within the Microsoft Dynamics AX development environment. Once the project is created, you can modify the look of the report using layout and style templates and add interactive features like grouping, sort order, and document maps.</p></td>
<td><p><a href="walkthrough-creating-an-auto-design-report.md">Walkthrough: Creating an Auto Design Report</a></p></td>
</tr>
<tr class="odd">
<td><p>Integrate a report into Microsoft Dynamics AX.</p></td>
<td><p>Once you have created a reporting project, you integrate the report into Microsoft Dynamics AX. For example, after the report is in Microsoft Dynamics AX, you can create an output menu item for the report and display the report on a menu within the application.</p></td>
<td><p><a href="walkthrough-integrating-new-reports-into-microsoft-dynamics-ax.md">Walkthrough: Integrating New Reports into Microsoft Dynamics AX</a></p></td>
</tr>
<tr class="even">
<td><p>Create a drillthrough repor.t</p></td>
<td><p>A drillthrough report is a report that a user opens by clicking a linked item in another report. It allows users to drill through to additional data.</p></td>
<td><p><a href="walkthrough-creating-a-drillthrough-report.md">Walkthrough: Creating a Drillthrough Report</a></p></td>
</tr>
<tr class="odd">
<td><p>Create a report from an external data source.</p></td>
<td><p>A data source is a facility for accessing data. You can use the predefined Dynamics AX data source, which connects to the Microsoft Dynamics AX application database. Or, you can define an external data source to retrieve data from a different location. In your report model, you will define an external data source that specifies the connection information for the database so that you can retrieve data from that database to display in your report.</p></td>
<td><p><a href="walkthrough-creating-a-report-from-an-external-data-source.md">Walkthrough: Creating a Report from an External Data Source</a></p></td>
</tr>
<tr class="even">
<td><p>Use a report data provider (RDP) class with business logic to process data and then display the outcome of the business logic on a report.</p></td>
<td><p>An RDP class is an X++ class that is used to access and process data for a Reporting Services report. The options for a data source type for a Microsoft Dynamics AX report are query, business logic, and RDP. An RDP class is an appropriate data source type when you cannot query directly for the data you want to render on a report, or the data to be processed and displayed is from Microsoft Dynamics AX.</p></td>
<td><p><a href="walkthrough-creating-a-report-bound-to-a-report-data-provider-class-x-business-logic.md">Walkthrough: Creating a Report Bound to a Report Data Provider Class (X++ Business Logic)</a></p></td>
</tr>
<tr class="odd">
<td><p>Add parameters to a report to allow users to filter the data that displays in the report.</p></td>
<td><p>For example, you can add a parameter and a filter that uses the parameter to allow users to select a customer for which to display data. Then, you can add parameters that will be used to determine whether to display the phone and fax numbers for the customers in the report.</p></td>
<td><p><a href="walkthrough-creating-a-report-with-parameters.md">Walkthrough: Creating a Report with Parameters</a></p></td>
</tr>
<tr class="even">
<td><p>Create a report to display customer transaction data in a matrix data region.</p></td>
<td><p>A matrix data region displays data in a two-dimensional grid of columns and rows that intersect at specific data points. When defining a matrix data region, you can specify column and row groupings. The data that appears in the detail cells are aggregates based on the intersections of columns and rows.</p></td>
<td><p><a href="walkthrough-creating-a-matrix-report.md">Walkthrough: Creating a Matrix Report</a></p></td>
</tr>
<tr class="odd">
<td><p>Create a report to display customer transaction data in a column chart.</p></td>
<td><p>A chart provides a graphical representation of data. Displaying data in a chart makes it easy for users to see comparisons, patterns, and trends in the data.</p></td>
<td><p><a href="walkthrough-using-ax-enum-provider-in-a-column-chart-report.md">Walkthrough: Using AX Enum Provider in a Column Chart Report</a></p></td>
</tr>
<tr class="even">
<td><p>Create a precision design for a report using SQL Report Designer.</p></td>
<td><p>You can create a precision design report to display the data returned by the queries that you created in Microsoft Dynamics AX. To do this, you will first define datasets for the report. Then, you will configure the parameters that are created for the datasets. Finally, you will use SQL Report Designer to define the report layout.</p></td>
<td><p><a href="walkthrough-referencing-a-report-parameter-from-multiple-datasets-in-a-precision-design-report.md">Walkthrough: Referencing a Report Parameter from Multiple Datasets in a Precision Design Report</a></p></td>
</tr>
<tr class="odd">
<td><p>Create a report that is bound to date effective data.</p></td>
<td><p>Date effective data is valid time state data for which changes must be tracked at different points in time. On a table in the AOT, you can set the ValidTimeStateFieldType property to make it a valid time state table. Setting this property causes the system to automatically add the ValidFrom and ValidTo columns which track a date range for each row. Reports that are bound to valid time state data will provide a parameter for the date range or a specific date on the parameter form when you run the report.</p></td>
<td><p><a href="walkthrough-creating-a-report-bound-to-date-effective-data.md">Walkthrough: Creating a Report Bound to Date Effective Data</a></p></td>
</tr>
<tr class="even">
<td><p>Create a report that uses dimensions</p></td>
<td><p>Dimensions are additional classifications defined in a table for financial, product, and cost attributes. You will can create a report that displays a dimension string, dimension attributes, and a report parameter based on a dimension. When you run the report, you can filter the report by the dimension.</p></td>
<td><p><span id="b692d6ad_bcad_41fa_a74f_2ab3bb7030f1"></span> <a href="walkthrough-creating-a-report-bound-to-a-dimension-data-source.md">Walkthrough: Creating a Report Bound to a Dimension Data Source</a></p></td>
</tr>
</tbody>
</table>


![Use](images/Gg723980.LessColor_Use(AX.60).png "Use")

The following sections provide information about how business users, such as CFOs and accounting managers, can create and use reports.

## Use the Reporting Services reports that are provided with Microsoft Dynamics AX

End users in your organization can use the information in the following table to work with the default reports that are provided with Microsoft Dynamics AX.

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
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Print or email a report</p></td>
<td><p>Microsoft Dynamics AX includes hundreds of preconfigured reports that you can use to view and analyze business data. The linked topic explains how to print or email a report.</p></td>
<td><p><a href="print-or-email-a-report.md">Print or email a report</a></p></td>
</tr>
<tr class="even">
<td><p>Print or email a report on a recurring basis</p></td>
<td><p>Microsoft Dynamics AX includes hundreds of preconfigured reports that you can use to view and analyze business data. The linked topic explains how to configure Microsoft Dynamics AX to automatically print a report for you on a recurring basis. For example, Microsoft Dynamics AX can send a specific report to you and your team members every Monday morning by email.</p></td>
<td><p><a href="print-or-email-a-report-on-a-recurring-basis.md">Print or email a report on a recurring basis</a></p></td>
</tr>
<tr class="odd">
<td><p>Print or email a report during off-peak hours</p></td>
<td><p>Occasionally, you may have to print an especially long report, such as a report that contains hundreds of rows of data. In this case, it may be best to print the report during off-peak hours, when few users are logged on to Microsoft Dynamics AX. The linked topic explains how to schedule a report to be printed during off-peak hours.</p></td>
<td><p><a href="print-or-email-a-report-during-off-peak-hours.md">Print or email a report during off-peak hours</a></p></td>
</tr>
<tr class="even">
<td><p>Print a report from the archive</p></td>
<td><p>If you saved a report to the print archive, you can use the linked topic to print the report from the archive.</p></td>
<td><p><a href="print-a-report-from-the-archive.md">Print a report from the archive</a></p></td>
</tr>
<tr class="odd">
<td><p>Filter the data on a report</p></td>
<td><p>By filtering the data that is displayed on a report, you can view only the data that is important to you. The linked topic shows how to filter the data on the Customers report. You can modify this procedure to filter the data on the report that you are working with.</p></td>
<td><p><a href="filter-the-data-on-a-report.md">Filter the data on a report</a></p></td>
</tr>
<tr class="even">
<td><p>Sort the data on a report</p></td>
<td><p>You can sort the data that is displayed on a report. The linked topic shows how to sort the data on the Customers report. You can modify this procedure to sort the data on the report that you are working with.</p></td>
<td><p><a href="sort-the-data-on-a-report.md">Sort the data on a report</a></p></td>
</tr>
</tbody>
</table>


## Create a custom report

End users in your organization can use the information in the following table to create the custom reports they need.

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
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Create a report by using the Microsoft Dynamics AX auto-report wizard</p></td>
<td><p>Auto-reports are preconfigured reports that you can generate by clicking <strong>File</strong> &gt; <strong>Print</strong> &gt; <strong>Print</strong> in a Microsoft Dynamics AX form. You can quickly generate an auto-report for use once, or you can create and save a custom auto-report that can be reused later.</p></td>
<td><p><a href="create-a-report-by-using-the-microsoft-dynamics-ax-auto-report-wizard.md">Create a report by using the Microsoft Dynamics AX auto-report wizard</a></p></td>
</tr>
<tr class="even">
<td><p>Create a report by using Excel</p></td>
<td><p>You can use Microsoft Excel to create a custom report that uses a Microsoft SQL Server Analysis Services cube as a data source.</p></td>
<td><p><a href="create-a-report-by-using-the-excel-data-connection-wizard-to-connect-to-a-cube.md">Create a report by using the Excel data connection wizard to connect to a cube</a></p></td>
</tr>
<tr class="odd">
<td><p>Create a report by using SQL Server Report Builder</p></td>
<td><p>You can use Report Builder, which is a component of Reporting Services, to create a custom report that uses an analysis cube as a data source.</p></td>
<td><p><a href="create-a-report-by-using-sql-server-report-builder-to-connect-to-a-cube.md">Create a report by using SQL Server Report Builder to connect to a cube</a></p></td>
</tr>
<tr class="even">
<td><p>Create a report by using Power View</p></td>
<td><p>Power View is a tool that you can use to create highly-interactive, ad-hoc reports that use analysis cubes as a data source.</p></td>
<td><p><a href="create-a-report-by-using-power-view-to-connect-to-a-cube.md">Create a report by using Power View to connect to a cube</a></p></td>
</tr>
</tbody>
</table>


![Troubleshoot](images/Gg723980.LessColor_Troubleshoot(AX.60).png "Troubleshoot")

The following topics explain how to troubleshoot issues that you may encounter when you work with reports.

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
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Troubleshoot issues with Reporting Services reports</p></td>
<td><p>Find possible solutions to common issues that may occur when you install, deploy, or use Reporting Services reports.</p></td>
<td><p><a href="troubleshoot-issues-when-running-the-setup-wizard-to-install-the-reporting-services-extensions.md">Troubleshoot issues when running the Setup wizard to install the Reporting Services extensions</a></p>
<p><a href="troubleshooting-report-definition-issues.md">Troubleshooting Report Definition Issues</a></p>
<p><a href="troubleshoot-report-deployment-issues.md">Troubleshoot Report Deployment Issues</a></p>
<p><a href="troubleshoot-issues-with-printing-and-emailing-reports.md">Troubleshoot Issues with Printing and Emailing Reports</a></p>
<p><a href="how-to-configure-the-debugger-to-debug-a-report-data-provider-class.md">How to: Configure the Debugger to Debug a Report Data Provider Class</a></p>
<p><a href="tips-to-help-prevent-long-running-reports-from-timing-out.md">Tips to help prevent long-running reports from timing out</a></p>
<p><a href="https://blogs.msdn.com/b/axsupport/archive/2015/01/08/ssrs-report.aspx">SSRS report tips to adjust alignment for pre-formatted print stock (i.e. 1099-MISC form)</a></p>
<p><a href="troubleshooting-system-services.md">Troubleshooting System Services</a></p></td>
</tr>
</tbody>
</table>


![View technical reference](images/Gg723980.LessColor_ViewTechRef(AX.60).png "View technical reference")

The following table provides links to technical reference information for reports.

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
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>View the Reporting Services report catalog</p></td>
<td><p>The Report Catalog for Microsoft Dynamics AX 2012 describes the Reporting Services reports that are provided with Microsoft Dynamics AX 2012.</p></td>
<td><p><a href="report-catalog-for-microsoft-dynamics-ax.md">Report catalog for Microsoft Dynamics AX</a></p></td>
</tr>
</tbody>
</table>

  


