---
title: Standard Document Services
TOCTitle: Standard Document Services
ms:assetid: b69ffe36-7920-493d-b8f0-8e16f981d433
ms:mtpsurl: https://technet.microsoft.com/library/Aa859008(v=AX.60)
ms:contentKeyID: 35249826
author: tonyafehr
ms.date: 04/13/2015
mtps_version: v=AX.60
---

# Standard Document Services 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Microsoft Dynamics AX 2012 contains many standard document services. Each service supports a particular business process. You can customize these standard documents or create custom documents that suit your individual business processes.

## Document Services that are included with AX 2012

In many cases, standard document services use the same data that is presented on the corresponding form. For example, you can programmatically access data for customer records by using the CustCustomerService service and work with the same data in the **Customer** form. (Click **Accounts Receivable** \> **Customers** \> **All customers**.)

Each document is represented by a class and a query in AX 2012. The name of a document class is preceded by Axd. For example, AxdSalesOrder is the name of the document and also the name of the document class and the related query in the AOT. You will often see the terms "document" and "Axd document" and "document class" used interchangeably.

The following table lists the document services that are included with AX 2012. The version number specifies in which version of Microsoft Dynamics AX the document originally shipped. The service class name is the name displayed in the **Select service operations** form and appears in the **Services** node of the Application Object Tree (AOT). For more information about the **Select service operations** form, see [Customize service contracts](customize-service-contracts.md). In most cases, the corresponding query has the same name as the document. You can click the service name to read more information, if it is available.

You can generate a schema for each document by creating an enhanced inbound integration port and specifying the service operation. For more information, see the section “Viewing schemas” in [Customize service contracts](customize-service-contracts.md). You can generate sample XML for a particular schema when you use Visual Studio to view the schema.

