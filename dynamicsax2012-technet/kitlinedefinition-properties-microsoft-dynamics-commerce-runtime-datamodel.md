---
title: KitLineDefinition Properties (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: KitLineDefinition Properties
ms:assetid: Properties.T:Microsoft.Dynamics.Commerce.Runtime.DataModel.KitLineDefinition
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.kitlinedefinition_properties(v=AX.60)
ms:contentKeyID: 62202297
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# KitLineDefinition Properties


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The [KitLineDefinition](kitlinedefinition-class-microsoft-dynamics-commerce-runtime-datamodel.md) type exposes the following members.

## Properties

<table>
<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="kitlinedefinition-componentproductid-property-microsoft-dynamics-commerce-runtime-datamodel.md">ComponentProductId</a></td>
<td>Gets the product Id that is used as a default component in the current kit component definition.</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="kitlinedefinition-componentproperties-property-microsoft-dynamics-commerce-runtime-datamodel.md">ComponentProperties</a></td>
<td>Gets the collection of kit related properties of a product as a flat list.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="commerceentity-entityname-property-microsoft-dynamics-commerce-runtime-datamodel.md">EntityName</a></td>
<td>Gets the name of the entity. (Inherited from <a href="commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md">CommerceEntity</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="commerceentity-extensionproperties-property-microsoft-dynamics-commerce-runtime-datamodel.md">ExtensionProperties</a></td>
<td>Gets or sets the extension properties. (Inherited from <a href="commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md">CommerceEntity</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="kitlinedefinition-indexedcomponentproperties-property-microsoft-dynamics-commerce-runtime-datamodel.md">IndexedComponentProperties</a></td>
<td>Gets a list of kit component properties of all products used in the kit component line as substitute or as a default component product, indexed by the productId.</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="commerceentity-item-property-microsoft-dynamics-commerce-runtime-datamodel.md">Item</a></td>
<td>Gets or sets the value associated with the specified key. (Inherited from <a href="commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md">CommerceEntity</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="kitlinedefinition-kitlineidentifier-property-microsoft-dynamics-commerce-runtime-datamodel.md">KitLineIdentifier</a></td>
<td>Gets the kit line identifier (RecordId) of the current kit line component definition.</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="kitlinedefinition-substituteproductids-property-microsoft-dynamics-commerce-runtime-datamodel.md">SubstituteProductIds</a></td>
<td>Gets all possible substitutable products for the current kit component line. If the substitutes are all variants of the same product master, only the product master is saved in this list, otherwise productvariant ids are saved. This list also includes the product used as a default component in the kit line.</td>
</tr>
</tbody>
</table>


Top

## See Also

#### Reference

[KitLineDefinition Class](kitlinedefinition-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

