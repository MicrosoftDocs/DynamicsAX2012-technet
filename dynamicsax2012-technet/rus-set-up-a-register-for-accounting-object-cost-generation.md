---
title: (RUS) Set up a register for accounting object cost generation
TOCTitle: (RUS) Set up a register for accounting object cost generation
ms:assetid: cbe5e35b-cb1f-4a10-9b88-ef25e84c901e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ923589(v=AX.60)
ms:contentKeyID: 53382722
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- set up a register
- accounting object
- accounting object cost generation
---

# (RUS) Set up a register for accounting object cost generation [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The **Goods cost calculation** register is used to calculate the cost of items. Records are produced in the register for each occurrence of an account object. An account object can be one of the following objects:

  - A purchase

  - A receipt from the production of items, services, and raw materials

  - An acquisition of fixed assets (FAs) and intangible assets (IAs)

The **Goods cost calculation** register displays records of all materials, items, raw materials, FAs, and IAs that are accepted for accounting for a specific accounting period. Charges for purchases that are distributed by item are specified on separate lines in the register, and these charges are accounted on the invoice total line in the register. If the acquisition cost of an FA or IA differs from the value that is paid for the FA or IA, a corrective line is created in the register to identify the cost difference.

1.  Click **General ledger** \> **Setup** \> **Profit tax** \> **Registers**.

2.  Create a register, and then in the **Register type** field, select **Goods cost calculation**.

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

## See also

[(RUS) Tax registers (form)](https://technet.microsoft.com/en-us/library/jj853195\(v=ax.60\))

[(RUS) Calculate registers](rus-calculate-registers.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

