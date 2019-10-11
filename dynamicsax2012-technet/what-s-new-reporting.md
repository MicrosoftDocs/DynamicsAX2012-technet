---
title: "What's new: Reporting"
TOCTitle: Reporting
ms:assetid: f09d8fb3-b3eb-48e2-9285-22217a06037c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn527264(v=AX.60)
ms:contentKeyID: 59623392
ms.date: 08/20/2014
mtps_version: v=AX.60
---

# What's new: Reporting 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Microsoft SQL Server Reporting Services is now the primary reporting platform for Microsoft Dynamics AX. The default, predefined reports that are provided with Microsoft Dynamics AX run on the Reporting Services platform.

This article describes the new reporting features of Microsoft Dynamics AX.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><img src="images/Dn507140.TopicIcons_WhatsNew(AX.60).png" title="What&#39;s new" alt="What&#39;s new" />
<p>New features in cumulative update 7 for Microsoft Dynamics AX 2012 R2</p>
<p>New features in Microsoft Dynamics AX 2012 R2</p>
<p>New features in Microsoft Dynamics AX 2012</p></td>
<td><img src="images/Dn507140.TopicIcons_Resources(AX.60).png" title="Resources" alt="Resources" />
<p><a href="ncdf/new-changed-and-deprecated-features-for-ax-2012.md">New, Changed, and Deprecated Features for AX 2012</a> (articles)</p>
<p><a href="what-s-new-analytics.md">What's new: Analytics</a> (article)</p></td>
</tr>
</tbody>
</table>


## New features in cumulative update 7 for Microsoft Dynamics AX 2012 R2

The following reporting features have been added in cumulative update 7.

## Windows PowerShell command for integrating multiple Reporting Services instances with Microsoft Dynamics AX

If multiple instances of Reporting Services run on the same computer, and you want to integrate those instances with Microsoft Dynamics AX, a Windows PowerShell command is now available that automates the process.

For example, assume that you have a report server that hosts three Reporting Services instances. To integrate these instances with Microsoft Dynamics AX, you must follow these steps:

1.  Integrate the first Reporting Services instance with Microsoft Dynamics AX. To do this, run the Microsoft Dynamics AX setup wizard to install the reporting extensions, and then deploy the reports that are included with Microsoft Dynamics AX. For more information, see [Checklist: Install the Reporting Services extensions and deploy reports](checklist-install-the-reporting-services-extensions-and-deploy-reports.md).

2.  Integrate the second Reporting Services instance with Microsoft Dynamics AX by running the Install-AXReportInstanceExtensions Windows PowerShell command.

3.  Integrate the third Reporting Services instance with Microsoft Dynamics AX by running the Install-AXReportInstanceExtensions command.

The following diagram summarizes this process.

![Multiple SSRS instances on one server](images/Dn527264.MultiSSRSInstances_CU7(AX.60).gif "Multiple SSRS instances on one server")

For information about how to run the Install-AXReportInstanceExtensions command, see [Install multiple instances of Reporting Services on the same computer (for use with Microsoft Dynamics AX)](install-multiple-instances-of-reporting-services-on-the-same-computer-for-use-with-microsoft-dynamics-ax.md).

## New class that improves the performance of the report server

Microsoft SQL Server Reporting Services periodically restarts, and each restart clears the Reporting Services cache. After the cache has been cleared, it may take some time for the next report that is run to display. To minimize the effect of Reporting Services restarts, a new class that is named SRSReportServerWarmup is included with cumulative update 7 for Microsoft Dynamics AX 2012 R2. When the SRSReportServerWarmup class runs, it prepares the report server for use by performing the following tasks:

1.  Loads Microsoft Dynamics AX business logic assemblies

2.  Connects to Reporting Services

3.  Runs a sample report that is named SRSReportServerWarmup

