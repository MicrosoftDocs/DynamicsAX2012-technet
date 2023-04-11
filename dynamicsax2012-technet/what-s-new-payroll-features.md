---
title: "What's new: Payroll features"
TOCTitle: Payroll features
ms:assetid: f7d33a7c-61c3-4313-871c-9756b62f74d1
ms:mtpsurl: https://technet.microsoft.com/library/Dn527242(v=AX.60)
ms:contentKeyID: 59623370
author: tonyafehr
ms.date: 11/14/2014
mtps_version: v=AX.60
---

# What's new: Payroll features 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Payroll processing was redesigned in Microsoft Dynamics AX 2012 R2 and now provides a more consistent user interface. Additionally, setup and data entry have been simplified.

## What’s new in AX 2012 R2

## Overview

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Item</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Required</p></td>
<td><p>Optional. You might not use these features, depending on how you run your business.</p></td>
</tr>
<tr class="even">
<td><p>Feature areas affected</p></td>
<td><p>Accounts payable</p>
<p>Human resources</p>
<p>General ledger</p>
<p>Project management and accounting</p></td>
</tr>
<tr class="odd">
<td><p>Stakeholders</p></td>
<td><p>Business decision makers</p>
<p>Technical decision makers</p>
<p>Implementation team members</p>
<p>Independent software vendors (ISVs)/developers</p>
<p>Partners</p></td>
</tr>
</tbody>
</table>


## New functionality

Payroll now handles mandatory deductions for garnishments (such as child support orders) and tax levies. When there is more than one garnishment order for a worker, the calculation sequences make sure that each garnishment is handled correctly, and that the combined deductions are not more than the amount that is legally allowed.

Before you can generate pay by using Payroll, positions must be assigned to workers. Position settings are used to control how earnings are generated. These settings are also used for workers’ compensation, general liability insurance, and unions.

Many payroll settings are now date effective. The date-effective settings make it easier to maintain data for which changes must be tracked at different times. For example, if a worker notifies you that her residence will change in a month, you can enter the future-dated change immediately. The current residency information is used until the effective date that you set up for the new information, and then the new information is automatically used.

## Special considerations

Payroll data and settings from Microsoft Dynamics AX 2009 can be migrated to Payroll for Microsoft Dynamics AX 2012. Due to the wide range of enhancements, many new settings must be configured before you can run payroll for the first time after migration.

Benefits and deductions have changed extensively from AX 2009. Benefit setup and the determination of eligibility for benefits are both handled in Human resources. Setup for deductions and contributions is performed in Payroll. Workers can be enrolled in benefits from either Human resources or Payroll.

The processes for posting payroll and issuing worker payments are now separate. Additionally, some terms that were used in AX 2009 have changed in AX 2012 so that they better match standard usage in the payroll industry.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Term used inAX 2009</p></th>
<th><p>New term for AX 2012</p></th>
<th><p>Comments</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Benefit</p></td>
<td><p>Benefit accrual</p></td>
<td><p>Benefit accrual plans for sick leave and paid time off can be set up in forms that you open from the <strong>Setup</strong>group on the <strong>Payroll</strong> area page.</p></td>
</tr>
<tr class="even">
<td><p>Fringe benefit</p></td>
<td><p>Benefit</p></td>
<td><p>Fringe benefits have been merged with all other benefits in AX 2012. What was known as a fringe benefit in AX 2009 is now a benefit that has an employer contribution but does not have a worker deduction.</p></td>
</tr>
<tr class="odd">
<td><p>Imputed earning</p></td>
<td><p>Fringe benefit</p></td>
<td><p>An imputed earning is now a fringe benefit that workers are taxed on, such as life insurance, even though the workers do not receive an increase in pay.</p></td>
</tr>
<tr class="even">
<td><p>Pay elements</p></td>
<td><p>Earning codes</p></td>
<td><p>Pay elements that were previously combined, such as deductions, contributions, and union fringe benefits, are now separate and are referred to as earning codes.</p></td>
</tr>
</tbody>
</table>


## Comparison with AX 2009

Payroll has changed considerably since AX 2009. AX 2012 includes the following new functionality:

  - Handling for garnishments (such as child support orders) and tax levies

  - Position settings for payroll

