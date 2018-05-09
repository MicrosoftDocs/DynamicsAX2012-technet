---
title: (RUS) Set up calculation sequences and counters
TOCTitle: (RUS) Set up calculation sequences and counters
ms:assetid: 36be22ba-236f-4b14-99f3-b9bc4c92bad8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ665279(v=AX.60)
ms:contentKeyID: 49387368
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- calculation
- counters
- sequences
- (RUS)
- Russia
---

# (RUS) Set up calculation sequences and counters 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Standard expenses sequence** and **Counter setup** forms to create calculation sequences that are used to create deferrals for vendor invoices. For more information, see [(RUS) Standard expenses sequence (form)](https://technet.microsoft.com/en-us/library/jj853198\(v=ax.60\))

Before you can set up the calculation sequence and counters, you must set up expense codes in the **Expense and income codes** form.

In the **Counter setup** form, you must select an expense code. When you generate deferrals by using the periodic process, the expense code that is specified for a counter is used to generate deferrals for vendor invoices that have the same expense code.

1.  Click **General ledger** \> **Setup** \> **Deferrals** \> **Sequence of calculation**.

2.  Create a new calculation sequence. For more information, see [(RUS) Set up calculation sequences, counters, and deferred expense write-off factors](rus-set-up-calculation-sequences-counters-and-deferred-expense-write-off-factors.md).

3.  In the **Sequence** and **Description** fields, enter a unique number and a description for the sequence.

4.  In the **Channel** field, select **Deferral**.

5.  In the **Channel reference** field, select the deferrals group.

6.  Click **Counters**.

7.  Create a new counter.

## See also

[(RUS) Set up a deferrals model](rus-set-up-a-deferrals-model.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

