---
title: Create an aging snapshot
TOCTitle: Create an aging snapshot
ms:assetid: b85e770b-7548-499e-8728-c0512f6eae0f
ms:mtpsurl: https://technet.microsoft.com/library/Hh242759(v=AX.60)
ms:contentKeyID: 36059110
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- balances
- aging
- period
- periods
- aged
- buckets
- trial balance
- customer balance
- past due
- trial
audience: Application User
ms.search.region: Global
---

# Create an aging snapshot 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Create aging snapshot records for all customers or for the customers in a customer pool. Aging snapshot information is shown on the **Collections** list page and in the **Collections** form. You must create an aging snapshot before you can use the list page. The list page shows information only for customers for whom an aging snapshot has been created. For more information, see [Customer aging snapshot (form)](https://technet.microsoft.com/library/hh242719\(v=ax.60\)).

1.  Click **Accounts receivable** \> **Periodic** \> **Collections** \> **Customer aging snapshot**.

2.  Select an aging period definition.

3.  Optional: Select a pool. For information about how to set up a customer pool, see [Set up collections](set-up-collections.md).

4.  Select the type of date in the transaction records to use to assign transactions to aging periods.

5.  Select a date to base the aging snapshot calculations on.
    

    > [!NOTE]
    > <P>If the aging snapshot process will run as part of a batch, select <STRONG>Today's date</STRONG> in the <STRONG>Aging as of</STRONG> field. Otherwise, the aging snapshot is always created for the same date.</P>



6.  Optional: Click the **Company range** tab and select the legal entities to include in the aging snapshot.

7.  Optional: Click the **Batch** tab and set up batch processing.

8.  Click **OK**.

  


