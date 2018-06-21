---
title: Earning code and earning code group tasks
TOCTitle: Earning code and earning code group tasks
ms:assetid: 694f48ca-9841-40e5-919f-cc12569da3a1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn876706(v=AX.60)
ms:contentKeyID: 63385348
ms.date: 11/14/2014
mtps_version: v=AX.60
f1_keywords:
- payroll
- earning codes
- Forms.PayrollEarningCode
- earning code
- MsDynAx060.Forms.PayrollEarningCode
- earning code group
- earning code groups
- Forms.PayrollEarningCodeGroup
---

# Earning code and earning code group tasks [AX 2012]


This topic describes the tasks that are required to set up earning codes and earning code groups.

Earning codes uniquely identify every type of earnings that workers receive. The codes various parameters that relate to earnings, such as accounting rules, tax laws, reporting requirements, and gross up capability.

Earning codes are also used to calculate various amounts that are used by the payroll system. For example, earning codes are required to determine these amounts:

  - Deductions and contributions for certain benefits

  - Balances in benefit accrual plans

  - Disposable income


> [!TIP]
> <P>During the initial payroll setup, you will be directed to add earning codes to the various payroll entities where they are required. Any time that you create or modify earning codes after the initial setup, consider everywhere that the earning code should be used, and update all affected payroll entities.</P>



After you create earning codes, you can assign the codes to workers or to earning code groups, and you can enter the codes manually on earnings statements.

Earning codes are assigned to workers in these situations:

  - When an earning is received on a recurring basis, such as every pay period.

  - When an earning has a unique flat amount for a worker position.

  - When an earning has a unique rate for a worker position.

You don’t have to assign an earning code to a worker to enter the earning code on the worker’s earnings statement. For example, earning codes for vacation or overtime hours are not usually assigned to workers.

Earning codes are assigned to earning code groups in these situations:

  - When it is convenient to group together similar earning codes for administrative reasons. For example, you might want to include all earning codes that are used for benefit accrual plans in one group so that you can easily identify the codes when you update the plans.

  - When a group of earning codes is used by a payroll process. For example, all earning codes that are used for nondiscretionary earnings must be included in a single group in order to calculate a regular-rate-of-pay premium.

The following illustration shows the steps that are required to set up earning codes and earning code groups. The numbers correspond to the procedures later in this topic.

![Earning codes and earning code groups process](images/Dn876706.Payroll_Earning_codes_and_earning_code_groups(AX.60).gif "Earning codes and earning code groups process")

For details about several different types of earning codes, see [Earning code examples](earning-code-examples.md).

## This task is part of a bigger process

The following illustration shows the relationship between this topic and the overall process of setting up Payroll for the first time.

For an overview of the process, see [Setting up payroll: Basic topics](setting-up-payroll-basic-topics.md).

![Basic steps for setting up Payroll the first time](images/JJ677367.Payroll_Set_up_payroll_basic(AX.60).gif "Basic steps for setting up Payroll the first time")

## Prerequisites

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
<td><p>Earning codes require Microsoft Dynamics AX 2012 R2.</p>
<p>Earning code groups and retroactive earnings require Microsoft Dynamics AX 2012 R3 or the Human resources/Payroll regulatory feature pack July 2014 for AX 2012 R2.</p>
<p>Controls for FMLA require cumulative update 8 for Microsoft Dynamics AX 2012 R3.</p></td>
</tr>
<tr class="even">
<td><p>Country/region</p></td>
<td><p>(USA) The primary address for the legal entity must be in the following countries/regions: United States</p></td>
</tr>
</tbody>
</table>


## 1\. Develop a list of the earning codes that you need

Because earning codes are used to uniquely identify every type of earnings that workers receive for their services, most organizations use many earning codes.

