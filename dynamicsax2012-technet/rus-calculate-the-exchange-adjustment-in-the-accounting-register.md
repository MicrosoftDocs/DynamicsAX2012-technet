---
title: (RUS) Calculate the exchange adjustment in the accounting register
TOCTitle: (RUS) Calculate the exchange adjustment in the accounting register
ms:assetid: 0b37970c-2b06-42d6-99c4-32c0b778cd0f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711381(v=AX.60)
ms:contentKeyID: 49387199
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Calculate the exchange adjustment in the accounting register 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Before you can calculate the **Exchange adjustment in accounting** register, you must set up the register in the **Tax registers** form and create a tax register journal.

To exclude the calculation of exchange adjustments for prepayments, select **No** in the **Prepayment journal voucher** field in the **Foreign currency revaluation** form.


> [!NOTE]
> <P>For more information, see <A href="about-foreign-currency-revaluations-for-open-vendor-transactions.md">About foreign currency revaluations for open vendor transactions</A> and <A href="revalue-foreign-currency-amounts-for-customers-or-vendors.md">Revalue foreign currency amounts for customers or vendors</A>.</P>



1.  Click **General ledger** \> **Journals** \> **Tax register journal**.

2.  Create a register journal, and then enter the required details. You can create a journal only if all previous journals are approved. For more information, see [(RUS) Create a tax register journal](rus-create-a-tax-register-journal.md) and [(RUS) Approve the register](rus-approve-the-register.md)

3.  Click **Lines**, and then select the **Exchange adjustment in accounting** register journal line.

4.  In the **Exchange adjustment in accounting** form, click **Calculate current** to calculate the register.

5.  Click **OK** to confirm the calculation and close the form. After the calculation is completed, the status of the register is displayed as **Calculated** in the **Status** field.
    

    > [!TIP]
    > <P>To view the details on the register lines after the calculation is completed, click <STRONG>Register lines</STRONG>.</P>



6.  Select the **Approved** check box to approve the register.

7.  In the **Worker** field, view the code of the employee who approved the register.

## See also

[(RUS) Tax register journal (form)](https://technet.microsoft.com/en-us/library/jj856114\(v=ax.60\))

[(RUS) Recalculate registers](rus-recalculate-registers.md)

[(RUS) Tax registers (form)](https://technet.microsoft.com/en-us/library/jj853195\(v=ax.60\))

  