The following Payroll functionality has changed for AX 2012:

  - Payroll taxes

  - Benefit accrual plans, such as paid time off and sick leave

  - Generation of earnings statements

  - Generation of pay statements

  - Earning codes to identify the type of earnings that workers receive for their services

  - Worker settings for payroll

  - Benefits and deductions

  - Posting and issuing pay

## Handling for garnishments (such as child support orders) and tax levies

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Set up deductions to process garnishments (such as child support orders) and tax levies.</p></td>
<td><p>Not available.</p></td>
<td><p>Set up garnishments and tax levies by using the same forms and controls that you use to set up benefits.</p></td>
<td><p>Data entry is simplified.</p></td>
</tr>
<tr class="even">
<td><p>Enter and store the state and federal requirements that are used to determine disposable income.</p></td>
<td><p>Not available.</p></td>
<td><p>Specify percentage-based limits and other data that is required to make sure that a garnishment or levy does not reduce a worker’s net pay below the minimum that is set by federal, state, or local governments.</p></td>
<td><p>Your payroll process complies with applicable legal requirements.</p></td>
</tr>
<tr class="odd">
<td><p>Correctly calculate deductions for one or more garnishments or tax levies.</p></td>
<td><p>Not available.</p></td>
<td><p>Specify the amount or percentage of wages to deduct, and the lifetime limit for the garnishment, if applicable. You can also specify the order in which deductions are calculated and the maximum percentage of the base wages that can be deducted.</p></td>
<td><p>Net pay is calculated correctly.</p></td>
</tr>
</tbody>
</table>


## Position settings for payroll

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Use position settings to control how earnings are generated.</p></td>
<td><p>Not available.</p></td>
<td><p>Specify the legal entity that the position is paid from, and set the typical hours that are worked per year and per pay cycle for the position. You can also select whether to generate pay based on salary or a schedule.</p></td>
<td><p>The amount of data entry that is required when workers change positions is reduced, and the risk of payroll errors is minimized.</p></td>
</tr>
<tr class="even">
<td><p>Set up workers’ compensation, general liability insurance, and union settings for the position.</p></td>
<td><p>Not available.</p></td>
<td><p>Assign default values to positions, so that you can control the standard worker settings.</p></td>
<td><p>The amount of data entry that is required when workers change positions is reduced, and the risk of errors is minimized.</p></td>
</tr>
<tr class="odd">
<td><p>Set up accounting details, such as financial dimensions and template support, for the position.</p></td>
<td><p>Accounting details were set up for the worker.</p></td>
<td><p>Assign default values to positions, so that you can control the standard worker settings.</p></td>
<td><p>The amount of data entry that is required when workers change positions is reduced, and the risk of errors is minimized.</p></td>
</tr>
</tbody>
</table>


## Payroll taxes

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Use position settings to control how earnings are generated.</p></td>
<td><p>Not available.</p></td>
<td><p>Specify the legal entity that the position is paid from, and set the typical hours that are worked per year and per pay cycle for the position. You can also select whether to generate pay based on salary or a schedule.</p></td>
<td><p>The amount of data entry that is required when workers change positions is reduced, and the risk of payroll errors is minimized.</p></td>
</tr>
<tr class="even">
<td><p>Set up workers’ compensation, general liability insurance, and union settings for the position.</p></td>
<td><p>Not available.</p></td>
<td><p>Automatically assign default values to workers’ positions, so that you can control the standard worker settings.</p></td>
<td><p>The amount of data entry that is required when workers change positions is reduced, and the risk of errors is minimized.</p></td>
</tr>
<tr class="odd">
<td><p>Set up accounting details, such as financial dimensions and template support, for the position.</p></td>
<td><p>Accounting details were set up for the worker.</p></td>
<td><p>Automatically assign default values to workers’ positions, so that you can control the standard worker settings.</p></td>
<td><p>The amount of data entry that is required when workers change positions is reduced, and the risk of errors is minimized.</p></td>
</tr>
</tbody>
</table>


