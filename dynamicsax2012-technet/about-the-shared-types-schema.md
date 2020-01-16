---
title: About the Shared Types Schema
TOCTitle: About the Shared Types Schema
ms:assetid: a6220937-dbd7-4f05-99fc-e5d29dc110c7
ms:mtpsurl: https://technet.microsoft.com/library/Hh769362(v=AX.60)
ms:contentKeyID: 43876670
author: Khairunj
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# About the Shared Types Schema 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The shared-types schema defines the enumerationss and extended data types (EDTs) that are used by a document service.

## Shared Types

The shared-types schema consolidates common data types into one schema that is imported by all document service schemas. The namespace for the shared-types schema is http://schemas.microsoft.com/dynamics/2008/01/sharedtypes. If you publish a new service that contains a new enumeration or EDT, the shared-types schema is automatically updated. The shared-types schema is included with the Web Services Definition Language (WSDL) file.

If you want to view the shared-types schema, view the schema for any service from either the **Inbound ports** or the **Outbound ports** form. To view the shared-types schema, in the **Schema** form, click **View imported schemas**. For more information, see the section “Viewing schemas” in [Customize service contracts](customize-service-contracts.md).


> [!IMPORTANT]
> <P>If you are providing a document XML Schema Definition (XSD) to an external party, you must include the shared-types schema. This is because the shared-types schema is imported by the XSD. Without the shared-types schema, the external user cannot use the service XSD.</P>



## See also

[Developing with Services and AIF](developing-with-services-and-aif.md)

[Managing integration ports](managing-integration-ports.md)

