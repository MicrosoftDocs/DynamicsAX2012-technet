---
title: 'Virtual company scenarios: Financials'
TOCTitle: 'Virtual company scenarios: Financials'
ms:assetid: 349e484d-710a-486a-b51d-da8d50d553ab
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ619166(v=AX.60)
ms:contentKeyID: 49114587
ms.date: 05/30/2014
mtps_version: v=AX.60
---

# Virtual company scenarios: Financials 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes the table collections that must be set up to support some common virtual company scenarios in the financial modules of Microsoft Dynamics AX. For an overview of the concept of virtual companies, and for step-by-step instructions to create table collections and virtual company accounts, see [Virtual company accounts in Microsoft Dynamics AX](virtual-company-accounts-in-microsoft-dynamics-ax.md).


> [!NOTE]
> <P>The first table in each list is the base table of the table collection. Other tables in the list are referenced by the base table.</P>



## Scenario: Use common reason codes for transaction processing

Reason codes can be applied when a user reverses one of the following transactions:

  - A general journal entry

  - A customer transaction that originates in Accounts receivable, such as a free text invoice or payment

  - A vendor transaction that originates in Accounts payable, such as a journal or vendor invoice

  - A payment in Bank

Create a virtual company account to share reason codes among company accounts. Create the following table collection to include in the virtual company.

**Financial reason codes table collection**

Include the following tables in a table collection to support sharing reason codes among company accounts.

  - ReasonTable

  - ReasonTableRef

## Scenario: Establish common groups that can be used for reporting and analysis

The following groups can be created in Microsoft Dynamics AX:

  - Customer groups

  - Vendor groups

  - Fixed asset groups

  - Bank groups

  - Bank transaction type groups

Create a virtual company to share groups among company accounts. Create the following table collections to include in the virtual company.

**Customer groups table collection**

To support sharing customer groups among company accounts, you must include the following tables in a table collection.

  - CustGroup

  - BankCustPaymIDTable
    

    > [!IMPORTANT]
    > <P>The system validates that the maximum length of number sequences for invoices, collection letters, and interest notes is less than or equal to the maximum length that is specified for the payment ID field. However, this information is validated only in the current company. For other companies where the BankCustPaymIdTable table is shared, make sure that the maximum length will accommodate payment IDs.</P>



  - PaymTerm
    
    When you share this table, you must also share tables that are related to payment terms. For information about which tables to share, see the table collection in this topic.

  - TaxGroupHeading
    
    When you share this table, you must also share tables that are related to sales tax groups. For information about which tables to share, see the sales tax groups table collection in this topic.

**Vendor groups table collection**

To support sharing vendor groups among company accounts, you must include the following tables in a table collection.

  - VendGroup

  - PaymTerm
    
    When you share this table, you must also share tables that are related to payment terms. For information about which tables to share, see the table collection in this topic.

  - TaxGroupHeading
    
    When you share this table, you must also share tables that are related to sales tax groups. For information about which tables to share, see the table collection in this topic.

**Fixed asset groups table collection**

To support sharing fixed asset groups and their related asset depreciation books among company accounts, you must include the following tables in a table collection.

  - AssetGroup

  - AssetBookGroupSetup

  - AssetBookTable
    
    When you share this table, you must also share tables that are related to fixed asset value models. For information about which tables to share, see the table collection in this topic.

  - AssetDepBookTable

  - AssetDepreciationProfile

  - AssetGroupDepBookSetup

  - AssetLocation

  - AssetMajorType

**Bank groups table collection**

To support sharing bank groups among company accounts, you must include the following tables in a table collection.

  - BankGroup

  - BankAccountTable
    
    When you share this table, you must also share tables that are related to bank accounts. For information about which tables to share, see the table collection in this topic.

  - HCMWorkerBankAccount

  - VendTable
    
    When you share this table, you must also share tables that are related to vendors. For information about which tables to share, see [Virtual company scenarios: CRM](virtual-company-scenarios-crm.md).

**Bank transaction groups table collection**

To support sharing bank transaction groups among company accounts, you must include the following tables in a table collection.

  - BankTransactionTypeGroupDetails

  - BankTransactionTypeGroupHeader

  - BankTransType

