---
title: (RUS) Calculate land tax registers
TOCTitle: (RUS) Calculate land tax registers
ms:assetid: 30800d8e-f1db-479c-9830-7874ba3a69f1
ms:mtpsurl: https://technet.microsoft.com/library/JJ665251(v=AX.60)
ms:contentKeyID: 49387340
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Calculate land tax registers 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The total land tax to be paid to the budget at the end of the tax period is determined as the difference between the tax total and the totals of advance tax payments that were estimated over the course of the tax period individually for every tax base. The tax and advance payments totals are calculated in the tax register journal.

To create a land tax declaration, these registers must be calculated and approved in the journal:

  - **Land tax - ground areas** – This register calculates the land tax amount for every fixed asset, based on the cadastral value with the tax benefits, coefficients, and land rates taken into account.

  - **Land tax** – This register summarizes the data and calculates the land tax amount based on RCOAD codes (National Classifier of Administrative and Territorial Subdivisions), budget classification codes (BCC), and land tax codes.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Fixed assets (Russia)** \> **Journals** \> **Tax register journal**.

2.  Press CTRL+N to create a new journal.

3.  In the **Journal batch number** field, the unique tax registry journal number. By default, this field displays the number from the number sequence set up in the **Fixed Asset Parameters** form.

4.  In the **Period type**, **Period number**, and **Years** fields, specify the period for which the journal will be created.

5.  Click **Lines** to create the periodic register journal lines.

6.  Click **Yes** in the **Register journal generation** dialog box to create register lines with the **Not Calculated** status.

7.  Select the **Land Tax - ground areas** register line, and then click **Calculate current**.

8.  Select the **Land tax** register line, and then click **Calculate current**.
    

    > [!NOTE]
    > <P>After calculation, the status of the registers is displayed as <STRONG>Calculated</STRONG> in the <STRONG>Status</STRONG> field.</P>



9.  Select the **Approved** check box to approve the register.

10. In the **Worker** field, select the code of the employee who approved the register.
    

    > [!NOTE]
    > <P>When you create the journal for a year in the <STRONG>Land tax</STRONG> register, the total of the advance payments that were paid for the previous accounting periods is calculated. If the journals for these periods were not created, the advance payments total for the previous accounting periods can be entered manually.</P>



## See also

[(RUS) Register journal lines (form)](https://technet.microsoft.com/library/jj839663\(v=ax.60\))

  