A typical set of earning codes includes codes for at least these types of earnings:

  - Base pay hourly earnings – If you have workers on multiple shifts, you will need a separate earning code for each shift.

  - Salaried earnings – You will need a separate earning code for each fixed compensation plan.

  - Premiums – If you pay premiums based on other earnings, such as shift differentials or overtime earnings, or if you pay premiums based on characteristics of the worker, such as bonuses based on credentials, you will need additional earning codes. For more information, see [Premium earning setup tasks](premium-earning-setup-tasks.md).

  - Leave – You will need separate earning codes for jury duty, bereavement leave, and any other types of leave your organization offers.

  - Benefit accruals – You will need a separate earning code for every benefit accrual plan. The earning code for a benefit accrual plan is used to verify the available balance in the plan and to reduce the balance when a pay statement line that includes the earning code is submitted for payment. For more information, see [Benefit accrual plan tasks](benefit-accrual-plan-tasks.md).

  - Retroactive earnings – For every type of earning that could be paid retroactively, we recommend that you create a retroactive earning code. It is helpful to name the two codes similarly. For example, if the regular earning code is Hourly union 1st shift, the retroactive earning code might be Hourly union 1st shift retro.

  - Miscellaneous or occasional earnings – Many organizations provide car allowances, reimbursement of relocation expenses, and other miscellaneous earnings. Each type requires a separate earning code.

Earning codes are shared across legal entities, except for the information on the **Accounting** tab. That information applies to the legal entity that you specify when you complete the information on the tab. This is described in detail in the following sections.

To see examples of some types of earning codes that your organization might need, see [Earning code examples](earning-code-examples.md).

## 2\. Create earning codes

Each earning type should have a unique earning code. To create an earning code, follow these steps:

1.  Click **Payroll** \> **Setup** \> **Earnings** \> **Earning codes**.

2.  Click **New**.

3.  Enter the following information for the form-level controls.
    
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
    <td><p><strong>Earning code</strong></p></td>
    <td><p>The name of the earning code. You might want to use a naming convention so that similar earning codes are grouped together.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Unit of measure</strong></p></td>
    <td><p>Select the unit of measure that is used to record the unit of work. You can select from these units of measure:</p>
    <ul>
    <li><p><strong>Hours</strong> –Earnings that are paid by the hour.</p></li>
    <li><p><strong>Pieces</strong> –Earning codes that are paid per each piece produced.</p></li>
    <li><p><strong>Each</strong> –All earning codes in which the earnings amount isn’t determined by the number of hours worked or pieces produced.</p></li>
    </ul></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Productive</strong></p></td>
    <td><p>Select this check box if the earning code is used for productive hours.</p>
    <p>Productive hours represent regular work hours, and nonproductive hours represent hours that were not actually worked, such as vacation and sick pay hours. Hours that are worked, but that are accounted for under another earning code, are also considered nonproductive. This information is used in several benefit and tax calculations. This includes the calculation of the regular rate of pay premium that is required under the Fair Labor Standards Act (FLSA) for overtime hours.</p>
    <p>For more information about premium earnings, see <a href="premium-earning-setup-tasks.md">Premium earning setup tasks</a>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Description</strong></p></td>
    <td><p>Enter a description of the earning code.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Include in payment run type</strong></p></td>
    <td><p>When you generate pay statements, you select a run type for each payment run. Earning codes that are included in that payment run type are processed in that payment run.</p>
    <p>Select a payment run type option for this earning code:</p>
    <ul>
    <li><p><strong>Primary</strong> – Include this earning code only in primary payment runs, such as weekly or biweekly. These runs are used for earnings such as regular pay, holiday pay, or vacation pay.</p>
    <div class="alert">

    > [!TIP]
    > <P>An earning code with the <STRONG>Primary</STRONG> type can be used in only one payroll run in each pay period. That can create difficulties if, for example, you make a mistake that you have to correct in the same payment run.</P>
    > <P>Earning codes with the <STRONG>Primary and additional</STRONG> type can be used more than once in a pay period. Therefore, you should consider selecting <STRONG>Primary and additional</STRONG> instead of <STRONG>Primary</STRONG> for the earning codes that will be used for your primary payment runs.</P>


    </div></li>
    <li><p><strong>Additional</strong> – Include this earning code only in additional payment runs, such as those used for bonuses or travel reimbursement.</p></li>
    <li><p><strong>Primary and additional</strong> – Include this earning code in both primary and additional payment runs.</p>
    <div class="alert">

    > [!TIP]
    > <P>When you select this payment run type, the earning code is processed in the first payment run in the pay period that is either primary or additional. You can’t reserve or hold the earning code for a specific run type.</P>


    </div></li>
    <li><p><strong>Gross up</strong> – Include this earning code in gross up payment runs, which are most often used for awards or reimbursements where the worker should receive a specific amount after taxes.</p>
    <p>If you select this option, you must select an earning code in the <strong>Gross up earning code</strong> field. Earning codes that are available in that field have a payment run type of <strong>Automatic</strong>.</p></li>
    <li><p><strong>Automatic</strong> –Use this earning code in gross up payment runs.</p>
    <p>Gross up payment runs use earning codes with two different payment run types, <strong>Gross up</strong> and <strong>Automatic</strong>. The earning code with the <strong>Gross up</strong> payment run type is used for the earning, often an award or a reimbursement, that is to be grossed up. The earning code with the <strong>Automatic</strong> payment run type is used for the earnings that cover the taxes so that the amount of the gross up earning comes out right.</p>
    <p>Earning lines that use earning codes with the <strong>Automatic</strong> payment run type are generated automatically when gross up earning codes are processed.</p></li>
    </ul>
    <div class="alert">

    > [!NOTE]
    > <P>When you select <STRONG>Gross up</STRONG> or <STRONG>Automatic</STRONG>, the <STRONG>Tax method</STRONG>, <STRONG>Base earnings component</STRONG>, <STRONG>Rate basis</STRONG>, and <STRONG>Unit of measure</STRONG> fields are set to predefined values and can’t be changed.</P>


    </div></td>
    </tr>
    <tr class="even">
    <td><p><strong>Base earnings component</strong></p></td>
    <td><p>If this check box is selected, the earnings that are calculated by using this earning code are included when worker base pay is determined. Base pay settings are used to generate earnings for salaried workers, and base pay figures are used to calculate and determine benefits that are based on pay.</p></td>
    </tr>
    </tbody>
    </table>


