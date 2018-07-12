---
title: (RUS) Calculate the accounts receivable bad debt reserve movement register
TOCTitle: (RUS) Calculate the accounts receivable bad debt reserve movement register
ms:assetid: 86aa155f-4a29-4176-8347-3db268eb38f3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678445(v=AX.60)
ms:contentKeyID: 49387674
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Calculate the accounts receivable bad debt reserve movement register 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You must set up the **Accounts receivable - bad debt reserve movement** register in the **Tax registers** form and create a tax register journal before calculating the register.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>




> [!NOTE]
> <P>For more information, see <A href="rus-set-up-a-register-for-accounts-receivable-bad-debt-reserve-movement.md">(RUS) Set up a register for accounts receivable bad debt reserve movement</A>.</P>



1.  Click **General ledger** \> **Journals** \> **Tax register journal**.

2.  Press CTRL+N to create a new register journal and enter the required details. You can create a new journal only if all the previous journals are approved.
    

    > [!NOTE]
    > <P>For more information, see <A href="rus-create-a-tax-register-journal.md">(RUS) Create a tax register journal</A> and <A href="rus-approve-the-register.md">(RUS) Approve the register</A>.</P>



3.  Click **Lines** to open the **Register journal lines** form. Register journal lines are created with the status as **Not calculated**.

4.  Select the **Accounts receivable - bad debt reserve movement** journal line.

5.  Click **Register calculation** \> **Calculate current** to calculate the register.

6.  Click **OK** to confirm the calculation. After calculation, the status of the register is displayed as **Calculated** in the **Status** field.
    

    > [!NOTE]
    > <P>To view the details in the register lines after calculation, click <STRONG>Register lines</STRONG> to open the <STRONG>Register lines</STRONG> form.</P>



7.  Select the **Approved** check box to approve the register.

8.  In the **Employee** field, view or modify the code of the employee who approved the register.

9.  Press CTRL+S or close the form.

## See also

[(RUS) Tax register journal (form)](https://technet.microsoft.com/en-us/library/jj856114\(v=ax.60\))

[(RUS) Register journal lines (form)](https://technet.microsoft.com/en-us/library/jj839663\(v=ax.60\))

[(RUS) Register lines (form)](https://technet.microsoft.com/en-us/library/jj943751\(v=ax.60\))

[(RUS) Calculate registers](rus-calculate-registers.md)

[(RUS) Recalculate registers](rus-recalculate-registers.md)

[(RUS) Tax registers (form)](https://technet.microsoft.com/en-us/library/jj853195\(v=ax.60\))

  


