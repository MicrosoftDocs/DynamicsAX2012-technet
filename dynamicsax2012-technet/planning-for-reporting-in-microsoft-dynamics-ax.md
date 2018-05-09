---
title: Planning for reporting in Microsoft Dynamics AX
TOCTitle: Planning for reporting
ms:assetid: 05dd329c-ba8a-41e6-a2d5-1d534c34b10a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dd309577(v=AX.60)
ms:contentKeyID: 35132809
ms.date: 03/11/2015
mtps_version: v=AX.60
---

# Planning for reporting in Microsoft Dynamics AX 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before you implement the reporting features of Microsoft Dynamics AX, there are several things you must consider. This article describes the things you must consider and the decisions you must make at each step in the planning process.

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<tbody>
<tr class="odd">
<td><img src="images/Dd309577.TopicIcons_Plan(AX.60).png" title="Plan" alt="Plan" />
<p>Verify prerequisites</p>
<p>Select a Reporting Services mode</p>
<p>Determine your topology</p>
<p>Determine if the reports that are provided with Microsoft Dynamics AX will meet your needs</p>
<p>Determine which tools will be used to create custom reports</p>
<p>Learn about Management Reporter</p>
<p>Next steps</p></td>
</tr>
</tbody>
</table>


## Verify prerequisites

Before you begin the planning process, you must make sure that the following prerequisites are in place.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
<th><p>Resources</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Required knowledge</p></td>
<td><p>Before you begin installing and using the reporting features of Microsoft Dynamics AX, you must be familiar with Microsoft SQL Server Reporting Services.</p></td>
<td><p><a href="http://technet.microsoft.com/en-us/library/ms159106.aspx">Reporting Services 2014</a></p>
<p><a href="http://technet.microsoft.com/en-us/library/ms159106(v=sql.110).aspx">Reporting Services 2012</a></p>
<p><a href="http://technet.microsoft.com/en-us/library/ms159106(v=sql.105).aspx">Reporting Services 2008 R2</a></p>
<p><a href="http://technet.microsoft.com/en-us/library/ms159106(v=sql.100).aspx">Reporting Services 2008</a></p></td>
</tr>
</tbody>
</table>


## Select a Reporting Services mode

If you do not already have Reporting Services installed, you must install it. When you install Reporting Services, you must select a mode in which to run the report server. Two modes are available: native mode and SharePoint integrated mode. The mode you select affects the steps you will need to complete to integrate the report server with Microsoft Dynamics AX.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Mode</p></th>
<th><p>Description</p></th>
<th><p>Resources</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Native</p></td>
<td><p>In native mode, a report server is a stand-alone application server. Native mode is the default mode for Reporting Services.</p>
<p>If the report server is running in native mode, the reports that are included with Microsoft Dynamics AX are deployed to the Report Manager website. You can manage and view the reports from this website.</p></td>
<td><p>For more information about native mode, see <a href="overview-of-reporting-services.md">Overview of Reporting Services</a>.</p>
<p>For instructions about how to install and configure Reporting Services in native mode, see <a href="before-you-install-the-reporting-services-extensions.md">Before you install the Reporting Services extensions</a>.</p></td>
</tr>
<tr class="even">
<td><p>SharePoint integrated</p></td>
<td><p>In SharePoint integrated mode, a report server runs in a SharePoint server farm.</p>
<p>If the report server is running in SharePoint integrated mode, the reports that are included with Microsoft Dynamics AX are deployed to a document library on a SharePoint website. You can manage and view the reports from this document library.</p>
<p>SharePoint integrated mode is supported if you are using Microsoft Dynamics AX 2012 R2 or later.</p></td>
<td><p>For more information about SharePoint integrated mode, see <a href="overview-of-reporting-services.md">Overview of Reporting Services</a>.</p>
<p>For instructions about how to install and configure Reporting Services in SharePoint integrated mode, see <a href="before-you-install-the-reporting-services-extensions.md">Before you install the Reporting Services extensions</a>.</p></td>
</tr>
</tbody>
</table>


