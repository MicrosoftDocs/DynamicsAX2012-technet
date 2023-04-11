---
title: IDiscount Methods (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: IDiscount Methods
ms:assetid: Methods.T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDiscount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.idiscount_methods(v=AX.60)
ms:contentKeyID: 47344048
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# IDiscount Methods


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The [IDiscount](idiscount-interface-microsoft-dynamics-retail-pos-contracts-services.md) type exposes the following members.

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
<td>Add discount line (Inherited from <a href="idiscountv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IDiscountV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="idiscountv1-addlinediscountamount-method-microsoft-dynamics-retail-pos-contracts-services.md">AddLineDiscountAmount</a></td>
<td>Applies a discount amount to a specific line item in a transaction. (Inherited from <a href="idiscountv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IDiscountV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="idiscountv1-addlinediscountpercent-method-microsoft-dynamics-retail-pos-contracts-services.md">AddLineDiscountPercent</a></td>
<td>Applies the percentage value to a specific line in a transaction. (Inherited from <a href="idiscountv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IDiscountV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="idiscountv2-addloyaltydiscountamount-method-microsoft-dynamics-retail-pos-contracts-services.md">AddLoyaltyDiscountAmount</a></td>
<td>Add the loyalty discount amount granted on the total transaction amount using loyalty points (Inherited from <a href="idiscountv2-interface-microsoft-dynamics-retail-pos-contracts-services.md">IDiscountV2</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="idiscountv1-addtotaldiscountamount-method-microsoft-dynamics-retail-pos-contracts-services.md">AddTotalDiscountAmount</a></td>
<td>Entry point for additional manipulation of the retail transaction. (Inherited from <a href="idiscountv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IDiscountV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="idiscountv1-addtotaldiscountpercent-method-microsoft-dynamics-retail-pos-contracts-services.md">AddTotalDiscountPercent</a></td>
<td>Applies the provided percentage value as a discount to the total transaction balance. (Inherited from <a href="idiscountv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IDiscountV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="idiscountv1-authorizelinediscountamount-method-microsoft-dynamics-retail-pos-contracts-services.md">AuthorizeLineDiscountAmount</a></td>
<td>Indicates whether the given line discount amount is allowed. (Inherited from <a href="idiscountv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IDiscountV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="idiscountv1-authorizelinediscountpercent-method-microsoft-dynamics-retail-pos-contracts-services.md">AuthorizeLineDiscountPercent</a></td>
<td>Indicates whether the given percentage discount is allowed.This method is invoked by the line discount percentage operation. (Inherited from <a href="idiscountv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IDiscountV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="idiscountv1-authorizetotaldiscountamount-method-microsoft-dynamics-retail-pos-contracts-services.md">AuthorizeTotalDiscountAmount</a></td>
<td>Indicates whether the given total discount amount is allowed.This method is invoked by the total discount percentage operation before calling the AddTotalDiscountAmount method. (Inherited from <a href="idiscountv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IDiscountV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="idiscountv1-authorizetotaldiscountpercent-method-microsoft-dynamics-retail-pos-contracts-services.md">AuthorizeTotalDiscountPercent</a></td>
<td>Indicates whether the given discount percentage is allowed.This method is invoked by the total discount percentage operation before calling the AddTotalDiscountPercentage method. (Inherited from <a href="idiscountv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IDiscountV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="idiscountv1-calculatediscount-method-microsoft-dynamics-retail-pos-contracts-services.md">CalculateDiscount</a></td>
<td>Calculates the discounts for all sales lines for the transaction. (Inherited from <a href="idiscountv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IDiscountV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="idiscountv2-calculatesimplediscount-method-microsoft-dynamics-retail-pos-contracts-services.md">CalculateSimpleDiscount</a></td>
<td>Calcalute simple discount, like discount offer. This is to delay computation heavy discount calculation until all items have been scanned. (Inherited from <a href="idiscountv2-interface-microsoft-dynamics-retail-pos-contracts-services.md">IDiscountV2</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="idiscountv1-isvalidationperiodactive-method-microsoft-dynamics-retail-pos-contracts-services.md">IsValidationPeriodActive</a></td>
<td>Finds the discount validation period and determines whether it is active for the given date and time (Inherited from <a href="idiscountv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IDiscountV1</a>.)</td>
</tr>
</tbody>
</table>


Top

## See Also

#### Reference

[IDiscount Interface](idiscount-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

