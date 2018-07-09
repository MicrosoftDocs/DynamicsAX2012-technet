---
title: (RUS) Set up profit tax registers
TOCTitle: (RUS) Set up profit tax registers
ms:assetid: 65f43c14-cc80-48dc-9a8a-8e8ec81c3609
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ911486(v=AX.60)
ms:contentKeyID: 52075389
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Set up profit tax registers [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The accounting rules that are used to group objects for tax purposes differ from the rules that are used in general accounting. The tax base for each reporting period is calculated based on tax accounting data that is accumulated during that period.

1.  Click **General ledger** \> **Setup** \> **Profit tax** \> **Registers**.

2.  Press CTRL+N to create a new profit tax register.

3.  In the **Register type** field, select the type of register.

4.  In the **Register code** field, enter an identification code for the register.

5.  In the **Register name** field, modify the name of the register, if a different name is required.

6.  In the **Period types** field, select the type of period for the register.

7.  Select the **Exclude** check box to exclude the tax register from the tax register journal.

8.  Click the **Hide** FastTab to move fields from the **Available fields:** list to the **Selected fields** list.

9.  Select the **Selected fields** check box to hide certain fields from the tax register.
    

    > [!NOTE]
    > <P>When you create new lines in the register journals, the hidden fields are automatically excluded from the registry. For each register, you can change the list of fields that is included in the calculation of register lines. The fields are saved together with all historical data, from creation to the adjustment of the list of fields.</P>



## See also

[(RUS) Tax registers (form)](https://technet.microsoft.com/en-us/library/jj853195\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

