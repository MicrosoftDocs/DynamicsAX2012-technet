---
title: 'Virtual company scenarios: Supply chain management (SCM)'
TOCTitle: 'Virtual company scenarios: Supply chain management (SCM)'
ms:assetid: 2b597c20-5c14-4be4-a737-47e78e27757c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ556268(v=AX.60)
ms:contentKeyID: 49089839
ms.date: 05/30/2014
mtps_version: v=AX.60
---

# Virtual company scenarios: Supply chain management (SCM) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes the table collections that must be set up to support some common virtual company scenarios in the Supply chain management module of Microsoft Dynamics AX. For an overview of the concept of virtual companies, and for step-by-step instructions to create table collections and virtual company accounts, see [Virtual company accounts in Microsoft Dynamics AX](virtual-company-accounts-in-microsoft-dynamics-ax.md).


> [!NOTE]
> <P>The first table in each list is the base table of the table collection. Other tables in the list are referenced by the base table.</P>



## Scenario: Share common setup data

Create a virtual company account to share supply chain management setup data among company accounts. Create the following table collections to include in the virtual company.

**Bar codes setup table collection**

To support sharing bar codes among company accounts, you must include the following tables in a table collection.


> [!NOTE]
> <P>Some tables that are listed in this table collection are available only if you are using Microsoft Dynamics AX 2012 R2 or Microsoft Dynamics AX 2012 R3.</P>



  - BarcodeSetup

  - RetailBarcodeMaskTable

  - RetailBarcodeMaskSegment

  - RetailBarcodeMaskCharacter

**Problem/Non-conformance types validation table collection**

To support sharing problem/non-conformance types among company accounts, you must include the following tables in a table collection.

  - InventProblemTypeSetup

  - InventProblemType

**Pallet types table collection**

To support sharing pallet types among company accounts, you must include the following tables in a table collection.

  - WMSPalletType

  - WMSPalletTypeGroup

  - WMSPalletTypeGroupMember

**Gantt colors table collection**

To support sharing Gantt colors among company accounts, you must include the GanttColorTable table in a table collection.

## Scenario: Share common groups for accounting, filtering, and reporting

Create a virtual company account to share common groups among company accounts. Create the following table collections to include in the virtual company.

**Item model groups table collection**

To support sharing item model groups among company accounts, you must include the following tables in a table collection.

  - InventModelGroup

  - PdsDispositionMaster

Some fields in the InventModelGroup table are available only when you are logged on to a company account that operates in a particular country/region. If the InventModelGroup table is shared among companies in multiple countries/regions, you must maintain the following fields in a company that operates in the specified country/region.

  - **Physical negative inventory** and **Financial negative inventory** – If the virtual company account includes company accounts that operate in Russia, these fields must be maintained in a company whose primary address is in Russia.

  - **Inventory model** – If the virtual company account includes company accounts that operate in China, this field must be maintained in a company whose primary address is in China.

**Product model groups table collection**

To support sharing product model groups among company accounts, you must include the PBACustGroup table in a table collection.

**Price/discount groups table collection**

To support sharing price/discount groups among company accounts, you must include the PriceDiscGroup table in a table collection.

**Rounding versions table collection**

To support sharing rounding versions among company accounts, you must include the following tables in a table collection.

  - PriceDiscSmartRoundingGroup

  - PriceDiscSmartRoundingGroupCurrency

  - PriceDiscSmartRoundingRule

**Supplementary item groups table collection**

To support sharing supplementary item groups among company accounts, you must include the SuppItemGroup table in a table collection.

**Production groups table collection**

To support sharing production groups among company accounts, you must include the ProdGroup table in a table collection.

**Production pools table collection**

To support sharing production pools among company accounts, you must include the ProdPool table in a table collection.

**Purchase pools table collection**

To support sharing purchase pools among company accounts, you must include the PurchPool table in a table collection.

**Buyer groups table collection**

To support sharing buyer groups among company accounts, you must include the InventBuyerGroup table in a table collection.

**Inventory profiles table collection**

To support sharing inventory profiles among company accounts, you must include the following tables in a table collection.

  - InventProfile\_RU

  - InventProfileRelation\_RU

**Order entry deadline groups table collection**

