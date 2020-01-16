---
title: About centralized customer payments
TOCTitle: About centralized customer payments
ms:assetid: 870990b7-23a1-464a-8d11-a86ef544c3dd
ms:mtpsurl: https://technet.microsoft.com/library/Gg213183(v=AX.60)
ms:contentKeyID: 36058420
author: Khairunj
ms.date: 07/01/2015
mtps_version: v=AX.60
f1_keywords:
- company
- central company
- central legal entity
- centralized
- cross-company
- due-from
- due-to
- intercompany
- invoice company
- invoice legal entity
- payment company
- operating
- payment legal entity
- customer payment
- customer payments
audience: Application User
ms.search.region: Global
---

# About centralized customer payments 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Organizations that include multiple legal entities can create and manage payments by using a legal entity that handles all payments. This eliminates the need to enter the same transaction in multiple legal entities and saves time by streamlining the payment proposal process, the settlement process, open transaction editing, and closed transaction editing for centralized payments.

In a centralized payment organization, there are many legal entities for operations, and each operating legal entity manages its own invoices receivable information. Payments for all the operating legal entities are received by a single legal entity, which is called the legal entity of the payment. During the settlement process, the applicable due-to and due-from transactions are generated. You can specify which legal entity in the organization will receive the realized gain or realized loss transactions, and how cash discount transactions that are related to a centralized payment are handled.

The following examples illustrate how posting is handled in various scenarios. The following configuration is assumed for all these examples:

  - The legal entities are Fabrikam, Fabrikam East, and Fabrikam West. Fabrikam is the legal entity of the payment.

  - The **Post cash discount** field in the **Intercompany accounting** form is set to **Legal entity of the invoice**.

  - The **Post currency exchange gain or loss** field in the **Intercompany accounting** form is set to **Legal entity of the payment**.

  - Fabrikam maintains a single global address book record, address book ID 4050, for Northwind Traders. This global address book record is mapped to a separate customer account in each legal entity.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Address book ID</p></th>
<th><p>Customer account</p></th>
<th><p>Name</p></th>
<th><p>Legal entity</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>4050</p></td>
<td><p>4000</p></td>
<td><p>Northwind Traders</p></td>
<td><p>Fabrikam</p></td>
</tr>
<tr class="even">
<td><p>4050</p></td>
<td><p>4000</p></td>
<td><p>Northwind Traders</p></td>
<td><p>Fabrikam East</p></td>
</tr>
<tr class="odd">
<td><p>4050</p></td>
<td><p>10000</p></td>
<td><p>Northwind Traders</p></td>
<td><p>Fabrikam West</p></td>
</tr>
</tbody>
</table>


## Example 1: Customer payment of invoice from another legal entity

Fabrikam receives a payment of 600.00 for Fabrikam customer account 4000, Northwind Traders. The payment is settled with an open invoice for customer account 4000 in Fabrikam East.

## Invoice is posted in Fabrikam East for customer 4000

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
<td><p>Accounts receivable (Fabrikam East)</p></td>
<td><p>600.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Sales (Fabrikam East)</p></td>
<td><p></p></td>
<td><p>600.00</p></td>
</tr>
</tbody>
</table>


## Payment is received and posted in Fabrikam for customer 4000

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
<td><p>Cash (Fabrikam)</p></td>
<td><p>600.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Accounts receivable (Fabrikam)</p></td>
<td><p></p></td>
<td><p>600.00</p></td>
</tr>
</tbody>
</table>


## Fabrikam payment is settled with Fabrikam East invoice

Fabrikam posting

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
<td><p>Accounts receivable (Fabrikam)</p></td>
<td><p>600.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Due to Fabrikam East (Fabrikam)</p></td>
<td><p></p></td>
<td><p>600.00</p></td>
</tr>
</tbody>
</table>


Fabrikam East posting

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
<td><p>Due from Fabrikam (Fabrikam East)</p></td>
<td><p>600.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Accounts receivable (Fabrikam East)</p></td>
<td><p></p></td>
<td><p>600.00</p></td>
</tr>
</tbody>
</table>


## Example 2: Customer payment of invoice from another legal entity with cash discount

