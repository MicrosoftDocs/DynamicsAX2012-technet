---
title: (RUS) Calculation algorithm for WIP and FP estimation
TOCTitle: (RUS) Calculation algorithm for WIP and FP estimation
ms:assetid: 7c427813-6d39-439c-bbbd-8c4edbad2580
ms:mtpsurl: https://technet.microsoft.com/library/JJ923548(v=AX.60)
ms:contentKeyID: 52075397
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Calculation algorithm for WIP and FP estimation 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

To calculate the work in process (WIP) and finished products (FP) estimate in the tax accounting register, you must summarize the general ledger account turnovers and balances if there is a total account, or issue offset account, for all register lines. Data for the **Starting balance** column is populated from the **Closing balance** column of the WIP and FP estimate in the tax accounting register for the previous period.

## Calculate the Accrued column

For WIP, the amount of production expenses in tax accounting is determined by using three components:

  - Production account turnover in accounting, where all transactions with the account are grouped by expense code, and tax calculation amounts are filtered by expense codes that have a direct expense type.

  - Depreciation and deferrals write-off turnovers on the tax value model, from the Fixed asset (FA) depreciation, Intangible asset (IA) depreciation, and Deferrals registers.

  - Turnovers on the production account in accounting that are reflected in the income and expenses that do not affect the tax base register are excluded.


> [!NOTE]
> <P>For transactions for the production account, you must specify the financial dimension in the <STRONG>Tax dimension</STRONG> field in the <STRONG>Profit tax</STRONG> area in the <STRONG>General ledger parameters</STRONG> form.</P>



## Calculate the Written off column

Work in process, half-finished products, finished products in inventory, and finished shipped products are calculated by using the same proportions that are used in accounting. The amount of the accrual and the starting balance are written off.

## Calculate the Issue column

Write-offs from production, half-finished products, and finished product accounts for every offset account are calculated by using the same proportions that are used in accounting. The amount of the accrual and the starting balance are written off.

## See also

[(RUS) Calculate and approve the WIP and FP estimate in a tax accounting register](rus-calculate-and-approve-the-wip-and-fp-estimate-in-a-tax-accounting-register.md)

  


