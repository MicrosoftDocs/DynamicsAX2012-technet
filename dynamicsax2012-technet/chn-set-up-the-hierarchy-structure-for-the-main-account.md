---
title: (CHN) Set up the hierarchy structure for the main account
TOCTitle: (CHN) Set up the hierarchy structure for the main account
ms:assetid: e979f334-b3d7-4a64-80ac-d42910e9f0d8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664147(v=AX.60)
ms:contentKeyID: 49384730
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: China (PRC)
---

# (CHN) Set up the hierarchy structure for the main account 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Companies in China create and maintain a chart of accounts in a hierarchical tree structure by setting up multiple levels for ledger accounts. You can create account numbers by using a format that indicates the number of levels in the ledger account. For example, to split a ledger account into two levels, you can use the account number format xxxx-yy. Here, the first four characters denote the first level, such as a cash account, and the last two characters denote the second level, such as a cash account in a different currency.

1.  Click **General ledger** \> **Setup** \> **Chart of accounts** \> **Chart of accounts**.

2.  Select an existing chart of accounts, or create a new chart of accounts. For more information, see [Set up a chart of accounts](set-up-a-chart-of-accounts.md).

3.  Click **Hierarchy setup** to open the **China main account hierarchy** form.
    

    > [!NOTE]
    > <P>This form is available only when the <STRONG>Chart of accounts</STRONG> form is empty.</P>



4.  On the **Main accounts hierarchy** FastTab, click **New**.

5.  In the **Maximum level** field, enter the maximum number of levels for the account tree hierarchy.

6.  In the **Separator** field, select the symbol that is used to separate the account levels. The separator symbol is used for display only.

7.  On the **Account number formats** FastTab, click **New**.

8.  In the **Length** field, enter the account format length for the new level. The combined length of all of the account levels must not exceed the maximum default length of 20 characters.

9.  In the **Level** field, specify the account number level. The number of levels must not exceed the maximum number of levels that is specified on the **Main accounts hierarchy** FastTab.

10. In the **Name** field, enter the name of the account level.

11. In the **Reference** field, select a chart of accounts for the account number format. The final account number format is displayed in the **Preview** field on the **Main accounts hierarchy** FastTab.

## See also

[(CHN) Main account hierarchy (form)](https://technet.microsoft.com/en-us/library/jj664039\(v=ax.60\))

[(CHN) Chart of accounts (modified form)](https://technet.microsoft.com/en-us/library/jj664101\(v=ax.60\))

[Chart of accounts (form)](https://technet.microsoft.com/en-us/library/aa618234\(v=ax.60\))

  


