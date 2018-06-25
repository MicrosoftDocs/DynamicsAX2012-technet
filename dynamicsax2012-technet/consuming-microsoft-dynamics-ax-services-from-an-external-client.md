---
title: Consuming Microsoft Dynamics AX Services from an External Client
TOCTitle: Consuming Microsoft Dynamics AX Services from an External Client
ms:assetid: 6e9cd3e0-b732-4231-95e3-0d1869c0beb2
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh500188(v=AX.60)
ms:contentKeyID: 37820255
ms.date: 04/17/2013
mtps_version: v=AX.60
---

# Consuming Microsoft Dynamics AX Services from an External Client [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can consume services that are hosted by Microsoft Dynamics AX from external clients that use .NET Framework languages such as C\#. For example, your C\# code can call a [document service](aif-document-services.md) or a [custom service](using-custom-services.md). Any service that is exposed by using an [integration port](integration-ports.md) in Microsoft Dynamics AX can be consumed by an external client. For more information about the different types of services in Microsoft Dynamics AX, see [Developing with Services and AIF](developing-with-services-and-aif.md).

The capability to call Microsoft Dynamics AX document services from external clients provides integration scenarios such as the following:

  - Updating customer information from an external client

  - Adding sales order and purchase order information to Microsoft Dynamics AX from an external client

  - Exchanging data with other enterprise software systems

Security for services that are consumed from an external client is based on the role-based security that is used in Microsoft Dynamics AX. For more information, see [About role-based security in services and AIF](about-role-based-security-in-services-and-aif.md) and [Security best practices for services and AIF](security-best-practices-for-services-and-aif.md).

To call Microsoft Dynamics AX services from clients on the Internet, you publish Microsoft Dynamics AX services through Internet Information Services (IIS). For more information, see [Install web services on IIS](install-web-services-on-iis.md) and [Application Integration Framework topology](application-integration-framework-topology.md).

## Consuming a Service from a .NET Framework Client

Before you can consume a Microsoft Dynamics AX service, it must be registered and exposed on an integration port. For more information about integration ports, see [Integration ports](integration-ports.md). For more information about registering services and exposing service operations, see the sections “Register services” and “Expose service operations” in [Customize service contracts](customize-service-contracts.md).

The following topic illustrates how to call a Microsoft Dynamics AX service from a C\# program to create a sales order in an inbound exchange:

  - [Walkthrough: Exchanging documents by using the NetTcp adapter](walkthrough-exchanging-documents-by-using-the-nettcp-adapter.md)

## See also

[Application integration](application-integration.md)

[Using the Call Context](using-the-call-context.md)

