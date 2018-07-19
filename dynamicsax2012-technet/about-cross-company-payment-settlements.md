---
title: About cross-company payment settlements
TOCTitle: About cross-company payment settlements
ms:assetid: f2c362bd-76bf-489e-9a43-df585d51d740
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg243279(v=AX.60)
ms:contentKeyID: 36059972
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- vendor
- customer
- payment
- due-from
- due-to
- invoice company
- invoice legal entity
- payment company
- payment legal entity
- discount
- overpayment
- overpayments
- underpayment
- underpayments
- penny
- voucher
audience: Application User
ms.search.region: Global
---

# About cross-company payment settlements 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When a customer or vendor payment is entered in one legal entity and is settled with an invoice that was entered in another legal entity, the applicable settlement, due-to, and due-from transactions are automatically generated for each legal entity. A settlement record is created for each combination of invoice and payment in the transaction. Each settlement record is assigned a new voucher number, which is based on the **Payment voucher** number sequence series that is specified in the **Accounts receivable parameters** form for customers and in the **Accounts payable parameters** form for vendors.

If additional settlement records are generated for cash discounts, foreign currency revaluations, penny differences, overpayments, or underpayments, they are assigned the later date of the payment or invoice transaction. If settlement occurs after the payment is posted, the settlement records use the settlement posting date that is specified in the **Settle open transactions** form.

For information about posting for cross-company payment settlements, see [About centralized customer payments](about-centralized-customer-payments.md) and [About centralized vendor payments](about-centralized-vendor-payments.md).

## Posting types, transaction types, and default descriptions

Intercompany settlement voucher transactions use the **Intercompany settlement** posting type and the **Intercompany customer settlement** and **Intercompany vendor settlement** transaction types. You can set up information for the transaction type in the **Default descriptions** form.

The following transaction types are available for use in single-company and cross-company settlements:

  - Settlement

  - Cash discount

  - Foreign currency revaluations (includes realized and unrealized foreign currency revaluations)

  - Penny difference

  - Overpayment/underpayment

You can also define default descriptions for intercompany settlement vouchers. For more information, see [Set up centralized customer payments](set-up-centralized-customer-payments.md) and [Set up centralized vendor payments](set-up-centralized-vendor-payments.md).

## Currency exchange gains or losses

The exchange rate that is used for customer or vendor transactions is stored with the transaction.

Realized gains or losses for currency exchanges are posted to either the legal entity of the invoice or the legal entity of the payment, depending on the option that is selected for the **Post currency exchange gain or loss** field in the **Intercompany accounting** form for the legal entity of the payment.

The following examples use these currencies:

  - Payment accounting currency: EUR

  - Invoice accounting currency: USD

  - Payment transaction currency: DKK

  - Invoice transaction currency: CAD

## Currency calculations

When settling an invoice that is entered in one legal entity with a payment that is entered in another legal entity, the transaction currency of the payment (DKK) is converted in three steps:

1.  Converted to the accounting currency of the payment (EUR), using the exchange rates from the legal entity of the payment

2.  Converted to the accounting currency of the invoice (USD)

3.  Converted to the transaction currency of the invoice (CAD), using the exchange rates from the legal entity of the invoice

The conversion process uses the exchange rates as of the payment date. If the resulting payment amount in the transaction currency of the invoice (CAD) is equal to the invoice amount (CAD), the invoice is considered fully paid.

When the **Settle open transactions** form is opened from a payment journal where the payment amount was not entered, the amount to settle is calculated based on the invoices that are selected for settlement in the **Settle open transactions** form. The amount to settle is converted in three steps:

1.  Converted to the accounting currency of the invoice (USD), using the exchange rates from the legal entity of the invoice as of the payment date

2.  Converted to the accounting currency of the payment (EUR), using the exchange rates from the legal entity of the invoice as of the payment date

3.  Converted to the transaction currency of the payment (DKK)

The resulting payment amount is transferred to the payment journal line when you close the **Settle open transactions** form.

## Posting for gain or loss because of different accounting currencies

If there is a currency exchange gain or loss, the gain or loss is posted to the legal entity that is specified for the **Post currency exchange gain or loss** field in the **Intercompany accounting** form for the legal entity of the payment. The gain or loss amount is converted to the accounting currency of the legal entity where the gain or loss amount is posted, using the exchange rate that is defined for that legal entity.