<table style="width:100%;">
<colgroup>
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Service Name</p></th>
<th><p>Document class name</p></th>
<th><p>Service class name</p></th>
<th><p>Version</p></th>
<th><p>Description</p></th>
<th><p>Supported service operations (Create, Read, Update, Delete, Find, findKeys, getKeys, getChangedKeys)</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Advance shipping notice</p></td>
<td><p>AxdASN</p></td>
<td><p>InventASNService</p></td>
<td><p>4.0</p></td>
<td><p>Sent to the customer when the sales order packing-slip updated.</p></td>
<td><p>R</p></td>
</tr>
<tr class="even">
<td><p>Exchange rates</p></td>
<td><p>AxdExchangeRates</p>
<p>AxdSendExchangeRates</p></td>
<td><p>LedgerExchangeRatesService</p></td>
<td><p>4.0</p></td>
<td><p>Enables you to send your exchange rates to another subsidiary.</p></td>
<td><p>CR</p></td>
</tr>
<tr class="odd">
<td><p>Free-text invoice</p></td>
<td><p>AxdFreeTextInvoice</p></td>
<td><p>CustFreeTextInvoiceService</p></td>
<td><p>4.0</p></td>
<td><p>Creates a sales order in the application. This document has significantly fewer restrictions on input data than the Sales Order document.</p></td>
<td><p>C</p></td>
</tr>
<tr class="even">
<td><p>Inventory counting journal document</p></td>
<td><p>AxdCountingJournal</p></td>
<td><p>InventCountingJournalService</p></td>
<td><p>4.0</p></td>
<td><p>Updates inventory amounts and balances with inventory information from a third-party warehouse system.</p></td>
<td><p>C</p></td>
</tr>
<tr class="odd">
<td><p>Inventory on hand</p></td>
<td><p>AxdInventoryOnHand</p></td>
<td><p>InventInventoryOnHandService</p></td>
<td><p>4.0</p></td>
<td><p>Enables external users to receive up-to-date information about on-hand inventory amounts.</p></td>
<td><p>R</p></td>
</tr>
<tr class="even">
<td><p>Inventory profit and loss journal</p></td>
<td><p>AxdProfitLossJournal</p></td>
<td><p>InventProfitLossJournalService</p></td>
<td><p>4.0</p></td>
<td><p>Creates an inventory profit and loss record that is based on information from a third-party warehouse management system.</p></td>
<td><p>C</p></td>
</tr>
<tr class="odd">
<td><p>Inventory transactions</p></td>
<td><p>AxdInventoryTransactions</p></td>
<td><p>InventInventoryTransactionsService</p></td>
<td><p>4.0</p></td>
<td><p>Describes the inventory transactions document.</p></td>
<td><p>R</p></td>
</tr>
<tr class="even">
<td><p>Inventory transfer journal</p></td>
<td><p>AxdTransferJournal</p></td>
<td><p>InventTransferJournalService</p></td>
<td><p>4.0</p></td>
<td><p>Updates the inventory warehouse data from a third-party warehouse management system.</p></td>
<td><p>C</p></td>
</tr>
<tr class="odd">
<td><p>Packing slip</p></td>
<td><p>AxdSalesPackingSlip</p></td>
<td><p>SalesSalesPackingSlipService</p></td>
<td><p>4.0</p></td>
<td><p>Creates a packing slip record. The packing slip record is based on the data from a third-party warehouse management system.</p></td>
<td><p>C</p></td>
</tr>
<tr class="even">
<td><p>Picking list</p></td>
<td><p>AxdPickingList</p></td>
<td><p>InventPickingListService</p></td>
<td><p>4.0</p></td>
<td><p>Sends a picking list to a third-party warehouse management system.</p></td>
<td><p>R</p></td>
</tr>
<tr class="odd">
<td><p>Price discount agreement journal</p></td>
<td><p>AxdPriceDiscountJournal</p></td>
<td><p>PricePriceDiscJournalService</p></td>
<td><p>4.0</p></td>
<td><p>Describes the price discount agreement document.</p></td>
<td><p>C</p></td>
</tr>
<tr class="even">
<td><p>Price list</p></td>
<td><p>AxdPriceList</p></td>
<td><p>PricePriceListService</p></td>
<td><p>4.0</p></td>
<td><p>Sends a compiled price list to a customer. The price list is based on the trade agreements and discounts for the specific customer.</p></td>
<td><p>R</p></td>
</tr>
<tr class="odd">
<td><p>Purchase invoice</p></td>
<td><p>AxdPurchaseInvoice</p></td>
<td><p>LedgerPurchaseInvoiceService</p></td>
<td><p>4.0</p></td>
<td><p>Creates a purchase invoice that is based on the associated purchase order.</p></td>
<td><p>C</p></td>
</tr>
<tr class="even">
<td><p>Purchase requisition</p></td>
<td><p>AxdPurchaseRequisition</p></td>
<td><p>PurchPurchReqService</p></td>
<td><p>4.0</p></td>
<td><p>Sends a purchase requisition to a vendor.</p></td>
<td><p>R</p></td>
</tr>
<tr class="odd">
<td><p>Sales invoice</p></td>
<td><p>AxdSalesInvoice</p></td>
<td><p>SalesSalesInvoiceService</p></td>
<td><p>4.0</p></td>
<td><p>Sends an invoice to a customer. The invoice is based on the sales order data of the customer.</p></td>
<td><p>R</p></td>
</tr>
<tr class="even">
<td><p><a href="sales-order-document-service.md">Sales order</a></p></td>
<td><p>AxdSalesOrder</p></td>
<td><p>SalesSalesOrderService</p></td>
<td><p>4.0</p></td>
<td><p>Creates a new sales order record.</p></td>
<td><p>CRUD</p></td>
</tr>
<tr class="odd">
<td><p>Address</p></td>
<td><p>AxdAddress</p></td>
<td><p>DirAddressService</p></td>
<td><p>4.0 SP2</p></td>
<td><p>Enables external systems to read, update, create, and delete alternative addresses.</p></td>
<td><p>CRUD</p></td>
</tr>
<tr class="even">
<td><p>Contact person</p></td>
<td><p>AxdContactPersons</p></td>
<td><p>DirContactPersonsService</p></td>
<td><p>4.0 SP2</p></td>
<td><p>Enables external system to read, create, update, and delete contact persons.</p></td>
<td><p>CRUD</p></td>
</tr>
<tr class="odd">
<td><p>Customer</p></td>
<td><p>AxdCustomer</p></td>
<td><p>CustCustomerService</p></td>
<td><p>4.0 SP2</p></td>
<td><p>Enables external systems to read, create, update, and delete customers.</p></td>
<td><p>CRUD</p></td>
</tr>
<tr class="even">
<td><p>Customer group</p></td>
<td><p>AxdCustomerGroups</p></td>
<td><p>CustCustomerGroupsService</p></td>
<td><p>4.0 SP2</p></td>
<td><p>Enables external systems to read, create, update, and delete customer groups.</p></td>
<td><p>R</p></td>
</tr>
<tr class="odd">
<td><p>Item</p></td>
<td><p>AxdItem</p></td>
<td><p>InventItemService</p></td>
<td><p>4.0 SP2</p></td>
<td><p>Enables a two-way collaboration of the item master for the objective of synchronization in a dgusiness-to-business relation.</p></td>
<td><p>CR</p></td>
</tr>
<tr class="even">
<td><p>Item dimension combination</p></td>
<td><p>AxdInventDimCombination</p></td>
<td><p>InventInventDimCombinationService</p></td>
<td><p>4.0 SP2</p></td>
<td><p>Enables external systems to read information about combinations of item dimensions, for example, color and size.</p></td>
<td><p>R</p></td>
</tr>
<tr class="odd">
<td><p>Payment terms</p></td>
<td><p>AxdPaymentTerms</p></td>
<td><p>PaymPaymentTermsService</p></td>
<td><p>4.0 SP2</p></td>
<td><p>Delivers a list of payment terms.</p></td>
<td><p>R</p></td>
</tr>
<tr class="even">
<td><p>Product groups</p></td>
<td><p>AxdInventItemGroup</p></td>
<td><p>InventInventItemGroupService</p></td>
<td><p>4.0 SP2</p></td>
<td><p>Enables external systems to read information about product groups.</p></td>
<td><p>R</p></td>
</tr>
<tr class="odd">
<td><p>Shipping methods</p></td>
<td><p>AxdDeliveryModes</p></td>
<td><p>InventDeliveryModesService</p></td>
<td><p>4.0 SP2</p></td>
<td><p>Enables external systems to read information about shipping methods.</p></td>
<td><p>R</p></td>
</tr>
<tr class="even">
<td><p>Warehouse</p></td>
<td><p>AxdInventLocation</p></td>
<td><p>InventInventLocationService</p></td>
<td><p>4.0 SP2</p></td>
<td><p>Enables external systems to receive information about a warehouse.</p></td>
<td><p>R</p></td>
</tr>
<tr class="odd">
<td><p>Bill of materials (BOM)</p></td>
<td><p>AxdBillsOfMaterials</p></td>
<td><p>BomBillsOfMaterialsService</p></td>
<td><p>5.0</p></td>
<td><p>Enables synchronization of a bill of materials with external systems, for example, when production is outsourced to a subcontractor.</p></td>
<td><p>CR</p></td>
</tr>
<tr class="even">
<td><p>Cash discount</p></td>
<td><p>AxdCashDisc</p></td>
<td><p>LedgerCashDiscService</p></td>
<td><p>5.0</p></td>
<td><p>Delivers a list of cash discounts available to a specific user.</p></td>
<td><p>R</p></td>
</tr>
<tr class="odd">
<td><p>Credit card</p></td>
<td><p>AxdTrvPBSMaindata</p></td>
<td><p>TrvTrvPBSMaindataService</p></td>
<td><p>5.0</p></td>
<td><p>Enables the import of corporate credit card transactions.</p></td>
<td><p>C</p></td>
</tr>
<tr class="even">
<td><p>Customer Payment Journal</p></td>
<td><p>AxdCustPaymJournal</p></td>
<td><p>LedgerCustPaymJournalService</p></td>
<td><p>5.0</p></td>
<td><p>Enables creating customer payment records based on a customer invoice.</p></td>
<td><p>C</p></td>
</tr>
<tr class="odd">
<td><p>Expense report</p></td>
<td><p>AxdExpense</p></td>
<td><p>TrvExpenseService</p></td>
<td><p>5.0</p></td>
<td><p>Enables the entry and submission of expense reports.</p></td>
<td><p>CR</p></td>
</tr>
<tr class="even">
<td><p>Fixed asset</p></td>
<td><p>AxdFixedAsset</p></td>
<td><p>AssetFixedAssetService</p></td>
<td><p>5.0</p></td>
<td><p>Delivers a list of assets, and enables creating new fixed asset records.</p></td>
<td><p>CRU</p></td>
</tr>
<tr class="odd">
<td><p>Fixed asset condition</p></td>
<td><p>AxdAssetCondition</p></td>
<td><p>AssetAssetConditionService</p></td>
<td><p>5.0</p></td>
<td><p>Delivers a list of the asset conditions. Fixed asset conditions describe the physical status of a fixed asset, such as good, new, refurbished, improved, or used.</p></td>
<td><p>R</p></td>
</tr>
<tr class="even">
<td><p>Fixed asset group</p></td>
<td><p>AxdAssetGroup</p></td>
<td><p>AssetAssetGroupService</p></td>
<td><p>5.0</p></td>
<td><p>Delivers a list of the asset groups.</p></td>
<td><p>R</p></td>
</tr>
<tr class="odd">
<td><p>Fixed asset location</p></td>
<td><p>AxdAssetLocation</p></td>
<td><p>AssetAssetLocationService</p></td>
<td><p>5.0</p></td>
<td><p>Delivers a list of the asset locations. Locations describe where a fixed asset resides and may include an address.</p></td>
<td><p>R</p></td>
</tr>
<tr class="even">
<td><p>Fixed asset major type</p></td>
<td><p>AxdAssetMajorType</p></td>
<td><p>AssetAssetMajorTypeService</p></td>
<td><p>5.0</p></td>
<td><p>Delivers a list of the asset major types. Fixed asset major types are high-level asset groupings, used for reporting purposes only.</p></td>
<td><p>R</p></td>
</tr>
<tr class="odd">
<td><p>Ledger journal</p></td>
<td><p>AxdLedgerGeneralJournal</p></td>
<td><p>LedgerGeneralJournalService</p></td>
<td><p>5.0</p></td>
<td><p>Delivers a list of general journals, and enables creating new general journals with ledger account types supporting multicurrency and intercompany accounts.</p></td>
<td><p>CR</p></td>
</tr>
<tr class="even">
<td><p>Product picking list</p></td>
<td><p>AxdProdPickingList</p></td>
<td><p>ProdProdPickingListService</p></td>
<td><p>5.0</p></td>
<td><p>Creates a production picking list journal. Enables a subcontractor to report consumption of items.</p></td>
<td><p>C</p></td>
</tr>
<tr class="odd">
<td><p>Project hour journal</p></td>
<td><p>AxdProjectHourJournal</p></td>
<td><p>ProjProjectHourJournalService</p></td>
<td><p>5.0</p></td>
<td><p>Enables external systems to create project hour journals.</p></td>
<td><p>C</p></td>
</tr>
<tr class="even">
<td><p>Project invoice</p></td>
<td><p>AxdProjInvoice</p></td>
<td><p>ProdProjEInvoiceService</p></td>
<td><p>5.0</p></td>
<td><p>Project invoice for Danish e-invoice. Creates an electronic invoice for the Danish tax authorities.</p></td>
<td><p>R</p></td>
</tr>
<tr class="odd">
<td><p>Return order</p></td>
<td><p>AxdReturnOrderIn</p></td>
<td><p>ReturnReturnOrderInService</p></td>
<td><p>5.0</p></td>
<td><p>Enables the entry of customer return orders.</p></td>
<td><p>CUD</p></td>
</tr>
<tr class="even">
<td><p>Return order acknowledgment</p></td>
<td><p>AxdReturnOrderOut</p></td>
<td><p>ReturnReturnOrderOutService</p></td>
<td><p>5.0</p></td>
<td><p>Enables the sending of a return order acknowledgement to the customer.</p></td>
<td><p>R</p></td>
</tr>
<tr class="odd">
<td><p>Route card</p></td>
<td><p>AxdRouteCard</p></td>
<td><p>ProdRouteCardService</p></td>
<td><p>5.0</p></td>
<td><p>Creates a production route card journal. Enables a subcontractor to report progress (hours spent, good quantity, error quantity, percent complete).</p></td>
<td><p>C</p></td>
</tr>
<tr class="even">
<td><p>Sales e-invoice</p></td>
<td><p>AxdSalesInvoice_Einvoice</p></td>
<td><p>SalesSalesEInvoiceService</p></td>
<td><p>5.0</p></td>
<td><p>Sales invoice for Danish e-invoice. Creates an electronic invoice for the Danish tax authorities.</p></td>
<td><p>R</p></td>
</tr>
<tr class="odd">
<td><p>Service agreement</p></td>
<td><p>AxdServiceAgreement</p></td>
<td><p>SMAServiceAgreementService</p></td>
<td><p>5.0</p></td>
<td><p>Enables the exchange of electronic service agreements including the service agreement header and lines.</p></td>
<td><p>R</p></td>
</tr>
<tr class="even">
<td><p>Service order</p></td>
<td><p>AxdServiceOrder</p></td>
<td><p>SMAServiceOrderService</p></td>
<td><p>5.0</p></td>
<td><p>Enable the exchange of electronic service orders including the service order header and lines.</p></td>
<td><p>CRUD</p></td>
</tr>
<tr class="odd">
<td><p>Vendor</p></td>
<td><p>AxdVendor</p></td>
<td><p>VendVendTableService</p></td>
<td><p>5.0</p></td>
<td><p>Enables synchronization of vendor data with external systems.</p></td>
<td><p>CRUD</p></td>
</tr>
<tr class="even">
<td><p>Vendor group</p></td>
<td><p>AxdVendorGroup</p></td>
<td><p>VendVendGroupService</p></td>
<td><p>5.0</p></td>
<td><p>Enables synchronization of vendor groups with external systems.</p></td>
<td><p>CRUD</p></td>
</tr>
<tr class="odd">
<td><p>Vendor payment</p></td>
<td><p>AxdVendorPayment</p></td>
<td><p>LedgerVendorPaymentService</p></td>
<td><p>5.0</p></td>
<td><p>Delivers payment information for a specific vendor.</p></td>
<td><p>R</p></td>
</tr>
<tr class="even">
<td><p>Budget transaction</p></td>
<td><p>AxdBudgetTransaction</p></td>
<td><p>BudgetTransactionService</p></td>
<td><p>AX 2012</p></td>
<td><p>Allows end user to create, read, update, and delete budget register entries</p></td>
<td><p>CRUDF, FK, GCK, GK</p></td>
</tr>
<tr class="odd">
<td><p>Catalog import</p></td>
<td><p>AxdCatImp</p></td>
<td><p>CatImpService</p></td>
<td><p>AX 2012</p></td>
<td><p>Allows end user (Vendor, Purchasing agent. Or Purchasing manager) to maintain the imported catalog of the vendor in Microsoft Dynamics AX</p></td>
<td><p>C, GCK, GK</p></td>
</tr>
<tr class="even">
<td><p>Customer electronic payment</p></td>
<td><p>AxdCustPayments</p></td>
<td><p>CustPaymentsService</p></td>
<td><p>AX 2012</p></td>
<td><p>Customer electronic payment service</p></td>
<td><p>FR</p></td>
</tr>
<tr class="odd">
<td><p>Document handling</p></td>
<td><p>DocumentHandlingService</p>
<div class="alert">

