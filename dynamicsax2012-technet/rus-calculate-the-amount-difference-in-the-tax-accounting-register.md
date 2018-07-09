---
title: (RUS) Calculate the amount difference in the tax accounting register
TOCTitle: (RUS) Calculate the amount difference in the tax accounting register
ms:assetid: 9b3321ae-05f1-457f-8dd1-c3cd1aa468fd
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678521(v=AX.60)
ms:contentKeyID: 49387750
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Calculate the amount difference in the tax accounting register [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can use the **Tax register journal** form to set up a register that is used for calculating the amount difference in tax accounting. You can then create a tax register journal before you calculate the register. The amount difference for prepayments in tax accounting is calculated separately in the general ledger. You must also specify whether the amount difference for prepayments that are generated from settlements must be calculated.


> [!NOTE]
> <P>The amount difference for prepayments is calculated only if you select <STRONG>Yes</STRONG> in the <STRONG>Value</STRONG> field for the <STRONG>Calculate amount difference for prepayments</STRONG> parameter on the <STRONG>Parameters</STRONG> FastTab in the <STRONG>Tax registers</STRONG> form.</P>



1.  Click **General ledger** \> **Journals** \> **Tax register journal**.

2.  Create a register journal, and enter the required details. You can create a new journal only if all the previous journals are approved.

3.  Click **Lines**. Register journal lines are created that have a status of **Not calculated**.

4.  Select the journal line to calculate the amount difference in tax accounting, and then click **Calculate current** to calculate the register.

5.  In the **Calculation of temporary tax differences** form, click **OK** to confirm the calculation. After the calculation is completed, the status of the register is displayed as **Calculated** in the **Status** field.
    

    > [!NOTE]
    > <P>To view the details on the register lines after the calculation, click <STRONG>Register lines</STRONG> to open the <STRONG>Exchange adjustment in accounting</STRONG> form.</P>



6.  Select the **Approved** check box to approve the register.

7.  In the **Worker** field, view or modify the identification code of the employee who approved the register.

## See also

[(RUS) Tax register journal (form)](https://technet.microsoft.com/en-us/library/jj856114\(v=ax.60\))

[(RUS) Register journal lines (form)](https://technet.microsoft.com/en-us/library/jj839663\(v=ax.60\))

[(RUS) Register lines (form)](https://technet.microsoft.com/en-us/library/jj943751\(v=ax.60\))

[(RUS) Calculate registers](rus-calculate-registers.md)

[(RUS) Recalculate registers](rus-recalculate-registers.md)

[(RUS) Tax registers (form)](https://technet.microsoft.com/en-us/library/jj853195\(v=ax.60\))

[(RUS) Set up calculation parameters for amount differences in tax accounting](rus-set-up-calculation-parameters-for-amount-differences-in-tax-accounting.md)

[(RUS) Approve the register](rus-approve-the-register.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

