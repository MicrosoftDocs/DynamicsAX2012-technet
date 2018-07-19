---
title: (RUS) Set up a register for goods issued
TOCTitle: (RUS) Set up a register for goods issued
ms:assetid: c1ab0765-2471-437e-b30e-26fa9a21802c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ839687(v=AX.60)
ms:contentKeyID: 50396833
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- register
- goods issued
- goods issued register
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up a register for goods issued 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The **Goods issued** register displays the income from the issue of items, services, and rights, and is generated based on the sales price. The register includes information about taxpayer asset disposal vouchers. The register also includes information about the work, services, and rights that the taxpayer performs. The register is used to calculate the revenue that is generated when the work, services, and rights are performed.

1.  Click **General ledger** \> **Setup** \> **Profit tax** \> **Registers**.

2.  Create a register, and then in the **Register type** field, select **Goods issued**.

3.  In the **Register code** field, enter an identification code for the register.

4.  In the **Register name** field, update the register name, if required.

5.  In the **Period types** field, select the period that the register is generated for, from the following options:
    
      - **Months** – The register is generated for a month.
    
      - **Quarter** – The register is generated for a quarter.
    
      - **Half-Yearly** – The register is generated for a half year.
    
      - **Years** – The register is generated for a calendar year.
    
      - **Nine months** – The register is generated for a period of nine months.

6.  Click the **Hide** FastTab.

7.  In the **Available fields:** list, select the fields to exclude from the register, and move those fields to the **Selected fields** list.

8.  In the **Selected fields** list, select the check box for each field to exclude from the register.

9.  Click **Expense codes**, and then click **New** to create an expense code.

10. In the **Expense code** field, select the expense code that is set up for items that are issued.

11. Click the **Exceptions** FastTab, and then click **Add** to specify the ledger accounts to exclude from the register.

12. In the **Valid for** field, select the ledger accounts to exclude from the register, from the following options:
    
      - **Table** – The vouchers of the ledger accounts that are selected in the **Debit account** and **Credit account** fields are excluded from the register.
    
      - **Group** – The vouchers of the ledger accounts in the group that is selected in the **Debit account** and **Credit account** fields are excluded from the register.
    
      - **All** – The vouchers of the ledger accounts that are selected in the **Debit account** and **Credit account** fields are excluded from the register.

13. In the **Debit account** and **Credit account** fields, select the codes of the ledger accounts to exclude from the register.

14. Click the **Exception dimension** FastTab, and then select the dimensions to exclude from the register.

## See also

[(RUS) Tax registers (form)](https://technet.microsoft.com/en-us/library/jj853195\(v=ax.60\))

[(RUS) Calculate registers](rus-calculate-registers.md)

  


