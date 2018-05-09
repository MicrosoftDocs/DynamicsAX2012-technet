---
title: Generate earnings
TOCTitle: Generate earnings
ms:assetid: 8fc44d1e-5a29-4ba8-ac48-15fe1477496c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn876708(v=AX.60)
ms:contentKeyID: 63385350
ms.date: 11/14/2014
mtps_version: v=AX.60
f1_keywords:
- payroll
- Classes.PayrollEarningStatementGeneration
- earnings statement
- earnings
- earning statement
- earning statements
- earnings statements
- payroll earnings
- Classes.PayrollPremiumEarningGeneration
- Classes.PayrollRetroactiveEarningGeneration
- Forms.PayrollEarningStatementRetroactiveLines
- payroll premiums
- premium earnings
---

# Generate earnings 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic describes the different ways that you can generate earnings for workers. You can automatically generate earnings for salaried positions, for positions that use a schedule, and for recurring earnings, premium earnings, and retroactive earnings. You can also enter earnings manually.

When you automatically generate earnings, we recommend that you use the batch processing mode to improve performance.

You must manually enter some earnings, such as sick time and paid time off. You can enter these earnings either before or after you use the automated process to generate the standard earning lines. If you use the automated process first, you must add and remove earning lines manually until the earnings statement is correct.


> [!NOTE]
> <P>This topic describes procedures for generating earnings the first time for a worker pay period. If you already generated earnings and you want to change them or take additional action on them, see <A href="work-with-existing-earnings.md">Work with existing earnings</A>.</P>



This illustration shows the steps involved in generating earnings. The numbers correspond to the procedures later in this topic.

![Steps required to generate payroll earnings](images/Dn876708.Payroll_Generate_earnings_all_types(AX.60).gif "Steps required to generate payroll earnings")

## This task is part of a bigger process

This illustration shows how this topic fits into the larger picture of payroll processing.

For an overview of the process, see [Processing payroll](processing-payroll.md).

![Basic steps for processing earnings](images/JJ677320.Payroll_Processing_earnings_basics(AX.60).gif "Basic steps for processing earnings")

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
<td><p>Microsoft Dynamics AX 2012 R2 or Microsoft Dynamics AX 2012 R3 Cumulative Update 8</p>
<p>Premium earnings are not available prior to AX 2012 R3 CU8. Retroactive earnings require AX 2012 R3 or the Human resources/Payroll regulatory feature pack July 2014 for AX 2012 R2.</p></td>
</tr>
<tr class="even">
<td><p>Country/region</p></td>
<td><p>(USA) The primary address for the legal entity must be in the following countries/regions: United States</p></td>
</tr>
<tr class="odd">
<td><p>Related configuration tasks</p></td>
<td><p>Before you can generate earnings for a worker, Payroll must be set up. For more information, see <a href="setting-up-payroll-basic-topics.md">Setting up payroll: Basic topics</a> and <a href="setting-up-payroll-advanced-topics.md">Setting up payroll: Advanced topics</a>.</p></td>
</tr>
</tbody>
</table>


## 1\. Automatically generate earnings

Earnings that are generated automatically use settings for the position to identify the pay cycle, legal entity, and whether the earnings will be generated as a salary amount or from a schedule. Recurring earnings that are assigned to a specific worker are automatically generated during this process if they are due in the specified pay period and pay cycle.


> [!NOTE]
> <P>When you generate earnings for workers, you designate only the pay cycle and pay period to use. You don’t specify the type of earning to generate. Recurring earnings, salary, leave, and schedule-based earnings are all created in the same process. Premium earnings, including overtime premiums, and retroactive earnings are created separately.</P>



To automatically generate worker earnings, follow these steps:

1.  Click **Payroll** \> **Periodic** \> **Earnings statement processing** \> **Generate earnings**.
    

    > [!NOTE]
    > <P>To generate earnings from the <STRONG>Workers</STRONG> or <STRONG>Positions</STRONG> form, click the <STRONG>Payroll</STRONG> tab.</P>



2.  Specify the following information for the worker positions to generate earnings for.
    
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
    <td><p><strong>Pay cycle</strong></p></td>
    <td><p>Select the pay cycle.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Pay period</strong></p></td>
    <td><p>Select the pay period. The pay periods that are displayed are available for the pay cycle. The first open pay period is the default pay period, but you can select any open pay period from the list.</p></td>
    </tr>
    </tbody>
    </table>


3.  Click **OK** to generate earning statements. A message is displayed to indicate that the earnings statements were generated successfully.
    

    > [!NOTE]
    > <P>Recurring earnings and the earnings from schedules are created first because salary amounts might be affected by other earnings that are automatically generated.</P>



