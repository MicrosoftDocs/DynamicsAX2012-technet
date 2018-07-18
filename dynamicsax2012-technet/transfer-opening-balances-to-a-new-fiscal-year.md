---
title: Transfer opening balances to a new fiscal year
TOCTitle: Transfer opening balances to a new fiscal year
ms:assetid: 941394d6-11e0-436d-ad53-b8061ae8e163
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa498391(v=AX.60)
ms:contentKeyID: 36941347
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Transfer opening balances to a new fiscal year 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Opening transactions** form to transfer opening balances for each account to a new fiscal year. You can modify the parameters for this process in the **General ledger parameters** form.


> [!IMPORTANT]
> <P>(ESP) For legal entities whose primary address is in Spain, the entries that are posted from the <STRONG>Opening sheets</STRONG> form are not deleted, even if the <STRONG>Delete close-of-year transactions during transfer</STRONG> check box is selected in the <STRONG>General ledger parameters</STRONG> form. However, if there is a repeated transfer of transactions, and the <STRONG>Delete close-of-year transactions during transfer</STRONG> check box is selected, all the entries are deleted.</P>




> [!NOTE]
> <P>If the <STRONG>Public Sector</STRONG> configuration key is selected, you must complete the following tasks to process year-end closing and opening for General ledger:</P>
> <UL>
> <LI>
> <P>Assign an account close type to the closing and opening accounts on the <STRONG>Main accounts</STRONG> list page. (Click <STRONG>General ledger</STRONG> &gt; <STRONG>Common</STRONG> &gt; <STRONG>Main accounts</STRONG>. Double-click a main account.)</P>
> <LI>
> <P>Set up posting definitions and transaction posting definitions. For more information, see <A href="set-up-posting-definitions.md">Set up posting definitions</A> and <A href="assign-posting-definitions-to-transaction-posting-types.md">Assign posting definitions to transaction posting types</A>.</P></LI></UL>



1.  Click **General ledger** \> **Periodic** \> **Fiscal year close** \> **Opening transactions**.

2.  In the **End date** field, select the closing date for the fiscal year that is being closed.
    

    > [!NOTE]
    > <P>If the <STRONG>Public Sector</STRONG> configuration key is selected, select the fiscal year that is being closed, and the periods through which balances will be used to create closing and opening entries.</P>



3.  (ITA) For legal entities whose primary address is in Italy, if the **Transaction date reference to competence date** field is selected in the **General ledger parameters** form, in the **Transaction date** field, enter the posting date when the legal entity gained knowledge of the transaction.

4.  For balance sheet accounts, select how to transfer the balances of main accounts.
    
      - Select **Closing-\>Opening** to transfer the balances automatically to the next fiscal year.
    
      - Select **Reset** to reset the balance accounts and manually create opening balances by using the **General journal** form.

5.  For balance sheet accounts, select the account to transfer the year-end information to.

6.  Select the **Use account for transfer of year-end result** check box to transfer all the year-end account balances to the main account that is specified in the **Main account for transfer of year-end result** field in the **Chart of accounts** form. (Click **General ledger** \> **Setup** \> **Chart of accounts** \> **Chart of accounts**.)
    

    > [!NOTE]
    > <P>If you have not defined an account in the <STRONG>Chart of accounts</STRONG> form, the main account that is specified in the <STRONG>Main account for transfer of year-end result</STRONG> field in the <STRONG>Main accounts - chart of accounts: %1</STRONG> form is used.</P>



7.  If you selected the **Voucher number must be filled in** check box in the **General ledger parameters** form, enter a voucher number.

8.  If the **Public Sector** configuration key is selected, select the **Select funds** check box and the funds that will be processed. To process all funds, clear the check box.

9.  If the **Public Sector** configuration key is selected, select the **Preview transactions** check box to view transactions before they are posted.

10. Select the **Print created transactions** check box to print a report of the year-end closing transactions that are created.

11. Click the **Financial dimensions** tab to select a dimension for the profit and loss transactions.

12. Select the **Transfer financial dimensions** check box to include financial dimensions on the opening transactions that are generated for the balance sheet accounts.

13. Close the profit and loss transactions for each financial dimension.
    
      - Select the **Close all** check box to move the main account balance to the transfer account, and to use the same combination of profit and loss account and financial dimension.
    
      - Select the main account to move all the main account balances to.

## See also

[Opening transactions (form)](https://technet.microsoft.com/en-us/library/aa572506\(v=ax.60\))

[Main accounts - chart of accounts (form)](https://technet.microsoft.com/en-us/library/hh209695\(v=ax.60\))

  


