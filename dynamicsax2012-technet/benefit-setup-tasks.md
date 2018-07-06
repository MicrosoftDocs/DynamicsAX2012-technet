---
title: Benefit setup tasks
TOCTitle: Benefit setup tasks
ms:assetid: c3c38da5-8889-4271-88c3-ad9acbc1fb7b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677359(v=AX.60)
ms:contentKeyID: 49384134
ms.date: 11/14/2014
mtps_version: v=AX.60
f1_keywords:
- payroll
- benefits
- medical
- benefit
- retirement plans
- insurance
- Forms.PayrollBenefitCalculationRateSetup
- benefit setup
- MsDynAx060.Forms.PayrollBenefitCalculationRateSetup
---

# Benefit setup tasks 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic describes how to set up current and future benefits that workers and their dependents and beneficiaries can receive, and also how to maintain payroll information for benefits. Examples of benefits include medical insurance, retirement investments, workers’ compensation plans, and parking benefits.

Garnishments and tax levies are also set up as benefits, although the steps that you must follow to set them up are different. For more information, see [Garnishment and tax levy setup tasks](garnishment-and-tax-levy-setup-tasks.md).

After you set up benefit elements by using the **Benefit elements** form, you must create the benefits so that they can be assigned to workers. When you create a benefit, you link an option to a benefit plan, designate a benefit period, and assign eligibility rules to the benefit.

The following illustration shows the steps that you must follow to set up benefits and mandatory deductions. The numbers correspond to the procedures later in this topic.

![Steps for setting up benefits](images/JJ677359.Payroll_Benefit_setup(AX.60).gif "Steps for setting up benefits")

## What do you want to do?

Understand the bigger process

Review the prerequisites

1\. Set up benefit elements

2\. Set up contribution calculation rates for retirement benefits

3\. Create a new benefit

4\. Set up workers’ compensation plans

Next step

Technical information for system administrators

Find form help

Find related tasks

## Understand the bigger process

The following illustration shows the relationship between this topic and the overall process of setting up Payroll for the first time.

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

## 1\. Set up benefit elements

A benefit is a combination of the benefit type, plan, and option:

  - **Type** – A collection of plans for a specific benefit, such as medical or parking.

  - **Plan** – A specific benefit that is contracted from a provider.

  - **Option** – The coverage level, such as employee only or employee and spouse.

### 1a. Set up benefit types

1.  Click **Human resources** \> **Setup** \> **Benefits** \> **Benefit elements**.

2.  In the **Types** area, click **New** to create a benefit type.

3.  Enter this information.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Type</strong></p>
    <p><strong>Description</strong></p></td>
    <td><p>Enter the name and a brief description of the benefit type.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Concurrent enrollment</strong></p></td>
    <td><p>Select one of the following concurrent enrollment options:</p>
    <ul>
    <li><p><strong>Multiple enrollments per type</strong> – You can enroll a worker in multiple plans that have the same benefit type, even if the enrollment is effective for the same period. For example, a worker can be enrolled in two term life insurance plans.</p></li>
    <li><p><strong>One enrollment per type</strong> – You can’t enroll a worker in more than one plan that has the same benefit type for the same period. For example, if the worker already has health insurance for a specified time period, you can’t enroll the worker in another health insurance plan that covers the same period.</p></li>
    </ul></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Payroll category</strong></p></td>
    <td><p>Select a payroll category to use for benefits that have the new benefit type. The payroll category determines which settings are available for a selected plan in the <strong>Plans</strong> area of this form. Settings that don’t apply to the payroll category aren’t available.</p></td>
    </tr>
    </tbody>
    </table>


Repeat these steps to set up additional benefit types. When you have finished, you can close the form, or continue with “Set up benefit plans.”

### 1b. Set up benefit plans

1.  Click **Payroll** \> **Setup** \> **Benefits** \> **Benefit elements**.

2.  In the **Plans** area, click **New** to create a benefit plan.

