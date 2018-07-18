---
title: (RUS) Create and post a budget journal for a fixed asset acquisition
TOCTitle: (RUS) Create and post a budget journal for a fixed asset acquisition
ms:assetid: e1039dc7-40d9-427c-90f5-2541b2abff96
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711710(v=AX.60)
ms:contentKeyID: 49388033
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Create and post a budget journal for a fixed asset acquisition 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Financial plans and current budgets can be created in the Fixed assets module using budget models. A budget model represents a collection of planned turnovers for specific accounts and periods.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Budgeting** \> **Setup** \> **Basic budgeting** \> **Budget models**.

2.  Press CTRL+N to create a new budget model.

3.  In the **Budget model** field, enter a number for the budget model.

4.  In the **Name** field, enter a name for the budget model.

5.  Press CTRL+S or close the form.
    

    > [!NOTE]
    > <P>For more information, see "Budget model (form)" and "About budget models" in the Applications and Business Processes Help.</P>



6.  Click **Fixed assets (Russia)** \> **Journals** \> **FA budget journal**.

7.  On the **Overview** tab, press CTRL+N to create a new journal.

8.  In the **Name** field, select a journal name.
    

    > [!NOTE]
    > <P>For more information, see "Journal names setup (form)" in the Applications and Business Processes Help.</P>



9.  Click **Lines** to open the **Journal voucher** form, where you can enter fixed asset budget transactions.

10. In the **Budget model** field, select the budget model.

11. In the **Accounting** field, view or modify the fixed asset value model.

12. In the **Transaction type** field, select **Putting into operation**.

13. In the **Date** field, view or modify the transaction date.

14. In the **Account type** field, view or modify the type of account.

15. In the **Account** field, select a fixed asset number.

16. In the **Transaction text** field, select a transaction text.

17. In the **Debit** or **Credit** field, enter a transaction amount.

18. In the **Offset account type** field, select the ledger account type.

19. In the **Offset account** field, select the ledger account number.
    

    > [!NOTE]
    > <P>If the posting profile is set up for this transaction, the <STRONG>Offset account</STRONG> field displays the account number automatically.</P>



20. Repeat steps 10 through 19 for each fixed asset transaction type.
    

    > [!NOTE]
    > <P>Click <STRONG>Putting into operation</STRONG> and <STRONG>Depreciation</STRONG> to create group acquisition and depreciation calculation transactions. Specify the transaction date and budget model when you create an acquisition transaction. Specify the transaction date, budget model, and value model for the transaction when you calculate depreciation.</P>



21. Click **Validate** \> **Validate** to verify the asset information in the journal.

22. Click **Post** \> **Transfer budgets** to transfer the transactions to the fixed asset budget.

23. Click **Post** \> **Transfer and update budgets** to transfer the transactions to the general ledger budget.

24. Press CTRL+S or close the form.

  


