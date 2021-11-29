---
title: (RUS) Create a ledger journal of amount difference transactions
TOCTitle: (RUS) Create a ledger journal of amount difference transactions
ms:assetid: 4c4743b6-2b6c-4816-a58f-b244d2e0ff76
ms:mtpsurl: https://technet.microsoft.com/library/JJ665357(v=AX.60)
ms:contentKeyID: 49387445
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Create a ledger journal of amount difference transactions 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Before you can create a ledger journal of amount difference transactions, you must set up and calculate the **Amount difference in tax accounting** register. For more information, see [(RUS) Set up a register for amount differences in tax accounting](rus-set-up-a-register-for-amount-differences-in-tax-accounting.md) [(RUS) Calculate the amount difference in the tax accounting register](rus-calculate-the-amount-difference-in-the-tax-accounting-register.md).


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **General ledger** \> **Journals** \> **Tax register journal**. click **Lines**.

2.  Select the **Amount difference in tax accounting** journal line, and then click **Register calculation** \> **Calculate current** to calculate the register.
    

    > [!NOTE]
    > <P>After calculation, the status of the register is displayed as <STRONG>Calculated</STRONG> in the <STRONG>Status</STRONG> field.</P>



3.  After calculating the register, select the **Approved** check box to approve the register.

4.  In the **Employee** field, view or modify the code of the employee who approved the register.

5.  Press CTRL+S or close the form to return to the **Tax register journal** form.

6.  In the **Tax register journal** form, press CTRL+S to save the settings, and then click **Ledger journal** \> **Amount difference**.

7.  In the **Journal** form, click **Create** \> **Create journal** to create a new journal with a line for each calculated amount difference.
    

    > [!NOTE]
    > <P>To view the created journal lines, click <STRONG>Lines</STRONG>.</P>



8.  Click **Post** \> **Post** to post the transactions with amount difference in the specified ledger accounts.
    

    > [!NOTE]
    > <P>In the <STRONG>Journal</STRONG> form, the <STRONG>Posted</STRONG> field is activated after the journal is posted.</P>



9.  Press CTRL+S or close the form.

## See also

[(RUS) Register journal lines (form)](https://technet.microsoft.com/library/jj839663\(v=ax.60\))

  


