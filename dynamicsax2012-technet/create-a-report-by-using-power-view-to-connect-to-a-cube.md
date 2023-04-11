---
title: Create a report by using Power View to connect to a cube
TOCTitle: Create a report by using Power View to connect to a cube
ms:assetid: 09cc9238-9944-4085-a5de-64d907b70cf3
ms:mtpsurl: https://technet.microsoft.com/library/JJ933492(v=AX.60)
ms:contentKeyID: 50935106
author: tonyafehr
ms.date: 05/02/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create a report by using Power View to connect to a cube 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Power View is a tool that you can use to create highly-interactive, ad-hoc reports. This article helps you create a Power View report that displays data from a Microsoft SQL Server Analysis Services cube. To create the report, you must first select the cube that you want to use, and create a data source to connect to that cube. Then, you can create the Power View report by selecting the fields that you want to display on the report. Finally, if you are a system administrator, you can display the report in a web part on a Role Center page in Microsoft Dynamics AX.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><img src="images/Dd309683.TopicIcons_Task(AX.60).png" title="Tasks" alt="Tasks" />
<p>1. Verify prerequisites</p>
<p>2. Create a data source to connect to a cube</p>
<p>3. Create the report</p>
<p>4. Display the report on a Role Center page</p></td>
<td><img src="images/Dn507140.TopicIcons_Resources(AX.60).png" title="Resources" alt="Resources" />
<p><a href="walkthrough-creating-an-analyze-data-button-on-a-list-page.md">Walkthrough: Creating an Analyze Data Button on a List Page</a> (article)</p>
<p><a href="https://office.microsoft.com/excel-help/power-view-explore-visualize-and-present-your-data-ha102835634.aspx">Power View documentation</a> (articles)</p>
<p><a href="https://blogs.msdn.com/b/dynamicsaxbi/archive/2012/12/11/better-together_2d00_microsoft-dynamics-ax-2012-r2-and-sql-server-power-view.aspx">Better together: Microsoft Dynamics AX 2012 R2 and SQL Server Power View</a> (blog post)</p></td>
</tr>
</tbody>
</table>


## 1\. Verify prerequisites

To complete the procedures in this topic, verify that the following requirements are in place.

## Required software

