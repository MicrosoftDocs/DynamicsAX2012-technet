---
title: 'Scenario: Cash discount handling for overpayments'
TOCTitle: 'Scenario: Cash discount handling for overpayments'
ms:assetid: 15ca32c1-9e68-43a0-8c0d-09cfbd53d2e2
ms:mtpsurl: https://technet.microsoft.com/library/Hh545514(v=AX.60)
ms:contentKeyID: 37832491
author: Khairunj
ms.date: 11/14/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Scenario: Cash discount handling for overpayments 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To specify how an obtainable cash discount difference is treated when an invoice is over paid, use the **Cash discount administration** and **Maximum overpayment or underpayment** fields in the **Accounts receivable parameters** form. An invoice is considered over paid when the payment amount is greater than the invoice amount less the cash discount.

In the following example, the customer has overpaid the invoice by 0.50.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Invoice total</p></th>
<th><p>Cash discount available</p></th>
<th><p>Amount to be paid, which includes the cash discount</p></th>
<th><p>Amount the customer actually pays</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>105.00</p></td>
<td><p>10.50</p></td>
<td><p>94.50</p></td>
<td><p>95.00</p></td>
</tr>
</tbody>
</table>


## Cash discount administration option: Specific

The full cash discount is taken when the **Specific** field is selected in the **Accounts for automatic transactions** form. The overpayment amount is either posted to a cash discount difference ledger account or remains a balance on the customer’s account. This is determined by whether the overpayment amount is between 0.00 and the amount that is entered in the **Maximum overpayment or underpayment** field or if the overpayment amount is over the **Maximum overpayment or underpayment** amount.

**Scenario 1:** Overpayment amount is between 0.00 and the maximum overpayment or underpayment. An invoice is entered for 105.00 with a cash discount available if the invoice is paid within seven days.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Invoice total</p></th>
<th><p>Cash discount available</p></th>
<th><p>Amount to be paid, which includes the cash discount</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>105.00</p></td>
<td><p>10.50</p></td>
<td><p>94.50</p></td>
</tr>
</tbody>
</table>


The customer submits a payment for 95.00. The payment is settled against the invoice for 105.00. After the invoice and payment are settled, the following transactions will be created in Account receivable for the customer.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Transaction</p></th>
<th><p>Amount</p></th>
<th><p>Balance</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Invoice</p></td>
<td><p>105.00</p></td>
<td><p>0.00</p></td>
</tr>
<tr class="even">
<td><p>Payment</p></td>
<td><p>-95.00</p></td>
<td><p>0.00</p></td>
</tr>
<tr class="odd">
<td><p>Cash discount</p></td>
<td><p>-10.50</p></td>
<td><p>0.00</p></td>
</tr>
</tbody>
</table>


The following accounting entries are generated for the payment and settlement.

**Payment**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account</p></th>
<th><p>Debit amount</p></th>
<th><p>Credit amount</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Cash</p></td>
<td><p>95.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Accounts receivable</p></td>
<td><p></p></td>
<td><p>95.00</p></td>
</tr>
</tbody>
</table>


**Settlement**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account</p></th>
<th><p>Debit amount</p></th>
<th><p>Credit amount</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>The account that is specified in the Main account for customer discounts field in the Cash discounts form</p></td>
<td><p>10.50</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Accounts receivable</p></td>
<td><p></p></td>
<td><p>10.50</p></td>
</tr>
<tr class="odd">
<td><p>The account that is specified in the Customer cash discount field in the Account for automatic transactions form</p></td>
<td><p></p></td>
<td><p>0.50</p></td>
</tr>
<tr class="even">
<td><p>Accounts receivable</p></td>
<td><p>0.50</p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


**Scenario 2:** The overpayment amount exceeds the maximum overpayment or underpayment amount. An invoice is entered for 105.00, with a cash discount available if the invoice is paid within seven days.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Invoice total</p></th>
<th><p>Cash discount available</p></th>
<th><p>Amount to be paid, which includes the cash discount</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>105.00</p></td>
<td><p>10.50</p></td>
<td><p>94.50</p></td>
</tr>
</tbody>
</table>


The customer submits a payment for 95.00. The payment is settled against the invoice for 105.00. After the invoice and payment are settled, the following transactions will be created in Account receivable for the customer.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Transaction</p></th>
<th><p>Amount</p></th>
<th><p>Balance</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Invoice</p></td>
<td><p>105.00</p></td>
<td><p>0.00</p></td>
</tr>
<tr class="even">
<td><p>Payment</p></td>
<td><p>-95.00</p></td>
<td><p>-0.50</p></td>
</tr>
<tr class="odd">
<td><p>Cash discount</p></td>
<td><p>-10.50</p></td>
<td><p>0.00</p></td>
</tr>
</tbody>
</table>