4.  Close the form. To view the earnings statements that were created or updated, open the **Earnings statements** list page.

5.  Verify that the batch job finished correctly. (Click **Home** \> **Inquiries** \> **Batch jobs** \> **My batch jobs**. Click **Log**, and then inspect the log for any errors that occurred.)

## 2\. Manually enter earnings

To enter earnings that are based on pieces and earnings for exceptions, such as sick time or vacation time, follow these steps:

1.  Click **Payroll** \> **Common** \> **Earnings statements** \> **Earnings statements**.

2.  Select an earnings statement, and then click **Edit**.

3.  Click **Add line**, and then enter this information:
    
      - Modify the earnings date if it isn’t the pay period end date.
    
      - Select the position in which the worker earned the earnings.
    
      - Select the tax region.
    
      - Select the earning code that represents the type of earning. When you select the earning code, the default description, quantity, unit type, and rate come from the earning code. You can enter a quantity that is appropriate for the unit type. You can also change the rate, as long as it is a flat rate and isn’t calculated by the system.

4.  If you did not generate earnings by using the automated process before you began manually entering lines, you can click **Earnings statement lines** to use the default values on the rest of the lines of the worker’s earning statement without affecting the lines that you entered manually. You can also automatically generate earnings statements by using the process that is described earlier in this topic with affecting the lines that you added manually.
    

    > [!NOTE]
    > <P>This step can be performed regardless of whether the worker is paid a salary or paid hourly.</P>



5.  Close the form to save the earnings statement.

## 3\. If required: Generate premium earnings

You can manually enter premium earnings or you can generate them by using an automated process. When you use the automated process, the system adds premium lines to existing pay statements that have the selected pay cycle. The premium earnings generation process does not create new earnings statements.

If a worker should receive a premium for a pay period in which they have no other earnings, manually create an earnings statement for that worker, and then generate the premium earnings.

To generate premium earnings for workers, follow these steps:

1.  Determine whether there are dependencies between any premiums that you offer. For example, if you offer a premium that is paid in addition to a shift differential, the earnings for the shift differential must already be on the earnings statement before the additional premium can be calculated.

2.  Click **Payroll \> Periodic \> Earnings statement processing \> Generate premium earnings**.
    

    > [!NOTE]
    > <P>You can generate premium earnings for a single worker from the worker’s earnings statement, but not from the <STRONG>Workers</STRONG> or <STRONG>Positions</STRONG> form.</P>



3.  Specify this information for the worker positions to generate premium earnings for.
    
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
    <td><p><strong>Pay cycle</strong></p></td>
    <td><p>Select the pay cycle.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Pay period</strong></p></td>
    <td><p>Select the pay period. The pay periods that are displayed are available for the pay cycle. The first open pay period is the default pay period, but you can select any open pay period from the list.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Replace premium earnings</strong></p></td>
    <td><p>Select this check box if you have to replace existing premium earning lines. When you select this check box, you frequently will also select the <strong>Generate earnings for specified codes only</strong> option.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Generate</strong></p></td>
    <td><p>Select from the following options:</p>
    <ul>
    <li><p><strong>Generate earnings for all premium codes</strong> – Select this option if there are no dependencies between premium codes.</p></li>
    <li><p><strong>Generate earnings for specified codes only</strong> – Select this option if there are dependencies between premium codes, and then select the premium codes to generate earnings for.</p></li>
    </ul></td>
    </tr>
    </tbody>
    </table>


4.  Click **OK** to generate premium earnings for all earnings statements. A message is displayed to indicate that the premium earnings were generated successfully.

5.  If required: Repeat this task to generate premiums for additional premium codes.

6.  Close the form. To view the earnings statements that were updated, open the **Earnings statements** list page.

7.  Verify that the batch job finished correctly. (Click **Home** \> **Inquiries** \> **Batch jobs** \> **My batch jobs**. Click **Log**, and then inspect the log for any errors that occurred.)

## 4\. If required: Manually add overtime premiums

To create overtime premiums, manually add earning lines that have a rate basis of **Regular rate of pay**. For example, a worker worked 48 hours in a work period, so their earnings statement includes 48 hours at the regular rate. You add a line that uses the earning code that you created for overtime premiums. The line calculates the full overtime premium by using the multiplier on the earning code to determine the worker's regular earnings plus any adjustments that are required by the Fair Labor Standards Act (FLSA).


> [!IMPORTANT]
> <P>To make sure that the calculations are correct, you must enter overtime lines after all other earnings for the pay period have been entered. If you change any earning on the earnings statement, delete and re-create the overtime premium lines.</P>



