---
title: (BRA) Cancel a project invoice
TOCTitle: (BRA) Cancel a project invoice
ms:assetid: 43120756-2256-47ea-8033-6a1347043f34
ms:mtpsurl: https://technet.microsoft.com/library/JJ851018(v=AX.60)
ms:contentKeyID: 50041973
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Brazil
---

# (BRA) Cancel a project invoice 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can cancel a customer invoice for a project. When you cancel a project invoice, a negative project invoice is created. When you post the negative project invoice, the original and negative project invoices are marked as canceled, and all the ledger and financial transactions are reversed. The original transaction is reported in the fiscal books as canceled, and the negative transaction is not reported in the fiscal books.

You cannot cancel a project invoice that is partially or fully settled. Also, you cannot cancel a project invoice if the posting date of the invoice is in a fiscal period that is closed.

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**. On the **All projects** list page, select a project for which to cancel an invoice. On the **Action Pane**, on the **Manage** tab, in the **Bill** group, click **Invoice journals**.
    
    –or–
    
    Click **Project management and accounting** \> **Common** \> **Projects** \> **Project contracts**. On the **Project contracts** list page, select a project contract for which to cancel an invoice. On the **Action Pane**, on the **Maintain** tab, in the **Bill** group, click **Invoice journals**.

2.  In the **Invoice journals** form, select an invoice for cancellation, and then click **Invoice cancellation**. In the **Cancel posted invoice** form, click **Yes**.

3.  In the **Invoice cancellation** form, in the **Reason code** field, select a reason for canceling the project invoice. For more information about how to create reason codes, see [Set up reason codes for financial modules](set-up-reason-codes-for-financial-modules.md).

4.  Optional: Enter a comment about the cancelation.

5.  In the **Canceling invoice date** field, select a date on which to post the cancelation. The date is required to complete the cancelation.

6.  Click **Cancel project invoice**.

A message is displayed to confirm the cancelation.

## See also

[(BRA) Cancel project invoice (form)](https://technet.microsoft.com/library/jj710496\(v=ax.60\))

[Reasons (form)](https://technet.microsoft.com/library/hh209362\(v=ax.60\))

  


