---
title: IEFT Methods (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: IEFT Methods
ms:assetid: Methods.T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IEFT
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.ieft_methods(v=AX.60)
ms:contentKeyID: 47343983
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# IEFT Methods

The [IEFT](ieft-interface-microsoft-dynamics-retail-pos-contracts-services.md) type exposes the following members.

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
<td><a href="ieftv1-capturepayment-method-microsoft-dynamics-retail-pos-contracts-services.md">CapturePayment</a></td>
<td>Captures the card payment by establishing a connection with the configured payment processor.Once a connection to the broker is established, it attempts to capture the authorized card payment. (Inherited from <a href="ieftv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IEFTV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ieftv2-generatecardtoken-method-microsoft-dynamics-retail-pos-contracts-services.md">GenerateCardToken</a></td>
<td>Generate Credit card token is created by a payment SDK processor and represents the credit card number and is used within AX to process customer order securely Needs to internally set the posTransaction.CreditCardToken (Inherited from <a href="ieftv2-interface-microsoft-dynamics-retail-pos-contracts-services.md">IEFTV2</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ieftv1-getcardinfoandamount-method-microsoft-dynamics-retail-pos-contracts-services.md">GetCardInfoAndAmount</a></td>
<td>Implements workflows supported by the card type. (Inherited from <a href="ieftv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IEFTV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ieftv2-getpinpad-method-microsoft-dynamics-retail-pos-contracts-services.md">GetPinPad</a></td>
<td>Gets the pin pad. (Inherited from <a href="ieftv2-interface-microsoft-dynamics-retail-pos-contracts-services.md">IEFTV2</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ieftv2-getsignaturecapture-method-microsoft-dynamics-retail-pos-contracts-services.md">GetSignatureCapture</a></td>
<td>Gets the signature capture. (Inherited from <a href="ieftv2-interface-microsoft-dynamics-retail-pos-contracts-services.md">IEFTV2</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ieftv1-gettransactiontoken-method-microsoft-dynamics-retail-pos-contracts-services.md">GetTransactionToken</a></td>
<td>Gets transaction token for authorized transaction (Secure card storage). (Inherited from <a href="ieftv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IEFTV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ieftv1-identifycard-method-microsoft-dynamics-retail-pos-contracts-services.md">IdentifyCard</a></td>
<td>Identifies the card if a match with pre-configured card types in not found by the application. (Inherited from <a href="ieftv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IEFTV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ieftv1-processcardpayment-method-microsoft-dynamics-retail-pos-contracts-services.md">ProcessCardPayment</a></td>
<td>Processes the card payment by establishing a connection with the configured payment processor. (Inherited from <a href="ieftv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IEFTV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ieftv1-voidtransaction-method-microsoft-dynamics-retail-pos-contracts-services.md">VoidTransaction</a></td>
<td>Voids the card payment by establishing a connection with the configured payment processor. (Inherited from <a href="ieftv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IEFTV1</a>.)</td>
</tr>
</tbody>
</table>


Top

## See Also

#### Reference

[IEFT Interface](ieft-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

