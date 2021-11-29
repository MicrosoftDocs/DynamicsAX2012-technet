---
title: Set up pay periods for time registration workers
TOCTitle: Set up pay periods for time registration workers
ms:assetid: e8e163d8-a62f-4f7d-9192-7c004596d162
ms:mtpsurl: https://technet.microsoft.com/library/Aa573402(v=AX.60)
ms:contentKeyID: 43976730
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up pay periods for time registration workers 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can set up pay periods for various tasks that are related to the calculation of pay for workers. For example, you use pay periods when you perform the following tasks:

  - Create pay adjustments.

  - Create count units.

  - Transfer pay transactions to an external file.

  - Set up payroll statistics.

Workers who make registrations that are used to generate pay must be assigned to a pay period. This assignment is made when the worker is set up as a time registration worker. For more information, see [Assign and maintain worker periods](assign-and-maintain-worker-periods.md).

1.  Click **Human resources** \> **Setup** \> **Time and attendance** \> **Payroll** \> **Period types**.

2.  In the **Period types** form, click **New**.

3.  In the **Period types** field, enter a name for the period type, such as **Week** or **Month**. Optionally, in the **Description** field, enter a description of the period type.

4.  In the **Frequency** field, select the frequency of the period type.

5.  If you want to automatically split weekly and bi-weekly periods at the end of a month, select the **Auto split week** check box.

6.  Click **Generate periods**.

7.  In the **Generate periods** form, if you want to generate new periods for the workers who are associated with the period type, select the **Update worker periods** check box.

8.  To define the weekly timesheet periods, select the **Update timesheet periods** check box. In the **Specify start date of the period** field, enter the start date of the period. Then, in the **Length of period** field, enter the number of periods that each ledger period is to be divided into.
    

    > [!NOTE]
    > <P>The <STRONG>Length of period</STRONG> field is not available if the <STRONG>Frequency</STRONG> field in the <STRONG>Period types</STRONG> form is set to <STRONG>Unlimited</STRONG>.</P>



9.  Optional: In the **Billable hours** field, enter the number of billable hours that are expected for the period.

10. Optional: In the **Efficiency hours** field, enter the number of efficiency hours that are expected for each period. Efficiency hours are the hours in which work is actually accomplished.

11. To see the periods that are generated, in the **Period types** form, click **Periods**.

## See also

[About payroll in Time and attendance](about-payroll-in-time-and-attendance.md)

[About pay adjustments and count units](about-pay-adjustments-and-count-units.md)

[About time registration workers](about-time-registration-workers.md)

  


