---
title: (RUS) Estimate remaining work in process and finished products for direct expenses
TOCTitle: (RUS) Estimate remaining work in process and finished products for direct expenses
ms:assetid: 6c861d5e-3897-4d78-b786-84cc81024c8a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ911505(v=AX.60)
ms:contentKeyID: 52075391
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Estimate remaining work in process and finished products for direct expenses 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

For direct expenses, you must estimate and report the remaining work in process (WIP), finished products (FP) in inventory, and finished products that are shipped but not sold. In addition, you must distribute direct and indirect expenses that are related to production by tax group. Accurate distribution of expenses is important, because the expenses become part of the tax base for profit tax calculation.

The direct expenses for the current month are distributed among these account objects:

  - Work in process

  - Finished products in inventory

  - Items that are shipped but not sold at the end of the production month

The WIP and FP estimation in the tax accounting register helps you perform the following tasks:

  - Estimate the WIP remainder cost price at period-end by using expense tax codes.

  - Estimate the remainder cost price of half-finished products, finished products in inventory, and shipped finished products at period-end for tax accounting.

  - Estimate the issue cost price of finished products and half-finished products for the period for tax accounting. The estimate includes sales to customers, written-off losses, and write-offs in costs.

  - Calculate the difference between the accounting and the tax cost price.

  - Create transactions on production tax accounting and sales on tax accounts.

You must set up the parameters that are important for profit tax calculation in the **General ledger parameters** form. The manufacturing expense sums in tax accounting are calculated based on the setup that you perform for tax registers in the **General ledger parameters** form in the **Profit tax** area, and on the turnover of accrued fixed assets, intangible asset depreciation, and deferrals in tax accounting. For more information, see [(RUS) Set up journal names and number sequences for tax cost price journals](rus-set-up-journal-names-and-number-sequences-for-tax-cost-price-journals.md).

The register calculations for tax accounting are as follows:

  - Manufacturing write-off = (Write-off of manufacturing (BA) \* Starting balance of manufacturing (TA) + Accrued manufacturing (TA)) / (Starting balance of manufacturing (BA) + Accrued manufacturing (BA))

  - Accrued half-finished product = (Accrued half-finished product (BA) \* Write-off of manufacturing (TA)) / (Write-off of manufacturing (BA))

  - Write-off of half-finished product = (Written-off half-finished product (BA) \* Starting balance of half-finished product (TA) + Accrued half-finished product (TA)) / (Starting balance of half-finished product (BA) + Accrued half-finished product (BA))

The other sections of the WIP and FP estimation in the tax accounting register are calculated in the same way.


> [!NOTE]
> <P>For more information about how to set up these registers, see <A href="rus-set-up-a-register-for-incomes-and-expenses-that-do-not-influence-the-tax-base.md">(RUS) Set up a register for incomes and expenses that do not influence the tax base</A>, <A href="rus-set-up-a-register-for-deferrals.md">(RUS) Set up a register for deferrals</A>, <A href="rus-set-up-a-depreciation-register-for-fixed-assets.md">(RUS) Set up a depreciation register for fixed assets</A>, and <A href="rus-set-up-a-depreciation-register-for-intangible-assets.md">(RUS) Set up a depreciation register for intangible assets</A>.</P>



## See also

[(RUS) Set up WIP and FP estimates for a tax accounting register](rus-set-up-wip-and-fp-estimates-for-a-tax-accounting-register.md)

[(RUS) Set up parameters to estimate WIP and FP in a tax accounting register](rus-set-up-parameters-to-estimate-wip-and-fp-in-a-tax-accounting-register.md)

  


