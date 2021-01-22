---
title: About line types
TOCTitle: About line types
ms:assetid: e6c68ee5-d121-42e4-8820-f77969a5c938
ms:mtpsurl: https://technet.microsoft.com/library/Aa573189(v=AX.60)
ms:contentKeyID: 37832541
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About line types 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you create a BOM line, you use the BOM line type to indicate how you want the system to handle the line when you estimate the production order. Each line type gives a different result. The **Line type** field is located on the **General** tab of the **BOM line** form. You can select from the following BOM line types.

## Item

Select **Item** when the item is a raw material or semi-finished item that is picked from inventory, or when the item is a service.

## Phantom

Select **Phantom** when you want to explode any lower-level BOM items that are contained on the BOM line. When you estimate the production order, and the BOM items are exploded, the component items are listed as BOM lines in the production order, and the corresponding routes are added to the production route.

BOM items are exploded by using the current configuration. When you use the **Phantom** line type, you can handle production and measurement configurations that occur at different BOM levels.

## Pegged supply

Select **Pegged supply** when you want to create a subproduction for any BOM items that are contained on the BOM line. The subproduction is created when you estimate the production order. The required item quantities are automatically reserved for the production.

## Vendor

Select **Vendor** if the production process uses a subcontractor, and you want to create a subproduction or a purchase order for the subcontractor automatically.


> [!NOTE]
> <P>The service or work that is performed by the subcontractor must be created as a <STRONG>BOM</STRONG> or <STRONG>Service</STRONG> item in the <STRONG>Released product details</STRONG> form. You can attach it to the parent item as a BOM line.</P>
> <P>The route must contain an operation that is assigned to the subcontractor's operations resource.</P>



## See also

[BOM versions and lines (form)](https://technet.microsoft.com/library/aa615779\(v=ax.60\))

[Run an estimation](run-an-estimation.md)

  


