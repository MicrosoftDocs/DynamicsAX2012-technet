---
title: (RUS) Calculate the fixed assets depreciation (nonlinear method) register
TOCTitle: (RUS) Calculate the fixed assets depreciation (nonlinear method) register
ms:assetid: 164e5615-c368-4443-828d-ad4e411dd4ec
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711426(v=AX.60)
ms:contentKeyID: 49387244
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Calculate the fixed assets depreciation (nonlinear method) register 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You must set up the **FA depreciation (nonlinear method)** register in the **Tax registers** form and create a tax register journal before calculating the register. For more information, see [(RUS) Set up a depreciation register (nonlinear method) for fixed assets](rus-set-up-a-depreciation-register-nonlinear-method-for-fixed-assets.md).


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **General ledger** \> **Journals** \> **Tax register journal**.

2.  Press CTRL+N to create a new register journal and enter the required details. You can create a new journal only if all the previous journals are approved.

3.  Click **Lines** to open the **Register journal lines** form. Register journal lines are created with the status as **Not calculated**.

4.  Select the **FA depreciation (nonlinear method)** journal line.

5.  Click **Register calculation** \> **Calculate current** to calculate the register.

6.  Click **OK** to confirm the calculation. After calculation, the status of the register is displayed as **Calculated** in the **Status** field.
    

    > [!NOTE]
    > <P>To view the details in the register lines after calculation, click <STRONG>Register lines</STRONG> to open the <STRONG>Register lines</STRONG> form.</P>



7.  Select the **Approved** check box to approve the register.

8.  In the **Employee** field, view or modify the code of the employee who approved the register.

## See also

[(RUS) Recalculate registers](rus-recalculate-registers.md)

  


