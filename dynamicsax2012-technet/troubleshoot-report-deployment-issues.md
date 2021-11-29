---
title: Troubleshoot Report Deployment Issues
TOCTitle: Troubleshoot Report Deployment Issues
ms:assetid: af490e4f-607e-47ae-be12-a5cecb7b9ec7
ms:mtpsurl: https://technet.microsoft.com/library/Gg724094(v=AX.60)
ms:contentKeyID: 35133452
author: Khairunj
ms.date: 04/17/2013
mtps_version: v=AX.60
---

# Troubleshoot Report Deployment Issues 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic provides information that can help you troubleshoot issues that you may encounter when you deploy Microsoft Dynamics AX reports.

For more information about how to troubleshoot Microsoft SQL Server Reporting Services reports, see [Troubleshooting Report Problems](https://go.microsoft.com/fwlink/?linkid=200936) in the SQL Server documentation.

## Why won’t my report deploy?

The following table provides possible issues and troubleshooting details for common deployment issues.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Issue</p></th>
<th><p>More information for troubleshooting</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Unable to deploy the report in Visual Studio</p></td>
<td><ul>
<li><p>Try to build the report. If there are errors, address the errors, and then try to deploy the report again.</p></li>
<li><p>If User Account Control (UAC) is enabled, disable UAC, or start Microsoft Dynamics AX with administrator privileges. Click the <strong>Start</strong> menu, point to <strong>All Programs</strong>, click the <strong>Microsoft Dynamics AX</strong> folder, right-click <strong>Microsoft Dynamics AX</strong>, and then click <strong>Run as administrator</strong>.</p>
<p>When you start Visual Studio by using <strong>Edit</strong> on the Application Object Tree (AOT) menu for the report, it starts with administrator privileges. Try to deploy the report.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Unable to deploy the report in the AOT</p></td>
<td><ul>
<li><p>Try to build the report. If there are errors, address the errors, and then try to deploy the report again.</p></li>
<li><p>If UAC is enabled, disable UAC, or start Microsoft Dynamics AX with administrator privileges. To do so, click the <strong>Start</strong> menu, point to <strong>All Programs</strong>, click the <strong>Microsoft Dynamics AX</strong> folder, right-click <strong>Microsoft Dynamics AX</strong>, and then click <strong>Run as administrator</strong>.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Why doesn’t deploying the report overwrite the old report?

The following list describes two scenarios and the steps to troubleshoot reports that are not updated.

  - The deployed report is not updated after you modify the report in Visual Studio.
    
    Follow these steps to update the Report Definition Language (RDL) and the data for the report:
    
    1.  In the AOT, expand the **SSRS Reports** node, right-click the **Reports** node, and then click **Refresh**.
    
    2.  Expand the **Reports** node, right-click the report to update, and then click **Restore**. The RDL and the data that is rendered on the report are updated.
        

        > [!NOTE]
        > <P>You can also update the cache. In a Development Workspace, on the <STRONG>Tools</STRONG> menu, click <STRONG>Caches</STRONG>, and then click <STRONG>Refresh elements</STRONG>.</P>



  - The deployed report is not updated after you add a default value to an existing parameter and then deploy the report.
    
    There are two options to resolve this issue:
    
      - Update the default value in Reporting Services Report Manager.
    
      - Delete the report before you deploy it.
        

        > [!NOTE]
        > <P>We do not recommend this option if you use the report history or subscriptions, because these are bound to the report and are deleted together with it.</P>



## Why do I get a permission error when I try to deploy a report?

The most common reasons for permission errors are as follows:

  - UAC is enabled. Run the applications that you are deploying reports from as the administrator. Right-click the application, and then click **Run as administrator**.

  - You are not a member of the local Administrators group on the report server.

  - You have not configured Reporting Services for local administration.
    
    If you want to administer a report server instance locally, you must complete additional configuration steps to deploy Reporting Services on Windows Server 2008. Windows Server 2008 limits the overuse of elevated permissions by removing administrator permissions when users try to access applications. Because the operating system removes permissions, members of the local Administrators group run most applications as if they are using the Standard User account. Although this practice improves the overall security of a system, it prevents you from using the predefined, built-in role assignments that Reporting Services creates for local administrators.
    
    For information about how to fix this issue, see [How to: Configure a Report Server for Local Administration on Windows Vista and Windows Server 2008 (UAC)](https://go.microsoft.com/fwlink/?linkid=200938).

## Why do I get a permission error when I try to access the Report Manager website?

When you try to access the Report Manager website, you may receive the following permission error:

*User '\[DomainName\]\\\[UserName\]' does not have required permissions. Verify that sufficient permissions have been granted and Windows User Account Control (UAC) restrictions have been addressed.*

By default, you cannot access the Report Manager website if UAC is enabled. To access the Report Manager site when UAC is enabled, follow these steps.

1.  Open your browser as an administrator. To open Internet Explorer as an administrator, follow these steps:
    
    1.  Click **Start**.
    
    2.  Right-click the **Internet Explorer** option.
    
    3.  Click **Run as administrator**.

2.  Open the Report Manager website. By default, the URL is http://\[SSRSServerName\]:80/Reports.

## Why does my report deployment throw this error: Unrecognized element 'extendedProtectionPolicy'?

When you deploy the report, you are running an application that is based on Windows Communication Foundation. The application uses the extendedProtectionPolicy type. The underlying .NET Framework 2.0 SP2 Network Client Library feature layer is not updated when the Windows Communication Foundation feature layer is updated to use the new type. The underlying .NET Framework 2.0 SP2 Network Client Library feature layer does not support this new type.

For information about why this occurred, and to download the hotfix, see [Microsoft Support Article 2262911](https://go.microsoft.com/fwlink/?linkid=200940).

## Why do I receive a network path error when I try to deploy a report?

When you try to deploy a report, you may receive the following error:

*The network path was not found.*

To resolve this issue, you may have to start the Remote Registry service on the server that runs Reporting Services. Follow these steps to start the service.

1.  Click **Start** \> **Administrative Tools** \> **Services** to open the **Services** management console.

2.  Right-click the **Remote Registry** service, and then click **Start**.

## Why do I receive a SQL connection error when I try to deploy a report?

Deployment failures can be expected if more than one developer is trying to deploy a report. Deployment often requires a service restart, which affects other active deployments.

## Why do I receive a security access fault when I try to deploy a report?

You must be a local administrator on the report server to deploy reports.

## How do I deploy reports after I receive a file locked error?

When you deploy reports, you may receive the following error:

*The process cannot access the file '\[ReportName\].dll' because it is being used by another process.*

To resolve this issue, you can add the **RestartReportServer** option as part of the report deployment in Windows PowerShell. For more information, see [Deploy the default reports](deploy-the-default-reports.md).

## See also

[Troubleshooting reporting](troubleshooting-reporting.md)

[Reporting in Microsoft Dynamics AX](reporting-in-microsoft-dynamics-ax.md)

