---
title: (RUS) Set up a register for outlay - realized tax
TOCTitle: (RUS) Set up a register for outlay - realized tax
ms:assetid: 1db16c80-18a1-4d71-bd6e-c0fab7845ed5
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn126119(v=AX.60)
ms:contentKeyID: 52075354
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up a register for outlay - realized tax 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Tax expense registers contain all the taxes and duties grouped by tax type. Before you create a register for tax and duty accruals, which are accounted as expenses, you must set up the correspondence between tax codes, off-budget funds, and expense codes. For more information, see [(RUS) Set up tax correspondence with expense codes](rus-set-up-tax-correspondence-with-expense-codes.md) and [(RUS) Set up budget revenue codes for fixed asset taxes](rus-set-up-budget-revenue-codes-for-fixed-asset-taxes.md).

To process taxes on advertising, extraction of mineral resources, and usage of water resources, you must complete the following tasks:

  - Create expense codes. For more information, see [(RUS) Create expense and income codes](rus-create-expense-and-income-codes.md).

  - Set up account correspondence. For more information, see [(RUS) Activate corresponding mechanism for accounting transactions](rus-activate-corresponding-mechanism-for-accounting-transactions.md).

  - Enter the amount origin and cost price manually.

  - Set up the settlement periods for all taxes except value-added tax (VAT). For more information, see [Set up a sales tax settlement period](set-up-a-sales-tax-settlement-period.md).

  - Verify that the period that the taxes are applicable for is equal to the register period.

Before you create the tax expense register, you must create and close a sales and purchase book for the period that the register is created for, because VAT is calculated based on closed sales and purchase books. If the sales and purchase book is not created, or if the sales and purchase book is not closed for the register period, other taxes are calculated in the register.

1.  Click **General ledger** \> **Setup** \> **Profit tax** \> **Registers**.

2.  Create a register, and then in the **Register type** field, select **Outlay - realized tax**.

3.  In the **Register code** field, enter an identification code for the register.

4.  In the **Register name** field, update the register name, if required.

5.  In the **Period types** field, select the period that the register is generated for, from the following options:
    
      - **Months** – The register is generated for a month.
    
      - **Quarter** – The register is generated for a quarter.
    
      - **Half-Yearly** – The register is generated for a half year.
    
      - **Years** – The register is generated for a calendar year.
    
      - **Nine months** – The register is generated for a period of nine months.

6.  On the **Hide** FastTab, in the **Available fields:** list, select the fields to exclude from the register, and then move those fields to the **Selected fields** list.

7.  In the **Selected fields** list, select the check box for each field to exclude from the register.

8.  Click **Expense codes**, and then click **New** to create an expense code.

9.  In the **Expense code** field, select the expense code that is set up for the **Outlay - realized tax** register.

10. On the **Exceptions** FastTab, click **Add** to specify the ledger accounts to exclude from the register.

11. In the **Valid for** field, select the ledger accounts to exclude from the register, from the following options:
    
      - **Table** – The vouchers from the ledger accounts that are selected in the **Debit account** and **Credit account** fields are excluded from the register.
    
      - **Group** – The vouchers from the ledger accounts in the group that is selected in the **Debit account** and **Credit account** fields are excluded from the register.
    
      - **All** – The vouchers from all of the ledger accounts are excluded from the register.

12. In the **Debit account** and **Credit account** fields, select the ledger account codes or groups to exclude from the register.

13. On the **Exception dimension** FastTab, select the dimensions to exclude from the register.

## See also

[(RUS) Tax registers (form)](https://technet.microsoft.com/en-us/library/jj853195\(v=ax.60\))

[(RUS) Calculate registers](rus-calculate-registers.md)

  