The following software must be installed in the Microsoft Dynamics AX environment:

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Requirement</p></th>
<th><p>Notes</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Microsoft Excel</p></td>
<td><p>Excel 2013 Professional Plus Edition</p></td>
</tr>
<tr class="even">
<td><p>Microsoft SharePoint Server 2010 or 2013 Enterprise Edition must be installed.</p></td>
<td><p>For information about how to install SharePoint Server 2010, see <a href="https://technet.microsoft.com/library/cc262957(v=office.14)">Deployment for SharePoint Server 2010</a>.</p>
<p>For information about how to install SharePoint Server 2013, see <a href="https://technet.microsoft.com/library/cc303424.aspx">Install SharePoint 2013</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Microsoft SQL Server Reporting Services 2012 Service Pack 1 must be installed in SharePoint integrated mode with <a href="https://support.microsoft.com/kb/2833645/en-us">cumulative update 4</a> applied.</p>
<p>-OR-</p>
<p>Microsoft SQL Server Reporting Services 2014 must be installed in SharePoint integrated mode.</p></td>
<td><p>For information about how to install Reporting Services in SharePoint integrated mode, see the <strong>Configure Reporting Services 2012 or 2014 in SharePoint integrated mode</strong> section of <a href="before-you-install-the-reporting-services-extensions.md">Before you install the Reporting Services extensions</a>.</p>
<p>If you install Reporting Services 2014, you must modify the SharePoint web.config file. This file is typically located at C:\Inetpub\wwwroot\wss\VirtualDirectories\80. Add the following line of code to the <strong>appSettings</strong> section:</p>
<pre><code>&lt;add key=&quot;DynamicsAxPowerViewSQLVersion&quot; value=&quot;12&quot;/&gt;</code></pre></td>
</tr>
<tr class="even">
<td><p>Microsoft SQL Server Analysis Services 2012 Service Pack 1 must be installed in multidimensional mode with <a href="https://support.microsoft.com/kb/2833645/en-us">cumulative update 4</a> applied.</p>
<p>-OR-</p>
<p>Microsoft SQL Server Analysis Services 2014 must be installed in multidimensional mode.</p></td>
<td><p>For information about how to install Analysis Services in multidimensional mode, see <a href="https://technet.microsoft.com/library/ms143708.aspx">Install Analysis Services in multidimensional and data mining mode</a>.</p>
<p>If you install Analysis Services 2014, you must modify the SharePoint web.config file. This file is typically located at C:\Inetpub\wwwroot\wss\VirtualDirectories\80. Add the following line of code to the <strong>appSettings</strong> section:</p>
<pre><code>&lt;add key=&quot;DynamicsAxPowerViewSQLVersion&quot; value=&quot;12&quot;/&gt;</code></pre></td>
</tr>
<tr class="odd">
<td><p>The Power View site collection feature in SharePoint must be activated.</p></td>
<td><p>For information about how to activate this feature, see the <strong>Active the Power View Site Collection Feature</strong> section of <a href="https://technet.microsoft.com/library/gg492276.aspx">Install Reporting Services SharePoint Mode as a Single Server Farm</a>.</p></td>
</tr>
<tr class="even">
<td><p>Microsoft Dynamics AX 2012 R2 with cumulative update 6 or higher, or Microsoft Dynamics AX 2012 R3 must be installed. The following components are required:</p>
<ul>
<li><p>Enterprise Portal and Role Centers must be deployed to SharePoint.</p></li>
<li><p>The cubes that are included with Microsoft Dynamics AX must be deployed to Analysis Services.</p></li>
</ul></td>
<td><p>For information about how to install Microsoft Dynamics AX, see <a href="install-microsoft-dynamics-ax-2012.md">Install Microsoft Dynamics AX 2012</a>.</p>
<p>For information about how to deploy Enterprise Portal and Role Centers, see <a href="checklist-deploy-an-internal-enterprise-portal-site-that-has-role-centers.md">Checklist: Deploy an internal Enterprise Portal site that has Role Centers</a>.</p>
<p>For information about how to deploy the cubes, see <a href="checklist-configure-analysis-services-and-deploy-cubes.md">Checklist: Configure Analysis Services and deploy cubes</a>.</p>
<p>If Power View is not enabled in the environment before Role Centers are deployed, you may need to complete the following steps to redeploy some specific Role Center pages. Keep in mind, when you redeploy the Role Center pages, you will lose customizations made to the pages.</p>
<ol>
<li><p>Open the Microsoft Dynamics AX client with administrator privileges.</p></li>
<li><p>Open the AOT.</p></li>
<li><p>Expand the <strong>Web</strong> &gt; <strong>Web Files</strong> &gt; <strong>Page Definitions</strong> node.</p></li>
<li><p>Right-click <strong>RoleCenterCFOPV</strong> and click <strong>Deploy Element</strong>.</p></li>
<li><p>Right-click <strong>RoleCenterTreasurerPV</strong> and click <strong>Deploy Element</strong>.</p></li>
<li><p>Right-click <strong>PowerViewDataSourceGeneratorPV</strong> and click <strong>Deploy Elements</strong>.</p></li>
</ol>
<p>If you receive errors when trying to redeploy the files listed above, you may need to complete the following steps:</p>
<ol>
<li><p>In the AOT, expand the <strong>Classes</strong> node.</p></li>
<li><p>Verify that the <strong>SrsReportHelper</strong> class includes the <strong>removeFromCache</strong> method.</p></li>
<li><p>Right-click the <strong>removeFromCache</strong> method and click <strong>Compile</strong>.</p>
<p>The method should compile without errors or warnings.</p></li>
<li><p>Click <strong>Build</strong> &gt; <strong>Generate Incremental CIL</strong>.</p>
<p>When the process is complete, the <strong>Infolog</strong> form will appear and display a message stating that the incremental CIL generation is done.</p></li>
<li><p>Redeploy the page definitions mentioned in the previous procedure.</p></li>
</ol></td>
</tr>
</tbody>
</table>


## Required permissions

