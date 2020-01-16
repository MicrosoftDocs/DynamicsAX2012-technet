---
title: IDiscountV1 Methods (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: IDiscountV1 Methods
ms:assetid: Methods.T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDiscountV1
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.idiscountv1_methods(v=AX.60)
ms:contentKeyID: 47344228
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# IDiscountV1 Methods

The [IDiscountV1](idiscountv1-interface-microsoft-dynamics-retail-pos-contracts-services.md) type exposes the following members.

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
<td><a href="idiscountv1-adddiscountline-method-microsoft-dynamics-retail-pos-contracts-services.md">AddDiscountLine</a></td>
<td>Add discount line</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="idiscountv1-addlinediscountamount-method-microsoft-dynamics-retail-pos-contracts-services.md">AddLineDiscountAmount</a></td>
<td>Applies a discount amount to a specific line item in a transaction.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="idiscountv1-addlinediscountpercent-method-microsoft-dynamics-retail-pos-contracts-services.md">AddLineDiscountPercent</a></td>
<td>Applies the percentage value to a specific line in a transaction.</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="idiscountv1-addtotaldiscountamount-method-microsoft-dynamics-retail-pos-contracts-services.md">AddTotalDiscountAmount</a></td>
<td>Entry point for additional manipulation of the retail transaction.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="idiscountv1-addtotaldiscountpercent-method-microsoft-dynamics-retail-pos-contracts-services.md">AddTotalDiscountPercent</a></td>
<td>Applies the provided percentage value as a discount to the total transaction balance.</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="idiscountv1-authorizelinediscountamount-method-microsoft-dynamics-retail-pos-contracts-services.md">AuthorizeLineDiscountAmount</a></td>
<td>Indicates whether the given line discount amount is allowed.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="idiscountv1-authorizelinediscountpercent-method-microsoft-dynamics-retail-pos-contracts-services.md">AuthorizeLineDiscountPercent</a></td>
<td>Indicates whether the given percentage discount is allowed.This method is invoked by the line discount percentage operation.</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="idiscountv1-authorizetotaldiscountamount-method-microsoft-dynamics-retail-pos-contracts-services.md">AuthorizeTotalDiscountAmount</a></td>
<td>Indicates whether the given total discount amount is allowed.This method is invoked by the total discount percentage operation before calling the AddTotalDiscountAmount method.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="idiscountv1-authorizetotaldiscountpercent-method-microsoft-dynamics-retail-pos-contracts-services.md">AuthorizeTotalDiscountPercent</a></td>
<td>Indicates whether the given discount percentage is allowed.This method is invoked by the total discount percentage operation before calling the AddTotalDiscountPercentage method.</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="idiscountv1-calculatediscount-method-microsoft-dynamics-retail-pos-contracts-services.md">CalculateDiscount</a></td>
<td>Calculates the discounts for all sales lines for the transaction.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="idiscountv1-isvalidationperiodactive-method-microsoft-dynamics-retail-pos-contracts-services.md">IsValidationPeriodActive</a></td>
<td>Finds the discount validation period and determines whether it is active for the given date and time</td>
</tr>
</tbody>
</table>


Top

## See Also

#### Reference

[IDiscountV1 Interface](idiscountv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