3.  Enter this form-level information.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Plan</strong></p>
    <p><strong>Description</strong></p></td>
    <td><p>Enter the name and a brief description of the benefit plan.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Type</strong></p></td>
    <td><p>Select the benefit type.</p>
    <p>The payroll category that is associated with the selected benefit type controls the options that are available for the benefit plan. For example, options that are related to retirement plans are available only when the payroll category for the benefit type is <strong>Retirement</strong>.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Payroll impact</strong></p></td>
    <td><p>Select one of these options:</p>
    <ul>
    <li><p><strong>None</strong> – No amounts are contributed by the employer or deducted from the worker’s pay. When this is selected, the FastTabs aren’t available in this form.</p>
    <div class="alert"> 

    > [!NOTE]
    > <P>When the payroll category for the benefit type is <STRONG>None</STRONG>, the payroll impact is also <STRONG>None</STRONG>.</P>


    </div></li>
    <li><p><strong>Deduction only</strong> – An amount is deducted from the worker’s pay for this benefit, but no employer contribution is made.</p>
    <p>When you select this option, controls that are related to payroll deductions are available on the other FastTabs, but controls that are related to employer contributions aren’t available.</p></li>
    <li><p><strong>Contribution only</strong> – An employer contribution is made for this benefit, but no amount is deducted from the worker’s pay.</p>
    <p>When you select this option, controls that are related to employer contributions are available on the other FastTabs, but controls that are related to payroll deductions aren’t available.</p></li>
    <li><p><strong>Deduction and contribution</strong> – An employer contribution is made for this benefit, and an additional amount is deducted from the worker’s pay.</p>
    <p>When you select this option, controls that are related both to employer contributions and to payroll deductions are available on the other FastTabs.</p></li>
    </ul></td>
    </tr>
    </tbody>
    </table>