4.  Complete the relevant information on the **General** tab.
    
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
    <td><p><strong>Rate basis</strong></p></td>
    <td><p>This field is used together with the <strong>Amount or multiplier</strong> field to determine the earnings amount.</p>
    <ul>
    <li><p>If you select <strong>Flat amount</strong>, the <strong>Amount or multiplier</strong> value is treated as a currency amount. Flat amounts are used when the earning amount isn’t based on a worker’s fixed compensation.</p>
    <p><strong>Examples</strong></p>
    <ul>
    <li><p>To pay a worker a recurring 500.00 car allowance, you select <strong>Flat amount</strong> in the <strong>Rate basis</strong> field and enter 500.00 in the <strong>Amount or multiplier</strong> field.</p></li>
    <li><p>To pay a worker .25 for each piece produced, you select <strong>Flat amount</strong> in the <strong>Rate basis</strong> field and enter .25 in the <strong>Amount or multiplier</strong> field. The worker receives .25 for each piece that is produced.</p></li>
    </ul></li>
    <li><p>If you select <strong>Hourly</strong>, <strong>Pay period</strong>, <strong>Monthly</strong>, or <strong>Annually</strong>, the earning rate is calculated by using the workers’ compensation settings, based on the time frame of the rate basis. The calculated fixed compensation for the worker is multiplied by the <strong>Amount or multiplier</strong> value to determine the earning rate. The rate is multiplied by the quantity on the earnings statement line to determine the amount.</p>
    <p><strong>Examples</strong></p>
    <ul>
    <li><p>To set up an earnings code for double-time pay for hourly workers, you select <strong>Hourly</strong> in the <strong>Rate basis</strong> field and enter 2 in the <strong>Amount or multiplier</strong> field. If the calculated hourly equivalent for the worker in the <strong>Employee fixed compensation</strong> form is 35.00, the worker receives 70.00 for each hour logged for this earning code.</p></li>
    <li><p>To set up a 1 percent uniform allowance that is paid out each pay period, you select <strong>Pay period</strong> in the <strong>Rate basis</strong> field and enter .01 in the <strong>Amount or multiplier</strong> field. The worker receives 1 percent of their pay each pay period.</p></li>
    </ul></li>
    <li><p>If you select <strong>Retroactive</strong>, the earning code is set up for retroactive pay.</p>
    <p>This option is available only if the <strong>Retroactive earning</strong> box is selected.</p></li>
    <li><p>If you select <strong>Percent of earnings</strong>, <strong>Hours of earnings</strong>, or <strong>Regular rate of pay</strong>, you must also select an earning code group in the <strong>Basis earning code group</strong> field.</p>
    <p>These rate bases are most often used to generate premium earnings. For more information, see <a href="premium-earning-setup-tasks.md">Premium earning setup tasks</a>.</p></li>
    </ul></td>
    </tr>
    <tr class="even">
    <td><p><strong>Amount or multiplier</strong></p></td>
    <td><p>The multiplier that is used to calculate earnings, unless the rate basis is a flat amount.</p>
    <ul>
    <li><p>If the rate basis is a flat amount, the value in this field is treated as a currency amount. For example, if you enter 500 in this field, the value is considered a flat amount of 500.00.</p></li>
    <li><p>When the rate basis is <strong>Hourly</strong>, <strong>Pay period</strong>, <strong>Monthly</strong>, or <strong>Annually</strong>, this field is used together with the <strong>Rate basis</strong> field to determine the earnings amount. The rate basis method determines the appropriate compensation rate for workers. Workers who have different hourly rates can use the same hourly earning code because the correct hourly rate is calculated for each worker and position. For example, if the compensation rate is 24,000 per year and the worker’s pay cycle is monthly, select <strong>Pay period</strong> as the rate basis and enter a multiplier of 1. The generated earnings will be 2,000.</p></li>
    <li><p>For information about the value to use when the rate basis is <strong>Hours of earnings</strong>, <strong>Percent of earnings</strong>, or <strong>Regular rate of pay</strong>, see <a href="premium-earning-setup-tasks.md">Premium earning setup tasks</a>.</p></li>
    </ul>
    <div class="alert">

    > [!NOTE]
    > <P>This field is ignored when retroactive earning codes are calculated.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Basis earning code group</strong></p></td>
    <td><p>The group of earning codes that are used to calculate the amount of an earnings statement line that uses the selected earning code.</p>
    <p>This field is available only when the rate basis is <strong>Hours of earnings</strong>, <strong>Percent of earnings</strong>, or <strong>Regular rate of pay</strong>. These rate bases are most often used for premium earnings.</p>
    <p>The earning code group is used differently, depending on the rate basis that is selected:</p>
    <ul>
    <li><p>If the rate basis is <strong>Hours of earnings</strong>, the line uses the earning codes in the earning code group to identify eligible hours. The earning code adds an additional amount for each eligible hour.</p></li>
    <li><p>If the rate basis is <strong>Percent of earnings</strong>, the line uses the earning codes in the earning code group to identify eligible earnings. The earning code adds an additional percentage to the eligible amount.</p></li>
    <li><p>If the rate basis is <strong>Regular rate of pay</strong>, the line uses the earning codes in the earning code group to identify eligible earnings. The earning code adds an amount that is based on the sum of all eligible earnings during a work period. This is most often used to calculate the amount of the overtime premium that is required by the FLSA.</p></li>
    </ul>
    <p>For information about how to use earning code groups to generate premium earnings, see <a href="premium-earning-setup-tasks.md">Premium earning setup tasks</a>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Retroactive earning</strong></p></td>
    <td><p>If this check box is selected, this earning code is set up as a retroactive earning code. This field isn’t available if <strong>Gross up</strong> or <strong>Automatic</strong> is selected in the <strong>Include in payment run type</strong> field.</p>
    <p>When a retroactive earning code is created, the <strong>Rate basis</strong>, <strong>Productive</strong>, <strong>Unit of measure</strong>, and <strong>Amount or multiplier</strong> fields are set to predefined values and can’t be changed.</p>
    <div class="alert">

    > [!NOTE]
    > <P>If you select this check box and then clear it, the <STRONG>Rate basis</STRONG> field is set to <STRONG>Flat amount</STRONG>.</P>


    </div>
    <p>To view an example of how you might set up a retroactive earning code, see <a href="earning-code-examples.md">Earning code examples</a>.</p>
    <p></p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Tax method</strong></p></td>
    <td><p>The tax rate that is used to determine the amount of tax that is withheld for this earning code:</p>
    <ul>
    <li><p><strong>Regular</strong> – Taxes are calculated by using the standard rate.</p></li>
    <li><p><strong>Supplemental</strong> – Taxes are calculated at a supplemental rate.</p></li>
    <li><p><strong>Exempt</strong> – No tax is charged on earnings that are calculated by using this earning code.</p></li>
    </ul></td>
    </tr>
    <tr class="even">
    <td><p><strong>Fringe benefit type</strong></p></td>
    <td><p>The benefits that the worker is taxed on, even if the worker does not receive any direct compensation for them, such as life insurance and health benefits.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Retroactive earning code</strong></p></td>
    <td><p>This field is used to associate a non-retroactive earning code with an earning code that will retroactively adjust the processed earning lines that use this code.</p>
    <p>To view an example of how you might set up a retroactive earning code, see <a href="earning-code-examples.md">Earning code examples</a>.</p>
    <div class="alert">

    > [!NOTE]
    > <P>This field is optional. It is available only if the <STRONG>Retroactive earning</STRONG> box is cleared.</P>


    </div></td>
    </tr>
    <tr class="even">
    <td><p><strong>Gross up earning code</strong></p></td>
    <td><p>Select an earning code to use in a gross up payment run for the earnings that cover the taxes so that the amount of the gross up earning comes out right.</p>
    <p>This field is available only if <strong>Gross up</strong> is selected in the <strong>Include in payment run type</strong> field. The earning codes that can be selected in this field have <strong>Automatic</strong> in the <strong>Include in payment run type</strong> field.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Allow editing of earning statement rates</strong></p></td>
    <td><p>Select this check box to let users change the rate on earning statement lines that are generated by using this earning code.</p>
    <p>If you plan to enter beginning balances during the initial payroll setup, select this check box for all earning codes when you create them. After you enter the beginning balances, you can clear this check box if you want to prevent rates from being changed during typical payroll processing.</p>
    <div class="alert">

    > [!NOTE]
    > <P>If a salary line is generated by using an automated process, the rate on that line can’t be changed, even if this check box is selected. If you add a salary line manually, you can change the rate on the line if this check box is selected.</P>


    </div>
    <p>This control is available only if you installed AX 2012 R3 or the Human resources/Payroll regulatory feature pack July 2014 for AX 2012 R2.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Reduce remaining FMLA time</strong></p></td>
    <td><p>If this check box is selected, the earnings that are calculated by using this earning code will reduce the number of FMLA hours available for workers. For more information, see <a href="working-with-fmla.md">Working with FMLA</a>.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Base definition</strong></p></td>
    <td><p>This field specifies how the earning code is used to calculate workers’ compensation and general liability insurance. You can select from these options:</p>
    <ul>
    <li><p><strong>Not applicable</strong> – The earnings associated with this earning code are not used in the calculations.</p></li>
    <li><p><strong>Base time</strong> – The calculations use 100 percent of the earnings.</p></li>
    <li><p><strong>Time and a half</strong> – The calculations use 150 percent of the earnings.</p></li>
    <li><p><strong>Double time</strong> – The calculations use 200 percent of the earnings.</p></li>
    </ul></td>
    </tr>
    </tbody>
    </table>


