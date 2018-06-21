---
title: Include cumulative updates and hotfixes in a new installation (slipstreaming)
TOCTitle: Include cumulative updates and hotfixes in a new installation (slipstreaming)
ms:assetid: bda5bb5d-78a2-491d-b2e4-713f1ef08a20
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh378076(v=AX.60)
ms:contentKeyID: 36870659
ms.date: 05/01/2014
mtps_version: v=AX.60
---

# Include cumulative updates and hotfixes in a new installation (slipstreaming) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If you are installing Microsoft Dynamics AX components for the first time, and cumulative updates, binary hotfixes, or service packs for Microsoft Dynamics AX are available, you can incorporate the updates into the installation by using a process that is known as slipstreaming. When updates are slipstreamed, Setup automatically detects and applies them. In this way, the time that is required to install the whole Microsoft Dynamics AX solution is reduced.


> [!NOTE]
> <P>Components that were previously installed are not updated during a later slipstream installation. For example, an instance of Application Object Server (AOS) is installed on a server. Later, you add updates to the installation source, and you also install another Microsoft Dynamics AX component on the same server. In this scenario, the existing AOS instance is not updated.</P>



You can slipstream the following kinds of updates:

  - Cumulative updates

  - Binary hotfixes

  - Help content updates

  - Service packs

Application (database) hotfixes cannot be included in the slipstreaming process. They must be installed by using AxUpdate.exe.

## The Updates folder

Before you install Microsoft Dynamics AX, you copy the DVD to a network location. This lets you modify the installation media to create a slipstream installation. Incorporate updates into the installation process by copying files to the Updates folder in the shared network location.


> [!NOTE]
> <P>For more information about how to install Microsoft Dynamics AX from a shared network folder, see <A href="create-a-shared-directory-for-installation.md">Create a shared directory for installation</A>.</P>



In the Updates folder, create a subfolder for each update package that you download. We recommend that you use the Knowledge Base article numbers of the updates as the names of the subfolders. For example, for the update that is associated with Knowledge Base article number 123456, create a subfolder that is named KB123456.

Extract each update into the appropriate subfolder. The following illustration shows an example of the recommended folder structure:

![Example folder structure for the Updates folder](images/Hh378076.UpdateFolderStructure(AX.60).png "Example folder structure for the Updates folder")

Any time that you apply a cumulative update package or a binary hotfix to your environment, we strongly recommend that you add the installation package to the Updates folder. This practice ensures that you can deploy new servers, clients, and other components of the correct version quickly. You should also make a copy of the updated installation media per your system recovery strategy.

## The slipstreaming process

The following is a high-level overview of the slipstreaming process:

1.  To find cumulative updates:
    
      - For AX 2012 R3, go to Microsoft Dynamics Lifecycle Services, and after selecting a project, click Updates. In the **Updates to include with new installations** section, select the slipstreamable update package that you want, and download it.
    
      - For AX 2012 R2 or earlier, visit the hotfix pages for [Microsoft Dynamics AX 2012](https://mbs.microsoft.com/customersource/downloads/hotfixes/ax2012hotfixes.htm) or [Microsoft Dynamics AX 2012 R2](https://mbs.microsoft.com/customersource/support/downloads/hotfixes/ax2012r2hotfixes.htm) on the CustomerSource web site. Logon is required.

2.  Create a shared network location from which to install Microsoft Dynamics AX.

3.  In the Updates folder, create a subfolder for each update package that you download. Then extract each update into the appropriate subfolder.

4.  Run Setup and select the components that you want to install. Setup detects and installs the updates.
    
    Follow the usual installation procedures to install Microsoft Dynamics AX components. For detailed installation instructions for each Microsoft Dynamics AX 2012 component, see Install Microsoft Dynamics AX.
    
    To install updates for Help content, you must select the **Help Server** component, and then select the updated content sets on the **Language and content selection** page.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

