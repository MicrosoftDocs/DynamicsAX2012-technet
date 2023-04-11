---
title: Generate timesheet periods
TOCTitle: Generate timesheet periods
ms:assetid: 49a3aa2e-6d08-42bf-b299-67c28ccbdbcf
ms:mtpsurl: https://technet.microsoft.com/library/Aa497006(v=AX.60)
ms:contentKeyID: 36056943
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- create periods
- employee periods
- generate periods
- period type
- split period
audience: Application User
ms.search.region: Global
---

# Generate timesheet periods 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Timesheet periods in Microsoft Dynamics AX are generated for each period type. Workers who are assigned to projects are assigned to one of these timesheet-related period types to determine how frequently they must submit timesheets. Timesheet periods are also used as the basis for generating the payroll.

## Create a timesheet period type

1.  Click **Organization administration** \> **Common** \> **Calendars** \> **Period types**.

2.  In the **Period types** form, click **New**.

3.  Enter a name and description for the period type, and then select a period frequency.

4.  To split weekly and bi-weekly periods automatically for weekly and biweekly timesheet periods, select the **Auto split week** check box. This option splits a timesheet week into two and prevents a timesheet week from spanning two ledger periods.

5.  In the **Day week starts** field, select the day of the week that you want timesheet periods to begin.

## Generate timesheet periods for a period type

1.  Click **Organization administration** \> **Common** \> **Calendars** \> **Period types**.

2.  In the **Period types** form, select a period, and then click **Generate periods**.

3.  Optional: Select the **Update worker periods** check box to create worker periods with the period type that you have selected.

4.  Select the **Update timesheet periods** check box to create timesheet periods with the period type that you have selected.

5.  Enter the start date of the period. A period always starts at the beginning of a period unit, such as the start of a month.
    

    > [!NOTE]
    > <P>If you have already created transactions for this period, the <STRONG>Specify start date of the period</STRONG> field is read-only. The new period starts the day after the end date of the last period that was generated.</P>



6.  In the **Length of period** field, enter the number of period units that you want the ledger period to be divided into.

7.  Optional: If you want to track billable hour utilization, in the **Billable hours** field, enter the number of chargeable hours that you expect for the period. This number is compared to the number of hours that are actually charged. You can view the difference in the **Billable rate** reports.

8.  Optional: If you want to track efficiency hour utilization, in the **Efficiency hours** field, enter the number of productive hours that you expect for the period. This number is compared to the number of hours that are entered as productive instead of nonproductive. You can view the difference in the **Efficiency rate** reports.

9.  Click **OK** to generate the periods.

## See also

[About utilization rates](about-utilization-rates.md)

[Period types (form)](https://technet.microsoft.com/library/aa586707\(v=ax.60\))

[Period transactions (form)](https://technet.microsoft.com/library/aa558283\(v=ax.60\))

[Generate periods (class form)](https://technet.microsoft.com/library/aa557965\(v=ax.60\))

[Assign and maintain worker periods](assign-and-maintain-worker-periods.md)

  