Fabrikam receives a payment of 580.00 for Fabrikam customer 4000, Northwind Traders. Fabrikam East has an open invoice for customer 4000, Northwind Traders. The invoice has a 20.00 cash discount available. The payment is settled with the open Fabrikam East invoices. The cash discount is posted to the legal entity of the invoice, Fabrikam East.

## Invoice is posted in Fabrikam East for Fabrikam East customer 4000

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
<td><p>Accounts receivable (Fabrikam East)</p></td>
<td><p>600.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Sales (Fabrikam East)</p></td>
<td><p></p></td>
<td><p>600.00</p></td>
</tr>
</tbody>
</table>


## Payment is received and posted in Fabrikam for Fabrikam customer 4000

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
<td><p>Cash (Fabrikam)</p></td>
<td><p>600.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Accounts receivable (Fabrikam)</p></td>
<td><p></p></td>
<td><p>600.00</p></td>
</tr>
</tbody>
</table>


## Fabrikam payment is settled with Fabrikam East invoice

Fabrikam posting

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
<td><p>Accounts receivable (Fabrikam)</p></td>
<td><p>580.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Due to Fabrikam East (Fabrikam)</p></td>
<td><p></p></td>
<td><p>580.00</p></td>
</tr>
</tbody>
</table>


Fabrikam East posting

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
<td><p>Due from Fabrikam (Fabrikam East)</p></td>
<td><p>580.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Accounts receivable (Fabrikam East)</p></td>
<td><p></p></td>
<td><p>580.00</p></td>
</tr>
<tr class="odd">
<td><p>Cash discount (Fabrikam East)</p></td>
<td><p>20.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Accounts receivable (Fabrikam East)</p></td>
<td><p></p></td>
<td><p>20.00</p></td>
</tr>
</tbody>
</table>


## Example 3: Customer payment of invoice from another legal entity with realized exchange rate gain

Fabrikam receives a payment of 600.00 EUR for Fabrikam customer 4000. The payment is settled with an open invoice for customer 4000 in Fabrikam East. A currency exchange gain transaction is generated during the settlement process.

Exchange rate for EUR to USD as of the invoice date: 1.2062

Exchange rate for EUR to USD as of the payment date: 1.2277

## Invoice is posted in Fabrikam East for Fabrikam East customer 4000

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
<td><p>Accounts receivable (Fabrikam East)</p></td>
<td><p>600.00 EUR / 723.72 USD</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Sales (Fabrikam East)</p></td>
<td><p></p></td>
<td><p>600.00 EUR / 723.72 USD</p></td>
</tr>
</tbody>
</table>


## Payment is received and posted in Fabrikam for Fabrikam customer 4000

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
<td><p>Cash (Fabrikam)</p></td>
<td><p>600.00 EUR / 736.62 USD</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Accounts receivable (Fabrikam)</p></td>
<td><p></p></td>
<td><p>600.00 EUR / 736.62 USD</p></td>
</tr>
</tbody>
</table>


## Fabrikam payment is settled with Fabrikam East invoice

Fabrikam posting

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
<td><p>Accounts receivable (Fabrikam)</p></td>
<td><p>600.00 EUR / 736.62 USD</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Due to Fabrikam East (Fabrikam)</p></td>
<td><p></p></td>
<td><p>600.00 EUR / 736.62 USD</p></td>
</tr>
<tr class="odd">
<td><p>Due to Fabrikam East (Fabrikam)</p></td>
<td><p>0.00 EUR / 12.90 USD</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Realized gain (Fabrikam)</p></td>
<td><p></p></td>
<td><p>0.00 EUR / 12.90 USD</p></td>
</tr>
</tbody>
</table>


Fabrikam East posting

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
<td><p>Due from Fabrikam (Fabrikam East)</p></td>
<td><p>600.00 EUR / 736.62 USD</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Accounts receivable (Fabrikam East)</p></td>
<td><p></p></td>
<td><p>600.00 EUR / 736.62 USD</p></td>
</tr>
<tr class="odd">
<td><p>Accounts receivable (Fabrikam East)</p></td>
<td><p>0.00 EUR / 12.90 USD</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Due from Fabrikam (Fabrikam East)</p></td>
<td><p></p></td>
<td><p>0.00 EUR / 12.90 USD</p></td>
</tr>
</tbody>
</table>


