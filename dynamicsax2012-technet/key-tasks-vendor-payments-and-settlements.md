---
title: 'Key tasks: Vendor payments and settlements'
TOCTitle: 'Key tasks: Vendor payments and settlements'
ms:assetid: c5d99b1a-bb20-416a-8ea1-4b7b7d4bc8e3
ms:mtpsurl: https://technet.microsoft.com/library/Hh242843(v=AX.60)
ms:contentKeyID: 36059305
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- vendor
- payments
- vendors
- payment
- settlement
- settlements
- pay
- AP
- accounts payable
- vendor payments
- vendor payment
- paying
audience: Application User
ms.search.region: Global
---

# Key tasks: Vendor payments and settlements 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can enter vendor payment information in multiple ways. You can also complete these procedures from the **Payment journals** list page.

## What do you want to do?

Learn more about...

Pay an invoice based on the invoice amount

Pay a specified amount and settle an invoice

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[About centralized vendor payments](about-centralized-vendor-payments.md)

[About parameters for settlements in Accounts payable](about-parameters-for-settlements-in-accounts-payable.md)

[Vendor payment settlement scenarios](vendor-payment-settlement-scenarios.md)

## Pay an invoice based on the invoice amount

Use this procedure when you know which invoices to pay, but you do not know the payment amount. This procedure shows how to pay a vendor invoice by check.

1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Create a journal, and then click **Lines** to open the **Journal voucher** form for payment journal lines. For information about how to create journals, see [Create and validate journals and journal lines](create-and-validate-journals-and-journal-lines.md).

3.  In the **Account** field, select the vendor account to which a payment will be issued.

4.  Click **Functions** \> **Settlement**.

5.  In the **Settle open transactions** form, select the **Mark** check box on the line for each vendor invoice that you want to pay.
    

    > [!NOTE]
    > <P>To make a partial payment, you can enter the amount to pay in the <STRONG>Amount to settle</STRONG> field.</P>



6.  Close the **Settle open transactions** form. The payment line that has information from the invoice is displayed in the **Journal voucher** form. The amount on the payment line contains the amount from the vendor invoice that the legal entity can pay to the vendor. The cash discount that applies to this payment, if any, is included.

7.  Verify that you want to pay the amount to the vendor, and then click **Functions** \> **Generate payments**.

8.  Depending on the method of payment on the journal line, select either the payment method or the export format, and select the bank account from which the payment is drawn. If you select a payment method, the payment method must have an export format associated with it.
    

    > [!NOTE]
    > <P>In the <STRONG>Journal voucher</STRONG> form, you can click <STRONG>Inquiries</STRONG> &gt; <STRONG>Balance control</STRONG> to verify that the bank account can cover the payment to the vendor.</P>



9.  In the **Generate payments** form, click **Dialog**, fill in the fields, and then click **Document** to specify a printer destination.

10. Click **OK** to close the **Printer setup** form, and then click **OK** to close the dialog box.

11. In the **Generate payments** form, click **OK**.

12. Click **Validate** \>**Validate voucher only** to validate the payment line, and then click **Post** \> **Post and transfer**.
    

    > [!NOTE]
    > <P>If you cannot post and you receive a message that mentions posting restrictions, you might be able to post only journals that you create. For more information, see <A href="https://technet.microsoft.com/library/hh227598(v=ax.60)">Posting restrictions (form)</A>.</P>



Back to top

## Pay a specified amount and settle an invoice

Use this procedure when you know the amount that you want to pay. You can settle the payment amount with as many invoices as possible.

1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Create a journal, and then click **Lines** to open the **Journal voucher** form for payment journal lines. For information about how to create journals, see [Create and validate journals and journal lines](create-and-validate-journals-and-journal-lines.md).

3.  In the **Account** field, select the vendor account to which a payment will be issued.

4.  Select the description.

5.  In the **Debit** field, enter the payment amount.

6.  Click **Functions** \> **Settlement**. The **Settlement** option is available only if multiple invoices exist for the vendor.

7.  In the **Settle open transactions** form, select the **Mark** check box on the line for each vendor invoice that you want to pay.
    

    > [!NOTE]
    > <P>To make a partial payment, you can enter the amount to pay in the <STRONG>Amount to settle</STRONG> field.</P>



8.  Close the **Settle open transactions** form.

9.  In the **Journal voucher** form, click **Functions** \> **Generate payments**.

10. Depending on the method of payment on the journal line, select either the payment method or the export format, and select the bank account from which the payment is drawn.

11. If the payment method requires printed documents, click **Dialog**, fill in the fields, and then click **Document** to print the documents.

12. Click **OK** to close the **Printer setup** form, and then click **OK** to close the dialog box.

13. In the **Generate payments** form, click **OK**.

14. Click **Validate** \> **Validate voucher only** to validate the payment line, and then click **Post** \> **Post and transfer**.

Back to top

## Find form help

[Journal voucher - Vendor payment journal (form)](https://technet.microsoft.com/library/aa599011\(v=ax.60\))

[Settle open transactions - vendor (form)](https://technet.microsoft.com/library/aa619609\(v=ax.60\))

## Find related tasks

[Print copies of payments as non-negotiable checks](print-copies-of-payments-as-non-negotiable-checks.md)

[Settle transactions with payments](settle-transactions-with-payments.md)

  


