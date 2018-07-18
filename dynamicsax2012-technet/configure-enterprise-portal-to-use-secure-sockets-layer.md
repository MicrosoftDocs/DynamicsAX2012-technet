---
title: Configure Enterprise Portal to use Secure Sockets Layer
TOCTitle: Configure Enterprise Portal to use Secure Sockets Layer
ms:assetid: 531ec2a4-ded7-4366-a3ec-0ff2a9aaf30c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh352285(v=AX.60)
ms:contentKeyID: 36687914
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSL
- EP with SSL
---

# Configure Enterprise Portal to use Secure Sockets Layer 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Secure Sockets Layer (SSL) enables web servers and clients to communicate more securely by using encryption. When SSL is not used, data that is sent between the client and server is vulnerable to observation by anyone who has physical access to the network. We recommend that you implement SSL for all Enterprise Portal and Role Center sites. If you are concerned about SSL and site performance, at a minimum, you should implement SSL on all public-facing sites.

## Implement SSL

To implement SSL, you must install a certificate and a private encryption key on the web server by using Internet Information Services (IIS) manager. For more information, see [How to Setup SSL on IIS 7](http://go.microsoft.com/fwlink/?linkid=223135).

## See also

[Configure Enterprise Portal to use host headers](configure-enterprise-portal-to-use-host-headers.md)

[Checklists for deploying Enterprise Portal sites](checklists-for-deploying-enterprise-portal-sites.md)

  