The overpayment amount of 0.50 will remain as an open balance on the payment and can be settled against another invoice.

The following accounting entries are generated for the payment and settlement.

**Payment**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account</p></th>
<th><p>Debit amount</p></th>
<th><p>Credit amount</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Cash</p></td>
<td><p>95.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Accounts receivable</p></td>
<td><p></p></td>
<td><p>95.00</p></td>
</tr>
</tbody>
</table>


**Settlement**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account</p></th>
<th><p>Debit amount</p></th>
<th><p>Credit amount</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>The account that is specified in the Main account for customer discounts field in the Cash discounts form</p></td>
<td><p>10.50</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Accounts receivable</p></td>
<td><p></p></td>
<td><p>10.50</p></td>
</tr>
</tbody>
</table>


## Cash discount administration option: Unspecific

In the **Accounts for automatic transactions** form, when **Unspecific** is selected in the **Cash discount administration** field, the cash discount amount is reduced by the overpayment amount. This is true regardless if the overpayment amount is over or under the amount entered in the **Maximum overpayment or underpayment** field.

**Scenario 3:** An invoice is entered for 105.00, with a cash discount available if paid within seven days.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Invoice total</p></th>
<th><p>Cash discount available</p></th>
<th><p>Amount to be paid, which includes the cash discount</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>105.00</p></td>
<td><p>10.50</p></td>
<td><p>94.50</p></td>
</tr>
</tbody>
</table>


The customer submits a payment for 95.00. The payment is settled against the invoice for 105.00. After the invoice and payment are settled, the following transactions will be created in Account receivable for the customer.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Transaction</p></th>
<th><p>Amount</p></th>
<th><p>Balance</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Invoice</p></td>
<td><p>105.00</p></td>
<td><p>0.00</p></td>
</tr>
<tr class="even">
<td><p>Payment</p></td>
<td><p>-95.00</p></td>
<td><p>-0.00</p></td>
</tr>
<tr class="odd">
<td><p>Cash discount</p></td>
<td><p>-10.00</p></td>
<td><p>0.00</p></td>
</tr>
</tbody>
</table>


The cash discount amount is reduced from 10.50 to 10.00. The payment and invoice are considered settled.

**Payment**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account</p></th>
<th><p>Debit amount</p></th>
<th><p>Credit amount</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Cash</p></td>
<td><p>95.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Accounts receivable</p></td>
<td><p></p></td>
<td><p>95.00</p></td>
</tr>
</tbody>
</table>


**Settlement**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account</p></th>
<th><p>Debit amount</p></th>
<th><p>Credit amount</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>The account that is specified in the Main account for customer discounts field in the Cash discounts form</p></td>
<td><p>10.50</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Accounts receivable</p></td>
<td><p></p></td>
<td><p>10.50</p></td>
</tr>
</tbody>
</table>


## See also

[Accounts receivable parameters (form)](https://technet.microsoft.com/library/aa576993\(v=ax.60\))

[About parameters for settlements in Accounts receivable](about-parameters-for-settlements-in-accounts-receivable.md)

[Scenario: Settle a customer payment with an invoice](scenario-settle-a-customer-payment-with-an-invoice.md)

[Scenario: Automatic settlement and prioritization](scenario-automatic-settlement-and-prioritization.md)

[Scenario: Settle a partial customer payment and settle the final payment in full before the discount date](scenario-settle-a-partial-customer-payment-and-settle-the-final-payment-in-full-before-the-discount-date.md)

[Scenario: Settle a partial customer payment before the discount date with a final payment after the discount date](scenario-settle-a-partial-customer-payment-before-the-discount-date-with-a-final-payment-after-the-discount-date.md)

[Scenario: Settle a partial customer payment that has multiple discount periods](scenario-settle-a-partial-customer-payment-that-has-multiple-discount-periods.md)

[Scenario: Use one customer payment to settle multiple invoices that span multiple discount periods](scenario-use-one-customer-payment-to-settle-multiple-invoices-that-span-multiple-discount-periods.md)

[Scenario: Settle a partial customer payment that has discounts on credit notes](scenario-settle-a-partial-customer-payment-that-has-discounts-on-credit-notes.md)

  