To create a Power View report, you must have the permissions listed in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>To create a Power View report, you must:</p></th>
<th><p>Articles that explain how system administrators can give you permission:</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Be assigned to a Microsoft Dynamics AX role.</p></td>
<td><p><a href="assign-users-to-security-roles.md">Assign users to security roles</a></p></td>
</tr>
<tr class="even">
<td><p>Have permission to view reports in SharePoint.</p></td>
<td><p><a href="security-settings-for-reports.md">Security settings for reports</a> (See the <strong>Configure security settings in SharePoint</strong> section.)</p></td>
</tr>
<tr class="odd">
<td><p>Be assigned to a role in Analysis Services that has access to the cube that you want to use.</p></td>
<td><p><a href="grant-users-access-to-cubes.md">Grant users access to cubes</a></p>
<p><a href="default-analysis-services-roles.md">Default Analysis Services roles</a></p></td>
</tr>
</tbody>
</table>


## 2\. Create a data source to connect to a cube

The first step is to determine which cube contains the data that you want to display on the report. To view the data that is contained in each cube, see [Cube and KPI reference for Microsoft Dynamics AX 2012 R2](cube-and-kpi-reference-for-microsoft-dynamics-ax-2012-r2-and-r3.md).

After you determine which cube you want to use, you may need to create a data source to connect to that cube. By default, data sources that connect to the Accounts payable, Accounts receivable, General ledger, and Sales cubes have been created for you. If you want to display data from any other cube, you must use the following procedure to create the data source.

1.  Open your browser and go to the Enterprise Portal site. The URL for the Enterprise Portal site is typically http://\[SharePointServerName\]/sites/DynamicsAX.
    

    > [!NOTE]
    > <P>For security reasons, integrating Power View with Microsoft Dynamics AX is not supported in environments where the Enterprise Portal site is configured for multiple data partitions.</P>



2.  Go to the **Power View Reports** folder. The URL for this folder is typically http://\[SharePointServerName\]/sites/DynamicsAX/Power%20View%20Reports.

3.  Click **Documents** \> **New Document** \> **Report Data Source**. The **Data Source Properties** page is displayed.

4.  In the **Name** field, enter a name for the data source. For example, if the data source will connect to the Retail cube, you may want to name the data source *Retail cube*.

5.  In the **Data Source Type** area, select **Microsoft BI Semantic Model for Power View**.

6.  In the **Connection string** area, enter the following connection string:
    
    Provider=MSOLAP.4;Integrated Security=SSPI;Persist Security Info=True;Data Source=\[ServerName\];Initial Catalog=\[DatabaseName\];Locale identifier=\[LocaleID\];Cube=\[CubeName\]
    
    The following table lists the documentation conventions that are used in the connection string.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Value</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>[ServerName]</p></td>
    <td><p>The name of the server on which Analysis Services is installed.</p></td>
    </tr>
    <tr class="even">
    <td><p>[DatabaseName]</p></td>
    <td><p>The name of the Analysis Services database that contains the cube that you want to connect to.</p></td>
    </tr>
    <tr class="odd">
    <td><p>[LocaleID]</p></td>
    <td><p>The identifier that designates the language of the labels to display on the report. For example, if you want measures and dimensions to be shown in German, you must add German translations to the cube and specify the locale identifier for German.</p>
    <p>For more information about how to add translations to a cube, see <a href="how-to-update-an-existing-sql-server-analysis-services-project.md">Update an Existing SQL Server Analysis Services Project</a>. For a list of the locales that are supported by both Enterprise Portal and SharePoint, see <a href="install-enterprise-portal-on-a-single-server.md">Install Enterprise Portal on a single server</a>.</p></td>
    </tr>
    <tr class="even">
    <td><p>[CubeName]</p></td>
    <td><p>The name of the cube that contains the data that you want to display on the report.</p></td>
    </tr>
    </tbody>
    </table>
    
    For example, if you want to connect to the Retail cube that is provided with Microsoft Dynamics AX, the default connection string is:
    
    Provider=MSOLAP.4;Integrated Security=SSPI;Persist Security Info=True;Data Source=\[ServerName\];Initial Catalog=Dynamics AX initial;Locale identifier=1033;Cube=Retail cube