## Example 4: Customer payment of invoice from another legal entity with cash discount and realized exchange rate gain

Fabrikam posts a payment for Fabrikam customer 4000, Northwind Traders, for an open invoice in Fabrikam East. The invoice has a cash discount available and a sales tax transaction is generated. The payment is settled with the open Fabrikam East invoice. A currency exchange gain transaction is generated during the settlement process. The cash discount is posted to the legal entity of the invoice (Fabrikam East) and the currency exchange gain is posted to the legal entity of the payment (Fabrikam).

Exchange rate for EUR to USD as of the invoice date: 1.2062

Exchange rate for EUR to USD as of the payment date: 1.2277

## Free text invoice is posted and a tax transaction is generated in Fabrikam East for customer 4000

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
<td><p>Accounts receivable (Fabrikam East)</p></td>
<td><p>638.22 EUR / 769.82 USD</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Sales (Fabrikam East)</p></td>
<td><p></p></td>
<td><p>600.00 EUR / 723.72 USD</p></td>
</tr>
<tr class="odd">
<td><p>Sales tax (Fabrikam East)</p></td>
<td><p></p></td>
<td><p>38.22 EUR / 46.10 USD</p></td>
</tr>
</tbody>
</table>


## Payment is received and posted in Fabrikam for customer 4000

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
<td><p>Cash (Fabrikam)</p></td>
<td><p>626.22 EUR / 768.81 USD</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Accounts receivable (Fabrikam)</p></td>
<td><p></p></td>
<td><p>626.22 EUR / 768.81 USD</p></td>
</tr>
</tbody>
</table>


## Fabrikam payment is settled with Fabrikam East invoice

Fabrikam posting

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
<td><p>Accounts receivable (Fabrikam)</p></td>
<td><p>626.22 EUR / 768.81 USD</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Due to Fabrikam East (Fabrikam)</p></td>
<td><p></p></td>
<td><p>626.22 EUR / 768.81 USD</p></td>
</tr>
<tr class="odd">
<td><p>Due to Fabrikam East (Fabrikam)</p></td>
<td><p>0.00 EUR / 13.46 USD</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Realized gain (Fabrikam)</p></td>
<td><p></p></td>
<td><p>0.00 EUR / 13.46 USD</p></td>
</tr>
</tbody>
</table>