5.  Complete the relevant information on the **Accounting** tab. This tab stores financial dimensions and posting rules that are applied when the selected earning code is assigned to a worker.
    
    Earning codes are shared across legal entities, but the settings on the **Accounting** tab are specific to the selected legal entity.
    
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
    <td><p><strong>Legal entity</strong></p></td>
    <td><p>The legal entity for the dimension template, default dimensions, accounting rules, and project category that are used together with the earning code.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Project category</strong></p></td>
    <td><p>The project category that the earnings are charged to, if applicable.</p>
    <div class="alert">

    > [!NOTE]
    > <P>If the <STRONG>Unit of measure</STRONG> field is set to <STRONG>Hours</STRONG> for this earning code, this list is limited to project categories that bill hourly. Conversely, if the <STRONG>Unit of measure</STRONG> field is not set to <STRONG>Hours</STRONG>, the project category list contains only projects that are billed as expenses.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Distribution template</strong></p></td>
    <td><p>The template that is used to determine the default dimension values and percentages for earning distributions. This information can be changed on individual earning lines.</p>
    <div class="alert">

    > [!NOTE]
    > <P>If you select a template in this field, this setting overrides the template that is assigned to the position when you create earnings statement lines.</P>


    </div></td>
    </tr>
    <tr class="even">
    <td><p><strong>Default financial dimensions</strong></p></td>
    <td><p>The default financial dimensions for the main account. When you select a financial dimension value, the <strong>Where the %1 dimension is used</strong> field group displays where the dimension is used in account structures and advanced rule structures.</p>
    <div class="alert">

    > [!NOTE]
    > <P>The dimension values from the earning code and the position are added to the earning line and can be changed. When a value for the same dimension is specified for both the earning code and the position, the dimension value for the earning code is used.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Posting rules</strong></p></td>
    <td><p>The accounting rules that are applied when earnings are posted that are generated for this earning code. The main account for distributions is based on the department, job, and worker selections for each posting rule.</p>
    <div class="alert">

    > [!NOTE]
    > <P>The main account can’t be changed on the earning lines.</P>


    </div></td>
    </tr>
    </tbody>
    </table>


