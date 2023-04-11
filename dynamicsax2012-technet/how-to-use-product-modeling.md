---
title: How to use product modeling
TOCTitle: How to use product modeling
ms:assetid: 1cb54ba6-b267-4cd4-9249-d9c3aab204a5
ms:mtpsurl: https://technet.microsoft.com/library/Aa550968(v=AX.60)
ms:contentKeyID: 36689189
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# How to use product modeling 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Product modeling can be used whenever you create a new sales, purchase or production order line or quotation line for a modeling enabled item. Items that use product modeling must have the **Modeling enabled** check box selected in the **Released products** form. Additionally, they must be attached to a product model.


> [!NOTE]
> <P>This information applies only to Product builder.</P>




> [!NOTE]
> <P>You can attach an item to a product model in the upper pane of the <STRONG>Product models</STRONG> form.</P>



Enable Product modeling in one of the following ways. Which you chose depends on the type of order or quotation line you create:

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Sales order lines</p></td>
<td><p>Click <strong>Sales and marketing</strong> &gt; <strong>Common</strong> &gt; <strong>Sales orders</strong> &gt; <strong>All sales orders</strong>. Select a sales order Click <strong>Edit</strong>. Select a modeling enabled item. Click <strong>Product and supply</strong> &gt; <strong>Configure line</strong>.</p></td>
</tr>
<tr class="even">
<td><p>Purchase order lines</p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Common</strong> &gt; <strong>Purchase orders</strong> &gt; <strong>All purchase orders</strong>. Select a purchase order. Click <strong>Edit</strong>. Select a modeling enabled item. Click <strong>Product and supply</strong> &gt; <strong>Configure line</strong>.</p></td>
</tr>
<tr class="odd">
<td><p>Production order lines</p></td>
<td><p>Click <strong>Production control</strong> &gt; <strong>Common</strong> &gt; <strong>Production orders</strong> &gt; <strong>All production orders</strong>. To create a new production order, click <strong>Production order</strong> on the <strong>Action Pane.</strong></p>
<p>Select a modeling enabled item in the <strong>Item number</strong> field and then click <strong>Configure production</strong>.</p></td>
</tr>
<tr class="even">
<td><p>Sales quotation lines</p></td>
<td><p>Click <strong>Sales and marketing</strong> &gt; <strong>Common</strong> &gt; <strong>Sales quotations</strong> &gt; <strong>All quotations</strong>. Select a quotation. Click <strong>Edit</strong>. Select a modeling enabled item. Click <strong>Product and supply</strong> &gt; <strong>Configure line</strong></p></td>
</tr>
</tbody>
</table>


The product model's user dialog box generates the product model's lineup of modeling variables when line configuration is opened in this manner. The user then enters the required values or outcomes, and approves the configuration. Finally, the **Product Builder** module processes the item's modeling tree. This generates a bill of material and a route for the item. This BOM and route are attached to the order line.

## See also

[Product models (form)](https://technet.microsoft.com/library/aa572853\(v=ax.60\))

  


