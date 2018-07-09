---
title: AXUpdate command line parameters reference
TOCTitle: AXUpdate command line parameters reference
ms:assetid: 42f5ad71-2470-46c8-903a-53e6d34714d1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh538445(v=AX.60)
ms:contentKeyID: 39508867
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# AXUpdate command line parameters reference [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you run the AXUpdate.exe, by default it runs the Update Setup Wizard. This wizard has a graphical user interface (GUI) that prompts you for required information. You can also run AXUpdate.exe at a command prompt, in silent mode. When AXUpdate.exe runs in silent mode, there is no GUI. Instead, you must supply all the required information at the command prompt when you start AXUpdate.exe.

The following command-line parameters can be used to install updates.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Parameter</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>AcceptLicenseTerms</strong></p></td>
<td><p>Specify whether you accept the terms of the license agreement.</p>
<ul>
<li><p>1 – Accept the license terms.</p></li>
<li><p>0 – Do not accept the license terms.</p></li>
</ul>
<p>If the <strong>HideUI</strong> parameter is set to 0, the <strong>License terms</strong> page is displayed, regardless of the setting of <strong>AcceptLicenseTerms</strong>.</p>
<p>If <strong>HideUI</strong> is set to 1, <strong>AcceptLicenseTerms</strong> must be set to 1. If <strong>AcceptLicenseTerms</strong> is set to 0, you receive an error message, and the installation stops.</p></td>
</tr>
<tr class="even">
<td><p><strong>AosInstanceName</strong></p></td>
<td><p>Specify the name of the instance of Application Object Server (AOS) to update. To update multiple AOS instances, enter a semicolon-delimited list. If this parameter is not included, all AOS instances are updated.</p></td>
</tr>
<tr class="odd">
<td><p><strong>AosStart</strong></p></td>
<td><p>Specify whether the AOS instances are restarted after the update is applied.</p>
<ul>
<li><p>0 – Do not restart the AOS instances.</p></li>
<li><p>1 – Restart the AOS instances. This is the default setting.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>HideUI</strong></p></td>
<td><p>Specify whether the UI for the installer is displayed.</p>
<ul>
<li><p>0 – Show the wizard. This is the default setting.</p></li>
<li><p>1 – Hide the wizard, and run in silent mode.</p></li>
</ul>
<p></p>
<p>If <strong>HideUI</strong> is set to 1, the <strong>AcceptLicenseTerms</strong> parameter must be set to 1. Otherwise, you receive an error message, and the installation stops.</p></td>
</tr>
<tr class="odd">
<td><p><strong>InstallAos</strong></p></td>
<td><p>Specify whether updates for the AOS instances are installed.</p>
<ul>
<li><p>0 – Do not install updates for AOS. This is the default setting.</p></li>
<li><p>1 – Install updates for AOS.</p></li>
</ul>
<p></p>
<p>If the <strong>AosInstanceName</strong> parameter is not included, all AOS instances are updated.</p></td>
</tr>
<tr class="even">
<td><p><strong>InstallClientOBA</strong></p></td>
<td><p>Specify whether updates for the Microsoft Dynamics AX client and the Microsoft Office Add-ins are installed.</p>
<ul>
<li><p>0 – Do not install updates for the client and the Office Add-ins. This is the default setting.</p></li>
<li><p>1 – Install updates for the client and the Office Add-ins.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>InstallComponents</strong></p></td>
<td><p>Specify whether updates for all other components are installed.</p>
<ul>
<li><p>0 – Do not install updates for other components. This is the default setting.</p></li>
<li><p>1 – Install updates for other components.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>InstallHelpServer</strong></p></td>
<td><p>Specify whether updates for Help Server are installed.</p>
<ul>
<li><p>0 – Do not install updates for Help Server. This is the default setting.</p></li>
<li><p>1 – Install updates for Help Server.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>InstallModelDatabase</strong></p></td>
<td><p>Specify whether updates for the model store database are installed.</p>
<ul>
<li><p>0 – Do not install updates for the model store database. This is the default setting.</p></li>
<li><p>1 – Install updates for the model store database.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>InstallSetupSupport</strong></p></td>
<td><p>Specify whether updates for Setup Support are installed.</p>
<ul>
<li><p>0 – Do not install updates for Setup Support. This is the default setting.</p></li>
<li><p>1 – Install updates for Setup Support.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>InstallTraceParser</strong></p></td>
<td><p>Specify whether updates for Trace Parser are installed.</p>
<ul>
<li><p>0 – Do not install updates for Trace Parser. This is the default setting.</p></li>
<li><p>1 – Install updates for Trace Parser.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>LogDir</strong></p></td>
<td><p>Specify where the log files for AXUpdate.exe are saved.</p>
<p>By default, the following path is used:</p>
<p>%ALLUSERSPROFILE%\Microsoft\Dynamics AX\Dynamics AX Setup Logs\</p>
<div class="alert">

> [!NOTE]
> <P>When log files are saved to the default location, they are arranged in dated folders to protect existing log files from being overwritten. If you override the default value for <STRONG>LogDir</STRONG>, the logs are saved to the exact folder that you specify. Any log files that are already located in that folder are overwritten.</P>


</div>
<p>The path can be fully qualified, or it can be relative to the location of the AXUpdate.exe file. Relative paths can include upward qualifiers, such as &quot;..\..\&quot;.</p></td>
</tr>
<tr class="odd">
<td><p><strong>ModelDatabaseInstanceName</strong></p></td>
<td><p>Specify the name of the model store database to update. To update multiple model store databases, enter a semicolon-delimited list.</p>
<p>If this parameter is not included, all model store databases from the server configurations for the local AOS instances are updated.</p></td>
</tr>
</tbody>
</table>


## See also

[Run AXUpdate in silent mode](run-axupdate-in-silent-mode.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

