---
title: (RUS) About tax accounting
TOCTitle: (RUS) About tax accounting
ms:assetid: 2fb4f71e-3963-46d1-aeca-f7e4a946f748
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn126120(v=AX.60)
ms:contentKeyID: 52075362
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) About tax accounting 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Legal entities must maintain separate tax records for business activities and general accounting. Accounting rules that are used to calculate tax for business activities differ from the rules that are used in general accounting. The tax base for each tax reporting period is calculated by using the tax accounting data.

The data from the following documents is used to generate a tax base:

  - Primary accounting documents

  - Analytic tax registers that systematize revenue and expenses for tax purposes

  - The tax base for the reporting period

The data from the preceding documents is also used to establish the accuracy of the following tax reports:

  - Profit tax and the receipt of a profit tax statement report

  - Assessed tax and the receipt of an assessed tax statement report
    

    > [!NOTE]
    > <P>Assessed tax is calculated by using the Russian accounting principles (RAP) value model.</P>



  - Value-added tax (VAT) and the receipt of a VAT statement report

In Microsoft Dynamics AX, tax registers are used to calculate the tax base. Each of the tax registers contains a set of figures that is used to calculate the tax base. The tax registers are grouped into expenses and revenue. The fundamental difference between tax registers and general accounting forms is that all figures on the register lines must be reconciled with the original document. This is done to confirm that the referenced expense or revenue is valid.

You must specify whether a transaction is an expense or revenue in the original documents, such as purchase orders, advance orders, employee pay records, fixed asset cards, and inventory journals. You must specify whether the transaction is an expense or revenue when you create inventory transactions and transactions that are related to suppliers, clients, and personnel.

## See also

[(RUS) About profit tax registers](rus-about-profit-tax-registers.md)

[(RUS) Set up profit tax registers](rus-set-up-profit-tax-registers.md)

[(RUS) Set up the expense and income codes for tax registers](rus-set-up-the-expense-and-income-codes-for-tax-registers.md)

[(RUS) View the register tree structure](rus-view-the-register-tree-structure.md)

[(RUS) Set up additional tax register parameters](rus-set-up-additional-tax-register-parameters.md)

[(RUS) Create a register using the wizard](rus-create-a-register-using-the-wizard.md)

  


