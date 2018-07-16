---
title: Benefit accrual plan tasks
TOCTitle: Benefit accrual plan tasks
ms:assetid: 020cfd57-205e-44a8-81b1-e07de7fb2474
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677319(v=AX.60)
ms:contentKeyID: 49384090
ms.date: 11/11/2015
mtps_version: v=AX.60
f1_keywords:
- payroll
- accrued time off
- accrued leave
- earned vacation
- paid time off
- benefit accrual plan
- earned leave
- earned time off
- PTO
- benefit accrual
- vacation
- sick
- vacation plan
- sick time
- sick leave
- PTO plan
- time off
- Menu_Items.Display.PayrollAccrual
- Menu_Items.Display.PayrollWorkerEnrolledAccrual
- benefit accrual plan tasks
- accrual plan
- accrual plans
- benefit accrual plans
- PTO plans
---

# Benefit accrual plan tasks 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic describes the tasks required to set up benefit accrual plans.

You can use benefit accrual plans, such as vacation and sick time off, to track accrual balances as they increase and decrease throughout the plan year.


> [!NOTE]
> <P>The procedure for completing this task has changed for Microsoft Dynamics AX 2012 R3 Cumulative Update 8. For information that is specific to AX 2012 R3 CU8, see the section later in this topic.</P>



The following illustration shows the steps that are required to set up benefit accrual plans. The numbers correspond to the procedures later in this topic.

![Steps for setting up benefit accrual plans](images/JJ677319.Payroll_Benefit_accrual_plans(AX.60).gif "Steps for setting up benefit accrual plans")

For additional information about benefit accrual plans, see [Payroll data updates](payroll-data-updates.md).

## What do you want to do?

Understand the bigger process

Review the prerequisites

1\. Gather the required information

2\. Set up benefit accrual plans

3\. Enroll workers in benefit accrual plans

Benefit accrual plan tasks in AX 2012 R3 CU8

Next step

Technical information for system administrators

Find form help

## Understand the bigger process

The following illustration shows the relationship between this topic and the overall process of setting up Payroll for the first time. For information about additional tasks required for this step in the process, and an overview of the whole process, see [Setting up payroll: Basic topics](setting-up-payroll-basic-topics.md).

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

## 1\. Gather the required information

A benefit accrual plan includes a set of rules that determine how hours in the plan are accrued and how they are used. The plan also includes a list of earning codes that are matched against the earning codes on earnings statement lines so that the plan balance can be reduced when that specific earning code is used.

The rules for the plan are based on the number of months that a worker has been employed with the organization. The months of employment are based on the employment start date or on the seniority date. You define the rules to control the rate at which benefits accrue and to control the maximum accrual limit, minimum balance, and carry-forward limit.

**Example**

Your paid time off (PTO) plan has three different rates, based on years of employment.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Years of employment</p></th>
<th><p>PTO days per year</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Fewer than 5</p></td>
<td><p>10</p></td>
</tr>
<tr class="even">
<td><p>At least 5 but fewer than 10</p></td>
<td><p>15</p></td>
</tr>
<tr class="odd">
<td><p>At least 10</p></td>
<td><p>20</p></td>
</tr>
</tbody>
</table>


The benefit accrual is based on the years of employment. To allow for workers to accrue the correct total, you must convert the years of employment to months of employment, and the number of PTO days per year to the number of PTO hours to accrue per hour worked.

  - To convert the years of employment to months of employment, you multiply the number of years by 12.
    
    These are the calculations for the example plan:
    
    0 x 12 = 0
    
    5 x 12 = 60
    
    10 x 12 = 120

  - To convert the PTO days per year to the hourly accrual rate, you multiply the number of days accrued per year by the number of hours in a work day to get the number of hours that are accrued per year. Then you divide that number by the number of hours worked in a year to get the hourly accrual rate. For most workers, you use this formula:
    
    Number of days accrued per year x 8 hours worked in a day / 2080 hours worked in a year = Hourly accrual rate
    
    These are the calculations for the example plan:
    
    10 x 8 / 2080 = 0.03846
    
    15 x 8 / 2080 = 0.05769
    
    20 x 8 / 2080 = 0.07692

