---
title: Payroll data updates
TOCTitle: Payroll data updates
ms:assetid: 1581d895-9315-4028-8d97-0d52260660d5
ms:mtpsurl: https://technet.microsoft.com/library/Dn876705(v=AX.60)
ms:contentKeyID: 63385343
author: tonyafehr
ms.date: 11/14/2014
mtps_version: v=AX.60
f1_keywords:
- position
- fiscal year
- new fiscal year
- positions
- benefit accrual plan
- PTO
- vacation
- sick time
- qualifying event
- benefit rates
- accrual plan
- accrual plans
- benefit accrual plans
- accrual balance
- accrual plan enrollment
- benefit plan year
- PTO accrual
- vacation accrual
audience: Application User
ms.search.region: USA
---

# Payroll data updates 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


This topic answers questions you might have about how to maintain payroll data.

This topic describes functionality that is available only if the **Payroll - USA** configuration key is selected.

## How do I prepare Payroll for a new fiscal year?

If a pay statement that contains a benefit accrual is generated in one fiscal year and then reversed in the next fiscal year, you might have to adjust the carry-forward balance. You also might have to adjust the carry-forward balance if a pay statement is generated in the new fiscal year before the final pay statement from the previous fiscal year was submitted or posted. For more information about how to adjust benefit accruals, see “Can I adjust the balance in a benefit accrual plan?” later in this topic.

To prepare Payroll for a new fiscal year, you have to set up pay periods and work periods for the year, as described in these steps:

1.  Verify that ledger calendars have been set up for the new year.

2.  Go to [Pay cycle and pay period tasks](pay-cycle-and-pay-period-tasks.md) and complete these tasks:
    
    1.  **Generate pay periods**
    
    2.  **Modify payment dates**

3.  Go to [Payroll calculation frequencies tasks](payroll-calculation-frequencies-tasks.md) and complete the **Associate pay periods with payroll calculation frequencies** task.

4.  Go to [Work cycle and work period tasks](work-cycle-and-work-period-tasks.md) and complete the **Generate work periods** task.

## Can I adjust the balance in a benefit accrual plan?

Yes, you can. You might have to adjust the balance in a benefit accrual plan in these situations:

  - If a worker isn’t enrolled in the plan when they should have been, you can adjust the amounts that were accrued and used so that you can include the correct amounts.

  - If a worker is granted additional time off, you can add that amount to the amount that was accrued.

  - If a worker has reached the maximum accrual limit, you can reduce the amount that was accrued to let the worker accrue additional hours.


> [!IMPORTANT]
> <P>All manual adjustments that you make are accepted, even if they create a plan balance that does not meet the limits that are set by the plan rules. To undo an adjustment, create a new adjustment that offsets the same amount that you added, or that adds the same amount that you subtracted.</P>



To adjust the balance in a benefit accrual plan, follow these steps:

1.  Click **Payroll** \> **Common** \> **Workers** \> **Workers**. Select a worker, click **Personal information**, and then click **Benefit accruals**.

2.  Select a plan and review the plan balances. All balances shown are for the current plan year, except for plans that don’t have a starting date. For those plans, the balances include the total of all amounts that have ever been carried forward, accrued, or used from the plan. The balances include both the amounts that were recorded automatically and any manual adjustments.

3.  Click **Adjust** to create a transaction to change the plan balance.

4.  In the **Adjustment type** field, select the balance to adjust.

5.  In the **Adjustment hours** field, enter the number of hours to change the balance by.
    
    Enter a positive number to increase the balance, and enter a negative number to decrease the balance.

6.  Select a transaction date. The date must be in the current plan year or a future plan year.
    
    Transactions that have a transaction date that is in the current plan year are added to the plan balances immediately. For example, your plan year is from January 1 to December 31. On January 2, you add an accrued amount that has a transaction date of June 1. That accrued amount is added to the balance and is available for the worker to use on January 2, even though the transaction date is June 1.

7.  Optional: Add a comment to explain the reason for the adjustment.

8.  Click **Adjust**.

Repeat these steps to create additional adjustment transactions. To reverse an adjustment, create a second adjustment that has the same type as the adjustment that you want to reverse. Use the same value, but use the opposite sign as the adjustment to reverse. For example, to reverse a carry-forward adjustment of 8.0 hours, create a carry-forward adjustment of -8.0 hours.

## Why can’t I delete a worker enrollment from a benefit accrual plan?

You can delete a worker enrollment from a benefit accrual plan only if these situations apply:

  - You’re logged on to the legal entity where the benefit accrual plan exists.

  - The benefit accrual plan has no balances, or has only manual adjustments or pending usage.

If the plan has a balance that was created when a pay statement was submitted, you can’t delete the worker enrollment from the plan, but you can deactivate the enrollment. To do this, in the **Benefit accruals** form, select both the **Stop accrual** and **Stop balance reduction** check boxes.

When the **Stop accrual** check box is selected, no hours accrue in the plan for this worker. When the **Stop balance reduction** check box is selected, validation doesn’t occur for hours used, and hours from the plan that are used aren’t subtracted from the worker’s available balance. When you select both check boxes, this has the same effect as removing the worker from the plan. Neither accrual transactions nor usage transactions are created when you submit a pay statement, and the plan doesn’t appear on the pay statement or the payment.

## Why aren’t hours accruing in a worker’s benefit accrual plan?

