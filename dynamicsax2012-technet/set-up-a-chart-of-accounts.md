---
title: Set up a chart of accounts
TOCTitle: Set up a chart of accounts
ms:assetid: f397b95f-e662-4204-be6a-8f40792620ec
ms:mtpsurl: https://technet.microsoft.com/library/Hh227530(v=AX.60)
ms:contentKeyID: 36059980
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- chart of accounts
- set up a chart of accounts
- shared chart of accounts
audience: Application User
ms.search.region: Global
---

# Set up a chart of accounts 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Chart of accounts** form to set up a chart of accounts. You can create main accounts for the chart of accounts.

1.  Click **General ledger** \> **Setup** \> **Chart of accounts** \> **Chart of accounts**.

2.  Click **New**. In the **Chart of accounts** field, enter a name for the chart of accounts.

3.  Enter a description.

4.  You can enter a format mask for a main account to create a structure that is used when main accounts are created for the chart of accounts.
    
    You can enter characters that remain the same for each main account, such as letters or a hyphen. You also can enter number signs (\#) and ampersands (&) as placeholders for letters and numbers that will change every time that a main account is created. Use a number sign (\#) as a placeholder for a number and an ampersand (&) as a placeholder for a letter.
    
    **Example**
    
    To limit the main account to the letters CC, a hyphen, and three numbers, you enter CC-\#\#\# as the format mask.

5.  On the **Main accounts** FastTab, click **New** to open the **Main accounts - chart of accounts: %1** form. To create a main account from a template, click **New from template**, select a template, and then click **Select**. For information about how to create main accounts, see [Create a main account](create-a-main-account.md). When you finish, close the form.

6.  The main account can be selected automatically, based on the first character that you enter for a main account. To set up automatic account selection, on the **Main accounts** FastTab, click **Automatic account type selection**. For more information, see [Automatic account type selection (form)](https://technet.microsoft.com/library/aa573049\(v=ax.60\)).

## See also

[Chart of accounts (form)](https://technet.microsoft.com/library/aa618234\(v=ax.60\))

  


