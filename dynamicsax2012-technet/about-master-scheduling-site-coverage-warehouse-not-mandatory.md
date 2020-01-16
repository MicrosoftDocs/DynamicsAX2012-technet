---
title: About master scheduling - site coverage, warehouse not mandatory
TOCTitle: About master scheduling - site coverage, warehouse not mandatory
ms:assetid: 0023cf96-0846-479c-a757-50ba86ab62ef
ms:mtpsurl: https://technet.microsoft.com/library/Gg230648(v=AX.60)
ms:contentKeyID: 36997717
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About master scheduling - site coverage, warehouse not mandatory 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This master scheduling scenario involves the following conditions:

  - The site dimension is set to mandatory and must be entered on the demand transaction.

  - The warehouse dimension is not set to mandatory. The warehouse may be known, but it is not used in the master scheduling calculation.

  - The site dimension is set for coverage planning. Other dimensions may be set for coverage planning also. However, they are not affected by the multisite functionality.

  - The warehouse dimension is not set for coverage planning. Therefore, supply and demand are aggregated by site and, perhaps, other coverage-planned dimensions also.

The following graphic illustrates how the master scheduling proceeds. The parameters that are referred to in the graphic, and their locations, are as follows:

  - Item coverage is defined for the item. Click **Product information management** \> **Common** \> **Released products**. Click **Grid View** or press CTRL+SHIFT+G to view all items. Select the item, and then click **Plan** \> **Item coverage**.

  - Refill relations are defined for the warehouse. Click **Inventory management** \> **Setup** \> **Inventory breakdown** \> **Warehouses**. On the **Master planning** tab, see the **Main warehouse** field group.

  - The default order type is set to **Production**, **Purchase order** or **Kanban**. Click **Product information management** \> **Common** \> **Released products**. Click **Grid View** or press CTRL+SHIFT+G to view all items. Select the item, and then click **Plan** \> **Default order settings**. In the **Default order settings** form, see the **Default order type** field.

![Demand for site coverage warehouse not mandatory](images/Gg230648.Multisitedemandexplosionscenarioforsitecoveragewarehousenotmandatory(AX.60).jpg "Demand for site coverage warehouse not mandatory")

## See also

[About mandatory inventory dimensions](about-mandatory-inventory-dimensions.md)

[Master planning and multisite functionality](master-planning-and-multisite-functionality.md)

[About master scheduling - how the BOM version is determined](about-master-scheduling-how-the-bom-version-is-determined.md)

[About master scheduling - site and warehouse coverage, warehouse mandatory](about-master-scheduling-site-and-warehouse-coverage-warehouse-mandatory.md)

[About master scheduling - site coverage, warehouse mandatory](about-master-scheduling-site-coverage-warehouse-mandatory.md)

[About master scheduling - site coverage, warehouse not mandatory](about-master-scheduling-site-coverage-warehouse-not-mandatory.md)

[About master scheduling - site and warehouse coverage, warehouse not mandatory](about-master-scheduling-site-and-warehouse-coverage-warehouse-not-mandatory.md)

  


