---
title: Create a shared directory for installation
TOCTitle: Create a shared directory for installation
ms:assetid: de9ff8fa-63ba-48d1-a76a-68e39c273eda
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dd362101(v=AX.60)
ms:contentKeyID: 35133097
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Create a shared directory for installation 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before you install Microsoft Dynamics AX and subsequent cumulative updates, we recommend that you create a shared directory on a file server. Then copy the contents of the Microsoft Dynamics AX DVD and the updates to this network location. Perform all installations from this network location instead of the DVD.

By giving users a shared network location from which to install Microsoft Dynamics AX, you can make sure that the same version of the software is installed on all computers.

Additionally, the installation program may later require access to files from the location where Setup was run. For example, the installation program may require access to the files when you upgrade, when you modify the installation, or when you uninstall a component or update. If Setup was run from a network location, the installation program can retrieve the files silently from the network. However, if Setup was run from a DVD, the user is prompted to insert the DVD when files are required.

Before you install Microsoft Dynamics AX, follow these steps to create a shared directory for the contents of the DVD.

1.  Create a directory that is named **DynamicsAX6**.

2.  Share the DynamicsAX6 directory:
    
      - Give the Administrator group full control, or owner access.
    
    <!-- end list -->
    
      - Give the Everyone group read access.
    
    As a security best practice, we recommend that you prevent users from making changes to this directory. Only read access is required to perform an installation from the directory.

3.  Copy the contents of the Microsoft Dynamics AX DVD to the DynamicsAX6 directory.

4.  Copy the installation files for cumulative updates and hotfixes to the directory. For more information about how to include updates, see [Include cumulative updates and hotfixes in a new installation (slipstreaming)](include-cumulative-updates-and-hotfixes-in-a-new-installation-slipstreaming.md).

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

