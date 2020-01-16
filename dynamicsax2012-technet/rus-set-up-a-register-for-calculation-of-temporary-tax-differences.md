---
title: (RUS) Set up a register for calculation of temporary tax differences
TOCTitle: (RUS) Set up a register for calculation of temporary tax differences
ms:assetid: e382f500-b1b8-4a26-8363-f6eec55f2c18
ms:mtpsurl: https://technet.microsoft.com/library/JJ839692(v=AX.60)
ms:contentKeyID: 50396838
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- set up a register
- tax difference
- temporary tax differences
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up a register for calculation of temporary tax differences 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Temporary tax differences can occur if expenses or revenues generate a profit in one reporting period and a taxable base in the next reporting period. This scenario causes a deferred tax on profits. These temporary differences are classified as either deductible or taxable, depending on the effect on taxable profits. Deferred tax on profit is considered either a deferred tax asset or a deferred tax liability.

1.  Click **General ledger** \> **Setup** \> **Profit tax** \> **Registers**.

2.  Create a register, and then in the **Register type** field, select **Calculation of temporary tax differences**.

3.  In the **Register code** field, enter an identification code for the register.

4.  In the **Register name** field, update the register name, if required.

5.  In the **Period types** field, select the period that the register is generated for, from the following options:
    
      - **Months** – The register is generated for a month.
    
      - **Quarter** – The register is generated for a quarter.
    
      - **Half-Yearly** – The register is generated for a half year.
    
      - **Years** – The register is generated for a calendar year.
    
      - **Nine months** – The register is generated for a period of nine months.

6.  Click the **Hide** FastTab.

7.  In the **Available fields:** list, select the fields to exclude from the register, and move them those fields to the **Selected fields** list.

8.  In the **Selected fields** list, select the check box for each field to exclude from the register.

## See also

[(RUS) Tax registers (form)](https://technet.microsoft.com/library/jj853195\(v=ax.60\))

[(RUS) Calculate registers](rus-calculate-registers.md)

  


