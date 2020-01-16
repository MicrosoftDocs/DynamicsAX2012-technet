---
title: Set up payroll statistics for time and attendance
TOCTitle: Set up payroll statistics for time and attendance
ms:assetid: f727afd2-188d-4dfa-a0bd-7ec00ae1d869
ms:mtpsurl: https://technet.microsoft.com/library/Aa499785(v=AX.60)
ms:contentKeyID: 36060026
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- payroll
- statistics
audience: Application User
ms.search.region: Global
---

# Set up payroll statistics for time and attendance 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can create payroll statistics to view the calculation of workers’ pay for different types of wages, such as standard time and overtime. The basis for a payroll statistic is one or more pay types that are summarized over a specific period of time.

## Create a payroll statistic

1.  Click **Human resources** \> **Setup** \> **Time and attendance** \> **Payroll** \> **Payroll statistics**.

2.  Click **New** to create a line.

3.  Enter an ID and description of the group.

4.  Select the **Transfer** check box to use the closing balance from one pay period as the opening balance in the next pay period.

5.  Click **Setup**.

6.  In the **Setup** form, select a pay type.

7.  On the **General** tab, select a pay period in the **Period code** field.

8.  Press CTRL+N to create more pay types for the payroll statistics group.

## Set up payroll statistics to be displayed in registration forms

You can display a worker's current payroll balances in the **Balances** form, which you can open from the **Job registration** form.


> [!NOTE]
> <P>Whether a worker has access to the <STRONG>Balances</STRONG> form depends on the setup of the <STRONG>Job registration</STRONG> form. For information about how to configure registrations forms, see <A href="key-tasks-set-up-manufacturing-execution.md">Key tasks: Set up manufacturing execution</A>.</P>



1.  Click **Human resources** \> **Setup** \> **Time and attendance** \> **Payroll** \> **Statistical balance setup**.

2.  Click **New** to create a line.

3.  In the **Payroll statistics group** field, select a payroll statistics group.

4.  In the **External name** field, enter the name that will be displayed in the **Balances** form. For example, you might want to display statistics for standard time and overtime.

5.  To include the flexible hours balance when the payroll balance is displayed, select the **Flex** check box.
    

    > [!IMPORTANT]
    > <P>This field and the <STRONG>Payroll statistics group</STRONG> field are mutually exclusive. You can either select a group in the <STRONG>Payroll statistics group</STRONG> field or select this check box for a statistical balance setup.</P>



## See also

[About payroll in Time and attendance](about-payroll-in-time-and-attendance.md)

  