To add overtime premiums for workers, follow these steps:

1.  Click **Payroll** \> **Common** \> **Earnings statements** \> **Earnings statements**.

2.  Select an earnings statement, and then click **Edit**.

3.  Click **Add line**, and then enter this information:
    
      - Change the earnings date if it isn’t in the work period that the overtime line applies to.
    
      - Select the position in which the worker earned the earnings.
    
      - Select the tax region.
    
      - Select the earning code for the overtime premium. When you select the earning code, the default description, quantity, unit type, and rate come from the earning code.

4.  Close the form to save the earnings statement.

## 5\. If required: Generate retroactive earnings

When an hourly worker or a worker who is paid by the piece is entitled to back pay, you can automatically calculate the difference between the previous rate of pay and the new rate of pay. This amount appears as retroactive pay on its own earnings statement line, and the original retroactive rate is listed as the source.

You can also calculate retroactive pay for salaried workers. The salary-based earnings statement lines are adjusted to reflect the new rate.


> [!NOTE]
> <P>If you generate earnings from the <STRONG>Payroll</STRONG> tab of the <STRONG>Workers</STRONG> or <STRONG>Positions</STRONG> forms, retroactive earnings are included and a separate process isn’t required.</P>



1.  Click **Payroll \> Periodic \> Earnings statement processing \> Retroactive earnings \> Generate retroactive earnings**.

2.  Enter this information.
    
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
    <td><p><strong>Pay cycle</strong></p></td>
    <td><p>The pay cycle to evaluate for retroactive earnings.</p>
    <p>Only those earnings that were processed in a pay period that is associated with the selected pay cycle are evaluated for retroactive earnings.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Start date</strong></p>
    <p><strong>End date</strong></p></td>
    <td><p>The first and last date in the range of dates to evaluate for retroactive earnings. Pay period start and end dates are ignored by the retroactive calculations.</p>
    <p>All earnings that are by the hour or by the piece that fall within the selected date range are evaluated to determine whether retroactive earnings should be generated.</p>
    <p>For salary-based earnings, the start date must be the first date of a pay period, and the end date must be the last day of a pay period. Retroactive pay calculations that affect part of a pay period might not be accurate.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Accounting date</strong></p></td>
    <td><p>The accounting date that is assigned to the retroactive earning lines.</p></td>
    </tr>
    </tbody>
    </table>


3.  Click **OK** to generate retroactive earnings and add them to earning statements. A message is displayed to indicate the number of earnings statements that were updated.

4.  Close the form. To view the earnings statements that were updated, open the **Earnings statements** list page. For earnings that are based on hours or pieces, the retroactive earnings appear on a separate line, together with the retroactive earning code. For salary-based earnings, the amounts have been adjusted, but don’t appear on separate lines.
    
    You can view all of the retroactive earnings that you generated on the **Review retroactive earnings lines** form. Click **Payroll \> Periodic \> Retroactive earnings \> Review retroactive earning lines.**

5.  Verify that the batch job finished correctly. (Click **Home** \> **Inquiries** \> **Batch jobs** \> **My batch jobs**. Click **Log**, and then inspect the log for any errors that occurred.)

## Next step

After you generate earnings, you must release them before you create pay statements. You might also have to change the earnings or place certain earnings on hold. For more information, see [Work with existing earnings](work-with-existing-earnings.md).

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

> [!IMPORTANT]
> <P>When you use Payroll, we highly recommend that you turn off the <STRONG>Payroll information</STRONG> configuration key under the <STRONG>Human resource I</STRONG> configuration key. The forms and tables that are enabled by that configuration key are not used by Payroll. If Payroll is installed and the configuration key is enabled, it might be difficult to make sure that your data is entered and tracked correctly.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Security roles and duties</strong></p></td>
<td><p>To generate earnings, you must be a member of a security role that includes this duty:</p>
<ul>
<li><p>Maintain earning entry (PayrollEarningStatementGenerationMaint)</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To generate earnings, you must be a member of a security role that includes these privileges:</p>
<ul>
<li><p>PayrollEarningGenerationProcess</p></li>
<li><p>PayrollEarningMaintain</p></li>
<li><p>PayrollEarningsImportServiceCreate</p></li>
<li><p>PayrollEarningsMaintain</p></li>
</ul></td>
</tr>
</tbody>
</table>


## See also

[Work with existing earnings](work-with-existing-earnings.md)

[Work with pay statements](work-with-pay-statements.md)

[Issue worker payments](issue-worker-payments.md)

[Post payroll and generate vendor invoices](post-payroll-and-generate-vendor-invoices.md)

[Work with existing payroll payments](work-with-existing-payroll-payments.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

