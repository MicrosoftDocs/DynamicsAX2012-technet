---
title: Using Basic Integration Ports
TOCTitle: Using Basic Integration Ports
ms:assetid: 5f27db79-d179-41c0-a98e-fcfbaea8966d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh496420(v=AX.60)
ms:contentKeyID: 37071997
ms.date: 04/21/2014
mtps_version: v=AX.60
---

# Using Basic Integration Ports 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Basic integration ports provide a way to define an endpoint for a service in Microsoft Dynamics AX. For example, you might create a basic port to use when you are testing a custom service in a non-production environment, and then create an enhanced port for the service in a production environment. Like an enhanced port, a basic port can contain more than one service. All services on one port must be either document services or custom services to guarantee consistency in the generated Web Services Description Language (WSDL).

Basic ports have limited options for customization. Use a basic port to expose services without configuring processing options, advanced security, or troubleshooting options. You must create an enhanced integration port to make a service available on the Internet using IIS, or to configure any of the following processing options:

  - Service contract customizations (for example, to select certain service operations to expose)

  - Data policies

  - Transforms

  - Pipeline components

  - Value mappings

  - Document filters

You create a basic port in the AOT when you create and deploy a [service group](services-service-operations-and-service-groups.md) that contains a service. To view basic ports, open the **Inbound ports** form. (Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Inbound ports**.) Both basic and enhanced ports appear in the list.


> [!NOTE]
> <P>AIF system services use basic ports that are provided as part of the Microsoft Dynamics AX installation. However, settings on the basic ports for system services cannot be viewed or changed on the <STRONG>Inbound ports</STRONG> form.</P>



## See also

[How to: Create a Basic Inbound Integration Port](how-to-create-a-basic-inbound-integration-port.md)

[Integration ports](integration-ports.md)

[Managing integration ports](managing-integration-ports.md)

[Create, edit, or delete an enhanced integration port](create-edit-or-delete-an-enhanced-integration-port.md)

[Configure processing options](configure-processing-options.md)

[AIF System Services](aif-system-services.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

