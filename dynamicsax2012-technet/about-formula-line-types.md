---
title: About formula line types
TOCTitle: About formula line types
ms:assetid: 6fda4eea-d452-4b8d-8cf0-d4394a5a5502
ms:mtpsurl: https://technet.microsoft.com/library/Hh352209(v=AX.60)
ms:contentKeyID: 36687843
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About formula line types 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you create a formula line, you use the line type to indicate how you want the program to handle the line. This is when you run master planning and producing batch orders. Each line type gives a different result. You can select from the following line types:

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Line type</strong></p></td>
<td><p><strong>Description</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Item</strong></p></td>
<td><p>Select <strong>Item</strong> when the item is a raw material or a semi-finished item that is picked from inventory or when the item is a service.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Phantom</strong></p></td>
<td><p>Select <strong>Phantom</strong> when you want to explode any lower-level formula items that are contained in formula lines. When you estimate the batch order and the formula items are exploded, the component items are listed as formula lines in the batch order. Also, the corresponding routes are added to the production route. Formula items are exploded using the current configuration. When you use the phantom line type, you can handle production and measurement configurations that occur at different formula levels.</p>
<div class="alert">

> [!NOTE]
> <P>If you select <STRONG>Phantom</STRONG> for a product on the <STRONG>Engineer</STRONG> FastTab in the <STRONG>Released product details</STRONG> form and then use this product in a formula, the formula line type changes to <STRONG>Phantom</STRONG>. You cannot select <STRONG>Phantom</STRONG> for a catch weight item or for items where the production type is <STRONG>Co-product</STRONG>, <STRONG>By-product</STRONG>, or <STRONG>Planning item</STRONG>.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Pegged supply</strong></p></td>
<td><p>Select <strong>Pegged supply</strong> to create a batch order for any formula items that are contained in formula lines. The batch order is created when you estimate the batch order. The required item quantities are reserved for the batch order.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Vendor</strong></p></td>
<td><p>Select <strong>Vendor</strong> if the production process uses a subcontractor and you want to create a sub production or a purchase order for the subcontractor. The service or work that is performed by the subcontractor must be created by using a Formula or Service item. You can attach it to the parent item as a formula line. The route must contain an operation that is assigned to the subcontractor’s operations resource. This operation is attached to the formula line using the <strong>Oper. No.</strong> field.</p></td>
</tr>
</tbody>
</table>


## See also

[About formulas](about-formulas.md)

[Formula (form)](https://technet.microsoft.com/library/hh328668\(v=ax.60\))

[Formula line (form)](https://technet.microsoft.com/library/hh352331\(v=ax.60\))

[(PM) Released product details (form)](https://technet.microsoft.com/library/hh352306\(v=ax.60\))

  


