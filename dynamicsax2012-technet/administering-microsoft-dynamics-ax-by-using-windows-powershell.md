---
title: Administering Microsoft Dynamics AX by using Windows PowerShell
TOCTitle: Administering Microsoft Dynamics AX by using Windows PowerShell
ms:assetid: 96e9ae2f-447a-426e-b77f-95636ddb9f15
ms:mtpsurl: https://technet.microsoft.com/library/Hh272856(v=AX.60)
ms:contentKeyID: 36584380
author: Khairunj
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Administering Microsoft Dynamics AX by using Windows PowerShell 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Windows PowerShell is a command-line scripting tool that lets administrators interact directly with Microsoft Dynamics AX to add users and user authentication, manage models, and manage configurations for communication between Microsoft Dynamics AX and Microsoft SQL Server Reporting Services. In addition, administrators can use Windows PowerShell cmdlets to create scripts. This term is pronounced "command-lets." For information about cmdlets available for Microsoft Dynamics AX, see [Windows PowerShell for Microsoft Dynamics AX](windows-powershell-for-microsoft-dynamics-ax.md).

When you install Microsoft Dynamics AX, Windows PowerShell 2.0 is installed if it is not already present. By default, Windows PowerShell is located in the following location: \<%SystemRoot%\>\\System32\\WindowsPowerShell\\v1.0\\PowerShell.exe.


> [!NOTE]
> <P>Windows PowerShell 2.0 is installed in the v1.0 folder, because it is backward compatible with Windows PowerShell 1.0.</P>



