---
title: (RUS) Calculate the fixed asset object information register
TOCTitle: (RUS) Calculate the fixed asset object information register
ms:assetid: caad52c9-4831-418f-aa40-5bdbd2fcc868
ms:mtpsurl: https://technet.microsoft.com/library/JJ711602(v=AX.60)
ms:contentKeyID: 49387926
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Calculate the fixed asset object information register 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You must set up the **FA - object information** register in the **Tax registers** form and create a tax register journal before calculating the register.


> [!NOTE]
> <P>For more information, see <A href="rus-set-up-an-object-information-register-for-fixed-assets.md">(RUS) Set up an object information register for fixed assets</A>.</P>




> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **General ledger** \> **Journals** \> **Tax register journal**.

2.  Press CTRL+N to create a new register journal and enter the required details. You can create a new journal only if all the previous journals are approved.
    

    > [!NOTE]
    > <P>For more information, see <A href="rus-create-a-tax-register-journal.md">(RUS) Create a tax register journal</A> and <A href="rus-approve-the-register.md">(RUS) Approve the register</A>.</P>



3.  Click **Lines** to open the **Register journal lines** form. Register journal lines are created with the status as **Not calculated**.

4.  Select the **FA - object information** journal line.

5.  Click **Register calculation** \> **Calculate current** to calculate the register.

6.  Click **OK** to confirm the calculation. After calculation, the status of the register is displayed as **Calculated** in the **Status** field.
    

    > [!NOTE]
    > <P>To view the details in the register lines after calculation, click <STRONG>Register lines</STRONG> to open the <STRONG>Register lines</STRONG> form.</P>



7.  Select the **Approved** check box to approve the register.

8.  In the **Worker** field, view or modify the code of the employee who approved the register.

9.  Press CTRL+S or close the form.

## See also

[(RUS) Tax register journal (form)](https://technet.microsoft.com/library/jj856114\(v=ax.60\))

[(RUS) Register journal lines (form)](https://technet.microsoft.com/library/jj839663\(v=ax.60\))

[(RUS) Calculate registers](rus-calculate-registers.md)

[(RUS) Recalculate registers](rus-recalculate-registers.md)

[(RUS) Tax registers (form)](https://technet.microsoft.com/library/jj853195\(v=ax.60\))

  


