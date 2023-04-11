---
title: (CHN) About BOM comparison
TOCTitle: (CHN) About BOM comparison
ms:assetid: 49361666-e338-4cd5-972b-5ce22d98eb87
ms:mtpsurl: https://technet.microsoft.com/library/JJ664034(v=AX.60)
ms:contentKeyID: 49384618
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BOM comparison
audience: Application User
ms.search.region: China (PRC)
---

# (CHN) About BOM comparison 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

A product may be accompanied by several versions of its bill of materials (BOM) over the course of its life-cycle, because many products are redesigned or modified to meet changing needs. The cost of a BOM generally reflects the actual cost of production, and is derived from the components and materials used, in addition to the direct and indirect costs of creating the final product. The price of the BOM can be assigned manually, or can be calculated by marking up the costs that are incurred during the manufacture or construction of the product.

Use the **BOM comparison** form to compare the component quantities and inventory cost, or the latest purchase price of the components among the various BOM versions.

BOM comparison also allows you to:

  - Create a new BOM for an existing product, based on earlier versions.

  - Compare and highlight differences in components among a group of similar products.

  - Answer customer inquiries about product differences and uses.

  - Maintain accurate inventory records in industrial and manufacturing environments.

  - Maintain accurate operational and personnel records, and data.

  - Respond quickly to changing production levels and requirements.

  - Control inventory levels.

  - Identify and reduce inventories of obsolete parts.

  - Lower overall manufacturing costs.

  - Improve design and construction processes.

  - Meet client needs by customizing designs and processes at various budget levels.

  - Generate conceptual estimates or customer quotes based on actual experience.

## Example

The following table illustrates how a BOM comparison is performed. In this example, products FG001 and FG003, each with one active BOM, and product FG002, which has two active BOMs, are compared. The report lists each component in a BOM version, displays the component quantity in the appropriate units, and displays the inventory cost or latest purchase price.

<table style="width:100%;">
<colgroup>
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Product</p></th>
<th><p>BOM</p></th>
<th><p>Site</p></th>
<th><p>Components</p></th>
<th><p>Quantity</p></th>
<th><p>Unit</p></th>
<th><p>Cost</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>FG001</p></td>
<td><p>FG001V1</p></td>
<td><p></p></td>
<td><p>MT001</p></td>
<td><p>2</p></td>
<td><p>pcs</p></td>
<td><p>USD 20.00</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p></p></td>
<td></td>
<td><p>MT002</p></td>
<td><p>3</p></td>
<td><p>cm</p></td>
<td><p>USD 10.00</p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>MT005</p></td>
<td><p>3</p></td>
<td><p>kg</p></td>
<td><p>USD 32.00</p></td>
</tr>
<tr class="even">
<td><p>FG002</p></td>
<td><p>FG002V1</p></td>
<td><p></p></td>
<td><p>MT001</p></td>
<td><p>1</p></td>
<td><p>pcs</p></td>
<td><p>USD 50.00</p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>MT003</p></td>
<td><p>1</p></td>
<td><p>pcs</p></td>
<td><p>USD 12.00</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>MT005</p></td>
<td><p>1</p></td>
<td><p>kg</p></td>
<td><p>USD 10.00</p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p>FG002V2</p></td>
<td><p>Site 1</p></td>
<td><p>MT002</p></td>
<td><p>3</p></td>
<td><p>cm</p></td>
<td><p>USD 30.00</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>MT004</p></td>
<td><p>2</p></td>
<td><p>box</p></td>
<td><p>USD 32.00</p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>MT005</p></td>
<td><p>1</p></td>
<td><p>kg</p></td>
<td><p>USD 10.00</p></td>
</tr>
<tr class="even">
<td><p>FG003</p></td>
<td><p>FG003V1</p></td>
<td><p></p></td>
<td><p>MT003</p></td>
<td><p>4</p></td>
<td><p>pcs</p></td>
<td><p>USD 30.00</p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>MT004</p></td>
<td><p>2</p></td>
<td><p>box</p></td>
<td><p>USD 23.00</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>MT005</p></td>
<td><p>3</p></td>
<td><p>kg</p></td>
<td><p>USD 18.00</p></td>
</tr>
</tbody>
</table>


## See also

[(CHN) BOM comparison (form)](https://technet.microsoft.com/library/jj664075\(v=ax.60\))

[BOM (form)](https://technet.microsoft.com/library/aa587282\(v=ax.60\))

[Create a BOM and BOM version](create-a-bom-and-bom-version.md)

[(CHN) Compare BOM versions and print the BOM comparison report](chn-compare-bom-versions-and-print-the-bom-comparison-report.md)

  


