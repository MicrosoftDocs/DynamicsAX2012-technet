---
title: About multisite - route validations
TOCTitle: About multisite - route validations
ms:assetid: 6a75211a-3326-4588-b409-315c9db9d1e7
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg231586(v=AX.60)
ms:contentKeyID: 36931873
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About multisite - route validations 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The site dimension is mandatory and you must enter a site value on all inventory transactions. When you plan materials and resources, the program selects a route version that is based on the site of the requirement, a valid date interval, and the quantity.

These are the rules that apply for sites on route versions and route lines:

  - A route version must specify a site. A route version cannot have a blank site.

  - A route version is valid for only one site.

  - When a site is defined for a route, you cannot change the site.

  - When you enter a site, the lookup forms for resources are filtered by the site that you enter.

  - If you want to use a route at another site, you can create a new route version.

  - When you copy an existing route to a different site, the resource on the route lines is cleared, and the default resources for the route relations are also cleared because the resources are site-specific.

## See also

[About multisite - BOM validations](about-multisite-bom-validations.md)

  


