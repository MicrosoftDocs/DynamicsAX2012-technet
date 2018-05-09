---
title: Create a main account
TOCTitle: Create a main account
ms:assetid: cd0241ce-7191-4fe0-845a-3f92c4c8ba93
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa572680(v=AX.60)
ms:contentKeyID: 36059459
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- create a main account
---

# Create a main account 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Main accounts - chart of accounts: %1** form to create a main account. A main account is an account in the general ledger. It is used to record financial transactions, balances, or totals that pertain to assets, liabilities, revenues, expenses, and owner equity. For more information about main accounts, see [Main accounts - chart of accounts (form)](https://technet.microsoft.com/en-us/library/hh209695\(v=ax.60\)).

1.  Click **General ledger** \> **Setup** \> **Chart of accounts** \> **Chart of accounts**.

2.  Select a chart of accounts.

3.  On the **Main accounts** FastTab, click **New**.

4.  In the **Main account** field, enter an account number, and then enter an account name.

5.  In the **Main account type** field, select the type of main account. **Profit and loss** is the default value, unless you have defined the automatic selection of account type by prefix by using the **Automatic account type selection** form.

6.  If the main account type is any value other than **Total**, you can enter or select a category for the main account.

7.  If the main account type is **Reporting**, you can enter or select a reporting type.

8.  On the **Financial dimensions** FastTab, select **Fixed value** to specify that amounts for the selected main account are always posted to this financial dimension value. When the financial dimension is a valid segment in the account structure for the main account, amounts are posted to this financial dimension value, even if the journal entry or source document contains other default values or changes to the ledger account.
    

    > [!NOTE]
    > <P>To view the <STRONG>Financial dimensions</STRONG> FastTab, select <STRONG>Companies</STRONG> in the <STRONG>Select the level of main account to display</STRONG> field.</P>



9.  You can enter additional information in the other fields. For more information, see [Main accounts - chart of accounts (form)](https://technet.microsoft.com/en-us/library/hh209695\(v=ax.60\)).

## See also

[Chart of accounts (form)](https://technet.microsoft.com/en-us/library/aa618234\(v=ax.60\))

[Configure account structures (form)](https://technet.microsoft.com/en-us/library/hh227362\(v=ax.60\))

[Automatic account type selection (form)](https://technet.microsoft.com/en-us/library/aa573049\(v=ax.60\))

[Link main accounts (form)](https://technet.microsoft.com/en-us/library/hh209475\(v=ax.60\))

[Main account categories (form)](https://technet.microsoft.com/en-us/library/hh227632\(v=ax.60\))

[Main account categories and analysis cubes](main-account-categories-and-analysis-cubes.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