You enter these numbers into a table, as shown here, to make it easier to set up the plan rules.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Months of employment</p></th>
<th><p>Hourly accrual rate</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>0</p></td>
<td><p>0.03846</p></td>
</tr>
<tr class="even">
<td><p>60</p></td>
<td><p>0.05769</p></td>
</tr>
<tr class="odd">
<td><p>120</p></td>
<td><p>0.07692</p></td>
</tr>
</tbody>
</table>



> [!TIP]
> <P>You can use the hourly accrual rate to verify the amount that should accrue in each pay statement. For example, if workers who accrue 15 days per year are paid biweekly, and they work 40 hours per week, multiply the hourly accrual rate of 0.05769 by 80 hours. The result is 4.6152. Therefore, the workers should accrue 4.6152 hours on each pay statement.</P>



Back to top

## 2\. Set up benefit accrual plans

1.  Click **Payroll** \> **Setup** \> **Benefits** \> **Benefit accrual plans**.

2.  Click **New**, and then enter a name and description for the plan.

3.  In the **Annual plan start date** field, enter the start date for the plan. The plan is reset each year on the anniversary of this date.
    
    If you leave this field blank, the plan isn’t reset. Any fields that show data for the plan year, such as the **Plan year accrued** and **Plan year used** fields in the **Benefit accrual balances** form, will include all transactions from the start of the plan, instead of all transactions in the plan year.

4.  To determine the number of hours of a benefit that are accrued in a pay period, the total number of hours on the earnings statement is multiplied by the hourly accrual rate. If the hours that are used from this plan should count as part of the total number of hours that are used to determine how many hours are accrued for this plan, select the **Accrue on usage** check box. To exclude the hours that are used from this plan from the total hours on the earnings statement before the number of accrued hours for this plan is calculated, clear this check box.

5.  To allow for balances at the end of the plan year to be carried over to the next plan year, select the **Carry forward balances** check box. You can limit the number of hours that can be carried forward when you create the plan rules.

6.  On the **Plan rules** FastTab, click **Add**.
    
    Each line that you add to a benefit accrual plan provides the rules for accruing time and for using plan benefits for workers who have the specified number of months of employment.

7.  In the **Months of employment** column in the grid, enter the minimum number of months of employment for the first rule in the plan. The number of months of employment is based either on the employment start date or on the seniority date, as specified in the **Benefit accruals** form for the worker.
    

    > [!NOTE]
    > <P>The employment start date is in the <STRONG>Employment history</STRONG> form, and the seniority date is in the <STRONG>Worker</STRONG> form.</P>
    > <P>We recommend that you make sure that the <STRONG>Seniority date</STRONG> field has a value. If you use the seniority date to determine the months of employment, and the <STRONG>Seniority date</STRONG> field in the <STRONG>Worker</STRONG> form is blank, the worker can use hours from the benefit accrual plan, but no hours can accrue in the plan.</P>

    
    We also recommend that every plan include a row starting at 0 (zero) months of employment. Each row ends when the next row starts. The last row starts at the specified number of months and does not end.
    
    For example, the rows in your plan have 0, 60, and 120 for months of employment. The rate and limits in the first row start when a worker is hired and are applied through the end of their eleventh month. The second row starts at 12 months and the rates and limits are applied through the end of the fifty-ninth month. The third row starts at 60 months and the rates and limits are applied as long as the worker continues to be employed by your organization.

8.  In the **Hourly accrual rate** field, enter the number of hours to add to the accrual plan balance for each hour that is on the earnings statement. For example, enter 0.03846 for a worker who receives 10 days off each year.

9.  In the **Maximum accrual limit** field, enter the maximum number of hours that can be accrued in the plan in a single plan year. When this number is reached, no more hours are accrued in the plan until the start of the next plan year, unless a manual adjustment reduces the accrued amount for the plan year.
    

    > [!NOTE]
    > <P>If the plan is not reset each year, this value is the maximum number of hours that can be accrued over the life of the plan.</P>



10. In the **Minimum balance** field, enter the number of hours that must be available in the plan before a worker can use hours from the plan. When the available balance is less than this number, the worker can’t use any hours from the plan until additional hours have accrued, or until the available balance has been adjusted.
    

    > [!TIP]
    > <P>To let workers take time off before they have accrued the hours, enter a negative number.</P>

    
    If an earnings statement includes hours that would reduce the available balance in the plan to be less than the minimum balance, the earnings statement lines that include those hours aren’t released.

