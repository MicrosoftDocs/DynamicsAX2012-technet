---
title: IItemTriggerV1 Methods (Microsoft.Dynamics.Retail.Pos.Contracts.Triggers)
TOCTitle: IItemTriggerV1 Methods
ms:assetid: Methods.T:Microsoft.Dynamics.Retail.Pos.Contracts.Triggers.IItemTriggerV1
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.triggers.iitemtriggerv1_methods(v=AX.60)
ms:contentKeyID: 47128793
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# IItemTriggerV1 Methods


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The [IItemTriggerV1](iitemtriggerv1-interface-microsoft-dynamics-retail-pos-contracts-triggers.md) type exposes the following members.

## Methods

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
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="iitemtriggerv1-postpriceoverride-method-microsoft-dynamics-retail-pos-contracts-triggers.md">PostPriceOverride</a></td>
<td>Triggered after the price of an item is overridden.</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="iitemtriggerv1-postreturnitem-method-microsoft-dynamics-retail-pos-contracts-triggers.md">PostReturnItem</a></td>
<td>Triggered after an item is returned.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="iitemtriggerv1-postsale-method-microsoft-dynamics-retail-pos-contracts-triggers.md">PostSale</a></td>
<td>Triggered after the item is added to the transaction. Prices and discounts have been calculated, but the event is triggered before processing infocodes or linked items.</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="iitemtriggerv1-postsetqty-method-microsoft-dynamics-retail-pos-contracts-triggers.md">PostSetQty</a></td>
<td>Triggered after the quantity of an item is set.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="iitemtriggerv1-postvoiditem-method-microsoft-dynamics-retail-pos-contracts-triggers.md">PostVoidItem</a></td>
<td>Triggered after an item is voided.</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="iitemtriggerv1-prepriceoverride-method-microsoft-dynamics-retail-pos-contracts-triggers.md">PrePriceOverride</a></td>
<td>Triggered before the price of an item is overridden.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="iitemtriggerv1-prereturnitem-method-microsoft-dynamics-retail-pos-contracts-triggers.md">PreReturnItem</a></td>
<td>Triggered before an item is returned. The return operation only sets the till to a &quot;return state&quot;. It is the item sale operation that really returns the item (sells it with a negative quantity). Therefore, programming the &quot;return triggers&quot; only affects whether the till can enter the state when an item can be returned.</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="iitemtriggerv1-presale-method-microsoft-dynamics-retail-pos-contracts-triggers.md">PreSale</a></td>
<td>Triggered before the item is added to the transaction. Note: Data in saleLineItem, such as price and tax, is not yet set when this method is invoked.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="iitemtriggerv1-presetqty-method-microsoft-dynamics-retail-pos-contracts-triggers.md">PreSetQty</a></td>
<td>Triggered before the quantity of an item is set.</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="iitemtriggerv1-prevoiditem-method-microsoft-dynamics-retail-pos-contracts-triggers.md">PreVoidItem</a></td>
<td>Triggered before an item is voided.</td>
</tr>
</tbody>
</table>


Top

## See Also

#### Reference

[IItemTriggerV1 Interface](iitemtriggerv1-interface-microsoft-dynamics-retail-pos-contracts-triggers.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Triggers Namespace](microsoft-dynamics-retail-pos-contracts-triggers-namespace.md)