As a best practice, you should schedule the batch job that runs the SRSReportServerWarmup class to run immediately after Reporting Services restarts. For more information about how to configure the batch job, see [Run the SRSReportServerWarmup class](run-the-srsreportserverwarmup-class.md).

## Ability to email reports to specific people by using tokens

In cumulative update 7, you can email reports to specific people by using tokens. When you use this feature, you don’t have to enter the email addresses of all recipients. Instead, you just enter a token. The token instructs Microsoft Dynamics AX to retrieve the appropriate email addresses from worker, customer, or vendor records.

You email reports to the following people:

  - Workers in your organization who have a specific job title
    
    You can use the **@\<Job Title\>@** token to email reports to workers in your organization who have a specific job title. For example, suppose that you want to email the **Recruitment Projects** report to all workers in your organization who have the job title of **Staffing Specialist**. In this scenario, you would enter the **@Staffing Specialist@** token in the **To** field when you email the report.
    
    The **@Staffing Specialist@** token instructs Microsoft Dynamics AX to perform the following tasks:
    
    1.  Retrieve a list of all workers who have the **Staffing Specialist** job title.
    
    2.  Retrieve the primary email address for each worker who is identified in step 1.
    
    3.  Email the **Recruitment Projects** report to each worker who is identified in step 1 by using the email addresses that are retrieved in step 2.

  - Customers and vendors who have a specific purpose
    
    You can email reports to customers and vendors who have a specific purpose by using the **@\<Purpose\>@** token. In Microsoft Dynamics AX, contact information (such as email addresses) for customers and vendors has a purpose associated with it. For example, a customer may have an email address where the purpose is *Billing* and another email address where the purpose is *Delivery*. Now suppose that you want to email a sales order to a customer. In this scenario, you would enter the following token in the **To** field when emailing the sales order: **\@Billing\@**
    
    The **\@Billing\@** token instructs Microsoft Dynamics AX to perform the following tasks:
    
    1.  Identify the customer that this sales order must be sent to.
    
    2.  Retrieve a list of email addresses for the customer that have the **Billing** purpose.
    
    3.  Send the sales order to the customer by using the email addresses that are retrieved in step 2.

For more information about how to insert tokens when you send a report as email, see [Print or email a report](print-or-email-a-report.md).

