---
title: (RUS) Set up a register for warehoused items
TOCTitle: (RUS) Set up a register for warehoused items
ms:assetid: af4e27ad-254f-40ef-978c-3815f400d392
ms:mtpsurl: https://technet.microsoft.com/library/JJ839683(v=AX.60)
ms:contentKeyID: 50396829
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- warehouse
- set up a register
- warehoused items
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up a register for warehoused items 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The **Warehoused items** register contains the following information:

  - Movement of raw materials and other materials into production

  - Item disposals

  - Items that are returned to the vendor

  - Item write-offs

<!-- end list -->

1.  Click **General ledger** \> **Setup** \> **Profit tax** \> **Registers**.

2.  Create a register, and then in the **Register type** field, select **Warehoused items**.

3.  In the **Register code** field, enter an identification code for the register.

4.  In the **Register name** field, update the register name, if required.

5.  In the **Period types** field, select the period that the register is generated for, from the following options:
    
      - **Months** – The register is generated for a month.
    
      - **Quarter** – The register is generated for a quarter.
    
      - **Half-Yearly** – The register is generated for a half year.
    
      - **Years** – The register is generated for a calendar year.
    
      - **Nine months** – The register is generated for a period of nine months.

6.  Click the **Hide** FastTab.

7.  In the **Available fields:** list, select the fields to exclude from the register, and then move those fields to the **Selected fields** list.

8.  In the **Selected fields** list, select the check box for each field to exclude from the register.

9.  Click the **Parameters** FastTab, and then in the **Value** field, enter a parameter value. This value is used as a delimiter to separate the values of inventory dimensions in the register field.

10. Click **Expense codes**, and then click **New** to create an expense code.

11. In the **Expense code** field, select the expense code that is set up for warehoused items.

12. Click the **Exceptions** FastTab, and then click **Add** to specify the ledger accounts to exclude from the register.

13. In the **Valid for** field, select the ledger accounts to exclude from the register, from the following options:
    
      - **Table** – The vouchers from the ledger accounts that are selected in the **Debit account** and **Credit account** fields are excluded from the register.
    
      - **Group** – The vouchers from the ledger accounts in the group that is selected in the **Debit account** and **Credit account** fields are excluded from the register.
    
      - **All** – The vouchers from all ledger accounts are excluded from the register.

14. In the **Debit account** and **Credit account** fields, select the codes of the ledger accounts to exclude from the register.

15. Click the **Exception dimension** FastTab, and then select the dimensions to exclude from the register.

## See also

[(RUS) Tax registers (form)](https://technet.microsoft.com/library/jj853195\(v=ax.60\))

[(RUS) Calculate registers](rus-calculate-registers.md)

  