4.  On the **Tax rule** FastTab, select the pretax basis for the plan. The pretax basis determines the pattern of before-tax and after-tax treatment for payroll deductions and employer contributions.
    
    In the rare case that no preset options are appropriate for your plan, select **Custom**, and then select a custom pretax method to specify the taxes that should not be deducted from the paychecks of employees who enroll in the plan. For more information, see [Benefit elements (form)](https://technet.microsoft.com/en-us/library/hh209498\(v=ax.60\)).
    

    > [!WARNING]
    > <P>Select <STRONG>Custom</STRONG> only when no preset patterns are appropriate. If you must use <STRONG>Custom</STRONG>, work with your legal advisors to make sure that you select the correct settings for the benefit plan.</P>



5.  If the payroll category of the benefit type that is used for this plan is **Retirement**, enter this information on the **Retirement plans** FastTab.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Retirement type</strong></p></td>
    <td><p>Select the type of retirement plan.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Contribution limit</strong></p></td>
    <td><p>Select the value that the maximum contribution for this benefit plan is based on:</p>
    <ul>
    <li><p><strong>None</strong> – There is no contribution limit.</p></li>
    <li><p><strong>Employee limit</strong> – The employer contribution stops when the employee’s payroll deduction limit is reached. For the payment in which the deduction limit is reached, the employer contribution is proportionally limited. For example, if only half of the expected employee deduction can be made before the limit is reached, only half of the employer contribution is made.</p></li>
    <li><p><strong>Fixed</strong> – The employer contribution limit is a fixed amount per calendar year. The amount is set in the contribution limit field on the benefit plan.</p></li>
    <li><p><strong>Combination</strong> – Both the employee limit method and the fixed method are evaluated, and the employer contribution is limited by whichever method reaches the limit first.</p></li>
    </ul>
    <p>The actual amount of the contribution limit is entered on the <strong>Payroll details</strong> FastTab.</p></td>
    </tr>
    </tbody>
    </table>


6.  On the **Payroll details** FastTab, specify this information.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Lock pay statement</strong></p></td>
    <td><p>Select this check box to prevent pay statement lines that include the benefit plan from being changed.</p>
    <p>When this check box is selected, lines that include the benefit plan can be added to or deleted from the pay statement, but lines that include this benefit plan can’t be changed.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Recover arrear</strong></p></td>
    <td><p>Select this check box to recover arrearages for benefits that are based on this plan.</p>
    <p>This check box is available only if the payroll category on the benefit type that is used for this plan is <strong>Standard</strong>.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Deduction method</strong></p></td>
    <td><p>Select the method to use to determine the deduction amount if the employee’s pay isn’t sufficient to cover the whole amount of the deduction for the selected benefit plan:</p>
    <ul>
    <li><p><strong>All or nothing</strong> – If the whole amount of the deduction can’t be made, no amount is deducted. The whole amount is placed in arrears.</p></li>
    <li><p><strong>Partial</strong> – Deduct as much of the deduction amount as possible. Any remaining amount is placed in arrears.</p></li>
    </ul></td>
    </tr>
    <tr class="even">
    <td><p><strong>Payment type</strong></p></td>
    <td><p>Select at least one of the following payment run types:</p>
    <ul>
    <li><p><strong>Primary</strong></p></li>
    <li><p><strong>Additional</strong></p></li>
    <li><p><strong>Gross up</strong></p></li>
    </ul>
    <p>Deductions and contributions for the selected benefit plan are included in payroll calculations for payroll runs that result in the payment run types that you select in this step. For more information about payment run types, see <a href="earning-code-and-earning-code-group-tasks.md">Earning code and earning code group tasks</a>.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Deduction priority</strong></p></td>
    <td><p>Assign a number to designate the default order that deductions for a benefit are made in, relative to other deductions.</p>
    <p>Amounts are deducted from pay statements starting with the benefit that has the lowest deduction priority number. When multiple benefits have the same number, the deductions for those benefits are made in alphabetical order.</p>
    <div class="alert"> 

    > [!WARNING]
    > <P>Certain benefits are considered mandatory deductions in some states. Those benefit plans should have the highest deduction priority, which means, the lowest deduction priority number. The lowest possible deduction priority number is 0 (zero).</P>
    > <P>In many states, deductions for garnishments and tax levies must be made before deductions for any other benefits are made. For more information, see <A href="garnishment-and-tax-levy-setup-tasks.md">Garnishment and tax levy setup tasks</A>.</P>
    > <P>Your legal advisors should help you determine the deduction priorities for the benefit plans that you offer.</P>


    </div>
    <p>By default, the value in this field is entered in the <strong>Maintain benefits</strong> form when a worker is enrolled in a benefit. You can change the value for a worker at the time of enrollment or at any other time.</p>
    <p>If you change the default value, existing benefit assignments don’t change. You must change those values individually.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Default deduction limits</strong></p>
    <p><strong>Default contribution limits</strong></p></td>
    <td><p>Enter the limit amount and the limit period.</p>
    <p>The limit amount is the maximum amount that can be deducted or contributed for the selected benefit during the specified limit period. If there is no maximum amount, leave these fields blank.</p>
    <p>When the payroll category assigned to the benefit type is <strong>Retirement</strong>, the limit period is automatically set to <strong>Year</strong>.</p>
    <p>When payroll is calculated, the limit amount is calculated across the limit period. For example, if the limit amount for deductions is 1200.00 and the limit period is <strong>Year</strong>, when the cumulative amount that has been deducted for the benefit reaches 1200.00, no more is deducted for that benefit for the rest of the year.</p></td>
    </tr>
    </tbody>
    </table>


7.  On the **Accounting** FastTab, select the legal entity to set the accounting information for, and then enter this information.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Category</strong></p></td>
    <td><p>Select the project category to use for the employer contribution. This usually is <strong>Payroll</strong>, although your organization might use a different category.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Vendor</strong></p></td>
    <td><p>Select the vendor that payments for this plan are paid to.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Financial dimensions</strong></p></td>
    <td><p>Enter the default financial dimensions.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Main account</strong></p></td>
    <td><p>Select the main accounts to use for posting deductions and contributions.</p></td>
    </tr>
    </tbody>
    </table>
    
    If the benefit plan is offered by more than one legal entity in your organization, repeat this step for each legal entity.

8.  On the **Reporting** FastTab, if the benefit must be reported on Form W-2, select the number of the box on Form W-2 where the amount of the payroll deductions or employer contributions for the selected benefit are reported, and enter the label to use for the boxes.

Repeat these steps to set up additional benefit plans. When you have finished, you can close the form, or continue with “Set up benefit options.”

### 1c. Set up benefit options

1.  Click **Payroll** \> **Setup** \> **Benefits** \> **Benefit elements**.

2.  In the **Options** area, click **New** to create a benefit option.

3.  Type the name of the option and a description.

4.  To allow for dependents to be covered under the benefit, select the **Allow dependent coverage** check box.

5.  To allow for the benefit to be designated to beneficiaries, select the **Allow beneficiary designations** check box.

Repeat these steps to set up additional benefit options. When you have finished, close the form.

To create the benefits that you can enroll workers in, see “Create a new benefit” later in this topic.


> [!NOTE]
> <P>To create retirement benefits, you must first set up the contribution calculation rate tables. If you have not yet set up the rate tables, continue with “Set up contribution calculation rates for retirement benefits” and then “Create a new benefit” in this topic.</P>



Back to top

## 2\. Set up contribution calculation rates for retirement benefits

For retirement benefits, the method that is used to determine the employer contribution and the employer contribution rates is determined by the rate table that is defined in the **Contribution calculation rates** form and then assigned to the benefit in the **Benefits** form.

Before you start this task, we recommend that you create a table of your retirement plans. For each plan, include the contribution method, employee deductions, and employer contributions for the plan.

**Example**

Your organization offers two retirement plans. For Plan 1, your organization matches the worker’s own contributions to the plan at 50 percent up to the first 3 percent, and then at 100 percent up to 6 percent. For Plan 2, your organization contributes 1 percent of the worker’s pay to the 401(k) plan when the worker’s own contributions are between 1 percent and 3 percent of their pay; 2 percent when the worker’s own contributions are between 3 percent and 6 percent; and 3 percent of the worker’s pay when the worker’s contributions are 6 percent or more. In this example, your table would look like this.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Plan</p></th>
<th><p><strong>Worker deduction</strong> rate</p></th>
<th><p><strong>Employer contribution</strong> rate</p></th>
<th><p><strong>Contribution method</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Plan 1</strong></p></td>
<td><p>0.0000</p></td>
<td><p>0.5000</p></td>
<td><p><strong>Percent of employee</strong></p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p>0.0300</p></td>
<td><p>1.000</p></td>
<td><p><strong>Percent of employee</strong></p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p>0.0600</p></td>
<td><p>0</p></td>
<td><p><strong>Fixed percent</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Plan 2</strong></p></td>
<td><p>0.0100</p></td>
<td><p>0.0100</p></td>
<td><p><strong>Fixed percent</strong></p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p>0.0300</p></td>
<td><p>0.0200</p></td>
<td><p><strong>Fixed percent</strong></p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p>0.0600</p></td>
<td><p>0.0300</p></td>
<td><p><strong>Fixed percent</strong></p></td>
</tr>
</tbody>
</table>


For Plans 1 and 2, the actual amount that the employer contributes depends on the tier type that you select in the **Contribution calculation rates** form. This list describes each tier type and includes an example of how the tier types affect the employer contribution amount for Plans 1 and 2.

  - **Single line** – Use this tier type to use only one line from the rate table to calculate the employer contribution amount.
    
    For Plan 1, if the worker’s contribution rate is 10 percent of their 1000.00 earnings, the employer contribution is 0.00. For Plan 2, the employer contribution is 30.00 for an employee who earns 1000.00 and whose contribution rate is 10 percent.

  - **Cascading tier** – Use this tier type to use multiple lines from the rate table to calculate the employer contribution amount. Only lines that have a deduction rate of less than or equal to the actual worker’s deduction rate are used to calculate the employer deduction amount.
    
    For Plan 1, if the worker’s deduction rate is 10 percent of their 1000.00 earnings, the employer contribution is 45.00. For Plan 2, the employer contribution is 60.00.

This table lists the formula for calculating the employer contribution amount for Plans 1 and 2 for each tier type.

<table style="width:100%;">
<colgroup>
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Plan</p></th>
<th><p>Tier type</p></th>
<th><p>Employee earnings</p></th>
<th><p>Employee deduction amount</p></th>
<th><p>Employer contribution amount</p></th>
<th><p>Formula used to calculate employer contribution amount</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Plan 1</strong></p></td>
<td><p><strong>Single line</strong></p></td>
<td><p>1000.00</p></td>
<td><p>100.00</p></td>
<td><p>0.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p><strong>Cascading tier</strong></p></td>
<td><p>1000.00</p></td>
<td><p>100.00</p></td>
<td><p>45.00</p></td>
<td><p>(1000 x 0) + ((1000 x (.06 - .03)) x 0.5) + ((1000 x (.03 - .00)) x 1) = 45</p></td>
</tr>
<tr class="odd">
<td><p><strong>Plan 2</strong></p></td>
<td><p><strong>Single line</strong></p></td>
<td><p>1000.00</p></td>
<td><p>100.00</p></td>
<td><p>30.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p><strong>Cascading tier</strong></p></td>
<td><p>1000.00</p></td>
<td><p>100.00</p></td>
<td><p>60.00</p></td>
<td><p>(1000 x .03) + (1000 x .02) + (1000 x .01) = 60</p></td>
</tr>
</tbody>
</table>


Use the data in your own table to set up the contribution calculation rate tables that you need.

### Set up a rate table for a retirement benefit plan

1.  Click **Payroll** \> **Setup** \> **Benefits** \> **Contribution calculation rates**.

2.  Click **New**.

3.  Enter a name and description that identifies the contribution calculation rate table.

4.  Select the tier type for the rate table.
    

    > [!WARNING]
    > <P>The tier type that you select can considerably affect the employer contribution amount of the retirement benefit plan. See the examples in “Set up contribution calculation rates for retirement benefits” earlier in this topic to understand how tier types affect employer contribution amounts.</P>



5.  Click **Maintain versions**.

6.  In the **Maintain rate structure versions** form, there are two **Add** buttons. The form-level button lets you add new versions of the rate table. The grid-level button lets you add rows to the rate table. Click the grid-level **Add** button.

7.  Enter this information for the rate table.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Grid columns</p></th>
    <th><p>Information</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Worker deduction</strong></p></td>
    <td><p>The lowest percentage of a worker’s pay that is matched by an employer contribution at the specified rate.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Employer contribution</strong></p></td>
    <td><p>The matching contribution to an employee’s retirement plan, expressed as a percentage of the employee’s pay or as a percentage of the employee’s own contribution to the plan.</p>
    <p>The <strong>Contribution method</strong> field determines how this rate is used to calculate the amount of the employer contribution.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Contribution method</strong></p></td>
    <td><p>This control is not available in versions of Microsoft Dynamics AX 2012 prior to cumulative update 6 for AX 2012.</p>
    <p>Select the method to use to calculate employer contributions for the selected row.</p>
    <ul>
    <li><p><strong>Fixed percent</strong> - The employer contribution is calculated by multiplying the employer contribution rate by the employee earnings. For example, if the rate for the worker deduction is .03 and the rate for the employer contribution is .02, the amount of the employer contribution is .02, or 2 percent of the employee earnings. For this option, the worker deduction amount and the employer contribution amount are calculated separately.</p></li>
    <li><p><strong>Percent of employee</strong> - The employer contribution is calculated by multiplying the employer contribution rate by the worker deduction rate. For example, if the worker deduction rate is .03 and the employer contribution rate is .5, the amount of the employer contribution is .03 x .5 = .015, or 1.5 percent of the employee earnings.</p></li>
    </ul>
    <div class="alert"> 

    > [!NOTE]
    > <P>The worker deduction and employer contribution rates are determined by the rate table that is defined in the <STRONG>Contribution calculation rates</STRONG> form and then assigned to the benefit in the <STRONG>Benefits</STRONG> form.</P>


    </div></td>
    </tr>
    </tbody>
    </table>


8.  Click the grid-level **Add** button again to add another row. When you have added all the rows that you need for this rate table, close the form.

Repeat this task to create additional contribution calculation rate tables. After you create a rate table, you can assign it to retirement benefits by using the **Benefits** form. For more information, see “Create a new benefit” in this topic.

Back to top

## 3\. Create a new benefit

After you have set up benefit elements by using the **Benefit elements** form, you must create the benefits so that they can be assigned to workers. When you create a benefit, you link an option to a benefit plan, designate a benefit period, and assign eligibility rules to the benefit.

1.  Click **Payroll** \> **Setup** \> **Benefits** \> **Benefits**.

2.  In the **New** group, click **Benefit**, and then enter this information:
    
      - **Plan** – The name of the benefit.
    
      - **Option** – An option to add to the benefit.
    
      - **Effective** – The first date when the benefit is available to a worker.
    
      - **Expiration** – The last date when the benefit is available to a worker.

3.  Click **Create benefit**.

4.  Click **Edit** and then click the **Eligibility rules** FastTab to select the method to use to determine eligibility for this benefit.
    
      - **All workers are eligible** – The benefit is included in eligibility processing, but eligibility rules aren’t enforced for the benefit. All workers are always eligible.
        
        When you select this method, any worker who is included in an eligibility event can enroll in the benefit after the event is processed, but not at any other time. This lets you restrict enrollment in the benefit to the appropriate enrollment periods, without otherwise limiting eligibility for the benefit.
    
      - **Rule based**– User-defined eligibility rules are enforced for the benefit. Select the rule type to use from the **Rule type** list.
        
        This method is used for most benefits.
    
      - **Bypass eligibility process**– The benefit is not included in eligibility processing. Any worker can be enrolled in the benefit at any time. You do not have to process an eligibility event before you enroll a worker in the benefit.
        
        This method is usually used for garnishments and tax levies.

5.  Optional: If there are workers who should be allowed to enroll in this benefit, but who don’t meet the criteria in the eligibility rules, assign an eligibility override for those workers.
    
    1.  On the **Eligibility overrides** FastTab, click **Add**.
    
    2.  In the **Name** field, select the worker to add an override for.
    
    3.  In the **Override start** and **Override end** fields, enter the first and last dates when the override applies. When you determine eligibility for a benefit by using a coverage start date that is in the specified date range, the employee is eligible for the benefit, regardless of the benefit eligibility rules.

6.  On the **Payroll details** FastTab, enter this payroll information for the benefit:
    

    > [!NOTE]
    > <P>This FastTab might include settings only for deductions, only for contributions, or for both deductions and contributions, depending on how the <STRONG>Payroll impact</STRONG> field in the <STRONG>Benefit elements</STRONG> form is set for the benefit plan. If the <STRONG>Payroll impact</STRONG> field is set to <STRONG>None</STRONG>, this FastTab isn’t available. For more information, see <A href="https://technet.microsoft.com/en-us/library/hh209498(v=ax.60)">Benefit elements (form)</A>.</P>
    > <P>The values on this FastTab are used as the default values in the <STRONG>Maintain benefits</STRONG> form for each worker who is enrolled in the selected benefit.</P>

    
      - **Frequency** – The payroll calculation frequency that is used to determine the pay periods that the selected benefit is calculated in. Payroll calculation frequencies and pay periods are defined in the **Payroll calculation frequencies** form.
    
      - **Basis** – The option to use together with the value in the **Amount or rate** field to determine the amount to deduct or contribute for the benefit. The amount is calculated only in the pay periods as determined by the payroll calculation frequency. Earnings are included in the calculation only when the earning code for the earnings is listed on the **Earning basis** FastTab and when the required parameters are set in the **Earning codes** form.
        
        For more information about the basis options, see [Benefits (form)](https://technet.microsoft.com/en-us/library/jj680907\(v=ax.60\)).
    
      - **Amount or rate** – The amount or rate to use together with the value in the **Basis** field to determine the amount to deduct or contribute for the benefit.
        
          - If the basis for the deduction is **Fixed amount**, enter the amount to use as the payroll deduction or employer contribution for the selected benefit.
        
          - If the basis for the deduction is **Percent of earnings**, **Regular portion of all pay**, or **Regular earnings**, enter the percentage of the worker’s included earnings or pay to use as the payroll deduction or employer contribution for the selected benefit.
        
          - If the basis for the deduction is **Productive hours**, **Earning hours**, **Regular hours**, or **Total hours**, enter the hourly rate for the payroll deduction or employer contribution.
        
        For more information, see [Benefits (form)](https://technet.microsoft.com/en-us/library/jj680907\(v=ax.60\)).
        
        This field isn’t available when the payroll category that is assigned to the benefit type in the **Benefit elements** form is **Retirement**.
    
      - **Calculation rate** – The variable rate structure that is used to calculate employer contributions to a retirement plan.
        
        This field is available only when the payroll category that is assigned to the benefit type in the **Benefit elements** form is **Retirement**.

7.  On the **Earning basis** FastTab, enter the earning codes that can be included when deductions and contributions for this benefit are calculated.
    
    If the **Payroll impact** field in the **Benefit elements** form is set to **None**, this FastTab isn’t available. For more information, see [Benefit elements (form)](https://technet.microsoft.com/en-us/library/hh209498\(v=ax.60\)).
    
    In addition to the earning codes entered here, the **Basis** setting on the **Payroll details** FastTab, in combination with the parameter settings in the **Earning codes** form, is also used to determine whether a specific earnings line is included in the calculation.
    
    To enter an earning code, click **Add**, and then select the earning code from the list. You can add all earning codes at the same time by clicking **Add all earning codes**.

Repeat these steps to create more benefits. When you have finished, close the form.

Back to top

## 4\. Set up workers’ compensation plans

In Microsoft Dynamics AX, workers’ compensation plans are handled just like other employee benefits.

1.  Follow the steps in “Set up benefit elements” in this topic to set up a benefit type for workers’ compensation plans. Use these values.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Value to enter</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Concurrent enrollment</strong></p></td>
    <td><p><strong>Multiple enrollments per type</strong></p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Payroll category</strong></p></td>
    <td><p><strong>Workers' compensation</strong></p></td>
    </tr>
    </tbody>
    </table>


2.  Follow the steps in “Set up benefit elements” in this topic to set up a workers’ compensation benefit plan for each workers’ compensation plan that your organization subscribes to. Use these values for each plan.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Value to enter</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Type</strong></p></td>
    <td><p>The benefit type that you created to use with workers’ compensation plans.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Payroll impact</strong></p></td>
    <td><p><strong>Contribution only</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Pretax basis</strong></p></td>
    <td><p><strong>None</strong></p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Limit period</strong></p></td>
    <td><p>Leave blank</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Limit amount</strong></p></td>
    <td><p>Leave blank</p></td>
    </tr>
    </tbody>
    </table>


3.  Follow the steps in “Create a new benefit” in this topic to create one workers’ compensation benefit for each workers’ compensation plan that your organization subscribes to. On the **Workers' compensation** FastTab, specify the state that each benefit applies to.

Back to top

## Next step

The next step is to set up payroll information for positions and workers. For more information, see [Worker and position payroll tasks](worker-and-position-payroll-tasks.md).

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
<td><p>To set up benefits, you must be a member of a security role that includes these duties:</p>
<ul>
<li><p><strong>Set up payroll master data</strong> (PayrollMasterDataMaintain)</p></li>
<li><p><strong>Inquire into payroll master data</strong> (PayrollMasterDataInquire)</p></li>
<li><p><strong>Set up payroll positions and workers</strong>(PayrollPositionWorkerSetupMaintain)</p></li>
<li><p><strong>Enable benefits process</strong> (HcmBenefitProcessEnable)</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To set up benefits, you must be a member of a security role that includes these privileges:</p>
<ul>
<li><p><strong>Maintain benefit setup</strong> (HcmBenefitElementSetupMaintain)</p></li>
<li><p><strong>Maintain benefits</strong> (HcmBenefitInquiryMaintain)</p></li>
<li><p><strong>Maintain worker enrollment</strong> (HcmWorkerEnrollmentMaintain)</p></li>
<li><p><strong>Maintain the date effective information for the selected rate structures</strong> (PayrollBenefitCalcRateDateMaintain)</p></li>
<li><p><strong>Maintain contribution calculation rates</strong> (PayrollBenefitCalcRateSetupMaintain)</p></li>
<li><p><strong>Maintain versions</strong> (PayrollBenefitReportingDateMgrMaintain)</p></li>
<li><p><strong>Maintain payroll calculation frequencies</strong> (PayrollCalculationFrequencyMaintain)</p></li>
<li><p><strong>Maintain disposable income definitions</strong> (PayrollDisposableIncomeMaintain)</p></li>
<li><p><strong>Maintain earning codes</strong> (PayrollEarningCodeMaintain)</p></li>
<li><p><strong>Maintain payroll earning code groups</strong> (PayrollEarningCodeGroupMaintain)</p></li>
<li><p><strong>Maintain worker garnishment and tax levy rules</strong> (PayrollGarnishmentRuleMaintain)</p></li>
<li><p><strong>Maintain payroll parameters</strong> (PayrollParametersMaintain)</p></li>
<li><p><strong>Maintain workers</strong> (HcmWorkerMaintain)</p></li>
</ul></td>
</tr>
</tbody>
</table>


Back to top

## Find form help

[Maintain versions (form)](https://technet.microsoft.com/en-us/library/jj729769\(v=ax.60\))

[Benefit elements (form)](https://technet.microsoft.com/en-us/library/hh209498\(v=ax.60\))

[Benefits (form)](https://technet.microsoft.com/en-us/library/jj680907\(v=ax.60\))

[Maintain benefits (form)](https://technet.microsoft.com/en-us/library/hh209235\(v=ax.60\))

## Find related tasks

[Worker and position payroll tasks](worker-and-position-payroll-tasks.md)

[Payroll calculation frequencies tasks](payroll-calculation-frequencies-tasks.md)

[Garnishment and tax levy setup tasks](garnishment-and-tax-levy-setup-tasks.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

