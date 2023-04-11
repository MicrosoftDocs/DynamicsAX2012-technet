---
title: (MEX) Create and post inflation adjustment ledger transactions
TOCTitle: (MEX) Create and post inflation adjustment ledger transactions
ms:assetid: 55163329-e611-47b3-b2d8-f900f04da137
ms:mtpsurl: https://technet.microsoft.com/library/Hh208960(v=AX.60)
ms:contentKeyID: 36057313
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Mexico
- ledger transactions
- adjustment
- inflation
audience: Application User
ms.search.region: Mexico
---

# (MEX) Create and post inflation adjustment ledger transactions 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The inflation adjustment process allows you to view inflation adjustment data in your financial statements by posting ledger transactions. Use the **Inflation adjustment B-10** form to create and post inflation adjustment ledger transactions for an adjustment period. The adjustment process calculates inflation adjustments for the following:

  - REPOMO effect

  - Profit and loss accounts

  - Inventory accounts

  - Capital accounts

You can run a simulation of the inflation adjustment process before creating an inflation adjustment transaction for an adjustment period.

1.  Click **General ledger** \> **Periodic** \> **Inflation adjustment B-10**.

2.  Press CTRL+N to create a new inflation adjustment journal.

3.  In the **From date** and **To date** fields, enter the starting date and ending date of the adjustment period.

4.  In the **Posting date** field, enter the posting date of the adjustment transaction.

5.  In the **Posting layer** field, select the posting layer for the transactions:
    
      - **Current** – Information is collected and posted from the current ledger.
    
      - **Operations** – Information is collected and posted from the operating layer.
    
      - **Tax** – Information is collected and posted from the tax layer.

6.  In the **Note** field, enter any additional notes about the inflation adjustment.

7.  Click **Inflation adjustment** to calculate the adjustment and post the corresponding ledger transactions.

8.  In the **Description** field, enter a description for the adjustment transaction.

9.  Click **Validate** to validate the inflation adjustment journal.

10. Click **OK** to post the journal. The status of the inflation adjustment is changed to **Posted**.

## See also

[(MEX) Inflation Adjustment B-10 (form)](https://technet.microsoft.com/library/hh209670\(v=ax.60\))

[(MEX) Set up the inflation adjustment parameters](mex-set-up-the-inflation-adjustment-parameters.md)

  


