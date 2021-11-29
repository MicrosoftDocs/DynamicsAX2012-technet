---
title: (RUS) Set up the expense and income codes for tax registers
TOCTitle: (RUS) Set up the expense and income codes for tax registers
ms:assetid: 64d41374-a3e4-46b4-9026-37681006df63
ms:mtpsurl: https://technet.microsoft.com/library/JJ665455(v=AX.60)
ms:contentKeyID: 49387542
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up the expense and income codes for tax registers 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **General ledger** \> **Setup** \> **Profit tax** \> **Registers**. and Click **Expense codes** to open the **Expense code setup** form.

2.  In the left section, press CTRL+N to create a new record.

3.  In the **Expense code** field, select the expense or income code.

4.  In the **Condition name** field, modify the description of the expense code if needed.

5.  In the right section, click the **Exceptions** tab, and then select the general ledger accounts whose transactions should not be displayed in the selected register.

6.  In the **Debit account** field, enter the debit account.

7.  In the **Credit account** field, enter the credit account.

8.  In the **Valid for** field, select from the following options:
    
      - **All** – The voucher on all expense groups is to be displayed in the accounts that are defined in the **Debit account** and **Credit Account** fields.
    
      - **Group** – The voucher on the group that is defined in the **Debit account** and **Credit account** fields should be displayed in the accounts.
    
      - **Table** – The voucher on the table that is defined in the **Debit account** and **Credit account** fields should be displayed in the accounts.

9.  Click the **Exception dimension** tab, and then select the dimension codes for which vouchers should not be displayed in the register.

10. Press CTRL+S or close the form.

## See also

[(RUS) Expense code setup (form)](https://technet.microsoft.com/library/jj839690\(v=ax.60\))

[(RUS) Set up the ledger accounts for expense and income codes](rus-set-up-the-ledger-accounts-for-expense-and-income-codes.md)

[(RUS) Tax registers (form)](https://technet.microsoft.com/library/jj853195\(v=ax.60\))

  


