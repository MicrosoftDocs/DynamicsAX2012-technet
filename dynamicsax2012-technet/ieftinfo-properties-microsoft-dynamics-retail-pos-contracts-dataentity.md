---
title: IEFTInfo Properties (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: IEFTInfo Properties
ms:assetid: Properties.T:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfo
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ieftinfo_properties(v=AX.60)
ms:contentKeyID: 47129033
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# IEFTInfo Properties


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The [IEFTInfo](ieftinfo-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md) type exposes the following members.

## Properties

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
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-accounttype-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">AccountType</a></td>
<td>Gets or sets the type of the account (for example, checking, saving, etc.). A debit operation, for example, may require that the account type be specified. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-acquirername-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">AcquirerName</a></td>
<td>Read this property to print the acquirer on the sales slip. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-additionalsecurityinformation-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">AdditionalSecurityInformation</a></td>
<td>Additional card security information collected from the hardware device. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-address-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">Address</a></td>
<td>The street address associated with the card. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-amount-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">Amount</a></td>
<td>The amount associated with the transaction. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-applicationidentifier-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">ApplicationIdentifier</a></td>
<td>Gets or sets the application identifier (AID). (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-authcode-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">AuthCode</a></td>
<td>For normal transactions, the authentication code can be read from this property. When manually calling for an authentication number, it must be placed in this property before authorization is requested. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-authorized-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">Authorized</a></td>
<td>True if the transaction was authorized; false if was not authorized. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-authorizedtext-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">AuthorizedText</a></td>
<td>Gets or sets the authorized text. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-authsourcecode-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">AuthSourceCode</a></td>
<td>Specifies how the authorization code was generated. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-authstring-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">AuthString</a></td>
<td>A zero filled from the left 6 digit number that is used. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-batchcode-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">BatchCode</a></td>
<td>A concatenated string specially used for receipts. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-batchnumber-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">BatchNumber</a></td>
<td>The current batch number for the terminal. The number can be read after each transaction. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-cardentrytype-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">CardEntryType</a></td>
<td>Indicates how the card number was received: manually or by swiping the card. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-cardname-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">CardName</a></td>
<td>The card name can be read from this property after the transaction. For example, “to be printed on a receipt”. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-cardnumber-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">CardNumber</a></td>
<td>The card number if the information was entered manually. After the transaction has been processed, this property holds the card number. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-cardnumberhidden-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">CardNumberHidden</a></td>
<td>Indicates whether the card number hidden. If so, the POS assumes it needs to ask for the card number. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-cardtype-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">CardType</a></td>
<td>The field is read to see what kind of card was used. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-cashback-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">CashBack</a></td>
<td>The cash back amount associated with the transaction for a debit card. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-checkdigits-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">CheckDigits</a></td>
<td>Gets or sets the check digits. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-encryptedpin-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">EncryptedPIN</a></td>
<td>The encrypted card pin number that is collected from the hardware device. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-entrysourcecode-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">EntrySourceCode</a></td>
<td>Indicate whether the card was swiped or manually entered. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-errorcode-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">ErrorCode</a></td>
<td>Gets or sets the error code. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-errormessage-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">ErrorMessage</a></td>
<td>The detailed error message for an EFT failure. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-europayauthcode-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">EuropayAuthCode</a></td>
<td>The contract number used for EuroPay. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-expdate-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">ExpDate</a></td>
<td>The expiration date if the information was entered manually. After the transaction has been processed, this property holds the expiration date. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-externalcardreceipts-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">ExternalCardReceipts</a></td>
<td>A list of card receipts acquired from an external EFT terminal that are to be printed at the end of the transaction. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-isauthonly-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">IsAuthOnly</a></td>
<td>Get or sets whether the EFT request is for authorize-only and should not be captured. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-isauthvoid-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">IsAuthVoid</a></td>
<td>True if the authorize transaction was cancelled; false if the transaction was not cancelled. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-isemv-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">IsEMV</a></td>
<td>The standard IC card type is EMV (Europay, MasterCard, and Visa). (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-isimmediatecapture-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">IsImmediateCapture</a></td>
<td>Get or sets whether the transaction is using immediate capture. The default is false for AuthOnly and CaptureOnly. true means we used auth and capture in one operation. This is a special case currently only supported by FDC EMP for debit cards. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-ispendingcapture-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">IsPendingCapture</a></td>
<td>Set if payment is pending capture. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov3-ispendingcustomersignature-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">IsPendingCustomerSignature</a></td>
<td>Gets or sets the customer sign expectation flag If it is true, it will be necessary to ask the customer to sign off the bank slip (Inherited from <a href="ieftinfov3-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV3</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-ispendingreversal-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">IsPendingReversal</a></td>
<td>Gets or sets the payment status to pending reversal. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-issuername-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">IssuerName</a></td>
<td>Gets or sets the issuer name. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-issuernumber-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">IssuerNumber</a></td>
<td>The issuer number. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-merchantnumber-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">MerchantNumber</a></td>
<td>A unique merchant number from VISA/Europay. The number can be read after processing the transaction. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-message-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">Message</a></td>
<td>Gets or sets the message. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-notauthorizedtext-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">NotAuthorizedText</a></td>
<td>Initialized to be empty (&quot;&quot;). (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov2-paymentproviderpropertiesxml-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">PaymentProviderPropertiesXML</a></td>
<td>Get or sets the Payment Provider Properties for this eft request (Inherited from <a href="ieftinfov2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV2</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-previoussequencecode-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">PreviousSequenceCode</a></td>
<td>Gets or sets the previous sequence code. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-processlocally-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">ProcessLocally</a></td>
<td>Indicate whether the card should be processed locally and not sent to the EFT service provider. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov2-processortenderid-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">ProcessorTenderId</a></td>
<td>Indicates the processor provided Tender ID for processor specific tenders (typically reprsented as a Guid)Null or empty when does not apply (Inherited from <a href="ieftinfov2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV2</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-providerresponsecode-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">ProviderResponseCode</a></td>
<td>Gets or sets the 2 digit provider response code. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-referraltelnumber-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">ReferralTelNumber</a></td>
<td>Gets or sets the referral telephone number. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-remainingbalance-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">RemainingBalance</a></td>
<td>The remaining balance on the card account, if available. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-responsecode-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">ResponseCode</a></td>
<td>The response code from Point. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-retrievalreferencenumber-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">RetrievalReferenceNumber</a></td>
<td>Gets or sets the retrieval reference number. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-savedcardnumber-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">SavedCardNumber</a></td>
<td>If the card number has been hidden, this holds the correct card number for refunds. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-securitycode-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">SecurityCode</a></td>
<td>The security code associated with the card. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-sequencecode-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">SequenceCode</a></td>
<td>A concatenated sequence code (seven letter - batch code) specially used for receipts. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-staffid-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">StaffId</a></td>
<td>The ID of the staff or operator if the operator is linked to the transaction. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-storenumber-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">StoreNumber</a></td>
<td>The store number. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-tendertype-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">TenderType</a></td>
<td>Gets or sets an ID that represents the tender that is used. The TenderType field is the ID of the payment made for the purchase. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-terminalid-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">TerminalId</a></td>
<td>A unique terminal ID from Visa or Europay. The ID can be read after processing the transaction. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-terminalnumber-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">TerminalNumber</a></td>
<td>The identification of the terminal that makes the transaction request. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-timeout-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">Timeout</a></td>
<td>The number of seconds to wait for the EFT Server. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-track1-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">Track1</a></td>
<td>Track1 of the magnetic stripe of the card if the card was swiped through a card reader. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-track2-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">Track2</a></td>
<td>Track2 of the magnetic stripe of the card if the card was swiped through a card reader. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov2-track3-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">Track3</a></td>
<td>Track4 of the magnetic stripe of the card - if the card was swept through a card reader (Inherited from <a href="ieftinfov2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV2</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov2-track4-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">Track4</a></td>
<td>Track4 of the magnetic stripe of the card - if the card was swept through a card reader (Inherited from <a href="ieftinfov2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV2</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-trackseperator-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">TrackSeperator</a></td>
<td>Gets or sets the track separator. It should be initialized to &quot;-&quot;. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-transactiondatetime-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">TransactionDateTime</a></td>
<td>The date and time of the transaction. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-transactionnumber-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">TransactionNumber</a></td>
<td>For a normal transaction, the transaction number can be read after the transaction. If this is a void transaction, this property must contain the transaction number to void. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-transactiontoken-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">TransactionToken</a></td>
<td>Get or sets the Transaction Token (the Secure Card Data) for this EFT request. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-transactiontype-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">TransactionType</a></td>
<td>Sets or returns the current value as described in the Enum TransactionType. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-visaauthcode-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">VisaAuthCode</a></td>
<td>The contract number used for Visa. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ieftinfov1-zipcode-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">ZipCode</a></td>
<td>The ZIP or Postal Code associated with the card. (Inherited from <a href="ieftinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IEFTInfoV1</a>.)</td>
</tr>
</tbody>
</table>


Top

## See Also

#### Reference

[IEFTInfo Interface](ieftinfo-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

