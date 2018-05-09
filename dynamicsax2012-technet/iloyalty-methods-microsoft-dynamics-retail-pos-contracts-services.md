---
title: ILoyalty Methods (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ILoyalty Methods
ms:assetid: Methods.T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ILoyalty
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.iloyalty_methods(v=AX.60)
ms:contentKeyID: 47344506
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ILoyalty Methods

The [ILoyalty](iloyalty-interface-microsoft-dynamics-retail-pos-contracts-services.md) type exposes the following members.

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
<td><a href="iloyaltyv3-addloyaltydiscount-method-microsoft-dynamics-retail-pos-contracts-services.md">AddLoyaltyDiscount</a></td>
<td>Adds loyalty discount to the transaction. User is prompted to enter loyalty card number and discount amount. (Inherited from <a href="iloyaltyv3-interface-microsoft-dynamics-retail-pos-contracts-services.md">ILoyaltyV3</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="iloyalty-addloyaltypayment-method-microsoft-dynamics-retail-pos-contracts-services.md">AddLoyaltyPayment</a></td>
<td>Overloaded.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="iloyalty-addloyaltyrequest-method-microsoft-dynamics-retail-pos-contracts-services.md">AddLoyaltyRequest</a></td>
<td>Overloaded.</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="iloyaltyv1-calculateloyaltypoints-method-microsoft-dynamics-retail-pos-contracts-services.md">CalculateLoyaltyPoints</a></td>
<td>Called from the BusinessLogic or TransactionSystem method. (Inherited from <a href="iloyaltyv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">ILoyaltyV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="iloyaltyv4-captureloyaltyredeemorrefundlines-method-microsoft-dynamics-retail-pos-contracts-services.md">CaptureLoyaltyRedeemOrRefundLines</a></td>
<td>Captures loyalty reward point lines for redeem or refund. (Inherited from <a href="iloyaltyv4-interface-microsoft-dynamics-retail-pos-contracts-services.md">ILoyaltyV4</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="iloyaltyv4-getloyaltybalance-method-microsoft-dynamics-retail-pos-contracts-services.md">GetLoyaltyBalance</a></td>
<td>Gets loyalty card balance (Inherited from <a href="iloyaltyv4-interface-microsoft-dynamics-retail-pos-contracts-services.md">ILoyaltyV4</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="iloyaltyv4-getloyaltybalanceinfo-method-microsoft-dynamics-retail-pos-contracts-services.md">GetLoyaltyBalanceInfo</a></td>
<td>Gets loyalty card balance info. (Inherited from <a href="iloyaltyv4-interface-microsoft-dynamics-retail-pos-contracts-services.md">ILoyaltyV4</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="iloyaltyv3-getloyaltyitem-method-microsoft-dynamics-retail-pos-contracts-services.md">GetLoyaltyItem</a></td>
<td>Gets loyalty item based on the passed in card number (Inherited from <a href="iloyaltyv3-interface-microsoft-dynamics-retail-pos-contracts-services.md">ILoyaltyV3</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="iloyaltyv1-issueloyaltycard-method-microsoft-dynamics-retail-pos-contracts-services.md">IssueLoyaltyCard</a></td>
<td>Isses loyalty card. (Inherited from <a href="iloyaltyv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">ILoyaltyV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="iloyaltyv2-printloyaltybalance-method-microsoft-dynamics-retail-pos-contracts-services.md">PrintLoyaltyBalance</a></td>
<td>Submits the request to print loyalty card balance to the printer. (Inherited from <a href="iloyaltyv2-interface-microsoft-dynamics-retail-pos-contracts-services.md">ILoyaltyV2</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="iloyaltyv4-trytoaddloyaltyrequest-method-microsoft-dynamics-retail-pos-contracts-services.md">TryToAddLoyaltyRequest</a></td>
<td>Adds loyalty to the transaction, if any. (Inherited from <a href="iloyaltyv4-interface-microsoft-dynamics-retail-pos-contracts-services.md">ILoyaltyV4</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="iloyaltyv1-updateloyaltypoints-method-microsoft-dynamics-retail-pos-contracts-services.md">UpdateLoyaltyPoints</a></td>
<td>Called to update points in HQ when concluding a transaction. (Inherited from <a href="iloyaltyv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">ILoyaltyV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="iloyaltyv1-voidloyaltypayment-method-microsoft-dynamics-retail-pos-contracts-services.md">VoidLoyaltyPayment</a></td>
<td>Called when a loyalty payment is being voided. (Inherited from <a href="iloyaltyv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">ILoyaltyV1</a>.)</td>
</tr>
</tbody>
</table>


Top

## See Also

#### Reference

[ILoyalty Interface](iloyalty-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