## Benefit accrual plans

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Keep a detailed audit history of all changes that are made to workers’ benefit accrual balances.</p></td>
<td><p>Balances could be updated, but no records were kept of when changes were made and who made them.</p></td>
<td><p>Audit records are created for every change in the balance of an accrual plan, regardless of whether the changes are made manually or as part of an automated process.</p></td>
<td><p>The integrity of benefit accrual data is better protected.</p></td>
</tr>
<tr class="even">
<td><p>Accrue balances based on either the worker’s hire date or the seniority date.</p></td>
<td><p>Accrued balances were based on the hire date only.</p></td>
<td><p>You can specify the basis that is used to accrue benefits under a benefit accrual plan.</p></td>
<td><p>You have more flexibility when you design benefit accrual plans.</p></td>
</tr>
<tr class="odd">
<td><p>Configure multiple earning codes to deduct the balances of a plan.</p></td>
<td><p>A single earning code was used for each benefit accrual plan.</p></td>
<td><p>You can set up as many earning codes as you require for each benefit accrual plan. For example, you could use separate earning codes for positions in different legal entities.</p></td>
<td><p>You have more flexibility when you account for benefit accrual plans.</p></td>
</tr>
</tbody>
</table>


## Generation of earnings statements

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Automatically generate earnings.</p></td>
<td><p>Earnings were generated based on a set of working days in a week.</p></td>
<td><p>Generate earnings based on either salary or a schedule.</p></td>
<td><p>Most manual entry is eliminated, and the risk of errors is reduced.</p></td>
</tr>
<tr class="even">
<td><p>Manually generate earnings. You can manually generate earnings that are not related to worked time or to leave.</p></td>
<td><p>Earning information was entered through employee attendance.</p></td>
<td><p>Enter the earning information on an earnings statement.</p></td>
<td><p>You have more flexibility when you enter earnings that are not generated as salary or from a schedule.</p></td>
</tr>
<tr class="odd">
<td><p>Release earnings for payment processing.</p></td>
<td><p>Not available.</p></td>
<td><p>Releasing earnings is a stand-alone procedure that designates the earnings as ready to be processed in a worker payment.</p></td>
<td><p>The release procedure validates that the accounting distributions for the earnings are completed.</p></td>
</tr>
</tbody>
</table>


## Generation of pay statements

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Track pay statements that are generated as part of a group in a single payroll run.</p></td>
<td><p>Not available.</p></td>
<td><p>Batch numbers are automatically assigned when you generate pay statements.</p></td>
<td><p>Reports and other downstream processes can be run on the same set of pay statements.</p></td>
</tr>
<tr class="even">
<td><p>Provide a combined pay statement for workers who hold multiple positions that are paid in the same pay cycle and by the same legal entity.</p></td>
<td><p>A separate pay statement was created for each position that a worker holds.</p></td>
<td><p>Include independent benefits and earnings on a single pay statement.</p></td>
<td><p>The potential for employee confusion is reduced, because employees receive a consolidated pay statement for a given time period.</p></td>
</tr>
</tbody>
</table>


## Earning codes

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Specify accounting templates and dimension values for earning codes.</p></td>
<td><p>Not available.</p></td>
<td><p>Accounting templates and dimensions are linked to earning codes. Therefore, different earnings can be accounted for differently.</p></td>
<td><p>The cost of earnings is distributed to accounting dimensions by using the accounting rules that are specified in the earning code.</p></td>
</tr>
<tr class="even">
<td><p>Integrate Payroll with fixed compensation plans in Human resources.</p></td>
<td><p>Not available.</p></td>
<td><p>When earnings are generated, the earning codes (which are provided for rates calculated per pay period or on an hourly, monthly, or annual basis) reference the fixed compensation plan for the worker’s position.</p></td>
<td><p>Setup of worker earnings is simplified. Additionally, this feature takes advantage of the HCM fixed compensation structure. This means you can specify earnings by position, multiple compensation plans can be active at the same time, and compensation rates can be derived for each worker and position instead of just for each worker.</p></td>
</tr>
<tr class="odd">
<td><p>Create and assign gross-up earning codes.</p></td>
<td><p>Gross-up earnings could be generated, but they were difficult to set up.</p></td>
<td><p>Create earning codes that are used to correctly calculate gross-up earnings. The gross-up amount is the amount that is added to the net take-home pay, so that an employee always receives a specified amount.</p></td>
<td><p>This process automatically “backs out” tax changes that might be missed if they are performed manually. For example, if a tax bracket changes, and a worker receives a 500.00 car allowance, the worker’s pay is automatically adjusted so that 500.00 is still received after the new tax amount is deducted.</p></td>
</tr>
</tbody>
</table>