## Cash discounts

Cash discounts that are generated during the cross-company settlement process are posted to either the legal entity of the invoice or the legal entity of the payment, depending on the option that is selected for the **Post cash discount** field in the **Intercompany accounting** form for the legal entity of the payment. A corresponding settlement transaction is generated in the legal entity of the invoice.


> [!NOTE]
> <P>Cash discounts that are generated during the cross-company settlement process for a credit note are posted to the legal entity of the credit note. For information about posting cash discounts, see <A href="about-centralized-customer-payments.md">About centralized customer payments</A> and <A href="about-centralized-vendor-payments.md">About centralized vendor payments</A>.</P>



## Overpayments and underpayments

Overpayment, underpayment, and penny difference tolerances are determined based on the legal entity of the payment for overpayments, and on the legal entity of the invoice for underpayments. The posting account that is used is determined by the setting in the **Cash discount administration** field in the **Accounts receivable parameters** form for customers, and the **Cash discount administration** field in the **Accounts payable parameters** form for vendors:

  - If the cash discount administration setting is **Specific**, or if the setting is **Unspecific** and the applicable cash discount is posted in a different legal entity from the overpayment, the automatic account for **Customer cash discount**, **Vendor cash discount**, or **Penny difference in accounting currency** is used. You can specify these accounts in the **Accounts for automatic transactions** form. (Click **General ledger** \> **Setup** \> **Posting** \> **Accounts for automatic transactions**.)

  - If the cash discount administration setting is **Unspecific** and the cash discount is posted in the same legal entity as the overpayment (the legal entity of the payment and the legal entity of the invoice are the same), the cash discount account is adjusted. For example, if an invoice for 100.00 with an available cash discount of 3.00 is settled with a payment for 98.00, the cash discount account is adjusted for 1.00. The net discount amount is 2.00.

  - If the cash discount administration setting is **Unspecific**, the cash discount is posted in the same legal entity as the overpayment, and the overpayment or underpayment is settled with multiple invoices with cash discounts, the cash discount account for the last invoice is adjusted.

If the cash discount administration selection is **Unspecific**, unspecific payment settlement rules apply only in the following situations:

  - There is an overpayment.

  - The overpayment is settled with one or more invoices that has a cash discount.

  - The cash discount is posted in the same legal entity as the overpayment.

In all other situations, overpayments or underpayments are posted to the automatic account for **Customer cash discount**, **Vendor cash discount**, or **Penny difference in accounting currency**.

## Sales tax

Sales tax transactions remain in the legal entity where they were originally posted.

If sales tax was posted for a prepayment, the cross-company settlement reverses the sales tax on the prepayment in the legal entity of the prepayment. The taxes in the legal entity of the invoice remain in the legal entity of the invoice.

## Financial dimensions

For customer payments, the due-to and due-from transactions in the legal entity of the payment use the financial dimensions that are specified for the accounts receivable summary account from the payment that is being settled. In the legal entity of the invoice, due-to and due-from transactions use the financial dimensions that are specified for the accounts receivable summary account from the invoice that is being settled.

For vendor payments, the due-to and due-from transactions in the legal entity of the payment use the financial dimensions that are specified for the accounts payable summary account from the payment that is being settled. In the legal entity of the invoice, due-to and due-from transactions use the financial dimensions that are specified for the accounts payable summary account from the invoice that is being settled.

## Withholding tax

The vendor account that is associated with the invoice is used to determine whether withholding tax should be calculated. If withholding tax applies, it is calculated in the legal entity that is associated with the invoice. If the legal entities use different currencies, the exchange rate from the legal entity that is associated with the invoice is used.

## See also

[About centralized customer payments](about-centralized-customer-payments.md)

[About centralized vendor payments](about-centralized-vendor-payments.md)

[Scenario: Single-company and cross-company payment settlements](scenario-single-company-and-cross-company-payment-settlements.md)

[Set up centralized customer payments](set-up-centralized-customer-payments.md)

[Set up centralized vendor payments](set-up-centralized-vendor-payments.md)

[Settle open transactions - customer (form)](https://technet.microsoft.com/en-us/library/aa558602\(v=ax.60\))

[Settle open transactions - vendor (form)](https://technet.microsoft.com/en-us/library/aa619609\(v=ax.60\))

  


