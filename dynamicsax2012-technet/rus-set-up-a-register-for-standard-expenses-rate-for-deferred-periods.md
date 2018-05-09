---
title: (RUS) Set up a register for standard expenses rate for deferred periods
TOCTitle: (RUS) Set up a register for standard expenses rate for deferred periods
ms:assetid: 735ba5b7-8fc5-44a9-ac16-a0f577f0aa6b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678362(v=AX.60)
ms:contentKeyID: 49387592
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Set up a register for standard expenses rate for deferred periods 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



Standard expenses are of two types:

  - Current standard expenses

  - Deferrals

This register contains the results of norm calculations for the future period. The future norm is adjusted to an expense above current period norm, and upon obtaining an amount, forms a deferred expense.

1.  Click **General ledger** \> **Setup** \> **Profit tax** \> **Registers**.

2.  Press CTRL+N to create a new line.

3.  In the **Register type** field, select **Standard expenses rate for deferred periods**.

4.  In the **Register code** field, enter an identification code for the register.

5.  In the **Register name** field, enter a name for the register.

6.  In the **Period type** field, select the type of time period for which the register is created.

7.  Click the **Hide** tab, and move any fields that you want to hide in the register from **Available fields** to **Selected fields**.

8.  In **Selected fields**, select the check box for the register fields to be hidden.

9.  Click **General ledger** \> **Setup** \> **Profit tax** \> **Register parameters** to set up any additional parameters for the register.

10. In the **Register name** field, select **Standard expenses rate for deferred periods**.

11. In the **Parameter name** field, select the parameter.

12. In the **Value** field, select a calculation sequence. If you specify more than one value, separate the values with commas.

13. Click **Specific** to open the **Standard expenses sequence** form to set up revenue or expense calculation sequences.

14. Press CTRL+S or close the form.

## See also

[(RUS) Tax registers (form)](https://technet.microsoft.com/en-us/library/jj853195\(v=ax.60\))

[(RUS) Standard expenses sequence (form)](https://technet.microsoft.com/en-us/library/jj853198\(v=ax.60\))

[(RUS) Calculate the standard expenses rate for deferred periods register](rus-calculate-the-standard-expenses-rate-for-deferred-periods-register.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

