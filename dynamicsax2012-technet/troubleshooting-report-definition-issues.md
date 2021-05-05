---
title: Troubleshooting Report Definition Issues
TOCTitle: Troubleshooting Report Definition Issues
ms:assetid: 06ff38d9-ca23-4e8f-8b06-fad378f8ef56
ms:mtpsurl: https://technet.microsoft.com/library/Gg731894(v=AX.60)
ms:contentKeyID: 35132812
author: Khairunj
ms.date: 01/09/2015
mtps_version: v=AX.60
---

# Troubleshooting Report Definition Issues 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The first step to troubleshooting a report issue is to identify the underlying cause for it. This topic describes common issues that may occur when you are defining a Microsoft Dynamics AX report. For SQL Server Reporting Services report troubleshooting information, see [Troubleshooting Report Problems](https://go.microsoft.com/fwlink/?linkid=200936).

The following table provides guidance to help you determine the cause of your report issue.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Issue</p></th>
<th><p>Additional information for troubleshooting</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>The report is broken for any reason and the data source is a query.</p></td>
<td><p>Execute the query outside of the report. Confirm that the query returns expected results. Use a form, job, or Query Services to test the query. For more information, see <a href="query-service.md">Query Service</a>.</p></td>
</tr>
<tr class="even">
<td><p>The report is broken and the data source is a report data provider (RDP) class.</p></td>
<td><p>Debug the class. For more information, see <a href="how-to-configure-the-debugger-to-debug-a-report-data-provider-class.md">How to: Configure the Debugger to Debug a Report Data Provider Class</a>.</p></td>
</tr>
<tr class="odd">
<td><p>When you preview the report you receive the following error:</p>
<p>No report data table with name &lt;dataset table name&gt; exists in report schema for data provider &lt;RDP name&gt;.</p></td>
<td><p>Verify that the report is bound to tables that exist and do not bind multiple datasets to a single report data provider class. Instead, define the report to have the multiple tables pointing to the same dataset.</p></td>
</tr>
<tr class="even">
<td><p>No data was returned in the report.</p></td>
<td><p>Verify you have the right company, that there is data entered for that company, and that the user has access to the expected data.</p></td>
</tr>
<tr class="odd">
<td><p>The report has a rendering error. When you try to run the report, you receive an error like the following:</p>
<p>An error has occurred during report processing.</p></td>
<td><p>The SSRS Execution Account password could be invalid.</p>
<ol>
<li><p>From the <strong>Start</strong> menu, point to <strong>All Programs</strong>, click the <strong>Microsoft SQL Server</strong> folder, click the <strong>Configuration Tools</strong> folder, and then click <strong>Reporting Services Configuration Manager</strong>.</p></li>
<li><p>In <strong>Reporting Services Configuration Manager</strong>, click <strong>Connect</strong> and then click <strong>Execution Account</strong>.</p></li>
<li><p>Set the password and then click <strong>Apply</strong>. The account and password should be the same as the Microsoft Dynamics AX proxy account. For more information, see <a href="before-you-install-the-reporting-services-extensions.md">Before you install the Reporting Services extensions</a>.</p></li>
<li><p>Click the <strong>ServerName/MSSQLSERVER</strong> and then click <strong>Stop</strong>. Then click <strong>Start</strong> to restart the server. Always check with the SQL administrator and make sure no other users are connected to the server before you restart the server.</p></li>
</ol></td>
</tr>
<tr class="even">
<td><p>The report labels do not display, or the report shows label IDs, like Labels!@SYS24426 instead of the label values.</p></td>
<td><p>The SSRS Service Account password could be invalid.</p>
<ol>
<li><p>From the <strong>Start</strong> menu, point to <strong>All Programs</strong>, click the <strong>SQL Server</strong> folder, click the <strong>Configuration Tools</strong> folder, and then click <strong>Reporting Services Configuration Manager</strong>.</p></li>
<li><p>In Reporting Services Configuration Manager click <strong>Connect</strong> and then click <strong>Service Account</strong>.</p></li>
<li><p>Set the password and then click <strong>Apply</strong>. The account and password should be the same as the Microsoft Dynamics AX proxy account. For more information, see <a href="before-you-install-the-reporting-services-extensions.md">Before you install the Reporting Services extensions</a>.</p></li>
<li><p>Click the <strong>ServerName/MSSQLSERVER</strong> and then click <strong>Stop</strong>. Then click <strong>Start</strong> to restart the server. Always check with the SQL administrator and make sure no other users are connected to the server before you restart the server.</p></li>
</ol></td>
</tr>
<tr class="odd">
<td><p>When running a report that uses an enumeration value as a multi-value parameter of a report, you get an error like the following:</p>
<p>The ‘ParameterName’ parameter is missing a value.</p></td>
<td><p>Set the <strong>Data Type</strong> property of the enumeration parameter to <strong>Integer</strong>.</p>
<p>This is because the label value of enumeration items are converted to name values in the SrsReportDataContractUIBuilder.getMultiSelectFromDialogField method.</p></td>
</tr>
<tr class="even">
<td><p>When building a report project that uses a SQL report data source, you receive the following error:</p>
<p>The report does not have the mandatory framework parameter AX_ReportContext.</p></td>
<td><p>Manually create the AX_ReportContext report parameter. For more information, see <a href="walkthrough-creating-a-report-with-parameters.md">Walkthrough: Creating a Report with Parameters</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Time values in a report bound to an AOT query are displayed as h:mm:ss tt in Visual Studio preview and the Microsoft Dynamics AX client instead of the actual time.</p></td>
<td><p>Select the field in the report design and set the following properties:</p>
<ul>
<li><p><strong>Expression</strong> property to =Microsoft.Dynamics.Framework.Reports.BuiltInMethods.ConvertAXTimeToDateTime(Fields!timefield.Value)</p></li>
<li><p><strong>Format String</strong> property to hh:mm:ss</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>An AOS connection error message indicates you cannot establish a connection to the AOS.</p></td>
<td><p>To delete, rename, save, or restore a report model element, you must have a connection to the Application Object Server (AOS). If the AOS is disconnected or stops running after a reporting project is opened, an AOS connection error message will display. To continue, restart or restore the connection to the AOS, and then repeat the command that failed.</p></td>
</tr>
<tr class="odd">
<td><p>The Undo command is not functioning in the report model.</p></td>
<td><p>In Model Editor, only unsaved commands can be undone. Once a command is saved, it cannot be undone by using the Undo command. To revert a saved command, you must manually modify the report element. If you are using source code control, another option is to discard the file that is checked out if no other changes have been made.</p></td>
</tr>
<tr class="even">
<td><p>The saved report model customization is not visible in Application Explorer.</p></td>
<td><p>Application Explorer does not automatically refresh as Model Editor saves changes to the model store database. To view changes in Application Explorer, right-click the model element, and then click <strong>Refresh</strong>.</p></td>
</tr>
<tr class="odd">
<td><p>The saved report model customization is not visible in the AOT.</p></td>
<td><p>The AOT does not automatically refresh as Model Editor saves changes in the model store database. To view changes in the AOT, in the Development Workspace <strong>Tools</strong> menu, click <strong>Development tools</strong>, <strong>Application objects</strong>, and then <strong>Refresh runtime model data</strong>.</p></td>
</tr>
<tr class="even">
<td><p>When previewing a report in Visual Studio you receive the following error:</p>
<p>The %0 parameter is missing a value %1</p></td>
<td><p>Verify that you did not create a report with a Labels expression in the <strong>Values</strong> property of the report parameter. This is not supported because Reporting Services resolves parameter labels after the parameter evaluation and execution occur.</p>
<p>--or--</p>
<p>Verify that you did not set the <strong>Allow Blank</strong> property to <strong>True</strong> to make the parameter optional. This is not supported for dataset bound parameters by the reporting framework. The following items identify the alternative approaches for OLTP and OLAP reports:</p>
<ul>
<li><p>OLTP reports – use an extended data type (EDT) to add a null-value string variable to the drop-down list as a default. When running the report, you can set the parameter value to NULL by not selecting anything from the drop-down list.</p></li>
<li><p>OLAP reports – add a value <strong>All</strong> to the drop-down list to indicate that no filtering is to be done by the parameter.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>The query for the report was changed but the report does not reflect the change.</p></td>
<td><p>After you run the report, the query and ranges are cached in the SRSReportQuery table. To refresh the cache, you must manually delete all records in the SRSReportQuery table for any reports or report parameters that use the query that was changed.</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td></td>
</tr>
<tr class="odd">
<td><p>Locking or hiding a range for a report parameter is not working. At runtime, the parameter is enabled and the user is able to filter on the range. This occurs when a report is bound to a query that has a range value with a <strong>Status</strong> property value of Locked or Hidden.</p></td>
<td><p>SQL Server Reporting Services does not honor the query range <strong>Status</strong> property.</p></td>
</tr>
<tr class="even">
<td><p>The <strong>Label</strong> reference does not display properly. The <strong>Value</strong> property is set to the Parameters!MyParm.Value parameter.</p></td>
<td><p>The parameter must be explicitly bound to data using a dataset in the Visual Studio Tools for Microsoft Dynamics AX report model.</p></td>
</tr>
<tr class="odd">
<td><p>The parameter is explicitly bound to datasets with two columns, label and value. The value displays properly. The <strong>Label</strong> reference displays properly everywhere except in the client.</p></td>
<td><p>The report viewer control does not support the ability to specify report parameter labels, only values.</p></td>
</tr>
<tr class="even">
<td><p>When you build a Visual Basic project for a report, the project does not build.</p>
<p>-or-</p>
<p>You receive the error “The business logic assembly ClassLibrary1, Version=1.0.0.0, Culture=neutral, PublicKeyToken=null does not contain a class for report Report1.”</p></td>
<td><p>You must clear out the namespace setting of the Visual Basic project. In Solution Explorer, right-click the project, and then click <strong>Properties</strong>. In the <strong>Application</strong> area, delete the text in the <strong>Root namespace</strong> field.</p></td>
</tr>
<tr class="odd">
<td><p>In Visual Studio, you build a project and receive the error, “System.InvalidOperationException: Object is currently in use elsewhere.”</p></td>
<td><p>This error indicates a synchronization issue. Close the solution and then rebuild the report.</p></td>
</tr>
<tr class="even">
<td><p>When you debug a C# data method, the SQL Server Reporting Services server crashes.</p></td>
<td><p>This is a known issue if you are debugging a C# data method on a machine that is running a 64 bit operating system. To work around this issue, open Visual Studio 2008, load the C# file, set the break point, and then attach to the Reporting Services process. For more information, see <a href="https://technet.microsoft.com/library/gg889265(v=ax.60)">Debugging Managed Code in Microsoft Dynamics AX</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Reports that run for more than ten minutes time out. For example:</p>
<ul>
<li><p>If you are previewing a report in Visual Studio and a timeout occurs, you will receive the following error:</p>
<p>Timeout error occured when calling AOS service. Use Dynamics AX Client Configuration Utility to change WCF configuration values. Exception details: The request channel timed out while waiting for a reply after 00:00:59.9449945. Increase the timeout value passed to the call to Request or increase the SendTimeout value on the Binding. The time allotted to this operation may have been a portion of a longer timeout.</p></li>
<li><p>If a user is trying to view a report in the Microsoft Dynamics AX client and a timeout occurs, the user will receive the following error in the InfoLog:</p>
<p>A connection attempt failed because the connected party did not properly respond after a period of time, or established connection failed because connected host has failed to respond.</p></li>
</ul></td>
<td><p>See <a href="tips-to-help-prevent-long-running-reports-from-timing-out.md">Tips to help prevent long-running reports from timing out</a>.</p></td>
</tr>
<tr class="even">
<td><p>Errors are generated when reports are saved to a file, printed to a printer, or emailed.</p></td>
<td><p>View the detailed error messages that are recorded for the <strong>Reporting</strong> module in the <strong>Exceptions</strong> form. Click <strong>System administration</strong> &gt; <strong>Periodic</strong> &gt; <strong>Services and Application Integration Framework</strong> &gt; <strong>Exceptions</strong>.</p></td>
</tr>
<tr class="odd">
<td><p>The same report contains different information when saved to different file formats.</p>
<p>For example, a sales invoice report that is saved to an .HTML file may contain header information, line items, and totals. When the same report is saved to an .XML file, it may contain only the line items and totals.</p></td>
<td><p>This is by design. For more information about how reports are rendered in the available file formats, see <a href="https://msdn.microsoft.com/library/dd239307(sql.105).aspx">Exporting Reports (Report Builder 3.0 and SSRS)</a> in the SQL Server documentation.</p></td>
</tr>
<tr class="even">
<td><p>Users receive the following error when clicking on a drill-through link on a report in Enterprise Portal:</p>
<p>[CompanyName] is not a valid company. Check the value and try again.</p></td>
<td><p>This situation may occur when Reporting Services 2008 or Reporting Services 2008 R2 is running in SharePoint integrated mode. To resolve this issue, install Reporting Services 2008 R2 with Service Pack 2.</p>
<div class="alert">

