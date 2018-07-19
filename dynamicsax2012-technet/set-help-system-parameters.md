---
title: Set Help system parameters
TOCTitle: Set Help system parameters
ms:assetid: b13c7325-b54a-4a5c-8e31-f379e6a595c1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg866983(v=AX.60)
ms:contentKeyID: 35256677
ms.date: 04/29/2014
mtps_version: v=AX.60
f1_keywords:
- help administration
- help parameters
- Help service
- Help url
---

# Set Help system parameters 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can specify the location of the Help service on your LAN by entering the service’s URL in the **Help system parameters** form. This setting is stored in Application Object Server (AOS) and is applied to all clients the next time they connect.

When you install the Microsoft Dynamics AX Help server, the URL that you assign to the Help service is stored in AOS. If you install the Help server on the Internet Information Services (IIS) Default Web Site, the URL is typically http://\<host:port\>/DynamicsAX6HelpServer/HelpService.svc on port 80. For more information about how to install the Help server, see [Install the help server](install-the-help-server.md).

Follow these steps to set a new location for the Help service.

1.  Click **System administration** \> **Setup** \> **System** \> **Help system parameters** to open the form.

2.  In the **Help service URL:** field, type the URL.

3.  Click **Close**.

  