Developers can customize the functionality of the tokens by using the [SysExtension](https://technet.microsoft.com/en-us/library/gg959544\(v=ax.60\)) framework. For example, you can develop an additional customization to retrieve titles from an external address book and send a report to the list of addresses that is retrieved externally.

You can also customize tokens to specify other print destinations by using print management. For example, you can use tokens to specify a printer based on location. In this scenario, a token such as **@wh printer@** can be used to specify a warehouse printer.

For more information about how to extend tokens, see [Customizing tokens for emailing and printing reports](customizing-tokens-for-emailing-and-printing-reports.md).

## New methods for advanced printer properties

The [SRSPrintDestinationSettings](https://technet.microsoft.com/en-us/library/gg938492\(v=ax.60\)) class contains new methods that let you choose the following printer properties:

  - Print orientation (portrait or landscape)

  - Number of copies to print

  - Target printer tray

  - Collation of printed documents

## Updated Compare Tool for Reporting Services reports

The [Compare Tool](https://technet.microsoft.com/en-us/library/aa849010\(v=ax.60\)) has been updated to support comparison of two Reporting Services report designs.

## Management Reporter now installed with Microsoft Dynamics AX

Management Reporter is a tool that you should use to create financial reports. Management Reporter can now be installed when you install Microsoft Dynamics AX. For installation instructions, see [Install Management Reporter server components](install-management-reporter-server-components.md).

For more information about how to configure and use Management Reporter, see the Management Reporter [configuration guide](http://www.microsoft.com/en-us/download/details.aspx?id=5916) and [blog](http://blogs.msdn.com/b/dynamicscpm/).

## New features in Microsoft Dynamics AX 2012 R2

The following reporting features have been added in AX 2012 R2.

## Support for data partitions

An installation of AX 2012 R2 can consist of multiple data partitions. One report server can support all the data partitions in an AX 2012 R2 installation. For more information about data partitions, see [Data partitioning architecture](data-partitioning-architecture.md).

## Support for report servers that run in SharePoint integrated mode

Reporting Services can be installed in either native mode or SharePoint integrated mode. Report servers that run in SharePoint integrated mode are supported by AX 2012 R2.

In SharePoint integrated mode, a report server runs in a SharePoint server farm. Reports are managed and viewed from SharePoint document libraries. For more information, see [Overview of Reporting Services](overview-of-reporting-services.md).

## Support for Power View

Power View is a tool that you can use to create highly-interactive, custom reports. For example, suppose that you want to create a report that shows sales amounts for your retail stores. In this scenario, you can open Power View, connect to the Retail cube, select the fields to display on the report, and then display the report on a Role Center page in Microsoft Dynamics AX.


> [!NOTE]
> <P>If Microsoft SQL Server Analysis Services and Enterprise Portal are installed on different computers, you must use Kerberos security to create Power View reports.</P>



For more information about how to create Power View reports, see [Create a report by using Power View to connect to a cube](create-a-report-by-using-power-view-to-connect-to-a-cube.md).

## New features in Microsoft Dynamics AX 2012

The following reporting features have been added in AX 2012.

## Simplified installation

In AX 2012, the Setup wizard has been updated to simplify the process of installing the Reporting Services extensions. When you install the Reporting Services extensions, the Setup wizard will:

1.  Verify that prerequisite software has been installed on the server that runs Reporting Services. For more information about the prerequisite software, see the [system requirements webpage](http://go.microsoft.com/fwlink/?linkid=165377).

2.  Prompt you to select an instance of Reporting Services. The extensions that you install will be configured to use this instance. For more information, see [Install Reporting Services extensions for Microsoft Dynamics AX](install-reporting-services-extensions-for-microsoft-dynamics-ax.md).

3.  Enable you to deploy the default reports that are included with Microsoft Dynamics AX.

## Upgrade information

When you upgrade from Microsoft Dynamics AX 2009, existing reports are copied to the AX 2012 system, but they are not upgraded. AX 2012 provides hundreds of default, predefined reports that you can deploy and customize. We recommend that you use these reports as templates and customize them to meet your requirements. For more information, see [Upgrading Reports](upgrading-reports.md).

## Improvements to the report deployment process

The process of deploying reports has changed in the following ways.

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
<th><p>Where can I find more information?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Deploy reports by using Windows PowerShell.</p></td>
<td><p>The <strong>Reporting Project Deployment</strong> form in Microsoft Dynamics AX is used to deploy reports.</p></td>
<td><p>Windows PowerShell is used to deploy reports.</p></td>
<td><p>It’s easier to deploy reports.</p></td>
<td><p><a href="deploy-the-default-reports.md">Deploy the default reports</a></p></td>
</tr>
<tr class="even">
<td><p>Deploy reports in multiple languages.</p></td>
<td><p>When a single report is deployed, 42 versions of that report are deployed, one version for every language that is supported by Microsoft Dynamics AX.</p>
<p>For example, when you deploy the <strong>Sales Order</strong> report, 42 versions of that report are deployed: one for English, one for French, one for German, and so on.</p></td>
<td><p>When you deploy a report, one version of the report is deployed. That version is rendered into every language that is supported by Microsoft Dynamics AX.</p></td>
<td><p>It’s easier and faster to deploy reports.</p></td>
<td><p><a href="deploy-the-default-reports.md">Deploy the default reports</a></p></td>
</tr>
</tbody>
</table>


## Security changes

The following changes that pertain to security have been made.

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>Microsoft Dynamics AX 2009</p></th>
<th><p>Microsoft Dynamics AX 2012</p></th>
<th><p>Why is this important?</p></th>
<th><p>Where can I find more information?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Implement Microsoft Dynamics AX without having to configure Kerberos authentication</p>
<div class="alert">

> [!NOTE]
> <P>If you’re using Microsoft Dynamics AX 2012 R2, see the note about Kerberos authentication in Support for Power View</P>


</div></td>
<td><p>Kerberos authentication is required for environments where:</p>
<ul>
<li><p>Enterprise Portal for Microsoft Dynamics AX is installed on a server other than the server that is running Reporting Services and/or Analysis Services.</p></li>
<li><p>The Reporting Services database exists on a server other than the server that is running the Windows service for Reporting Services.</p></li>
</ul></td>
<td><p>Kerberos authentication is not required.</p></td>
<td><p>It’s easier to implement Microsoft Dynamics AX.</p></td>
<td><p><a href="security-settings-for-reports.md">Security settings for reports</a></p></td>
</tr>
<tr class="even">
<td><p>Configure security settings in Microsoft Dynamics AX</p></td>
<td><p>Security is implemented by using security groups and security keys.</p></td>
<td><p>Reports are fully integrated into the new Microsoft Dynamics AX role-based security model. When you help secure data by using duties and privileges, reports automatically respect that security.</p></td>
<td><p>It’s easier to configure security settings for reports in Microsoft Dynamics AX, and you can specify with more precision which data is displayed on a report.</p></td>
<td><p><a href="security-settings-for-reports.md">Security settings for reports</a></p>
<p><a href="security-considerations-creating-a-report.md">Security Considerations Creating a Report</a></p>
<p><a href="role-based-security-in-microsoft-dynamics-ax.md">Role-based security in Microsoft Dynamics AX</a></p></td>
</tr>
</tbody>
</table>


## Improvements to report development

The following improvements have been made to the report development process.

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
<th><p>Where can I find more information?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Access data for a report.</p></td>
<td><p>To access data, you use Microsoft Dynamics AX queries, data from analysis cubes, external Microsoft SQL Server databases, data methods that access data from Microsoft Dynamics AX or other sources, and managed code.</p></td>
<td><p>Use the data access methods that are available in AX 2012 and the report data provider (RDP) framework to define business logic for a report.</p></td>
<td><p>When you use Microsoft Dynamics AX queries, the reporting framework was enhanced to support display methods, field groups, and dimensions. When you add a field to a field group, the field is automatically reflected throughout the application. Therefore, reports automatically add the field. Display methods are treated like fields in the query, even though the display method retrieves the data from a different table. Because of the support for dimensions, you can create a report design by using dimension attributes in the data set, and dimension attributes can be used as report parameters.</p>
<p>An RDP class lets you write X++ code to define the business logic for your report.</p></td>
<td><p><a href="report-data-overview.md">Report Data Overview</a></p>
<p><a href="http://go.microsoft.com/fwlink/?linkid=230569">Report Programming Guide</a></p></td>
</tr>
<tr class="even">
<td><p>Use labels on a report.</p></td>
<td><p>Each language locale requires a .resx file to store localized strings.</p></td>
<td><p>Use Microsoft Dynamics AX labels in your reports. These labels can be dynamically resolved at run time.</p></td>
<td><p>By using Microsoft Dynamics AX labels on reports, you no longer have to create a .resx file for each language. Therefore less time is required to deploy reports. Only one report definition is required for each report.</p></td>
<td><p><a href="how-to-use-a-label-in-a-report.md">How to: Use a Label in a Report</a></p></td>
</tr>
<tr class="odd">
<td><p>Use data that is based on specific periods on a report.</p></td>
<td><p>This feature is not available.</p></td>
<td><p>Create a report that has data that is based on specific periods. The reporting framework supports date-effective data.</p></td>
<td><p>You do not have to handle date-effective data explicitly for query-based datasets in Microsoft Dynamics AX.</p></td>
<td><p><a href="walkthrough-creating-a-report-bound-to-date-effective-data.md">Walkthrough: Creating a Report Bound to Date Effective Data</a></p></td>
</tr>
<tr class="even">
<td><p>Use an improved set of developer tools.</p></td>
<td><p>You use the X++ Reporting Framework and Microsoft Visual Studio 2008.</p></td>
<td><p>Use Microsoft Visual Studio 2010 integration, take advantage of enhancements to auto-design reports, and create precision-design reports that use the chart features in Reporting Services 2008.</p></td>
<td><p>This change fits the long-term goal of aligning Microsoft Dynamics AX with the Microsoft technology stack.</p>
<p>This change also lets Microsoft Dynamics AX developers use Reporting Services features, such as rich charting and interactive reports. The following additional improvements have been made to the reporting tools:</p>
<ul>
<li><p>The <strong>Preview</strong> option is now enabled for all nodes under the design node.</p></li>
<li><p>A drop-down list was added to display the possible parameter types.</p></li>
<li><p>Microsoft PowerPivot and other Open Data Protocol (OData) clients are now supported.</p></li>
<li><p>Reporting Services sub-reports in precision design are now supported.</p></li>
<li><p>Report Data Customization Extension (RDCE) uses Windows Event Viewer logging.</p></li>
<li><p>New expressive charting capabilities are available for precision-design reports.</p></li>
</ul></td>
<td><p><a href="creating-reports-overview.md">Creating Reports Overview</a></p></td>
</tr>
<tr class="odd">
<td><p>Process business logic for data on a report.</p></td>
<td><p>You use a report data method and managed code.</p></td>
<td><p>Use the RDP framework that supports complex business logic in X++ code.</p></td>
<td><p>The RDP framework can support logic to handle data on a report. For example, an amount can be calculated based on a specific field.</p></td>
<td><p><a href="how-to-use-a-report-data-provider-class-in-a-report.md">How to: Use a Report Data Provider Class in a Report</a></p>
<p><a href="http://go.microsoft.com/fwlink/?linkid=230569">Report Programming Guide</a></p></td>
</tr>
<tr class="even">
<td><p>Use services to access data and business logic for a report.</p></td>
<td><p>You use .NET Business Connecter, which has a weakly-typed programming model.</p></td>
<td><p>Create a custom service, and access the service from a report.</p>
<p>Queries and RDP use services to access data for a report.</p></td>
<td><p>Standards-based service interfaces let you integrate with many platforms.</p>
<p>Services are strongly typed. Therefore issues are found at design time instead of run time.</p>
<p>The reporting framework added a service that can consume an RDP class from an external application. Services let you quickly expose existing X++ business logic without additional coding.</p></td>
<td><p><a href="services-and-application-integration-framework-aif.md">Services and Application Integration Framework (AIF)</a></p>
<p>How to: Reference a Service from a Data Method</p></td>
</tr>
<tr class="odd">
<td><p>Work with large datasets for a report.</p></td>
<td><p>You use a report data method to return a data table.</p></td>
<td><p>Create reports that use large datasets. Added functionality now binds to data methods that return data on a page or in a stream of data.</p></td>
<td><p>Only the first row of a dataset must be run to determine the report schema. This change makes it easier to work with large datasets. Now you can write business logic that returns data on a page or in a stream of data. You no longer have to fill the data table before you return it. Therefore, you use less memory and resources on the Reporting Server.</p></td>
<td><p><a href="report-data-method-overview.md">Report Data Method Overview</a></p></td>
</tr>
<tr class="even">
<td><p>Use Microsoft Dynamics AX metadata to automatically format a report.</p></td>
<td><p>You must define the report format explicitly.</p></td>
<td><p>Create reports that are automatically formatted based on the formatting that is specified for the extended data types.</p></td>
<td><p>Display width, date/time, and numeric formatting are automatically set. All styles and colors were updated so that they are correct.</p>
<p>You can use metadata to determine whether a field or table should be visible on a report.</p></td>
<td><p><a href="report-data-overview.md">Report Data Overview</a></p></td>
</tr>
<tr class="odd">
<td><p>Create an unlimited number of dimension attributes.</p></td>
<td><p>The number of dimensions and dimension attributes is limited to three default dimensions and seven user-definable dimension attributes.</p></td>
<td><p>Use the query picker, report model, and report generation. All these features were updated so that they reflect improvements to the dimension framework.</p></td>
<td><p>Create an unlimited number of dimension attributes by using the dimension framework. You also have more flexibility, because you can combine dimension attributes.</p></td>
<td><p><a href="walkthrough-creating-a-report-bound-to-a-dimension-data-source.md">Walkthrough: Creating a Report Bound to a Dimension Data Source</a></p></td>
</tr>
<tr class="even">
<td><p>Take advantage of queries by using a surrogate foreign key (SFK).</p></td>
<td><p>The tables that report queries use as a data source sometimes contain natural keys, and the text for the fields is not always understandable.</p></td>
<td><p>Use queries that now use SFKs instead of natural keys.</p></td>
<td><p>Some of the benefits include improved readability, reduced database size, decreased time to upgrade, and fewer data integrity issues.</p>
<p>A lookup was added to the ReportRunUI control for SFK parameters, so that you can filter on a SFK relationship on a report.</p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/gg847984(v=ax.60)">Walkthrough: Leveraging Foreign Keys in Query Relations</a></p></td>
</tr>
<tr class="odd">
<td><p>Access cross-reference information for a Reporting Services report.</p></td>
<td><p>This feature is not available.</p></td>
<td><p>Use the cross-reference tool together with Reporting Services reports.</p></td>
<td><p>You can see what data the report is using. You can also see what objects in the Microsoft Dynamics AX Application Object Tree (AOT) are using the report.</p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/gg889239(v=ax.60)">Walkthrough: Using the Cross-Reference Tool with Visual Studio Projects</a></p></td>
</tr>
<tr class="even">
<td><p>Define a report that can be flipped from right to left, depending on the language that is set for the report.</p></td>
<td><p>A report cannot be flipped from right to left.</p>
<p>A new precision design is required, where all the report items are flipped manually. Therefore, there might be two designs for the same report.</p></td>
<td><p>Create a report that is flipped from right to left at run time, depending on the language that is set and the properties that are set on the report.</p></td>
<td><p>You no longer have to maintain two report designs for reports that must be flipped from right to left.</p></td>
<td><p><a href="localizing-reports.md">Localizing Reports</a></p></td>
</tr>
<tr class="odd">
<td><p>The AX_CompanyName report parameter has been updated to reflect changes in AX 2012.</p></td>
<td><p>The report parameter for the company name, AX_CompanyName, is added to each report at report design time.</p>
<p>The AX_CompanyName report parameter is unique, because it cannot be deleted and does not have to be initialized.</p></td>
<td><p>The AX_CompanyName parameter is added only when the query is company-specific.</p>
<p>You can initialize the AX_CompanyName parameter by using built-in methods.</p></td>
<td><p>You can add organization parameters to your report, such as <strong>Operating Unit</strong> or <strong>Department</strong>.</p>
<p>The AX_CompanyName parameter was created by the Microsoft Dynamics AX framework for queries that are company-specific.</p>
<p>This change reflects the product-wide feature for organization hierarchies.</p></td>
<td><p><a href="how-to-create-a-company-parameter-in-a-report.md">How to: Create a Company Parameter in a Report</a></p>
<p><a href="organizations-and-organizational-hierarchies.md">Organizations and organizational hierarchies</a></p></td>
</tr>
<tr class="even">
<td><p>Use the improved drill-through functionality on reports.</p></td>
<td><p>This feature is not available.</p></td>
<td><p>The following changes were made to improve the drill-through functionality on reports:</p>
<ul>
<li><p>The client no longer uses table IDs. Instead, the client uses table names and field names to determine which menu item the report link should use.</p></li>
<li><p>The link style is no longer underlined, and the color was changed.</p></li>
<li><p>The drill-through now opens in a new client window.</p></li>
</ul></td>
<td><p>Using table and field names reduces ambiguity and errors.</p>
<p>The updated link style is consistent with the link style that users expect. This change improves the look and usability of reports that have links.</p>
<p>Opening a new window for a linked report is consistent with the expected behavior and improves the usability of reports that have links.</p></td>
<td><p><a href="walkthrough-creating-a-drillthrough-report.md">Walkthrough: Creating a Drillthrough Report</a></p></td>
</tr>
</tbody>
</table>


## Parity with the legacy X++ reporting framework

The following features have been added so that Reporting Services reports have the same capabilities as the legacy X++ reports.

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
<th><p>Where can I find more information?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Filter and sort the data on Reporting Services reports.</p></td>
<td><p>This feature is not supported.</p></td>
<td><p>This feature is supported.</p></td>
<td><p>It’s easier to use Reporting Services reports in Microsoft Dynamics AX.</p></td>
<td><p><a href="filter-the-data-on-a-report.md">Filter the data on a report</a></p>
<p><a href="sort-the-data-on-a-report.md">Sort the data on a report</a></p></td>
</tr>
<tr class="even">
<td><p>Create auto-reports that run on the Reporting Services platform.</p></td>
<td><p>This feature is not supported.</p></td>
<td><p>This feature is supported.</p></td>
<td><p>You can quickly generate a Reporting Services report by clicking <strong>File</strong> &gt; <strong>Print</strong> &gt; <strong>Print</strong> in a Microsoft Dynamics AX form. You can generate an auto-report that is used only one time. Alternatively, you can create a custom auto-report, and then save the report so that it can be reused later.</p></td>
<td><p><a href="create-a-report-by-using-the-microsoft-dynamics-ax-auto-report-wizard.md">Create a report by using the Microsoft Dynamics AX auto-report wizard</a></p></td>
</tr>
<tr class="odd">
<td><p>Print Reporting Services reports as part of a batch.</p></td>
<td><p>This feature is not supported.</p></td>
<td><p>This feature is supported.</p></td>
<td><p>You can now perform the following tasks:</p>
<ul>
<li><p>Print a Reporting Services report on a recurring basis.</p></li>
<li><p>Schedule a Reporting Services report so that it is printed during off-peak hours.</p></li>
</ul></td>
<td><p><a href="print-or-email-a-report-on-a-recurring-basis.md">Print or email a report on a recurring basis</a></p>
<p><a href="print-or-email-a-report-during-off-peak-hours.md">Print or email a report during off-peak hours</a></p></td>
</tr>
<tr class="even">
<td><p>Manage print settings for Reporting Services reports.</p></td>
<td><p>This feature is not supported.</p></td>
<td><p>This feature is supported.</p></td>
<td><p>You can now perform the following tasks:</p>
<ul>
<li><p>Modify the print settings of a Reporting Services report, based on the contents of the data that is printed. For example, you can print sales orders that total less than USD 1,000 to printer A, and sales orders that total USD 1,000 or more to printer B.</p></li>
<li><p>Specify print settings at various levels of the application. For example, you can set up module-level print settings that apply to all documents in a specific module. Alternatively, you can set up customer-level print settings that apply to documents for specific customers.</p></li>
</ul></td>
<td><p><a href="http://download.microsoft.com/download/2/b/4/2b41d4f0-3072-4f93-90a5-4b0e08a96a43/printmgmtintegrationguide.pdf">Print Management Integration Guide</a></p></td>
</tr>
</tbody>
</table>

  


