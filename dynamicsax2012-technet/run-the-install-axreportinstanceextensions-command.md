---
title: Run the Install-AXReportInstanceExtensions command
TOCTitle: Run the Install-AXReportInstanceExtensions command
ms:assetid: 8d7114ff-43d6-4661-906c-5434837bfb64
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn527682(v=AX.60)
ms:contentKeyID: 59626214
ms.date: 06/03/2014
mtps_version: v=AX.60
dev_langs:
- powershell
---

# Run the Install-AXReportInstanceExtensions command 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The Install-AXReportInstanceExtensions command is a Windows PowerShell command that you can use to integrate multiple instances of Microsoft SQL Server Reporting Services—that are running on one computer—with Microsoft Dynamics AX. The Install-AXReportInstanceExtensions command modifies Reporting Services configuration files. If you do not run the Install-AXReportInstanceExtensions command, you must *manually* modify the configuration files, as described in [Modify Reporting Services configuration files](modify-reporting-services-configuration-files.md).

## Prerequisites

Before you can complete the procedures in this topic, you must make sure that the following prerequisites are met.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th> <p>
   
	 Category
  </p> </th>
    <th> <p>
   
	 Prerequisite
  </p> </th>
  </tr>
  <tr>
    <td rowspan="2"> <p>
   
	 Required software
  </p> </td>
    <td> <p>
   
	 Windows PowerShell 2.0 must be installed on the computer that you are using.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Cumulative update 7 for Microsoft Dynamics AX 2012 R2 or Microsoft Dynamics AX 2012 R3 must be installed in the environment.
  </p> </td>
  </tr>
  <tr>
    <td rowspan="2"> <p>
   
	 Required permissions
  </p> </td>
    <td> <p>
   
	 You must be a member of the Administrators group on the server that runs Reporting Services.
  </p> <div><table><tr><th align="left"><img runat="server" AltText="Note" src="https://technet.microsoft.com/en-us/Dn527682.alert_note(AX.60).gif" title="Note" alt="Note" /><strong>Note </strong></th></tr><tr><td> <p>
   
	 If your Windows domain account is assigned to a group that is a member of the Administrators group, it may take some time to validate that you are a member of the Administrators group. If you experience a delay when you run the Install-AXReportInstanceExtensions command, consider adding your Windows domain account directly to the Administrators group.
  </p> </td></tr></table></div></td>
  </tr>
  <tr>
    <td> <p>
   
	 If Reporting Services is running in native mode, you must be assigned to the System Administrator role on the Report Manager website.
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Required tasks
  </p> </td>
    <td>
      <ol>
        <li> <p>
   
	 Configure the initial instance of Reporting Services and integrate it with Microsoft Dynamics AX. To do this, complete the procedures in <a href="checklist-install-the-reporting-services-extensions-and-deploy-reports.md" runat="server" xmlns="http://www.w3.org/1999/xhtml">Checklist: Install the Reporting Services extensions and deploy reports</a>.
  </p> </li>
        <li> <p>
   
	 Install and configure the next instance of Reporting Services. To do this, see <a href="install-the-new-reporting-services-instance.md" runat="server" xmlns="http://www.w3.org/1999/xhtml">Install the new Reporting Services instance</a> and <a href="configure-the-new-reporting-services-instance.md" runat="server" xmlns="http://www.w3.org/1999/xhtml">Configure the new Reporting Services instance</a>.
  </p> </li>
      </ol>
    </td>
  </tr>
</table>


## Make backups of the Reporting Services configuration files

