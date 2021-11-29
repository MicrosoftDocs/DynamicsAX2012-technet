---
title: OfferDiscount Methods (Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData)
TOCTitle: OfferDiscount Methods
ms:assetid: Methods.T:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData.OfferDiscount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine.discountdata.offerdiscount_methods(v=AX.60)
ms:contentKeyID: 62206738
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# OfferDiscount Methods


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The [OfferDiscount](offerdiscount-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md) type exposes the following members.

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
<td><img src="images/Dn987397.protmethod(en-us,AX.60).gif" title="Protected method" alt="Protected method" /></td>
<td><a href="discountbase-candiscountapply-method-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md">CanDiscountApply</a></td>
<td>Determines if this discount can possibly apply to the specified transaction by examining all of the triggering rules not related to the actual line items on the transaction. (Inherited from <a href="discountbase-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md">DiscountBase</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.protmethod(en-us,AX.60).gif" title="Protected method" alt="Protected method" /></td>
<td><a href="discountbase-containsproductforretaildiscountlines-method-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md">ContainsProductForRetailDiscountLines</a></td>
<td>Determines if the trigger products contain the product or the variant Id. (Inherited from <a href="discountbase-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md">DiscountBase</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="https://technet.microsoft.com/library/bsc2ak47(v=ax.60)">Equals</a></td>
<td>(Inherited from <a href="https://technet.microsoft.com/library/e5kfa45b(v=ax.60)">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.protmethod(en-us,AX.60).gif" title="Protected method" alt="Protected method" /></td>
<td><a href="https://technet.microsoft.com/library/4k87zsw7(v=ax.60)">Finalize</a></td>
<td>(Inherited from <a href="https://technet.microsoft.com/library/e5kfa45b(v=ax.60)">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="offerdiscount-generatediscountlines-method-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md">GenerateDiscountLines</a></td>
<td>(Overrides <a href="discountbase-generatediscountlines-method-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md">DiscountBase.GenerateDiscountLines(AppliedDiscountApplication, DiscountableItemGroup[], PriceContext)</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="offerdiscount-getapplieddiscountapplication-method-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md">GetAppliedDiscountApplication</a></td>
<td>(Overrides <a href="discountbase-getapplieddiscountapplication-method-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md">DiscountBase.GetAppliedDiscountApplication(DiscountableItemGroup[], Decimal[], Stack&lt;AppliedDiscountApplication&gt;, DiscountApplication, PriceContext, Boolean)</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="offerdiscount-getdiscountapplications-method-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md">GetDiscountApplications</a></td>
<td>Gets all of the possible applications of this discount to the specified transaction and line items. (Overrides <a href="discountbase-getdiscountapplications-method-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md">DiscountBase.GetDiscountApplications(SalesTransaction, DiscountableItemGroup[], Decimal[], IEnumerable&lt;Int64&gt;, String, IPricingDataManagerV2, Boolean, PriceContext)</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.protmethod(en-us,AX.60).gif" title="Protected method" alt="Protected method" /></td>
<td><a href="discountbase-getdiscountcodefordiscount-method-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md">GetDiscountCodeForDiscount</a></td>
<td>Gets the (first) discount code from the transaction that triggered the discount. (Inherited from <a href="discountbase-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md">DiscountBase</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.protmethod(en-us,AX.60).gif" title="Protected method" alt="Protected method" /></td>
<td><a href="discountbase-getexistingdiscountdictionaryanddiscountedprices-method-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md">GetExistingDiscountDictionaryAndDiscountedPrices</a></td>
<td>(Inherited from <a href="discountbase-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md">DiscountBase</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.protmethod(en-us,AX.60).gif" title="Protected method" alt="Protected method" /></td>
<td><a href="discountbase-getfirstmatchinglineforitem-method-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md">GetFirstMatchingLineForItem</a></td>
<td>Determines if the specified item is valid for the specified discount line. (Inherited from <a href="discountbase-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md">DiscountBase</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="https://technet.microsoft.com/library/zdee4b3y(v=ax.60)">GetHashCode</a></td>
<td>(Inherited from <a href="https://technet.microsoft.com/library/e5kfa45b(v=ax.60)">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="discountbase-getproductorvariantidtoretaildiscountlinesmap-method-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md">GetProductOrVariantIdToRetailDiscountLinesMap</a></td>
<td>Gets product or variant Id to retail discount lines map. (Inherited from <a href="discountbase-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md">DiscountBase</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.protmethod(en-us,AX.60).gif" title="Protected method" alt="Protected method" /></td>
<td><a href="discountbase-getsortindexforretaildiscountline-method-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md">GetSortIndexForRetailDiscountLine</a></td>
<td>Gets the sort index to use for a discount application using the specified discount line. (Inherited from <a href="discountbase-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md">DiscountBase</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="https://technet.microsoft.com/library/dfwy45w9(v=ax.60)">GetType</a></td>
<td>(Inherited from <a href="https://technet.microsoft.com/library/e5kfa45b(v=ax.60)">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.protmethod(en-us,AX.60).gif" title="Protected method" alt="Protected method" /></td>
<td><a href="discountbase-initializediscountdictionary-method-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md">InitializeDiscountDictionary</a></td>
<td>(Inherited from <a href="discountbase-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md">DiscountBase</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.protmethod(en-us,AX.60).gif" title="Protected method" alt="Protected method" /></td>
<td><a href="discountbase-isitemvalidforline-method-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md">IsItemValidForLine</a></td>
<td>Determines if the specified item is valid for the specified discount line. (Inherited from <a href="discountbase-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md">DiscountBase</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.protmethod(en-us,AX.60).gif" title="Protected method" alt="Protected method" /></td>
<td><a href="https://technet.microsoft.com/library/57ctke0a(v=ax.60)">MemberwiseClone</a></td>
<td>(Inherited from <a href="https://technet.microsoft.com/library/e5kfa45b(v=ax.60)">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.protmethod(en-us,AX.60).gif" title="Protected method" alt="Protected method" /></td>
<td><a href="discountbase-newdiscountline-method-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md">NewDiscountLine</a></td>
<td>Create a new discount line. (Inherited from <a href="discountbase-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md">DiscountBase</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="https://technet.microsoft.com/library/7bxwbwt2(v=ax.60)">ToString</a></td>
<td>(Inherited from <a href="https://technet.microsoft.com/library/e5kfa45b(v=ax.60)">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.protmethod(en-us,AX.60).gif" title="Protected method" alt="Protected method" /></td>
<td><a href="discountbase-trygetretaildiscountlines-method-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md">TryGetRetailDiscountLines</a></td>
<td>Try getting retail discount lines by variant Id or product Id. (Inherited from <a href="discountbase-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md">DiscountBase</a>.)</td>
</tr>
</tbody>
</table>


Top

## See Also

#### Reference

[OfferDiscount Class](offerdiscount-class-microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine.DiscountData Namespace](microsoft-dynamics-commerce-runtime-services-pricingengine-discountdata-namespace.md)

