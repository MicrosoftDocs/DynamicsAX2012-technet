---
title: (BRA) Generate a trial balance report
TOCTitle: (BRA) Generate a trial balance report
ms:assetid: 4c24b07d-8d4b-420c-abc8-1f24f34c4361
ms:mtpsurl: https://technet.microsoft.com/library/JJ710493(v=AX.60)
ms:contentKeyID: 49384385
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- trial balance
- BRA
- Brazil
- accounting books
- generate accounting books
audience: Application User
ms.search.region: Brazil
---

# (BRA) Generate a trial balance report 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the Trial balance summary report to generate a trial balance report that lists the ledger accounts with their corresponding balances, and displays the sum of the debit and credit balances. The trial balance report can have a maximum of 500 pages, referred to as an accounting book. It can contain more than one volume, if necessary, for the same calendar year.

1.  Click **General ledger** \> **Reports** \> **Transactions** \> **Trial balance summary**.

2.  In the **Date interval** field, select a date interval code. For more information, see [Date intervals (form)](https://technet.microsoft.com/library/aa558459\(v=ax.60\)).

3.  In the **From date** and **To date** fields, enter the starting and ending dates of the period that the report is generated for.

4.  Select the **Include opening** check box to include the opening transactions in the report.

5.  In the **Page** and **Book number** fields, enter the number of pages in the accounting book and an accounting book number.

6.  In the **Posting layer** field, select a posting layer that has transactions to include in the report from the following options:
    
      - **Current** – Transactions that are posted to the **Current** posting layer are included.
    
      - **Operations** – Transactions that are posted to the **Current** or **Operations** posting layer are included.
    
      - **Tax** – Transactions that are posted to the **Current** or **Tax** posting layer are included.
    
      - **Operations minus tax** – Transactions that are posted to the **Operations** posting layer, minus the transactions that are posted to the **Tax** posting layer are included.
    
      - **Only operations** – Transactions that are posted to the **Operations** posting layer are included.
    
      - **Only tax** – Transactions that are posted to the **Tax** posting layer are included.
    
      - **Operations plus tax** – Transactions that are posted to the **Operations** or **Tax** posting layer are included.
    
      - **Total** – Transactions that are posted to the **Current**, **Operations**, and **Tax** posting layers are included.
    
      - **Dual warehouse** – Transactions that are posted to the **Dual warehouse** posting layer are included.

7.  Click **OK** to generate the report.

## See also

[(BRA) Trial balance summary report (LedgerTrialBalance\_BR)](https://technet.microsoft.com/library/jj710466\(v=ax.60\))

  


