---
title: IPeriodicDiscountItemV1 Properties (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: IPeriodicDiscountItemV1 Properties
ms:assetid: Properties.T:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPeriodicDiscountItemV1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.iperiodicdiscountitemv1_properties(v=AX.60)
ms:contentKeyID: 49841985
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# IPeriodicDiscountItemV1 Properties

The [IPeriodicDiscountItemV1](iperiodicdiscountitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md) type exposes the following members.

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
<td><a href="iperiodicdiscountitemv1-concurrencymode-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">ConcurrencyMode</a></td>
<td>How should the discount be applied Exclusively, by best price, or compounded</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iperiodicdiscountitemv1-discountcode-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">DiscountCode</a></td>
<td>Which coupon/promotion code (if any?) activated this discount</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iperiodicdiscountitemv1-iscompoundable-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">IsCompoundable</a></td>
<td>Some discount methods (e.g. offer price) can not be compounded, even if they're designated to be</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iperiodicdiscountitemv1-offerid-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">OfferId</a></td>
<td>The id of a periodic discount.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iperiodicdiscountitemv1-offername-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">OfferName</a></td>
<td>The name of a periodic discount.</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iperiodicdiscountitemv1-periodicdiscgroupid-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">PeriodicDiscGroupId</a></td>
<td>Identifies a particular application or 'instantiation' of a discount. When choosing best prices, the whole group is considered together. This is gives us the granularity to apply or skip parts of a discount or apply it to some of its eligible items, but not others.</td>
</tr>
</tbody>
</table>


Top

## See Also

#### Reference

[IPeriodicDiscountItemV1 Interface](iperiodicdiscountitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

