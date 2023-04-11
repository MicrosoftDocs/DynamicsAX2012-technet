---
title: (RUS) Create expense and income codes
TOCTitle: (RUS) Create expense and income codes
ms:assetid: d85d063f-1d86-4434-8d53-92aa77a00886
ms:mtpsurl: https://technet.microsoft.com/library/JJ923595(v=AX.60)
ms:contentKeyID: 52075438
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Create expense and income codes 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Income and expense codes are saved in a hierarchical directory of revenue and expenses. This hierarchical structure enables revenue and expenses to be grouped according to the lines of the profit tax statement, so that the directory contains all revenue and expense codes that are used in tax reporting.

The turnover for expense or income codes in the upper level is determined by the turnover for expense or income codes in the lower levels. The same method that is used to calculate the tax return is used to calculate turnover for the expense or income coeds.

You can create expense or income codes in either the expense codes directory or the dimensions directory. An entry should be made in one of these directories, and an identical entry should be made by using the synchronization function.

1.  Click **General ledger** \> **Setup** \> **Expense codes** \> **Expense codes**.

2.  In the **Expense and income codes** form, press CTRL+N to create a new line.

3.  In the **Expense code** field, enter an expense or income code.
    

    > [!NOTE]
    > <P>The numbering of the revenue and expense codes must follow the hierarchical structure.</P>



4.  In the **Name** field, enter a description of the expense or income type.

5.  On the **General** FastTab, in the **Short description** field, enter a description of the expense or income code.

6.  In the **Code type** field, select the type of code that represents the expense or income.

7.  Select the **Direct** check box to define the type of accounting expense for direct tax.

8.  In the **Parent code** field, select the parent expense or income code if the specified code is a child code.

9.  In the **Sales tax code** field, select the value that corresponds to the profit tax. The profit tax is used to calculate the Deferred Tax Liability (DTL) and Deferred Tax Asset (DTA) according to the specified expense code.
    

    > [!NOTE]
    > <P>The <STRONG>Name</STRONG> field displays the name that is applied for the sales tax code.</P>



10. Select the **Locked** check box to prevent the selected expense or income code from being synchronized with the dimension code.

11. Click the **Set up** FastTab to select the registers that are used to calculate the totals.
    

    > [!NOTE]
    > <P>You cannot select registers for parent expense or income codes.</P>



12. In the **Available registers** field, select the registers that are used to calculate the totals. Then click the left arrow button to move these registers to the **Selected registers** field.

13. Click **Default** to set the registers for the expense or income codes as defaults. Select one of the following options:
    
      - **Default** – Set up the registers for the selected expense or income code. Data from the selected code is used to calculate the totals.
    

    > [!NOTE]
    > <P>These registers are selected if the specified expense or income code, or its parent code, is selected when you set up the register. These registers are also selected if the specified expense or income code, or its parent code, was used when you set up a subsequent calculation of standard expenses.</P>

    
      - **By default - all** – Set up the registers for all expense or income codes. Data from all codes is used to calculate the totals.

14. Click **Ledger account setup** to open the **Expense code and ledger relation** form and set up expense code relations with a ledger account.

15. Click **Tree view** to view the hierarchy of the registers in a tree structure.

## See also

[(RUS) Expense and income codes (form)](https://technet.microsoft.com/library/jj923268\(v=ax.60\))

[(RUS) Set up account interval groups](rus-set-up-account-interval-groups.md)

[(RUS) Synchronize the directory of expense and income codes](https://technet.microsoft.com/library/jj665243\(v=ax.60\))

  


