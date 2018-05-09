---
title: 'Virtual company scenarios: CRM'
TOCTitle: 'Virtual company scenarios: CRM'
ms:assetid: 20281b2c-1def-44f6-bfc7-5e73e8452961
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ556270(v=AX.60)
ms:contentKeyID: 49089836
ms.date: 05/30/2014
mtps_version: v=AX.60
---

# Virtual company scenarios: CRM 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes the table collections that must be set up to support some common virtual company scenarios in the CRM module of Microsoft Dynamics AX. For an overview of the concept of virtual companies, and for step-by-step instructions to create table collections and virtual company accounts, see [Virtual company accounts in Microsoft Dynamics AX](virtual-company-accounts-in-microsoft-dynamics-ax.md).


> [!NOTE]
> <P>The first table in each list is the base table of the table collection. Other tables in the list are referenced by the base table.</P>



## Scenario: Use common commission reference data

Create a virtual company account to share commission reference data among company accounts. Create the following table collections to include in the virtual company.

**Commission customer groups table collection**

To support sharing commission customer groups among company accounts, you must include the CommissionCustomerGroup table in a table collection.

**Commission sales groups table collection**

Include the following tables in a table collection to support sharing commission sales groups among company accounts.

  - CommissionSalesGroup

  - CommissionSalesRep

## Scenario: Share customer records

Create a virtual company account to share customers among company accounts. Create the following table collection to include in the virtual company.

**Customers table collection**

Include the following tables in a table collection to support sharing customer records among company accounts.


