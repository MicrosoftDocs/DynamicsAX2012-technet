---
title: Verify system settings using the Microsoft Baseline Configuration Analyzer
TOCTitle: Verify system settings using the Microsoft Baseline Configuration Analyzer
ms:assetid: acf750c4-d6f1-493c-9b93-3625a29032ab
ms:mtpsurl: https://technet.microsoft.com/library/Hh500673(v=AX.60)
ms:contentKeyID: 37822172
author: tonyafehr
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Verify system settings using the Microsoft Baseline Configuration Analyzer 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to use Microsoft Baseline Configuration Analyzer 2.0 (MBCA 2.0) to help maintain system configurations for Microsoft Dynamics AX components. MBCA 2.0 analyzes Microsoft Dynamics AX configurations against a predefined set of best practices, and then reports the results of the analysis. By using MBCA 2.0, you can analyze configurations for the following Microsoft Dynamics AX components:

  - Microsoft SQL Server Analysis Services for Microsoft Dynamics AX

  - Application Object Server (AOS)

  - The Microsoft Dynamics AX database

  - Enterprise Portal for Microsoft Dynamics AX

  - Microsoft SQL Server Reporting Services for Microsoft Dynamics AX

## Before you begin

Verify system requirements on the [Microsoft Baseline Configuration Analyzer 2.0](https://go.microsoft.com/fwlink/?linkid=228454) download site. After you verify system requirements, download and install MBCA 2.0 on an AOS instance where you want to analyze configurations. You do not have to install MBCA on every component server for Microsoft Dynamics AX. After MBCA is installed on an AOS instance, you can run it against remote component servers if all the following criteria are met:

1.  You are a member of the Windows Administrators group on the component server.

2.  Windows PowerShell version 2.0 is installed on the component server.

3.  In Windows PowerShell, you run the set-executionPolicy command and specify, at a minimum, the RemoteSigned execution policy on the component server.

## Prepare the server for MBCA

Before you can run MBCA on the server, you must run the following commands in Windows PowerShell to ensure connectivity and valid credentials. These commands are required for MBCA. For more information about the commands, see Windows PowerShell Help.

1.  On the AOS instance where you want to analyze configurations, open a Command Prompt window for Windows PowerShell as an administrator.

2.  Type the following command, and then press ENTER to enable WinRM on the server:
    
    enable-psremoting -f

3.  Type the following command and then press ENTER to enable CredSSP authentication to send user credentials on this server to a remote computer:
    
    enable-wsmanCredSSP -role Client -DelegateComputer Computer fully-qualified domain name
    
    For example: enable-wsmanCredSSP -role Client -DelegateComputer TestServer1.contoso.com
    
    When you are prompted, press Y.

4.  Type the following command and then press ENTER to enable CredSSP authentication to accept user credentials from a remote server:
    
    enable-WSManCredSSP -role Server
    
    When you are prompted, press Y.

5.  Verify that the server is configured correctly to run MBCA. Type the following command, and then press ENTER:
    
    $c = get-credential
    
    When you are prompted, enter the credentials of an AOS administrator.

6.  enter-PsSession -computerName localhost -auth credssp -cred $c
    
    The command is successful if it runs without errors.

## Verify system settings by using MBCA

1.  Download and install the [Microsoft Dynamics AX 2012 MBCA models](https://go.microsoft.com/fwlink/?linkid=228905) on the AOS instance.

2.  Open MBCA. Click **Start**, click **All Programs**, and then click **Microsoft Baseline Configuration Analyzer 2.0**.

3.  In the **Select a product** list, select the model for a Microsoft Dynamics AX component.

4.  Click **Start Scan**.

5.  Enter the required parameters. The following table includes examples of the parameters for each component.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Component</p></th>
    <th><p>Parameters</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>Microsoft Dynamics AX 2012 Analysis Services model</p></td>
    <td><p>For a default instance, enter parameters in the form ServerName. For a remote server, enter parameters in the form ServerName\InstanceName.</p></td>
    </tr>
    <tr class="even">
    <td><p>Microsoft Dynamics AX 2012 Application Object Server (AOS) model</p></td>
    <td><p>Enter parameters in the form of a number. For example, the name of the default instance is 01. Separate the names of multiple AOS instances by using a comma. For example, enter 01, 02. For a remote AOS instance, enter parameters in the form Server Name\Instance Name.</p></td>
    </tr>
    <tr class="odd">
    <td><p>Microsoft Dynamics AX 2012 database model</p></td>
    <td><p>Enter the name of the Microsoft Dynamics AX database. For example, the name of the default instance is MicrosoftDynamicsAX. If the database includes a named instance, enter parameters in the form ServerName$InstanceName\DatabaseName. For a remote server, enter parameters in the form ServerName\InstanceName.</p></td>
    </tr>
    <tr class="even">
    <td><p>Microsoft Dynamics AX 2012 Enterprise Portal model</p></td>
    <td><p>Enter the full URL as it appears in the <strong>External URL</strong> field in the <strong>Web sites</strong> form. For example, the default URL is http://&lt;machine-name&gt;/Sites/DynamicsAx.</p></td>
    </tr>
    <tr class="odd">
    <td><p>Microsoft Dynamics AX 2012 Reporting Services model</p></td>
    <td><p>Enter the full URL as it appears in the <strong>Web service URL</strong> field in the <strong>Report servers</strong> form. For example, the default URL is http://&lt;machine-name&gt;/ReportServer.</p></td>
    </tr>
    <tr class="even">
    <td><p>Credentials</p></td>
    <td><p>Enter the user name and password of a Microsoft Dynamics AX administrator.</p></td>
    </tr>
    </tbody>
    </table>
    
    Click **Start Scan**.

6.  After the scan is completed, review the report, and perform the actions that the report recommends.

## See also

[System maintenance tasks](system-maintenance-tasks.md)

[Application Object Servers](application-object-servers.md)

[Enterprise Portal and Role Centers](enterprise-portal-and-role-centers.md)

[System setup for Microsoft Dynamics AX](system-setup-for-microsoft-dynamics-ax.md)

  


