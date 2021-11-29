---
title: Close the general ledger at month end
TOCTitle: Close the general ledger at month end
ms:assetid: 7fa71a7e-5538-45bd-901e-bdb3f8680613
ms:mtpsurl: https://technet.microsoft.com/library/Aa571542(v=AX.60)
ms:contentKeyID: 36058329
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- general ledger closing
- closing procedures
- month-end
- period closing
- monthly closing
audience: Application User
ms.search.region: Global
---

# Close the general ledger at month end 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the following information to complete monthly closing procedures for General ledger. All procedures are optional, and you might not be able to complete a procedure, depending on the options that are selected in the **Configuration** form.

1.  Complete closing tasks for all other modules. For more information, see [Close Accounts receivable overview](close-accounts-receivable-overview.md), [Close Accounts payable overview](close-accounts-payable-overview.md), and [About inventory close](about-inventory-close.md).

2.  Verify that all journal vouchers for the month are posted. For more information, see [Post and print a journal or journal lines](post-and-print-a-journal-or-journal-lines.md).

3.  Use the **Foreign currency revaluation** form to process the currency foreign currency revaluation to generate any unrealized gain or loss amounts due to currency fluctuation. For more information, see [Perform a foreign currency revaluation](perform-a-foreign-currency-revaluation.md).

4.  Settle transactions for each ledger account with transactions from the same or other ledger accounts in the **Ledger settlements** form. For more information, see [Settle transactions between ledger accounts](settle-transactions-between-ledger-accounts.md).

5.  Use the **Process allocation request** form to process allocation rules. For more information, see [Process an allocation request](process-an-allocation-request.md).

6.  Use the **Journal** form to enter and post any manual period-end adjustments. For more information, see [Journal header (form)](https://technet.microsoft.com/library/aa557917\(v=ax.60\)).

7.  Journalize transactions monthly in the **Journalize transactions** form and view the **Ledger journal** report to verify the information. For more information, see [Journal header (form)](https://technet.microsoft.com/library/aa557917\(v=ax.60\)).

8.  In the legal entity that is set up for consolidation, consolidate and verify the changes in the **Consolidations** form. For more information, see [Consolidate transactions](consolidate-transactions.md).

9.  Print the **Trial balance**, **Account statement**, **Financial statement**, and required reconciliation reports.

10. In the **Ledger calendar** form, select the fiscal year and period to modify, and then select **On hold** or **Closed** in the **Period status** field to prevent users from posting transactions in the closed month. You can reopen a period that is on hold, but you cannot reopen a closed period.

You can also complete the following procedures, and might legally be required to do this.

1.  To calculate the sales tax that is due for a specific period, use the **Sales tax payments** form. (Click **General ledger** \> **Periodic** \> **Sales tax payments** \> **Sales tax payments**.)

2.  To print information about trade between European Union (EU) countries/regions, use the **Intrastat** form. (Click **Organization administration** \> **Periodic** \> **Foreign trade** \> **Intrastat**.)

3.  To print information about EU sales for value added tax (VAT) declaration purposes, use the **EU sales list** form. (Click **Organization administration** \> **Periodic** \> **Foreign trade** \> **EU sales list**.)

## See also

[Close periods in the general ledger](close-periods-in-the-general-ledger.md)

[Ledger calendar (form)](https://technet.microsoft.com/library/hh242506\(v=ax.60\))

  