> [!NOTE]
> <P>Some tables that are listed in this table collection are available only if you are using Microsoft Dynamics AX 2012 R2 or Microsoft Dynamics AX 2012 R3.</P>



  - CustTable

  - BankCentralBankPurpose

  - BankConstantSymbol

  - BankCustPaymIdTable

  - BankGroup

  - CashDisc
    
    When you share this table, you must also share tables that are related to cash discounts. For information about which tables to share, see [Virtual company scenarios: Financials](virtual-company-scenarios-financials.md).

  - CommissionCustomerGroup

  - CommissionSalesGroup
    
    When you share this table, you must also share tables that are related to commission sales groups. For information about which tables to share, see the table collection in this topic.

  - CompanyNAFCode

  - ContactPerson
    
    When you share this table, you must also share tables that are related to contacts. For information about which tables to share, see the table collection in this topic.

  - CreditCardCust
    
    When you share this table, you must also share tables that are related to payment services. For information about which tables to share, see [Virtual company scenarios: Financials](virtual-company-scenarios-financials.md).

  - CustBankAccount

  - CustClassificationGroup

  - CustDefaultLocation

  - CustFineSetup\_BR

  - CustGroup
    
    When you share this table, you must also share tables that are related to customer groups. For information about which tables to share, see [Virtual company scenarios: Financials](virtual-company-scenarios-financials.md).

  - CustInterestSetup\_BR

  - CustPaymModeSpec
    
    When you share this table, you must also share tables that are related to customer methods of payment. For information about which tables to share, see [Virtual company scenarios: Financials](virtual-company-scenarios-financials.md).

  - CustPaymModeTable
    
    When you share this table, you must also share tables that are related to customer methods of payment. For information about which tables to share, see [Virtual company scenarios: Financials](virtual-company-scenarios-financials.md).

  - CustStatisticsGroup

  - CustTradingPartnerCode

  - CustVendItemGroup

  - DestinationCode
    
    When you share this table, you must also share tables that are related to destination codes. For information about which tables to share, see [Virtual company scenarios: Supply chain management (SCM)](virtual-company-scenarios-supply-chain-management-scm.md).

  - DlvMode
    
    When you share this table, you must also share tables that are related to modes of delivery. For information about which tables to share, see [Virtual company scenarios: Supply chain management (SCM)](virtual-company-scenarios-supply-chain-management-scm.md).

  - DlvReason
    
    When you share this table, you must also share tables that are related to reasons for delivery. For information about which tables to share, see [Virtual company scenarios: Supply chain management (SCM)](virtual-company-scenarios-supply-chain-management-scm.md).

  - DlvTerm
    
    When you share this table, you must also share tables that are related to terms of delivery. For information about which tables to share, see [Virtual company scenarios: Supply chain management (SCM)](virtual-company-scenarios-supply-chain-management-scm.md).

  - ExtCodeValueTable

  - InventOrderEntryDeadlineGroup
    
    When you share this table, you must also share tables that are related to order entry deadline groups. For information about which tables to share, see [Virtual company scenarios: Supply chain management (SCM)](virtual-company-scenarios-supply-chain-management-scm.md).

  - InventProfile\_RU
    
    When you share this table, you must also share tables that are related to inventory profiles. For information about which tables to share, see [Virtual company scenarios: Supply chain management (SCM)](virtual-company-scenarios-supply-chain-management-scm.md).

  - LineOfBusiness

  - LvPaymTransCodes

  - MarkupGroup
    
    When you share this table, you must also share tables that are related to charges groups. For information about which tables to share, see [Virtual company scenarios: Supply chain management (SCM)](virtual-company-scenarios-supply-chain-management-scm.md).

  - PaymDay
    
    When you share this table, you must also share tables that are related to payment days. For information about which tables to share, see [Virtual company scenarios: Financials](virtual-company-scenarios-financials.md).

  - PaymSched
    
    When you share this table, you must also share tables that are related to payment schedules. For information about which tables to share, see [Virtual company scenarios: Financials](virtual-company-scenarios-financials.md).

  - PaymTerm
    
    When you share this table, you must also share tables that are related to payment terms. For information about which tables to share, see [Virtual company scenarios: Financials](virtual-company-scenarios-financials.md).

  - PBACustGroup
    
    When you share this table, you must also share tables that are related to product model groups. For information about which tables to share, see [Virtual company scenarios: Supply chain management (SCM)](virtual-company-scenarios-supply-chain-management-scm.md).

  - PdsCustRebateGroup

  - PdsRebateProgramTMATable

  - PlTaxDueTable

  - PriceDiscGroup
    
    When you share this table, you must also share tables that are related to price/discount groups. For information about which tables to share, see [Virtual company scenarios: Supply chain management (SCM)](virtual-company-scenarios-supply-chain-management-scm.md).

  - PrintMgmtDocInstance

  - RetailCustTable

  - RetailShipCarrierInterface

  - SalesPool
    
    When you share this table, you must also share tables that are related to order pools. For information about which tables to share, see [Virtual company scenarios: Supply chain management (SCM)](virtual-company-scenarios-supply-chain-management-scm.md).

  - ShipCarrierTable
    
    When you share this table, you must also share tables that are related to shipping carriers. For information about which tables to share, see [Virtual company scenarios: Supply chain management (SCM)](virtual-company-scenarios-supply-chain-management-scm.md).

  - smmBusRelChainGroup

  - smmBusRelSalesDistrictGroup

  - smmBusRelSegmentGroup

  - smmBusRelSubSegmentGroup

  - smmResponsibilitiesEmplTable

  - SuppItemGroup
    
    When you share this table, you must also share tables that are related to supplementary item groups. For information about which tables to share, see [Virtual company scenarios: Supply chain management (SCM)](virtual-company-scenarios-supply-chain-management-scm.md).

  - TaxGroupHeading
    
    When you share this table, you must also share tables that are related to sales tax groups. For information about which tables to share, see [Virtual company scenarios: Financials](virtual-company-scenarios-financials.md).

  - TaxInformationCustTable\_IN
    
    When you share this table, you must also share tables that are related to withholding tax groups. For information about which tables to share, see [Virtual company scenarios: Financials](virtual-company-scenarios-financials.md).

  - TaxVATNumTable

  - TaxWithholdGroupHeading
    
    When you share this table, you must also share tables that are related to withholding tax groups. For information about which tables to share, see [Virtual company scenarios: Financials](virtual-company-scenarios-financials.md).

  - VendTable
    
    When you share this table, you must also share tables that are related to vendors. For information about which tables to share, see the table collection in this topic.

  - WHSCustTable

  - WorkCalendarTable
    
    When you share this table, you must also share tables that are related to work time calendars. For information about which tables to share, see [Virtual company scenarios: Supply chain management (SCM)](virtual-company-scenarios-supply-chain-management-scm.md).

