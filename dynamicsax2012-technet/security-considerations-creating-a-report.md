---
title: Security Considerations Creating a Report
TOCTitle: Security Considerations Creating a Report
ms:assetid: 3561ba22-d9af-4333-9b95-2c066e903397
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Cc596325(v=AX.60)
ms:contentKeyID: 28119339
ms.date: 04/18/2014
mtps_version: v=AX.60
dev_langs:
- vb
---

# Security Considerations Creating a Report 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes security considerations for creating Reporting Services reports using the Microsoft Dynamics AX reporting tools.

## Data Access

  - When accessing data from the Microsoft Dynamics AX database, it is recommended that you use the predefined Microsoft Dynamics AX data sources to ensure that appropriate security is enforced. For more information about the predefined Dynamics AX data source, see [Report Data Overview](report-data-overview.md). When you use the query and report data provider data source types, all data access requests go through the Role and Task security system. When you use an external SQL or OLAP data source, security settings from the Role and Task security system are not applied when accessing data. In this case, you can use the role-based security features that are available from Microsoft SQL Server to secure the data. For more information about the security features from Microsoft SQL Server, see [Securing Reports and Resources](http://go.microsoft.com/fwlink/?linkid=110169) and [Securing Reporting Services](http://go.microsoft.com/fwlink/?linkid=110170) in SQL Server 2008 Books Online.

## Extensible Data Security

The extensible data security framework enables you to secure data in shared tables such that users have access to only the part of the table that is allowed by the enforced policy. Extensible data security policies, when deployed, are enforced on Microsoft Dynamics AX reports. For more information, see the [Extensible Data Security](http://go.microsoft.com/fwlink/?linkid=230460) white paper.


> [!NOTE]
> <P>When you bind a report to a report data provider class that writes data to a temp table, apply the XDS policy to the table that contains the source data for the report, not the temp table.</P>



## Projects and Build

  - When building from the command line, Microsoft Dynamics AX reporting tools does not perform any checks for unsafe entries in the project file. The project file entries are not analyzed by Microsoft Dynamics AX reporting tools from a security perspective. Therefore, it is strongly recommended that you do not build third-party reporting projects from the command line. Build from the command line only in trusted scenarios.

  - Microsoft Visual Studio, with the help of MSBuild, analyzes unsafe entries in a project file when it is loaded and warns you about them. An example of an unsafe entry is the redirection of the project output path to a system folder. For example, the output path could be redirected to C:\\Windows, which could overwrite a system file. Or, the output path could be redirected so as to overwrite a default MSBuild property for Microsoft Dynamics AX reporting tools projects. When attempting to open a reporting project that contains unsafe entries, a dialog box displays that prompts you not to open the project. If you experience this, you should inspect the unsafe entries as you decide whether to open the project.

  - Project files, model files, code files, and referenced assemblies should always be placed in a safe location whether it is a local folder, network share, or source code control database. The default project location for Microsoft Visual Studio projects is \\My Documents\\Visual Studio 2010\\Projects, which is protected by the administrator and current user access control lists.

  - Threat detection in a business logic project is limited to the functionality provided by standard C\# and Visual Basic project systems in Microsoft Visual Studio. The current implementation of the C\# and Visual Basic project systems displays only the first detected threat in the project file. Therefore, if you skip the threat and load the project file, all other threats that exist in the project file will be skipped.

  - The build cache file has an internal binary structure. The first violation of this structure that is discovered will force the compilation to regenerate the file. If the file is modified without violating the structure, the issue will not be mitigated, but you can invoke a clean build to regenerate the build cache file to eliminate the threat.

## Assembly Access on a Report Server

  - If an administrator grants an assembly access to the SessionManager API (which wraps .NET Business Connector), then the assembly must be given the AxSessionPermissionSet in the rssrvpolicy.config file on the report server.
    

    > [!NOTE]
    > <P>This is the recommended setting for business logic assemblies (depending on the main report project name length, either .BusinessLogic.dll or .BL.dll), and it is added by default for the business logic assemblies that are created for a deployed reporting project. This includes the business logic assemblies from referenced reporting projects.</P>



  - Giving a custom assembly full trust in the report server security policy file allows the assembly to directly access .NET Business Connector running under the Business Connector proxy account. This is an account that has elevated privileges that allows for access to the LogonAs functionality. In this case, the assembly could impersonate any user and access their records.

  - Granting a custom assembly ReflectionPermission with MemberAccess could allow the assembly to retrieve cached sessions from the session cache. Those sessions are logged in for a specific user, and the custom assembly could have access to that user's data.

  - The following code must be present in the custom code section of the RDL file if the report is expected to make use of the SessionManager API:
    
    ``` vb
    Protected Overrides Sub OnInit()
    Microsoft.Dynamics.Framework.Reports.SessionManager.BeginRequest(Report)
    End Sub
    ```

  - Entries in the security policy file will not be created for any assemblies referenced by business logic assemblies.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

