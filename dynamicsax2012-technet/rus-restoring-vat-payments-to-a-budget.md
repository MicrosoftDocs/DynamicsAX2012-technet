---
title: (RUS) Restoring VAT payments to a budget
TOCTitle: (RUS) Restoring VAT payments to a budget
ms:assetid: e47e8889-2612-41ad-84ab-c82714c26f95
ms:mtpsurl: https://technet.microsoft.com/library/JJ711721(v=AX.60)
ms:contentKeyID: 49388044
author: tonyafehr
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- (RUS)
- Russia
- Restoring VAT
- VAT payments
audience: Application User
ms.search.region: Russia
---

# (RUS) Restoring VAT payments to a budget 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Materials and fixed assets that are acceptable as deductions and used in value-added tax (VAT)-free activities are subject to VAT amount restoration. Companies that conduct operations that are subject to VAT, and that are tax exempt, can deduct all incoming VAT amounts if their share of expenses on tax-exempt operations is not greater than 5 percent of the total production cost. The VAT amount deducted on goods, materials, or fixed assets that are not subject to VAT can be recovered or restored by goods shipment on export and fixed asset usage in export production.

VAT amounts can also be restored for the following transactions:

  - Write-off of a fixed asset

  - Disposal because of fire

  - Transfer to authorized capital

The cost of goods, such as work or services, can be calculated by including or excluding VAT, depending on the revenue calculation method for VAT amount restoration.


> [!NOTE]
> <P>The amount is specified as excluding VAT during realization on export transactions.</P>



The restored VAT amount can be canceled for the current period. The restored VAT processing and cancelation log is displayed in the **VAT processing log** form. During confirmation of the export process, any VAT amounts that were restored earlier can be reimbursed. Companies can reimburse a VAT amount on export factures under these conditions:

  - Confirmation on export factures was received in time.

  - Confirmation on export factures was not received, and the confirmation term has expired in the current period.

You must complete the following set up tasks to restore VAT amounts and calculate revenue:

  - Set up ledger posting groups. For more information, see [Set up ledger posting groups for sales tax](set-up-ledger-posting-groups-for-sales-tax.md).

  - Set up sales tax settlement periods. For more information, see [Set up a sales tax settlement period](set-up-a-sales-tax-settlement-period.md).

  - Set up VAT operation codes.For more information,see[(RUS) VAT operation codes (form)](https://technet.microsoft.com/library/jj839695\(v=ax.60\))

  - Set up sales tax codes for export operation. For more information, see [Sales tax codes (form)](https://technet.microsoft.com/library/aa553257\(v=ax.60\)) and [(RUS) Define parameters for export operations](rus-define-parameters-for-export-operations.md).

  - Set up sales tax groups and sales tax authorities. For more information, see [Sales tax groups (form)](https://technet.microsoft.com/library/aa498345\(v=ax.60\)), [(RUS) Set up sales tax groups for tax calculation](rus-set-up-sales-tax-groups-for-tax-calculation.md), and [Set up sales tax authorities](set-up-sales-tax-authorities.md).

  - Set up item sales tax groups. For more information, see [(RUS) Set up item sales tax groups for tax calculation](rus-set-up-item-sales-tax-groups-for-tax-calculation.md).

  - Set up customer posting profiles. For more information, see [Customer posting profiles (form)](https://technet.microsoft.com/library/aa600572\(v=ax.60\)).

  - Set up dimension groups.

  - Set up general ledger parameters to restore VAT amount and revenue calculations.

## See also

[(RUS) Set up parameters for VAT restoration and revenue calculation](rus-set-up-parameters-for-vat-restoration-and-revenue-calculation.md)

  


