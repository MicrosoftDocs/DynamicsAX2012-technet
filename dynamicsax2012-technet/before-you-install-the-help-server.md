---
title: Before you install the help server
TOCTitle: Before you install the help server
ms:assetid: 61c3e00d-b4ce-47b5-b53a-55e9a5011109
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg731816(v=AX.60)
ms:contentKeyID: 35132663
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Before you install the help server [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes the tasks that you must complete before you can install the Microsoft Dynamics AX Help server.

## Check for required permissions

Verify that you have the permissions that are required to install the Help server. For more information, see [Verify that you have the required permissions for installation](verify-that-you-have-the-required-permissions-for-installation.md).

## Install prerequisites

On the computer where you will install the Help server, run the prerequisite validation utility to verify that system requirements have been met. For information about how to run the prerequisite validation utility, see [Check prerequisites](check-prerequisites.md).

For more information about the hardware and software requirements for Microsoft Dynamics AX, see the [Microsoft Dynamics AX 2012 System Requirements](http://go.microsoft.com/fwlink/?linkid=165377) guide.

## Select a web site for the Help server

The Help server must be installed on a web site in Internet Information Services (IIS). You can create a new web site for the Help server, or you can use an existing site. The following sections describe these options.

## Create a new web site

If you want to create a new web site for the Help server, see the IIS documentation for information about how to create a web site.

## Use an existing web site

You can install the Help server on an existing web site that is used by other applications. However, you must verify that neither Microsoft SharePoint Foundation 2010 nor Microsoft SharePoint Server 2010 is running on the same site.

If you install the Help server on the default web site in IIS, and you later install Microsoft SharePoint Foundation or Microsoft SharePoint Server on the server, the SharePoint installation program stops the default web site and creates a new site for SharePoint. This new site runs on port 80. You must then open Internet Information Services (IIS) Manager and follow these steps:

1.  Configure the default web site to run on a different port.

2.  Restart the default web site.

## Install help content updates

If updates for the Microsoft Dynamics AX help content are available, you can incorporate the updates into the installation.

Use the following steps to include help updates in the installation:

1.  Locate and download help content updates from the [CustomerSource](http://go.microsoft.com/fwlink/?linkid=210925) web site (logon required).

2.  Browse to the directory where the files from the Microsoft Dynamics AX DVD are shared. For more information, see [Create a shared directory for installation](create-a-shared-directory-for-installation.md).

3.  Navigate to the \\Msi\\HelpContent folder.

4.  Copy the new or updated help .msi files to the appropriate language folder.

5.  When you run Setup and select the Help Server component, the new content will be displayed as an option. Select the content sets that you want to install. Any content that was previously installed will be replaced. If you clear the check box for a content set that was previously installed, it will be removed.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

