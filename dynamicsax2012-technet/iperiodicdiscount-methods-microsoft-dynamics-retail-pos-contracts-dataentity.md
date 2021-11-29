---
title: IPeriodicDiscount Methods (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: IPeriodicDiscount Methods
ms:assetid: Methods.T:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPeriodicDiscount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iperiodicdiscount_methods(v=AX.60)
ms:contentKeyID: 49854879
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# IPeriodicDiscount Methods


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The [IPeriodicDiscount](iperiodicdiscount-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md) type exposes the following members.

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
<td><a href="https://technet.microsoft.com/library/es4s3w1d(v=ax.60)">Dispose</a></td>
<td>(Inherited from <a href="https://technet.microsoft.com/library/aax125c9(v=ax.60)">IDisposable</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="iperiodicdiscountv1-get-method-microsoft-dynamics-retail-pos-contracts-dataentity.md">Get</a></td>
<td>Retrieves the applicable discount lines for the item/variant. (Inherited from <a href="iperiodicdiscountv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IPeriodicDiscountV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="iperiodicdiscountv1-getdiscountofferdetails-method-microsoft-dynamics-retail-pos-contracts-dataentity.md">GetDiscountOfferDetails</a></td>
<td>Get barcode, Discountcode associated with an Offer (Inherited from <a href="iperiodicdiscountv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IPeriodicDiscountV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="iperiodicdiscountv1-hasitem-method-microsoft-dynamics-retail-pos-contracts-dataentity.md">HasItem</a></td>
<td>Returns true when the indicated item/variant discount rows have already been added to the cache (whether with a discount or no discount). This will prevent unneeded trips to the DB for subsequent calls. (Inherited from <a href="iperiodicdiscountv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IPeriodicDiscountV1</a>.)</td>
</tr>
</tbody>
</table>


Top

## See Also

#### Reference

[IPeriodicDiscount Interface](iperiodicdiscount-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