## Determine your topology

To help plan your Microsoft Dynamics AX implementation, determine a topology that supports the reporting needs of your organization. Consider the following information when determining your topology.

## Multiple instances of Reporting Services on one computer

You can install multiple instances of Reporting Services on the same computer. In this kind of deployment environment, each instance of Reporting Services is connected to an independent Microsoft Dynamics AX installation. You may want to install multiple instances of Reporting Services on the same computer for the following reasons:

  - To support development and production installations of Microsoft Dynamics AX
    
    For example, in the following sample diagram, assume that *AOS instance 1* is a development installation of Microsoft Dynamics AX, and *AOS instance 2* is the production installation of Microsoft Dynamics AX.

  - To support multiple production installations of Microsoft Dynamics AX
    
    For example, if you are a Microsoft Dynamics AX solution provider, you may have to support multiple production installations of Microsoft Dynamics AX. For this scenario, assume that *AOS instance 1* (in the sample diagram) is a production installation of Microsoft Dynamics AX for one client, Northwind Traders. Assume that *AOS instance 2* is a production installation of Microsoft Dynamics AX for another client, Contoso Pharmaceuticals.

![Multiple SSRS instances on one computer](images/Dd309577.BI_Modern_MultipleSSRS(AX.60).png "Multiple SSRS instances on one computer")


> [!NOTE]
> <P>You cannot install multiple instances of Reporting Services 2012 or 2014—that run in SharePoint integrated mode—on the same computer.</P>



For more information, see [Install multiple instances of Reporting Services on the same computer (for use with Microsoft Dynamics AX)](install-multiple-instances-of-reporting-services-on-the-same-computer-for-use-with-microsoft-dynamics-ax.md).

## AOS scale-out deployments

You can distribute the user load in Microsoft Dynamics AX across multiple instances of the Application Object Server (AOS) by creating a load balancing cluster. The cluster may or may not include a dedicated load balancer.

In an environment that contains an AOS load balancing cluster, you must point each AOS instance to the same Reporting Services instance. For example, your environment may resemble the following illustration.

![AOS scale-out deployment](images/Dd309577.BI_Modern_AOSScaleOut(AX.60).png "AOS scale-out deployment")

To integrate an AOS load balancing cluster with Reporting Services, complete the following tasks.

1.  Install the Reporting Services extensions on the server running Reporting Services. For more information, see [Install the Reporting Services extensions](install-the-reporting-services-extensions.md).
    
    When you install the Reporting Services extensions, the Setup wizard requires you to connect to an AOS instance. Connect to an AOS instance in the cluster. However, if the cluster includes a dedicated load balancer, **do not** connect to the AOS instance that serves as the dedicated load balancer.
    
    When the installation is complete, the AOS instance that you selected is connected to the Reporting Services instance. You can view the properties of this connection in the **Report servers** form in Microsoft Dynamics AX.

