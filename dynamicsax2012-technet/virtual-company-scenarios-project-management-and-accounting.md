---
title: 'Virtual company scenarios: Project management and accounting'
TOCTitle: 'Virtual company scenarios: Project management and accounting'
ms:assetid: 18066ccc-9266-4b1a-b980-93e413690648
ms:mtpsurl: https://technet.microsoft.com/library/JJ712650(v=AX.60)
ms:contentKeyID: 49468954
author: tonyafehr
ms.date: 05/30/2014
mtps_version: v=AX.60
---

# Virtual company scenarios: Project management and accounting 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!IMPORTANT]
> <P>The functionality described in this topic is available only if Microsoft Dynamics AX 2012 R2 or Microsoft Dynamics AX 2012 R3 is installed.</P>



This topic describes the table collections that must be set up to support some common virtual company scenarios in the Project management and accounting module of Microsoft Dynamics AX. The first table in each list is the base table of the table collection. Other tables in the list are referenced by the base table.

For an overview of the concept of virtual companies, and for step-by-step instructions to create table collections and virtual company accounts, see [Virtual company accounts in Microsoft Dynamics AX](virtual-company-accounts-in-microsoft-dynamics-ax.md).

If you use Microsoft Project Server integration, virtual companies are not supported. You can’t enable Project Server integration for a virtual company.

## Scenario: Share project line properties

To share project line properties, create a **Project line properties** table collection to include in a virtual company. Include the ProjLineProperty table in the table collection.

## Scenario: Share project categories

Create a virtual company account to share project categories among company accounts. Create the following table collection to include in the virtual company.

**Project categories table collection**

Include the following tables in a table collection to support sharing project categories among company accounts.

  - CategoryTable

  - ProjCategoryGroup

  - ProjCategory
    
    When you share this table, you must also share tables that are related to project line properties. For information about which tables to share, see the table collection in this topic.

  - TaxItemGroupHeading
    
    When you share this table, you must also share tables that are related to sales tax groups. For information about which tables to share, see [Virtual company scenarios: Financials](virtual-company-scenarios-financials.md).

  - TaxWithholdItemGroupHeading\_TH

## Scenario: Share project cost templates

Project cost templates are used to compute estimates in fixed price projects. Create a virtual company account to share cost templates among company accounts. Create the following table collection to include in the virtual company.

**Project cost templates table collection**

Include the following tables in a table collection to support sharing project cost templates among company accounts.

  - ProjControl

  - ProjControlCategory
    
    When you share this table, you must also share tables that are related to project categories. For information about which tables to share, see the table collection in this topic.

  - ProjControlCostGroup

## Scenario: Share project periods

Project periods are used for timesheets and to compute estimates for fixed-price projects. Create a virtual company account to share project periods among company accounts. Create the following table collection to include in the virtual company.

**Project periods table collection**

Include the following tables in a table collection to support sharing project periods among company accounts.

  - ProjPeriodTable

  - ProjPeriodLine
    
    The ProjPeriodLine table has a dependency on the ForecastModel table. However, we recommend that you do not share the ForecastModel table through virtual companies. If you share project periods among company accounts, make sure that project periods do not contain references to forecast models. These references must remain blank.

  - ProjPeriodTimesheetWeek

## Scenario: Share project groups

To share project groups, create a **Project groups** table collection to include in a virtual company. Include the ProjGroup table in the table collection.

When you share this table, you must also share tables that are related to project categories, project cost templates, and project periods. For information about which tables to share, see the table collections in this topic.

## Scenario: Share indirect cost components

Indirect cost components are used to calculate indirect costs on timesheets. Create a virtual company account to share indirect cost components among company accounts. Create the following table collection to include in the virtual company.

**Indirect cost components table collection**

Include the following tables in a table collection to support sharing indirect cost components among company accounts.

  - PSAIndirectComponent
    
    When you share this table, you must also share tables that are related to project categories. For information about which tables to share, see the table collection in this topic.

  - PSAIndirectComponentGroup

  - PSAIndirectCompoundingSetup

  - PSAIndirectCompoundingRules

  - PSAIndirectCompoundingRuleSelection

## Scenario: Share retention terms

Create a virtual company account to share retention terms among company accounts. Create the following table collection to include in the virtual company.

**Vendor retention terms table collection**

Include the following tables in a table collection to support sharing vendor retention terms among company accounts.

  - PSAVendorRetentionTermsTable

  - PSAVendorRetentionTermsLine

**Customer retention terms table collection**

Include the following tables in a table collection to support sharing customer retention terms among company accounts.

  - PSACustomerRetentionTermsTable

  - PSACustomerRetentionTermsLine

  


