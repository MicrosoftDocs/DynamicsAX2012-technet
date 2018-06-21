---
title: (RUS) Set up a register for amount differences in tax accounting
TOCTitle: (RUS) Set up a register for amount differences in tax accounting
ms:assetid: 4d9004da-0d0e-4365-a7df-a30fbbe43393
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ911376(v=AX.60)
ms:contentKeyID: 52075380
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- set up a register
- amount differences
- tax accounting
---

# (RUS) Set up a register for amount differences in tax accounting [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The **Amount difference in tax accounting** register is used to calculate amount differences in tax accounting, and to summarize expenses and revenues that are used in the calculation of the tax differences register. Transactions that have amount differences are processed in the ledger journal based on the amounts in the **Amount difference in tax accounting** register.

1.  Click **General ledger** \> **Setup** \> **Profit tax** \> **Registers**.

2.  Create a register, and then in the **Register type** field, select **Amount difference in tax accounting**.

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

9.  Click the **Parameters** FastTab, and then in the **Value** field, select **Yes** or **No** to specify whether amount difference is calculated for prepayments.

## See also

[(RUS) Tax registers (form)](https://technet.microsoft.com/en-us/library/jj853195\(v=ax.60\))

[(RUS) Calculate registers](rus-calculate-registers.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

