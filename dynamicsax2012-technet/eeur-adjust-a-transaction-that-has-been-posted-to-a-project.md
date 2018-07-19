---
title: (EEUR) Adjust a transaction that has been posted to a project
TOCTitle: (EEUR) Adjust a transaction that has been posted to a project
ms:assetid: 2d5c647a-94bc-4484-a12e-fe20a925731d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ683247(v=AX.60)
ms:contentKeyID: 49685129
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Czech Republic, Estonia, Hungary, Latvia, Lithuania, Poland, Russia
---

# (EEUR) Adjust a transaction that has been posted to a project 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to adjust a project transaction as a whole or in part. Project adjustment transactions can be posted as corrections in the general ledger.

**Prerequisite**

Before you can complete the procedures in this topic, you must take the following steps:

1.  Click **General ledger** \> **Setup** \> **General ledger parameters**. In the **Ledger** area, on the **Accounting rules** FastTab, select the **Correction** check box so that adjustment transactions can be posted as corrections in the general ledger.

2.  Click **Project management and accounting** \> **Setup** \> **Project management and accounting parameters**. In the **General** area, in the **Adjustment** field group, select the **Adjustment of project transactions - correction** check box to set the default for the **Adjust transactions** form.

## Adjust a transaction that has been posted to a project

1.  Click **Project management and accounting** \> **Periodic** \> **Transactions** \> **Adjust transactions**.

2.  In the **Adjustments** form, click **Select**.

3.  In the **Select transactions for adjustment** form, select the criteria for the transactions that you want to adjust. To refine the selection criteria, click **Select**.

4.  In the **Proj Adjustment Select** form, select a query, enter the selection criteria, and then click **OK**.
    
    For more information about how to use queries to select records, see [Inquiry (form)](https://technet.microsoft.com/en-us/library/aa575929\(v=ax.60\)). For example, you can use a query to select transactions for a specific project contract or project.

5.  In the **Select transactions for adjustment** form, click **OK**.

6.  In the **Adjustments** form, in the upper pane, select the transactions to be adjusted.

7.  Click **Adjust**, and then, in the **Adjust transactions** form, adjust the selected transactions. Click **OK** to close the form.
    
    By default, the **Adjustment of project transactions - correction** check box is selected, but you can clear it.

8.  In the **Adjustments** form, in the lower pane, review the effect of the adjustment, and then click **Check** to validate the changes.

9.  If no errors appear, click **Post** to post the adjusted line.

## See also

[Create adjustment transactions (class form)](https://technet.microsoft.com/en-us/library/aa634561\(v=ax.60\))

[Adjust transactions (class form) (Project)](https://technet.microsoft.com/en-us/library/aa583326\(v=ax.60\))

[Adjust transactions](adjust-transactions.md)

[Adjustments (form)](https://technet.microsoft.com/en-us/library/aa553205\(v=ax.60\))

[(EEUR) Project management and accounting parameters (modified form)](https://technet.microsoft.com/en-us/library/jj710688\(v=ax.60\))

  


