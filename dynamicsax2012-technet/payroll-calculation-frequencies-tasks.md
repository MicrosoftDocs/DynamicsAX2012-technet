---
title: Payroll calculation frequencies tasks
TOCTitle: Payroll calculation frequencies tasks
ms:assetid: de11c019-c79c-4a0a-a04a-f767fe11e871
ms:mtpsurl: https://technet.microsoft.com/library/JJ677367(v=AX.60)
ms:contentKeyID: 49384143
author: Khairunj
ms.date: 11/14/2014
mtps_version: v=AX.60
f1_keywords:
- payroll calculation frequency
- Payroll calculation frequencies
- Forms.PayrollCalculationFrequency
- Payroll
- MsDynAx060.Forms.PayrollCalculationFrequency
audience: Application User
ms.search.region: USA
---

# Payroll calculation frequencies tasks 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic describes the tasks that are required to set up payroll calculation frequencies.

Certain earnings, contributions, and deductions should be processed in specified pay periods. For example, the worker deduction for medical insurance might be processed in the first pay period of every month, and the employer contribution might be processed in the first pay period of every quarter. A car allowance might be processed in the last pay period of the month.

You can use payroll calculation frequencies to control which pay periods these payroll elements are processed in. You create the payroll calculation frequencies that you need for your payroll, and assign pay periods to those frequencies. After you do that, you can assign the frequencies to earning codes on a worker detail form and to benefit contributions and deductions.


> [!NOTE]
> <P>The payroll calculation frequency and the pay cycle frequency are not the same thing. The <EM>pay cycle frequency</EM> determines how often a pay cycle is run. Pay periods and pay dates are defined as part of the pay cycle. You use the <EM>payroll calculation frequency</EM> to select the specific pay periods when you want certain earnings or other payroll entities to be processed. For more information about pay cycle frequencies, see <A href="pay-cycle-and-pay-period-tasks.md">Pay cycle and pay period tasks</A>.</P>



By default, all earnings, contributions, and deductions are processed in every pay period. If this meets your payroll processing requirements, you do not have to complete the tasks in this topic.

The following illustration shows the steps that you must follow to set up payroll calculation frequencies. The numbers correspond to the procedures later in this topic.

![Steps to set up payroll calculation frequencies](images/JJ677367.Payroll_calculation_frequencies(AX.60).gif "Steps to set up payroll calculation frequencies")

## What do you want to do?

Understand the bigger process

Review the prerequisites

1\. Create payroll calculation frequencies

2\. Assign pay periods to payroll calculation frequencies

3\. Assign payroll calculation frequencies to payroll elements

Next step

Technical information for system administrators

Find related tasks

## Understand the bigger process

The following illustration shows the relationship between this topic and the overall process of setting up Payroll for the first time. You do not have to set up payroll calculation frequencies unless you have to control which pay periods various payroll elements are processed in.

For an overview of the process, see [Setting up payroll: Basic topics](setting-up-payroll-basic-topics.md).

![Basic steps for setting up Payroll the first time](images/JJ677367.Payroll_Set_up_payroll_basic(AX.60).gif "Basic steps for setting up Payroll the first time")

Back to top

## Review the prerequisites

The following table shows the prerequisites that must be in place before you start.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Version</p></td>
<td><p>Microsoft Dynamics AX 2012 R2</p></td>
</tr>
<tr class="even">
<td><p>Country/region</p></td>
<td><p>(USA) The primary address for the legal entity must be in the following countries/regions: United States</p></td>
</tr>
</tbody>
</table>


Back to top

## 1\. Create payroll calculation frequencies

Before you begin, determine when you process various payroll elements. These are some of the commonly used processing frequencies:

  - All pay periods

  - Monthly, first pay period

  - Monthly, second pay period

  - Monthly, third pay period

  - Monthly, fourth pay period

  - Monthly, last pay period

  - Alternating pay periods, even

  - Alternating pay periods, odd

  - Yearly, first pay period of the calendar year

  - Yearly, last pay period of the calendar year

  - Yearly, first pay period of the fiscal year

  - Yearly, last pay period of the fiscal year

  - Yearly, on a specific date


> [!NOTE]
> <P>The default payroll calculation frequency <STRONG>All</STRONG>, for all pay periods, is provided for you.</P>



1.  Click **Payroll** \> **Setup** \> **Payroll calculation frequencies**.