For this table collection, the related parameters tables include CustFormLetterParameters, ProjFormletterParameters, RetailParameters, SalesParameters, and CustParameters. Because we recommend that you do not share parameters, make sure that the following settings are the same in all companies that share the CustTable table. Alternatively, verify that the expected setting is used in each company, and correct it if necessary.

  - Payment attachment fields - When you create customers, the default payment attachment options come from the customer form letter parameters and project form letter parameters for the current company.

  - **Require identification with credit selection** and **Limit value** - The system validates the **Mandatory credit limit** and **Credit limit** values for a customer based on the selections for these options in the customer parameters for the current company.

  - **Mandatory tax group** and **Tax exempt number** - You must enter values in the **Sales tax group** and **Tax exempt number** fields if these requirements are selected in the customer parameters for the current company.

  - **Credit limit per agreement** – For companies that operate in Russia, the system validates the **Credit limit** value for a customer based on the selection for the **Credit limit per agreement** option in the customer parameters for the current company.

  - **VAT report date code** – For companies that operate in Poland, the default **VAT report date code** value for a customer comes from the associated customer group or customer parameters for the current company.

  - **Post as shipment** – When you create customers, the default **Post as shipment** value comes from the **Default customer posting** field in the retail parameters for the current company.

  - **Posting type** – For companies that operate in Russia, the default **Posting type** value for customers comes from the **Posting type** field in the sales parameters for the current company.

  - **Generate incoming fiscal document** – For companies that operate in Brazil, the **Generate incoming fiscal document** option is selected by default for customers that are created without ID numbers. The option is selected when those customers are associated with Person records.

We recommend that you do not share InventSite and InventLocation tables. Sites and warehouses are locations at which a specific legal entity performs production activities and stores products. If customer records are shared among company accounts, make sure that the fields that reference these tables are blank.

We recommend that you do not share WHSInventStatus table. Inventory statuses are specific to a legal entity and modification of statuses are only validated against the current company. If customer records are shared among company accounts, make sure that the field that reference the table is blank.

The following company-specific tables have foreign key relationships to the CustTable table. We recommend that you do not share these tables or their dependent tables in a virtual company, because sharing them can cause duplicate index violations in the database.

  - SalesJournalAutoSummary – If customer records are shared among company accounts, you cannot use the automatic summary update feature when you process sales orders.

  - SalesPurchCycle – If customer records are shared among company accounts, you cannot use the sales cycle feature when you process sales orders. The **Sales cycle** option in the sales parameters must not be selected in any of the companies where the CustTable table is shared.

## Scenario: Share vendor records

Create a virtual company account to share vendors among company accounts. Create the following table collection to include in the virtual company.


> [!NOTE]
> <P>Some tables that are listed in this table collection are available only if you are using Microsoft Dynamics AX 2012 R2 or Microsoft Dynamics AX 2012 R3.</P>



**Vendors table collection**

