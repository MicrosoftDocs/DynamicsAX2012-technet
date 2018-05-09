---
title: Work with existing earnings
TOCTitle: Work with existing earnings
ms:assetid: f243de0f-005e-4beb-a299-2f25fa5ba1a8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn876710(v=AX.60)
ms:contentKeyID: 63385357
ms.date: 11/14/2014
mtps_version: v=AX.60
f1_keywords:
- payroll
- Classes.PayrollEarningReleaseForPayment
- earnings statement
- earnings
- earning statement
- earning statements
- earnings statements
- premium earnings
- existing earnings
---

# Work with existing earnings 


This topic describes tasks, such as releasing or holding earnings, that you can complete after you generate an earnings statement. You must release earning statement lines before you generate pay statements.

Retroactive earnings aren’t discussed in this topic. For information about retroactive earnings, see [Generate earnings](generate-earnings.md).

## This task is part of a bigger process

This illustration shows where releasing earnings fits into the larger picture of payroll processing. Other tasks that are described in this topic are not part of the end-to-end payroll process.

For an overview of the process see [Processing payroll](processing-payroll.md)

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
<td><p>Task</p></td>
<td><p><a href="generate-earnings.md">Generate earnings</a></p></td>
</tr>
<tr class="even">
<td><p>Version</p></td>
<td><p>Microsoft Dynamics AX 2012 R2 or Microsoft Dynamics AX 2012 R3 Cumulative Update 8</p></td>
</tr>
<tr class="odd">
<td><p>Country/region</p></td>
<td><p>(USA) The primary address for the legal entity must be in the following countries/regions: United States</p></td>
</tr>
</tbody>
</table>


## If required: Hold earnings from payment processing

You can put one or more earning statement lines on hold so that you can change information or correct errors, as long as the line isn’t included on a pay statement.

You can complete these steps, regardless of whether some or all of the earning statement lines are released.

To put earning lines on hold, follow these steps:

1.  Click **Payroll** \> **Common** \> **Earnings statements** \> **Earnings statements**.

2.  Complete one of these tasks:
    
      - To put all the lines for an earnings statement on hold, select one or more earnings statements, and then click **Hold earnings statement**. The payment status is set to **On hold** so that the lines won’t be included on any pay statements until you release the lines for processing.
    
      - To put individual lines on hold so that the rest of the earnings statement can be processed, open the earnings statement, select the lines to put on hold, and then click **Hold lines for payment**.

## Release earnings for payment processing

Follow these steps to change the status of all earnings statement lines from **None** to **Released**. You must release earning statement lines before you generate pay statements.

If an earnings statement line is on hold, this process releases the line only if you select the **Release lines on hold** check box.

To release earning statement lines, follow these steps:

1.  Click **Payroll** \> **Common** \> **Earnings statements** \> **Earnings statements**.

2.  Select **Release earnings statement**.

3.  In the **Pay cycle** field, select the pay cycle of the worker positions to process.

4.  In the **Pay period** field, select the pay period for the worker position earnings. The pay periods that are displayed are available for the pay cycle. The default pay period is the first open pay period, but you can select any open pay period from the list.

5.  Optional: Select the **Release lines on hold** check box to release any lines that are on hold on the earnings statements.

6.  Click **OK** to change all the earnings statement lines that have a payment status of **None** to **Released**, so that they can be processed.
    

    > [!NOTE]
    > <P>When you release an earnings statement line for an accrued benefit, such as sick time or vacation time, the number of hours on the line is verified against the minimum balance that is required by the benefit accrual plan. If the balance includes fewer hours than the number of hours on the line, the line isn’t released.</P>
    > <P>For more information, see <A href="benefit-accrual-plan-tasks.md">Benefit accrual plan tasks</A> or <A href="https://technet.microsoft.com/en-us/library/jj677450(v=ax.60)">Benefit accrual balances (form)</A>.</P>



## If required: Change earnings statements

After you generate an earnings statement, you can add lines to it and change existing lines, as long as they haven’t been released or processed.

You can delete released lines, but not processed lines.


> [!IMPORTANT]
> <P>There are two ways to change earnings statement lines that were included on a pay statement. If you can delete the pay statement, do so, put the earning statement lines on hold, and then change the lines. If you can’t delete the pay statement because of its status, enter a new earnings statement line to offset the original line, and then create a new, correct line. You will process the new line that offsets the original line in a subsequent pay statement. For more information, see <A href="work-with-pay-statements.md">Work with pay statements</A>.</P>



1.  Click **Payroll** \> **Common** \> **Earnings statements** \> **Earnings statements**.

2.  Select the earnings statement to change.

3.  Make any changes. Keep in mind these special circumstances:
    
      - Salaried workers – If you change or add a line for a salaried worker, lines that have a source of **Salary** are calculated and re-created unless you click **Calculate Salary**. This helps make sure that a salaried worker does not receive more or less than their typical amount for the pay period. We recommend that you don’t turn off the **Calculate Salary** functionality unless you are terminating a worker’s employment.
    
      - Overtime premiums – Earnings statement lines that have a rate basis of **Regular rate of pay** are used to create overtime premiums. These lines are calculated based on all other earnings statement lines for nondiscretionary earnings. Therefore, after you change any earnings statement line, you must delete any lines that have a rate basis of **Regular rate of pay**, and then add those lines again. Otherwise, the **Regular rate of pay** lines might not be correct.
    
      - Retroactive earnings – You can change retroactive earning lines, but you can’t change the original retroactive rate that the earning statement line originated from.
        
        For more information, see [Earning code and earning code group tasks](earning-code-and-earning-code-group-tasks.md).

## Next step

After you finalize all the earnings, you’re ready to generate pay statements. For more information, see [Work with pay statements](work-with-pay-statements.md).

## Related tasks

[Earnings and the earnings generation process](earnings-and-the-earnings-generation-process.md)

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
<td><p>To work with existing earnings, you must be a member of a security role that includes this duty:</p>
<ul>
<li><p>Maintain earning entry (PayrollEarningStatementGenerationMaint)</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To issue payments to workers, you must be a member of a security role that includes these privileges:</p>
<ul>
<li><p>Generate earnings (PayrollEarningGenerationProcess)</p></li>
<li><p>Maintain payroll earnings (PayrollEarningMaintain)</p></li>
<li><p>Earnings import service operation (PayrollEarningsImportServiceCreate)</p></li>
<li><p>Maintain payroll earnings (PayrollEarningsMaintain)</p></li>
</ul></td>
</tr>
</tbody>
</table>


## See also

[Processing payroll](processing-payroll.md)

[Generate earnings](generate-earnings.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

