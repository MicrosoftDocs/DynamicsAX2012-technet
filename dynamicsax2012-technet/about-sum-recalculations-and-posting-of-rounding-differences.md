---
title: About sum recalculations and posting of rounding differences
TOCTitle: About sum recalculations and posting of rounding differences
ms:assetid: 7d43c68a-3a5b-4df9-b96a-21c340754809
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa571526(v=AX.60)
ms:contentKeyID: 36058295
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# About sum recalculations and posting of rounding differences [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The following information explains where differences in rounding might occur.

  - If prices of products have been converted to zero, a report is printed, which displays the product number, module type, price before the conversion, and unit.

  - Rounding differences between sales tax and the general ledger are posted to the general journal.

  - Foreign currency revaluation amounts are recalculated and customer and vendor transaction amounts are recalculated.

  - Customer and vendor settlement records are created for rounding differences for each customer and vendor transaction.

  - Rounding differences for customers and vendors are posted to the general journal.

  - Settled cost amounts and cost adjustment amounts in closed inventory transactions are recalculated.

  - Rounding differences in Inventory management are posted to the general journal.

  - On-hand inventory is recalculated.

  - Total amounts in ledger journals are recalculated.

  - Ledger closing sheets are recalculated.

  - Ledger balances are recalculated.

  - Rounding differences in General ledger are posted to the general journal.

  - Opening ledger transactions are recalculated.

  - The final amount in the ledger balances is calculated.

If you convert to a new ledger accounting currency, and an error has occurred during the recalculation of total amounts or the posting of rounding differences, you must close the **Ledger accounting currency conversion** form. The total amounts will be recalculated and the rounding differences will be posted.

You must close Microsoft Dynamics AX and restart it when the conversion date in the **Ledger accounting currency conversion** form is changed.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

