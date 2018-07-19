---
title: Import vendor products overview
TOCTitle: Import vendor products overview
ms:assetid: 8569fd89-dcd4-481f-b60b-0d192c1e56ba
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh597150(v=AX.60)
ms:contentKeyID: 39519206
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- vendor
- vendors
- overview
- products
- product
audience: Application User
ms.search.region: Global
---

# Import vendor products overview 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

The topics in this section provide information about how to import products from vendors.

[About importing products from a vendor](about-importing-products-from-a-vendor.md)

[Set up vendor's product numbers](set-up-vendor-s-product-numbers.md)

[Set up a retail vendor hierarchy](set-up-a-retail-vendor-hierarchy.md)

[Import a product file from a vendor](import-a-product-file-from-a-vendor.md)

[Set up vendor sales price margins](set-up-vendor-sales-price-margins.md)

[Set up vendor sales price points](set-up-vendor-sales-price-points.md)

You can import product data files from vendors by using the vendor catalog import feature in Microsoft Dynamics AX. You can use the product data in these files to create and update products. The files from vendors are submitted as catalog maintenance request (CMR) files. CMR files can include the vendor’s product numbers, bar codes, descriptions, the vendor’s categories, size and color information, purchase prices, and sales prices. You can review the product data that is included in a CMR file, and then approve or reject the products. After the products are approved, the product data is added to the product master and released to specific legal entities. Product data is also added or updated for sales prices, purchase prices, bar codes, and variants, or used to create purchase orders.

For general information about the vendor catalog import feature in Microsoft Dynamics AX, see [Imported vendor catalogs overview](imported-vendor-catalogs-overview.md).

## Importing vendor products business process component forms

The following table lists the forms that support the Importing vendor products business process component. The table entries are organized by business process component task and then alphabetically by form name.


> [!NOTE]
> <P>Some forms in the following table require information or parameter settings to navigate to them.</P>



<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Business process component task</p></th>
<th><p>Form name</p></th>
<th><p>Usage</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Set up a vendor’s product numbers.</p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh597108(v=ax.60)">External product descriptions (form)</a></p></td>
<td><p>Map an external vendor’s product identifier and dimensions to an internal product.</p></td>
</tr>
<tr class="even">
<td><p> </p></td>
<td><p> </p></td>
<td><p> </p></td>
</tr>
<tr class="odd">
<td><p>Import a product data file from a vendor.</p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh209505(v=ax.60)">Catalog approval page (form)</a></p></td>
<td><p>Review and approve the vendor products to add them to the product master.</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh209525(v=ax.60)">Update catalog (form)</a></p></td>
<td><p>Add a new CMR file for a vendor.</p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh227602(v=ax.60)">Vendor catalog import parameters (form)</a></p></td>
<td><p>Set up the parameters that are used to store the CMR files that are received from vendors, and import the product data.</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh227480(v=ax.60)">Vendor catalogs (list page)</a></p></td>
<td><p>Create a catalog file to store the CMR files that are received from vendors, configure the vendor for catalog import, and generate the retail vendor template that is used to create the CMR files.</p></td>
</tr>
<tr class="odd">
<td><p> </p></td>
<td><p> </p></td>
<td><p> </p></td>
</tr>
<tr class="even">
<td><p>Set up sales price margins for vendors.</p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh580650(v=ax.60)">Vendor sales price margin setup (form)</a></p></td>
<td><p>Set up a formula that converts the vendor's suggested retail price or the vendor's purchase price to a sales price in local currency. This formula is used only if an entry for the product does not exist in the vendor's sales price points.</p></td>
</tr>
<tr class="odd">
<td><p> </p></td>
<td><p> </p></td>
<td><p> </p></td>
</tr>
<tr class="even">
<td><p>Set up sales price points for vendors.</p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/hh597319(v=ax.60)">Vendor sales price point setup (form)</a></p></td>
<td><p>Create a sales price point that converts the suggested retail prices of a vendor’s products to sales prices in local currency.</p></td>
</tr>
</tbody>
</table>


## See also

[About importing products from a vendor](about-importing-products-from-a-vendor.md)

  