## Worker settings for payroll

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Set up worker bank accounts.</p></td>
<td><p>An employee bank account in Payroll was used.</p></td>
<td><p>Payroll is integrated with the worker bank account in Human resources, and also with the bank account distributions in Cash and bank management.</p></td>
<td><p>The information is set up and maintained in one area, which means there are fewer chances for discrepancies.</p></td>
</tr>
<tr class="even">
<td><p>Set up bank account disbursements by legal entity.</p></td>
<td><p>Workers were paid through a Payroll bank account.</p></td>
<td><p>Workers are paid through the worker bank account in Human resources.</p></td>
<td><p>The amount of setup that is required is reduced, and integration is improved.</p></td>
</tr>
<tr class="odd">
<td><p>Use date-effective settings to maintain worker information that affects payroll status, such as residency and marital status.</p></td>
<td><p>Changes to tax-related settings were effective as soon as they were entered. There was no record of previous values for those settings.</p></td>
<td><p>You can enter worker information for tax regions and tax codes, and specify the date that the changes take effect.</p></td>
<td><p>Data management is simplified, and payroll taxes are calculated correctly.</p></td>
</tr>
</tbody>
</table>


## Benefits and deductions

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Enroll workers in the benefits they are eligible for by using the new eligibility policy function in Human resources.</p></td>
<td><p>Any worker could be enrolled in any benefit.</p></td>
<td><p>Workers can be enrolled in only the benefits that they meet the eligibility requirements for.</p></td>
<td><p>The policies that your organization sets for benefit eligibility are enforced fairly, and there is less risk of error.</p></td>
</tr>
<tr class="even">
<td><p>Set up benefits in different categories, such as healthcare, retirement, and workers’ compensation.</p></td>
<td><p>Each category of benefits was set up and processed individually.</p></td>
<td><p>Use the same forms and controls to set up all benefit categories.</p></td>
<td><p>Data entry is simplified.</p></td>
</tr>
</tbody>
</table>


## Posting and issuing pay

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Submit pay statements to Accounts payable for payment.</p></td>
<td><p>A single process was used to submit pay statements to Accounts payable and to post the payments.</p></td>
<td><p>Submit pay statements to the payment journal for payment.</p></td>
<td><p>Users have more flexibility to submit pay statements and post payments in any order, so that workers can be paid in a timely manner.</p></td>
</tr>
<tr class="even">
<td><p>Post pay statements.</p></td>
<td><p>A single process was used to submit pay statements to Accounts payable and to post the payments.</p></td>
<td><p>Post the pay statements.</p></td>
<td><p>Users have more flexibility to submit and post pay statements in any order, so that workers can be paid in a timely manner.</p></td>
</tr>
</tbody>
</table>


## More information

For more information, see [Payroll](payroll.md).

