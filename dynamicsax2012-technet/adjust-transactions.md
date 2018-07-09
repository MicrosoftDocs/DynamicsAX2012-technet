---
title: Adjust transactions
TOCTitle: Adjust transactions
ms:assetid: 1aa36eb3-725d-4ede-8fef-4a881ef2f049
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa569923(v=AX.60)
ms:contentKeyID: 36056124
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- adjust transaction
- adjustment history
- adjustment transaction
- transaction adjustment
---

# Adjust transactions [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can adjust project transactions in Microsoft Dynamics AX one at a time, or select from a list of all project transactions.

If you want to make changes to only part of a transaction, you can split the transaction into lines. The total amount for the lines must equal the amount in the original transaction.

## Example of an adjustment transaction split into two lines

Previously, you posted 25 hours on a project. Now you need to correct the number to 15 hours, and you must invoice those 15 hours to the customer.

First, split the transaction into two adjustment lines, one for 15 hours and the other for 10 hours. Next, change the line property of the 10-hour entry to non-chargeable. Finally, post the two new adjusted lines.

## Adjust transactions in single or multiple projects

1.  Click **Project management and accounting** \> **Periodic** \> **Transactions** \> **Adjust transactions**.
    
    –or–
    
    If you want to adjust transactions in a single project:
    
    1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**.
    
    2.  Select the project with the transaction or transactions to be adjusted.
    
    3.  On the **Manage** tab, in the **Process** group, click **New adjustment**.

2.  In the **Adjustment** form, click **Select**.

3.  In the **Create adjustment transactions** form, select the parameters by which you want to filter transactions, and then click **OK**.

4.  In the **Adjustment** form, select one or more transactions to be adjusted, and then click **Adjust**.

5.  In the **Adjust transactions** form, in the **Split in number of lines** field, enter the number of new adjustment lines that you want to create.
    

    > [!NOTE]
    > <P>If you enter “1,” the transaction is adjusted as a whole. If you enter “2” or greater, the transaction is split into even quantities that can be adjusted individually. If the transaction consists of an uneven number of hours, the odd hour is added to the last quantity.</P>



6.  In the **New value for selected lines** area, specify any changes that you want to make to the assigned project, activity, category, or line property for these adjustments.

7.  In the **Field update** area, clear the check boxes of the values that you do not want to appear in the new transactions, and then click **OK**.

8.  In the lower pane in the **Adjustment** form, make any additional changes that you want to make to the new lines.

9.  Click **Check** to ensure there are no problems with the adjustment lines, and then click **Post**.


> [!WARNING]
> <P>Any adjustment lines for which you do not click <STRONG>Post</STRONG> are deleted when you close the <STRONG>Adjustment</STRONG> form.</P>



## See also

[About automatic adjustment transactions](about-automatic-adjustment-transactions.md)

[Adjust transactions (class form) (Project)](https://technet.microsoft.com/en-us/library/aa583326\(v=ax.60\))

[Adjust transactions in projects](adjust-transactions-in-projects.md)

[Adjustments (form)](https://technet.microsoft.com/en-us/library/aa553205\(v=ax.60\))

[Create adjustment transactions (class form)](https://technet.microsoft.com/en-us/library/aa634561\(v=ax.60\))

[View and record transactions](view-and-record-transactions.md)

[View transaction adjustment history](view-transaction-adjustment-history.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