> [!NOTE]
> <P>SharePoint integrated mode is supported if you are using Microsoft Dynamics AX 2012 R2 or later.</P>


</div></td>
</tr>
<tr class="odd">
<td><p>Tables are not aligned correctly when viewing reports in right-to-left (RTL) languages.</p></td>
<td><p>This is a known issue with the Reporting Services tablix control. For more information about the issue, see <a href="https://blogs.msdn.com/b/dynamicsaxbi/archive/2012/10/02/known-issue-dynamic-precision-designs-spacing-issues-in-rtl-languages.aspx">Known Issue: Dynamic Precision designs spacing issues in RTL languages</a> in the Microsoft Dynamics AX Business Intelligence blog.</p></td>
</tr>
<tr class="even">
<td><p>The Reporting Services extensions become unusable when additional Reporting Services instances are installed on the same computer. As a result:</p>
<ul>
<li><p>Reports cannot be deployed.</p></li>
<li><p>Reports cannot be displayed.</p></li>
</ul></td>
<td><p>To resolve this issue, configure all the Reporting Services instances on the computer. For more information about how to install and configure multiple instances of Reporting Services on the same computer, see <a href="install-multiple-instances-of-reporting-services-on-the-same-computer-for-use-with-microsoft-dynamics-ax.md">Install multiple instances of Reporting Services on the same computer (for use with Microsoft Dynamics AX)</a>.</p></td>
</tr>
<tr class="odd">
<td><p>When printing a report that has been saved as a PDF file, the printer page size does not correspond to the PDF page size.</p></td>
<td><p>To resolve this issue, select the <strong>Choose paper source by PDF page size</strong> check box in the <strong>Print</strong> window that is displayed when printing the report to the printer.</p></td>
</tr>
<tr class="even">
<td><p>When using an environment that includes a hardware load balancer, such as F5, reports that run for more than five minutes time out.</p></td>
<td><p>To resolve this issue, adjust the timeout period specified in the hardware load balancer. For example, if you are using F5, set the <strong>Idle Timeout</strong> field to 7200 seconds or higher. For more information, see the <a href="http://support.f5.com/kb/en-us/solutions/public/7000/600/sol7606.html">F5 Knowledge Base</a>.</p></td>
</tr>
<tr class="odd">
<td><p>You need to adjust the alignment of a report.</p></td>
<td><p>For tips on adjusting the alignment, see this blog post: <a href="https://blogs.msdn.com/b/axsupport/archive/2015/01/08/ssrs-report.aspx">SSRS report tips to adjust alignment for pre-formatted print stock (i.e. 1099-MISC form)</a>.</p></td>
</tr>
</tbody>
</table>


## See also

[Troubleshooting reporting](troubleshooting-reporting.md)

[Reporting in Microsoft Dynamics AX](reporting-in-microsoft-dynamics-ax.md)

  


