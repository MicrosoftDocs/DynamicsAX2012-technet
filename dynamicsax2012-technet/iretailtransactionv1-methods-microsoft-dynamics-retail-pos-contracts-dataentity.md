---
title: IRetailTransactionV1 Methods (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: IRetailTransactionV1 Methods
ms:assetid: Methods.T:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransactionV1
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iretailtransactionv1_methods(v=AX.60)
ms:contentKeyID: 49833884
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# IRetailTransactionV1 Methods

The [IRetailTransactionV1](iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md) type exposes the following members.

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
<td><a href="iretailtransactionv1-addtotaldiscamountlines-method-microsoft-dynamics-retail-pos-contracts-dataentity.md">AddTotalDiscAmountLines</a></td>
<td>This method will distribute the amountToDiscount across all the sale items in the transaction proportionally except for the line item with the largest amount. The remainder will be distributed to the line item with the largest amount to ensure the amount to discount is exactly applied. This method currently works for either the customer discount or when the total discount button is applied</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="iretailtransactionv1-addtotaldiscpctlines-method-microsoft-dynamics-retail-pos-contracts-dataentity.md">AddTotalDiscPctLines</a></td>
<td>Adds total discount lines to the item lines.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="iretailtransactionv1-calctotals-method-microsoft-dynamics-retail-pos-contracts-dataentity.md">CalcTotals</a></td>
<td>Calculates all total sum in the transaction</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="iretailtransactionv1-calculateamountdue-method-microsoft-dynamics-retail-pos-contracts-dataentity.md">CalculateAmountDue</a></td>
<td>Calculates the amount due for this transaction</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="iretailtransactionv1-clearalldiscounts-method-microsoft-dynamics-retail-pos-contracts-dataentity.md">ClearAllDiscounts</a></td>
<td>Clears all discounts of all saleline items</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="iretailtransactionv1-clearcustomerdiscounts-method-microsoft-dynamics-retail-pos-contracts-dataentity.md">ClearCustomerDiscounts</a></td>
<td>Clears all customer discounts of all saleline items</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="iretailtransactionv1-clearperiodicdiscounts-method-microsoft-dynamics-retail-pos-contracts-dataentity.md">ClearPeriodicDiscounts</a></td>
<td>Clears all periodic discounts of all saleline items</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="iretailtransactionv1-cleartotaldiscountlines-method-microsoft-dynamics-retail-pos-contracts-dataentity.md">ClearTotalDiscountLines</a></td>
<td></td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="iretailtransactionv1-infocodeneeded-method-microsoft-dynamics-retail-pos-contracts-dataentity.md">InfoCodeNeeded</a></td>
<td>Looks through existing infocodes and check if the infocode already exists on the transaction.</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="iretailtransactionv1-iscustomerallowed-method-microsoft-dynamics-retail-pos-contracts-dataentity.md">IsCustomerAllowed</a></td>
<td>Determines whether [is customer allowed].</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="iretailtransactionv1-settotaldiscamount-method-microsoft-dynamics-retail-pos-contracts-dataentity.md">SetTotalDiscAmount</a></td>
<td>Set the amount given as a total discount for the transaction</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="iretailtransactionv1-settotaldiscpercent-method-microsoft-dynamics-retail-pos-contracts-dataentity.md">SetTotalDiscPercent</a></td>
<td>Set the total percentage discount given for the transaction</td>
</tr>
</tbody>
</table>


Top

## See Also

#### Reference

[IRetailTransactionV1 Interface](iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

