---
title: Master planning and multisite functionality
TOCTitle: Master planning and multisite functionality
ms:assetid: 327813a9-4541-4b02-bfdb-133f8fa08f79
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg231036(v=AX.60)
ms:contentKeyID: 36056361
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- demand explosion scenarios
- multisite planning
- warehouse storage dimension
audience: Application User
ms.search.region: Global
---

# Master planning and multisite functionality 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To accommodate the multisite functionality, master scheduling must take the settings of the site and warehouse inventory dimensions into account. The site dimension is mandatory, and you can set the warehouse dimension to mandatory.

When a dimension is mandatory, a dimension value must be entered on all inventory transactions. Therefore, during master scheduling, the site and the warehouse for the initial demand are known. The site dimension is also consistent so that during the explosion of lower-level demand, the site value does not change.

When the warehouse is not set to mandatory, it may not be known from the initial demand. The planning engine must determine which warehouse to use based on the settings that are defined for the item, individual warehouses, and the details of the order line.

The following scenarios describe how the planning engine works, when different settings are defined, to determine the warehouse to use. For more information, see the following topics:

  - [About master scheduling - site and warehouse coverage, warehouse mandatory](about-master-scheduling-site-and-warehouse-coverage-warehouse-mandatory.md)

  - [About master scheduling - site coverage, warehouse mandatory](about-master-scheduling-site-coverage-warehouse-mandatory.md)

  - [About master scheduling - site coverage, warehouse not mandatory](about-master-scheduling-site-coverage-warehouse-not-mandatory.md)

  - [About master scheduling - site and warehouse coverage, warehouse not mandatory](about-master-scheduling-site-and-warehouse-coverage-warehouse-not-mandatory.md)

  - [About master scheduling - demand explosion of a BOM version](about-master-scheduling-demand-explosion-of-a-bom-version.md)

## See also

[About sites and the multisite functionality](about-sites-and-the-multisite-functionality.md)

[About mandatory inventory dimensions](about-mandatory-inventory-dimensions.md)

[About master scheduling - how the BOM version is determined](about-master-scheduling-how-the-bom-version-is-determined.md)

  


