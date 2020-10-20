---
title: About compensation plans
TOCTitle: About compensation plans
ms:assetid: e6327f6b-6b54-4f59-81b8-242bdda5d8d7
ms:mtpsurl: https://technet.microsoft.com/library/Hh781107(v=AX.60)
ms:contentKeyID: 43894524
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About compensation plans 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You use compensation management to control the delivery of base pay and awards. You control an employee's fixed base pay and merit increases through fixed compensation plans. You control the payment of incentive pay, such as bonus payments, performance awards, stock options, and grants, and also one-time awards, through variable compensation plans.

Employees can be enrolled in one or more plans of both types. An employee must meet the following requirements in order to be eligible for enrollment in a compensation plan:

  - The employee must have an active position assignment.

  - The employee must meet the criteria that are defined by eligibility rules for a compensation plan.

## Compensation setup

The following table lists components of the compensation process that can be integral in setting up your company's compensation plans. For specific compensation tasks, see [Key tasks: Compensation plans](key-tasks-compensation-plans.md).

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Component</p></th>
<th><p>More information…</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Fixed compensation actions</p></td>
<td><p>Fixed compensation actions have two purposes:</p>
<ul>
<li><p>The fixed compensation action is mandatory information if you change the fixed compensation setup for an employee to increase or decrease the employee's base pay. For example, you might have to indicate that the reason or the change is for a promotion or a demotion.</p></li>
<li><p>The actions are applied to an event process when fixed compensation plans are calculated.</p></li>
</ul>
<p>For more information, see <a href="https://technet.microsoft.com/library/hh694711(v=ax.60)">Fixed compensation actions (form)</a>.</p></td>
</tr>
<tr class="even">
<td><p>Levels</p></td>
<td><p>Levels are associated with jobs and any positions that are related to a job reference. You can create discrete levels for the three types of compensation plans: <strong>Grade</strong>, <strong>Band</strong>, and <strong>Step</strong>. For more information, see <a href="https://technet.microsoft.com/library/hh208814(v=ax.60)">Levels (form)</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Range utilization matrix</p></td>
<td><p>A range utilization matrix helps you transition employees to the control point for their jobs.</p>
<p>You can also use range utilization to control pay rate equity in the company without regard to an individual employee's performance or the overall performance of the company. For example, employees who are paid lower in their range get higher percentage increases than employees who are paid higher in the range. In this manner, you can systematically offset equity differences.</p>
<p>The range utilization is calculated as follows: (Fixed Pay Rate - Range Minimum) ÷ (Range Maximum - Range Minimum).</p></td>
</tr>
<tr class="even">
<td><p>Reference point setups</p></td>
<td><p>A reference point setup includes a set of reference points that represent ranges in a matrix. Each range can be associated with a pay rate. For more information, see <a href="https://technet.microsoft.com/library/hh803014(v=ax.60)">Reference point setups (form)</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Compensation matrix</p></td>
<td><p>A compensation matrix is a set of reference points and levels that you use to create a compensation structure.</p></td>
</tr>
<tr class="even">
<td><p>Compensation structure</p></td>
<td><p>A compensation structure is a compensation matrix that has ranges that are associated with pay rates.</p></td>
</tr>
<tr class="odd">
<td><p>Eligibility rules</p></td>
<td><p>Eligibility rules are used to identify employees in specific jobs, job functions, job types, departments, labor unions, or compensation regions that are covered by specific compensation plans. You can create eligibility rules for both variable and fixed compensation plans.</p>
<p>After eligibility rules are specified for a compensation plan, you can define the levels from the plan that should apply to the jobs that are covered by the plan.</p></td>
</tr>
<tr class="even">
<td><p>Pay frequencies</p></td>
<td><p>Pay frequencies are used to define the frequency of employee payment. Pay frequencies are also used to set up conversion factors to convert compensation from monthly, weekly, biweekly and hourly pay frequencies to an annual pay frequency.</p></td>
</tr>
<tr class="odd">
<td><p>Compensation regions</p></td>
<td><p>Compensation regions are used to specify employee compensation based on the location of the workplace. For more information, see <a href="https://technet.microsoft.com/library/hh209560(v=ax.60)">Compensation regions (form)</a>.</p></td>
</tr>
<tr class="even">
<td><p>Control point</p></td>
<td><p>The control point is the ideal pay rate for all employees at a compensation level. For grade plan structures, control points are typically the midpoint of the ranges. Band structures rarely use control points. You can specify the control point for a fixed compensation plan in the <strong>Fixed compensation plans</strong> form. For more information, see <a href="https://technet.microsoft.com/library/hh242871(v=ax.60)">Fixed compensation plans (form)</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Job functions</p></td>
<td><p>Job functions can be classified and then combined with job types to filter compensation plans to specific jobs. For more information, see <a href="https://technet.microsoft.com/library/hh209705(v=ax.60)">Job functions (form)</a>.</p></td>
</tr>
<tr class="even">
<td><p>Job types</p></td>
<td><p>Job types can be classified and then combined with job functions to filter compensation plans to specific jobs. For more information, see <a href="https://technet.microsoft.com/library/hh209312(v=ax.60)">Job types and exempt status (form)</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Variable compensation types</p></td>
<td><p>Variable compensation types, such as stock awards or cash award bonuses, are set up in variable compensation plans. For more information, see <a href="https://technet.microsoft.com/library/hh803008(v=ax.60)">Variable compensation types (form)</a>.</p></td>
</tr>
<tr class="even">
<td><p>Compensation grids</p></td>
<td><p>Compensation grids can be set up if your company does not use Microsoft Dynamics AX to set up compensation plans. For more information, see <a href="https://technet.microsoft.com/library/hh694712(v=ax.60)">Compensation grids (form)</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Performance plans</p></td>
<td><p>Performance plans are used to associate performance with an allocation matrix, so that you can use the plan in a pay-for-performance strategy. For more information, see <a href="https://technet.microsoft.com/library/hh781096(v=ax.60)">Performance plans (form)</a>.</p></td>
</tr>
<tr class="even">
<td><p>Performance ratings</p></td>
<td><p>Performance ratings are used in compensation plans to determine the amount of a merit award or performance award. For more information, see <a href="https://technet.microsoft.com/library/hh781109(v=ax.60)">Performance ratings (form)</a>.</p></td>
</tr>
</tbody>
</table>


## Process events

A process event calculates compensation information for a specific period for all employees who are enrolled in one or more fixed or variable compensation plans. You can run a process event repeatedly to test or update calculated compensation results. When the calculations are correct, you can load the process event to update the compensation records for the employees who are affected by the process event.

## Recommendations

After you run a process event, you can recommend adjustments to an employee’s merit increase or award amount, based on the calculated guidelines of the process event. To make recommendations for employees, you must enable recommendations when you set up compensation plans or when you set up the process event.

## See also

[Key tasks: Pay for performance](key-tasks-pay-for-performance.md)

  


