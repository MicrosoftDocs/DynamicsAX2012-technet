---
title: 'Key tasks: Customer payments and settlements'
TOCTitle: 'Key tasks: Customer payments and settlements'
ms:assetid: 18919f74-3ef6-4911-952b-549b206ae7ea
ms:mtpsurl: https://technet.microsoft.com/library/Hh208443(v=AX.60)
ms:contentKeyID: 36056101
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- payments
- customer
- payment
- accounts receivable
- pay
audience: Application User
ms.search.region: Global
---

# Key tasks: Customer payments and settlements 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can enter customer payment information in multiple ways.

You can also complete the following procedures from the **Open customer invoices** or **Payment journals** list page.

## What do you want to do?

Enter and settle a check with transactions

Enter and settle a payment for a single invoice in a payment journal

Enter and settle a payment for multiple invoices in a payment journal

Mark invoice lines for settlement

Find form help

Find related tasks

## Enter and settle a check with transactions

Use this procedure if you want to enter payment and settlement information in the same form, **Enter customer payments**. For example, you might do this if your customer sends a check for the amount of an invoice.

1.  Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Create a journal and then click **Enter customer payments**. For information about how to create a journal, see [Create and validate journals and journal lines](create-and-validate-journals-and-journal-lines.md).

3.  If you know the invoice, interest note, collection letter, or other transaction identifier, enter the identifier, and then click the lookup button in the **Search for customer transactions** field group. Select a document and go to step 5.

4.  In the **Enter customer payment information** field group, enter information about the payment.

5.  If the **Mark by priority** button is available, you can click this button to mark all debit transactions for settlement. The transactions are marked according to the settlement priority that is specified in the **Accounts receivable parameters** form. For more information about this button, see [Enter customer payments (form)](https://technet.microsoft.com/library/hh209561\(v=ax.60\)).

6.  If the **Mark invoice lines** button is available when you select an invoice, you can click this button to open the **Mark invoice lines** form. Use this form to mark individual transaction lines for settlement and modify the amounts to settle for those lines.

7.  Click **Save in journal**.

8.  Repeat steps 3 through 7 for the remaining payments.

9.  Click **Close**.

10. In the **Journal** form, click **Validate** to validate the payment line or lines, and then click **Post** \> **Post the customer payment journal**.

Back to top

## Enter and settle a payment for a single invoice in a payment journal

Use this procedure if you know which invoice number the payment is for.

1.  Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Create a journal, and then click **Lines** to open the **Journal voucher** form for payment journal lines. For information about how to create a journal, see [Create and validate journals and journal lines](create-and-validate-journals-and-journal-lines.md).

3.  In the **Invoice** field, enter or select the invoice that you have received a payment for. Information about the customer is displayed automatically.

4.  Click **Validate** \> **Validate voucher only** to validate the payment line, and then click **Post** \> **Post the customer payment journal**.

Back to top

## Enter and settle a payment for multiple invoices in a payment journal

Use this procedure if you know which customer account the payment is for, or if the payment is intended to settle multiple invoices.

1.  Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Create a journal, and then click **Lines** to open the **Journal voucher** form for payment journal lines. For information about how to create a journal, see [Create and validate journals and journal lines](create-and-validate-journals-and-journal-lines.md).

3.  In the **Account** field, enter or select the customer account that you have received a payment for.

4.  Click **Functions** \> **Settlement**.

5.  In the **Settle open transactions** form, select the **Mark** check box on the line for the customer invoice that corresponds to the received payment.
    
    If the customer has sent a payment that applies to several invoices, select the **Mark** check box on each relevant invoice line.

6.  To see whether the payment causes a discount for the customer for a specific invoice, select the invoice line, and then click the **Cash discount** tab. If a discount applies, it will be automatically subtracted from the original invoice amount when the payment line is created in step 9.

7.  If the **Mark by priority** button is available, you can click this button to mark all debit transactions for settlement, according to the settlement priority that is specified in the **Accounts receivable parameters** form. For more information about this button, see [Settle open transactions - customer (form)](https://technet.microsoft.com/library/aa558602\(v=ax.60\))

8.  If the **Mark invoice lines** button is available when you select an invoice, you can click this button to open the **Mark invoice lines** form. Use this form to mark individual transaction lines for settlement and modify the amounts to settle for those lines.

9.  Close the **Settle open transactions** form. The payment line or lines appear in the **Journal voucher** form with the correct invoice information.

10. Click **Validate** \> **Validate voucher only** to validate the payment line or lines, and then click **Post** \> **Post the customer payment journal**.
    

    > [!NOTE]
    > <P>If you cannot post an invoice and you receive a message that mentions posting restrictions, you might be able to post only journals that you created. For more information, see <A href="https://technet.microsoft.com/library/hh227598(v=ax.60)">Posting restrictions (form)</A>.</P>



Back to top

## Mark invoice lines for settlement

When you process a customer payment using the **Enter customer payments**, payment **Journal voucher**, or **Settle open transactions** forms, you might have to mark specific invoice lines for settlement and modify the amounts to settle for those lines.

Use this procedure to mark and modify invoice lines for settlement using the **Mark invoice lines** form. To open this form, click **Mark invoice lines** in the settlement forms. The button is available if all of the following circumstances apply:

  - The **Mark lines on free text invoices and interest notes** check box is selected in the **Accounts receivable parameters** form.

  - The total amount of the selected customer transaction must be greater than zero; it is not a credit memo or a credit interest note.

  - The selected transaction contains more than one transaction that is available to be marked.

### Mark invoice lines for settlement

1.  Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**. Click **Lines**.
    

    > [!NOTE]
    > <P>You can also mark invoice lines from the <STRONG>Enter customer payments</STRONG> form. (Click <STRONG>Accounts receivable</STRONG> &gt; <STRONG>Journals</STRONG> &gt; <STRONG>Payments</STRONG> &gt; <STRONG>Payment journal</STRONG>. Click <STRONG>Enter customer payments</STRONG>.)</P>



2.  Select an invoice that contains multiple lines.

3.  Click **Mark invoice lines**.

4.  In the **Mark** field, mark the transactions that you want to settle.
    

    > [!NOTE]
    > <P>By default, all transaction lines that have an amount to settle are marked when you open the <STRONG>Mark invoice lines</STRONG> form. Lines that have negative amounts are also marked, but you cannot modify the amount to settle for lines that have negative amounts.</P>



5.  Optional: Enter an amount in the **Amount to settle** field for each invoice line.
    

    > [!NOTE]
    > <P>The default amount for this field is the <STRONG>Amount in transaction currency</STRONG> value minus the <STRONG>Discount to take</STRONG> value for the selected line. You can decrease the default amount, but you cannot increase it. You cannot specify an overpayment for a line.</P>



Back to top

## Find form help

[Journal voucher - Customer payment journal (form)](https://technet.microsoft.com/library/aa556141\(v=ax.60\))

[Enter customer payments (form)](https://technet.microsoft.com/library/hh209561\(v=ax.60\))

## Find related tasks

[Place an Accounts receivable transaction on hold](place-an-accounts-receivable-transaction-on-hold.md)

[Settle transactions with payments](settle-transactions-with-payments.md)

  


