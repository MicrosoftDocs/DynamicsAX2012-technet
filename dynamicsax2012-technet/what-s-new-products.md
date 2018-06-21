---
title: "What's new: Products"
TOCTitle: Products
ms:assetid: 107cac2b-8fa7-4325-863c-76970cfa2b78
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn507146(v=AX.60)
ms:contentKeyID: 59623235
ms.date: 05/01/2014
mtps_version: v=AX.60
---

# What's new: Products [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX 2012, new products can be defined and released to individual companies. Additionally, an item is now always based on a product definition. In Microsoft Dynamics AX 2009, you could create items without using a formalized definition process.

## Overview

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Item</strong></p></th>
<th><p><strong>Description</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Required</p></td>
<td><p>Conditionally required. If you are using this feature in an earlier version of Microsoft Dynamics AX, significant changes have been made, and you must review this topic.</p></td>
</tr>
<tr class="even">
<td><p>Feature areas affected</p></td>
<td><p>Inventory management</p>
<p>Product information management</p></td>
</tr>
<tr class="odd">
<td><p>Stakeholders</p></td>
<td><p>Business decision makers</p>
<p>Technical decision makers</p>
<p>Implementation team members</p>
<p>Independent software vendors (ISVs)/developers</p>
<p>Partners</p></td>
</tr>
</tbody>
</table>


## New functionality

A product definition level is added as a mandatory step in the process for creating items, and all items are now associated with a product definition.

## Special considerations

Items are based on product definitions. Therefore, product definitions are required for all items in AX 2012.

## Comparison with AX 2009

The inventory process has changed considerably since AX 2009. AX 2012 includes changes to the following areas:

  - Products and product variants

  - Product release

  - Product translations

  - New division of the inventory dimension group

## Products and product variants

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Create and maintain definitions for products, and master definitions for sets of products, at the shared company level.</p></td>
<td><p>The feature was not available, because item definitions were created directly in the item table.</p></td>
<td><p>Items are always based on product definitions, and product definitions can be shared across companies.</p></td>
<td><p>Product creation is centralized, and all the products and product variants that are available in the whole organization are displayed.</p></td>
</tr>
<tr class="even">
<td><p>Generate product variants that are based on product masters.</p></td>
<td><p>Product variants were available as combinations of item dimensions. However, it was difficult to administer which legal entities had access to which variants.</p></td>
<td><p>New items can be created as product variants that are based on an associated product dimension setup.</p></td>
<td><p>An overview is provided of the product variants that are traded.</p></td>
</tr>
<tr class="odd">
<td><p>Configure product variants by using a product configuration technology.</p></td>
<td><p>The feature was available but did not include the configuration technology option.</p></td>
<td><p>Product definitions include information about when and how variants are configured.</p></td>
<td><p>A user can control the configuration strategy of an item through the product definition.</p></td>
</tr>
<tr class="even">
<td><p>Standardize items by using product definition templates.</p></td>
<td><p>Not available</p></td>
<td><p>A product definition record can be saved as a template.</p></td>
<td><p>A product definition template can help standardize items.</p></td>
</tr>
</tbody>
</table>


## Product release

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Share product definitions across companies.</p></td>
<td><p>Not available</p></td>
<td><p>Product definitions can be authorized for use in multiple companies.</p></td>
<td><p>A product repository can be centrally controlled.</p></td>
</tr>
<tr class="even">
<td><p>Maintain open product releases.</p></td>
<td><p>Not available</p></td>
<td><p>A release can be repeated after an error is corrected, or the release of a product can be postponed.</p></td>
<td><p>The release process and the timing of product releases can be controlled.</p></td>
</tr>
</tbody>
</table>


## Product translations

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Translate product names and information.</p></td>
<td><p>Only product descriptions were translated.</p></td>
<td><p>Product names, product variant names, and the description attributes for a product definition are displayed on a customer invoice.</p></td>
<td><p>This feature provides a better understanding of the actual product definition.</p></td>
</tr>
</tbody>
</table>


## New division of the inventory dimension group

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Set up separate product, storage, and tracking dimension groups.</p></td>
<td><p>Items were associated with one inventory dimension group, where all three types of dimensions were set up.</p></td>
<td><p>The setup of inventory dimensions for items is flexible. The following dimensions are specified separately:</p>
<ul>
<li><p>Product dimensions for item characteristics that are associated with the product definition</p></li>
<li><p>Storage and tracking dimensions for a location-specific setup that is associated with the physical handling of items in companies</p></li>
</ul></td>
<td><p>The setup of the storage and tracking dimension groups can be either centralized or decentralized.</p></td>
</tr>
</tbody>
</table>


## More information

For more information about the address book framework, see the white paper [Implementing the Item-Product data management framework for Microsoft Dynamics AX 2012](http://download.microsoft.com/download/4/e/3/4e36b655-568e-4d4a-b161-152b28baaf30/implementing_item-product_data_management_framework_for_microsoft_dynamics_ax_2012_applications_ax2012.pdf).

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

