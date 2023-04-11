---
title: IBankDropTransaction Properties (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: IBankDropTransaction Properties
ms:assetid: Properties.T:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IBankDropTransaction
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ibankdroptransaction_properties(v=AX.60)
ms:contentKeyID: 49830704
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# IBankDropTransaction Properties


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The [IBankDropTransaction](ibankdroptransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md) type exposes the following members.

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
<td><a href="ibankdroptransactionv1-bankbagno-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">BankBagNo</a></td>
<td>(Inherited from <a href="ibankdroptransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IBankDropTransactionV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ipostransactionv1-begindatetime-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">BeginDateTime</a></td>
<td>Gets the start date and time of the transaction. (Inherited from <a href="ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IPosTransactionV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ipostransactionv3-businessdate-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">BusinessDate</a></td>
<td>Gets or sets the business date. (Inherited from <a href="ipostransactionv3-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IPosTransactionV3</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ipostransactionv1-comment-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">Comment</a></td>
<td>Gets the comment added by the operator. (Inherited from <a href="ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IPosTransactionV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ipostransactionv2-createdoffline-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">CreatedOffline</a></td>
<td>Gets whether this transaction was created while the terminal was offline. (Inherited from <a href="ipostransactionv2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IPosTransactionV2</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ipostransactionv1-createdonterminalid-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">CreatedOnTerminalId</a></td>
<td>Gets the original terminal that the transaction was created on, if the transaction was transferred from another terminal. (Inherited from <a href="ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IPosTransactionV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ipostransactionv2-creditcardtoken-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">CreditCardToken</a></td>
<td>Credit card token is created by the processor and represents the credit card number and is used within AX to process customer order securely (Inherited from <a href="ipostransactionv2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IPosTransactionV2</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ipostransactionv1-enddatetime-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">EndDateTime</a></td>
<td>Gets the finishing date and time of the transaction. (Inherited from <a href="ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IPosTransactionV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ipostransactionv1-fiscaldocumentid-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">FiscalDocumentId</a></td>
<td>Gets or sets the fiscal document ID. Available for add-in use; limited to 80 characters. (Inherited from <a href="ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IPosTransactionV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ipostransactionv1-fiscalserialid-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">FiscalSerialId</a></td>
<td>Gets or sets the fiscal serial ID. Available for add-in use; limited to 80 characters (Inherited from <a href="ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IPosTransactionV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ipostransactionv1-headofficecurrencycode-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">HeadOfficeCurrencyCode</a></td>
<td>Gets head office currency code, for example, GBP, USD, or EUR . (Inherited from <a href="ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IPosTransactionV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ipostransactionv1-lastrunoperationisvalidpayment-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">LastRunOperationIsValidPayment</a></td>
<td>Gets whether the last run operation was a valid payment operation. (Inherited from <a href="ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IPosTransactionV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ipostransactionv2-localhourofday-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">LocalHourOfDay</a></td>
<td>Local hour of day when transaction is created (Inherited from <a href="ipostransactionv2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IPosTransactionV2</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ipostransactionv1-opendrawer-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">OpenDrawer</a></td>
<td>Gets whether the drawer opened during the transaction. (Inherited from <a href="ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IPosTransactionV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ipostransactionv1-operationcancelled-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">OperationCancelled</a></td>
<td>Gets or sets the status of the operation. (Inherited from <a href="ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IPosTransactionV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ipostransactionv1-operatorid-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">OperatorId</a></td>
<td>Gets the operator ID. (Inherited from <a href="ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IPosTransactionV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ipostransactionv1-operatorname-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">OperatorName</a></td>
<td>Gets the operator name. (Inherited from <a href="ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IPosTransactionV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ipostransactionv1-operatornameonreceipt-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">OperatorNameOnReceipt</a></td>
<td>Gets the operator name that appears on the receipt. (Inherited from <a href="ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IPosTransactionV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ipostransactionv1-partnerdata-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">PartnerData</a></td>
<td>Get the dynamic object that holds the partner's data. (Inherited from <a href="ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IPosTransactionV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ipostransactionv1-receiptid-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">ReceiptId</a></td>
<td>Gets the receipt ID. (Inherited from <a href="ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IPosTransactionV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ipostransactionv1-shift-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">Shift</a></td>
<td>Gets or sets the shift for the transaction. (Inherited from <a href="ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IPosTransactionV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ipostransactionv1-statementmethod-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">StatementMethod</a></td>
<td>Gets the way a statement is done for the store (staff, terminal, or total). (Inherited from <a href="ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IPosTransactionV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ipostransactionv1-storeaddress-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">StoreAddress</a></td>
<td>Gets the store address. (Inherited from <a href="ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IPosTransactionV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ipostransactionv1-storecurrencycode-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">StoreCurrencyCode</a></td>
<td>Gets the store currency code, for example, GBP, USD, or EUR. (Inherited from <a href="ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IPosTransactionV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ipostransactionv1-storeexchangerate-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">StoreExchangeRate</a></td>
<td>Gets the exchange rate between the headquarters currency and the store currency. (Inherited from <a href="ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IPosTransactionV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ipostransactionv1-storeid-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">StoreId</a></td>
<td>Gets the store ID. (Inherited from <a href="ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IPosTransactionV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ipostransactionv1-storename-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">StoreName</a></td>
<td>Gets the store name. (Inherited from <a href="ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IPosTransactionV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ipostransactionv1-storephone-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">StorePhone</a></td>
<td>Gets the store phone number. (Inherited from <a href="ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IPosTransactionV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ipostransactionv1-terminalid-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">TerminalId</a></td>
<td>Gets the terminal ID. (Inherited from <a href="ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IPosTransactionV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ipostransactionv1-training-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">Training</a></td>
<td>Gets whether the POS is in training mode. (Inherited from <a href="ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IPosTransactionV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ipostransactionv1-transactionid-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">TransactionId</a></td>
<td>Gets the transaction ID. Note: This value is assigned quite late in the transaction process and therefore is not available from the beginning of the process. (Inherited from <a href="ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IPosTransactionV1</a>.)</td>
</tr>
</tbody>
</table>


Top

## See Also

#### Reference

[IBankDropTransaction Interface](ibankdroptransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