**Bank accounts table collection**

To support sharing bank accounts among company accounts, you must include the following tables in a table collection.

  - BankAccountTable

  - BankChequeLayout

  - BankGroup

  - LedgerJournalName
    
    When you share this table, you must also share tables that are related to ledger journal names. For information about which tables to share, see the table collection in this topic.

  - MarkupGroup
    
    When you share this table, you must also share tables that are related to charges groups. For information about which tables to share, see [Virtual company scenarios: Supply chain management (SCM)](virtual-company-scenarios-supply-chain-management-scm.md).

## Scenario: Use common payment elements for transaction processing and payment management

Payment elements such as payment terms, cash discounts, payment schedule, and payment days are used to determine when payments must be made to vendors or received from customers. Payment mode is used on payment transactions.

To minimize setup and maintenance, create a virtual company to share these payment elements among company accounts. Create the following table collections to include in the virtual company.

**Vendor methods of payment table collection**

To support sharing vendor methods of payment among company accounts, you must include the following tables in a table collection.

  - VendPaymModeTable

  - BankTransType

  - BankVendPaymModeBankAccounts

  - LedgerJournalName
    
    When you share this table, you must also share tables that are related to ledger journal names. For information about which tables to share, see the table collection in this topic.
    

    > [!NOTE]
    > <P>When you share the LedgerJournalName table, the number sequence for vouchers is also shared. If you do not use the functionality to automatically create promissory notes and bills of exchange, you can omit the LedgerJournalName table from the table collection to prevent sharing this number sequence. If you omit the LedgerJournalName table from the table collection, you must leave the journal name blank on methods of payment.</P>



For this table collection, the related parameters table is LedgerParameters. We recommend that you do not share the LedgerParameters table through virtual companies. Because we recommend that you do not share this table, make sure that the following settings are the same in all companies that share the VendPaymModeTable table. Alternatively, verify that the expected setting is used in each company, and correct it if necessary.

  - **Clearing account for issued checks** - When you select the **Postdated check clearing posting** option for a vendor method of payment, the default bridging account comes from the ledger parameters for the current company.

**Customer methods of payment table collection**

To support sharing customer methods of payment among company accounts, you must include the following tables in a table collection.

  - CustPaymModeTable

  - BankCustPaymIDTable

  - BankTransType

  - LedgerJournalName
    
    When you share this table, you must also share tables that are related to ledger journal names. For information about which tables to share, see the table collection in this topic.
    

    > [!NOTE]
    > <P>When you share the LedgerJournalName table, the number sequence for vouchers is also shared. If you do not use the functionality to automatically create promissory notes and bills of exchange, you can omit the LedgerJournalName table from the table collection to prevent sharing this number sequence. If you omit the LedgerJournalName table from the table collection, you must leave the journal name blank on methods of payment.</P>



For this table collection, the related parameters table is LedgerParameters. We recommend that you do not share the LedgerParameters table through virtual companies. Because we recommend that you do not share this table, make sure that the following settings are the same in all companies that share the CustPaymModeTable table. Alternatively, verify that the expected setting is used in each company, and correct it if necessary.

  - **Clearing account for received checks** - When you select the **Postdated check clearing posting** option for a customer method of payment, the default bridging account comes from the ledger parameters for the current company.

**Payment terms table collection**

To support sharing payment terms among company accounts, you must include the following tables in a table collection.

  - PaymTerm

  - PaymDay
    
    When you share this table, you must also share tables that are related to payment days. For information about which tables to share, see the table collection in this topic.

  - PaymSched
    
    When you share this table, you must also share tables that are related to payment schedules. For information about which tables to share, see the table collection in this topic.

**Payment schedules table collection**

To support sharing payment schedules among company accounts, you must include the following tables in a table collection.

  - PaymSched

  - PaymSchedLine

**Payment days table collection**

To support sharing payment days among company accounts, you must include the following tables in a table collection.

  - PaymDay

  - PaymDayLine

**Payment services table collection**

To support sharing payment services among company accounts, you must include the following tables in a table collection.


