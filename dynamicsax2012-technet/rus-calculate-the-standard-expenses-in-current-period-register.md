---
title: (RUS) Calculate the standard expenses in current period register
TOCTitle: (RUS) Calculate the standard expenses in current period register
ms:assetid: 9fa1bd31-16f3-4c96-a74a-75c803f3616b
ms:mtpsurl: https://technet.microsoft.com/library/JJ678538(v=AX.60)
ms:contentKeyID: 49387767
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Calculate the standard expenses in current period register 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



You must set up the **Standard expenses in current period** register in the **Tax registers** form and create a tax register journal before calculating the register.

1.  Click **General ledger** \> **Journals** \> **Tax register journal**.

2.  Press CTRL+N to create a new register journal and enter the required details. You can create a new journal only if all the previous journals are approved.

3.  Click **Lines** to open the **Register journal lines** form. Register journal lines are created with the status as **Not calculated**.

4.  Select the **Standard expenses in current period** journal line.

5.  Click **Calculate current** to calculate the register.

6.  Click **OK** to confirm the calculation. After calculation, the status of the register is displayed as **Calculated** in the **Status** field.
    

    > [!NOTE]
    > <P>To view the details in the register lines after calculation, click <STRONG>Register lines</STRONG> to open the <STRONG>Register lines</STRONG> form.</P>



7.  Select the **Approved** check box to approve the register.

8.  In the **Worker** field, view or modify the code of the employee who approved the register.

## See also

[(RUS) Recalculate registers](rus-recalculate-registers.md)

  


