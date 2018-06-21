---
title: Pay statements and the payment generation process
TOCTitle: Pay statements and the payment generation process
ms:assetid: 0248906d-a05a-49e5-ab62-7939b4d773be
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn876700(v=AX.60)
ms:contentKeyID: 63385344
ms.date: 11/14/2014
mtps_version: v=AX.60
f1_keywords:
- payroll
- pay statement
- final payment
- terminated worker
- pay statements
- distributions for earnings
- pay statement line distribution
- payment generation
- terminated employee
---

# Pay statements and the payment generation process [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic answers some questions you might have about how to generate pay statements and worker payments.

This topic describes functionality that is available only if the **Payroll - USA** configuration key is selected.

## How do I record payments that were made outside Payroll?

In some cases, a worker payment is made and taxes are withheld outside the Payroll system. For example, when stock shares for an employee are vested, and a certain number of shares of stock are withheld to cover the taxes, the vesting is a worker payment. Although the event occurs outside payroll, you must record the event and all transactions that are associated with it in Payroll so that statutory reporting and pay statement reporting are accurate.

To record payments that were made outside Payroll, follow these steps:

1.  In [Generate earnings](generate-earnings.md), follow the steps in the “Manually enter worker earnings” section to enter the earnings for payments that were made outside Payroll. On the **Line details** FastTab, select the **Manual** check box.
    

    > [!NOTE]
    > <P>The earning code for these earnings can’t be set up for a fringe benefit or a gross up payment run type. The rate basis must be a flat amount.</P>



2.  In [Work with existing earnings](work-with-existing-earnings.md), follow the steps in the “Release earnings for payment processing” section to release the earnings.

3.  In [Work with pay statements](work-with-pay-statements.md), follow the steps in the “Generate pay statements” section to generate the pay statement.
    
    The payment run type must be **Manual**. If you don’t want to record accounting-related information or post the pay statement to the general ledger, select **Disable accounting**.

4.  In [Work with pay statements](work-with-pay-statements.md), follow the steps in the “Modify pay statements” section to add the tax lines and benefit lines to the pay statement. You can add, remove, or change all tax lines and benefit lines on the pay statement. These include lines that are usually locked, such as Federal Insurance Contributions Act (FICA) lines.
    
    When the pay statement is correct, click **Finalize** in the message bar.

## How do I issue the final payment to a terminated worker?

If you have to issue a payment to a single worker, you generate the earnings statement and the pay statement from the **Payroll** tab on the **Action Pane** of the **Worker** form, instead of using the periodic processes. Consider this information when you issue the final payment to a terminated worker:

  - Verify that you entered earning codes to allow for payment for accrued benefits, if appropriate. Also verify that any premiums, arrearages, tax levies, or garnishments have been handled according your organization’s policies and any applicable laws or regulations.

  - If a worker is paid a salary, when you try to adjust the earning statements lines on the final earnings statement, the values are automatically adjusted so that the worker still receives the expected amount for the pay period. To override this, turn off the **Calculate Salary** functionality in the **Earnings statement** form.

## Why are the benefit lines and amounts on a pay statement different from what I expect?


> [!WARNING]
> <P>If arrearages were created when the pay statement was generated, the arrearage amounts are displayed in the <STRONG>Arrears</STRONG> FactBox. The arrearages might cause the pay statement benefit lines to differ from the lines and amounts that you expect.</P>
> <P>If a benefit line seems to be missing, it might have been removed when the benefit was calculated because the pay wasn’t sufficient to cover the amount.</P>
> <P>Likewise, if a benefit line or amount unexpectedly appears on the pay statement, it might have been added to recover arrears from previous pay statements. There is no indication on the pay statement itself that an arrearage amount has been recovered. Use the <STRONG>Worker arrears</STRONG> form to determine whether arrears were recovered on the pay statement.</P>



## Can I change the distributions for a pay statement line?

No. However, you can change distributions for earnings from the earnings statement line. For more information, see [Earnings and the earnings generation process](earnings-and-the-earnings-generation-process.md).

## Can I create a pay statement with zero earnings?

Yes. For example, if you simply need to create a pay statement so that you can correct benefit and tax contributions or deductions, you can manually create a pay statement.

### Manually create a pay statement with zero earnings

1.  Click **Payroll** \> **Common** \> **Pay statements** \> **All pay statements**.

2.  Click **Pay statements**.

3.  Select the pay cycle, pay period, and payment date for the pay statement.

4.  Select the worker to update benefit and tax deductions or contributions for.

5.  Click **OK**.

6.  Click the **Benefit calculations** link and add benefit deduction or contribution lines for the worker.

7.  Click the **Tax calculations** link and add tax deduction or contribution lines for the worker.

8.  In the message bar, click **Calculate**.
    

    > [!IMPORTANT]
    > <P>You must calculate the pay statement before you can submit it for payment or post it to the general ledger.</P>



## Don't see your question here?

We're working to include as many questions as we can, so that Microsoft Dynamics AX Help will be more useful to people just like you.

Tell us what question you would like to add to this topic. Send email to <adocs@microsoft.com>.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

