---
title: 'Setting up payroll: Basic topics'
TOCTitle: 'Setting up payroll: Basic topics'
ms:assetid: c6e4e88a-6f34-4853-aecc-b2d3b4ed6dee
ms:mtpsurl: https://technet.microsoft.com/library/JJ677361(v=AX.60)
ms:contentKeyID: 49384136
author: tonyafehr
ms.date: 12/12/2014
mtps_version: v=AX.60
f1_keywords:
- payroll
audience: Application User
ms.search.region: USA
---

# Setting up payroll: Basic topics 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic contains high-level procedures to help you set up Payroll in Microsoft Dynamics AX 2012. Each procedure contains links to basic setup topics that describe the tasks that are required to set up Payroll for the first time.

The following illustration shows the basic Payroll setup process. The numbers correspond to the procedures later in this topic.

![Basic steps for setting up Payroll the first time](images/JJ677367.Payroll_Set_up_payroll_basic(AX.60).gif "Basic steps for setting up Payroll the first time")

Setup tasks that are especially complex are not listed in this topic. Instead, they are included in the [Setting up payroll: Advanced topics](setting-up-payroll-advanced-topics.md) section. Review the advanced setup topics before you begin the basic setup.

This topic describes functionality that is available only if the **Payroll - USA** configuration key is selected.


> [!TIP]
> <P>To make it easier to find the procedures you need, click <STRONG>Collapse All</STRONG> or <STRONG>Hide all</STRONG> to close the detailed information and see just the list of procedures. Scan the list to find the procedure you want to use. Click the triangle next to the procedure title to open and close the detailed information.</P>



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
<td><p>Microsoft Dynamics AX 2012 R2</p>
<ul>
<li><p>Earning code groups require Microsoft Dynamics AX 2012 R3 or the Human resources/Payroll regulatory feature pack July 2014 for AX 2012 R2.</p></li>
<li><p>Tax groups are not available prior to cumulative update 7 for Microsoft Dynamics AX 2012 R2.</p></li>
<li><p>Premium earnings, work cycles, and work periods are not available prior to cumulative update 8 for AX 2012 R3.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Configuration tasks</p></td>
<td><p>All fields on the <strong>Payroll parameters</strong> form must be evaluated and set according to the requirements of your organization. For more information, see <a href="https://technet.microsoft.com/library/jj677433(v=ax.60)">Payroll parameters (form)</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Country/region</p></td>
<td><p>(USA) The primary address for the legal entity must be in the following countries/regions: United States</p></td>
</tr>
</tbody>
</table>


## 1\. Verify setup in Human resources and General ledger

Before you use Payroll for the first time, certain tasks must already be done in Human resources and General ledger. After those tasks are completed, you can set up the system for Payroll.


> [!IMPORTANT]
> <P>When you use Payroll, we highly recommend that you turn off the <STRONG>Payroll information</STRONG> configuration key under the <STRONG>Human resource I</STRONG> configuration key. The forms and tables that are enabled by that configuration key are not used by Payroll. If Payroll is installed and the configuration key is enabled, it might be difficult to make sure that your data is entered and tracked correctly.</P>



1.  Verify that general ledger accounts for payroll, accounting distributions, journal names, methods of payment for check and electronic payments to workers, and the vendor account for worker payments have been set up.
    
    To avoid posting journals before checks are printed or an ACH file is generated, make sure that the methods of payment for check and electronic payments have a payment status of **Sent**.

2.  Consider setting up positive pay for Payroll, which lets you generate an electronic list of payroll checks that you can later provide to the bank. When someone presents one of your payroll checks to the bank, the bank can compare the check with the list of checks. If the check matches what the bank has on file in the list, the bank clears the check. If there is a difference, the bank holds the check for review.
    
    For more information about how to set up positive pay, see [Set up positive pay](set-up-positive-pay.md).

3.  Verify that workers, positions, and compensation plans have been created. For more information, see [Key tasks: Workers](key-tasks-workers.md), [Key tasks: New worker positions](key-tasks-new-worker-positions.md), and [Key tasks: Compensation plans](key-tasks-compensation-plans.md).

