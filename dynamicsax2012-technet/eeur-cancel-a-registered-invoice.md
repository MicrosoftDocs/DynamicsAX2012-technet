---
title: (EEUR) Cancel a registered invoice
TOCTitle: (EEUR) Cancel a registered invoice
ms:assetid: a955b5bc-c8b0-48f2-9094-3bac5a7bb2cf
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ730996(v=AX.60)
ms:contentKeyID: 49675238
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (EEUR) Cancel a registered invoice [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to cancel a registered invoice in Accounts payable. Registered invoices are entered in journals, which require approval by another employee before they can be posted.

1.  Click **General ledger** \> **Setup** \> **General ledger parameters**. In the **Ledger** area, on the **Accounting rules** FastTab, select the **Correction** check box so that transactions that have negative amounts can be posted as corrections in the general ledger.
    
    After you complete this step, the voucher transactions that are created by canceling the journal follow the storno accounting principle.

2.  Click **Accounts payable** \> **Journals** \> **Invoices** \> **Invoice approval journal**.

3.  Click **New**, and then select the name of the journal that your organization uses for invoice approval journals.

4.  Enter any additional information, and then click **Lines**.

5.  In the **Journal voucher** form, click **Find vouchers**.

6.  In the **Find vouchers** form, select the voucher for the registered invoice that you want to cancel, and then click **Select**. Click **OK**.

7.  In the **Journal voucher** form, click **Functions** \> **Cancel**.

8.  Click **Post** \> **Post**.

## See also

[Journal voucher - Invoice approval journal (form)](https://technet.microsoft.com/en-us/library/aa498954\(v=ax.60\))

[(POL) Journal voucher - Invoice approval journal (modified form)](https://technet.microsoft.com/en-us/library/jj678203\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