> [!NOTE]
> <P>This table collection is supported only in Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3.</P>



  - CreditCardProcessors

  - CreditCardAccountSetup

  - CreditCardTypeCurrency

  - CreditCardTypeSetup

  - LedgerJournalName
    
    When you share this table, you must also share tables that are related to ledger journal names. For information about which tables to share, see the table collection in this topic.

**Cash discounts table collection**

To support sharing cash discounts among company accounts, you must include the following tables in a table collection.

  - CashDisc

  - LanguageTxt

## Scenario: Establish common profiles for transaction posting

Posting profiles are used for all journals and source documents. To minimize setup and maintenance, create a virtual company to share profiles for transaction posting among company accounts. Create the following table collections to include in the virtual company.

**Customer posting profiles table collection**

To support sharing customer posting profiles among company accounts, you must include the following tables in a table collection.

  - CustLedger

  - ClearingLedgerDimension

  - CustCollectionLetterTable

  - CustGroup
    
    When you share this table, you must also share tables that are related to customer groups. For information about which tables to share, see the table collection in this topic.

  - CustLedgerAccounts

  - CustLedgerAccountsCustInterest

  - CustTable
    
    When you share this table, you must also share tables that are related to customers. For information about which tables to share, see [Virtual company scenarios: CRM](virtual-company-scenarios-crm.md).

  - DepositLedgerDimension

  - DimensionHierarchy\_RU

  - EndorseLedgerDimension

  - ExportSalesLedgerDimension

  - FineLedgerDimension\_BR

  - InterestLedgerDimension\_BR

  - LiabilitiesForDiscountLedgerDimension

  - SummaryLedgerDimension

  - TaxTransferLedgerDimension\_BR

  - VATPrepaymentsLedgerDimension

  - WriteOffLedgerDimension

**Vendor posting profiles table collection**

To support sharing vendor posting profiles among company accounts, you must include the following tables in a table collection.

  - VendLedger

  - ClearingLedgerDimension

  - DimensionHierarchy\_RU

  - FineLedgerDimension\_BR

  - InterestLedgerDimension\_BR

  - PurchasingLedgerDimension

  - PurchasingOffsetLedgerDimension

  - SummaryLedgerDimension

  - TaxTransferLedgerDimension\_BR

  - VATPrepaymentsLedgerDimension

  - VendGroup
    
    When you share this table, you must also share tables that are related to vendor groups. For information about which tables to share, see the table collection in this topic.

  - VendLedgerAccounts

  - VendTable
    
    When you share this table, you must also share tables that are related to vendors. For information about which tables to share, see [Virtual company scenarios: CRM](virtual-company-scenarios-crm.md).

**Fixed asset posting profiles table collection**

To support sharing fixed asset posting profiles among company accounts, you must include the AssetLedger table in a table collection.

**Bank document posting profiles table collection**

To support sharing bank document posting profiles among company accounts, you must include the BankDocumentPosting table in a table collection.

**Ledger journal names table collection**

To support sharing ledger journal names among company accounts, you must include the following tables in a table collection.

  - LedgerJournalName
    

    > [!NOTE]
    > <P>When you share the LedgerJournalName table, the number sequence for vouchers is also shared. If you do not use the functionality to automatically create promissory notes and bills of exchange, you can omit the LedgerJournalName table from the table collection to prevent sharing this number sequence. If you omit the LedgerJournalName table from the table collection, you must leave the journal name blank on methods of payment.</P>



  - LedgerJournalControlHeader

  - LedgerJournalControlDetail

For this table collection, the related parameters table is LedgerParameters. We recommend that you do not share the LedgerParameters table through virtual companies. Because we recommend that you do not share this table, make sure that the following settings are the same in all companies that share the LedgerJournalName table. Alternatively, verify that the expected setting is used in each company, and correct it if necessary.

  - **Clearing account for received checks** - When you create a ledger journal name, the default **Amounts include sales tax** option comes from the sales tax parameters in the current company.

  - **Check continuous numbers** - When you assign a voucher series to a ledger journal name, this option from the ledger parameters is used to validate whether the assigned voucher series is set up as a continuous number sequence.

  - Number sequence for temporary voucher numbers - If you select the **Number allocation at posting** option, the system validates that a number sequence is set up for temporary voucher numbers only in the current company.

