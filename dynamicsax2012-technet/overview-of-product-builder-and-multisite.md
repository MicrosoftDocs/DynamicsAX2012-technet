---
title: Overview of Product Builder and multisite
TOCTitle: Overview of Product Builder and multisite
ms:assetid: ff4a9c8c-3617-4194-bdd6-0308b2425562
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg243318(v=AX.60)
ms:contentKeyID: 36676423
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- product builder
- multisite
- product model
audience: Application User
ms.search.region: Global
---

# Overview of Product Builder and multisite 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Product builder configuration supports single and multiple site environments and organizations that have not set up multiple sites. You have the option to create bills of materials (BOM) and route versions with the Product Builder configuration process.


> [!NOTE]
> <P>This information applies only to Product builder.</P>



When you enter a transaction using a Product Model enabled item, you can enter the site ID or accept the default site ID. The following tables describe how the default site ID is determined for each type of transaction.

For example, if there is a sales order line where the site ID field is blank in the **Customers** form, the site ID from the **Released products** form is used. If there is no site ID in the **Released products** form, the fallback warehouse in the **Inventory and warehouse management parameters** form is used.

Sales order lines and quotation lines:

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Default site ID assigned to this form</p></th>
<th><p>Navigation to the form</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>All customers</strong></p></td>
<td><p>Click <strong>Accounts receivable</strong> &gt; <strong>Common</strong> &gt; <strong>Customers</strong> &gt; <strong>All customers</strong>.Double-click a customer record. Click the <strong>Sales order defaults</strong> FastTab.</p></td>
</tr>
<tr class="even">
<td><p><strong>Released products</strong></p></td>
<td><p>Click <strong>Product information management</strong> &gt; <strong>Common</strong> &gt; <strong>Released products</strong>. Double-click a released product record. Click the <strong>Plan</strong> tab &gt; <strong>Default order settings</strong>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Inventory and warehouse management parameters</strong></p></td>
<td><p>Click <strong>Inventory management</strong> &gt; <strong>Setup</strong> &gt; <strong>Inventory and warehouse management parameters</strong>. The <strong>Fallback warehouse</strong> on the <strong>General</strong> tab.</p></td>
</tr>
</tbody>
</table>


Production order lines and project order lines:

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Default site ID assigned to this form</p></th>
<th><p>Navigation to the form</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Released products</strong></p></td>
<td><p>Click <strong>Product information management</strong> &gt; <strong>Common</strong> &gt; <strong>Released products</strong>. Double-click a released product record. Click the <strong>Plan</strong> tab &gt; <strong>Default order settings</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Inventory and warehouse management parameters</strong></p></td>
<td><p>Click <strong>Inventory management</strong> &gt; <strong>Setup</strong> &gt; <strong>Inventory and warehouse management parameters</strong>. The <strong>Fallback warehouse</strong> on the <strong>General</strong> tab.</p></td>
</tr>
</tbody>
</table>


Purchase order lines:

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Default site ID assigned to this form</p></th>
<th><p>Navigation to the form</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>All vendors</strong></p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Common</strong> &gt; <strong>Vendors</strong> &gt; <strong>All vendors</strong>. Double click a vendor record. Click the <strong>Purchase order defaults</strong> tab.</p></td>
</tr>
<tr class="even">
<td><p><strong>Released products</strong></p></td>
<td><p>Click <strong>Product information management</strong> &gt; <strong>Common</strong> &gt; <strong>Released products</strong>. Double-click a released product record. Click the <strong>Plan</strong> tab &gt; <strong>Default order settings</strong>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Inventory and warehouse management parameters</strong></p></td>
<td><p>Click <strong>Inventory management</strong> &gt; <strong>Setup</strong> &gt; <strong>Inventory and warehouse management parameters</strong>. The <strong>Fallback warehouse</strong> on the <strong>General</strong> tab.</p></td>
</tr>
</tbody>
</table>


As the items are configured during the sales process, custom BOMs and routes are created automatically at the correct production site.


> [!NOTE]
> <P>The default warehouse settings are transferred from the <STRONG>General</STRONG> tab of the <STRONG>Default order settings</STRONG> form to the <STRONG>Overview</STRONG> tab of the <STRONG>Site specific order settings</STRONG> form. The default warehouse settings on the <STRONG>General</STRONG> tab of the <STRONG>Default order settings</STRONG> form are replaced by the default site settings. Click <STRONG>Product information management</STRONG> &gt; <STRONG>Common</STRONG> &gt; <STRONG>Released products</STRONG>. Press CTRL+SHIFT+G to view all items. Select an item, and then click <STRONG>Plan</STRONG> &gt; <STRONG>Default order settings</STRONG>.</P>



## See also

[Configure a product model to use a distribution site](configure-a-product-model-to-use-a-distribution-site.md)

[Configure a multilevel BOM item requiring production in multiple sites](configure-a-multilevel-bom-item-requiring-production-in-multiple-sites.md)

[Order settings (form)](https://technet.microsoft.com/en-us/library/hh209541\(v=ax.60\))

  