11. In the **Carry-forward limit** field, enter the highest number of hours that can be carried forward from one plan year to the next.
    
    If the **Carry forward balances** check box is cleared, no hours are carried forward.

12. Repeat steps 6 through 11 for each remaining rule in the plan. When you have finished, go to step 13.

13. On the **Earning codes for plan usage** FastTab, click **Add**, and then select the earning code to use to record the hours used from this plan. You can repeat this step to add more earning codes.
    
    We recommend that you use a separate earning code for each benefit accrual plan. The earning code is used to verify the available balance when the earning statement is released. It is also used to reduce the plan balance when a pay statement line that includes the earning code is submitted for payment.
    
    If you use the earning code for a benefit accrual on an earnings statement for a worker who is not enrolled in the plan, no validation occurs.

Repeat these steps to set up additional benefit accrual plans. When you have finished, close the form.

Back to top

## 3\. Enroll workers in benefit accrual plans

The process for enrolling workers in benefit accrual plans differs from the process of enrolling them in other benefits. Mass enrollment isn’t available for benefit accrual plans, and eligibility processing is not performed.

1.  Click **Payroll** \> **Common** \> **Workers** \> **Workers**. Select a worker, click **Personal information**, and then click **Benefit accruals**.

2.  Click **New**.

3.  In the **Benefit accrual plan** column in the grid, select a benefit accrual plan.
    
    You can add and delete enrollments only for benefit accrual plans for the legal entity that you are logged on to.

4.  Make sure that the value in the **Accrual date basis** field is correct.
    
    If the accrual date basis is set to **Seniority date**, make sure that a seniority date is assigned to the worker:
    
    1.  On the **Workers** list page, double-click the name of the worker.
    
    2.  In the **Worker** form, on the **Worker summary** FastTab, review the **Seniority date** field.
    
    3.  If the **Seniority date** field is blank, click **Edit**, and then enter a seniority date.
    
    4.  Close the form.

Repeat these steps to enroll the worker in additional benefit accrual plans. When you have finished, close the form.

Back to top

## Benefit accrual plan tasks in AX 2012 R3 CU8

## 1\. Gather the required information

A benefit accrual plan includes a set of rules that determine how hours in the plan are accrued and how they are used. The plan also includes a list of earning codes that are matched against the earning codes on earnings statement lines so that the plan balance can be reduced when that specific earning code is used.

The rules for the plan are based on the number of months that a worker has been with the organization. The months of service are based on the employment start date, the seniority date, or a date that is specific to the individual worker. You define the rules to control the rate at which benefits accrue and to control the maximum accrual limit, minimum balance, and carry-forward limit.

**Example**

Your paid time off (PTO) plan has three different rates, based on years of service.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Years of service</p></th>
<th><p>PTO days per year</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Fewer than 5</p></td>
<td><p>10</p></td>
</tr>
<tr class="even">
<td><p>At least 5 but fewer than 10</p></td>
<td><p>15</p></td>
</tr>
<tr class="odd">
<td><p>At least 10</p></td>
<td><p>20</p></td>
</tr>
</tbody>
</table>


The benefit accrual is based on the years of service. To allow for your workers to accrue the correct total, you must convert the years of service to months of service, and the number of PTO days per year to the number of PTO hours to accrue per hour worked.

  - To convert the years of service to months of service, you multiply the number of years by 12.
    
    These are the calculations for the example plan:
    
    0 x 12 = 0
    
    5 x 12 = 60
    
    10 x 12 = 120

  - To convert the PTO days per year to the hourly accrual rate, you multiply the number of days accrued per year by the number of hours in a work day to get the number of hours that are accrued per year. Then you divide that number by the number of hours worked in a year to get the hourly accrual rate. For most workers, you use this formula:
    
    Number of days accrued per year x 8 hours worked in a day / 2080 hours worked in a year = Hourly accrual rate
    
    These are the calculations for the example plan:
    
    10 x 8 / 2080 = 0.03846
    
    15 x 8 / 2080 = 0.05769
    
    20 x 8 / 2080 = 0.07692

You enter these numbers into a table, as shown here, to make it easier to set up the plan rules.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Months of service</p></th>
<th><p>Hourly accrual rate</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>0</p></td>
<td><p>0.03846</p></td>
</tr>
<tr class="even">
<td><p>60</p></td>
<td><p>0.05769</p></td>
</tr>
<tr class="odd">
<td><p>120</p></td>
<td><p>0.07692</p></td>
</tr>
</tbody>
</table>



