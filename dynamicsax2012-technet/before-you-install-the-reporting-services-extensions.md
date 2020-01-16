---
title: Before you install the Reporting Services extensions
TOCTitle: Before you install the Reporting Services extensions
ms:assetid: 11952a63-2f66-44fa-ae1a-fa0510a94dfe
ms:mtpsurl: https://technet.microsoft.com/library/Ee355041(v=AX.60)
ms:contentKeyID: 28119311
author: Khairunj
ms.date: 06/04/2014
mtps_version: v=AX.60
---

# Before you install the Reporting Services extensions 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before you install the Microsoft SQL Server Reporting Services extensions, you must complete the following procedures.

## Verify that you have the required permissions to install the Reporting Services extensions

To install the Reporting Services extensions, you must have the required permissions. For more information, see [Verify that you have the required permissions for installation](verify-that-you-have-the-required-permissions-for-installation.md).

## Assign system service accounts to the appropriate Active Directory groups

Identify which accounts are used for the following purposes:

  - The account used to run the Microsoft Dynamics AX Application Object Server (AOS)

  - The account used as the Business Connector proxy

Assign the accounts listed above to the following Active Directory groups on the domain server:

  - Windows Authorization Access group

  - Pre-Windows 2000 Compatibility Access group

## Install prerequisites

On the computer where Reporting Services is installed, or where you plan to install Reporting Services, run the prerequisite validation utility to verify that system requirements have been met. For information about how to run the prerequisite validation utility, see [Check prerequisites](check-prerequisites.md).