4.  Verify that each worker has been assigned to at least one position and compensation plan.

## 2\. Set up number sequences

1.  Click **Payroll** \> **Setup** \> **Parameters** \> **Payroll parameters**.

2.  Click the **Number sequences** tab.

3.  Select a number sequence code for each type of payroll document. The number sequences provide automatic consecutive numbering and guarantee unique document IDs.

## 3\. Set up pay cycles and pay periods

Pay cycles and pay periods are required, and they control how often and when workers are paid. Go to [Pay cycle and pay period tasks](pay-cycle-and-pay-period-tasks.md) and follow these steps:

1.  **Set up pay cycles**.

2.  **Generate pay periods**: Organizations typically create the number of pay periods that are required for one year.

3.  **Modify payment dates**: Change any default payment dates that are on a day when payments can’t be made.

## 4\. Optional: Set up payroll calculation frequencies

You can use payroll calculation frequencies to control when benefits and certain earnings are processed. Go to [Payroll calculation frequencies tasks](payroll-calculation-frequencies-tasks.md) and follow these steps:

1.  **Create payroll calculation frequencies**.

2.  **Associate pay periods with payroll calculation frequencies**: Some payroll calculation frequencies can be associated with pay periods from more than one pay cycle.

## 5\. Set up work cycles and work periods

A work cycle is used to specify the frequency of work periods for positions. Certain earnings, such as the overtime premiums required by the Fair Labor Standards Act (FLSA), are based on work periods and not pay periods. Go to [Work cycle and work period tasks](work-cycle-and-work-period-tasks.md) and follow these steps:

1.  **Set up work cycles**.

2.  **Generate work periods**: Organizations typically create the number of work periods that are required for one year.

## 6\. Set up earning codes and earning code groups


> [!IMPORTANT]
> <P>Information about how to set up earning codes and earning code groups for premium earnings is included in the advanced topic, <A href="premium-earning-setup-tasks.md">Premium earning setup tasks</A>. Please review that topic before setting up earning codes.</P>



Earning codes and earning code groups are used throughout the payroll system. You must create a unique earning code for each type of earning that your organization offers. The codes define the earning type exactly. For example, you need separate earning codes for regular hours worked on the first shift and on the second shift, even if the earnings for the shifts are the same. Similarly, if you have separate vacation plans for salaried workers, union workers, and hourly non-union workers, you need a separate earning code for each plan.

To set up earning codes and earning code groups, see [Earning code and earning code group tasks](earning-code-and-earning-code-group-tasks.md) and perform all the tasks.

## 7\. Set up schedules, leave types, and benefit accrual plans

Working time calendars are used to maintain schedules for hourly employees and to control the payroll processing for worker leaves, such as parental leave.

