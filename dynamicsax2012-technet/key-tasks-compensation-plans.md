---
title: 'Key tasks: Compensation plans'
TOCTitle: 'Key tasks: Compensation plans'
ms:assetid: 8136620d-1758-4068-9348-2fd62273fc60
ms:mtpsurl: https://technet.microsoft.com/library/Hh781095(v=AX.60)
ms:contentKeyID: 43894507
author: tonyafehr
ms.date: 09/03/2014
mtps_version: v=AX.60
f1_keywords:
- salary
- payment
- pay
- salaries
- compensation
- remuneration
audience: Application User
ms.search.region: Global
---

# Key tasks: Compensation plans 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic contains key information about compensation plans.

## What do you want to do?

Learn more about...

Create a fixed compensation plan

Create an eligibility rule for a compensation plan

Enroll an employee in a fixed compensation plan

Maintain or change the fixed compensation of an employee

Create a variable compensation plan

Enroll an employee in a variable compensation plan

Add exceptions to an employee's variable plan enrollment

Create and run a process event

View the results of a process event for an employee

Enable recommendations on fixed or variable plans

Use recommendations to adjust fixed increases or awards

Approve an employee’s compensation change

Update compensation from a compensation process event

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[About compensation plans](about-compensation-plans.md)

 

## Create a fixed compensation plan

Use one of the following procedures to set up a fixed compensation plan.

## Create a fixed compensation plan using the Fixed compensation plan form

Use this procedure if you do not use a compensation system that is external to Microsoft Dynamics AX.

1.  Click **Human resources** \> **Periodic** \> **Compensation** \> **Fixed compensation plans**.

2.  Click **New**.

3.  In the **Type** field, select **Band**, **Grade**, or **Step** type.

4.  If you selected **Band** in the previous step, you can select the **Market price indicator** check box to use the market price ranges that are entered for each job, in addition to the broad compensation ranges that are entered for this compensation plan.

5.  Select an option in the **Out of range tolerance** field to indicate how restrictions on manual pay rate changes should be handled.

6.  Select the **Enable recommendation** check box to enable a manager or a compensation administrator to suggest changes to the guideline amounts that are calculated for the plan.

7.  Select **Percent** in the **Hire rule** field to indicate if prorated pay should be used for employees that are hired during the compensation cycle.

8.  Optional: To transition employees toward the control point for their jobs, on the **Range utilization matrix** tab, add steps for a range utilization matrix. For more information, see [About compensation plans](about-compensation-plans.md).

9.  Press CTRL+S.

10. Click **Set up compensation** to open the **Set up compensation** form, where you can select one of the following options:
    
      - **Set up new compensation matrix** – Select a reference point setup. The reference point setup that you select determines the compensation structure for the fixed compensation plan.
    
      - **Create new from existing compensation matrix** – Copy an existing compensation structure that was created for another plan.
        
        For example, suppose that employees who are located in compensation region A should be paid 10 percent more than those in compensation region B. You would create a plan for the compensation region A employees, and then select **Create new from existing compensation matrix** when you create the plan for the compensation region B employees. You can then modify the compensation structure of the copied plan by 10 percent.
    
      - **Use existing compensation matrix** – Use the same compensation structure as a plan that already exists.
        

        > [!NOTE]
        > <P>Any changes that you make to the wage levels that are in the compensation structure are reflected in any other compensation plan setup where this compensation structure is used.</P>



11. After you select an option in the **Set up compensation** form, click **OK** to open the **Compensation structure** form, where you can review the levels and wage ranges for the compensation structure lines.

12. Adjust the levels and wage ranges, as necessary, and then close the **Compensation structure** form. To adjust multiple values in the grid at the same time:
    
    1.  Click the **Mass change** button.
    
    2.  Select an **Adjustment type**.
    
    3.  Enter an **Adjustment amount**.
    
    4.  Click **Apply to grid**.
    
    5.  Click **Close** to save the values in the grid.
        

        > [!TIP]
        > <P>For more information, see <A href="https://technet.microsoft.com/library/hh803022(v=ax.60)">Compensation structure (form)</A>.</P>



13. Click the **General** tab in the **Fixed compensation plans** form, and select a control point in the **Control point** field. The control point is the target pay rate for a job that is covered by the current plan and comes from the reference point setup.