> [!NOTE]
> <P>The corresponding query is called <STRONG>DocumentHandling</STRONG>.</P>


</div></td>
<td><p>DocumentHandlingService</p></td>
<td><p>AX 2012</p></td>
<td><p>Allows users to submit unattached documents and push them into workflow for association with records.</p></td>
<td><p>C</p></td>
</tr>
<tr class="even">
<td><p>Product master dimension values</p></td>
<td><p>AxdEcoResProductMasterDimValue</p></td>
<td><p>EcoResProductMasterDimValueService</p></td>
<td><p>AX 2012</p></td>
<td><p>Allows read and write of product dimension values for a product master.</p></td>
<td><p>CRF, FK, GCK, GK</p></td>
</tr>
<tr class="odd">
<td><p>Product service</p></td>
<td><p>AxdEcoResProduct</p></td>
<td><p>EcoResProductService</p></td>
<td><p>AX 2012</p></td>
<td><p>Enables external systems to read or write products into shared product repository.</p></td>
<td><p>CRF, FK, GCK, GK</p></td>
</tr>
<tr class="even">
<td><p>Meter reading service</p></td>
<td><p>AxdEMSMeterReadingFlow</p></td>
<td><p>EMSMeterReadingFlowService</p></td>
<td><p>AX 2012</p></td>
<td><p>Allows external systems to record meter readings in the environmental sustainability dashboard.</p></td>
<td><p>C, GCK, GK</p></td>
</tr>
<tr class="odd">
<td><p>Substance flow</p></td>
<td><p>AxdEMSSubstanceFlow</p></td>
<td><p>EMSSubstanceFlowService</p></td>
<td><p>AX 2012</p></td>
<td><p>Allows external systems to record substance flow transactions in the environmental sustainability dashboard.</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>EU sales list reporting</p></td>
<td><p>AxdEUSLReporting</p></td>
<td><p>EUSLReportingService</p></td>
<td><p>AX 2012</p></td>
<td><p>Enables generation of EU sales list files which are used for reporting to government authorities.</p></td>
<td><p>R, F, GCK, GK</p></td>
</tr>
<tr class="odd">
<td><p>Warehouse item</p></td>
<td><p>AxdInventItemLocation</p></td>
<td><p>InventInventItemLocationService</p></td>
<td><p>AX 2012</p></td>
<td><p>Enables external systems to create and retrieve warehouse items.</p></td>
<td><p>CRF, FK, GCK, GK</p></td>
</tr>
<tr class="even">
<td><p>Barcode service</p></td>
<td><p>AxdInventItemBarcode</p></td>
<td><p>InventItemBarcodeService</p></td>
<td><p>AX 2012</p></td>
<td><p>Enables external systems to retrieve barcode information for a released product.</p></td>
<td><p>RF, FK, GCK, GK</p></td>
</tr>
<tr class="odd">
<td><p>Create inventory transfer order</p></td>
<td><p>AxdTransferOrderCreate</p></td>
<td><p>InventTransferOrderCreateService</p></td>
<td><p>AX 2012</p></td>
<td><p>Enables external systems to create inventory transfer orders.</p></td>
<td><p>C, GCK, GK</p></td>
</tr>
<tr class="even">
<td><p>Inventory transfer order posting</p></td>
<td><p>AxdTransferOrderPosting</p></td>
<td><p>InventTransferOrderPostingService</p></td>
<td><p>AX 2012</p></td>
<td><p>Enables external systems to post inventory transfer orders.</p></td>
<td><p>C, GCK, GK</p></td>
</tr>
<tr class="odd">
<td><p>Read inventory transfer order</p></td>
<td><p>AxdTransferOrder</p></td>
<td><p>InventTransferOrderService</p></td>
<td><p>AX 2012</p></td>
<td><p>Enables external systems to read inventory transfer orders.</p></td>
<td><p>RF, FK, GCK, GK</p></td>
</tr>
<tr class="even">
<td><p>Request for quote reply</p></td>
<td><p>AxdRFQReply</p></td>
<td><p>PurchPurchRFQReplyService</p></td>
<td><p>AX 2012</p></td>
<td><p>Enables a customer to receive vendor quotes in response to a request for quote.</p></td>
<td><p>UF, GCK, GK</p></td>
</tr>
<tr class="odd">
<td><p>Request for quote send</p></td>
<td><p>AxdRFQSend</p></td>
<td><p>PurchPurchRFQSendService</p></td>
<td><p>AX 2012</p></td>
<td><p>Enables a customer to send requests for quote to vendors.</p></td>
<td><p>RF, FK, GCK, GK</p></td>
</tr>
<tr class="even">
<td><p>Purchaser requisition</p></td>
<td><p>AxdPurchaseRequisition</p></td>
<td><p>PurchReqImportService</p></td>
<td><p>AX 2012</p></td>
<td><p>Enables the creation, retrieval, and cancellation of purchase requisitions.</p></td>
<td><p>Cancel, CRDF, FK, GCK, GK</p></td>
</tr>
<tr class="odd">
<td><p>Request for quote sites</p></td>
<td><p>AxdPurchRFQSites</p></td>
<td><p>PurchRFQSitesService</p></td>
<td><p>AX 2012</p></td>
<td><p>Enables the customer to manage request for quote documents.</p></td>
<td><p>CRUF, FK, GCK, GK</p></td>
</tr>
<tr class="even">
<td><p>Sales quotation journal</p></td>
<td><p>AxdCustomerQuotation</p></td>
<td><p>SalesCustomerQuotationService</p></td>
<td><p>AX 2012</p></td>
<td><p>Enables external systems to read sales quotation journals.</p></td>
<td><p>RF, FK, GCK, GK</p></td>
</tr>
<tr class="odd">
<td><p>Line discount list</p></td>
<td><p>AxdLineDiscount</p></td>
<td><p>SalesLineDiscountService</p></td>
<td><p>AX 2012</p></td>
<td><p>Enables external systems to retrieve line discount lists.</p></td>
<td><p>Find, GCK, GK</p></td>
</tr>
<tr class="even">
<td><p>Multiline discount list</p></td>
<td><p>AxdSalesMultilineDiscount</p></td>
<td><p>SalesMultilineDiscountService</p></td>
<td><p>AX 2012</p></td>
<td><p>Enables external systems to retrieve multiline discount lists.</p></td>
<td><p>F, GCK, GK</p></td>
</tr>
<tr class="odd">
<td><p>Sales confirmation</p></td>
<td><p>AxdSalesConfirmation</p></td>
<td><p>SalesSalesConfirmationService</p></td>
<td><p>AX 2012</p></td>
<td><p>Enables external systems to read sales order confirmations.</p></td>
<td><p>RF, FK, GCK, GK</p></td>
</tr>
<tr class="even">
<td><p>Sales quotation</p></td>
<td><p>AxdSalesQuotation</p></td>
<td><p>SalesSalesQuotationService</p></td>
<td><p>AX 2012</p></td>
<td><p>Enables external systems to read, create, update, and delete sales quotations.</p></td>
<td><p>CRUDF, FK, GCK, GK</p></td>
</tr>
<tr class="odd">
<td><p>Total discount</p></td>
<td><p>AxdSalesTotalDiscount</p></td>
<td><p>SalesTotalDiscountService</p></td>
<td><p>AX 2012</p></td>
<td><p>Enables external systems to retrieve total discount lists.</p></td>
<td><p>F, GCK, GK</p></td>
</tr>
<tr class="even">
<td><p>Expense policy violation</p></td>
<td><p>TrvExpensePolicyViolation</p></td>
<td><p>TrvExpensePolicyViolationService</p></td>
<td><p>AX 2012</p></td>
<td><p>Delivers a list of expense violations for a given expense report.</p></td>
<td><p>Custom service operation TrvExpensePolicyViolationService.getPolicyViolations</p></td>
</tr>
<tr class="odd">
<td><p>Warehouse location load service</p></td>
<td><p>WMSLocationLocationLoadService</p></td>
<td><p>WMSLocationLocationLoadService</p></td>
<td><p>AX 2012</p></td>
<td><p>Enables external systems to view load information (volume, weight) for warehouse locations.</p></td>
<td><p>R</p></td>
</tr>
<tr class="even">
<td><p>Payroll earnings import</p></td>
<td><p>AxdPayrollEarningsImport</p></td>
<td><p>PayrollEarningsImportService</p></td>
<td><p>AX 2012 R2</p></td>
<td><p>Enables import of earnings statements from external systems.</p></td>
<td><p>C</p></td>
</tr>
<tr class="odd">
<td><p>Worker import</p></td>
<td><p>AxdHcmWorkerImport</p></td>
<td><p>HcmWorkerImportService</p></td>
<td><p>AX 2012 R2</p></td>
<td><p>Enables external systems to read, create, and update worker information.</p></td>
<td><p>C, R, U</p></td>
</tr>
<tr class="even">
<td><p>Budget plan</p></td>
<td><p>AxdBudgetPlan</p></td>
<td><p>BudgetPlanService</p></td>
<td><p>AX 2012 R2</p></td>
<td><p>Enables external systems to read, create, update, and delete budget plans.</p></td>
<td><p>C, R, U, D</p></td>
</tr>
<tr class="odd">
<td><p>Bank statement</p></td>
<td><p>AxdBankStmt</p></td>
<td><p>BankStmtService</p></td>
<td><p>AX 2012 R2</p></td>
<td><p>Enables import of bank statements.</p>
<div class="alert">

