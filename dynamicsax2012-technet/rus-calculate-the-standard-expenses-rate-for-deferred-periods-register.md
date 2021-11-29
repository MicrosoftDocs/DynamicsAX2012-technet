---
title: (RUS) Calculate the standard expenses rate for deferred periods register
TOCTitle: (RUS) Calculate the standard expenses rate for deferred periods register
ms:assetid: a4d9bb05-b260-452c-b7aa-bd0d08bf0206
ms:mtpsurl: https://technet.microsoft.com/library/JJ678567(v=AX.60)
ms:contentKeyID: 49387795
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Calculate the standard expenses rate for deferred periods register 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



You must set up the **Standard expenses rate for deferred periods** register in the **Tax registers** form and create a tax register journal before calculating the register.


> [!NOTE]
> <P></P>



1.  Click **General ledger** \> **Journals** \> **Tax register journal**.

2.  Press CTRL+N to create a new register journal and enter the required details. You can create a new journal only if all the previous journals are approved.
    

    > [!NOTE]
    > <P></P>



3.  Click **Lines** to open the **Register journal lines** form. Register journal lines are created with the status as **Not calculated**.

4.  Select the **Standard expenses rate for deferred periods** journal line.

5.  Click **Register calculation** \> **Calculate current** to calculate the register.

6.  Click **OK** to confirm the calculation. After calculation, the status of the register is displayed as **Calculated** in the **Status** field.
    

    > [!NOTE]
    > <P>To view the details in the register lines after calculation, click <STRONG>Register lines</STRONG> to open the <STRONG>Register lines</STRONG> form.</P>



7.  Select the **Approved** check box to approve the register.

8.  In the **Employee** field, view or modify the code of the employee who approved the register.

9.  Press CTRL+S or close the form.

## See also

[(RUS) Recalculate registers](rus-recalculate-registers.md)

  


