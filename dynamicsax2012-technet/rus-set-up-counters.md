---
title: (RUS) Set up counters
TOCTitle: (RUS) Set up counters
ms:assetid: fc564312-feb2-4447-aade-2ae83d53b441
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678659(v=AX.60)
ms:contentKeyID: 49388141
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up counters 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **General ledger** \> **Setup** \> **Profit tax** \> **Counters**.

2.  In the upper pane, press CTRL+N to create a new line.

3.  In the **Sequence** field, enter the sequence code for which the counter is being configured.

4.  In the **Description** field, enter a description of the calculation sequence.

5.  In the **Expense code** field, select the expense code for which the calculation will be performed.

6.  In the **Description** field, enter a description of the counter.

7.  In the lower pane, press CTRL+N to create a new line to set up the calculation algorithms.

8.  In the **Operator** field, select the mathematical and logical operators for the calculation sequence.

9.  In the **Line type** field, select the line type.

10. In the **From** and **To** fields, select the range of directory values.

11. In the **Period type** field, select the reporting period for the calculation.

12. In the **Index** field, enter the index of the period, such as **0** = current period, **1** = next period, **-1** = previous period, and so on.

13. In the **Register field** field, select the register field.
    

    > [!NOTE]
    > <P>This field displays the calculated result in the <STRONG>Register Lines</STRONG> form if the register value is selected in the <STRONG>Line type</STRONG> field.</P>



14. In the **Note** field, enter any additional information needed to describe the counters.

15. Click **Copy counter** to open the **Copy aisle** form to create new counters by copying existing ones.

16. Under the **Copy from** field group, in the **Sequence** and **Expense code** fields, select the sequence code and expense code from which you want to copy the settings.

17. Under the **Copy to** field group, in the **Sequence** and **Expense code** fields, select the sequence code and expense code into which you want to copy the settings.

18. Click **OK** to return to the **Counter setup** form.

19. Press CTRL+S or close the form.

## See also

[(RUS) Counter setup (form)](https://technet.microsoft.com/en-us/library/jj856173\(v=ax.60\))

[(RUS) Standard expenses sequence (form)](https://technet.microsoft.com/en-us/library/jj853198\(v=ax.60\))

[(RUS) Copy aisle (form)](https://technet.microsoft.com/en-us/library/jj711606\(v=ax.60\))

[(RUS) Set up calculation sequences, counters, and deferred expense write-off factors](rus-set-up-calculation-sequences-counters-and-deferred-expense-write-off-factors.md)

  


