---
title: Generating payroll reports
TOCTitle: Generating payroll reports
ms:assetid: 59e9512a-8ec9-4f4f-b2c8-2fde6b57c281
ms:mtpsurl: https://technet.microsoft.com/library/JJ677340(v=AX.60)
ms:contentKeyID: 49384114
author: tonyafehr
ms.date: 11/15/2014
mtps_version: v=AX.60
f1_keywords:
- report
- reports
- pay statement
- tax register
- electronic form w-2
- form w-2
- form w-2 reconciliation
- payroll reports
- payroll tax register
- worker payment register
- custom report
- payroll report
- pay statements
- ad hoc reports
- custom reports
- ad hoc payroll report
- ad hoc payroll reports
- ad hoc report
- custom payroll report
- custom payroll reports
- form w-2 reconciliation report
audience: Application User
ms.search.region: USA
---

# Generating payroll reports 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Microsoft Dynamics AX provides a set of standard payroll reports to assist you with payroll processing and government reporting. If you have installed Microsoft Dynamics AX 2012 R3 or cumulative update 7 or later for AX 2012 R2, a Payroll data cube is also available. Use the standard reports to create pay statements and W-2 forms to issue to your workers, to validate payroll taxes and benefit amounts, and to complete federal and state regulatory reports. Use the Payroll cube to create custom reports that answer a variety of questions that you might have about your payroll data.

This topic describes functionality that is available only if the **Payroll - USA** configuration key is selected.


> [!NOTE]
> <P>This topic includes information about features that were added or changed for cumulative update 7 or later for Microsoft Dynamics AX 2012 R2. This information also applies to AX 2012 R3.</P>



## Standard Payroll reports

The following table summarizes when and why you would use each report. For more information about how to use reports, see [Microsoft Dynamics AX reports](microsoft-dynamics-ax-reports.md).

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Report</p></th>
<th><p>Each pay period</p></th>
<th><p>Quarterly</p></th>
<th><p>Annually</p></th>
<th><p>As required</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Pay statements</strong></p></td>
<td><p>After you generate the payroll payment journal, use this report to print pay statements to issue to workers.</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>Use this report to reprint pay statements for workers.</p></td>
</tr>
<tr class="even">
<td><p><strong>Benefit register</strong></p></td>
<td><p>Use this report to validate the benefit amounts that were calculated during payroll processing.</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>Use this report to validate the benefit amounts that were calculated during payroll processing.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Worker payment register</strong></p></td>
<td><p>To comply with auditing best practices, use this payroll report each pay period to validate data and to sign off on pay runs.</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>Tax register</strong></p></td>
<td><p>Use this report to validate the tax amounts that were calculated during payroll processing.</p></td>
<td><p>Use this report to validate the tax amounts that were calculated during payroll processing.</p></td>
<td><p>Use this report to validate the tax amounts that were calculated during payroll processing.</p></td>
<td><p>Use this report to validate the tax amounts that were calculated during payroll processing.</p></td>
</tr>
<tr class="odd">
<td><p><strong>State quarterly wage and tax preparation</strong></p></td>
<td><p></p></td>
<td><p>Use the information in this report when you prepare the quarterly wage and tax forms for state unemployment taxes.</p>
<div class="alert">

> [!NOTE]
> <P>This report is available only if you have installed Microsoft Dynamics AX 2012 R3 or cumulative update 7 or later for AX 2012 R2.</P>


</div></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>Form 941 preparation</strong></p></td>
<td><p></p></td>
<td><p>Use the information in this form when you prepare the quarterly report of payroll taxes for the IRS.</p>
<div class="alert">

> [!NOTE]
> <P>This report is available only if you have installed Microsoft Dynamics AX 2012 R3 or cumulative update 7 or later for AX 2012 R2.</P>


</div></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>Form 940 preparation</strong></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>Use the information in this report when you prepare the annual federal unemployment (FUTA) tax return.</p>
<div class="alert">

> [!NOTE]
> <P>This report is available only if you have installed Microsoft Dynamics AX 2012 R3 or cumulative update 7 or later for AX 2012 R2.</P>


</div></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>Form W-2 reconciliation</strong></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>Use this report to balance Form W-2s and to run validation before you issue Form W-2s to workers.</p></td>
<td><p>Use this report to balance Form W-2s and to run validation before you issue Form W-2s to workers.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Form W-2</strong></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>Use this report to create Form W-2s to issue to workers.</p></td>
<td><p>Use this report to create Form W-2s to issue to workers.</p></td>
</tr>
<tr class="even">
<td><p><strong>Electronic Form W-2</strong></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>Use this report to file Form W-2s with the Social Security Administration.</p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


## Custom Payroll reports in Microsoft Dynamics AX 2012 R3 or cumulative update 7 or later for AX 2012 R2

