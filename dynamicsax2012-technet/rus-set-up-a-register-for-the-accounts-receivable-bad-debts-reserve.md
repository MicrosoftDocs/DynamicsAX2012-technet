---
title: (RUS) Set up a register for the accounts receivable bad debts reserve
TOCTitle: (RUS) Set up a register for the accounts receivable bad debts reserve
ms:assetid: 91d203da-8823-403c-95c8-337881bdb41e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678485(v=AX.60)
ms:contentKeyID: 49387714
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Set up a register for the accounts receivable bad debts reserve 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



The **Accounts receivable – bad debts reserve** register is created to calculate the reserve amount. This reserve is used later to settle unrecoverable debt. The register complies with the totals of the Accounts receivable - inventory register and reflects the remaining debt.

The remaining reserve for the previous period is taken in respect of the Accounts receivable - reserve movement register for the previous period (if not available, it is regarded as equal to zero). The difference between the calculated reserve for the current period and the remainder of the previous period is spread across the unrealized revenues or the unrealized expenses account, depending on the signifier.

1.  Click **General ledger** \> **Setup** \> **Profit tax** \> **Registers**.

2.  Press CTRL+N to create a new line.

3.  In the **Register type** field, select **Accounts receivable – bad debts reserve**.

4.  In the **Register code** field, enter an identification code for the register.

5.  In the **Register name** field, modify the name of the register, if necessary.

6.  In the **Period type** field, select the type of time period for which the register is created.

7.  Click the **Hide** tab, and move any fields that you want to hide in the register from **Available fields** to **Selected fields**.

8.  In **Selected fields**, select the check box for the register fields to be hidden.

9.  Press CTRL+S or close the form.

## See also

[(RUS) Tax registers (form)](https://technet.microsoft.com/en-us/library/jj853195\(v=ax.60\))

[(RUS) Calculate the accounts receivable bad debts reserve register](rus-calculate-the-accounts-receivable-bad-debts-reserve-register.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