Fabrikam East posting

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
<td><p>Due from Fabrikam (Fabrikam East)</p></td>
<td><p>626.22 EUR / 768.81 USD</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Accounts receivable (Fabrikam East)</p></td>
<td><p></p></td>
<td><p>626.22 EUR / 768.81 USD</p></td>
</tr>
<tr class="odd">
<td><p>Accounts receivable (Fabrikam East</p></td>
<td><p>0.00 EUR / 13.46 USD</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Due from Fabrikam (Fabrikam East)</p></td>
<td><p></p></td>
<td><p>0.00 EUR / 13.46 USD</p></td>
</tr>
<tr class="odd">
<td><p>Cash discount (Fabrikam East)</p></td>
<td><p>12.00 EUR / 14.47 USD</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Accounts receivable (Fabrikam East)</p></td>
<td><p></p></td>
<td><p>12.00 EUR / 14.47 USD</p></td>
</tr>
</tbody>
</table>


## Example 5: Customer credit note with primary payment

Fabrikam receives a payment of 75.00 from customer 4000, Northwind Traders. The payment is settled with an open invoice for Fabrikam West customer 10000 and an open credit note for Fabrikam East customer 4000. The payment is selected as the primary payment in the **Settle open transactions** form.

## Invoice is posted to Fabrikam West for customer 10000

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
<td><p>Accounts receivable (Fabrikam West)</p></td>
<td><p>100.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Sales (Fabrikam West)</p></td>
<td><p></p></td>
<td><p>100.00</p></td>
</tr>
</tbody>
</table>


## Credit note is posted to Fabrikam East for customer 4000

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
<td><p>Sales returns (Fabrikam East)</p></td>
<td><p>25.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Accounts receivable (Fabrikam East)</p></td>
<td><p></p></td>
<td><p>25.00</p></td>
</tr>
</tbody>
</table>


## Payment is posted to Fabrikam for customer 4000

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
<td><p>Cash (Fabrikam)</p></td>
<td><p>75.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Accounts receivable (Fabrikam)</p></td>
<td><p></p></td>
<td><p>75.00</p></td>
</tr>
</tbody>
</table>


## Fabrikam payment is settled with Fabrikam West invoice and Fabrikam East credit note

Fabrikam posting

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
<td><p>Due from Fabrikam East (Fabrikam)</p></td>
<td><p>25.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Accounts receivable (Fabrikam)</p></td>
<td><p></p></td>
<td><p>25.00</p></td>
</tr>
<tr class="odd">
<td><p>Accounts receivable (Fabrikam)</p></td>
<td><p>100.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Due to Fabrikam West (Fabrikam)</p></td>
<td><p></p></td>
<td><p>100.00</p></td>
</tr>
</tbody>
</table>


Fabrikam East posting

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
<td><p>Accounts receivable (Fabrikam East)</p></td>
<td><p>25.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Due to Fabrikam (Fabrikam East)</p></td>
<td><p></p></td>
<td><p>25.00</p></td>
</tr>
</tbody>
</table>


Fabrikam West posting

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
<td><p>Due from Fabrikam (Fabrikam West)</p></td>
<td><p>100.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Accounts receivable (Fabrikam West)</p></td>
<td><p></p></td>
<td><p>100.00</p></td>
</tr>
</tbody>
</table>


## Example 6: Customer credit note without primary payment

Fabrikam receives a payment of 75.00 from customer 4000, Northwind Traders. The payment is settled with an open invoice for Fabrikam West customer 10000 and an open credit note for Fabrikam East customer 4000. The payment is not selected as the primary payment in the **Settle open transactions** form.

## Invoice is posted to Fabrikam West for customer 10000

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
<td><p>Accounts receivable (Fabrikam West)</p></td>
<td><p>100.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Sales (Fabrikam West)</p></td>
<td><p></p></td>
<td><p>100.00</p></td>
</tr>
</tbody>
</table>


## Credit note is posted to Fabrikam East for customer 4000

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
<td><p>Sales returns (Fabrikam East)</p></td>
<td><p>25.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Accounts receivable (Fabrikam East)</p></td>
<td><p></p></td>
<td><p>25.00</p></td>
</tr>
</tbody>
</table>


## Payment is posted to Fabrikam for customer 4000

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
<td><p>Cash (Fabrikam)</p></td>
<td><p>75.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Accounts receivable (Fabrikam)</p></td>
<td><p></p></td>
<td><p>75.00</p></td>
</tr>
</tbody>
</table>


## Fabrikam payment is settled with Fabrikam West invoice and Fabrikam East credit note

Fabrikam posting

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
<td><p>Accounts receivable (Fabrikam)</p></td>
<td><p>75.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Due to Fabrikam West (Fabrikam)</p></td>
<td><p></p></td>
<td><p>75.00</p></td>
</tr>
</tbody>
</table>


Fabrikam East posting

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
<td><p>Accounts receivable (Fabrikam East)</p></td>
<td><p>25.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Due to Fabrikam West (Fabrikam East)</p></td>
<td><p></p></td>
<td><p>25.00</p></td>
</tr>
</tbody>
</table>


Fabrikam West posting

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
<td><p>Due from Fabrikam (Fabrikam West)</p></td>
<td><p>75.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Accounts receivable (Fabrikam West)</p></td>
<td><p></p></td>
<td><p>75.00</p></td>
</tr>
<tr class="odd">
<td><p>Due from Fabrikam East (Fabrikam West)</p></td>
<td><p>25.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Accounts receivable (Fabrikam West)</p></td>
<td><p></p></td>
<td><p>25.00</p></td>
</tr>
</tbody>
</table>


## See also

[Set up centralized customer payments](set-up-centralized-customer-payments.md)

[Scenario: Single-company and cross-company payment settlements](scenario-single-company-and-cross-company-payment-settlements.md)

[About cross-company payment settlements](about-cross-company-payment-settlements.md)

  