## Scenario: Establish common parameters for handling transaction data

Parameters are used to define how data generated by transactions is handled. To minimize setup and maintenance, create virtual companies to share parameters among company accounts. Create the following table collections to include in the virtual company.

**Bank parameters table collection**

To support sharing parameters of the Bank module among company accounts, you must include the following tables in a table collection.

  - BankParameters

  - BankTransType

**Fixed assets parameters table collection**

To support sharing parameters of the Fixed assets module among company accounts, you must include the following tables in a table collection.

  - AssetParameters

  - AssetBook

  - AssetBookTable
    
    When you share this table, you must also share tables that are related to fixed asset value models. For information about which tables to share, see the table collection in this topic.

  - AssetDepreciationProfile

  - AssetGroupBookSetup

  - AssetLedger

  - AssetTable

  - InventJournalName

**Tax parameters table collection**

To support sharing tax parameters among company accounts, you must include the following tables in a table collection.

  - TaxParameters

  - TaxGroupHeading
    
    When you share this table, you must also share tables that are related to sales tax groups. For information about which tables to share, see the table collection in this topic.

  - TaxItemGroupHeading
    
    When you share this table, you must also share tables that are related to sales tax groups. For information about which tables to share, see the table collection in this topic.

## Scenario: Establish common aging periods

Aging periods are used to determine and manage customer and vendor payments. To minimize setup and maintenance, create a virtual company to share aging periods among company accounts. Create the following table collection to include in the virtual company.

**Aging period definitions table collection**

To support sharing aging periods among company accounts, you must include the following tables in a table collection.

  - StatRepInterval

  - StatRepIntervalLine

## Scenario: Establish common asset depreciation profiles

When you define a new fixed asset, you can assign a fixed asset group. Value models and depreciation books are assigned to the asset based on the fixed asset group that you select. Create a virtual company to share depreciation profiles among company accounts. Create the following table collections to include in the virtual company.

**Acquisition methods table collection**

To support sharing acquisition methods among company accounts, you must include the AssetAcquisitionMethod table in a table collection.

**Depreciation profiles table collection**

To support sharing the calculation details for depreciation among company accounts, you must include the AssetDepreciationProfile table in a table collection.

**Depreciation schedules table collection**

To support sharing schedules or intervals for a depreciation profile among company accounts, you must include the following tables in a table collection.

  - AssetDepreciationProfile

  - AssetDepreciationProfileSpec

**Value models table collection**

To support sharing depreciation information related to value models among company accounts, you must include the following tables in a table collection.

  - AssetBookTable

  - AssetBookTableDerived

  - AssetBookTableShiftDepreciation\_IN

  - AssetBookTaxCoefficient

  - AssetDepBookTable

  - AssetDepBookTableDerived

  - AssetDepreciationProfile

**Depreciation books table collection**

To support sharing depreciation books among company accounts, you must include the following tables in a table collection.

  - AssetDepBookTable

  - AssetDepreciationProfile

**Asset conditions table collection**

To support sharing asset conditions among company accounts, you must include the AssetCondition table in a table collection.

**Property group codes table collection**

To support sharing property group codes for fixed assets among company accounts, you must include the AssetPropertyGroup table in a table collection.

**Asset types table collection**

To support sharing asset types among company accounts, you must include the AssetMajorType table in a table collection.

## Scenario: Establish common tax reference entries

Tax reference information is used in the following situations:

  - When calculating and posting withholding tax

  - When calculating, collecting, reporting, or paying sales tax

  - When setting up the general ledger, customers, or vendors

To minimize setup and maintenance, create a virtual company to share tax reference information among legal entities. Create the following table collections to include in the virtual company.

**Sales tax groups table collection**

