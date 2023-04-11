---
title: About shipment templates and priorities
TOCTitle: About shipment templates and priorities
ms:assetid: d9ecb9a1-e63d-451c-9940-c656fd19299b
ms:mtpsurl: https://technet.microsoft.com/library/Gg213715(v=AX.60)
ms:contentKeyID: 36059658
author: tonyafehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- create new shipment
- default shipment settings
- shipment template
audience: Application User
ms.search.region: Global
---

# About shipment templates and priorities 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic applies to features in the **Inventory management** module. It does not apply to features in the [Warehouse management](warehouse-management.md) module.

A shipment template is a collection of default settings that are used when a new shipment is created. The more information that is specified on the shipment template, the easier it is to create a new shipment. You can create any number of shipment templates so that as little information as possible must be changed on the individual shipments.

The mandatory fields on a shipment template include the following:

  - **Shipment template**

  - **Sequence ID**

  - **Site**

  - **Warehouse**

Shipments can be created manually or automatically. Automatic creation of shipments is a setup option in the **Shipment templates** form. When an output order is created, the existing shipment templates are searched for a site and warehouse that match the output order. If a template is found, a new shipment is created, and the output order is added to it. If more than one template matches the output order, the **Priority** field value for the template is used to determine the template with the highest priority, where a value of 1 is the highest priority. That template is used to create the shipment.

If no template is found, you can create a shipment manually in the **Shipments** form, or you can add it to an existing shipment.

## See also

[Shipment templates (form)](https://technet.microsoft.com/library/aa634909\(v=ax.60\))

  


