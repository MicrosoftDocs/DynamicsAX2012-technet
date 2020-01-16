---
title: (RUS) Set up a register for the calculation of constant tax differences
TOCTitle: (RUS) Set up a register for the calculation of constant tax differences
ms:assetid: af149ef9-8141-429d-83b2-882b0ceec396
ms:mtpsurl: https://technet.microsoft.com/library/JJ839685(v=AX.60)
ms:contentKeyID: 50396831
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- register
- constant tax
- set up register
- tax differences
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up a register for the calculation of constant tax differences 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

To show the amounts of permanent and temporary tax differences in an account, you must set up and calculate tax liabilities and asset calculation registers. Based on the calculations, transactions are entered in the general ledger. The **Calculation of constant tax differences** register is used to calculate constant tax differences based on the following registers:

  - **Incomes and expenses that do not influence the tax base**

  - **Standard expenses in current period**

  - **Amount difference in tax accounting**

  - **Exchange adjustment in accounting**

  - **Exchange adjustment in tax accounting**

  - **Depreciation bonus recovery**

<!-- end list -->

1.  Click **General ledger** \> **Setup** \> **Profit tax** \> **Registers**.

2.  Create a register, and then in the **Register type** field, select **Calculation of constant tax differences**.

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

## See also

[(RUS) Tax registers (form)](https://technet.microsoft.com/library/jj853195\(v=ax.60\))

[(RUS) Calculate registers](rus-calculate-registers.md)

  


