---
title: (RUS) Set up a register for outlays - other unrealized
TOCTitle: (RUS) Set up a register for outlays - other unrealized
ms:assetid: 118de812-6ba7-4925-8f05-6f3733bf6125
ms:mtpsurl: https://technet.microsoft.com/library/JJ839650(v=AX.60)
ms:contentKeyID: 50396798
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- other unrealized outlays
- outlays
- unrealized outlay
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up a register for outlays - other unrealized 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The **Outlays - other unrealized** register is calculated based on the general ledger transactions or expenses that are entered manually in the register.

1.  Click **General ledger** \> **Setup** \> **Profit tax** \> **Registers**.

2.  Create a register, and then in the **Register type** field, select **Outlays - other unrealized**.

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

9.  In the **Expense code** field, select the expense code that is set up for warehoused items.

10. On the **Exceptions** FastTab, click **Add** to specify the ledger accounts to exclude from the register.

11. In the **Valid for** field, select the ledger accounts to exclude from the register, from the following options:
    
      - **Table** – The vouchers from the ledger accounts that are selected in the **Debit account** and **Credit account** fields are excluded from the register.
    
      - **Group** – The vouchers from the ledger accounts in the group that is selected in the **Debit account** and **Credit account** fields are excluded from the register.
    
      - **All** – The vouchers from all of the ledger accounts are excluded from the register.

12. In the **Debit account** and **Credit account** fields, select the codes of the ledger accounts or groups to exclude from the register.

13. On the **Exception dimension** FastTab, select the dimensions to exclude from the register.

## See also

[(RUS) Tax registers (form)](https://technet.microsoft.com/library/jj853195\(v=ax.60\))

[(RUS) Calculate registers](rus-calculate-registers.md)

  


