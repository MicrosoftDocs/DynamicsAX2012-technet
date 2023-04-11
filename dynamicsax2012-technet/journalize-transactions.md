---
title: Journalize transactions
TOCTitle: Journalize transactions
ms:assetid: db130911-2d31-46d0-bfa1-a50ae84d4f26
ms:mtpsurl: https://technet.microsoft.com/library/Aa551219(v=AX.60)
ms:contentKeyID: 36059664
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Journalize transactions 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Transactions are usually recorded in a journal at least once a month. Each transaction is marked with the number of the journal it was recorded in, as well as the line number.

To ensure that the transactions also get a date and time stamp of their entry in the journal, select the **Extended ledger journal** check box in the **General ledger parameters** form.

All further transactions will occur in the next journal. It is therefore important to always include all open periods in the journal.

1.  Click **General ledger** \> **Periodic** \> **Journals** \> **Journalizing**.

2.  Click **OK**.


> [!TIP]
> <P>To enter a range of vouchers or dates to journalize, click <STRONG>Select</STRONG>. You will usually want to journalize all available transactions.</P>



The journalization procedure creates a journal list, which can be viewed in the **Ledger journal** form or printed.

## See also

[Ledger journal lines (form)](https://technet.microsoft.com/library/aa557422\(v=ax.60\))

[Ledger journal (form)](https://technet.microsoft.com/library/aa589041\(v=ax.60\))

  


