---
title: "What's new: Installation"
TOCTitle: Installation features
ms:assetid: 21756ba4-0bc4-44ee-8f95-686d9a5c158c
ms:mtpsurl: https://technet.microsoft.com/library/Gg751368(v=AX.60)
ms:contentKeyID: 35132577
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# What's new: Installation 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

For Microsoft Dynamics AX 2012, we have changed and added functionality that is related to installation.

## Overview

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Item</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Required feature</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="even">
<td><p>Product areas affected</p></td>
<td><p>All</p></td>
</tr>
<tr class="odd">
<td><p>Stakeholders</p></td>
<td><p>Business decision makers</p>
<p>Technical decision makers</p>
<p>Implementation team members</p>
<p>Independent software vendors (ISVs)/developers</p>
<p>Partners</p></td>
</tr>
</tbody>
</table>


## What's new in AX 2012 R3

For AX 2012 R3, cumulative update packages can be downloaded from the Microsoft Dynamics Lifecycle Services Updates section.

## What’s new in AX 2012

The following general improvements make the installation process easier and more intuitive:

  - **Wizard pages are redesigned.** The Setup wizard has a new appearance that is designed to be easy to use and consistent with other Windows installers.

  - **Progress indicators are improved.** The Setup wizard provides more detailed feedback than in previous releases. While components are being installed, you can see what has been successfully completed, what is in progress, and what must still be completed.

  - **Only one run of Setup is required.** In previous releases of Microsoft Dynamics AX, you had to run the Initialization Checklist after you installed the basic Microsoft Dynamics AX components. These basic components include Microsoft Dynamics AX Application Object Server (AOS), the database, application files, and the client. Most components, such as Enterprise Portal for Microsoft Dynamics AX and reporting extensions, could not be installed until the checklist was completed. Therefore, you had to run Setup multiple times to complete an installation. In AX 2012, the Initialization Checklist is no longer part of the installation process. Therefore, you can install all components without completing the checklist.

  - **Post-installation configuration steps are provided.** In AX 2012, instructions for post-installation configuration are integrated into the Setup wizard. After a component is installed, the **Setup summary** report displays the next steps that are required to complete the deployment. In previous releases, this information was provided only in the Installation Guide.

The following table lists the improvements to specific installation scenarios.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>Microsoft Dynamics AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Validate prerequisites.</p></td>
<td><p>Setup verified that underlying technologies were installed and configured correctly at various stages of the installation process.</p></td>
<td><p>Validation of prerequisites has been improved as follows:</p>
<ul>
<li><p><strong>A stand-alone utility validates prerequisites.</strong> Before you install Microsoft Dynamics AX, you can run a stand-alone utility to identify the prerequisites that are required for the Microsoft Dynamics AX components that you select. The utility can also install and configure some prerequisites for you.</p></li>
<li><p><strong>Prerequisite verification is consolidated.</strong> All validation of prerequisites and configurations occurs at the same time. Therefore, you can resolve all issues that involve prerequisites at the same time and then move on to installation.</p></li>
</ul></td>
<td><p>Installation is easier and more efficient.</p></td>
</tr>
<tr class="even">
<td><p>Deploy the Microsoft Dynamics AX client to multiple computers.</p></td>
<td><p>The .msi file, or installer file, for the client also contained other components. Therefore, it was difficult to deploy many clients by using mass deployment technologies, such as Systems Management Server or Group Policy.</p></td>
<td><p>The client components are contained in a separate .msi file. A separate client installer provides more options for mass deployment of clients.</p>
<p>Additionally, you can now use Setup to configure all clients so that they use a shared configuration file. In previous releases, the administrator had to configure clients individually.</p></td>
<td><p>Installation is easier and more efficient.</p></td>
</tr>
<tr class="odd">
<td><p>Slipstream service packs and updates.</p></td>
<td><p>You could install service packs and updates only after the Microsoft Dynamics AX installation was completed. Therefore, depending on the number of updates that were available, you had to run several installation wizards to complete the deployment.</p></td>
<td><p>Service packs and quarterly roll-up updates can be integrated into the Microsoft Dynamics AX installation. This kind of installation is known as a “slipstreamed” installation. If updates are available when you deploy AX 2012, you can download them to the location of the installation source. When you run Setup from the updated installation source, all updates are applied automatically.</p></td>
<td><p>Installation is easier and more efficient.</p></td>
</tr>
<tr class="even">
<td><p>Review log files and reports.</p></td>
<td><p>Log files were stored in multiple locations.</p></td>
<td><p>Because log files and reports are saved to a single location, you do not have to search in multiple locations. Additionally, the new <strong>Setup summary</strong> report lists the components that you installed, their installation status, and the next steps, if additional steps are required. You can access the Setup log files and reports from links in the Setup wizard, or locate the SetupLogs folder in the folder where you installed Microsoft Dynamics AX.</p></td>
<td><p>Troubleshooting is easier.</p></td>
</tr>
<tr class="odd">
<td><p>Apply updates to Setup.</p></td>
<td><p>The Setup application and its related files existed only on the DVD, and could not be patched through standard hotfixes or service packs. To modify Setup files, you had to perform manual workarounds.</p></td>
<td><p>The Setup application and its files are installed on the computer as the first step in the installation process. Because the files are installed on the computer, service packs and hotfixes can be applied to the Setup files, just as they can be applied to any other Microsoft Dynamics AX file. When Setup starts, it verifies whether you have downloaded the most recent version of the files. If a more recent version is available, Setup installs it.</p></td>
<td><p>Installation is easier.</p></td>
</tr>
<tr class="even">
<td><p>Install a full default Microsoft Dynamics AX installation on a single computer for development or testing.</p></td>
<td><p>You could install components on the same computer, but the installation process was the same as the installation process for a production environment.</p></td>
<td><p>You can select the <strong>Single-computer installation</strong> option to install a complete Microsoft Dynamics AX system on a single computer. This option installs the database, AOS, client components, business intelligence components, Enterprise Portal, the Help server, and the developer components in a single run of Setup. Setup uses default values for all components and does not prompt you for additional input.</p></td>
<td><p>Installation is easier.</p></td>
</tr>
</tbody>
</table>


## More information

For more detailed information about installation, see [Install Microsoft Dynamics AX 2012](install-microsoft-dynamics-ax-2012.md).

You can download a printable version of the [Installation Guide](https://go.microsoft.com/fwlink/?linkid=163796) from the Microsoft Download Center.

  


