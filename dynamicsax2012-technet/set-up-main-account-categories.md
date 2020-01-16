---
title: Set up main account categories
TOCTitle: Set up main account categories
ms:assetid: cbcc15d1-bf00-4322-b94c-85abef2ae4c9
ms:mtpsurl: https://technet.microsoft.com/library/Gg213663(v=AX.60)
ms:contentKeyID: 36059344
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- main accounts
- account categories
- main account categories
audience: Application User
ms.search.region: Global
---

# Set up main account categories 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Main account categories** form to set up main account categories. You can use main account categories, which are attributes that provide an additional classification, to categorize general ledger main accounts and define an account range to view information from a group of accounts. For more information, see [Main account categories (form)](https://technet.microsoft.com/library/hh227632\(v=ax.60\)).

Main account categories are used for key performance indicators (KPIs) and calculated measures for analysis cubes. Based on the main account categories that are assigned to the main accounts, the KPIs and calculated measures provide summarized views of your data. For more information, see [Main account categories and analysis cubes](main-account-categories-and-analysis-cubes.md).

1.  Click **General ledger** \> **Setup** \> **Chart of accounts** \> **Main account categories**.

2.  Click **New** to create a main account category.

3.  Enter a unique name for the main account category and a description.

4.  Select a main account type to associate to the main account category.
    

    > [!NOTE]
    > <P>The main account type is displayed in the <STRONG>Main account type</STRONG> field in the <STRONG>Main accounts - chart of accounts: %1</STRONG> form. Selecting a main account type here does not prevent you from linking the main account category to main accounts that have a different main account type.</P>



5.  To link a main account category to a main account, click **Link main accounts**. For more information, see [Link main accounts to main account categories](link-main-accounts-to-main-account-categories.md).
    
    We recommend that you link the main accounts to main account categories when you use Management Reporter for Microsoft Dynamics ERP. When you link main accounts to main account categories, you can use the default reports that are included with Management Reporter without any modifications. This can make it faster and easier to design and maintain reports. This feature is available only if cumulative update 6 or later for Management Reporter is installed.

## See also

[Link main accounts (form)](https://technet.microsoft.com/library/hh209475\(v=ax.60\))

  


