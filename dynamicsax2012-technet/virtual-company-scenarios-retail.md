---
title: 'Virtual company scenarios: Retail'
TOCTitle: 'Virtual company scenarios: Retail'
ms:assetid: 6643c91f-47e3-43e7-8074-abb169f29da6
ms:mtpsurl: https://technet.microsoft.com/library/JJ916615(v=AX.60)
ms:contentKeyID: 50934000
author: tonyafehr
ms.date: 05/09/2014
mtps_version: v=AX.60
---

# Virtual company scenarios: Retail 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2_

This topic describes the table collections that must be set up to support some common virtual company scenarios in the Retail module of Microsoft Dynamics AX. For an overview of the concept of virtual companies, and for step-by-step instructions to create table collections and virtual company accounts, see [Virtual company accounts in Microsoft Dynamics AX](virtual-company-accounts-in-microsoft-dynamics-ax.md).


> [!IMPORTANT]
> <P>The functionality described in this topic is applicable only in Microsoft Dynamics AX 2012 R2. In Microsoft Dynamics AX 2012 R3, you can configure gift cards to be shared across multiple legal entities. Also, loyalty programs are no longer constrained by legal entity. They are tied to channels, which are global entities.</P>




> [!NOTE]
> <P>The first table in each list is the base table of the table collection. Other tables in the list are referenced by the base table.</P>



## Scenario: Use gift cards in multiple companies

Create a virtual company account to use gift cards in multiple company accounts. Create the following table collection to include in the virtual company.

**Gift cards table collection**

Include the following tables in a table collection to support sharing gift card data among company accounts.

  - RetailGiftCardTable

  - RetailGiftCardTransactions

## Scenario: Share loyalty schemes among company accounts

Create a virtual company account to share loyalty schemes among company accounts. Create the following table collection to include in the virtual company.

**Loyalty scheme table collection**

Include the following tables in a table collection to support sharing loyalty schemes among company accounts.

  - RetailLoyaltyCustTable

  - RetailLoyaltyMSRCardTable

  - RetailLoyaltyMSRCardTrans

  - RetailLoyaltyMSRCardTransCustInvoiceJour

  - RetailLoyaltyPointsTable

  - RetailLoyaltySchemesTable

  