We recommend that you make a backup of each Reporting Services configuration file. Make a backup of each file listed in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>File</p></th>
<th><p>Default location</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Web.config</p></td>
<td><ul>
<li><p>If you are using SQL Server 2008, the default location of this file is: \Program Files\Microsoft SQL Server\MSRS10.[SSRSInstanceName]\Reporting Services\ReportManager.</p></li>
<li><p>If you are using SQL Server 2008 R2, the default location of this file is: \Program Files\Microsoft SQL Server\MSRS10_50.[SSRSInstanceName]\Reporting Services\ReportManager.</p></li>
<li><p>If you are using SQL Server 2012, the default location of this file is: \Program Files\Microsoft SQL Server\MSRS11.[SSRSInstanceName]\Reporting Services\ReportManager.</p></li>
<li><p>If you are using SQL Server 2014, the default location of this file is: \Program Files\Microsoft SQL Server\MSRS12.[SSRSInstanceName]\Reporting Services\ReportManager.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>RsReportServer.config</p></td>
<td><ul>
<li><p>If you are using SQL Server 2008, the default location of this file is: \Program Files\Microsoft SQL Server\MSRS10.[SSRSInstanceName]\Reporting Services\ReportServer.</p></li>
<li><p>If you are using SQL Server 2008 R2, the default location of this file is: \Program Files\Microsoft SQL Server\MSRS10_50.[SSRSInstanceName]\Reporting Services\ReportServer.</p></li>
<li><p>If you are using SQL Server 2012, the default location of this file is: \Program Files\Microsoft SQL Server\MSRS11.[SSRSInstanceName]\Reporting Services\ReportServer.</p></li>
<li><p>If you are using SQL Server 2014, the default location of this file is: \Program Files\Microsoft SQL Server\MSRS12.[SSRSInstanceName]\Reporting Services\ReportServer.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>RsSrvPolicy.config</p></td>
<td><ul>
<li><p>If you are using SQL Server 2008, the default location of this file is: \Program Files\Microsoft SQL Server\MSRS10.[SSRSInstanceName]\Reporting Services\ReportServer.</p></li>
<li><p>If you are using SQL Server 2008 R2, the default location of this file is: \Program Files\Microsoft SQL Server\MSRS10_50.[SSRSInstanceName]\Reporting Services\ReportServer.</p></li>
<li><p>If you are using SQL Server 2012, the default location of this file is: \Program Files\Microsoft SQL Server\MSRS11.[SSRSInstanceName]\Reporting Services\ReportServer.</p></li>
<li><p>If you are using SQL Server 2014, the default location of this file is: \Program Files\Microsoft SQL Server\MSRS12.[SSRSInstanceName]\Reporting Services\ReportServer.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Web.config</p></td>
<td><ul>
<li><p>If you are using SQL Server 2008, the default location of this file is: \Program Files\Microsoft SQL Server\MSRS10.[SSRSInstanceName]\Reporting Services\ReportServer.</p></li>
<li><p>If you are using SQL Server 2008 R2, the default location of this file is: \Program Files\Microsoft SQL Server\MSRS10_50.[SSRSInstanceName]\Reporting Services\ReportServer.</p></li>
<li><p>If you are using SQL Server 2012, the default location of this file is: \Program Files\Microsoft SQL Server\MSRS11.[SSRSInstanceName]\Reporting Services\ReportServer.</p></li>
<li><p>If you are using SQL Server 2014, the default location of this file is: \Program Files\Microsoft SQL Server\MSRS12.[SSRSInstanceName]\Reporting Services\ReportServer.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Run the Install-AXReportInstanceExtensions command

Complete the following procedure to run the Install-AXReportInstanceExtensions command. This command modifies Reporting Services configuration files.

1.  Open Windows PowerShell as an administrator by following these steps:
    
    1.  Click **Start** \> **Administrative Tools**.
    
    2.  Right-click the **Microsoft Dynamics AX 2012 Management Shell** option.
    
    3.  Click **Run as administrator**.

2.  Run the Install-AXReportInstanceExtensions command. Note the following information:
    
      - \[SSRSInstanceName\] is the name of the Reporting Services instance that you are integrating with Microsoft Dynamics AX.
    
      - \[DomainName\\UserName\] is the domain and user name of the Business Connector proxy account.
    
    <!-- end list -->
    
    ``` powershell
    Install-AXReportInstanceExtensions –ReportServerInstanceName [SSRSInstanceName] -Credential [DomainName\UserName]
    ```
    
    For more information about the Install-AXReportInstanceExtensions command, see [Install-AXReportInstanceExtensions](install-axreportinstanceextensions.md).

## Next steps

After you run the Install-AXReportInstanceExtensions command, you must complete these steps to fully integrate the Reporting Services instance with Microsoft Dynamics AX.

1.  [Restart the new Reporting Services instance](restart-the-new-reporting-services-instance.md)

2.  [Create a new Microsoft Dynamics AX configuration](create-a-new-microsoft-dynamics-ax-configuration.md)

3.  [Connect Microsoft Dynamics AX to the new Reporting Services instance](connect-microsoft-dynamics-ax-to-the-new-reporting-services-instance.md)

4.  [Deploy reports for the new Reporting Services instance](deploy-reports-for-the-new-reporting-services-instance.md)

5.  [Revert to the original Microsoft Dynamics AX configuration](revert-to-the-original-microsoft-dynamics-ax-configuration.md)

## See also

[Install multiple instances of Reporting Services on the same computer (for use with Microsoft Dynamics AX)](install-multiple-instances-of-reporting-services-on-the-same-computer-for-use-with-microsoft-dynamics-ax.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

