---
title: Integration ports
TOCTitle: Integration ports
ms:assetid: 6797e3b5-f1a2-44b2-8c41-d7fecf170317
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg731821(v=AX.60)
ms:contentKeyID: 35132669
ms.date: 04/17/2013
mtps_version: v=AX.60
---

# Integration ports [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX 2012, integration ports provide simplified administration of services and Application Integration Framework (AIF). Integration ports replace the AIF endpoints and related concepts that were used in previous releases of Microsoft Dynamics AX. Each integration port can expose one or more services, and each integration port has a unique Uniform Resource Identifier (URI) that identifies the address of the port.

Each integration port also has a direction. An integration port can be either an inbound integration port or an outbound integration port. An inbound integration port is a destination for messages that originate from outside Microsoft Dynamics AX. An outbound integration port is a destination for messages that originate from your Microsoft Dynamics AX system. Inbound integration ports can be one of two types: basic or enhanced. Outbound integration ports are always enhanced ports.

## Basic integration ports

Basic integration ports are exposed at a specific Windows Communication Foundation (WCF) endpoint on the Application Object Server (AOS) host. Only a developer can create a new basic integration port. When a developer creates an automatically deployed service group in the Application Object Tree (AOT), a basic inbound integration port is also automatically created. The basic inbound integration port is then associated with the service group that is being deployed. Some basic integration ports, such as those that are used for system services, are always deployed and enabled by default.

## Enhanced integration ports

If you want advanced integration capabilities that you can use to customize the behavior of an integration port, you must create an enhanced integration port. Enhanced integration ports provide the following capabilities that basic integration ports do not provide:

  - Services can be hosted on either AOS or Internet Information Services (IIS).

  - A variety of protocols are supported through WCF adapters. These protocols include HTTP, NetTCP, and Message Queuing, which is also known as MSMQ. Enhanced integration ports also support a file system adapter that lets you use file paths as addresses.

  - You can perform pre-processing and post-processing of service requests and service responses.

  - You can create customizations for data contracts by specifying service operations and policies for document data.

  - You can specify advanced security and troubleshooting settings.

For information about how to configure enhanced integration ports, see [Managing integration ports](managing-integration-ports.md).

## See also

[Using Basic Integration Ports](using-basic-integration-ports.md)

[How to: Create a Basic Inbound Integration Port](how-to-create-a-basic-inbound-integration-port.md)