Include the following tables in a table collection to support sharing vendor records among company accounts.

  - VendTable

  - BankCentralBankPurpose

  - BankConstantSymbol

  - BankGroup

  - CashDisc
    
    When you share this table, you must also share tables that are related to cash discounts. For information about which tables to share, see [Virtual company scenarios: Financials](virtual-company-scenarios-financials.md).

  - CompanyNAFCode

  - ContactPerson
    
    When you share this table, you must also share tables that are related to contacts. For information about which tables to share, see the table collection in this topic.

  - CustVendItemGroup

  - DestinationCode
    
    When you share this table, you must also share tables that are related to destination codes. For information about which tables to share, see [Virtual company scenarios: Supply chain management (SCM)](virtual-company-scenarios-supply-chain-management-scm.md).

  - DlvMode
    
    When you share this table, you must also share tables that are related to modes of delivery. For information about which tables to share, see [Virtual company scenarios: Supply chain management (SCM)](virtual-company-scenarios-supply-chain-management-scm.md).

  - DlvTerm
    
    When you share this table, you must also share tables that are related to terms of delivery. For information about which tables to share, see [Virtual company scenarios: Supply chain management (SCM)](virtual-company-scenarios-supply-chain-management-scm.md).

  - ExtCodeValueTable

  - InventBuyerGroup
    
    When you share this table, you must also share tables that are related to buyer groups. For information about which tables to share, see [Virtual company scenarios: Supply chain management (SCM)](virtual-company-scenarios-supply-chain-management-scm.md).

  - InventProfile\_RU
    
    When you share this table, you must also share tables that are related to inventory profiles. For information about which tables to share, see [Virtual company scenarios: Supply chain management (SCM)](virtual-company-scenarios-supply-chain-management-scm.md).

  - LineOfBusiness

  - LvPaymTransCodes

  - MarkupGroup
    
    When you share this table, you must also share tables that are related to charges groups. For information about which tables to share, see [Virtual company scenarios: Supply chain management (SCM)](virtual-company-scenarios-supply-chain-management-scm.md).

  - PaymDay
    
    When you share this table, you must also share tables that are related to payment days. For information about which tables to share, see [Virtual company scenarios: Financials](virtual-company-scenarios-financials.md).

  - PaymSched
    
    When you share this table, you must also share tables that are related to payment schedules. For information about which tables to share, see [Virtual company scenarios: Financials](virtual-company-scenarios-financials.md).

  - PaymTerm
    
    When you share this table, you must also share tables that are related to payment terms. For information about which tables to share, see [Virtual company scenarios: Financials](virtual-company-scenarios-financials.md).

  - PlTaxDueTable

  - PriceDiscGroup
    
    When you share this table, you must also share tables that are related to price/discount groups. For information about which tables to share, see [Virtual company scenarios: Supply chain management (SCM)](virtual-company-scenarios-supply-chain-management-scm.md).

  - PrintMgmtDocInstance

  - PurchPool
    
    When you share this table, you must also share tables that are related to purchase pools. For information about which tables to share, see [Virtual company scenarios: Supply chain management (SCM)](virtual-company-scenarios-supply-chain-management-scm.md).

  - RetailReplenishmentRuleLines

  - RetailReplenishmentRuleTable

  - RetailRoundingMethodGroup

  - RetailSalesPricePointGroup

  - RetailServiceCategory

  - RetailVendTable

  - smmBusRelChainGroup

  - smmBusRelSegmentGroup

  - smmBusRelSubSegmentGroup

  - smmResponsibilitiesEmplTable

  - SuppItemGroup
    
    When you share this table, you must also share tables that are related to supplementary item groups. For information about which tables to share, see [Virtual company scenarios: Supply chain management (SCM)](virtual-company-scenarios-supply-chain-management-scm.md).

  - TAMVendRebateGroup

  - Tax1099Fields

  - TaxGroupHeading
    
    When you share this table, you must also share tables that are related to sales tax groups. For information about which tables to share, see [Virtual company scenarios: Financials](virtual-company-scenarios-financials.md).

  - TaxInformationVendTable\_IN
    
    When you share this table, you must also share tables that are related to withholding tax groups. For information about which tables to share, see [Virtual company scenarios: Financials](virtual-company-scenarios-financials.md).

  - TaxVATNumTable

  - TaxWithholdGroupHeading
    
    When you share this table, you must also share tables that are related to withholding tax groups. For information about which tables to share, see [Virtual company scenarios: Financials](virtual-company-scenarios-financials.md).

  - VATOperationCodeTable\_RU

  - VendBankAccount

  - VendContractZakat\_SA

  - VendDefaultAccounts

  - VendDefaultLocation

  - VendExceptionGroup

  - VendFineSetup\_BR

  - VendGroup
    
    When you share this table, you must also share tables that are related to vendor groups. For information about which tables to share, see [Virtual company scenarios: Financials](virtual-company-scenarios-financials.md).

  - VendInfoZakat\_SA

  - VendInterestSetup\_BR

  - VendInvoiceDeclaration\_IS

  - VendPaymModeSpec
    
    When you share this table, you must also share tables that are related to vendor methods of payment. For information about which tables to share, see [Virtual company scenarios: Financials](virtual-company-scenarios-financials.md).

  - VendPaymModeTable
    
    When you share this table, you must also share tables that are related to vendor methods of payment. For information about which tables to share, see [Virtual company scenarios: Financials](virtual-company-scenarios-financials.md).

  - VendPriceToleranceGroup

  - VendStateTaxID

  - VendTotalPriceTolerance

  - WorkCalendarTable
    
    When you share this table, you must also share tables that are related to work time calendars. For information about which tables to share, see [Virtual company scenarios: Supply chain management (SCM)](virtual-company-scenarios-supply-chain-management-scm.md).