> [!TIP]
> <P>You can use the hourly accrual rate to verify the amount that should accrue in each pay statement. For example, if workers who accrue 15 days per year are paid biweekly, and they work 40 hours per week, multiply the hourly accrual rate of 0.05769 by 80 hours. The result is 4.6152. Therefore, the workers should accrue 4.6152 hours on each pay statement.</P>



## 2\. Set up benefit accrual plans

1.  Click **Payroll** \> **Setup** \> **Benefits** \> **Benefit accrual plans**.

2.  Click **New**, and then enter the following information.
    
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
    <td><p><strong>Benefit accrual plan</strong></p>
    <p><strong>Description</strong></p></td>
    <td><p>A name and description for the plan.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Annual plan start date</strong></p></td>
    <td><p>The start date for the plan. The plan is reset each year on the anniversary of this date.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Carry forward balances</strong></p></td>
    <td><p>If you select this check box, balances at the end of the plan year can be carried over to the next plan year. You can limit the number of hours to be carried forward when you create the plan rules.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Accrual rate basis</strong></p></td>
    <td><p>The method that this plan uses to accrue benefits for workers who are enrolled in the plan. The method is used together with the value in the <strong>Amount or rate</strong> field to determine the number of hours to add to the worker’s plan.</p>
    <p>Select from the following options:</p>
    <ul>
    <li><p><strong>Hourly rate</strong> – Hours are added to the plan balance based on the number of eligible hours on the pay statement times the rate in the <strong>Amount or rate</strong> field.</p></li>
    <li><p><strong>Fixed amount by payroll frequency</strong> –The number of hours in the <strong>Amount or rate</strong> field is added to the plan balance on the last day of each pay period that is included in the selected payroll calculation frequency.</p></li>
    <li><p><strong>Fixed amount by date</strong> –The number of hours in the <strong>Amount or rate</strong> field is added to the plan balance on the last day of the pay period that includes the date that is determined based on the <strong>Accrual date</strong> field.</p></li>
    <li><p><strong>Hours of compensatory time</strong> – Hours are added to the plan balance based on the number of eligible hours on the pay statement times the rate in the <strong>Rate for compensatory time</strong> field on the <strong>Earning codes for plan accrual</strong> FastTab.</p></li>
    </ul></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Frequency</strong></p></td>
    <td><p>The payroll calculation frequency that includes the pay periods when the number of hours in the <strong>Amount or rate</strong> field is added to the plan balance.</p>
    <p>This field is available only when the accrual rate basis is <strong>Fixed amount by payroll frequency</strong>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Accrual date</strong></p></td>
    <td><p>The day each year when the number of hours in the <strong>Amount or rate</strong> field is added to the plan balance.</p>
    <p>Select from the following options:</p>
    <ul>
    <li><p><strong>Employment start date</strong> – This date is in the <strong>Employment history</strong> form.</p></li>
    <li><p><strong>Seniority date</strong> – This date is in the <strong>Worker</strong> form.</p>
    <p>We recommend that you make sure the seniority date field always has a value. If you use the seniority date to determine the months of service, and the <strong>Seniority date</strong> field in the <strong>Worker</strong> form is blank, the worker can use hours from the benefit accrual plan, but no hours can accrue in the plan.</p></li>
    <li><p><strong>Annual plan start date</strong></p></li>
    <li><p><strong>Custom date</strong> – A date that is specified for this plan.</p></li>
    </ul>
    <p>This field is available only when the accrual rate basis is <strong>Fixed amount by date</strong>.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Custom accrual date</strong></p></td>
    <td><p>The month and date each year when the number of hours in the <strong>Amount or rate</strong> field is added to the plan balance.</p>
    <p>This field is available only when the accrual rate basis is <strong>Fixed amount by date</strong> and the accrual date is <strong>Custom date</strong>.</p></td>
    </tr>
    </tbody>
    </table>


3.  On the **Plan rules** FastTab, click **Add**.
    
    Each line that you add to a benefit accrual plan provides the rules for accruing time and for using plan benefits for workers who have the specified number of months of service.

