---
title: (RUS) Calculate registers
TOCTitle: (RUS) Calculate registers
ms:assetid: eedba38f-fb1c-4f38-b38b-58cf64025947
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678588(v=AX.60)
ms:contentKeyID: 49388070
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Calculate registers 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Before you calculate a register, you must enter all primary documents for the reporting period, perform the inventory closing process, and calculate the exchange adjustment.

Before you can calculate the **Calculation of constant tax differences** register, you must calculate the following registers:

  - **Incomes and expenses that do not influence the tax base**

  - **Standard expenses in current period**

  - **Amount difference in tax accounting**

  - **Exchange adjustment in accounting**

  - **Exchange adjustment in tax accounting**

  - **Depreciation bonus recovery**

<!-- end list -->

1.  Click **General ledger** \> **Journals** \> **Tax register journal**.
    
    –or–
    
    Click **Fixed assets (Russia)** \> **Journals** \> **Tax register journal**.

2.  Press CTRL+N to create a tax register journal, and then in the **Journal batch number** field, enter a batch number for the journal.
    

    > [!NOTE]
    > <P>If there are existing tax register journals, you must approve all the journals before you can create a new tax register journal. To approve journals, in the <STRONG>Register journal lines</STRONG> form, select the <STRONG>Approved</STRONG> check box for each register line.</P>



3.  In the **Period types** field, select the period that the tax register journal is created for, from the following options:
    
      - **Months** – The tax register journal is generated for a month.
    
      - **Quarter** – The tax register journal is generated for a quarter.
    
      - **Half-Yearly** – The tax register journal is generated for a half year.
    
      - **Years** – The tax register journal is generated for a calendar year.
    
      - **Nine months** – The tax register journal is generated for a period of nine months.

4.  Click **Lines**.

5.  Click **Current register calculation.** to calculate the selected register.
    
    –or–
    
    Click **Calculate all** to calculate all the registers.

6.  Click **OK** to confirm the calculation. In the **Register journal lines** form, the status of the register is updated to **Calculated**.
    

    > [!NOTE]
    > <P>After the register calculation is completed, click <STRONG>Register lines</STRONG> to view the details of the register lines.</P>



7.  Select the **Approved** check box to approve the register calculation.

8.  In the **Worker** field, select the name of the employee who approves the register.

## See also

[(RUS) Register journal lines (form)](https://technet.microsoft.com/en-us/library/jj839663\(v=ax.60\))

[(RUS) Recalculate registers](rus-recalculate-registers.md)

[(RUS) Tax registers (form)](https://technet.microsoft.com/en-us/library/jj853195\(v=ax.60\))

  