7.  In the **Credentials** area, select **Windows authentication (integrated) or SharePoint user**.
    

    > [!NOTE]
    > <P>If Analysis Services and Enterprise Portal are installed on different computers, you must use Kerberos security. To configure Kerberos security, see <A href="https://www.microsoft.com/en-us/download/details.aspx?id=16080">this white paper.</A> After you have configured Kerberos security to work with the servers, complete the following steps:</P>
    > <OL>
    > <LI>
    > <P>In the <STRONG>Credentials</STRONG> area, select <STRONG>Stored credentials</STRONG>.</P>
    > <LI>
    > <P>Enter the user name and the password for the account that is assigned to the Analysis Services server administrator role. In most cases, this is the Business Connector proxy account. For more information, see the <STRONG>Assign the Business Connector proxy account to the Analysis Services server administer role</STRONG> section in <A href="before-you-configure-analysis-services.md">Before you configure Analysis Services</A>.</P>
    > <LI>
    > <P>Select the <STRONG>Use as Windows credentials</STRONG> check box.</P>
    > <LI>
    > <P>Select the <STRONG>Set execution context to this account</STRONG> check box.</P></LI></OL>



8.  Click **Test Connection** to verify the connection to the cube.

9.  In the **Availability** area, select the **Enable this data source** check box.

10. Click **OK**. The data source is created.

## 3\. Create the report

To create and design the Power View report, complete the following procedure.

1.  Go to the **Power View Reports** folder. The URL for this folder is typically http://\[SharePointServerName\]/sites/DynamicsAX/Power%20View%20Reports.

2.  Click the data source that you created in the previous procedure. A blank, untitled Power View report is displayed in your browser.

3.  To add fields to the report, select the fields in the **Field List** pane, or drag the fields onto the report.
    
    For example, suppose that you want to create a report that shows sales amounts for your retail stores. In this scenario, you would:
    
    1.  Expand the **Retail channel** node and select **Retail channel – Name**.
    
    2.  Expand the **Customer invoice lines** node, and select **Customer invoice line amount – accounting currency**.
    
    3.  Expand the **Date** node and drag **Month** to the **Filters** area of the report.

4.  Enter a name for the report in the title area.

5.  Use the options on the **Styles**, **Design**, and **Layout** tabs to format the report as necessary. For more information about how to use the Power View options to format the report, see [Power View Design Experience](https://technet.microsoft.com/library/hh231518.aspx) in the SQL Server documentation.

6.  Save the report.

## 4\. Display the report on a Role Center page

To display the report in a web part on a Role Center page, complete the following procedure. You must be a Microsoft Dynamics AX system administrator to complete this procedure.

If you’d rather display a link to the report in the Quick Links web part on a Role Center page, follow the instructions in [Manage quick links (Enterprise Portal)](manage-quick-links-enterprise-portal.md).

1.  Open the Microsoft Dynamics AX client.

2.  Click **System administration** \> **Common** \> **Users** \> **User profiles**. The **User profiles** form is displayed.

3.  Select the Role Center that will display the report.

4.  Click **View role center**. Your browser opens and displays that Role Center page.

5.  Click **Site Actions** \> **Edit Page**. The page is displayed in design mode.

6.  Find the location where you want to display the report, and click **Add a Web Part** in that area. The top of the page now displays an area where you can select the web part that you want to add.

7.  To select the web part that you want to add, do the following:
    
    1.  In the **Categories** area, select **Microsoft Dynamics AX**.
    
    2.  In the **Web Parts** area, select **SQL Server Power View**.
    
    3.  In the **About the Web Part** area, click **Add**.
    
    The SQL Server Power View web part is displayed on the page.

8.  In the web part’s menu, click **Edit Web Part**. The web part’s properties pane, where you can configure the web part, is displayed on the right side of the page.

9.  To configure the web part, do the following:
    
    1.  In the **Select a report** area, click the **Browse** icon to select the Power View report that you created.
    
    2.  In the **Title** field, enter an appropriate name for the web part.
    
    3.  Set the **Height** and **Width** properties so that the web part is displayed optimally on the page.
    
    4.  Click **OK** to save your changes.

  


