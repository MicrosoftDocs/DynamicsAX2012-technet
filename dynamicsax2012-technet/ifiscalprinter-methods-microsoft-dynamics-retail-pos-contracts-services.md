---
title: IFiscalPrinter Methods (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: IFiscalPrinter Methods
ms:assetid: Methods.T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IFiscalPrinter
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.ifiscalprinter_methods(v=AX.60)
ms:contentKeyID: 62203537
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# IFiscalPrinter Methods

The [IFiscalPrinter](ifiscalprinter-interface-microsoft-dynamics-retail-pos-contracts-services.md) type exposes the following members.

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
<td><a href="ifiscalprinterv3-addtogiftcard-method-microsoft-dynamics-retail-pos-contracts-services.md">AddToGiftCard</a></td>
<td>Add to gift card given the current transaction. (Inherited from <a href="ifiscalprinterv3-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV3</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-applicationstart-method-microsoft-dynamics-retail-pos-contracts-services.md">ApplicationStart</a></td>
<td>Triggers once, whenever the application starts. (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-authorizelinediscountamount-method-microsoft-dynamics-retail-pos-contracts-services.md">AuthorizeLineDiscountAmount</a></td>
<td>Returns true if discount amount is authorized. (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-authorizelinediscountpercent-method-microsoft-dynamics-retail-pos-contracts-services.md">AuthorizeLineDiscountPercent</a></td>
<td>Returns true if discount percent is correct. (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-authorizetotaldiscountamount-method-microsoft-dynamics-retail-pos-contracts-services.md">AuthorizeTotalDiscountAmount</a></td>
<td>Returns true if total discount amount is authorized. (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-authorizetotaldiscountpercent-method-microsoft-dynamics-retail-pos-contracts-services.md">AuthorizeTotalDiscountPercent</a></td>
<td>Returns true if total discount percent is authorized. (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-begintransaction-method-microsoft-dynamics-retail-pos-contracts-services.md">BeginTransaction</a></td>
<td>Triggered at the start of a new transaction, but after loading the transaction with initialisation data, such as the store, terminal number, date, etc... (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-blankoperations-method-microsoft-dynamics-retail-pos-contracts-services.md">BlankOperations</a></td>
<td>Displays an alert message according operation id passed. (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-canbeinitialized-method-microsoft-dynamics-retail-pos-contracts-services.md">CanBeInitialized</a></td>
<td>True if Fiscal printer can be initialized. (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-capstatus-method-microsoft-dynamics-retail-pos-contracts-services.md">CapStatus</a></td>
<td>Check if the cash drawer is capable of reporting back whether it's closed or open. (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-draweropen-method-microsoft-dynamics-retail-pos-contracts-services.md">DrawerOpen</a></td>
<td>Check if cash drawer is open. (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-fiscalprinterenabled-method-microsoft-dynamics-retail-pos-contracts-services.md">FiscalPrinterEnabled</a></td>
<td>Verifies if the fiscal printer extension is enabled for the current store. (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-getnextreceiptid-method-microsoft-dynamics-retail-pos-contracts-services.md">GetNextReceiptId</a></td>
<td>Retrieves the next receipt ID to use in the fiscal coupon. (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-hasreceiptidnumbering-method-microsoft-dynamics-retail-pos-contracts-services.md">HasReceiptIdNumbering</a></td>
<td>Determines whether the fiscal printer supports numbering function. (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv2-hassameshiftid-method-microsoft-dynamics-retail-pos-contracts-services.md">HasSameShiftId</a></td>
<td>Checks if Fiscal printer shift id equals to POS one (Inherited from <a href="ifiscalprinterv2-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV2</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-initialize-method-microsoft-dynamics-retail-pos-contracts-services.md">Initialize</a></td>
<td>Tries to initialize the class instance. (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-initializeprinter-method-microsoft-dynamics-retail-pos-contracts-services.md">InitializePrinter</a></td>
<td>Tries to initialize the printer driver, connect to the serial port, verifies the printer state, paper status and recover any pending transaction (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-issuegiftcard-method-microsoft-dynamics-retail-pos-contracts-services.md">IssueGiftCard</a></td>
<td>Issues a gift card given the current transaction. (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-isthirdpartycardpaymentenabled-method-microsoft-dynamics-retail-pos-contracts-services.md">IsThirdPartyCardPaymentEnabled</a></td>
<td>Verifies if there is EFT service integrated (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="iperipheralv1-load-method-microsoft-dynamics-retail-pos-contracts-services.md">Load</a></td>
<td>Loads the device. (Inherited from <a href="iperipheralv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IPeripheralV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-onpayment-method-microsoft-dynamics-retail-pos-contracts-services.md">OnPayment</a></td>
<td>Triggered after a payment. (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-opendrawer-method-microsoft-dynamics-retail-pos-contracts-services.md">OpenDrawer</a></td>
<td>Open the cash drawer. (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-postclearqty-method-microsoft-dynamics-retail-pos-contracts-services.md">PostClearQty</a></td>
<td>Triggered after clearing the quantity of a sale line item at the transaction. (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-postendtransaction-method-microsoft-dynamics-retail-pos-contracts-services.md">PostEndTransaction</a></td>
<td>Triggered at the end a transaction, after saving the transaction and printing of receipts (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-postlinediscountamount-method-microsoft-dynamics-retail-pos-contracts-services.md">PostLineDiscountAmount</a></td>
<td>Triggered after setting a line discount amount to the transaction. (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-postlinediscountpercent-method-microsoft-dynamics-retail-pos-contracts-services.md">PostLineDiscountPercent</a></td>
<td>Triggered after setting a line discount percent to the transaction. (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-postlogon-method-microsoft-dynamics-retail-pos-contracts-services.md">PostLogOn</a></td>
<td>Triggers after the login operation has been executed. (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-postprocessoperation-method-microsoft-dynamics-retail-pos-contracts-services.md">PostProcessOperation</a></td>
<td>After the operation has been processed this trigger is called. (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-postsale-method-microsoft-dynamics-retail-pos-contracts-services.md">PostSale</a></td>
<td>Triggered after adding a sale line item to the transaction. (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-postsetqty-method-microsoft-dynamics-retail-pos-contracts-services.md">PostSetQty</a></td>
<td>Triggered after setting the quantity of a sale line item at the transaction. (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-posttotaldiscountamount-method-microsoft-dynamics-retail-pos-contracts-services.md">PostTotalDiscountAmount</a></td>
<td>Triggered after setting a total discount amount to the transaction. (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-posttotaldiscountpercent-method-microsoft-dynamics-retail-pos-contracts-services.md">PostTotalDiscountPercent</a></td>
<td>Triggered after setting a total discount percent to the transaction. (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-postvoiditem-method-microsoft-dynamics-retail-pos-contracts-services.md">PostVoidItem</a></td>
<td>Triggered after voiding a sale line item at the transaction. (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-postvoidpayment-method-microsoft-dynamics-retail-pos-contracts-services.md">PostVoidPayment</a></td>
<td>Triggered after voiding of a payment. (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-postvoidtransaction-method-microsoft-dynamics-retail-pos-contracts-services.md">PostVoidTransaction</a></td>
<td>Triggered after voiding a transaction. (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-preclearqty-method-microsoft-dynamics-retail-pos-contracts-services.md">PreClearQty</a></td>
<td>Triggered prior to clearing the quantity of a sale line item at the transaction. (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-precustomer-method-microsoft-dynamics-retail-pos-contracts-services.md">PreCustomer</a></td>
<td>Triggered prior to adding a customer to the transaction (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-precustomerclear-method-microsoft-dynamics-retail-pos-contracts-services.md">PreCustomerClear</a></td>
<td>Triggered prior to clearing a customer from the transaction (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-precustomersearch-method-microsoft-dynamics-retail-pos-contracts-services.md">PreCustomerSearch</a></td>
<td>Triggered prior to adding a customer to the transaction using Customer search (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-precustomerset-method-microsoft-dynamics-retail-pos-contracts-services.md">PreCustomerSet</a></td>
<td>Triggered prior to setting a customer to the transaction after it has been set (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-preendtransaction-method-microsoft-dynamics-retail-pos-contracts-services.md">PreEndTransaction</a></td>
<td>Triggered at the end a transaction, before saving the transaction and printing of receipts (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-prelinediscountamount-method-microsoft-dynamics-retail-pos-contracts-services.md">PreLineDiscountAmount</a></td>
<td>Triggered prior to setting a line discount amount to the transaction. (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-prelinediscountpercent-method-microsoft-dynamics-retail-pos-contracts-services.md">PreLineDiscountPercent</a></td>
<td>Triggered prior to setting a line discount percent to the transaction. (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-prepayment-method-microsoft-dynamics-retail-pos-contracts-services.md">PrePayment</a></td>
<td>Triggered prior to a payment. (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-prepriceoverride-method-microsoft-dynamics-retail-pos-contracts-services.md">PrePriceOverride</a></td>
<td>Triggered prior to overriding the price of a sale line item at the transaction. (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-preprocessoperation-method-microsoft-dynamics-retail-pos-contracts-services.md">PreProcessOperation</a></td>
<td>Before the operation is processed this trigger is called. (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-prereturnitem-method-microsoft-dynamics-retail-pos-contracts-services.md">PreReturnItem</a></td>
<td>Triggered prior to returning a sale line item to the transaction. (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-prereturntransaction-method-microsoft-dynamics-retail-pos-contracts-services.md">PreReturnTransaction</a></td>
<td>Triggered prior to returning. (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-presale-method-microsoft-dynamics-retail-pos-contracts-services.md">PreSale</a></td>
<td>Triggered prior to adding a sale line item to the transaction. (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-presetqty-method-microsoft-dynamics-retail-pos-contracts-services.md">PreSetQty</a></td>
<td>Triggered prior to setting the quantity of a sale line item at the transaction. (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-pretotaldiscountamount-method-microsoft-dynamics-retail-pos-contracts-services.md">PreTotalDiscountAmount</a></td>
<td>Triggered prior to setting a total discount amount to the transaction. (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-pretotaldiscountpercent-method-microsoft-dynamics-retail-pos-contracts-services.md">PreTotalDiscountPercent</a></td>
<td>Triggered prior to setting a total discount percent to the transaction. (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-prevoiditem-method-microsoft-dynamics-retail-pos-contracts-services.md">PreVoidItem</a></td>
<td>Triggered prior to voiding a sale line item at the transaction. (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-prevoidpayment-method-microsoft-dynamics-retail-pos-contracts-services.md">PreVoidPayment</a></td>
<td>Triggered before voiding of a payment. (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-prevoidtransaction-method-microsoft-dynamics-retail-pos-contracts-services.md">PreVoidTransaction</a></td>
<td>Triggered prior to voiding a transaction. (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-printbankdrop-method-microsoft-dynamics-retail-pos-contracts-services.md">PrintBankDrop</a></td>
<td>Print Bank drop Receipt (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-printfloatentry-method-microsoft-dynamics-retail-pos-contracts-services.md">PrintFloatEntry</a></td>
<td>Print Float Entry Receipt (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-printinvoice-method-microsoft-dynamics-retail-pos-contracts-services.md">PrintInvoice</a></td>
<td>Print invoice receipt. (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv2-printloyaltycardbalance-method-microsoft-dynamics-retail-pos-contracts-services.md">PrintLoyaltyCardBalance</a></td>
<td>Prints the loyalty card balance. (Inherited from <a href="ifiscalprinterv2-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV2</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinter-printreceipt-method-microsoft-dynamics-retail-pos-contracts-services.md">PrintReceipt</a></td>
<td>Overloaded.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-printremovetender-method-microsoft-dynamics-retail-pos-contracts-services.md">PrintRemoveTender</a></td>
<td>Print Tender Removal (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-printsafedrop-method-microsoft-dynamics-retail-pos-contracts-services.md">PrintSafeDrop</a></td>
<td>Print safe drop Receipt (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-printslip-method-microsoft-dynamics-retail-pos-contracts-services.md">PrintSlip</a></td>
<td>Prints a slip containing the text in the textToPrint parameter (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-printstartingamount-method-microsoft-dynamics-retail-pos-contracts-services.md">PrintStartingAmount</a></td>
<td>Print Starting Amount Declaration Receipt (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-printxreport-method-microsoft-dynamics-retail-pos-contracts-services.md">PrintXReport</a></td>
<td>Print Report for currently opend batch (X-Report) (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-printzreport-method-microsoft-dynamics-retail-pos-contracts-services.md">PrintZReport</a></td>
<td>Print recently closed batch report (Z-Report) (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-processcardpayment-method-microsoft-dynamics-retail-pos-contracts-services.md">ProcessCardPayment</a></td>
<td>Processes the card payment for the EFT provider. (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv2-prohibitprintingreceiptonnonfiscalprinters-method-microsoft-dynamics-retail-pos-contracts-services.md">ProhibitPrintingReceiptOnNonFiscalPrinters</a></td>
<td>Determines whether the fiscal printer prohibits printing receipt on non fiscal printers. (Inherited from <a href="ifiscalprinterv2-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV2</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv2-savetransaction-method-microsoft-dynamics-retail-pos-contracts-services.md">SaveTransaction</a></td>
<td>Triggered during save of a transaction to database. (Inherited from <a href="ifiscalprinterv2-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV2</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv1-showprintpreview-method-microsoft-dynamics-retail-pos-contracts-services.md">ShowPrintPreview</a></td>
<td>Returns true if print preview ids shown. (Inherited from <a href="ifiscalprinterv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV1</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ifiscalprinterv2-supportprintingreceiptinnonfiscalmode-method-microsoft-dynamics-retail-pos-contracts-services.md">SupportPrintingReceiptInNonFiscalMode</a></td>
<td>Determines whether the fiscal printer supports printing receipt in non fiscal mode. (Inherited from <a href="ifiscalprinterv2-interface-microsoft-dynamics-retail-pos-contracts-services.md">IFiscalPrinterV2</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="iperipheralv1-unload-method-microsoft-dynamics-retail-pos-contracts-services.md">Unload</a></td>
<td>Unloads the device. (Inherited from <a href="iperipheralv1-interface-microsoft-dynamics-retail-pos-contracts-services.md">IPeripheralV1</a>.)</td>
</tr>
</tbody>
</table>


Top

## See Also

#### Reference

[IFiscalPrinter Interface](ifiscalprinter-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