4.  For each line in the plan, enter the following information.
    
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
    <td><p><strong>Months of service</strong></p></td>
    <td><p>The minimum number of months of service for the selected rule. The number of months of service is based on the employment start date, the seniority date, or a date that is specified for the worker in the <strong>Benefit accruals</strong> form.</p>
    <div class="alert"> 

    > [!NOTE]
    > <P>The employment start date is in the <STRONG>Employment history</STRONG> form, and the seniority date is in the <STRONG>Worker</STRONG> form.</P>
    > <P>We recommend that you make sure that the <STRONG>Seniority date</STRONG> field has a value. If you use the seniority date to determine the months of service, and the <STRONG>Seniority date</STRONG> field in the <STRONG>Worker</STRONG> form is blank, the worker can use hours from the benefit accrual plan, but no hours can accrue in the plan.</P>


    </div>
    <p>We recommend that every plan include a row starting at 0 (zero) months of service. Each row ends when the next row starts. The last row starts at the specified number of months and does not end.</p>
    <p>For example, the rows in your plan have 0, 60, and 120 for months of service. The rate and limits in the first row start when a worker is hired and are applied through the end of their eleventh month. The second row starts at 12 months and the rates and limits are applied through the end of the fifty-ninth month. The third row starts at 60 months and the rates and limits are applied as long as the worker continues to be employed by your organization.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Amount or rate</strong></p></td>
    <td><p>The amount of the accrual if the accrual rate basis is a fixed amount, or the rate that is used to calculate the amount if the accrual rate basis is an hourly rate. For example, if you have a plan where a worker accrues 80 hours each year, and the benefit accrues at an hourly rate, you would enter 0.03846; if the benefit accrues as a fixed amount by date, you would enter 80.</p>
    <p>The rate for compensatory time plans is entered on the <strong>Earning codes for plan accrual</strong> FastTab.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Maximum accrual limit</strong></p></td>
    <td><p>The maximum number of hours that can be accrued in the plan in a single plan year. When this number is reached, no more hours are accrued in the plan until the start of the next plan year, unless a manual adjustment reduces the accrued amount for the plan year.</p>
    <p>If the plan is not reset each year, this value is the maximum number of hours that can be accrued over the life of the plan.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Minimum balance</strong></p></td>
    <td><p>The number of hours that must be available in the plan before a worker can use hours from the plan. When the available balance is less than this number, the worker can’t use any hours from the plan until additional hours have accrued, or until the available balance has been adjusted.</p>
    <div class="alert"> 

    > [!TIP]
    > <P>To let workers take time off before they have accrued the hours, enter a negative number.</P>


    </div>
    <p>If an earnings statement includes hours that would reduce the available balance in the plan to be less than the minimum balance, the earnings statement lines that include those hours aren’t released.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Carry-forward limit</strong></p></td>
    <td><p>The highest number of hours that can be carried forward from one plan year to the next.</p>
    <p>If the <strong>Carry forward balances</strong> check box is cleared, this field is not available, and no hours are carried forward.</p></td>
    </tr>
    </tbody>
    </table>


5.  Click the **Earning codes for plan usage** FastTab. The earning codes that are entered here are used to verify the available balance when an earnings statement that includes the earning code is released. The codes are also used to reduce the plan balance when a pay statement line that includes the earning code is submitted for payment.

6.  Click **Add**, and then select the earning code to use to record the hours used from this plan. You can repeat this step to add more earning codes.
    
    We recommend that you use a separate earning code for plan usage for each benefit accrual plan.
    
    If you use the earning code for a benefit accrual on an earnings statement for a worker who is not enrolled in the plan, no validation occurs.

7.  Click the **Earning codes for plan accrual** FastTab. The earning codes that are entered here are used to increase the plan balance when a pay statement line that includes the earning code is submitted for payment.
    
    For example, suppose you enter an earning code for Regular hours here. If that earning code is used on an earnings statement line that contains eight hours, when that earnings statement is submitted for payment, the worker’s balance in the plan is increased by eight hours times the specified rate.
    

    > [!NOTE]
    > <P>This FastTab is available only when the accrual rate basis for the plan is <STRONG>Hourly rate</STRONG> or <STRONG>Hours of compensatory time</STRONG>.</P>



