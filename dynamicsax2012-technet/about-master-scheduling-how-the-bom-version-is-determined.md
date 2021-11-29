---
title: About master scheduling - how the BOM version is determined
TOCTitle: About master scheduling - how the BOM version is determined
ms:assetid: 62874701-f17e-4129-a2e4-dc33816a7177
ms:mtpsurl: https://technet.microsoft.com/library/Gg231533(v=AX.60)
ms:contentKeyID: 36057673
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BOM
- BOM version
- Demand explosion
audience: Application User
ms.search.region: Global
---

# About master scheduling - how the BOM version is determined 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

During a demand explosion, if an item has a planned order type of production (in the coverage settings for an item), the planning engine finds a valid BOM version based on the site. The site is already known and is stated on the demand transaction. The following process is used to determine the BOM version to use:

  - If there is a BOM version defined for the item at the demand site, the site-specific BOM is used.

  - If there is no site-specific BOM version defined for an item at the demand site, a general BOM is used. A general BOM does not state a site, and it is valid for multiple sites. If there is a general BOM, it is used.

  - If there is no general BOM version to use, the demand explosion stops at this point.

A valid BOM version, whether site-specific or general, must meet the required criteria for date and quantity.

## See also

[Master planning and multisite functionality](master-planning-and-multisite-functionality.md)

[About master scheduling - how the BOM version is determined](about-master-scheduling-how-the-bom-version-is-determined.md)

[About master scheduling - site and warehouse coverage, warehouse mandatory](about-master-scheduling-site-and-warehouse-coverage-warehouse-mandatory.md)

[About master scheduling - site coverage, warehouse mandatory](about-master-scheduling-site-coverage-warehouse-mandatory.md)

[About master scheduling - site coverage, warehouse not mandatory](about-master-scheduling-site-coverage-warehouse-not-mandatory.md)

[About master scheduling - site and warehouse coverage, warehouse not mandatory](about-master-scheduling-site-and-warehouse-coverage-warehouse-not-mandatory.md)

  


