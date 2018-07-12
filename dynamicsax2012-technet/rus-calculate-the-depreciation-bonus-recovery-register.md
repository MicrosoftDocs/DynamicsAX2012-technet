---
title: (RUS) Calculate the depreciation bonus recovery register
TOCTitle: (RUS) Calculate the depreciation bonus recovery register
ms:assetid: a2adec1b-ad1e-4ce2-818d-62c00f510b0e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ839680(v=AX.60)
ms:contentKeyID: 50396826
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- (RUS)
- Forms.RTax25RegisterJournalTable
- Forms.RTax25RegisterJournalTrans
- Calculate the depreciation
- depreciation bonus
- depreciation bonus recovery register
- MsDynAx060.Forms.RTax25RegisterJournalTrans
- MsDynAx060.Forms.RTax25RegisterJournalTable
audience: Application User
ms.search.region: Russia
---

# (RUS) Calculate the depreciation bonus recovery register 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

If a fixed asset is sold before it has been in operation for five years, the bonus depreciation is restored and included in the company income.


> [!NOTE]
> <P>In AX 2012 R3 and cumulative update 6 or later for AX 2012 R2: If you sell a fixed asset before it has been in operation for five years, you can restore the bonus depreciation only if you sell the fixed asset to an affiliated customer. For more information, see <A href="rus-set-up-an-affiliated-customer.md">(RUS) Set up an affiliated customer</A>.</P>



To restore the bonus depreciation, set up the **Depreciation bonus recovery** register in the **Tax registers** form. Restoration of the bonus depreciation affects tax accounting, so you must create and calculate a tax register journal. The tax register journal contains information about the fixed asset and the bonus depreciation amount. The bonus depreciation amount is equal to the difference between the tax accounting amount and the business accounting amount.

You must calculate the **Depreciation bonus recovery** register before you calculate the following registers:

  - The **Calculation of constant tax differences** register

  - The **Incomes - current period** register

Use the following procedure to calculate the depreciation bonus recovery register.

1.  Click **General ledger** \> **Journals** \> **Tax register journal**.

2.  Create a register journal, and then enter the required details. You can create a journal only if all previous journals are approved. For more information, see [(RUS) Create a tax register journal](rus-create-a-tax-register-journal.md) and [(RUS) Approve the register](rus-approve-the-register.md).

3.  Click **Lines** to open the **Register journal lines** form. When register journal lines are created, they have a status of **Not calculated**.

4.  Select the **Depreciation bonus recovery** journal line, and then click **Calculate current** to calculate the register.

5.  Click **OK** to confirm the calculation. After the calculation is completed, the status of the register is updated as **Calculated** in the **Status** field.
    

    > [!NOTE]
    > <P>To view the details of the register lines after the calculation, click <STRONG>Register lines</STRONG> to open the <STRONG>Depreciation bonus recovery</STRONG> form.</P>



In the **Register journal lines** form, on the **Overview** tab, select the **Approved** check box to approve the register. In the **Worker** field, view or modify the code of the employee who approved the register.

## See also

[(RUS) Set up a register to calculate the depreciation bonus recovery](rus-set-up-a-register-to-calculate-the-depreciation-bonus-recovery.md)

[(RUS) Recalculate registers](rus-recalculate-registers.md)

[(RUS) Set up a register for the calculation of constant tax differences](rus-set-up-a-register-for-the-calculation-of-constant-tax-differences.md)

[(RUS) Set up a register for incomes - current period](rus-set-up-a-register-for-incomes-current-period.md)

[(RUS) Tax registers (form)](https://technet.microsoft.com/en-us/library/jj853195\(v=ax.60\))

[(RUS) Register journal lines (form)](https://technet.microsoft.com/en-us/library/jj839663\(v=ax.60\))

  