14. Enter information in the remaining fields, as needed. For more information, see [Fixed compensation plans (form)](https://technet.microsoft.com/library/hh242871\(v=ax.60\)).

## Create a fixed compensation structure using the Compensation grid form

If your company uses external compensation systems, you can use the **Compensation grids** form to set up basic compensation structures.


> [!NOTE]
> <P>Compensation structures that are created in the <STRONG>Fixed compensation plans</STRONG> form are automatically copied to the <STRONG>Compensation grids</STRONG> form. However, a compensation structure that is created in the <STRONG>Compensation grids</STRONG> form is not copied to the <STRONG>Fixed compensation plans</STRONG> form.</P>



1.  Click **Human resources** \> **Setup** \> **Compensation** \> **Compensation grids**.

2.  Click **New**.

3.  Enter a name and a description for the grid.

4.  In the **Type** field, select the compensation level type for the structure.

5.  Select the reference point setup for the structure. The reference points included in the reference point setup determine the ranges that you can use to set up wage range guidelines for each level in the structure.

6.  Select the currency for the structure.

7.  Enter the effective and expiration dates for the structure.

8.  Click **Compensation structure** to open the **Compensation structure** form, where you can modify the wage range guidelines for the structure. For more information, see [Compensation structure (form)](https://technet.microsoft.com/library/hh803022\(v=ax.60\)).

Back to top

 

## Create an eligibility rule for a compensation plan

Use eligibility rules to identify employees who are eligible for compensation plans. Before you can create an eligibility rule, you must have created one or more compensation plans. You can also select a set of compensation levels to specify the job levels of the jobs to be available for a plan.

1.  Click **Human resources** \> **Periodic** \> **Compensation** \> **Eligibility rules**.

2.  Click **New**.

3.  Enter a name and description for the eligibility rule.

4.  Enter effective and expiration dates and times for the eligibility rule.

5.  Select the compensation plan type to create an eligibility rule for.

6.  Select the compensation plan to create an eligibility rule for.

7.  Select the organizational criteria for eligibility in the compensation plan.
    
    For example, only employees who work in a specific department might be eligible for the compensation plan associated with the eligibility rule. If this is the case, you would select the specific department in the **Department** field.

8.  Select the job criteria for eligibility in the compensation plan.
    
    For example, only employees who work in a specific job type might be eligible for the compensation plan associated with the eligibility rule. If this is the case, you would enter the specific job type in the **Job type** field.

### Add levels to an eligibility rule

1.  Click **Human resources** \> **Periodic** \> **Compensation** \> **Eligibility rules**.

2.  Select an eligibility rule to add levels to.

3.  Select the **Enable levels** check box and then press CTRL+S to save the information in the form.

4.  Click **Levels** to open the **Eligibility levels** form.

5.  Select the levels for the eligibility rule.

Back to top

 

## Enroll an employee in a fixed compensation plan

Before you can enroll an employee in a fixed compensation plan, the employee must meet the criteria that are defined in an eligibility rule for the plan.

1.  Click **Human resources** \> **Common** \> **Workers** \> **Workers**. On the **Action Pane**, click **Compensation** tab \> **Employee compensation** group \>**Fixed plan**.
    

    > [!WARNING]
    > <P>You can only open the <STRONG>Employee fixed compensation</STRONG> form if the selected employee is eligible for the fixed compensation plan.</P>



2.  Click **New** to open the **Create compensation** form.

3.  In the **Action** field, select the compensation action or the reason for entering the record.

4.  In the **Position** field, select the position in which the person works.

5.  In the **Plan** field, select the plan to enroll the employee in. The plans that are available are determined by eligibility rules for the fixed compensation plans. Employees must meet the criteria defined in the eligibility rule for a plan to be eligible for the plan.

6.  For **Step** type plans only, in the **Step** field, specify the step in the compensation structure that corresponds to the pay rate to be granted to the employee. The pay rate associated with the step is displayed in the **Pay rate** field.

7.  For **Grade** and **Band** type plans, enter the fixed base salary amount in the **Pay rate** field. A warning might be displayed if the pay rate that you enter is not in the range that is specified by the plan.

8.  Click **OK** to save the information and return to the **Employee fixed compensation** form.
    

    > [!NOTE]
    > <P>After the information is saved, you cannot modify it in the <STRONG>Employee fixed compensation</STRONG> form. To modify fixed compensation information, click <STRONG>Change compensation</STRONG>. You might do this, for example, to specify a merit increase.</P>



Back to top

 

## Maintain or change the fixed compensation of an employee

1.  Click **Human resources** \> **Common** \> **Workers** \> **Workers**. On the **Action Pane**, click **Compensation** tab \> **Employee compensation** group \> **Fixed plan**.

2.  Click **Change compensation**.

3.  Select an action to indicate why you are changing the fixed compensation for the employee.

4.  Modify the remaining fields on the form, as necessary, and then click **OK**.

Back to top

 

## Create a variable compensation plan

1.  Click **Human resources** \> **Periodic** \> **Compensation** \> **Variable compensation plans**.

2.  Click **New**.

3.  Enter a name and description for the plan.

4.  Enter the effective and expiration dates for the plan.

5.  Select the plan type.

6.  In the **Variable award basis** field, select one of the following options:
    
      - **Percent of basis** – Select this option to determine the variable award based on a percentage of the base pay.
    
      - **Number of units** – Select this option to use a specific variable award amount. For example, select this option to award a specific monetary amount or a specific number of shares of stock.

7.  If you selected **Number of units** in the previous step, enter the number of units to award.
    
    If you selected **Percent of basis** and the compensation plan type is a cash plan type, go to step 11.
    
    If you selected **Percent of basis** and the compensation plan type is a non-cash plan type, go to the next step.

8.  If one award unit is equal to the value of one unit of the currency that you use to pay the employees who will be enrolled in the plan, select the **1:1 relationship** check box.
    

    > [!NOTE]
    > <P>For cash plans that have a specific variable amount, this check box is automatically selected and you cannot modify it.</P>



9.  Enter the currency in which the unit is valued. This field is required for stock awards if you did not select the **1:1 relationship** check box.
    

    > [!NOTE]
    > <P>Cash awards are based on the currency in which fixed compensation is paid.</P>



10. Enter the value of one unit. This field is available only if you did not select the **1:1 relationship** check box.
    
    If the value of the award is more or less than 100 percent of their fixed pay rate, enter the value here. For example, if the compensation plan awards stock to employees, enter the value of the stock. If this is a cash award, enter the amount of the award. For example, to award a 1,000 bonus USD, enter 1000.

11. Select a vesting rule. Vesting rules are for reporting, only, and are used to classify compensation plans.

12. Select the **Annualize the basis** check box to make sure that variable awards are calculated against an employee’s annualized fixed pay rate.
    

    > [!NOTE]
    > <P>If this check box is not selected, employees with fixed pay rates entered in monthly, weekly, or hourly frequencies will have their variable award calculated as a single month, a single week, or a single hour award.</P>



13. If all employees enrolled in the plan should receive an award of the same percentage of their fixed pay, enter the percentage of base pay to award. This field is only available if you selected **Percent of basis** in the **Variable award basis** field.

14. Select the **Recommendation** check box if recommendations should be enabled for the plan. This lets you suggest a pay amount that is different from the amount that is calculated by the settings in the plan.

15. Select **None** or **Percent** in the **Hire rule** field to specify to use prorated pay for employees that are hired during the compensation cycle.

16. If employees enrolled in the plan are at different compensation levels and should be awarded different percentages, select the **Enable levels** check box, and then click the **Levels** button to open the **Levels** form, where you can enter the percentages for the awards.

17. In the **Variable compensation plans** form, select an option under the **Variable award basis** field group to indicate whether to calculate the award using an employee's fixed pay rate, or the control point that is associated with an employee’s fixed compensation plan.

18. Select one of the following calculation methods for the plan:
    
      - **Composite** – Prorates all changes in compensation for the employee for the compensation cycle when an award amount is calculated.
    
      - **Point-in-time** – Uses compensation information that is active at a specific point in time only.

19. Optional: To base the award on the overall performance of a specific department, enter information on the **Leverage** tab. For descriptions of the fields on the **Leverage** tab, see [Variable compensation plans (form)](https://technet.microsoft.com/library/hh803020\(v=ax.60\)).

Back to top

 

## Enroll an employee in a variable compensation plan

1.  Click **Human resources** \> **Common** \> **Workers** \> **Workers**. Select a worker to enroll in a variable compensation plan. On the **Action Pane**, click **Compensation** tab \> **Employee compensation** group \> **Variable plan enrollment**.

2.  Select the plan to enroll the employee in.

3.  Enter the effective dates for enrollment in the plan in the **Start date/time** and **End date/time** fields.
    

    > [!NOTE]
    > <P>The <STRONG>Start date/time</STRONG> can also be set to a date in the past if the employee was hired in the compensation period and was not eligible for a full incentive award.</P>



Back to top

 

## Add exceptions to an employee's variable plan enrollment

Use the following procedure to override some of the elements in an employee's variable compensation plan enrollment.

1.  Click **Human resources** \> **Common** \> **Workers** \> **Workers**. Select a worker who is enrolled in a variable compensation plan. On the **Action Pane**, click **Compensation** tab \> **Employee compensation** group \> **Variable plan enrollment**.

2.  Click the **Overrides** FastTab and enter any of the following information that applies to the current employee:
    
      - **Hire rule date** – Enter a hire rule date to override the date of the employee's enrollment in the variable plan.
    
      - **Award percent** – Enter an award percentage to override the information defined for the variable compensation plan. The award percentage is subject to the calculation rules of the plan setup and other settings that are used to calculate the incentive award. Individual and organizational performance factors are applied when the final award is calculated, if they are enabled by the plan.
    
      - **Award amount** – Enter an award amount to override the information in a variable compensation plan. This award amount represents the actual amount of the award and is not affected by any other event process calculations. Individual and performance factors are not applied when the final award is calculated.

3.  Click the **Organizational overrides** FastTab to enter one or more departments whose performance will affect the final award, and then indicate the percentages of performance contribution for each department.
    

    > [!NOTE]
    > <P>The total percentage of the departments must always equal 100 percent.</P>



Back to top

 

## Create and run a process event


> [!NOTE]
> <P>We recommend that you use the same fixed or variable compensation plan in only one process event setup or work stream. If a plan is used in several process event setups or work streams, it could cause duplicate calculations.</P>



1.  Click **Human resources** \> **Periodic** \> **Compensation** \> **Process events**.

2.  Click **New**.

3.  Enter a name and description for the process event.

4.  Enter the effective and expiration dates for the process event. These dates are for your information, only, and do not affect the process events.

5.  Select the process type. The process type is for categorization only.

6.  Click the **Date setup** FastTab and enter the following information:
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <tbody>
    <tr class="odd">
    <td><p>Cycle starting and ending dates</p></td>
    <td><p>Enter dates for the period when the merit increase or award guideline is calculated.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Transaction active date</strong></p></td>
    <td><p>Enter the date when the new calculated compensation information is active and when variable awards are paid out.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Point-in-time date</strong></p></td>
    <td><p>If the process event includes variable plans that use the <strong>Point in time</strong> calculation method, enter the date that the award information should be calculated for.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Fixed pay pro rated hire date</strong></p></td>
    <td><p>If employees are hired on a date that is after the starting date of the compensation cycle, enter the date when the merit increase should be calculated. For example, your compensation period is one calendar year. Employees who were hired after January 1, 2012, should not receive a merit increase that is calculated using the entire compensation period. Instead, you might have a company policy that new employees can only receive a merit increase that is calculated using half of the compensation period. For this example, enter July 1, 2012.</p></td>
    </tr>
    </tbody>
    </table>


7.  Save the information that you entered, and then click **Setup** to open the **Set up process event** form.

8.  In the **Type** field in the upper part of the **Set up process event** form, select **Fixed** or **Variable**, depending on the type or guideline that you are creating.

9.  Select the **Enable pay for performance** check box to include performance ratings in the calculation.

10. In the **Action** field in the lower part of the form, add one or more compensation action for the process, for example, **Merit**, or the **General award** variable compensation action.
    

    > [!WARNING]
    > <P>For fixed compensation plans, you can add multiple actions to a process event. For variable compensation plans, you can only add one action to a process event.</P>



11. Select the **Enable recommendation** check box to enable recommendations. For more information, see [Recommendation (form)](https://technet.microsoft.com/library/hh802985\(v=ax.60\)).
    

    > [!NOTE]
    > <P>To enable recommendations on the process event, the fixed or variable compensation plan must be set up to enable recommendations.</P>



12. Click the **General** tab in the lower part of the form to enter additional information.
    
    You can indicate whether the result of the previous fixed compensation action in the process event should be used in the calculation or whether the original basis should be used. You can also indicate the amount of the general increase. For **Step** plans, you can enter the number of steps that the pay is increased. For more information about the fields on this form, see [Setup process event (form)](https://technet.microsoft.com/library/hh209544\(v=ax.60\)).

13. Close the **Set up process event** form.

14. In the **Process events** form, click **Run process**.

15. In the **Create compensation process events** form, select **Show info** to view an **Infolog** dialog that displays detailed information about the process after it is run.

16. Click **OK** to run the compensation process.

Back to top

 

## View the results of a process event for an employee

1.  Click **Human resources** \> **Periodic** \> **Compensation** \> **Compensation events**.

2.  Select the compensation event to view information for and then click **Employees**.

3.  Select the employee to view calculated compensation information for, and then click **Recommendation** to view the calculated compensation guidelines for the employee.

Back to top

 

## Enable recommendations on fixed or variable plans

When you enable recommendations on a compensation plan, you permit changes to the calculated guideline amount for employees. Therefore, after you run your compensation process event, you can review the compensation award or increase for each employee and modify it, if it is needed.

1.  Click **Human resources** \> **Periodic** \> **Compensation** \> **Fixed compensation plans**.
    
    –or–
    
    Click **Human resources** \> **Periodic** \> **Compensation** \> **Variable compensation plans**.

2.  Click the **General** FastTab, and select the **Recommendation** check box.

Back to top

 

## Use recommendations to adjust fixed increases or awards

1.  Click **Human resources** \> **Periodic** \> **Compensation** \> **Compensation events**.

2.  Select an event, and then click **Employees**.

3.  Select the employee to recommend a fixed increase or an award amount for, and then click **Recommendation**.

4.  Enter your recommendation as follows:
    
      - Enter fixed recommendations on the **Fixed overview** or **Fixed general** tab.
    
      - Enter variable composite plan recommendations on the **General** tab or in the fields in the **Recommended** field group on the **Composite overview** tab.
    
      - Enter variable point-in-time plan recommendations on the **General** tab.

Back to top

 

## Approve an employee’s compensation change

Before you can update the compensation information, or transactions, in an employee’s compensation records, you must approve the compensation changes for the employee.

1.  Click **Human resources** \> **Periodic** \> **Compensation** \> **Compensation events**.

2.  Select a compensation event.

3.  Click **Employees**.

4.  Select an employee to approve compensation changes for and then click **Change status** \> **Approved**.

5.  Repeat step 4 for each employee.

Back to top

 

## Update compensation from a compensation process event

If calculated compensation guidelines are correctly calculated by a process event and additional recommendations are not needed for the employees affected by the process event, you can update the compensation information, or transactions, to the employees’ compensation records. You can only update compensation information for employees whom you approved compensation changes for. See the previous procedure for more information.

1.  Click **Human resources** \> **Periodic** \> **Compensation** \> **Compensation events**.

2.  Select the compensation event to update.

3.  Click **Load compensation**.

Back to top

## Find form help

[Fixed compensation plans (form)](https://technet.microsoft.com/library/hh242871\(v=ax.60\))

[Employee fixed compensation (form)](https://technet.microsoft.com/library/hh697729\(v=ax.60\))

[Change compensation (form)](https://technet.microsoft.com/library/hh781087\(v=ax.60\))

[Variable compensation plans (form)](https://technet.microsoft.com/library/hh803020\(v=ax.60\))

[Employee variable compensation enrollment (form)](https://technet.microsoft.com/library/hh697697\(v=ax.60\))

[Eligibility rules (form)](https://technet.microsoft.com/library/hh597167\(v=ax.60\))

[Eligibility levels (form)](https://technet.microsoft.com/library/hh597347\(v=ax.60\))

[Compensation grids (form)](https://technet.microsoft.com/library/hh694712\(v=ax.60\))

## Find related tasks

[Key tasks: Pay for performance](key-tasks-pay-for-performance.md)

  


