---
title: Troubleshoot installation issues with client components
TOCTitle: Troubleshoot installation issues with client components
ms:assetid: 8318ff7c-8f7b-4372-b417-483dc81bda1e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Ee355062(v=AX.60)
ms:contentKeyID: 35132704
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Troubleshoot installation issues with client components [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic provides information that can help you troubleshoot issues that you may encounter when you install the Microsoft Dynamics AX client components.

## User not recognized error when you try to start the client

If you are not a user in the system, the client returns the following error: “User not recognized.” An administrative user can add you to the system as a user, and then assign you to the appropriate security roles. The person who installed Microsoft Dynamics AX is the first administrative user. For more information, see the Microsoft Dynamics AX [Technical Library](http://go.microsoft.com/fwlink/?linkid=182420) on TechNet.

## Open the client configuration utility

You can access the Microsoft Dynamics AX Configuration utility from the **Administrative Tools** menu. On computers that run Windows 7, **Administrative Tools** is an item in Control Panel.

## Connection with Application Object Server cannot be established

When you try to start the client, you may receive the following error: “Connection with the Application Object Server cannot be established.”

This error can indicate that the **Microsoft Dynamics AX Object Server** service is not running. On the server computer for Application Object Server (AOS), verify the status of the service by using the **Services** control panel. (Click **Start** \> **Administrative Tools** \> **Services**.)

If you specified a shared configuration file when you installed the client, you might receive this error the first time that you start the client. To resolve this issue, click **OK** to close the client, and then restart the client.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

