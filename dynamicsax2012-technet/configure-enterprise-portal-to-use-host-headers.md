---
title: Configure Enterprise Portal to use host headers
TOCTitle: Configure Enterprise Portal to use host headers
ms:assetid: af2684b5-cd44-4254-8fdc-047906df1b4e
ms:mtpsurl: https://technet.microsoft.com/library/Hh352312(v=AX.60)
ms:contentKeyID: 36687941
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Configure Enterprise Portal to use host headers 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic includes an overview of host headers and information about how to configure host headers for Enterprise Portal.

## About host headers

A host header is a friendly name for a web site or a collection of web sites. For external-facing sites, the host header might be the name of the business or organization, as registered by using a domain-hosting company. For example, www.microsoft.com is the familiar host-header name and domain address for the multiple computers that service requests for Microsoft. For internal sites, a host header can be a permutation of the business or organization name, or something more specific, such as the name of a department.

By default, when you create an Enterprise Portal site, SharePoint uses the name of the computer that hosts the site in the URL. For example, the default URL for a new Enterprise Portal site is http://server_name/sites/DynamicsAx. As an administrative best practice, we recommend that you change the URL to use a host header. In this manner, users can remember the name of the site more easily, and you can avoid displaying computer names to external users. Another benefit of host headers is that one web application can host multiple web sites by using a single port number, such as port 80.


> [!IMPORTANT]
> <P>If you attempt to install Enterprise Portal on an existing Internet Information Services (IIS) site that is already configured with a host header, the installation fails unless you create a <A href="https://go.microsoft.com/fwlink/?linkid=194948">BackConnectionHostNames</A> registry entry.</P>



## Configure host headers

If you are creating a new Enterprise Portal web site in SharePoint, you can specify a name in the **Host Header** text box in the **Create New Web Application** form. To specify a host header for an existing site, use IIS Manager. For more information, see [Configure a Host Header for a Web site (IIS 7)](https://go.microsoft.com/fwlink/?linkid=223134). If you specify a host-header name for an existing site in IIS, you must also specify the name in the **Web sites** form in Microsoft Dynamics AX (Click **System administration**> **Setup**> **Enterprise Portal**> **Web sites**.).

## See also

[Checklists for deploying Enterprise Portal sites](checklists-for-deploying-enterprise-portal-sites.md)

[Configure Enterprise Portal to use Secure Sockets Layer](configure-enterprise-portal-to-use-secure-sockets-layer.md)

  


