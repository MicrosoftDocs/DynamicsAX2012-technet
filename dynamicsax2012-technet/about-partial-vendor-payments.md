---
title: About partial vendor payments
TOCTitle: About partial vendor payments
ms:assetid: 8e28b76c-050f-457d-9058-36bbaf72dccb
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh209359(v=AX.60)
ms:contentKeyID: 36058509
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- notes
- payments
- partial
- full
- payment
- settlement
- discount
- credit
- note
- overpayment
- overpayments
- underpayment
- underpayments
audience: Application User
ms.search.region: Global
---

# About partial vendor payments 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Sometimes you might make a payment to a vendor that is less than the amount of an invoice. You have multiple options for handling this situation. The options that are available to you depend on your configuration.

## Discount amounts

A vendor can offer you a discount for paying an invoice before the due date.

For example, you receive terms of payment that specify a 2% discount if the invoice is paid within 10 days of being issued. An invoice is posted for 100.00. If you make a payment of 98.00 within 10 days, you would enter a debit of 98.00 in a payment journal. The debit amount is shown in the **Amount to settle** field and 2.00 is shown in the **Cash discount amount** field in the **Settle open transactions** form.

## Partial payments with discounts

You might make a partial payment, with the intention of making an additional partial payment to fully settle the invoice.

For example, you receive a cash discount that specifies a 2% discount if the invoice is paid within 10 days of being issued. An invoice is posted for 100.00. If you make a payment of 49.00 within 10 days, you would enter a debit of 49.00 in a payment journal. The debit amount is shown in the **Amount to settle** field in the **Settle open transactions** form. If the **Calculate cash discounts for partial payments** check box in the **Accounts payable parameters** form is selected, the discount is automatically calculated. When you settle the partial payment in the **Settle open transactions** form, 1.00 is displayed in the **Cash discount amount to take** field. The discount amount is posted to a cash discount account.


> [!NOTE]
> <P>If you enter a partial payment and leave the full invoice amount in the <STRONG>Amount to settle</STRONG> field, the <STRONG>Cash discount amount to take</STRONG> field is automatically recalculated when you post the transactions.</P>



## Partial payments with multiple discount levels

You might make multiple partial payments, with the intention of taking the maximum discount that is available for the first partial payment, and a smaller discount for the subsequent partial payments.

For example, you receive a cash discount that specifies a 2% discount if the invoice is paid within 10 days of being issued. You also receive a 1% discount if the invoice is paid within 30 days. An invoice is posted for 100.00. If you make a payment of 49.00 within 10 days, you would enter a debit of 49.00 in a payment journal. The debit amount is shown in the **Amount to settle** field in the **Settle open transactions** form. If the **Calculate cash discounts for partial payments** check box in the **Accounts payable parameters** form is selected, the discount is automatically calculated. When you settle the partial payment in the **Settle open transactions** form, 1.00 is displayed in the **Cash discount amount to take** field. The discount amount is posted to a cash discount account.

If you make a payment for the remaining amount after 10 days but before 30 days after the invoice is issued, the available discount would be 1%. The available discount amount would be 0.50, which is 1% of the remaining amount, 50.00. You would enter a debit for 49.50 in a payment journal.

## Credit notes with discounts

You might return some of the items on an invoice and you receive a credit note. If a discount has previously been taken, you can subtract the value of the discount and receive a refund for the correct amount.

For example, you receive a cash discount that specifies a 2% discount if the invoice is paid within 10 days of being issued. An invoice for 100.00 is posted. If you return the goods and you receive a credit note, you can enter the credit note by entering a negative transaction with a value in the **Invoice** field in the **Journal voucher** form for an invoice journal. If the **Calculate cash discounts for credit notes** check box in the **Accounts payable parameters** form is selected, the discount is automatically calculated for the credit note. When you view the credit note in the **Settle open transactions** form, 98.00 is displayed in the **Amount to settle** field and -2.00 is displayed in the **Cash discount amount** field. The discount amount is posted to a cash discount account.

## Overpayment/underpayment amounts

You might make a payment and the remaining amount to settle is very small.

For example, you receive an invoice from a vendor for 1,000.00 and you pay 999.99. If the amount is less than the amount specified for overpayments or underpayments in the **Accounts payable parameters** form, the difference is posted to an overpayment/underpayment account.

## Full settlement

You might make a payment and there is a remaining amount to settle.

For example, an invoice is posted for 1,000.00. If you make a payment of 990.00, you would enter a debit of 990.00 in a payment journal. You can select the **Mark** check box in the **Settle open transactions** form and the invoice is considered fully settled. The 10.00 difference is posted to a cash discount account, as an additional discount amount.


> [!NOTE]
> <P>(AUT, CHE, DEU) Full settlement functionality is available only if the <STRONG>Full settlement</STRONG> configuration key is selected, the primary address of the legal entity is in Austria, Germany, or Switzerland, and you open the form from a payment journal.</P>



## See also

[Accounts payable parameters (form)](https://technet.microsoft.com/en-us/library/aa596348\(v=ax.60\))

[Settle open transactions - vendor (form)](https://technet.microsoft.com/en-us/library/aa619609\(v=ax.60\))

[Vendor payment proposal - Edit (form)](https://technet.microsoft.com/en-us/library/aa616323\(v=ax.60\))

[Print copies of payments as non-negotiable checks](print-copies-of-payments-as-non-negotiable-checks.md)

  