8.  Click **Add**, and then enter the following information.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Fields</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Earning type</strong></p></td>
    <td><p>Select whether to enter an earning code or an earning code group.</p>
    <p>When you include both earning codes and earning code groups in a benefit accrual plan, an earning code can be included in the table multiple times. This occurs when an earning code appears in the table by itself and as part of an earning code group. Each earning code is processed only one time, regardless of how many times the code occurs in the table.</p>
    <div class="alert"> 

    > [!NOTE]
    > <P>This control is available only when the accrual rate basis for the plan is <STRONG>Hourly rate</STRONG>.</P>


    </div></td>
    </tr>
    <tr class="even">
    <td><p><strong>Earning code group</strong></p></td>
    <td><p>The earning code groups that contain hourly earning codes.</p>
    <p>The hourly earning codes increase the plan balance when a pay statement line that includes the earning code is submitted for payment. Earning codes other than hourly earning codes are disregarded when the plan balance is calculated.</p>
    <div class="alert"> 

    > [!NOTE]
    > <P>This control is available only when the accrual rate basis for the plan is <STRONG>Hourly rate</STRONG>.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Earning code</strong></p></td>
    <td><p>The earning codes that increase the plan balance when a pay statement line that includes the earning code is submitted for payment.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Description</strong></p></td>
    <td><p>The description of the selected earning code or earning code group.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Rate for compensatory time</strong></p></td>
    <td><p>The rate that is used to calculate the amount of compensatory time. For example, if the worker accrues one hour of compensatory time for each hour worked by using the selected earning code, enter 1. If the worker accrues 1.5 hours of compensatory time, enter 1.5.</p>
    <div class="alert"> 

    > [!NOTE]
    > <P>This control is available only when the accrual rate basis for the plan is <STRONG>Hours of compensatory time</STRONG>.</P>


    </div></td>
    </tr>
    </tbody>
    </table>
    
    You can repeat this step to add more earning codes.

Repeat these steps to set up additional benefit accrual plans. When you have finished, close the form.

## 3\. Enroll workers in benefit accrual plans

The process for enrolling workers in benefit accrual plans differs from the process of enrolling them in other benefits. Mass enrollment isn’t available for benefit accrual plans, and eligibility processing is not performed.

1.  Click **Payroll** \> **Common** \> **Workers** \> **Workers**. Select a worker, click **Personal information**, and then click **Benefit accruals**.

2.  Click **New**.

3.  In the **Benefit accrual plan** column in the grid, select a benefit accrual plan.
    

    > [!NOTE]
    > <P>You can add and delete enrollments only for benefit accrual plans for the legal entity that you are logged on to.</P>



4.  Make sure that the value in the **Service date basis** field is correct. The default value for this field is assigned in the **Payroll parameters** form.
    
    If the service date basis is set to **Seniority date**, make sure that a seniority date is assigned to the worker.
    
    1.  On the **Workers** list page, double-click the name of the worker.
    
    2.  In the **Worker** form, on the **Worker summary** FastTab, review the **Seniority date** field.
    
    3.  If the **Seniority date** field is blank, click **Edit**, and then enter a seniority date.
    
    4.  Close the form.

Repeat these steps to enroll the worker in additional benefit accrual plans. When you have finished, close the form.

Back to top

## Next step

The next step is to set up payroll taxes. For more information, see [Tax information tasks](tax-information-tasks.md).

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
<td><p>To set up benefit accrual plans, you must be a member of a security role that includes these duties:</p>
<ul>
<li><p><strong>Set up payroll master data</strong> (PayrollMasterDataMaintain)</p></li>
<li><p><strong>Inquire into payroll master data</strong> (PayrollMasterDataInquire)</p></li>
<li><p><strong>Set up payroll positions and workers</strong>(PayrollPositionWorkerSetupMaintain)</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To set up benefit accrual plans, you must be a member of a security role that includes these privileges:</p>
<ul>
<li><p><strong>Inquire into benefit accrual plans</strong> (PayrollAccrualPlanSetupMaintain)</p></li>
<li><p><strong>Maintain benefit accrual plan adjustments</strong> (PayrollWorkerAccrualAdjustMaintain)</p></li>
<li><p><strong>Maintain worker benefit accrual plans</strong> (PayrollWorkerEnrolledAccrualMaintain)</p></li>
</ul></td>
</tr>
</tbody>
</table>


Back to top

## Find form help

[Benefit accrual balances (form)](https://technet.microsoft.com/en-us/library/jj677450\(v=ax.60\))

[Benefit accrual transactions (form)](https://technet.microsoft.com/en-us/library/jj677426\(v=ax.60\))

[Worker (form)](https://technet.microsoft.com/en-us/library/hh209054\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

