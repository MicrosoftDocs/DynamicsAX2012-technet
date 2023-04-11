---
title: (RUS) Set up a register for cash payment receipt
TOCTitle: (RUS) Set up a register for cash payment receipt
ms:assetid: 13166020-b196-4912-a4e9-370428e83a86
ms:mtpsurl: https://technet.microsoft.com/library/JJ711406(v=AX.60)
ms:contentKeyID: 49387225
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up a register for cash payment receipt 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



The **Cash payment receipt** register is created to combine cash inflow information for an enterprise in order to affiliate income that equally relates to current and future periods and vouchers that define the amount of future expenses.

You must set up account interval groups, create expense or income codes, and set up ledger accounts for the expense or income codes.


> [!NOTE]
> <P>For more information, see <A href="rus-set-up-account-interval-groups.md">(RUS) Set up account interval groups</A>, <A href="rus-set-up-the-expense-and-income-codes-for-tax-registers.md">(RUS) Set up the expense and income codes for tax registers</A>, and <A href="rus-set-up-the-ledger-accounts-for-expense-and-income-codes.md">(RUS) Set up the ledger accounts for expense and income codes</A>.</P>



1.  Click **General ledger** \> **Setup** \> **Profit tax** \> **Registers**.

2.  Press CTRL+N to create a new line.

3.  In the **Register type** field, select **Cash payment receipt**.

4.  In the **Register code** field, enter an identification code for the register.

5.  In the **Register name** field, modify the name of the register, if necessary.

6.  In the **Period types** field, select the type of time period for which the register is created.

7.  Click the **Hide** tab, and move any fields that you want to hide in the register from **Available fields** to **Selected fields**.

8.  In **Selected fields**, select the check box for the register fields to be hidden.

9.  Click **Expense codes** to open the **Expense code setup** form.

10. In the left pane, press CTRL+N to create a record that specifies the expense codes that correspond to the **Cash payment receipt** register.

11. In the right pane, click the **Exceptions** tab and select the ledger accounts whose transactions should not be displayed in the register.

12. Click the **Exception dimension** tab and select the dimension codes for which vouchers should not be displayed in the register.

13. Press CTRL+S or close the form.

## See also

[(RUS) Tax registers (form)](https://technet.microsoft.com/library/jj853195\(v=ax.60\))

[(RUS) Expense code setup (form)](https://technet.microsoft.com/library/jj839690\(v=ax.60\))

  


