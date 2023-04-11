---
title: (RUS) Reverse a fixed asset acquisition transaction
TOCTitle: (RUS) Reverse a fixed asset acquisition transaction
ms:assetid: bcaa74e4-cfb5-466b-8dab-cb0697828d66
ms:mtpsurl: https://technet.microsoft.com/library/JJ711556(v=AX.60)
ms:contentKeyID: 49387879
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Reverse a fixed asset acquisition transaction  


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

When you create a reverse transaction, the information and amount of the original transaction are saved. By default, the reversal date and the original transaction date are the same. However, when reversing transactions, you can specify a reversal date that is different from the original transaction date. You can also reverse an amortization transaction using this process. To change the fixed asset status to **Operation**, you must cancel the write-off for all value models.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Fixed assets** \> **Common** \> **Fixed assets** \> **Fixed assets**. click **Value Models**\> **Transactions** to open the **FA Transactions** form.

2.  Select the fixed asset acquisition transaction, and then click **Reverse transaction** to open the **Reverse transaction** form.

3.  In the **Reverse date**, select the transaction reverse date.

4.  Click **OK**. A transaction is created in the **FA transactions** form that reverses the original transaction.

5.  Click **Voucher** to view the transaction in the ledger in the **Operation codes** form.
    

    > [!NOTE]
    > <P>To change the status to <STRONG>Scheduled</STRONG>, run the reverse acquisition transaction for all value models. If the asset that was reversed was built from warehoused components, transactions are created to record the return of the components to the warehouse. When you reverse an acquisition transaction, the cost price of the returned components may differ from the current warehouse cost price. However, after warehouse closure, the components will reflect the current pricing.</P>


  


