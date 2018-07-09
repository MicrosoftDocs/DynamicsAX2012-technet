---
title: (RUS) Set up a register for cash payment issue
TOCTitle: (RUS) Set up a register for cash payment issue
ms:assetid: f99117ca-266e-4131-b205-1e16e07b78e1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678636(v=AX.60)
ms:contentKeyID: 49388118
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Set up a register for cash payment issue [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



The **Cash payment issue** register is created to combine cash outflow information for an enterprise in order to affiliate expenses that equally relate to current and future periods and vouchers that define the amount of future revenue.

The data in the register is grouped by disposal terms or cash outflow type. The total values of the registers as well as the general total of the account are calculated for each cash disposal term.

1.  Click **General ledger** \> **Setup** \> **Profit tax** \> **Registers**.

2.  Press CTRL+N to create a new line.

3.  In the **Register type** field, select **Cash payment issue**.

4.  In the **Register code** field, enter an identification code for the register.

5.  In the **Register name** field, modify the name of the register, if necessary.

6.  In the **Period type** field, select the type of time period for which the register is created.

7.  Click the **Hide** tab, and move any fields that you want to hide in the register from **Available fields** to **Selected fields**.

8.  In **Selected fields**, select the check box for the register fields to be hidden.

9.  Click **Expense codes** to open the **Expense code setup** form.

10. In the left pane, press CTRL+N to create a record that specifies the expense codes that correspond to the **Cash payment issue** register.

11. In the right pane, click the **Exceptions** tab and select the ledger accounts that should not be displayed in the register.

12. Click the **Exception dimension** tab and set up the dimension codes for which vouchers should not be displayed in the register.

13. Press CTRL+S or close the form.

## See also

[(RUS) Tax registers (form)](https://technet.microsoft.com/en-us/library/jj853195\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