To support sharing order entry deadline groups among company accounts, you must include the InventOrderEntryDeadlineGroup table in a table collection.

**Order pools table collection**

To support sharing order pools among company accounts, you must include the SalesPool table in a table collection.

**Order origin codes table collection**

To support sharing order origin codes among company accounts, you must include the SalesOrigin table in a table collection.

**Charges groups table collection**

To support sharing charges groups among company accounts, you must include the MarkupGroup table in a table collection.

**Charges codes table collection**

To support sharing charges codes among company accounts, you must include the following tables in a table collection.

  - MarkupTable

  - LanguageTxt

  - MarkupTolerance

  - TaxItemGroupHeading
    
    When you share this table, you must also share tables that are related to sales tax groups. For information about which tables to share, see [Virtual company scenarios: Financials](virtual-company-scenarios-financials.md).

  - ExtCodeValueTable

We recommend that you do not share parameters tables through virtual companies. For this table collection, the related parameters table is VendParameters. Because we recommend that you do not share parameters, make sure that the following settings are the same in all companies that share the MarkupTable table. Alternatively, verify that the expected setting is used in each company, and correct it if necessary.

  - **Post to charge account in ledger** - When you create a charges code, **Debit** values are validated based on this option in the accounts payable parameters for the current company.

## Scenario: Share common delivery reference data

Create a virtual company account to share delivery reference data among company accounts. Create the following table collections to include in the virtual company.

**Modes of delivery table collection**

To support sharing modes of delivery among company accounts, you must include the following tables in a table collection.


> [!NOTE]
> <P>Some tables that are listed in this table collection are available only if you are using Microsoft Dynamics AX 2012 R3.</P>



  - DlvMode

  - ExtCodeValueTable

  - LanguageTxt

  - MarkupGroup
    
    When you share this table, you must also share tables that are related to charges groups. For information about which tables to share, see the table collection in this topic.

  - MCRExpediteTable

  - RetailDlvModeAddressLine

  - RetailDlvModeChannelLine

  - RetailDlvModeProductLine

  - RetailShipCarrierInterface

  - ShipCarrierTable
    
    When you share this table, you must also share tables that are related to shipping carriers. For information about which tables to share, see the table collection in this topic.

**Reasons for delivery table collection**

To support sharing reasons for delivery among company accounts, you must include the following tables in a table collection.

  - DlvReason

  - LanguageTxt

**Terms of delivery table collection**

To support sharing terms of delivery among company accounts, you must include the following tables in a table collection.


> [!NOTE]
> <P>Some tables that are listed in this table collection are available only if you are using Microsoft Dynamics AX 2012 R3.</P>



  - DlvTerm

  - ExtCodeValueTable

  - InventProfile\_RU
    
    When you share this table, you must also share tables that are related to shipping carriers. For information about which tables to share, see the table collection in this topic.

  - LanguageTxt

  - TMSDlvTerm

**Destination codes table collection**

To support sharing destination codes among company accounts, you must include the DestinationCode table in a table collection.

**Shipping carriers table collection**

To support sharing shipping carriers among company accounts, you must include the following tables in a table collection.

  - ShipCarrierCompany

  - MarkupTable
    
    When you share this table, you must also share tables that are related to charges codes. For information about which tables to share, see the table collection in this topic.

  - RetailShipCarrierAccountConfiguration

  - ShipCarrierCompanyAccounts

  - VendTable
    
    When you share this table, you must also share tables that are related to vendors. For information about which tables to share, see [Virtual company scenarios: CRM](virtual-company-scenarios-crm.md).

## Scenario: Share work time calendars

Create a virtual company account to share work time calendars among company accounts. Create the following table collections to include in the virtual company.

**Work time calendars table collection**

To support sharing work time calendars among company accounts, you must include the following tables in a table collection.

  - WorkCalendarTable

  - WorkCalendarDate

  - WorkCalendarDateLine

  - WrkCtrProperty
    
    When you share this table, you must also share tables that are related to resource properties. For information about which tables to share, see the table collection in this topic.

**Resource properties table collection**

To support sharing resource properties among company accounts, you must include the following tables in a table collection.

  - WrkCtrProperty

  - WrkCtrPropertyLine

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

