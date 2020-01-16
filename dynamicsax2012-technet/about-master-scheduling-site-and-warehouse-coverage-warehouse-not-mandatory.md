---
title: About master scheduling - site and warehouse coverage, warehouse not mandatory
TOCTitle: About master scheduling - site and warehouse coverage, warehouse not mandatory
ms:assetid: dc988e0d-97fe-4233-963b-da68458d78fb
ms:mtpsurl: https://technet.microsoft.com/library/Gg243193(v=AX.60)
ms:contentKeyID: 37072067
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About master scheduling - site and warehouse coverage, warehouse not mandatory 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This master scheduling scenario involves the following conditions:

  - The site dimension is set to mandatory and must be entered on the demand transaction.

  - The warehouse dimension is not set to mandatory. The warehouse may be known, but it is not used in the master scheduling calculation.

  - The site and warehouse dimensions are set for coverage planning. Other dimensions may be set for coverage planning also. However, they are not affected by the multisite functionality.

The following graphic illustrates how the master scheduling proceeds. The parameters that are referred to in the graphic, and their locations, are as follows:

  - The warehouse is set to **Manual**. Click **Inventory management** \> **Setup** \> **Inventory breakdown** \> **Warehouses**. On the **Master planning** FastTab, see the **Manual** field.

  - Item coverage is defined for the item. Click **Product information management** \> **Common** \> **Released products**. Click **Grid View** or press CTRL+SHIFT+G to view all items. Select the item, and then, on the **Action pane**, on the **Plan** tab, click **Item coverage**.

  - Refill relations are defined for the warehouse. Click **Inventory management** \> **Setup** \> **Inventory breakdown** \> **Warehouses**. On the **Master planning** FastTab, see the **Main warehouse** field group.

  - The default order type is set to **Production**, **Purchase order**, or **Kanban**. Click **Product information management** \> **Common** \> **Released products**. Click **Grid View** or press CTRL+SHIFT+G to view all items. Select the item, and then, on the **Action pane**, on the **Plan** tab, click **Default order settings**. In the **Default order settings** form, see the **Default order type**.

![Demand for site and warehouse, warehouse not](images/Gg243193.Multisitedemandexplosionscenarioforsiteandwarehousecoveragewarehousenotmandatory(AX.60).jpg "Demand for site and warehouse, warehouse not")

## See also

[About mandatory inventory dimensions](about-mandatory-inventory-dimensions.md)

[Master planning and multisite functionality](master-planning-and-multisite-functionality.md)

[About master scheduling - how the BOM version is determined](about-master-scheduling-how-the-bom-version-is-determined.md)

[About master scheduling - site and warehouse coverage, warehouse mandatory](about-master-scheduling-site-and-warehouse-coverage-warehouse-mandatory.md)

[About master scheduling - site coverage, warehouse mandatory](about-master-scheduling-site-coverage-warehouse-mandatory.md)

[About master scheduling - site coverage, warehouse not mandatory](about-master-scheduling-site-coverage-warehouse-not-mandatory.md)

[About master scheduling - site and warehouse coverage, warehouse not mandatory](about-master-scheduling-site-and-warehouse-coverage-warehouse-not-mandatory.md)

  