Sales tax groups determine the sales tax and duty calculation for customers, vendors, or ledger accounts. To support sharing sales tax groups among company accounts, you must include the following tables in a table collection.

  - TaxGroupHeading

  - TaxData

  - LanguageTxt

  - TaxExemptCodeTable

  - TaxGroupData

  - TaxGroupTaxJurisdiction

  - TaxItemGroupHeading

  - TaxJurisdiction
    
    When you share this table, you must also share tables that are related to sales tax jurisdictions. For information about which tables to share, see the table collection in this topic.

  - TaxOnItem

  - TaxParameters
    
    When you share this table, you must also share tables that are related to tax parameters. For information about which tables to share, see the table collection in this topic.

  - TaxTable
    
    When you share this table, you must also share tables that are related to sales tax codes. For information about which tables to share, see the table collection in this topic.

**Item sales tax groups table collection**

To support sharing item sales tax groups among company accounts, you must include the following table in a table collection.

  - TaxItemGroupHeading

  - TaxOnItem

  - TaxTable
    
    When you share this table, you must also share tables that are related to sales tax codes. For information about which tables to share, see the table collection in this topic.

**Ledger posting groups table collection**

To support sharing ledger posting groups for sales taxes among company accounts, you must include the TaxLedgerAccountGroup table in a table collection.


> [!NOTE]
> <P>It is assumed that if you are sharing posting groups among company accounts, you are also using a shared chart of accounts.</P>



**Withholding tax groups table collection**

To support sharing withholding tax groups among company accounts, you must include the following table in a table collection.

  - TaxWithholdGroupHeading

  - TaxWithholdGroupDate

  - TaxWithholdTable
    
    When you share this table, you must also share tables that are related to withholding tax codes. For information about which tables to share, see the table collection in this topic.

**Sales tax codes table collection**

To support sharing sales tax codes among company accounts, you must include the following tables in a table collection.

  - TaxTable

  - LogisticsLocationAccessView

  - PaymTerm
    
    When you share this table, you must also share tables that are related to payment terms. For information about which tables to share, see the table collection in this topic.

  - TaxAuthorityAddress

  - TaxCollectLimit

  - TaxData

  - TaxJurisdiction
    
    When you share this table, you must also share tables that are related to sales tax jurisdictions. For information about which tables to share, see the table collection in this topic.

  - TaxLedgerAccountGroup

  - TaxPeriodHead

  - TaxReportCollection

  - TaxVATReportCategory\_MX

  - VendTable
    
    When you share this table, you must also share tables that are related to vendors. For information about which tables to share, see [Virtual company scenarios: CRM](virtual-company-scenarios-crm.md).

**Tax exempt codes table collection**

To support sharing sales tax exempt codes among company accounts, you must include the TaxExemptCodeTable table in a table collection.

**Sales tax reporting codes table collection**

To support sharing sales tax reporting codes for country or region specific sales tax reports among company accounts, you must include the TaxReportCollection table in a table collection.

**Withholding tax codes table collection**

To support sharing withholding tax codes among company accounts, you must include the following tables in a table collection.

  - TaxWithholdTable

  - PaymTerm
    
    When you share this table, you must also share tables that are related to payment terms. For information about which tables to share, see the table collection in this topic.

  - TaxAuthorityAddress

  - TaxWithholdData

  - TaxWithholdLedgerAccountGroup\_TH

  - TaxWithholdLimit

  - TaxWithholdPeriodHead\_TH

  - VendTable
    
    When you share this table, you must also share tables that are related to vendors. For information about which tables to share, see [Virtual company scenarios: CRM](virtual-company-scenarios-crm.md).

**Sales tax jurisdictions table collection**

To support sharing sales tax jurisdictions among company accounts, you must include the following tables in a table collection.

  - TaxJurisdiction

  - PaymTerm
    
    When you share this table, you must also share tables that are related to payment terms. For information about which tables to share, see the table collection in this topic.

  - TaxAuthorityAddress

  - TaxLedgerAccountGroup

  - TaxPeriodHead

  - VendTable
    
    When you share this table, you must also share tables that are related to vendors. For information about which tables to share, see [Virtual company scenarios: CRM](virtual-company-scenarios-crm.md).

**Tax withholding groups table collection**

To support sharing tax withholding groups among company accounts, you must include the following tables in a table collection.

  - TaxWithholdGroupData

  - TaxWithholdGroupHeading

  - TaxWithholdTable

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