The following tables provide examples of common questions you might ask, and the measures and dimensions in the data cube for Payroll that you can use to answer those questions.

After the data cube has been deployed and processed at least one time, you can use Microsoft Excel, Microsoft SQL Server Analysis Services, or other tools to create custom reports based on the data in the cube. As you become more familiar with the data cube, you’ll be able to find answers to more and more of your questions.

If you have Power View configured, you can also access the data cube from the **Workers** list page. To do this, click the **Analyze data** button on the **Payroll** tab in the **Action Pane**. Power View provides quick and easy visualization of your data. When you use Power View, you can access the same measures and dimensions you would access by using Excel or SQL Server Analysis Services. After you select the dimensions and measures, you can quickly visualize raw data, adjust it to make multiple charts that correspond to each other, and save the charts to a library. You can access that library in a list format or place any chart from the library into any Role Center.


> [!TIP]
> <P>The data in the custom reports will be accurate as of the last time the cube was processed. To keep the data current, the cube should be processed frequently, for example, each night.</P>



For more information about how to create custom reports from the data in a cube, see [Create a report by using Power View to connect to a cube](create-a-report-by-using-power-view-to-connect-to-a-cube.md), [Create a report by using SQL Server Report Builder to connect to a cube](create-a-report-by-using-sql-server-report-builder-to-connect-to-a-cube.md), or [Create a report by using the Excel data connection wizard to connect to a cube](create-a-report-by-using-the-excel-data-connection-wizard-to-connect-to-a-cube.md).

## Pay and earnings

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Questions to answer</p></th>
<th><p>Measures and attributes to use</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>What was the gross amount of each pay statement in a particular pay period?</p></td>
<td><ul>
<li><p>The <strong>Pay statement - sum of gross amount</strong> measure in the <strong>Pay statements</strong> measure group</p></li>
<li><p>The <strong>Pay statement number</strong> dimension attribute under the <strong>Pay statements</strong> dimension</p></li>
<li><p>A filter for the pay period using the <strong>Pay period end date</strong> dimension attribute under the <strong>Pay period</strong> dimension</p></li>
</ul>
<div class="alert">

> [!TIP]
> <P>To see the combined gross pay for all pay statements in all pay periods, delete the <STRONG>Pay statement number</STRONG> dimension attribute and clear the filter.</P>


</div></td>
</tr>
<tr class="even">
<td><p>What was a worker’s gross pay and net pay for a particular pay statement?</p></td>
<td><ul>
<li><p>The following measures in the <strong>Pay statements</strong> measure group:</p>
<ul>
<li><p><strong>Pay statement - sum of gross amount</strong></p></li>
<li><p><strong>Pay statement - sum of net amount</strong></p></li>
</ul></li>
<li><p>The <strong>Pay statement number</strong> dimension attribute under the <strong>Pay statements</strong> dimension</p></li>
<li><p>The <strong>Worker</strong>.<strong>Worker - Name</strong> dimension attribute under the <strong>Worker</strong> dimension</p>
<p>–or–</p>
<p>A filter for the worker’s name in the <strong>Worker</strong>.<strong>Worker - Name</strong> dimension attribute under the <strong>Worker</strong> dimension</p>
<p></p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>What was the average gross pay per pay statement for each worker last year?</p></td>
<td><ul>
<li><p>The <strong>Pay statement - average of gross amount</strong> measure in the <strong>Pay statements</strong> measure group</p></li>
<li><p>The <strong>Worker</strong>.<strong>Worker - Name</strong> dimension attribute under the <strong>Worker</strong> dimension</p></li>
<li><p>A filter for the last calendar year using the <strong>Accounting date</strong>.<strong>Year</strong> dimension attribute under the <strong>Accounting date</strong> dimension</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Which workers receive physical checks instead of electronic payments?</p></td>
<td><ul>
<li><p>The <strong>Number of workers paid by check</strong> measure in the <strong>Payroll workers</strong> measure group</p></li>
<li><p>The <strong>Worker</strong>.<strong>Worker - Name</strong> dimension attribute under the <strong>Worker</strong> dimension</p></li>
<li><p>(Optional) The <strong>Company</strong> dimension attribute under the <strong>Company</strong> dimension</p></li>
</ul>
<div class="alert">

> [!TIP]
> <P>A 1 for the worker means that the worker is paid by check. A 0 means that the worker is paid electronically.</P>
> <P>If you want to know how many workers are paid by check, and not which ones, omit the <STRONG>Worker</STRONG>.<STRONG>Worker - Name</STRONG> dimension attribute.</P>


