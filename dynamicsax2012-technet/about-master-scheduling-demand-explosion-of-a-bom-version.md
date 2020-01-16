---
title: About master scheduling - demand explosion of a BOM version
TOCTitle: About master scheduling - demand explosion of a BOM version
ms:assetid: d58d9b7f-ad15-4add-8c88-2d8c2d4376c0
ms:mtpsurl: https://technet.microsoft.com/library/Gg213699(v=AX.60)
ms:contentKeyID: 36931883
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About master scheduling - demand explosion of a BOM version 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This master scheduling scenario involves the following conditions:

  - The site dimension is mandatory and must be entered on the demand transaction.

  - The site dimension is consistent. Therefore, the site for lower-level demand is the same as the site on the initial demand transaction.

A successful demand explosion of a BOM version creates a demand for each BOM line item at a specific site and, possibly, at a specific warehouse. A site-specific BOM may have a specific warehouse defined for each BOM line. Also, for each BOM line, the item's dimension settings determine whether the warehouse is required. This resulting demand for each BOM line item becomes, in turn, the starting point for additional demand explosion.

The following graphic illustrates how the master scheduling demand explosion proceeds.

![Demand explosion using BOM version](images/Gg213699.MultisitedemandexplosionscenariousingBOMversion(AX.60).gif "Demand explosion using BOM version")

## See also

[Master planning and multisite functionality](master-planning-and-multisite-functionality.md)

[About master scheduling - how the BOM version is determined](about-master-scheduling-how-the-bom-version-is-determined.md)

[About master scheduling - site and warehouse coverage, warehouse mandatory](about-master-scheduling-site-and-warehouse-coverage-warehouse-mandatory.md)

[About master scheduling - site coverage, warehouse mandatory](about-master-scheduling-site-coverage-warehouse-mandatory.md)

[About master scheduling - site coverage, warehouse not mandatory](about-master-scheduling-site-coverage-warehouse-not-mandatory.md)

[About master scheduling - site and warehouse coverage, warehouse not mandatory](about-master-scheduling-site-and-warehouse-coverage-warehouse-not-mandatory.md)

[About mandatory inventory dimensions](about-mandatory-inventory-dimensions.md)

  


