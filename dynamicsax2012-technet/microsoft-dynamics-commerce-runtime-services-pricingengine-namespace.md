---
title: Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine Namespace ()
TOCTitle: Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine Namespace
ms:assetid: N:Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.pricingengine(v=AX.60)
ms:contentKeyID: 49834811
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine
dev_langs:
- CSharp
- C++
- VB
---

# Microsoft.Dynamics.Commerce.Runtime.Services.PricingEngine Namespace


[!INCLUDE[archive-banner](includes/archive-banner.md)]

## Classes

<table>
<thead>
<tr class="header">
<th> </th>
<th>Class</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="images/Dn988315.pubclass(en-us,AX.60).gif" title="Public class" alt="Public class" /></td>
<td><a href="chargelinetotaler-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md">ChargeLineTotaler</a></td>
<td>This class encapsulates all logic for totalling a charge line once all the prices, discounts, charges, taxes, etc. have been set on it.</td>
</tr>
<tr class="even">
<td><img src="images/Dn988315.pubclass(en-us,AX.60).gif" title="Public class" alt="Public class" /></td>
<td><a href="discountparameters-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md">DiscountParameters</a></td>
<td>These parameters indicate which types of AX discounts (aka trade agreement discounts, aka not Retail Periodic Discounts) are currently activated and should be allowed on the transaction.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn988315.pubclass(en-us,AX.60).gif" title="Public class" alt="Public class" /></td>
<td><a href="indiapricehelper-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md">IndiaPriceHelper</a></td>
<td>Helper of India retail price.</td>
</tr>
<tr class="even">
<td><img src="images/Dn988315.pubclass(en-us,AX.60).gif" title="Public class" alt="Public class" /></td>
<td><a href="pricecontext-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md">PriceContext</a></td>
<td>Represents the overall settings and configuration to use when calculating prices for set of lines.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn988315.pubclass(en-us,AX.60).gif" title="Public class" alt="Public class" /></td>
<td><a href="pricecontexthelper-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md">PriceContextHelper</a></td>
<td>Price context builder.</td>
</tr>
<tr class="even">
<td><img src="images/Dn988315.pubclass(en-us,AX.60).gif" title="Public class" alt="Public class" /></td>
<td><a href="pricingengine-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md">PricingEngine</a></td>
<td>Contains logic for calculating retail prices.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn988315.pubclass(en-us,AX.60).gif" title="Public class" alt="Public class" /></td>
<td><a href="saleslinetotaller-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md">SalesLineTotaller</a></td>
<td>This class encapsulates all logic for totalling a sales line once all the prices, discounts, charges, taxes, etc. have been set on it.</td>
</tr>
<tr class="even">
<td><img src="images/Dn988315.pubclass(en-us,AX.60).gif" title="Public class" alt="Public class" /></td>
<td><a href="simpleprofiler-class-microsoft-dynamics-commerce-runtime-services-pricingengine.md">SimpleProfiler</a></td>
<td></td>
</tr>
</tbody>
</table>


## Enumerations

<table>
<thead>
<tr class="header">
<th> </th>
<th>Enumeration</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="images/Dn967095.pubenumeration(en-us,AX.60).gif" title="Public enumeration" alt="Public enumeration" /></td>
<td><a href="discountmethodtype-enumeration-microsoft-dynamics-commerce-runtime-services-pricingengine.md">DiscountMethodType</a></td>
<td>This indicates the method used to calculate the discount. Except for Least Expensive or Line-specific, these will define how a numeric discount value (defined elsewhere) is to be interpreted. E.g. if this is DiscountPercent, the value represents a percent off, if this is DealPrice, the value represents the price of the discounted item.</td>
</tr>
</tbody>
</table>