</div></td>
</tr>
<tr class="odd">
<td><p>What is the amount of earnings per pay statement?</p></td>
<td><ul>
<li><p>The <strong>Pay statement lines - sum of earning lines amounts</strong> measure in the <strong>Pay statements</strong> measure group</p></li>
<li><p>The <strong>Pay statement number</strong> dimension attribute under the <strong>Pay statements</strong> dimension</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>How many earnings statements from a particular pay period included lines that were entered manually?</p></td>
<td><ul>
<li><p>The <strong>Earning statements count</strong> measure in the <strong>Worker earnings statement totals</strong> measure group</p></li>
<li><p>The <strong>Pay period end date</strong> dimension attribute under the <strong>Pay period</strong> dimension</p></li>
<li><p>A filter for the <strong>Source</strong> dimension attribute under the <strong>Earnings statement</strong> dimension where the attribute value is {User entry}</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>What is the average amount of earnings statement lines for a particular worker?</p></td>
<td><ul>
<li><p>The <strong>Earnings statement lines - average of line amounts</strong> measure in the <strong>Worker earnings statement totals</strong> measure group</p></li>
<li><p>A filter for the <strong>Worker</strong>.<strong>Worker - Name</strong> dimension attribute under the <strong>Worker</strong> dimension where the attribute value is the worker’s name</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Taxes and benefits

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Questions to answer</p></th>
<th><p>Measures and attributes to use</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>How much did we pay in state unemployment insurance last year?</p></td>
<td><ul>
<li><p>The <strong>Pay statement lines - sum of tax line amounts</strong> measure in the <strong>Pay statements</strong> measure group</p></li>
<li><p>A filter for the <strong>Tax code type</strong> dimension attribute under the <strong>Tax code</strong> dimension where the attribute value is {State unemployment insurance}</p></li>
<li><p>A filter for the <strong>Accounting date</strong>.<strong>Year</strong> dimension attribute under the <strong>Accounting date</strong> dimension where the attribute value is the last calendar year</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>How many employees have waived healthcare coverage?</p></td>
<td><ul>
<li><p>The <strong>Number of benefit enrollments</strong> measure in the <strong>Payroll worker enrolled benefits</strong> measure group</p></li>
<li><p>A filter for the <strong>Benefit type</strong> dimension attribute under the <strong>Benefit type</strong> dimension where the attribute value is {Medical}</p></li>
<li><p>A filter for the <strong>Benefit option</strong> dimension attribute under the <strong>Benefit option</strong> dimension where the attribute value is {Waive}</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Which benefits are most used by employees?</p></td>
<td><ul>
<li><p>The <strong>Number of benefit enrollments</strong> measure in the <strong>Payroll worker enrolled benefits</strong> measure group</p></li>
<li><p>The <strong>Payroll benefit plan</strong> dimension attribute under the <strong>Payroll benefit plan</strong> dimension</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>How many workers have tax levies and garnishments?</p></td>
<td><ul>
<li><p>The <strong>Number of benefit enrollments</strong> measure in the <strong>Payroll worker enrolled benefits</strong> measure group</p></li>
<li><p>A filter for the <strong>Benefit type</strong> dimension attribute under the <strong>Benefit type</strong> dimension where the attribute value is {Garnishment, Tax levy}</p></li>
</ul>
<div class="alert">

> [!TIP]
> <P>The total shows the number of enrollments in tax levies and garnishments, not the number of workers. To determine the number of workers, you can add the <STRONG>Worker</STRONG>.<STRONG>Worker - Name</STRONG> dimension attribute under the <STRONG>Worker</STRONG> dimension, which will allow you to find workers with multiple enrollments.</P>


</div></td>
</tr>
<tr class="odd">
<td><p>How much has the company contributed for healthcare benefits?</p></td>
<td><ul>
<li><p>The <strong>Sum of contribution amount</strong> measure in the <strong>Payroll worker enrolled benefits</strong> measure group</p></li>
<li><p>A filter for the <strong>Benefit type</strong> dimension attribute under the <strong>Benefit type</strong> dimension where the attribute value is {Medical}</p></li>
</ul>
<div class="alert">

> [!TIP]
> <P>To see the amount that has been contributed for a specific plan, delete the <STRONG>Benefit type</STRONG> filter and add a filter using the <STRONG>Payroll benefit plan</STRONG> dimension attribute under the <STRONG>Payroll benefit plan</STRONG> dimension.</P>


</div></td>
</tr>
<tr class="even">
<td><p>How much has been deducted from worker pay for healthcare benefits?</p></td>
<td><ul>
<li><p>The <strong>Sum of deduction amount</strong> measure in the <strong>Payroll worker enrolled benefits</strong> measure group</p></li>
<li><p>A filter for the <strong>Benefit type</strong> dimension attribute under the <strong>Benefit type</strong> dimension where the attribute value is {Medical}</p></li>
<li><p>(Optional) A filter for the <strong>Worker</strong>.<strong>Worker - Name</strong> dimension attribute under the <strong>Worker</strong> dimension where the attribute value is the worker’s name</p></li>
</ul>
<div class="alert">

