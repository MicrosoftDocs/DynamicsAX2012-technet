---
title: (ITA) Reverse a closed conditional sales tax transaction
TOCTitle: (ITA) Reverse a closed conditional sales tax transaction
ms:assetid: 61264c63-3c28-483f-b987-ccd4eeaa1fec
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh209170(v=AX.60)
ms:contentKeyID: 36057643
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- reverse
- Italy
- sales tax
---

# (ITA) Reverse a closed conditional sales tax transaction 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Sales tax is paid on conditional sales transactions when an invoice is settled, not when the invoice is posted. For invoices that are not fully settled with a single payment, you must report and pay sales tax only on the amounts that are settled. You can reverse a conditional sales tax transaction only during the fiscal month in which it was created.

You must create a sales tax group, sales tax code, item sales tax group, and settlement period for conditional sales tax transactions. For more information, see [Set up conditional sales taxes](set-up-conditional-sales-taxes.md).

You can post a free text invoice, settle the payment for the invoice, and then calculate the sales tax payment for the conditional sales tax transaction.

## Post a free text invoice and settle the transaction

Use the **Free text invoice details** form to create and post a free text invoice.

1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**.

2.  Create a new free text invoice or double-click on an existing free text invoice to modify.

3.  In the **Sales tax group** field, select a sales tax group.

4.  In the **Item sales tax group** field, select an item sales tax group.

5.  Click **Post** to open the **Post free text invoice** form, and then click **OK** to post the free text invoice.

6.  Close the form to save your changes.

7.  Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**.

8.  Press CTRL+N to create a new journal. For more information, see [Create and validate journals and journal lines](create-and-validate-journals-and-journal-lines.md).

9.  Click **Lines**.

10. In the **Account** and **Invoice** fields, select a customer account number and the number of the free text invoice that is posted for the customer.

11. Click **Payment fee** tab, and in the **Fee ID** field, select the payment fee for the transaction.

12. In the **Currency** field, select the currency for payment.

13. In the **Sales tax group** field, select the sales tax group.

14. In the **Item sales tax group** field, select the item sales tax group.

15. Click **Functions** \> **Settlement** to open the **Settle open transactions** form.

16. Select the **Mark** check box to select the voucher for settlement.

17. Close the form to save your changes.

18. Click **Validate** \> **Validate** to validate the journal, and then click **Post** \> **Post** to post the journal.

19. Close the forms to save your changes.

## Calculate a sales tax payment

Use the **Sales tax payment** form to calculate and record sales tax payments for the settlement period.

1.  Click **General ledger** \> **Periodic** \> **Sales tax payments** \> **Sales tax payments**.

2.  In the **From date** and **Transaction date** fields, select the start date and the end date of the fiscal month. For more information, see [Sales tax payment (class form)](https://technet.microsoft.com/en-us/library/aa598539\(v=ax.60\)).

3.  In the **Sales tax payment version** field, select **Original**.

4.  Select the **Update** check box, and then click **OK** to post the sales tax payment calculations for the settlement period.

## Reverse a posted transaction

You can reverse a closed conditional sales tax transaction if the fiscal month has not closed. Use the **Closed transaction editing in several currencies** form to reverse a closed transaction for conditional sales tax.

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.

2.  Select a customer account, and then click **Collect** \> **Closed transaction editing** to open the **Closed transaction editing in several currencies** form.

3.  Select the **Mark** check box for the transaction to be reversed, and then click **Reverse**. The transaction is reversed.

4.  Close the forms to save your changes.

## See also

[Sales tax codes (form)](https://technet.microsoft.com/en-us/library/aa553257\(v=ax.60\))

[General ledger parameters (form)](https://technet.microsoft.com/en-us/library/aa557286\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

