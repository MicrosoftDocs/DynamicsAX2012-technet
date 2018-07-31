---
title: 'Scenario: Settle a customer payment with an invoice'
TOCTitle: 'Scenario: Settle a customer payment with an invoice'
ms:assetid: eace0014-819e-482d-8461-0d699f3879d1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh545537(v=AX.60)
ms:contentKeyID: 37832547
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Scenario: Settle a customer payment with an invoice 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This scenario illustrates three simple examples of a settlement in which one payment is settled with one or more invoices. For more information, see [Key tasks: Customer payments and settlements](key-tasks-customer-payments-and-settlements.md), [About parameters for settlements in Accounts receivable](about-parameters-for-settlements-in-accounts-receivable.md), and [Accounts receivable parameters (form)](https://technet.microsoft.com/en-us/library/aa576993\(v=ax.60\)).

## Prerequisites

Fabrikam has sold products to customer 4050, Contoso, two times, and has also invoiced the customer two times. As of January 26, Contoso’s balance is 600.00.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Invoice number</p></th>
<th><p>Invoice date</p></th>
<th><p>Invoice amount</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>0100_FTI</p></td>
<td><p>January 15</p></td>
<td><p>100.00</p></td>
</tr>
<tr class="even">
<td><p>0200_FTI</p></td>
<td><p>January 25</p></td>
<td><p>500.00</p></td>
</tr>
</tbody>
</table>


## Option 1: Enter and settle a payment with transactions

On February 1, Fabrikam receives a payment from Contoso for 100.00. Arnie settles this payment with the first invoice, 0100\_FTI, by following these steps.

1.  Open the Accounts receivable **Payment journal** form, create a journal, and then click **Enter customer payments**.

2.  In the **Enter customer payment information** field group, enter the payment information.

3.  In the **Select to pay** grid, select invoice 0100\_FTI.

4.  Click **Save in journal**.

5.  Close the form.

6.  In the **Payment journal** form, click **Post** \> **Post** to post the payment journal.

Contoso’s balance is now 500.00.

## Option 2: Enter and settle a payment for a single invoice in a payment journal

On February 1, Fabrikam receives a payment from Contoso for 500.00. Arnie settles this payment with the second invoice, 0200\_FTI, by following these steps.

1.  Open the Accounts receivable **Payment journal** form, create a journal, and then click **Lines**.

2.  In the **Invoice** field, enter 0200\_FTI. Information about the customer is displayed automatically.

3.  Click **Post** \> **Post** to post the payment journal.

Contoso’s balance is now 100.00.

## Option 3: Enter and settle a payment for multiple invoices in a payment journal

On February 1, Fabrikam receives a payment from Contoso for 600.00. Arnie settles this payment with invoices 0100\_FTI and 0200\_FTI by following these steps.

1.  Open the Accounts receivable **Payment journal** form, create a journal, and then click **Lines**.

2.  In the **Account** field, enter Contoso’s account, 4050.

3.  Click **Functions** \> **Settlement**.

4.  In the **Settle open transactions** form, select the **Mark** check box on the line for both the 0100\_FTI and 0200\_FTI customer invoices.

5.  Close the **Settle open transactions** form.

6.  Click **Post** \> **Post** to post the payment journal.

Contoso’s balance is now 0.00.

## See also

[Key tasks: Customer payments and settlements](key-tasks-customer-payments-and-settlements.md)

[Accounts receivable parameters (form)](https://technet.microsoft.com/en-us/library/aa576993\(v=ax.60\))

[About parameters for settlements in Accounts receivable](about-parameters-for-settlements-in-accounts-receivable.md)

[Scenario: Settle a customer payment with an invoice](scenario-settle-a-customer-payment-with-an-invoice.md)

[Scenario: Automatic settlement and prioritization](scenario-automatic-settlement-and-prioritization.md)

[Scenario: Cash discount handling for overpayments](scenario-cash-discount-handling-for-overpayments.md)

[Scenario: Settle a partial customer payment and settle the final payment in full before the discount date](scenario-settle-a-partial-customer-payment-and-settle-the-final-payment-in-full-before-the-discount-date.md)

[Scenario: Settle a partial customer payment before the discount date with a final payment after the discount date](scenario-settle-a-partial-customer-payment-before-the-discount-date-with-a-final-payment-after-the-discount-date.md)

[Scenario: Settle a partial customer payment that has multiple discount periods](scenario-settle-a-partial-customer-payment-that-has-multiple-discount-periods.md)

[Scenario: Use one customer payment to settle multiple invoices that span multiple discount periods](scenario-use-one-customer-payment-to-settle-multiple-invoices-that-span-multiple-discount-periods.md)

[Scenario: Settle a partial customer payment that has discounts on credit notes](scenario-settle-a-partial-customer-payment-that-has-discounts-on-credit-notes.md)

  


