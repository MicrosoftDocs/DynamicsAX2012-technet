---
title: (POL) Create a credit correction for packing slip ledger postings during sales invoice posting
TOCTitle: (POL) Create a credit correction for packing slip ledger postings during sales invoice posting
ms:assetid: 3f2ac0a7-75c5-4c78-860f-c542dea3001e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678180(v=AX.60)
ms:contentKeyID: 49386904
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Poland
---

# (POL) Create a credit correction for packing slip ledger postings during sales invoice posting 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

For a sales order, you can post a packing slip for credit correction in the **Posting packing slip** form. The posted packing slip is reversed when the invoice is posted as a correction transaction.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**. On the **Action Pane**, in the **New** group, click **Sales order**.

2.  On the **Sales order** form, click the **Pick and pack** tab.

3.  On the **Pick and pack** tab, on the **Action Pane** in the **Generate** group, click **Packing slip**.

4.  On the **Packing slip posting** form, on the **Other** tab, select the **Credit correction** check box to do the following:
    
      - Reverse a debit transaction by adding a minus debit transaction to the Packing slip ledger account on the **Posting** form for **Inventory and warehouse management**. (Click **Inventory management** \> **Setup** \> **Posting** \> **Posting**. On the **Sales order** tab, select the **Packing slip** option.) For more information see [Posting (form)](https://technet.microsoft.com/en-us/library/aa551718\(v=ax.60\)).
    
      - Reverse a credit transaction by adding a minus credit transaction to the Packing slip offset ledger account on the **Posting** form for **Inventory and warehouse management**. (Click **Inventory management** \> **Setup** \> **Posting** \> **Posting**. On the **Sales order** tab, select the **Packing slip offset** option.) For more information see [Posting (form)](https://technet.microsoft.com/en-us/library/aa551718\(v=ax.60\)).

5.  Click **OK** to post the invoice.

  