> [!NOTE]
> <P>You must select the <STRONG>Advanced bank reconciliation</STRONG> option on the <STRONG>Bank account</STRONG> form to import bank statements.</P>


</div></td>
<td><p>C, R, D, F, GK, GCK</p></td>
</tr>
<tr class="even">
<td><p>Warehouse space utilization forecast</p></td>
<td><p>WMSSpaceUtilService</p></td>
<td><p>WMSSpaceUtilService</p></td>
<td><p>AX 2012 R2</p></td>
<td><p>Creates forecast data for a warehouse space utilization report.</p></td>
<td><p>Custom service operation buildForecast</p></td>
</tr>
<tr class="odd">
<td><p>Warehouse workload capacity forecast</p></td>
<td><p>WMSWorkLoadService</p></td>
<td><p>WMSWorkLoadService</p></td>
<td><p>AX 2012 R2</p></td>
<td><p>Creates forecast data for a warehouse work load capacity report.</p></td>
<td><p>Custom service operation buildForecast</p></td>
</tr>
<tr class="even">
<td><p><a href="https://go.microsoft.com/fwlink/?linkid=393441%26clcid=0x409">Advanced Ledger Entry</a></p></td>
<td><p>AxdAdvancedLedgerEntry</p></td>
<td><p>AdvancedLedgerEntryService</p></td>
<td><p>AX 2012 R2</p></td>
<td><p>Imports different types of transactions, for example, payroll transactions, and uses the posting definitions to handle the balancing entries.</p></td>
<td><p>C, R, U, D, F, FK</p></td>
</tr>
<tr class="odd">
<td><p>Customer collections letter for Norway</p></td>
<td><p>AxdCustECollectionLetter_NO</p></td>
<td><p>CustCollectionLetterService_NO</p></td>
<td><p>AX 2012 R2</p></td>
<td><p>Sends collection letters in electronic format to customers that have electronic invoicing enabled. Applies to Norway only.</p></td>
<td><p>R</p></td>
</tr>
<tr class="even">
<td><p>Customer transaction service</p></td>
<td><p>AxdCustomerTransaction</p></td>
<td><p>CustomerTransactionService</p></td>
<td><p>AX 2012 R2</p></td>
<td><p>Retrieves a list of a customer’s open and closed transactions.</p></td>
<td><p>F, FK, R</p></td>
</tr>
<tr class="odd">
<td><p>Routes service</p></td>
<td><p>AxdRoutes</p></td>
<td><p>RoutesService</p></td>
<td><p>AX 2012 R2</p></td>
<td><p>Supports synchronization of a route with external systems.</p></td>
<td><p>C, R, F, FK</p></td>
</tr>
<tr class="even">
<td><p>Vendor invoice</p></td>
<td><p>AxdVendInvoice</p></td>
<td><p>VendInvoiceService</p></td>
<td><p>AX 2012 R2</p></td>
<td><p>Creates a new Vendor invoice.</p>
<div class="alert">