2.  Connect the other AOS instances in the cluster to the Reporting Services instance. To connect an AOS instance to the Reporting Services instance, complete these steps:
    
    1.  Open the Microsoft Dynamics AX client.
    
    2.  Click **System administration** \> **Setup** \> **Business intelligence** \> **Reporting Services** \> **Report servers**.
    
    3.  Connect the AOS instance to the Reporting Services instance by creating a new record in the **Report servers** form. For more information about how to use this form, see [Report servers (form)](https://technet.microsoft.com/en-us/library/aa548504\(v=ax.60\)).

## Reporting Services scale-out deployments

A report server scale-out deployment includes two or more report server instances that share a single report server database. By using a Reporting Services scale-out deployment, you can increase the number of users who can access reports at the same time. You can also improve the availability of the report server.

Microsoft Dynamics AX supports scale-out deployments of Reporting Services in an environment that has the following configuration:

  - The Reporting Services instances are installed on separate computers.

  - The Reporting Services instances share a single database.

  - A Network Load Balancing (NLB) cluster is used.

  - The Reporting Services extensions that are provided by Microsoft Dynamics AX are installed on each computer where Reporting Services is installed.

An environment of this kind may resemble the following illustration.

![SSRS scale-out deployment](images/Dd309577.BI_Modern_SSRSScaleOut(AX.60).png "SSRS scale-out deployment")

For more information about how to configure a scale-out deployment, see the [Configuring a SQL Server Reporting Services scale-out deployment to run on a Network Load Balancing cluster](http://go.microsoft.com/fwlink/?linkid=248235) white paper. For more information about Reporting Services scale-out deployments, see [Planning for scale-out deployment](http://msdn.microsoft.com/en-us/library/bb630407.aspx) in the SQL Server documentation.

## Failover clustering

Reporting Services cannot be installed on a failover cluster because you cannot run the Reporting Services service as part of a failover cluster. However, you can install the report server database on a computer that has a failover cluster installed. For more information, see [Host a Report Server Database in a SQL Server Failover Cluster](http://msdn.microsoft.com/en-us/library/bb630402.aspx).

## AlwaysOn

SQL Server AlwaysOn is a capability that enables highly available, SQL Server databases. This capability has been available since SQL Server 2012. Key points to keep in mind:

  - Systems administrators can deploy AlwaysOn capabilities to create a robust environment for databases, including the Microsoft Dynamics AX database, as well as other staging databases associated with a Microsoft Dynamics AX implementation, such as the SSRS catalog database.

  - The AlwaysOn feature enables retaining a read-only replica of the primary Microsoft Dynamics AX database. This read-only replica can be used for processing cubes, thereby relieving the load on the primary Microsoft Dynamics AX database.

  - Secondary databases created as a result of enabling SQL Server AlwaysOn cannot be used to scale-out Reporting Services. To scale-out your Microsoft Dynamics AX SQL Server Reporting Services deployments see the information here.

## Determine if the reports that are provided with Microsoft Dynamics AX will meet your needs

Microsoft Dynamics AX provides hundreds of preconfigured reports that users can use to view and analyze business data. Review details about these reports in the [Report catalog for Microsoft Dynamics AX](report-catalog-for-microsoft-dynamics-ax.md) to determine if they will meet organization’s needs. If you need to create custom reports, see the next section.

## Determine which tools will be used to create custom reports

If you or anyone in your organization needs to create a new, custom report, several tools are available. The following table lists the tools that can be used to create reports, and the type of user who will most likely use those tools.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th> <p>
   
	 Category
  </p> </th>
    <th> <p>
   
	 Tool that is used to create the report
  </p> </th>
    <th> <p>
   
	 Type of user who typically creates this kind of report
  </p> </th>
    <th> <p>
   
	 Resources
  </p> </th>
  </tr>
  <tr>
    <td rowspan="5"> <p> <strong>Transactional reports</strong> </p> <p>
   
	 Transactional reports retrieve data from the transaction processing database for Microsoft Dynamics AX. 
  </p> <p></p> <p></p> <p></p> <p></p> </td>
    <td> <p>
   
	 Visual Studio
  </p> </td>
    <td> <p>
   
	 Developer
  </p> </td>
    <td> <p> <a href="development-tasks-for-reporting.md" runat="server" xmlns="http://www.w3.org/1999/xhtml">Development Tasks for Reporting</a> </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Microsoft Dynamics AX list page
  </p> </td>
    <td> <p>
   
	 System administrator
  </p> <p>
   
	 Application user
  </p> </td>
    <td> <p> <a href="use-a-list-page.md" runat="server" xmlns="http://www.w3.org/1999/xhtml">Use a list page</a> </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Microsoft Dynamics AX auto-report wizard
  </p> </td>
    <td> <p>
   
	 System administrator
  </p> <p>
   
	 Application user
  </p> </td>
    <td> <p> <a href="create-a-report-by-using-the-microsoft-dynamics-ax-auto-report-wizard.md" runat="server" xmlns="http://www.w3.org/1999/xhtml">Create a report by using the Microsoft Dynamics AX auto-report wizard</a> </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Microsoft Dynamics AX add-in for Excel
  </p> </td>
    <td> <p>
   
	 System administrator
  </p> <p>
   
	 Application user
  </p> </td>
    <td> <p> <a href="using-the-microsoft-dynamics-ax-add-in-for-excel.md" runat="server" xmlns="http://www.w3.org/1999/xhtml">Using the Microsoft Dynamics AX Add-in for Excel</a> </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Management Reporter for Microsoft Dynamics ERP
  </p> </td>
    <td> <p>
   
	 System administrator
  </p> <p>
   
	 Application user
  </p> </td>
    <td> <p> <a href="http://www.microsoft.com/download/en/details.aspx?id=5916" runat="server">Microsoft Management Reporter: Installation, Migration, and Configuration Guides</a> </p> </td>
  </tr>
  <tr>
    <td rowspan="5"> <p> <strong>Analytical reports</strong> </p> <p>
   
	 Analytical reports retrieve data from Microsoft SQL Server Analysis Services cubes.
  </p> <p></p> <p></p> <p></p> <p></p> </td>
    <td> <p>
   
	 Visual Studio
  </p> </td>
    <td> <p>
   
	 Developer
  </p> </td>
    <td> <p> <a href="walkthrough-displaying-cube-data-in-a-report.md" runat="server" xmlns="http://www.w3.org/1999/xhtml">Walkthrough: Displaying Cube Data in a Report</a> </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 SQL Server Business Intelligence Development Studio or SQL Server Data Tools
  </p> </td>
    <td> <p>
   
	 Developer
  </p> </td>
    <td> <p> <a href="walkthrough-defining-kpis-for-a-cube.md" runat="server" xmlns="http://www.w3.org/1999/xhtml">Walkthrough: Defining KPIs for a Cube</a> </p> <p> <a href="walkthrough-displaying-kpis-in-a-role-center.md" runat="server" xmlns="http://www.w3.org/1999/xhtml">Walkthrough: Displaying KPIs in a Role Center</a> </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 SQL Server Report Builder
  </p> </td>
    <td> <p>
   
	 Developer
  </p> <p>
   
	 System administrator
  </p> </td>
    <td> <p> <a href="create-a-report-by-using-sql-server-report-builder-to-connect-to-a-cube.md" runat="server" xmlns="http://www.w3.org/1999/xhtml">Create a report by using SQL Server Report Builder to connect to a cube</a> </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Excel
  </p> </td>
    <td> <p>
   
	 System administrator
  </p> <p>
   
	 Application user
  </p> </td>
    <td> <p> <a href="create-a-report-by-using-the-excel-data-connection-wizard-to-connect-to-a-cube.md" runat="server" xmlns="http://www.w3.org/1999/xhtml">Create a report by using the Excel data connection wizard to connect to a cube</a> </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 SQL Server Power View
  </p> </td>
    <td> <p>
   
	 System administrator
  </p> <p>
   
	 Application user
  </p> </td>
    <td> <p> <a href="create-a-report-by-using-power-view-to-connect-to-a-cube.md" runat="server" xmlns="http://www.w3.org/1999/xhtml">Create a report by using Power View to connect to a cube</a> </p> </td>
  </tr>
</table>


## Learn about Management Reporter

Management Reporter for Microsoft Dynamics ERP is the recommended financial reporting solution for Microsoft Dynamics AX 2012. Use Management Reporter to create, distribute, and analyze financial statements and other financial reports. For more information, see [Management Reporter for Microsoft Dynamics ERP](http://technet.microsoft.com/en-us/library/dn435963.aspx).

## Next steps

[Install Reporting Services extensions for Microsoft Dynamics AX](install-reporting-services-extensions-for-microsoft-dynamics-ax.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