If hours aren’t accruing, this usually occurs for one or more of these reasons:

  - The worker isn’t enrolled in the plan.

  - The **Stop accrual** check box is selected in the **Benefit accruals** form.

  - The plan balance has reached the maximum accrual limit for the year. Review the plan rules in the **Benefit accrual plans** form.

## How do I update benefit rates before the new plan year?

When the amount or rate that is used to calculate payroll deductions and employer contributions for a benefit changes, you have to change it both on the benefit itself and on the benefit records of the workers who are enrolled in that benefit. A yellow message bar notifies you when the rates for the worker enrollments don’t match the rates for the benefit.

You can use an automated process to update rates for workers who have a rate source of **Benefit**. You must manually update rates for workers who have a rate source of **Custom**.


> [!NOTE]
> <P>If the time zone that is set for the legal entity differs from the time zone where the benefit was created, the automated process might cause some dates to be off by one calendar day. If this occurs, you can adjust the dates by running the process again.</P>



In AX 2012 R3 and cumulative update 7 or later for AX 2012 R2:

### Update the rate on the benefit

1.  On the **Benefits** list page, select a benefit. Review the current rate information for the benefit under the grid.

2.  Click **Maintain versions**.

3.  On the **Payroll details** FastTab, click **Add**.

4.  In the **Effective** field, select the date when the new rate takes effect.

5.  Enter new values in the **Frequency**, **Basis**, and **Amount or rate** fields, and then close the form.

After you have updated rates on the benefit, see [Worker and position payroll tasks](worker-and-position-payroll-tasks.md) for information about how to update the benefit rates for the workers who are enrolled in the benefit.

### Update rates for workers when the rate source is Benefit

1.  Click **Payroll** \> **Setup** \> **Benefits** \> **Benefits**.

2.  Select a benefit. Review the current rate information for the benefit under the grid.

3.  Click **Update benefit rates**. Depending on how many workers are enrolled in the benefit, the update might take some time.

### Update rates for workers when the rate source is Custom

1.  Click **Payroll** \> **Setup** \> **Benefits** \> **Benefits**.

2.  Select the benefit to update custom rates for. To the right of the grid, review the **Payroll details custom rates** list. The workers in this list have custom rates for the benefit. Click **\&More...** to see a list of all workers who have custom rates for the selected benefit.
    
    To see more information about custom rates for workers, use the **Worker benefit and deduction setup** inquiry form.

3.  Select a worker who has a custom rate that you want to update. Click **Personal information**, and then click **Benefits**.

4.  In the list of benefits that the worker is enrolled in, select the benefit to update.

5.  Click the **Payroll details** FastTab. The fields on this FastTab vary, depending on how the **Payroll impact** field in the **Benefit elements** form is set.

6.  Enter the new custom rates for this worker for the selected benefit:
    
      - If the rate source for the deduction is **Custom**, update the amount in the **Deduction** field.
    
      - If the rate source for the contribution is **Custom**, update the amount in the **Contribution** field.

7.  Repeat steps 2 through 6 for all workers who have custom rates that you have to update.

## How do I change payroll settings when a worker changes to a new position assignment?

Before you can make the necessary payroll changes, the worker and position information must already be changed in the Human resources module.

To change the payroll settings after that is done, follow these steps:

1.  Go to [Worker and position payroll tasks](worker-and-position-payroll-tasks.md) and complete these tasks to update the worker:
    
    1.  **Add earning codes to worker position assignments**
    
    2.  **Set up worker tax regions**: If the new position is in a different tax region, add the new worker tax region.
    
    3.  **Assign default tax regions**: A default tax region is required for each position that a worker holds.
    
    4.  **Configure worker tax codes**: If the new position is in a different tax region, or if it is paid by a different legal entity, you can assign additional tax codes to the worker. You must set up these tax codes before the worker can be paid.

2.  When you change a worker position, this also might change which benefits the worker is eligible for. Go to [Key tasks: Determine benefit eligibility](key-tasks-determine-benefit-eligibility.md) and complete these tasks:
    
    1.  **Create an eligibility event**
    
    2.  **Process eligibility for benefits**
    
    3.  **Enroll workers in benefits**

3.  Go to [Worker and position payroll tasks](worker-and-position-payroll-tasks.md) and, for each benefit that you enrolled the worker in, perform the **Set up payroll information for benefits** task.

## How do I change benefits for a worker after a qualifying event?

When a worker has a qualifying life event that allows for a change of benefits, other payroll data for that worker might also change because of the event.

To change the benefits, follow these steps:

1.  Go to [Key tasks: Determine benefit eligibility](key-tasks-determine-benefit-eligibility.md) and complete these tasks:
    
    1.  **Create an eligibility event**
    
    2.  **Process eligibility for benefits**
    
    3.  **Enroll workers in benefits**

2.  Go to [Worker and position payroll tasks](worker-and-position-payroll-tasks.md) and, for each benefit that you enrolled the worker in, perform the **Set up payroll information for benefits** task.

3.  If the worker has moved to a new location, go to [Worker and position payroll tasks](worker-and-position-payroll-tasks.md) and complete these tasks:
    
    1.  **Set up worker tax regions**
    
    2.  **Change worker residency**

## Don't see your question here?

We're working to include as many questions as we can, so that Microsoft Dynamics AX Help will be more useful to people just like you.

Tell us what question you would like to add to this topic. Send email to <adocs@microsoft.com>.

  