Time off for sickness or vacation is typically managed through benefit accrual plans. These plans are set up independently of leave types or benefit types.

  - To set up calendars and leave types, see [Work schedule and leave tasks](work-schedule-and-leave-tasks.md) and perform all the tasks.

  - To set up benefit accrual plans, follow these steps:
    
    1.  Click **Payroll** \> **Setup** \> **Parameters** \> **Payroll parameters**. In the **Default service date basis** field, select the date to use to determine a worker’s months of service so that the correct rule from a benefit accrual plan is used. (In versions of Microsoft Dynamics AX prior to AX 2012 R3, this field is the **Default accrual date basis** field.) For more information, see [Payroll parameters (form)](https://technet.microsoft.com/library/jj677433\(v=ax.60\)).
    
    2.  Go to [Benefit accrual plan tasks](benefit-accrual-plan-tasks.md), and then follow these steps:
        
        1.  **Set up benefit accrual plans**.
        
        2.  **Enroll workers in benefit accrual plans**.

## 8\. Set up taxes

When you set up Payroll, you must configure the payroll tax settings that are used throughout the organization, such as the states where you have a nexus, or the rates for unemployment taxes.

To set up these payroll tax settings, go to [Tax information tasks](tax-information-tasks.md) and follow these steps:

1.  **Update tax data**.

2.  **Set up employer tax regions for nexus**.

3.  **Create tax regions**.

4.  **Set up tax codes**: You do not have to create tax codes. The codes for all payroll taxes that are supported by Microsoft Dynamics AX are provided for you when you update tax data for the first time. However, you must provide information about how your organization uses each tax code.

5.  **Set up tax groups**.

For more information about payroll taxes, see [Tax codes, tax groups, and posting definitions](tax-codes-tax-groups-and-posting-definitions.md).

## 9\. Set up benefits and mandatory deductions


> [!IMPORTANT]
> <P>In Microsoft Dynamics AX, garnishments and tax levies are created and managed by using the benefit framework. Information about how to set up garnishments and tax levies is included in the advanced topic, <A href="garnishment-and-tax-levy-setup-tasks.md">Garnishment and tax levy setup tasks</A>.</P>



To set up benefits and mandatory deductions, follow these steps:

1.  Click **Payroll** \> **Setup** \> **Parameters** \> **Payroll parameters**. Set the parameters that apply to benefits:
    
    1.  Select the **Apply annual retirement wage limit** check box to stop calculating retirement benefits when the worker reaches the annual wage limit. This setting applies to all retirement plans that your organization offers.
    
    2.  Specify parameters for arrearages, which are created when a worker has insufficient pay to cover all the deductions for taxes and benefits. For each benefit plan that your organization offers, the **Benefit elements** form controls whether to recover arrears for that plan. The following parameters control how the arrears are recovered:
        
          - Select the **Recover arrears in all payment run types** check box to recover arrearage amounts every time that a worker who has an amount in arrears is paid, regardless of the payment run type. Clear the check box to recover arrearage amounts only in primary payment runs.
        
          - The **Arrear threshold** value prevents the calculations for arrears from entering an infinite loop. The amount under the threshold amount is not placed in arrears and is not recovered. Zero is not a valid amount.
        
        For more information about these controls, see [Payroll parameters (form)](https://technet.microsoft.com/library/jj677433\(v=ax.60\)).

2.  To create the benefits that your organization offers, see [Benefit setup tasks](benefit-setup-tasks.md) and follow these steps:
    
    1.  **Set up benefit elements**: Each benefit consists of three benefit elements: benefit type, a benefit plan, and a benefit option.
    
    2.  **Set up contribution calculations for retirement benefits**.
    
    3.  **Create a new benefit**.

3.  To create the benefits that are used to manage workers’ compensation, see [Benefit setup tasks](benefit-setup-tasks.md) and perform the following task:
    
      - **Set up workers’ compensation plans**.

## 10\. Record payroll information for positions and workers

After workers are set up in Human resources, payroll information must be configured for each position and each worker. Go to [Worker and position payroll tasks](worker-and-position-payroll-tasks.md) and perform all tasks.

For information about how to revise payroll data for workers and positions, see [Payroll data updates](payroll-data-updates.md).

## 11\. Optional: Enter payroll beginning balances

You might want to migrate or transfer beginning balances for earning codes, deductions, benefits, and taxes from another system into Microsoft Dynamics AX.

1.  Complete the following planning steps:
    
    1.  Gather the following information from the previous payroll system:
        
          - Earnings
        
          - Benefits
        
          - Deductions
        
          - Employee taxes
        
          - Employer taxes
        
          - Year-to-date (YTD) amounts
    
    2.  Decide whether to bring over pay statement data in YTD or quarterly increments.
        
        If you enter quarterly beginning balances, you must manually generate and finalize four pay statements per employee. If you enter YTD beginning balances, you must manually generate and finalize only one pay statement per employee.
    
    3.  Make sure that the earning codes that you created to enter beginning balances are effective as of the first day of the employee’s pay cycle in Microsoft Dynamics AX.

2.  Go to [Payroll beginning balance tasks](payroll-beginning-balance-tasks.md) and complete the following tasks:
    
    1.  **Generate earnings statements and pay statements that have beginning balances**.
    
    2.  **Update pay statements that have beginning balances for benefits and taxes**.
    
    3.  **If required: Reverse pay statements**.

## See also

[Setting up payroll: Advanced topics](setting-up-payroll-advanced-topics.md)

[Processing payroll](processing-payroll.md)

[Generating payroll reports](generating-payroll-reports.md)

  