For a list of the new features in Windows PowerShell 2.0, see [About Windows PowerShell 2.0](https://go.microsoft.com/fwlink/?linkid=113247).


> [!IMPORTANT]
> <P>The Remote Registry service must be started in your environment on the server that is running the Microsoft Dynamics AX databases.</P>



## Accessing Windows PowerShell for Microsoft Dynamics AX

After you install Microsoft Dynamics AX, the applicable Windows PowerShell cmdlets are available from either the Microsoft Dynamics AX Management Shell or the Windows PowerShell console. By using the Management Shell, you can manage many aspects of Microsoft Dynamics AX. For example, you can add users and user authentication, manage models, and manage configurations for communication between Microsoft Dynamics AX and Reporting Services. The cmdlets that are run from the Management Shell output Microsoft Dynamics AX objects that are based on the Microsoft .NET Framework. These objects can then be used as input for other cmdlets, or they can be stored in local variables for later use.

When you use the Microsoft Dynamics AX Management Shell or the Windows PowerShell console, you can load additional snap-ins. For more information, see [Customizing Profiles](https://go.microsoft.com/fwlink/?linkid=183166).

## Access the Microsoft Dynamics AX 2012 Management Shell

1.  On the **Start** menu, click **All Programs**.

2.  Click **Administrative Tools**.

3.  Click **Microsoft Dynamics AX 2012 Management Console**.

## Permissions

Before you can use the Microsoft Dynamics AX 2012 Management Shell and the Windows PowerShell cmdlets, verify that you meet the following minimum requirements:

  - You have administrative permissions on the local computer.

  - You have System Administrator rights in Microsoft Dynamics AX.

  - If you are using model and modelstore management cmdlets, you must have the following additional rights in SQL Server:
    
      - You are a member of the Securityadmin server role on the SQL Server instance.
    
      - You are assigned to the db\_owner role in a database.

  - If you are managing Enterprise Portal for Microsoft Dynamics AX, you must run the Windows PowerShell cmdlets on the server that runs Enterprise Portal. You must have the following rights:
    
      - Microsoft SharePoint Server farm administrator
    
      - Membership in the local Administrators group on the server that runs Enterprise Portal

  - If you are managing Microsoft SQL Server Reporting Services, you must have the following rights:
    
      - System Administrator rights in Reporting Services
    
      - Membership in the local Administrators group on the server that runs Reporting Services

## Scripts and execution policies

Although you can use Windows PowerShell to perform a single administrative task, the real benefit of Windows PowerShell cmdlets is the capability to automate a series of tasks by using a script. A script is a plain text file that contains one or more Windows PowerShell cmdlets. Windows PowerShell scripts have a .ps1 file name extension.

To use a script, the minimum execution policy that is required for Microsoft Dynamics AX is RemoteSigned, whereas the default policy for Windows PowerShell is Restricted. If the policy is left as Restricted, the Microsoft Dynamics AX Management Shell changes the policy for Windows PowerShell to RemoteSigned. Therefore, the Microsoft Dynamics AX Management Shell must use elevated administrative permission. To start the Management Shell so that it uses elevated administrative permission, select **Run as administrator**. This change applies to all sessions of Windows PowerShell. For more information about scripts, see [about\_scripts](https://technet.microsoft.com/library/dd819484.aspx). For more information about execution policies, see [about\_Execution\_Policies](https://technet.microsoft.com/library/dd347641.aspx).

## Learning Windows PowerShell

The following information describes some of the learning resources that are available to help Microsoft Dynamics AX professionals who are not familiar with Windows PowerShell.

## TechNet Gallery

The TechNet Gallery includes many resources that can help you learn the basics of Windows PowerShell. The TechNet Gallery also contains script repositories that include samples of scripts that are frequently used together with various Microsoft products. The following table shows the main learning resources.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Page</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><a href="https://go.microsoft.com/fwlink/?linkid=187813">Windows PowerShell Documentation on TechNet</a></p></td>
<td><p>The section of the TechNet Library that contains web copies of the core Get Help topics for Windows PowerShell. This section also contains web copies of the Windows PowerShell Getting Started document, the PowerShell.exe Help, and a primer for Windows PowerShell.</p></td>
</tr>
<tr class="even">
<td><p><a href="https://go.microsoft.com/fwlink/?linkid=187815">Scripting With Windows PowerShell</a></p></td>
<td><p>The home page for learning resources for Windows PowerShell scripting.</p></td>
</tr>
<tr class="odd">
<td><p><a href="https://go.microsoft.com/fwlink/?linkid=187817">Windows PowerShell Owner's Manual</a></p></td>
<td><p>A web-based guide that can help you start to work with Windows PowerShell.</p></td>
</tr>
<tr class="even">
<td><p><a href="https://go.microsoft.com/fwlink/?linkid=187819">Windows PowerShell Quick Reference</a></p></td>
<td><p>A downloadable copy of the Quick Reference document that is installed together with Windows PowerShell.</p></td>
</tr>
</tbody>
</table>


## Windows PowerShell documents

Windows PowerShell installs the following documents in the Windows PowerShell 1.0 program group. These documents can also be installed after you download the [Windows PowerShell 1.0 Documentation Pack](https://go.microsoft.com/fwlink/?linkid=187822).

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>File</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>GettingStarted.rtf</p></td>
<td><p>Information about how to start to use Windows PowerShell.</p></td>
</tr>
<tr class="even">
<td><p>UsersGuide.rtf</p></td>
<td><p>A primer for the Windows PowerShell environment and language.</p></td>
</tr>
<tr class="odd">
<td><p>QuadFold.rtf</p></td>
<td><p>A printable quick reference document for frequently used syntax and commands for Windows PowerShell. This document is also available as a download from the TechNet Scripting Center.</p></td>
</tr>
</tbody>
</table>


When you use these resources, you may find it useful to learn the following concepts and cmdlets before you use Windows PowerShell for Microsoft Dynamics AX:

  - [Get-Command](https://go.microsoft.com/fwlink/?linkid=171069)

  - [Get-Member](https://go.microsoft.com/fwlink/?linkid=171070)

  - [Get-Help](https://go.microsoft.com/fwlink/?linkid=171068)

  - [Aliasing](https://go.microsoft.com/fwlink/?linkid=113207)

  - [Piping and the Pipeline in Windows PowerShell](https://go.microsoft.com/fwlink/?linkid=187808)

  - [Cmdlet Parameter Sets](https://go.microsoft.com/fwlink/?linkid=187810)

  - [Foreach-Object](https://go.microsoft.com/fwlink/?linkid=187812)

  - [Where-Object](https://go.microsoft.com/fwlink/?linkid=187811)

## See also

[Windows PowerShell for Microsoft Dynamics AX](windows-powershell-for-microsoft-dynamics-ax.md)

[AxUtil and Windows PowerShell Commands for Deploying Models](axutil-and-windows-powershell-commands-for-deploying-models.md)

  