For this table collection, the related parameters tables include PurchParameters and VendParameters. Because we recommend that you do not share parameters, make sure that the following settings are the same in all companies that share the VendTable table. Alternatively, verify that the expected setting is used in each company, and correct it if necessary.

  - **Purchase order prices/amount** - When you create vendors, the default selection in this field comes from the purchasing parameters for the current company.

  - **Check for W-9 form** - When you create vendors, the default selection in this field comes from the vendor parameters for the current company.

  - **Line matching policy** - The system validates the **Line matching policy** based on the vendor parameters for the current company.

  - **Mandatory tax group** and **Tax exempt number** - You must enter values in the **Sales tax group** and **Tax exempt number** fields if the requirements are selected in the vendor parameters for the current company.

  - **Credit limit per agreement** – For companies that operate in Russia, the system validates the **Credit limit** value for a vendor based on the selection for the **Credit limit per agreement** option in the vendor parameters for the current company.

  - **VAT report date code** – For companies that operate in Poland, the default **VAT report date code** value for a vendor comes from the associated vendor group or the vendor parameters for the current company.

We recommend that you do not share InventSite and InventLocation tables. Sites and warehouses are locations at which a specific legal entity performs production activities and stores products. If vendor records are shared among company accounts, make sure that the fields that reference these tables are blank.

We recommend that you do not share WHSInventStatus table. Inventory statuses are specific to a legal entity and modification of statuses are only validated against the current company. If vendor records are shared among company accounts, make sure that the field that reference the table is blank.

The following company-specific tables have foreign key relationships to the VendTable table. We recommend that you do not share these tables or their dependent tables in a virtual company, because sharing them can cause duplicate index violations in the database.

  - PurchJournalAutoSummary – If vendor records are shared among company accounts, you cannot use the automatic summary update feature when you process purchase orders.

  - SalesPurchCycle – If vendor records are shared among company accounts, you cannot use the purchase cycle feature when you process purchase orders. The **Purchase cycle** option in the purchasing parameters must not be selected in any of the companies where the VendTable table is shared.

## Scenario: Share contact person records

Create a virtual company account to share contact person records among company accounts. Create the following table collection to include in the virtual company.

**Contact person table collection**

Include the following tables in a table collection to support sharing contact person records among company accounts.

  - ContactPerson

  - CustTable
    
    When you share this table, you must also share tables that are related to customers. For information about which tables to share, see the table collection in this topic.

  - PersonTitleTable

  - smmCharacterGroup

  - smmContactGreetingsGroup

  - smmContactInterest

  - smmContactIntroGroup

  - smmDecisionGroup

  - smmFunctionGroup

  - smmInterestGroup

  - smmLoyaltyGroup

  - smmNoteItTable

## Scenario: Share prospects

Create a virtual company account to share prospects among company accounts. Create the following table collection to include in the virtual company.

**Prospects table collection**

Include the following tables in a table collection to support sharing prospect records among company accounts.

  - smmBusRelTable

  - CompanyNAFCode

  - ContactPerson
    
    When you share this table, you must also share tables that are related to contacts. For information about which tables to share, see the table collection in this topic.

  - CustGroup
    
    When you share this table, you must also share tables that are related to customer groups. For information about which tables to share, see [Virtual company scenarios: Financials](virtual-company-scenarios-financials.md).

  - CustTable
    
    When you share this table, you must also share tables that are related to customers. For information about which tables to share, see the table collection in this topic.

  - DestinationCode
    
    When you share this table, you must also share tables that are related to destination codes. For information about which tables to share, see [Virtual company scenarios: Supply chain management (SCM)](virtual-company-scenarios-supply-chain-management-scm.md).

  - DirOrgPersonRelations

  - DlvMode
    
    When you share this table, you must also share tables that are related to modes of delivery. For information about which tables to share, see [Virtual company scenarios: Supply chain management (SCM)](virtual-company-scenarios-supply-chain-management-scm.md).

  - DlvTerm
    
    When you share this table, you must also share tables that are related to terms of delivery. For information about which tables to share, see [Virtual company scenarios: Supply chain management (SCM)](virtual-company-scenarios-supply-chain-management-scm.md).

  - LineOfBusiness

  - smmBusRelChainGroup

  - smmBusRelDefaultLocation

  - smmBusRelSalesDistrictGroup

  - smmBusRelSectorTable

  - smmBusRelSegmentGroup

  - smmBusRelStatusGroup

  - smmBusRelSubSegmentGroup

  - smmBusRelTypeGroup

  - smmBusSectorGroup

  - smmConvertedBusRel

  - smmNoteItTable

  - smmResponsibilitiesEmplTable

  - TaxGroupHeading
    
    When you share this table, you must also share tables that are related to sales tax groups. For information about which tables to share, see [Virtual company scenarios: Financials](virtual-company-scenarios-financials.md).

  - VendGroup
    
    When you share this table, you must also share tables that are related to vendor groups. For information about which tables to share, see [Virtual company scenarios: Financials](virtual-company-scenarios-financials.md).

  - VendTable
    
    When you share this table, you must also share tables that are related to vendors. For information about which tables to share, see the table collection in this topic.

  - WorkCalendarTable
    
    When you share this table, you must also share tables that are related to work time calendars. For information about which tables to share, see [Virtual company scenarios: Supply chain management (SCM)](virtual-company-scenarios-supply-chain-management-scm.md).

