---
title: About the chart of accounts
TOCTitle: About the chart of accounts
ms:assetid: 3ef9f48f-f753-4fa0-b08c-849f498a3a9b
ms:mtpsurl: https://technet.microsoft.com/library/Aa496941(v=AX.60)
ms:contentKeyID: 36056696
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- accounts
- chart of accounts
- main accounts
- chart of account
- main account
audience: Application User
ms.search.region: Global
---

# About the chart of accounts 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To track and maintain financial information in an organization, you can set up a chart of accounts, which is a collection of accounts that define a financial framework. To further track the transactions in these accounts, segments, which are called financial dimensions, are added to the main accounts. For example, an expense account might include financial dimensions named Department, Cost center, and Purpose. User-defined rules, which are called advanced rules, dictate how these financial dimensions are attached to the main accounts and other financial dimensions, and how transactions can be entered against an account structure.

The chart of accounts is a structured list of a legal entity’s general ledger accounts. The list is used to prepare financial reports for authorities and owners. The accounts are grouped into types of accounts and further aggregated into larger categories. At the most general level, the accounts are grouped as revenues and costs (operating accounts), and assets and liabilities (balance accounts).

A chart of accounts can be shared and used by any legal entity in an organization. However, main accounts must be unique to a legal entity. Select the chart of accounts that can be used by a legal entity in the **Ledger** form.

You must consider several factors when you make decisions about how to structure the chart of accounts for your organization, including the following:

  - The reporting requirements of the country/region where your organization is based

  - The reporting requirements of your legal entity

  - The degree of specification needed, for both external organizations and for your organization

Create the chart of accounts in the **Chart of accounts** form. Use the **Main accounts - chart of accounts: %1** form to set up main accounts in each category, and include gaps between the accounts so that you can insert new main accounts, as needed. Main accounts in the same category have similar account numbers, and often have header and total lines that allow for easier identification and aggregation of the account category.

We recommend that you link the main accounts to main account categories when you use Management Reporter for Microsoft Dynamics ERP. When you link main accounts to main account categories, you can use the default reports that are included with Management Reporter without any modifications. This can make it faster and easier to design and maintain reports. This feature is available only if cumulative update 6 or later for Management Reporter is installed.

Use the **Configure account structures** form to create account structures, which are used to define valid combinations. The combinations, together with main accounts, form a chart of accounts.

## See also

[About main account types](about-main-account-types.md)

[Chart of accounts (form)](https://technet.microsoft.com/library/aa618234\(v=ax.60\))

[Configure account structures (form)](https://technet.microsoft.com/library/hh227362\(v=ax.60\))

[Link main accounts to main account categories](link-main-accounts-to-main-account-categories.md)

  


