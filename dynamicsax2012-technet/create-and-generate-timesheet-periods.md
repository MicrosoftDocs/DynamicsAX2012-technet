---
title: Create and generate timesheet periods
TOCTitle: Create and generate timesheet periods
ms:assetid: 8d2d02e4-6fed-41ad-bf9b-f34607e4caf8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh209351(v=AX.60)
ms:contentKeyID: 36058489
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- timesheet
- employee periods
- period type
- period frequency
- project periods
- timesheet periods
- split week
audience: Application User
ms.search.region: Global
---

# Create and generate timesheet periods 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Project periods are applied to estimates, subscriptions, and workers. The periods are created based on a period type. For each period type, you create a period frequency. For example, if hours are to be reported weekly, you must create a period type with the period frequency of a week. You then select a period frequency to define the timesheet period.


> [!NOTE]
> <P>Some options on the forms that are used in the following procedures are not applicable for timesheet periods. This is because periods are used for various purposes.</P>



1.  Click **Organization administration** \> **Common** \> **Calendars** \> **Period types**.

2.  In the **Period types** form, click **New**.

3.  In the **Period types** field, enter a name for the period type, such as Week or Month.

4.  Optional: In the **Description** field, enter a description of the period type.

5.  In the **Frequency** field, select the frequency of the period type.
    

    > [!NOTE]
    > <P>Timesheets only support weekly, bi-weekly, semi-monthly, and monthly frequencies. Other period options do not apply to timesheet periods.</P>



6.  If you want to automatically split weekly and bi-weekly periods at the end of a month, select the **Auto split week** check box.

7.  Click the **Generate periods** button.

8.  In the **Generate periods** form, if you want to generate new periods for the workers who are associated with the period type, select the **Update worker periods** check box.

9.  To define the weekly timesheet periods, select the **Update timesheet periods** check box.

10. Enter a date in the **Specify start date of the period** field. Then, in the **Length of period** field, enter the number of periods that each ledger period is to be divided into.
    

    > [!NOTE]
    > <P>The <STRONG>Length of period</STRONG> field is unavailable if the <STRONG>Frequency</STRONG> field in the <STRONG>Period types</STRONG> form is set to <STRONG>Unlimited</STRONG>.</P>



11. Optional: In the **Billable hours** field, enter the expected number of billable hours for the period.

12. Optional: In the **Efficiency hours** field, enter the expected number of efficiency hours for each period. Efficiency hours are the hours in which work is actually accomplished.

To see the generated periods, click the **Periods** button in the **Period types** form.

After periods have been generated, you must assign every worker who enters time against projects to a period type. For more information, see [Assign and maintain worker periods](assign-and-maintain-worker-periods.md).

You must also associate periods with estimates because the estimate frequency is based on a period type. You can use the same periods for timesheets and estimates, or create additional periods that are used only for estimates. For more information, see [About estimate periods](about-estimate-periods.md).

## See also

[Set up parameters for a timesheet system](set-up-parameters-for-a-timesheet-system.md)

[Period types (form)](https://technet.microsoft.com/en-us/library/aa586707\(v=ax.60\))

[Generate periods (class form)](https://technet.microsoft.com/en-us/library/aa557965\(v=ax.60\))

  


