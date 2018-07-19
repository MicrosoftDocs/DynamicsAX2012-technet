---
title: Earnings and the earnings generation process
TOCTitle: Earnings and the earnings generation process
ms:assetid: fe4c112d-17a0-47fa-be7a-0f7663223da4
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn876711(v=AX.60)
ms:contentKeyID: 63385356
ms.date: 11/14/2014
mtps_version: v=AX.60
f1_keywords:
- payroll
- earnings statement
- earnings
- earning statement
- earning statements
- earnings statements
- payroll earnings
audience: Application User
ms.search.region: USA
---

# Earnings and the earnings generation process 


This topic answers some questions you might have about earnings and generating earnings.

This topic describes functionality that is available only if the **Payroll - USA** configuration key is selected.

## Can I change the distributions for an earning line?

Yes. Select the line, and then click **Distribute earnings** to view and change the distributions.

The default main account and dimensions for earning lines are based on the accounting rule for the earning and the default dimensions and dimension templates that are defined for the earning code or the position.

Distributions for earnings must be changed from the earning statement line. After the earnings are processed, the distributions cannot be changed on the pay statement.

## What are recurring earnings?

Recurring earnings are earnings that are assigned to workers and that occur regularly. Some examples are a monthly car allowance or a uniform allowance that is based on the pay period amount and is earned each pay period. Recurring earnings are generated automatically when earnings are generated. These are some important points to note about recurring earnings:

  - Worker payroll earning codes that have a frequency specified are generated if the frequency is in the pay period that you’re generating earnings for.
    
    Only earning codes that have **Each** assigned as the unit of measure require a frequency.

  - The fixed compensation plan is determined by the combination of worker, position, and legal entity. The plan provides the fixed compensation rate, which is used in the formula that determines the earning amount.
    
    If the earning is a flat amount, fixed compensation plans aren’t used.

  - If a recurring earning is generated, the source of the earning line is set to **Recurring** in the **Earnings statement** form.

  - If a recurring earnings statement line is generated that is identical to one that you entered manually, both lines will exist, but the source will differ. The manually entered line will have a source of **User entry**, and the system-calculated source will be **Recurring** in the earning statement line detail.

## How are earnings calculated for salaries?

Salary earnings are generated automatically during the generation process that is described earlier in this topic. These are some important points to note about salary earnings:

  - Positions that are identified as salaried positions should receive a base earning amount regardless of whether they have earnings that have been manually entered. For example, if you enter eight hours of sick time, the earning statement lines are adjusted so that a worker receives no more and no less than the salary amount that is authorized for their position.

  - Recurring earnings and the earnings from schedules are created first because salary amounts might be affected by other earnings that are automatically generated if these other earnings are considered base salary components.
    

    > [!NOTE]
    > <P>If you manually enter earning lines after you generate earnings, the earning lines that were previously generated are recalculated so that the worker pay is accurate. If you don’t want the earning lines to be recalculated so that the salary amounts are correct, you can click <STRONG>Calculate Salary</STRONG> on the earnings statement to keep the line values unchanged. You typically do this only if you’re terminating a worker’s employment.</P>



## How do I generate earnings for a salaried worker who is on leave?

To generate earnings for leave, you must assign a schedule to the position that the worker is taking leave from, even if it is a salaried position. For more information, see [Work schedule and leave tasks](work-schedule-and-leave-tasks.md).

If an earning code is assigned to the leave type, then the scheduled lines will use the earning code from the leave type instead of the one from the schedule. The earning code that is on the leave type can be configured as paid or unpaid based on the amount or multiplier, which would be zero for unpaid leave. If no earning code is assigned to the leave type, then no lines will be created from the schedule or leave for the days on leave. For more information, see [Leave types (form)](https://technet.microsoft.com/en-us/library/aa619619\(v=ax.60\)).

## Can a salaried worker receive retroactive earnings?

Yes. However, when you use the retroactive earning generation process to change the compensation for a salaried position, you must make all compensation rate changes effective at the start of the pay period. If you have to change the compensation during a pay period, you must manually calculate the retroactive adjustment for the pay period in which the change took effect.

## Why didn’t the selection criteria return any results?

When you generate earnings, you might receive this message: “The selection criteria did not return any results.” If you expected earnings to be generated, these actions might be causing the lack of results:

  - Earnings for the selection were already generated.

  - You selected a pay cycle that does not match the pay cycle that is specified on the **Payroll** FastTab of the **Position** form for the worker.

  - You selected a pay period during which the worker wasn’t assigned to a position.

  - You are logged on to a legal entity that does not match the **Paid by** field that was in effect for the position at the end of the pay period.

  - You haven’t selected the **Generate salary** or **Generate earnings from schedule** options in the **Position** form and there aren’t any recurring earning codes to generate for any workers.

  - You selected a pay period that has the wrong year. For example, you selected January 1, 2013 through January 15, 2013, but you meant to select January 1, 2014 through January 15, 2014.


> [!IMPORTANT]
> <P>The fields on the <STRONG>Payroll</STRONG> FastTab in the <STRONG>Position</STRONG> form have their own date-effective settings. To view these, open the <STRONG>Maintain versions</STRONG> form from the <STRONG>Payroll</STRONG> FastTab.</P>



## Don't see your question here?

We're working to include as many questions as we can, so that Microsoft Dynamics AX Help will be more useful to people just like you.

Tell us what question you would like to add to this topic. Send email to <adocs@microsoft.com>.

  


