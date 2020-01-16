---
title: About multisite - BOM validations
TOCTitle: About multisite - BOM validations
ms:assetid: b7e053e6-d829-4a11-9de5-186b19fa7e17
ms:mtpsurl: https://technet.microsoft.com/library/Gg232437(v=AX.60)
ms:contentKeyID: 36059108
ms.date: 11/13/2015
mtps_version: v=AX.60
f1_keywords:
- BOM version by site
- multisite production
- multiple production sites
- select BOM version
- validate BOM version
audience: Application User
ms.search.region: Global
---

# About multisite - BOM validations 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A typical scenario for production at multiple sites might involve an end item that includes component items, where the component items are produced at and moved between different sites, and the sites share common item numbers.

This scenario requires that the bills of material (BOM) versions for the component items are structured to support the mandatory site dimension. The warehouse operations that support material consumption and item storage must also be aligned by site.

When planning materials and resources in an environment with multiple production sites, the program selects the BOM version to use based on the following criteria:

  - The site of the requirement

  - A valid date interval

  - The quantity

These are the rules that apply for BOM versions and BOM lines in the **Lines** form and the **Designer** form.

  - A BOM version can only span one site, and all BOM lines must be associated with the same site that is defined on the corresponding BOM version.

  - A BOM can have a blank site, in which case, the BOM can be used at more than one site.

  - If a BOM version does not specify a site, the site field on the BOM and the corresponding BOM lines must be blank. Likewise, the warehouse field on the corresponding BOM lines must also be blank.

  - If the site on a BOM version is changed, the site on the BOM lines is also changed, and the warehouse is cleared.

  - The warehouse lookup on BOM lines is filtered by the site.

  - When you select the resource consumption field on a BOM line, the warehouse is cleared. In this case, the picking warehouse is found through the route, by locating the warehouse that is assigned to the production unit that the resource belongs to.
    
    This validation occurs at run time when the production BOM is created. An inconsistency results in the production order not being created.

  - If no warehouse is entered on the BOM line, and the resource consumption is not selected, the warehouse is found through the site-specific settings on the item. If no warehouse is entered on the item, the warehouse field is left blank.
    
    This validation occurs at run time when the production BOM is created. An inconsistency results in the production order not being created.

  - If a site is entered on the BOM version, and a warehouse is entered on the BOM line, if the user selects the resource consumption field, the warehouse field is cleared.
    
    If during run time, no warehouse is found for the resource, the warehouse is found through the site-specific settings on the item. If no warehouse is entered on the item, the warehouse field is left blank.

## See also

[About multisite - route validations](about-multisite-route-validations.md)

  


