---
title: (RUS) Calculate transport tax registers
TOCTitle: (RUS) Calculate transport tax registers
ms:assetid: ca6df6a7-e649-4366-b4bd-3c1ded4344c3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711613(v=AX.60)
ms:contentKeyID: 49387937
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- calculate
- Russia
- transport tax
---

# (RUS) Calculate transport tax registers 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Tax register journal** form to calculate the total tax amount and the advance tax payments that are required. The calculation of the tax base for vehicles uses the following criteria:

  - Engine power measured in horsepower

  - Jet thrust measured in kilograms

  - Gross tonnage measured in vessel tons

All fixed assets for which the cards contain a transport tax code and are of the **Vehicle** asset type are included in the transport tax calculation. If the fixed asset is written off or sold during the accounting period, the tax calculation uses data for the month in which legal registration and removal from the register occurred.

Before you can create a transport tax declaration, the following registers must be calculated and approved in the journal:

  - **Vehicle - tax calculation** – Tax is calculated in this register for each fixed asset, based on the tax code settings, tax benefits, service period, and tax base. To determine the transport tax base for a vehicle, you must obtain summarized accounting data from each independent subdivision of the legal entity that maintains its own balance sheet.

  - **Transport tax** – Tax is calculated for each Russian Classification of Objects of Administrative Division (RCOAD) code of the tax code.

<!-- end list -->

1.  Click **Fixed assets (Russia)** \> **Journals** \> **Tax register journal**.

2.  Create a new journal.

3.  In the **Journal batch number** field, enter the unique number of the tax register journal.

4.  In the **Period types**, **Period number**, and **Years** fields, indicate the period that the journal is created for.

5.  Select the **Vehicle - tax calculation** register line, and then click **Calculate current**.

6.  Select the **Transport tax** register line, and then click **Calculate current**.
    

    > [!NOTE]
    > <P>After calculation, the status of the registers is set to <STRONG>Calculated</STRONG> in the <STRONG>Status</STRONG> field.</P>



7.  Select the **Approved** check box to approve the register.

8.  In the **Worker** field, view or modify the code of the employee who approved the register.

9.  Click **Register lines** to view the register lines after the calculation is completed.

When you create a journal in the transport tax register for the accounting year, the advance payment total that was paid for the previous accounting periods is calculated. If the journals for those periods do not exist, the advance payment total for the previous accounting periods can be entered manually.

## See also

[(RUS) Tax register journal (form)](https://technet.microsoft.com/en-us/library/jj856114\(v=ax.60\))

[(RUS) Register journal lines (form)](https://technet.microsoft.com/en-us/library/jj839663\(v=ax.60\))

[(RUS) Set up the calculation of transport tax](rus-set-up-the-calculation-of-transport-tax.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