> [!TIP]
> <P>To see the amount that has been deducted for a specific plan, delete the <STRONG>Benefit type</STRONG> filter and add a filter using the <STRONG>Payroll benefit plan</STRONG> dimension attribute under the <STRONG>Payroll benefit plan</STRONG> dimension.</P>


</div></td>
</tr>
<tr class="odd">
<td><p>What is the total cost of benefits by worker?</p></td>
<td><ul>
<li><p>The following measures in the <strong>Payroll worker enrolled benefits</strong> measure group:</p>
<ul>
<li><p><strong>Sum of contribution amount</strong></p></li>
<li><p><strong>Sum of deduction amount</strong></p></li>
<li><p><strong>Sum of default deduction amount</strong></p></li>
<li><p><strong>Sum of default contribution amount</strong></p></li>
</ul></li>
<li><p>The <strong>Worker</strong>.<strong>Worker - Name</strong> dimension attribute under the <strong>Worker</strong> dimension</p></li>
</ul></td>
</tr>
</tbody>
</table>


## PTO and other benefit accrual plans

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Questions to answer</p></th>
<th><p>Measures and attributes to use</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>How much sick time has been used at one company compared to another company?</p></td>
<td><ul>
<li><p>The <strong>Total used</strong> measure in the <strong>Benefit accruals</strong> measure group</p></li>
<li><p>(Optional) The <strong>Company</strong> dimension attribute under the <strong>Company</strong> dimension</p></li>
<li><p>A filter for the sick-time plan using the <strong>Benefit accrual plan</strong> dimension attribute under the <strong>Benefit accrual plan</strong> dimension</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>How many hours of PTO were carried over from last year to this year?</p></td>
<td><ul>
<li><p>The <strong>Total carry-forward</strong> measure in the <strong>Benefit accruals</strong> measure group</p></li>
<li><p>A filter for the PTO plan using the <strong>Benefit accrual plan</strong> dimension attribute under the <strong>Benefit accrual plan</strong> dimension</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>How many hours did a worker have accrued in the benefit accrual plan for sick time as of a particular pay statement?</p></td>
<td><ul>
<li><p>The <strong>Pay statement accrual balances - sum of accrued hours</strong> measure in the <strong>Pay statements</strong> measure group</p></li>
<li><p>The <strong>Pay statement number</strong> dimension attribute under the <strong>Pay statements</strong> dimension</p></li>
<li><p>(Optional) A filter for a specific worker name using the <strong>Worker</strong>.<strong>Worker - Name</strong> dimension attribute under the <strong>Worker</strong> dimension</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Tips

  - Some dimensions, such as those related to benefit deductions and contributions, do not contain date attributes. For these dimensions, you can’t answer questions about what a measure was during a particular time period, or how it changed over time.

  - When you work with the **Positions** dimension, you see attributes called **ValidFrom** and **ValidTo**. Use these dimension attributes when you analyze date-effective information about positions and workers.
    
    To see which details are date effective, click the **Maintain versions** button in the **Position** form to open the date manager form. All these field values have an effective date and an expiration date, which are reflected in the cube as **ValidFrom** and **ValidTo**.

  - Under the **Payroll employment** dimension, you can use a filter with the **Is position worker assignment active** dimension attribute set to **Yes** to help you view date-effective data. This attribute filters out data that is out of date. For example, if you use the **Number of employments** measure in the **Payroll workers** together with the company, department, and worker dimensions, you might see a count of 11 instead of 7 because a worker might have worked in one of the positions in a specific department in the past. The past position adds to the count unless you set **Is position worker assignment active** to **Yes**.

  - A worker can have more than one position assignment and can have an employment in more than one company at the same time. As a result, the **Number of employments** measure and the **Number of position assignments** measure in the **Payroll workers** measure group give different results when they are used with the **Company** dimension. The **Company** dimension attribute represents the legal entity. When you use it with the **Number of employments** measure, it shows the number of past, present, and future employments in the legal entity. When you use it with the **Number of position assignments** measure, it shows the total number of past, present, and future position assignments that have been assigned to workers in a company.

  - Under the **Worker** dimension, there are two dimension attributes for the names of workers, **Worker**.**Worker** and **Worker**.**Worker - Name**. The **Worker**.**Worker** attribute shows duplicates, and the **Worker**.**Worker - Name** attribute shows distinct values. When you create a report by using measures and dimensions, it doesn’t matter which one that you use; both attributes produce the same results.

  - As you work with dimensions, sometimes you see an **IsNotApplicable** dimension attribute. This attribute is added to every dimension because one row always is retained for records that are not applicable. If a measure contains any values that are not in the dimension, the measure is designated as **IsNotApplicable**.

  


