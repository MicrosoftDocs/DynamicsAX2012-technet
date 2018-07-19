---
title: (RUS) Set up the ledger accounts for expense and income codes
TOCTitle: (RUS) Set up the ledger accounts for expense and income codes
ms:assetid: dff72dd6-4ce3-48fc-a311-5dbe5396264f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711691(v=AX.60)
ms:contentKeyID: 49388013
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up the ledger accounts for expense and income codes 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can set up a ledger account for transaction data to be transferred into a specified income or expense code.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **General ledger** \> **Setup** \> **Expense codes** \> **Expense codes**. Select an expense code, and then click **Ledger account setup**.

2.  Press CTRL+N to create a new line.

3.  In the **Valid for** field, select from the following options:
    
      - **Table** – The voucher in the table that is defined in the **Debit account** and **Credit account** fields should be displayed in the accounts.
    
      - **All** – The voucher in all expense groups should be displayed in the accounts that are defined in the **Debit account** and **Credit Account** fields.
    
      - **Group** – The voucher in the ledger account that is defined in the **Debit account** and **Credit account** fields should be displayed in the accounts.

4.  In the **Debit account** field, select the debit account number or interval group.

5.  In the **Credit account** field, select the credit account number or interval group.

6.  Click the **Dimensions** tab to set up the financial dimension codes in the **Department**, **Cost center**, and **Purpose** fields that the transaction data will be transferred to using the specified expense or income code.
    

    > [!NOTE]
    > <P>If the financial dimension codes are highlighted in the expense or income code settings, the general ledger account codes and the dimension codes must match in order to transfer a transaction into the specified expense or income code.</P>



7.  Press CTRL+S or close the form.

## See also

[(RUS) Expense code and ledger relation (form)](https://technet.microsoft.com/en-us/library/jj839671\(v=ax.60\))

[(RUS) Set up account interval groups](rus-set-up-account-interval-groups.md)

[(RUS) Create expense and income codes](rus-create-expense-and-income-codes.md)

[(RUS) Synchronize the directory of expense and income codes](https://technet.microsoft.com/en-us/library/jj665243\(v=ax.60\))

  