2.  Click **New**.

3.  In the **Frequency** field, enter the name of the payroll calculation frequency. For example, you might enter M-1 for the first pay period of the month, or M-last for the last pay period of the month.

4.  In the **Description** field, enter a few words to describe the payroll calculation frequency. For example, you might enter last pay period of the month.

5.  Repeat steps 2 through 4 to create additional payroll calculation frequencies.

When you have finished, close the form or continue with ”Assign pay periods to payroll calculation frequencies.” The payroll calculation frequencies have no effect until you assign pay periods to them.

Back to top

## 2\. Assign pay periods to payroll calculation frequencies

You can assign pay periods from one or more pay cycles to each payroll calculation frequency. For example, you might have positions that have a weekly pay cycle and positions that have a semimonthly pay cycle. You might also have a car allowance that should always be processed in the first pay period of the month, regardless of which pay cycle the worker’s position uses. To accomplish this, you assign pay periods from both pay cycles to the payroll calculation frequency for the first of the month.


> [!NOTE]
> <P>You can’t delete the payroll calculation frequency after you select pay periods or assign the payroll calculation frequency to any other payroll element.</P>



1.  Click **Payroll** \> **Setup** \> **Payroll calculation frequencies**.

2.  In the **Status filter** field, select **View all pay periods**.

3.  Select a payroll calculation frequency from the list.

4.  In the **Pay cycle** field, select a pay cycle.

5.  Click **Add**.

6.  Select the pay periods to assign to the selected payroll calculation frequency.

7.  Click **Add**.

8.  Repeat steps 4 through 7 to assign pay periods from additional pay cycles to this payroll calculation frequency.

9.  Repeat steps 3 through 8 to assign pay periods to additional payroll calculation frequencies.

10. When you have finished, close the form.

You can now use the payroll calculation frequencies to control when certain deductions, contributions, and earning codes are processed. See “Assign payroll calculation frequencies to payroll elements” to continue.

Back to top

## 3\. Assign payroll calculation frequencies to payroll elements

Assign payroll calculation frequencies to payroll elements to control when those payroll elements are processed.

  - To specify when the deductions and contributions for a benefit are processed, see “Create a new benefit” in [Benefit setup tasks](benefit-setup-tasks.md).

  - To specify when an earning code is processed for a worker, see “Add earning codes to worker position assignments” in [Worker and position payroll tasks](worker-and-position-payroll-tasks.md).

If you do not specify a payroll calculation frequency for these payroll elements, they will be processed in every pay period.

Back to top

## Next step

The next step is to set up work cycles and work periods. Certain earnings, such as the overtime premiums that are required by the Fair Labor Standards Act (FLSA), are based on work periods and not pay periods. For more information, see [Work cycle and work period tasks](work-cycle-and-work-period-tasks.md).

Back to top

## Technical information for system administrators

If you don't have access to the pages that are used to complete this task, contact your system administrator and provide the information that is shown in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Configuration keys</strong></p></td>
<td><p><strong>Payroll - USA</strong></p>
<div class="alert">

> [!NOTE]
> <P>When you use Payroll, we highly recommend that you turn off the <STRONG>Payroll information</STRONG> configuration key under the <STRONG>Human resource I</STRONG> configuration key. The forms and tables that are enabled by that configuration key are not used by Payroll. If Payroll is installed and the configuration key is enabled, it might be difficult to make sure that your data is entered and tracked correctly.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Security roles and duties</strong></p></td>
<td><p>To set up payroll calculation frequencies, you must be a member of a security role that includes these duties:</p>
<ul>
<li><p><strong>Set up payroll master data</strong> (PayrollMasterDataMaintain)</p></li>
<li><p><strong>Inquire into payroll master data</strong> (PayrollMasterDataInquire)</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To set up payroll calculation frequencies, you must be a member of a security role that includes this privilege:</p>
<ul>
<li><p><strong>Maintain payroll calculation frequencies</strong> (PayrollCalculationFrequencyMaintain)</p></li>
</ul></td>
</tr>
</tbody>
</table>


Back to top

## Find related tasks

[Pay cycle and pay period tasks](pay-cycle-and-pay-period-tasks.md)

[Benefit setup tasks](benefit-setup-tasks.md)

[Worker and position payroll tasks](worker-and-position-payroll-tasks.md)

  


