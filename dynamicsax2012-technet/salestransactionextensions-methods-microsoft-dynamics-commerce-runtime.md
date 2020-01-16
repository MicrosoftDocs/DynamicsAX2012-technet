---
title: SalesTransactionExtensions Methods (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: SalesTransactionExtensions Methods
ms:assetid: Methods.T:Microsoft.Dynamics.Commerce.Runtime.SalesTransactionExtensions
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.salestransactionextensions_methods(v=AX.60)
ms:contentKeyID: 49823105
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# SalesTransactionExtensions Methods

The [SalesTransactionExtensions](salestransactionextensions-class-microsoft-dynamics-commerce-runtime.md) type exposes the following members.

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
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /> <img src="images/Dn987454.static(en-us,AX.60).gif" title="Static member" alt="Static member" /></td>
<td><a href="salestransactionextensions-chargestotal-method-microsoft-dynamics-commerce-runtime.md">ChargesTotal</a></td>
<td>Get the sum of all charges on transaction and lines.</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /> <img src="images/Dn987454.static(en-us,AX.60).gif" title="Static member" alt="Static member" /></td>
<td><a href="salestransactionextensions-iseligiblefordiscount-method-microsoft-dynamics-commerce-runtime.md">IsEligibleForDiscount</a></td>
<td>True if this sales line may be valid for discounting (i.e. hasn't been voided or had a price override).</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /> <img src="images/Dn987454.static(en-us,AX.60).gif" title="Static member" alt="Static member" /></td>
<td><a href="salestransactionextensions-netamountwithnotax-method-microsoft-dynamics-commerce-runtime.md">NetAmountWithNoTax</a></td>
<td>The line amount not including tax (whether tax-exclusive or inclusive scenario). Any inclusive tax is subtracted from NetAmount.</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /> <img src="images/Dn987454.static(en-us,AX.60).gif" title="Static member" alt="Static member" /></td>
<td><a href="salestransactionextensions-netamountwithtax-method-microsoft-dynamics-commerce-runtime.md">NetAmountWithTax</a></td>
<td>The line amount including tax (whether tax-exclusive or inclusive scenario). Add exclusive taxes to NetAmount, inclusive taxes are already included in NetAmount.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /> <img src="images/Dn987454.static(en-us,AX.60).gif" title="Static member" alt="Static member" /></td>
<td><a href="salestransactionextensions-netamountwithtaxperunit-method-microsoft-dynamics-commerce-runtime.md">NetAmountWithTaxPerUnit</a></td>
<td>The line amount including tax (whether tax-exclusive or inclusive scenario) per unit. Add exclusive taxes to NetAmount, inclusive taxes are already included in NetAmount.</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /> <img src="images/Dn987454.static(en-us,AX.60).gif" title="Static member" alt="Static member" /></td>
<td><a href="salestransactionextensions-periodicdiscountlines-method-microsoft-dynamics-commerce-runtime.md">PeriodicDiscountLines</a></td>
<td>A collection of all periodic discounts belonging to the sales line.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /> <img src="images/Dn987454.static(en-us,AX.60).gif" title="Static member" alt="Static member" /></td>
<td><a href="salestransactionextensions-validatesalesorder-method-microsoft-dynamics-commerce-runtime.md">ValidateSalesOrder</a></td>
<td></td>
</tr>
</tbody>
</table>


Top

## See Also

#### Reference

[SalesTransactionExtensions Class](salestransactionextensions-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

