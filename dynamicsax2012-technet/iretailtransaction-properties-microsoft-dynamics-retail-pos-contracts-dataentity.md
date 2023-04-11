---
title: IRetailTransaction Properties (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: IRetailTransaction Properties
ms:assetid: Properties.T:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iretailtransaction_properties(v=AX.60)
ms:contentKeyID: 47128834
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# IRetailTransaction Properties


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The [IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md) type exposes the following members.

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
<td><a href="iretailtransactionv1-amounttoaccount-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">AmountToAccount</a></td>
<td>The total amount posted to customer account. (Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv1-balancenetamountwithtax-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">BalanceNetAmountWithTax</a></td>
<td>The total net amount(grossamount minus discounts) exluding tax. (Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ipostransactionv1-begindatetime-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">BeginDateTime</a></td>
<td>Gets the start date and time of the transaction. (Inherited from <a href="ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IPosTransactionV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ipostransactionv3-businessdate-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">BusinessDate</a></td>
<td>Gets or sets the business date. (Inherited from <a href="ipostransactionv3-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IPosTransactionV3</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv1-capture-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">Capture</a></td>
<td>Conclude transaction capture state. (Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv2-channelid-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">ChannelId</a></td>
<td>Id of the originating Channel (Inherited from <a href="iretailtransactionv2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV2</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv2-channelreferenceid-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">ChannelReferenceId</a></td>
<td>Reference ID set by the originating Channel (Inherited from <a href="iretailtransactionv2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV2</a>.)</td>
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
<td><a href="iretailtransactionv1-customerpaystax-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">CustomerPaysTax</a></td>
<td>Is set to true if the customer pays tax, else false. (Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv1-customerpurchrequestid-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">CustomerPurchRequestId</a></td>
<td>(Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv2-deliverymode-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">DeliveryMode</a></td>
<td>Delivery mode for the order (Inherited from <a href="iretailtransactionv2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV2</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ipostransactionv1-enddatetime-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">EndDateTime</a></td>
<td>Gets the finishing date and time of the transaction. (Inherited from <a href="ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IPosTransactionV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ipostransactionv1-fiscaldocumentid-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">FiscalDocumentId</a></td>
<td>Gets or sets the fiscal document ID. Available for add-in use; limited to 80 characters. (Inherited from <a href="ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IPosTransactionV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ipostransactionv1-fiscalserialid-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">FiscalSerialId</a></td>
<td>Gets or sets the fiscal serial ID. Available for add-in use; limited to 80 characters (Inherited from <a href="ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IPosTransactionV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv1-grossamount-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">GrossAmount</a></td>
<td>The total amount excluding tax; (Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv4-hasloyaltypayment-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">HasLoyaltyPayment</a></td>
<td>(Inherited from <a href="iretailtransactionv4-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV4</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ipostransactionv1-headofficecurrencycode-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">HeadOfficeCurrencyCode</a></td>
<td>Gets head office currency code, for example, GBP, USD, or EUR . (Inherited from <a href="ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IPosTransactionV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv1-idleelapsedtime-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">IdleElapsedTime</a></td>
<td>The total time the terminal was idle during the transaction. (Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv1-incomeexpenseamounts-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">IncomeExpenseAmounts</a></td>
<td>The total amount of income and expense accounts in the transaction (Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv2-inventlocationid-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">InventLocationId</a></td>
<td>Warehouse ID (Inherited from <a href="iretailtransactionv2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV2</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv3-inventlocationidreturns-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">InventLocationIdReturns</a></td>
<td>Warehouse ID for returns (Inherited from <a href="iretailtransactionv3-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV3</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv2-inventsiteid-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">InventSiteId</a></td>
<td>Site ID (Inherited from <a href="iretailtransactionv2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV2</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv1-invoicecomment-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">InvoiceComment</a></td>
<td>Comment to be printed on the invoice (Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv4-isdiscountfullycalculated-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">IsDiscountFullyCalculated</a></td>
<td>(Inherited from <a href="iretailtransactionv4-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV4</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv1-itemelapsedtime-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">ItemElapsedTime</a></td>
<td>The total time the terminal was handling items. (Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv1-keyitemgroupcount-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">KeyItemGroupCount</a></td>
<td>The number of items that where sold on an item group. (Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv1-keyitemgrouppercent-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">KeyItemGroupPercent</a></td>
<td>The percentage of items that where sold as an item group. (Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ipostransactionv1-lastrunoperationisvalidpayment-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">LastRunOperationIsValidPayment</a></td>
<td>Gets whether the last run operation was a valid payment operation. (Inherited from <a href="ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IPosTransactionV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv1-linediscount-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">LineDiscount</a></td>
<td>The total line discount given in this transaction minus the total discount. (Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv1-lineitemskeyedcount-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">LineItemsKeyedCount</a></td>
<td>The number of items that where keyed in. (Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv1-lineitemskeyedpercent-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">LineItemsKeyedPercent</a></td>
<td>The perenctage of items that where keyed in. (Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv1-lineitemsmultiscannedcount-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">LineItemsMultiScannedCount</a></td>
<td>The number of items that where scanned with a multi scanning device (Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv1-lineitemsmultiscannedpercent-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">LineItemsMultiScannedPercent</a></td>
<td>The percentage of items that where scanned with a multi scanning device (Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv1-lineitemssinglescannedcount-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">LineItemsSingleScannedCount</a></td>
<td>The number of items that where scanned with a single scanning device (Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv1-lineitemssinglescannedpercent-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">LineItemsSingleScannedPercent</a></td>
<td>The percentage of items that where scanned with a single scanning device (Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ipostransactionv2-localhourofday-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">LocalHourOfDay</a></td>
<td>Local hour of day when transaction is created (Inherited from <a href="ipostransactionv2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IPosTransactionV2</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv1-lockelapsedtime-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">LockElapsedTime</a></td>
<td>The total time the terminal was locked during the transaction. (Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv4-loyaltydiscount-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">LoyaltyDiscount</a></td>
<td>(Inherited from <a href="iretailtransactionv4-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV4</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv4-loyaltyitem-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">LoyaltyItem</a></td>
<td>(Inherited from <a href="iretailtransactionv4-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV4</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv4-loyaltymanualdiscountamount-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">LoyaltyManualDiscountAmount</a></td>
<td>(Inherited from <a href="iretailtransactionv4-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV4</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv1-miscellaneouschargestotal-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">MiscellaneousChargesTotal</a></td>
<td>Gets the miscellaneous charges total. (Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv1-netamountwithnotax-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">NetAmountWithNoTax</a></td>
<td>The total net amount(grossamount minus discounts) exluding tax. (Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv1-netamountwithtax-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">NetAmountWithTax</a></td>
<td>The total net amount(grossamount minus discounts) including tax. (Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv1-netamountwithtaxandcharges-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">NetAmountWithTaxAndCharges</a></td>
<td>The total net amount(grossamount minus discounts) including tax. (Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv1-noofitemlines-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">NoOfItemLines</a></td>
<td>Number of the item lines, not the qty of the items (Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv1-noofitems-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">NoOfItems</a></td>
<td>Number of items in the transaction - the total quantity. (Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv1-noofpaymentlines-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">NoOfPaymentLines</a></td>
<td>Number of payment lines. (Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ipostransactionv1-opendrawer-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">OpenDrawer</a></td>
<td>Gets whether the drawer opened during the transaction. (Inherited from <a href="ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IPosTransactionV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ipostransactionv1-operationcancelled-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">OperationCancelled</a></td>
<td>Gets or sets the status of the operation. (Inherited from <a href="ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IPosTransactionV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ipostransactionv1-operatorid-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">OperatorId</a></td>
<td>Gets the operator ID. (Inherited from <a href="ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IPosTransactionV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ipostransactionv1-operatorname-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">OperatorName</a></td>
<td>Gets the operator name. (Inherited from <a href="ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IPosTransactionV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ipostransactionv1-operatornameonreceipt-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">OperatorNameOnReceipt</a></td>
<td>Gets the operator name that appears on the receipt. (Inherited from <a href="ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IPosTransactionV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ipostransactionv1-partnerdata-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">PartnerData</a></td>
<td>Get the dynamic object that holds the partner's data. (Inherited from <a href="ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IPosTransactionV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv1-partnerobject-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">PartnerObject</a></td>
<td>An object which can hold any information that localization might want to add to the RetailTransaction (Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv1-payment-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">Payment</a></td>
<td>The total payment including the vat (Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv1-periodicdiscountamount-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">PeriodicDiscountAmount</a></td>
<td>//The total periodic discount given in this transaction. (Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv1-postasshipment-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">PostAsShipment</a></td>
<td>If the sale should be posted as an invoice or a shipment. Only used if customer is selected. (Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv1-receiptemailaddress-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">ReceiptEmailAddress</a></td>
<td>If the receipt for the transaction should be emailed the adderss is kept here. (Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ipostransactionv1-receiptid-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">ReceiptId</a></td>
<td>Gets the receipt ID. (Inherited from <a href="ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IPosTransactionV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv1-receiptsettings-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">ReceiptSettings</a></td>
<td>Should the receipt for the transaction be printed, emailed or even both. (Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv1-refundreceiptid-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">RefundReceiptId</a></td>
<td>Id of a receiption for items that will be refunded. (Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv2-requesteddeliverydate-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">RequestedDeliveryDate</a></td>
<td>Requested Delivery date for the order (Inherited from <a href="iretailtransactionv2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV2</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv4-returntransactionhasloyaltypayment-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">ReturnTransactionHasLoyaltyPayment</a></td>
<td>(Inherited from <a href="iretailtransactionv4-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV4</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv1-roundingdifference-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">RoundingDifference</a></td>
<td>(Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv1-roundingsalepmtdiff-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">RoundingSalePmtDiff</a></td>
<td>Rouding difference between payment and sales amount. Sales can be 9,99 but payment can be 10 (Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv1-saleisreturnsale-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">SaleIsReturnSale</a></td>
<td>True if the sale is a credit sale. (Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv1-salesinvoiceamounts-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">SalesInvoiceAmounts</a></td>
<td>The total amount of sales invoice payments in the transaction (Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv1-salesorderamounts-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">SalesOrderAmounts</a></td>
<td>The total amount of sales orders payments in the transaction (Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv1-salespersonid-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">SalesPersonId</a></td>
<td>The id of a salesperson if other than other than the operator. (Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv1-salespersonname-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">SalesPersonName</a></td>
<td>The name of a salesperson if other than other than the operator. (Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv1-salespersonnameonreceipt-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">SalesPersonNameOnReceipt</a></td>
<td>The name of a salesperson if other than other than the operator. (Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
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
<td><a href="iretailtransactionv1-tableid-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">TableId</a></td>
<td>The table id where the customers where sitting (Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv1-taxamount-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">TaxAmount</a></td>
<td>The total tax in transaction (Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv1-taxincludedinprice-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">TaxIncludedInPrice</a></td>
<td>Does the BO system provide the price including a tax. (Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv1-tenderelapsedtime-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">TenderElapsedTime</a></td>
<td>The total time the terminal was handling payments. (Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="ipostransactionv1-terminalid-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">TerminalId</a></td>
<td>Gets the terminal ID. (Inherited from <a href="ipostransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IPosTransactionV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv1-timewhentotalpressed-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">TimeWhenTotalPressed</a></td>
<td>The time of the first payment. (Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv1-totaldiscount-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">TotalDiscount</a></td>
<td>The total discount given in this transaction excluding the linediscount. (Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv1-totalmanualdiscountamount-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">TotalManualDiscountAmount</a></td>
<td>The total amount discount given manually for the total discount. (Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv1-totalmanualpctdiscount-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">TotalManualPctDiscount</a></td>
<td>The percentage discount given manually for the total discount. (Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
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
<tr class="even">
<td><img src="images/Dn998427.pubproperty(en-us,AX.60).gif" title="Public property" alt="Public property" /></td>
<td><a href="iretailtransactionv1-transsalepmtdiff-property-microsoft-dynamics-retail-pos-contracts-dataentity.md">TransSalePmtDiff</a></td>
<td>The difference between payment and grossAmount plus rounded (Inherited from <a href="iretailtransactionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md">IRetailTransactionV1</a>.)</td>
</tr>
</tbody>
</table>


Top

## See Also

#### Reference

[IRetailTransaction Interface](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

