---
title: IPricingDataManager Methods (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: IPricingDataManager Methods
ms:assetid: Methods.T:Microsoft.Dynamics.Commerce.Runtime.Data.IPricingDataManager
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.ipricingdatamanager_methods(v=AX.60)
ms:contentKeyID: 49850325
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# IPricingDataManager Methods

The [IPricingDataManager](ipricingdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md) type exposes the following members.

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
<td><a href="ipricingdatamanager-findpriceadjustments-method-microsoft-dynamics-commerce-runtime-data.md">FindPriceAdjustments</a></td>
<td>Get all retail price adjustments matching the given product, channel price groups, currency, unit of measure, and date.</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ipricingdatamanager-findtradeagreements-method-microsoft-dynamics-commerce-runtime-data.md">FindTradeAgreements</a></td>
<td>This function retrieves all possible price agreements for the given args (item, customer, currency, etc), item relation code (item/group/all), and account relation code (customer/price group/all).</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ipricingdatamanager-getdiscountcodesbyofferid-method-microsoft-dynamics-commerce-runtime-data.md">GetDiscountCodesByOfferId</a></td>
<td>Get the discount codes (aka 'promo codes') associated with the given discount offer identifiers.</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ipricingdatamanager-getitems-method-microsoft-dynamics-commerce-runtime-data.md">GetItems</a></td>
<td>Gets the items using the specified item identifiers.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ipricingdatamanager-getmixandmatchlinegroupsbyoffer-method-microsoft-dynamics-commerce-runtime-data.md">GetMixAndMatchLineGroupsByOffer</a></td>
<td></td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ipricingdatamanager-getperiodicdiscounts-method-microsoft-dynamics-commerce-runtime-data.md">GetPeriodicDiscounts</a></td>
<td>Get all retail periodic discounts (offer, quantity discounts, and mix and match discount) configurations which match the given product and context.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ipricingdatamanager-getpricegroups-method-microsoft-dynamics-commerce-runtime-data.md">GetPriceGroups</a></td>
<td></td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ipricingdatamanager-getpriceparameters-method-microsoft-dynamics-commerce-runtime-data.md">GetPriceParameters</a></td>
<td>Retrieves PriceParameters from the database. This indicates which types of trade agreements are active for various combinations of customer and item types</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ipricingdatamanager-getquantitydiscountlevelbyquantity-method-microsoft-dynamics-commerce-runtime-data.md">GetQuantityDiscountLevelByQuantity</a></td>
<td>Get the quantity discount threshold level which the given quantity qualifies for on the given offer.</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ipricingdatamanager-getvalidationperiodbyid-method-microsoft-dynamics-commerce-runtime-data.md">GetValidationPeriodById</a></td>
<td>Get the periodic discount validation period with given identifier.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ipricingdatamanager-getvariantbyitemidandinventdimid-method-microsoft-dynamics-commerce-runtime-data.md">GetVariantByItemIdAndInventDimId</a></td>
<td>Gets the variant info for given item identifier and variant inventory dimension identifier.</td>
</tr>
</tbody>
</table>


Top

## See Also

#### Reference

[IPricingDataManager Interface](ipricingdatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