6.  Complete the relevant information on the **Reporting** tab. This tab contains tax-related information that is required by the Internal Revenue Service (IRS).
    
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
    <td><p><strong>Form W-2 control data</strong></p></td>
    <td><p>The box number and label on Form W-2 that is used to report tax-related information to the IRS.</p></td>
    </tr>
    </tbody>
    </table>


7.  Complete the relevant information on the **Earning code groups** tab. This tab displays the earning code groups that the selected earning code is assigned to, and lets you add and remove earning code groups to and from the earning code.
    
    You can create earning code groups in the **Earning code groups** form.
    
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
    <td><p><strong>Add</strong></p></td>
    <td><p>Select the earning code group to assign the earning code to. Earning code groups that already include the earning code aren’t available.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Remove</strong></p></td>
    <td><p>Select the earning code group to remove the earning code from, and then click <strong>Remove</strong>. The earning code group still exists, but no longer includes the selected earning code.</p></td>
    </tr>
    </tbody>
    </table>


## 3\. If required: Create earning code groups

Earning code groups are required when you select the **Percent of earnings**, **Hours of earnings**, and **Regular rate of pay** options for rate basis.


> [!WARNING]
> <P>If you use regular-rate-of-pay-earning codes to calculate and pay the overtime premiums that are required by FLSA, every earning code for nondiscretionary earnings must be included in the earning code group that is used by the regular-rate-of-pay earning codes. If any earning codes are omitted from the earning code group, the overtime premium won’t be calculated correctly.</P>



