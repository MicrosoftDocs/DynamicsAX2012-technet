---
title: Finish the currency conversion
TOCTitle: Finish the currency conversion
ms:assetid: 5e4beb66-b9ac-4946-b19a-eaafa09990e1
ms:mtpsurl: https://technet.microsoft.com/library/Aa549103(v=AX.60)
ms:contentKeyID: 36057582
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Finish the currency conversion 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

After you have completed a currency conversion, you must complete some additional procedures. You must reconcile rounding differences in converted amounts, recalculate business statistics, journalize the ledger transactions, restrict access to the conversion tool, and revalue foreign currency amounts for customer and vendor accounts.

## Reconcile after conversion and recalculation

After the currency conversion, all reconciliation reports must be generated again to make sure that all converted amounts are correct.

  - If the conversion of the ledger accounting currency causes rounding differences, these differences are not posted by using the voucher where the rounding difference occurred. Instead, the differences are posted by using the voucher that was entered for the conversion postings. After the conversion, all reports that check by voucher and date include these rounding differences. This behavior is correct and can be ignored.

  - If the customer and vendor reconciliation reports display a difference amount on the total line, and no difference amount existed before the conversion, this difference amount has to be posted. The account is the summary account for customers and vendors. The offset account is the ledger account for conversion loss or conversion profit.

## Complete final steps for the conversion

When all business statistics have been deleted, open the **Business statistics** form. Click **General ledger** \> **Periodic** \> **Currency conversions** \> **Post-conversion recalculations** \> **Business statistics**. Recalculate the business statistics by clicking **Update**.

When all ledger transaction journals have been deleted, you can journalize the ledger transactions. Click **General ledger** \> **Periodic** \> **Journals** \> **Journalizing**.

## Restrict access to the conversion tool

After the currency conversion has been successfully completed, you should restrict access to the conversion tool to prevent additional use.

1.  Click **System administration** \> **Setup** \> **Security** \> **Security privileges**.

2.  In the left pane, under **Process cycles**, expand the **Expenditure cycle** node.

3.  Expand the **Enable general ledger process** node.

4.  Set permissions for the **Convert ledger accounting currency** and **Convert ledger reporting currency** privileges. For more information, see [Security privileges (form)](https://technet.microsoft.com/library/hh209366\(v=ax.60\)).

## Revalue foreign currency amounts for customer and vendor accounts

If necessary, you can revalue foreign currency amounts after the currency conversion. You revalue foreign currency amounts by selecting **Standard** in the **Method** field for the revaluation. For more information, see [Revalue foreign currency amounts for customers or vendors](revalue-foreign-currency-amounts-for-customers-or-vendors.md), [Customer foreign currency revaluation periodic job (class form)](https://technet.microsoft.com/library/aa574761\(v=ax.60\)), and [Vendor foreign currency revaluation periodic job (class form)](https://technet.microsoft.com/library/aa554435\(v=ax.60\)).

1.  Click **Accounts receivable** \> **Periodic** \> **Foreign currency revaluation**.

2.  Click **Foreign currency revaluation**.

3.  In the **Method** field, select **Standard**.

4.  In the **Considered date** field, select the day after the date that you used for the currency conversion.

5.  In the **Date of rate** field, select the day after the date that you used for the currency conversion.

6.  Enter values in the other fields, as necessary.

7.  Click **OK** to revalue the foreign currency amounts for customers.

8.  Click **Accounts payable** \> **Periodic** \> **Foreign currency revaluation**.

9.  Click **Foreign currency revaluation**.

10. In the **Method** field, select **Standard**.

11. In the **Considered date** field, select the day after the date that you used for the currency conversion.

12. In the **Date of rate** field, select the day after the date that you used for the currency conversion.

13. Enter values in the other fields, as necessary.

14. Click **OK** to revalue the foreign currency amounts for vendors.

  


