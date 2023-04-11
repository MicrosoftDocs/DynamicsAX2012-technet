---
title: (RUS) Activate corresponding mechanism for accounting transactions
TOCTitle: (RUS) Activate corresponding mechanism for accounting transactions
ms:assetid: 3572cf1e-06c9-4e85-ac0f-b7e1db035a90
ms:mtpsurl: https://technet.microsoft.com/library/JJ665271(v=AX.60)
ms:contentKeyID: 49387360
author: tonyafehr
ms.date: 07/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Activate corresponding mechanism for accounting transactions 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The account correspondence mechanism allows you to create correspondence relations between transactions. When the account correspondence mechanism is turned on, each new accounting transaction created will consist of a set of two-way corresponding transactions. When posting the accounting transactions, the corresponding relation is defined automatically. If non-corresponded transactions existed before the account correspondence mechanism was turned on, they would not be linked automatically.

1.  Click **General ledger** \> **Setup** \> **General ledger parameters**.

2.  Click **Ledger**, and then select the **Use corresponding mechanism** check box to activate the account correspondence mechanism.

3.  Click **Number sequences** and then select the number sequence code for **Correspondence pack**.


> [!NOTE]
> <P>After the correspondence mechanism is activated, all new transactions will have correspondence relations. If you cannot establish a correspondence link for a transaction, a message with a warning is displayed. Click this message to go to the manual correspondence function to correspond the transactions manually.</P>



## See also

[(RUS) Manual correspondence (form)](https://technet.microsoft.com/library/jj733174\(v=ax.60\))

[(RUS) Define corresponding relations for transactions manually](rus-define-corresponding-relations-for-transactions-manually.md)

  