Earning code groups can also be used to make it easier to manage earning codes. For example, you can create a group that contains all earning codes that apply to union members. If changes in the union contract require you to update these earning codes, the earning code group makes it easy for you to identify the affected earning codes.

You can assign earning codes to groups when you create them, or you can assign an earning code to a group on the **Earning code groups** tab of the **Earning codes** form.

To create an earning code group, follow these steps:

1.  Click **Payroll \> Setup \> Earnings \> Earning code groups**.

2.  Click **New**.

3.  Enter a name for the earning code group. This might be the name of the group of workers who have the same earning codes, such as Admin, or it might be a group of earning codes that are used together to calculate a premium earning, such as 2nd shift.

4.  Enter a description, such as Administrative assistants or Second shift differential to help users make the appropriate selection when they use the earning code group.

5.  Click **Add**.

6.  Select an earning code to add to the group.

7.  Repeat these steps until you list all the earning codes to include in this group.
    

    > [!TIP]
    > <P>You can’t change the earning code values in this form. If an earning code isn’t accurate for this group, you can change the existing earning code in the <STRONG>Earning codes</STRONG> form, or you can create a new earning code as described in the “Create earning codes” section earlier in this topic.</P>



## 4\. Optional: View the groups that include an earning code and add earning codes to the group

To view all the earning code groups that include a specific earning code, and to change which earning codes are in a group, follow these steps:

1.  Click **Payroll** \> **Setup** \> **Earnings** \> **Earning codes**.

2.  Select the earning code to view the groups for.

3.  On the **Earning code groups** tab, view the earning code groups that include the earning code.

4.  Optional: Click **Add** to add more earning codes to the group, or click **Remove** to remove the selected earning code from the group.

## Next step

The next step is to set up schedules, leave types, and benefit accrual plans. For more information, see [Work schedule and leave tasks](work-schedule-and-leave-tasks.md) and [Benefit accrual plan tasks](benefit-accrual-plan-tasks.md).

## Related tasks

[Generate earnings](generate-earnings.md)

[Processing payroll](processing-payroll.md)

[Generating payroll reports](generating-payroll-reports.md)

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
<td><p>To set up earning codes and earning code groups, you must be a member of a security role that includes these duties:</p>
<ul>
<li><p><strong>Set up payroll master data</strong> (PayrollMasterDataMaintain)</p></li>
<li><p><strong>Inquire into payroll master data</strong> (PayrollMasterDataInquire)</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To set up earning codes and earning code groups, you must be a member of a security role that includes these privileges:</p>
<ul>
<li><p><strong>Maintain earning codes</strong> (PayrollEarningCodeMaintain)</p></li>
<li><p><strong>Maintain payroll earning code groups</strong> (PayrollEarningCodeGroupMaintain)</p></li>
</ul></td>
</tr>
</tbody>
</table>


## See also

[Earning code examples](earning-code-examples.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

