---
title: Create accounting distributions for free text invoices
TOCTitle: Create accounting distributions for free text invoices
ms:assetid: 0915dd10-3e3b-4760-97cf-db7d355bc65d
ms:mtpsurl: https://technet.microsoft.com/library/Hh242121(v=AX.60)
ms:contentKeyID: 36055979
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- accounting distributions
- create accounting distributions
- create distributions
- distributions
audience: Application User
ms.search.region: Global
---

# Create accounting distributions for free text invoices 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use the **Accounting distributions** form to create and modify distribution lines for free text invoices. For more information about distributions, see [About accounting distributions and subledger journal entries for free text invoices](about-accounting-distributions-and-subledger-journal-entries-for-free-text-invoices.md).

1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**.

2.  Double-click the invoice to create a distribution for.

3.  To distribute header amounts, click **Distribute amounts** on the **Action Pane**, and then skip to step 5.

4.  To distribute line amounts, select the invoice line to create a distribution for, and then click **Distribute amounts** in the **Invoice lines** grid.

5.  In the **Accounting distributions** form, in the **Distributed by** field, select whether to distribute amounts by percentage, amount, or quantity.

6.  You can create distributions in the following ways:
    
      - To create multiple distributions that have the same quantity, percentage, or amount distribution, click **Split** for each distribution to create, select a ledger account for each distribution, and then click **Distribute equally**.
    
      - To create distributions one at a time, click **Split**. Select the ledger account to distribute the invoice line to and enter the quantity, percentage, or amount to distribute. For example, if you selected **Quantity** in the **Distributed by** field, enter an amount in the **Quantity** field.
        
        Repeat until you are finished creating distributions.

  