## What’s new in cumulative update 7 for Microsoft Dynamics AX 2012 R2

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Update benefit rates for workers.</p></td>
<td><p>You can now mass-update the rates for worker deductions and employer contributions for all workers who are enrolled in a benefit. Workers who have custom rates are flagged and excluded from the mass-update process.</p>
<p>For more information, see ”Update benefit rates” in <a href="benefit-setup-tasks.md">Benefit setup tasks</a>.</p></td>
</tr>
<tr class="even">
<td><p>Tiered contribution calculation rates for retirement benefit plans.</p></td>
<td><p>You can now create a retirement benefit plan that calculates the employer contribution. This is based on a cumulative tiered calculation of the rows in the contribution calculation rates table.</p>
<p>For more information, see <a href="benefit-setup-tasks.md">Benefit setup tasks</a> and <a href="https://technet.microsoft.com/library/jj677430(v=ax.60)">Contribution calculation rates (form) 6.2 CU7 and prior</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Create and update payroll tax groups.</p></td>
<td><p>You can now create and update groups of payroll taxes. Each tax group contains a set of payroll tax codes. You can update all the tax codes in a tax group at the same time. For example, you can change the vendor and main account for every tax code in a tax group at the same time.</p>
<p>Tax groups can also be used in transaction posting definitions. Each tax code can be included in multiple tax groups, but a tax code can be in only one tax group that is enabled for posting definitions.</p>
<p>For more information, see <a href="https://technet.microsoft.com/library/dn527701(v=ax.60)">Tax groups (form) 6.2 CU7 and prior</a> and <a href="tax-information-tasks.md">Tax information tasks</a>.</p></td>
</tr>
<tr class="even">
<td><p>(USA) Preparation of regulatory compliance reports for payroll.</p></td>
<td><p>The following preparation reports are now provided, to make it easier for employers to complete mandatory reports for payroll:</p>
<ul>
<li><p>Form 940 preparation report</p></li>
<li><p>Form 941 preparation report</p></li>
<li><p>State and quarterly wage and tax preparation report</p></li>
</ul>
<p>These reports provide some or all of the information that is required to complete the mandatory reports. This information lets employers prepare the actual reports in whatever format is required.</p>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="form-940-preparation-report-payrollunempltaxrtnprepreport.md">Form 940 preparation report (PayrollUnemplTaxRtnPrepReport)</a></p></li>
<li><p><a href="form-941-preparation-report-payrollemplquarterfedtax.md">Form 941 preparation report (PayrollEmplQuarterFedTax)</a></p></li>
<li><p><a href="state-quarterly-wage-and-tax-preparation-report-payrollstatewagetaxprepreport.md">State quarterly wage and tax preparation report (PayrollStateWageTaxPrepReport)</a></p></li>
</ul>
<p>These topics are also available in the <a href="report-catalog-for-microsoft-dynamics-ax.md">Report catalog for Microsoft Dynamics AX</a> on TechNet.</p></td>
</tr>
<tr class="odd">
<td><p>Separate positive pay statements for Payroll bank accounts.</p></td>
<td><p>You can now generate a positive pay statement file for your Payroll bank account. You can also configure positive pay for bank accounts that are not Payroll bank accounts, so that you can exclude payroll payments. This change helps make sure that only a Payroll user can generate a positive pay statement for the Payroll bank account.</p></td>
</tr>
</tbody>
</table>


## What’s new in Microsoft Dynamics AX 2012 R3 Cumulative Update 8

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s New</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Automatically calculate regular rate of pay earnings.</p></td>
<td><p>The Fair Labor Standards Act (FLSA) provides the framework for U.S. organizations to pay overtime to workers. One part of FLSA defines the way that the premium portion of overtime pay must be calculated. Failure to calculate the overtime payment correctly can open up the organization and its management team to significant fines and penalties.</p>
<p>By using earning codes that have a rate basis of regular rate of pay to calculate and pay overtime premiums (instead of a standard 1.5x or 2.0x overtime code), the premium calculation will be made according to FLSA rules.</p>
<p>For more information, see Premium earning setup tasks and Generate earnings.</p></td>
</tr>
<tr class="even">
<td><p>Generate premium earnings based on characteristics of the worker or position, or on other earnings.</p></td>
<td><p>You can now use the Dynamics AX policy framework to automatically determine when workers qualify for premium earnings such as shift differentials or certifications held by workers. The premium generation process then calculates the amount of the earnings and adds the appropriate lines to worker pay statements.</p>
<p>For more information, see Premium earning setup tasks and Generate earnings.</p></td>
</tr>
<tr class="odd">
<td><p>Generate retroactive earnings.</p></td>
<td><p>You can now automatically generate retroactive earnings statement lines when a worker receives earnings for past services at a new rate. An example might be an increase in compensation that was agreed on after the worker was already paid.</p>
<p>For more information, see <a href="earning-code-examples.md">Earning code examples</a> and Generate earnings.</p></td>
</tr>
<tr class="even">
<td><p>Additional flexibility for benefit accrual plans.</p></td>
<td><p>New options allow you more flexibility to define when accrual plan benefits are accrued and used.</p>
<p>For more information, see <a href="benefit-accrual-plan-tasks.md">Benefit accrual plan tasks</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Pay statements with zero earnings</p></td>
<td><p>You can now manually generate a pay statement without earnings included. You might do this to update only benefit or tax deductions and contributions. For more information, see Pay statements and the payment generation process.</p></td>
</tr>
</tbody>
</table>

  