For more information about the hardware and software requirements for Microsoft Dynamics AX, see the [system requirements](https://go.microsoft.com/fwlink/?linkid=165377).

## Configure Reporting Services in native mode

If you installed Reporting Services in native mode, you must complete the following procedures to configure the Reporting Services instance.

## Configure the Reporting Services instance by using the Reporting Services Configuration Manager tool

Use the following procedure to configure the Reporting Services instance.


> [!NOTE]
> <P>If you installed the Reporting Services instance in its default configuration, Reporting Services is already configured for you. However, we recommend that you complete this procedure to verify that the options are configured correctly.</P>



1.  Click **Start** \> **All Programs** \> **Microsoft SQL Server** \> **Configuration Tools** \> **Reporting Services Configuration Manager** to open Reporting Services Configuration Manager.

2.  Connect to your Reporting Services instance.

3.  Configure the options that are described in the following table. For detailed information about each option, see the SQL Server documentation.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Click this option…</p></th>
    <th><p>To do this…</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>[ServerName]\[InstanceName]</p></td>
    <td><p>Verify that the Reporting Services instance is running. If it is not running, click <strong>Start</strong>.</p></td>
    </tr>
    <tr class="even">
    <td><p>Service Account</p></td>
    <td><p>The action that you should take depends on the configuration mode that you selected when you installed the Reporting Services instance.</p>
    <ul>
    <li><p>If you installed the default configuration for native mode, no action is required. The service account is set to the account that you specified when you installed the Reporting Services instance.</p></li>
    <li><p>If you installed but did not configure the report server, select the Network Service built-in account.</p></li>
    </ul>
    <div class="alert">

    > [!NOTE]
    > <P>When you install the Reporting Services extensions, the Business Connector proxy account is automatically assigned as the service account for the Reporting Services instance.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p>Web Service URL</p></td>
    <td><p>Create a virtual directory for the Reporting Services web service. By default, the virtual directory is named <strong>ReportServer</strong>, and the URL is http://[SSRSServerName]:80/ReportServer.</p></td>
    </tr>
    <tr class="even">
    <td><p>Database</p></td>
    <td><p>Create a database for the Reporting Services instance. By default, the database is named <strong>ReportServer</strong>.</p></td>
    </tr>
    <tr class="odd">
    <td><p>Report Manager URL</p></td>
    <td><p>Create a virtual directory for Report Manager. Report Manager is the website that reports are published to. By default, the virtual directory is named <strong>Reports</strong>, and the URL is http://[SSRSServerName]:80/Reports.</p></td>
    </tr>
    <tr class="even">
    <td><p>E-mail Settings</p></td>
    <td><p>This option is not required. For more information, see the SQL Server documentation.</p></td>
    </tr>
    <tr class="odd">
    <td><p>Execution Account</p></td>
    <td><p>Take no action.</p>
    <div class="alert">

    > [!NOTE]
    > <P>When you install the Reporting Services extensions, the Business Connector proxy account is automatically assigned as the execution account for the Reporting Services instance.</P>


    </div></td>
    </tr>
    <tr class="even">
    <td><p>Encryption Keys</p></td>
    <td><p>This option is not required. For more information, see the SQL Server documentation.</p></td>
    </tr>
    <tr class="odd">
    <td><p>Scale-out Deployment</p></td>
    <td><p>This option is not required. For more information, see the SQL Server documentation.</p></td>
    </tr>
    </tbody>
    </table>


4.  Click **Exit** to close Reporting Services Configuration Manager.

## Configure the Reporting Services instance for local administration

To administer an instance of the report server locally, you must complete additional configuration steps when you deploy Reporting Services on Windows Server 2008. Windows Server 2008 limits the overuse of elevated permissions by removing administrator permissions when you access applications. If you are a member of the local Administrators group, you run most applications as if you are using the Standard User account because the operating system removes permissions.

Although this practice improves the overall security of your system, it prevents you from using the predefined, built-in role assignments that Reporting Services creates for local administrators. However, by completing additional configuration steps, you can manage the report server's content and operations by using standard user permissions. For instructions, see [How to: Configure a Report Server for Local Administration on Windows Vista and Windows Server 2008](https://technet.microsoft.com/library/bb630430.aspx) on TechNet.

After you have configured the Reporting Services instance for local administration, verify that you can access the websites that are listed in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Website</p></th>
<th><p>Default URL</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Reporting Services web service</p></td>
<td><p>http://[SSRSServerName]:80/ReportServer</p></td>
</tr>
<tr class="even">
<td><p>Report Manager</p></td>
<td><p>http://[SSRSServerName]:80/Reports</p></td>
</tr>
</tbody>
</table>


## Configure Reporting Services in SharePoint integrated mode

If you installed Reporting Services in SharePoint integrated mode, use one of the following procedures to configure the Reporting Services instance. The procedure that you should use depends on the version of SQL Server that you are using.


> [!NOTE]
> <P>SharePoint integrated mode is supported if you are using Microsoft Dynamics AX 2012 R2 or later.</P>



## Configure Reporting Services 2008 in SharePoint integrated mode

If you are using Reporting Services 2008 or Reporting Services 2008 R2, follow these steps to configure Reporting Services in SharePoint integrated mode.

1.  Configure Reporting Services by using the following topics in the SQL Server documentation:
    
      - [How to: Install and Configure SharePoint Integration on a Stand-alone Server](https://technet.microsoft.com/library/bb677368\(sql.105\).aspx)
    
      - [How to: Install and Configure SharePoint Integration on Multiple Servers](https://technet.microsoft.com/library/bb677365\(sql.105\).aspx)
    

    > [!NOTE]
    > <P>When you configure Reporting Services, set the Reporting Services service account and execution account to the Business Connector proxy account.</P>



2.  Configure the Reporting Services integration in SharePoint Central Administration. For more information, see [How to: Configure Report Server Integration in SharePoint Central Administration](https://technet.microsoft.com/library/bb326213\(sql.105\).aspx) in the SQL Server documentation.

3.  Verify that you can access the websites that are listed in the following table.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Website</p></th>
    <th><p>Default URL</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>Reporting Services web service</p></td>
    <td><p>http://[SSRSServerName]:80/ReportServer</p></td>
    </tr>
    <tr class="even">
    <td><p>SharePoint site</p></td>
    <td><p>The URL of the SharePoint site varies based on the URL that you provided when you created the site collection. The URL of the SharePoint site may be:</p>
    <p>http://[SharePointServerName]:[PortNumber]</p>
    <p>-or-</p>
    <p>http://[SharePointServerName]:[PortNumber]/sites/[SiteName]</p></td>
    </tr>
    </tbody>
    </table>


## Configure Reporting Services 2012 or 2014 in SharePoint integrated mode

If you are using Reporting Services 2012 or 2014, follow these steps to configure Reporting Services in SharePoint integrated mode.

1.  Configure Reporting Services by using the following topics in the SQL Server documentation:
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>If you are using SharePoint 2010, see these topics:</p></th>
    <th><p>If you are using SharePoint 2013, see these topics:</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><ul>
    <li><p><a href="https://technet.microsoft.com/library/gg492276.aspx">Install Reporting Services SharePoint Mode for SharePoint 2010</a></p>
    <div class="alert">

    > [!IMPORTANT]
    > <P>When installing Reporting Services 2012 in SharePoint integrated mode, be sure that you <STRONG>do not</STRONG> mark the <STRONG>Reporting Services – Native</STRONG> option on the <STRONG>Feature Selection</STRONG> page of the SQL Server Setup Wizard.</P>


    </div></li>
    <li><p><a href="https://technet.microsoft.com/library/hh479774.aspx">Add an Additional Report Server to a Farm (SSRS Scale-out)</a></p></li>
    <li><p><a href="https://technet.microsoft.com/library/hh479775.aspx">Add an Additional Reporting Services Web Front-end to a Farm</a></p></li>
    </ul></td>
    <td><ul>
    <li><p><a href="https://msdn.microsoft.com//library/jj219068.aspx">Install Reporting Services SharePoint Mode for SharePoint 2013</a></p>
    <div class="alert">

    > [!IMPORTANT]
    > <P>When installing Reporting Services 2012 in SharePoint integrated mode, be sure that you <STRONG>do not</STRONG> mark the <STRONG>Reporting Services – Native</STRONG> option on the <STRONG>Feature Selection</STRONG> page of the SQL Server Setup Wizard.</P>


    </div></li>
    <li><p><a href="https://technet.microsoft.com/library/hh479774.aspx">Add an Additional Report Server to a Farm (SSRS Scale-out)</a></p></li>
    <li><p><a href="https://technet.microsoft.com/library/hh479775.aspx">Add an Additional Reporting Services Web Front-end to a Farm</a></p></li>
    </ul></td>
    </tr>
    </tbody>
    </table>


2.  If you did not create a site collection when installing and configuring SharePoint, create one now. If you are using SharePoint 2010, see the instructions [here](https://technet.microsoft.com/library/cc263094\(v=office.14\).aspx). If you are using SharePoint 2013, see the instructions [here](https://technet.microsoft.com/library/cc263094\(v=office.15\).aspx).

3.  Verify that you can access the websites that are listed in the following table.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Website</p></th>
    <th><p>Default URL</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>Reporting Services web service</p></td>
    <td><p>The URL of the Reporting Services web service varies based on the URL that you provided when you created the site collection. The URL of the Reporting Services web service may be:</p>
    <p>http://[SharePointServerName]:[PortNumber]/_vti_bin/ReportServer</p>
    <p>-or-</p>
    <p>http://[SharePointServerName]:[PortNumber]/sites/[SiteName]/_vti_bin/ReportServer</p></td>
    </tr>
    <tr class="even">
    <td><p>SharePoint site</p></td>
    <td><p>The URL of the SharePoint site varies based on the URL that you provided when you created the site collection. The URL of the SharePoint site may be:</p>
    <p>http://[SharePointServerName]:[PortNumber]</p>
    <p>-or-</p>
    <p>http://[SharePointServerName]:[PortNumber]/sites/[SiteName]</p></td>
    </tr>
    </tbody>
    </table>
    
    For more information about how to verify that the integration is configured correctly, see [Verify a Reporting Services Installation](https://technet.microsoft.com/library/ms143773.aspx) in the SQL Server documentation.

  


