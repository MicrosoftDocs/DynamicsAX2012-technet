---
title: Set up fallback warehouses for sites
TOCTitle: Set up fallback warehouses for sites
ms:assetid: 92c33447-6d4b-4d49-8cbe-5871d82393e1
ms:mtpsurl: https://technet.microsoft.com/library/Gg232185(v=AX.60)
ms:contentKeyID: 44081012
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up fallback warehouses for sites 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to set up a fallback warehouse for a site.

The fallback warehouse is used when the warehouse cannot be determined because it has not been specified on a sales order. This situation might occur when sales orders are being received via intercompany trade, Enterprise Portal for Microsoft Dynamics AX, or Application Integration Framework (AIF). The fallback warehouse is also used when transport time is calculated, if the warehouse is not specified on a sales order line.

An enhanced integration port is required for this feature. For information about how to configure the enhanced integration port, see [Managing integration ports](managing-integration-ports.md).

1.  Click **Inventory management** \> **Setup** \> **Distribution** \> **Fallback warehouse for site**.

2.  Click **New**.

3.  In the **Site** field, select the site to associate a fallback warehouse with.

4.  In the **Warehouse** field, select the warehouse to use as the fallback warehouse for the site.

## See also

[Fallback warehouse for site (form)](https://technet.microsoft.com/library/hh209725\(v=ax.60\))

  


