---
title: Specify when a bank account is active or inactive
TOCTitle: Specify when a bank account is active or inactive
ms:assetid: 13009da8-c44c-4c9c-9e5f-cada126b1ea7
ms:mtpsurl: https://technet.microsoft.com/library/Hh242142(v=AX.60)
ms:contentKeyID: 36056043
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- active
- bank
- deactivate
- inactivate
- inactive
audience: Application User
ms.search.region: Global
---

# Specify when a bank account is active or inactive 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Follow the steps in these procedures to specify when a bank account is active or inactive for transactions. When a bank is inactive for all transactions, no transactions are permitted for that bank.

## Specify when a bank account is active for all transactions

By default, bank accounts are active. Follow these steps to activate an inactive bank account. If your organization requires a bank account to be active on a specific date, or to remain active for a limited time, you can specify a date or date range when the bank account is active.

1.  Click **Cash and bank management** \> **Common** \> **Bank accounts**.

2.  Select the bank account that you want to update, and then click the **Edit** button on the **Action Pane**.

3.  On the **General** FastTab, in the **Bank account status** field, select **Active for all transactions**.

4.  If you want the bank account to be active only for a limited time, enter the date range in the **Active from** and **Active to** fields.
    

    > [!NOTE]
    > <P>If you do not enter a date in the <STRONG>Active from</STRONG> field, the bank account immediately becomes active for new transactions when you select <STRONG>Active for all transactions</STRONG> in the <STRONG>Bank account status</STRONG> field. If you do not enter a date in the <STRONG>Active to</STRONG> field, the bank account will remain active indefinitely.</P>



## Inactivate a bank account for all or only new transactions

Follow these steps to inactivate a bank account for all or only new transactions. If you inactivate a bank account for only new transactions, existing transactions that have not yet been completed, such as pending payments, will still occur as they were originally scheduled.

1.  Click **Cash and bank management** \> **Common** \> **Bank accounts**.

2.  Select the bank account that you want to update, and then click the **Edit** button on the **Action Pane**.

3.  Click the **General** FastTab.

4.  To inactivate the bank account for all transactions, select **Inactive for all transactions** in the **Bank account status** field.
    
    –or–
    
    To inactivate the bank account for only new transactions, select **Inactive for new transactions** in the **Bank account status** field.

## See also

[Bank accounts (form)](https://technet.microsoft.com/library/aa587660\(v=ax.60\))

  