> [!NOTE]
> <P>You must provide the InventTransId value for the desired Purchase Order line on VendInvoiceInfoLine if receiving against Purchase Order.</P>


</div></td>
<td><p>C, R, D, F, FK, GK, GCK</p></td>
</tr>
<tr class="odd">
<td><p>Asset depreciation rate for Japan</p></td>
<td><p>AxdAssetDepRateExpImp_JP</p></td>
<td><p>AssetDepRateExpImp_JPService</p></td>
<td><p>AX 2012 R3</p></td>
<td><p>Supports import and export of depreciation rates in Japan for fixed asset depreciation methods including old straight line, new straight line, old declining balance, and new declining balance by using Excel.</p></td>
<td><p>C, R, D, U</p></td>
</tr>
<tr class="even">
<td><p>Asset depreciation method change for Japan</p></td>
<td><p>AxdAssetUndepBalanceExpImp_JP</p></td>
<td><p>AssetUndepBalanceExpImp_JPService</p></td>
<td><p>AX 2012 R3</p></td>
<td><p>Supportsimport and export of rate depreciation method change for Japan.</p></td>
<td><p>C, R, D, U</p></td>
</tr>
<tr class="odd">
<td><p>Job reporting service</p></td>
<td><p>JmgShopFloorService</p></td>
<td><p>JmgShopFloorServiceClass</p></td>
<td><p>AX 2012 R3</p></td>
<td><p>Creates, updates, and reads data for the shop floor companion app that enables shop floor operators to report on production jobs.</p></td>
<td><p>C, U, R</p></td>
</tr>
<tr class="even">
<td><p>Expense fields visibility configuration</p></td>
<td><p>TrvAdminCustomFieldsService</p></td>
<td><p>TrvAdminCustomFieldsService</p></td>
<td><p>AX 2012 R3</p></td>
<td><p>Returns a list of all the expense report and line fields and how their visibility is configured: read-only, visible, or hidden.</p></td>
<td><p>R</p></td>
</tr>
<tr class="odd">
<td><p>Expense categories</p></td>
<td><p>TrvExpenseCategoryService</p></td>
<td><p>TrvExpenseCategoryService</p></td>
<td><p>AX 2012 R3</p></td>
<td><p>Returns a list of expense categories including their subcategories and information about the category.</p></td>
<td><p>R</p></td>
</tr>
<tr class="even">
<td><p>Expense module configuration settings</p></td>
<td><p>TrvExpenseConfigurationService</p></td>
<td><p>TrvExpenseConfigurationService</p></td>
<td><p>AX 2012 R3</p></td>
<td><p>Returns configuration data for the user’s expense module, including default company, currency, and personnel number.</p></td>
<td><p>R</p></td>
</tr>
<tr class="odd">
<td><p>Expense lines</p></td>
<td><p>TrvExpenseLineCustomService</p></td>
<td><p>TrvExpenseLineCustomService</p></td>
<td><p>AX 2012 R3</p></td>
<td><p>Creates, reads, updates and deletes an expense line that belongs to an expense report.</p></td>
<td><p>C, R, U, D</p></td>
</tr>
<tr class="even">
<td><p>Expense module reference data</p></td>
<td><p>TrvExpenseReferenceDataService</p></td>
<td><p>TrvExpenseReferenceDataService</p></td>
<td><p>AX 2012 R3</p></td>
<td><p>Returns reference data needed by the expense report module like locations, expense purpose, and the like.</p></td>
<td><p>R</p></td>
</tr>
<tr class="odd">
<td><p>Expense report</p></td>
<td><p>TrvExpenseReportCustomService</p></td>
<td><p>TrvExpenseReportCustomService</p></td>
<td><p>AX 2012 R3</p></td>
<td><p>Creates, reads, updates, deletes, submits and recalls an expense report.</p></td>
<td><p>C, R, U, D, submit, recall</p></td>
</tr>
<tr class="even">
<td><p>Guest expense line</p></td>
<td><p>TrvExpGuestService</p></td>
<td><p>TrvExpGuestService</p></td>
<td><p>AX 2012 R3</p></td>
<td><p>Creates, reads, updates and deletes guest records on an expense line.</p></td>
<td><p>C, R, U, D</p></td>
</tr>
<tr class="odd">
<td><p>Expense report receipts</p></td>
<td><p>TrvReceiptService</p></td>
<td><p>TrvReceiptService</p></td>
<td><p>AX 2012 R3</p></td>
<td><p>Creates, updates, reads, deletes, attaches, detaches receipts from an expense report or an expense line.</p></td>
<td><p>C, R, U, D, and others</p></td>
</tr>
<tr class="even">
<td><p>Warehouse Item Hierarchy Change</p></td>
<td><p>WHSChangeItemHierarchyService</p></td>
<td><p>WHSChangeItemHierarchyService</p></td>
<td><p>AX 2012 R3</p></td>
<td><p>Stateless service operation that changes the reservation on an item that already has transactions and inventory.</p></td>
<td><p>Custom service operation changeItemHierarchy</p></td>
</tr>
<tr class="odd">
<td><p>Warehouse Mobile Device Service</p></td>
<td><p>WHSMobileDevicesServiceFacade</p></td>
<td><p>WHSMobileDevicesService</p></td>
<td><p>AX 2012 R3</p></td>
<td><p>Custom service operations that enable the communication between the Warehouse Mobile Device Portal (WMDP) and the AX 2012 server (AOS).</p></td>
<td><p>Custom service operations: getNextFormHandHeld, getServiceUserLanguage, SessionLogFindTransacation, SessionLogUserList, WorkUserDisplaySettings</p></td>
</tr>
<tr class="even">
<td><p>Warehouse Session Log Cleanup Service</p></td>
<td><p>WHSSessionLogCleanupService</p></td>
<td><p>WHSSessionLogCleanupService</p></td>
<td><p>AX 2012 R3</p></td>
<td><p>Stateless service operations for cleaning up the Warehouse worker user session logs.</p></td>
<td><p>Custom service operation doCleanup</p></td>
</tr>
<tr class="odd">
<td><p>Warehouse Shipment ASN Service</p></td>
<td><p>WHSShipmentASNService</p></td>
<td><p>WHSShipmentASNService</p></td>
<td><p>AX 2012 R3</p></td>
<td><p>Document service for import, create, delete or update Advance Shipment Notice (ASN) data.</p></td>
<td><p>C, D, F, FK, GCK, GK, R, U</p></td>
</tr>
</tbody>
</table>


## Excluded field list

The following fields are excluded in all AIF XML documents. These fields are not imported during the inbound action and are not exported during outbound actions.

  - Fields starting with Del\_.

  - Fields marked with status of Not visible.

## Non-Editable Fields

In an inbound message, the XML cannot contain data for fields that are non-editable in the table (the AllowEdit property is set to No). That is, for each non-editable table field, the field element must not be in the inbound XML or the field element must be filtered out in the endpoint action data policy.

## See also

[Document Services Classes](document-services-classes.md)

[AIF Class Naming Conventions](aif-class-naming-conventions.md)

[About Document Service Classes](about-document-service-classes.md)

[About Axd\<Document\> Classes](about-axd-document-classes.md)

  


