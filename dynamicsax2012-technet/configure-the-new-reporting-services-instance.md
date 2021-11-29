---
title: Configure the new Reporting Services instance
TOCTitle: Configure the new Reporting Services instance
ms:assetid: 480a18d8-edd6-4f9a-bdc2-ba2a7a842916
ms:mtpsurl: https://technet.microsoft.com/library/Hh389764(v=AX.60)
ms:contentKeyID: 36899744
author: Khairunj
ms.date: 06/03/2014
mtps_version: v=AX.60
---

# Configure the new Reporting Services instance 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Complete the following procedures to configure the new instance of Microsoft SQL Server Reporting Services. This topic assumes that the new instance of Reporting Services meets the version requirements that are listed in [Install multiple instances of Reporting Services on the same computer (for use with Microsoft Dynamics AX)](install-multiple-instances-of-reporting-services-on-the-same-computer-for-use-with-microsoft-dynamics-ax.md).

## Configure the Reporting Services instance by using the Reporting Services Configuration Manager tool

Use the following procedure to configure the new Reporting Services instance.

1.  Click **Start** \> **All Programs** \> **Microsoft SQL Server** \> **Configuration Tools** \> **Reporting Services Configuration Manager** to open Reporting Services Configuration Manager.

2.  Connect to the new Reporting Services instance.

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
    <td><p>Enter the name and password of the account that is used as the Business Connector proxy.</p>
    <div class="alert">

    > [!NOTE]
    > <P>To view the account that is used as the Business Connector proxy, open Microsoft Dynamics AX and then click <STRONG>System administration</STRONG> &gt; <STRONG>Setup</STRONG> &gt; <STRONG>System</STRONG> &gt; <STRONG>System service accounts</STRONG>.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p>Web Service URL</p></td>
    <td><p>Create a virtual directory for the Reporting Services web service. By default, the virtual directory is named <strong>ReportServer</strong>, and the URL is http://[SSRSServerName]:80/ReportServer_[SSRSInstanceName].</p></td>
    </tr>
    <tr class="even">
    <td><p>Database</p></td>
    <td><p>Create a database for the Reporting Services instance.</p></td>
    </tr>
    <tr class="odd">
    <td><p>Report Manager URL</p></td>
    <td><ul>
    <li><p>If Reporting Services is running in native mode, create a virtual directory for Report Manager. Report Manager is the website that reports are published to. By default, the virtual directory is named <strong>Reports</strong>, and the URL is http://[SSRSServerName]:80/Reports_[SSRSInstanceName].</p></li>
    <li><p>If Reporting Services is running in SharePoint integrated mode, skip this page. Report Manager is not used when Reporting Services is running in SharePoint integrated mode.</p></li>
    </ul></td>
    </tr>
    <tr class="even">
    <td><p>E-mail Settings</p></td>
    <td><p>This option is not required. For more information, see the SQL Server documentation.</p></td>
    </tr>
    <tr class="odd">
    <td><p>Execution Account</p></td>
    <td><p>Enter the name and password of the account that is used as the Business Connector proxy.</p></td>
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

After you have configured the Reporting Services instance for local administration, verify that you can access the sites that are listed in the following table.

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
<td><p>http://[SSRSServerName]:80/ReportServer_[SSRSInstanceName]</p></td>
</tr>
<tr class="even">
<td><p>Report Manager</p>
<div class="alert">

> [!NOTE]
> <P>If Reporting Services is running in SharePoint integrated mode, you do not have to verify that you can access this website. Report Manager is not used when Reporting Services is running in SharePoint integrated mode.</P>


</div></td>
<td><p>http://[SSRSServerName]:80/Reports_[SSRSInstanceName]</p></td>
</tr>
</tbody>
</table>

  


