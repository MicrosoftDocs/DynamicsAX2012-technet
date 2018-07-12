---
title: About product models
TOCTitle: About product models
ms:assetid: a88d03bf-435f-4030-962f-9fcaec530335
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa550313(v=AX.60)
ms:contentKeyID: 36676402
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About product models 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A product model is an executable schema that enables the configuration of an item by using the user dialog box that is based on a set of modeling and calculation variables, validation rules and modeling tree nodes.


> [!NOTE]
> <P>This information applies only to Product builder.</P>



Product models are only created for products with the **Modeling enabled** check box selected on the **Released product details** form.

When you create a product model, at a minimum you must:

  - Create modeling variables

  - Create modeling variable groups

  - Create calculation variables

  - Set up validation rules

  - Insert nodes in the modeling tree

When you develop a product model in Product Builder, you extend the code base of Microsoft Dynamics AX 2012 with new X++ code. Be sure to secure any external resources used by your product model, such as graphics and files, in addition to the application’s temporary folder.

## See also

[About product builder items](about-product-builder-items.md)

  


