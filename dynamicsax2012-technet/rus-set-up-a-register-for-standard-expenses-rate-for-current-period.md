---
title: (RUS) Set up a register for standard expenses rate for current period
TOCTitle: (RUS) Set up a register for standard expenses rate for current period
ms:assetid: 2fd9ecfe-7c93-41ee-a18a-c46c6840edb6
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ665246(v=AX.60)
ms:contentKeyID: 49387335
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Set up a register for standard expenses rate for current period [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



The **Standard expenses rate for current period** register contains the results of norm calculations for the current period. Expenses are taken into the current period tax account in specific accordance with these norms.

1.  Click **General ledger** \> **Setup** \> **Profit tax** \> **Registers**.

2.  Press CTRL+N to create a new line.

3.  In the **Register type** field, select **Standard expenses rate for current period**.

4.  In the **Register code** field, enter an identification code for the register.

5.  In the **Register name** field, enter a name for the register.

6.  In the **Period type** field, select the type of time period for which the register is created.

7.  Click the **Hide** tab, and move any fields that you want to hide in the register from **Available fields** to **Selected fields**.

8.  In **Selected fields**, select the check box for the register fields to be hidden.

9.  Click **Expense codes** to open the **Expense code setup** form to select the revenue and expense codes that relate to the register.

10. Click **General ledger** \> **Setup** \> **Profit tax** \> **Registers**. to set up any additional parameters for the register.

11. In the **Register name** field, select **Standard expenses rate for current period**.

12. In the **Parameter name**, select the parameter.

13. In the **Value** field, select a calculation sequence. If you specify more than one value, separate the values with commas.

14. Click **Specific** to open the **Standard expenses sequence** form to set up revenue or expense calculation sequences.

15. Press CTRL+S or close the form.

## See also

[(RUS) Tax registers (form)](https://technet.microsoft.com/en-us/library/jj853195\(v=ax.60\))

[(RUS) Standard expenses sequence (form)](https://technet.microsoft.com/en-us/library/jj853198\(v=ax.60\))

[(RUS) Calculate the standard expenses rate for the current period register](rus-calculate-the-standard-expenses-rate-for-the-current-period-register.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