For this table collection, the related parameters table is smmParametersTable. Because we recommend that you do not share parameters, make sure that the following settings are the same in all companies that share the smmBusRelTable table. Alternatively, verify that the expected setting is used in each company, and correct it if necessary.

  - **Type ID** - When you create prospects, the default selection in this field comes from the sales and marketing parameters for the current company.

  - **Customer group** - When you create prospects, the default selection in this field comes from the sales and marketing parameters for the current company.

  - **Vendor group** - When you create prospects, the default selection in this field comes from the sales and marketing parameters for the current company.

  - **Opening time** - When you create prospects, the default selection in this field comes from the sales and marketing parameters for the current company.

  - **Closing time** - When you create prospects, the default selection in this field comes from the sales and marketing parameters for the current company.

  - **Currency** - When you create prospects, the default selection in this field comes from the sales and marketing parameters for the current company.

## Scenario: Share leads

Create a virtual company account to share leads among company accounts. Create the following table collection to include in the virtual company.

**Leads table collection**

Include the following tables in a table collection to support sharing lead records among company accounts.

  - smmLeadTable

  - ContactPerson
    
    When you share this table, you must also share tables that are related to contacts. For information about which tables to share, see the table collection in this topic.

  - CustTable
    
    When you share this table, you must also share tables that are related to customers. For information about which tables to share, see the table collection in this topic.

  - DirOrgPersonRelations

  - smmBusRelTable
    
    When you share this table, you must also share tables that are related to prospects. For information about which tables to share, see the table collection in this topic.

  - smmLeadPriorityTable

  - smmLeadRatingTable

  - smmLeadRelTable

  - smmLeadTypeTable

  - smmQuotationReasonGroup

  - smmResponsibilitiesEmplTable

  - smmSalesUnit

  - smmSalesUnitMembers

  - smmSourceTypeTable

  - smmSourceTypeOptions

## Scenario: Share opportunities

Create a virtual company account to share opportunities among company accounts. Create the following table collection to include in the virtual company.

**Opportunities table collection**

Include the following tables in a table collection to support sharing opportunity records among company accounts.

  - smmOpportunityTable

  - ContactPerson
    
    When you share this table, you must also share tables that are related to contacts. For information about which tables to share, see the table collection in this topic.

  - CustTable
    
    When you share this table, you must also share tables that are related to customers. For information about which tables to share, see the table collection in this topic.

  - DirOrgPersonRelations

  - smmBusRelTable
    
    When you share this table, you must also share tables that are related to prospects. For information about which tables to share, see the table collection in this topic.

  - smmOpportunityRelTable

  - smmQuotationProbabilityGroup

  - smmQuotationPrognosisGroup

  - smmQuotationReasonGroup

  - smmResponsibilitiesEmplTable

  - smmSalesUnit

  - smmSalesUnitMembers

  - smmSourceTypeTable

  - smmSourceTypeOptions

  - smmSwotTable

For this table collection, the related parameters table is smmParametersTable. Because we recommend that you do not share parameters, make sure that the following settings are the same in all companies that share the smmOpportunityTable table. Alternatively, verify that the expected setting is used in each company, and correct it if necessary.

  - **Type ID**, **Language**, and **Currency** - The system validates whether an opportunity can be converted to a prospect based on these fields in the sales and marketing parameters for the current company.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

