---
title: About centralized vendor payments
TOCTitle: About centralized vendor payments
ms:assetid: 1c171d11-5b5e-45dd-92d1-87d4a7391a2b
ms:mtpsurl: https://technet.microsoft.com/library/Gg230974(v=AX.60)
ms:contentKeyID: 36056132
author: Khairunj
ms.author: daxcpft
ms.date: 05/02/2014
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
- vendor payments
- invoice company
- invoice legal entity
- payment company
- operating
- payment legal entity
- vendor payment
audience: Application User
ms.search.region: Global
---

# About centralized vendor payments 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Organizations that include multiple legal entities can create and manage payments using a legal entity that handles all payments. This eliminates the need to enter the same transaction in multiple legal entities and saves time by streamlining the payment proposal process, the settlement process, open transaction editing, and closed transaction editing for cross-company payments.

In a centralized payments organization, there are many legal entities for operations, and each operating legal entity manages its own invoices payable information. Payments for all the operating legal entities are generated from a single legal entity, which is called the legal entity of the payment. During the settlement process, the applicable due-to and due-from transactions are generated. You can specify which legal entity in the organization will receive the realized gain or realized loss transactions, and how cash discount transactions that are related to a cross-company payment are handled.

The following examples illustrate how posting is handled in various scenarios. The following configuration is assumed for all these examples:

  - The legal entities are Fabrikam, Fabrikam East, and Fabrikam West. Fabrikam is the legal entity of the payment.

  - The **Post cash discount** field in the **Intercompany accounting** form is set to **Legal entity of the invoice**.

  - The **Post currency exchange gain or loss** field in the **Intercompany accounting** form is set to **Legal entity of the payment**.

  - Fabrikam maintains a single global address book record, directory ID 1050, for Fourth Coffee. This global address book record is mapped to a separate vendor account in each legal entity.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Directory ID</p></th>
<th><p>Vendor account</p></th>
<th><p>Name</p></th>
<th><p>Legal entity</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>1050</p></td>
<td><p>3004</p></td>
<td><p>Fourth Coffee</p></td>
<td><p>Fabrikam</p></td>
</tr>
<tr class="even">
<td><p>1050</p></td>
<td><p>100</p></td>
<td><p>Fourth Coffee</p></td>
<td><p>Fabrikam East</p></td>
</tr>
<tr class="odd">
<td><p>1050</p></td>
<td><p>3004</p></td>
<td><p>Fourth Coffee</p></td>
<td><p>Fabrikam West</p></td>
</tr>
</tbody>
</table>


## Example 1: Vendor payment of invoice from another legal entity

Fabrikam East has an open invoice for vendor account 100, Fourth Coffee. Fabrikam enters and posts a payment to Fabrikam vendor account 3004, Fourth Coffee. The payment is settled with the open invoice.

## Invoice is posted in Fabrikam East for vendor 100

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
<td><p>Expense (Fabrikam East)</p></td>
<td><p>600.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Accounts payable (Fabrikam East)</p></td>
<td><p></p></td>
<td><p>600.00</p></td>
</tr>
</tbody>
</table>


## Payment is generated and posted in Fabrikam for vendor 3004

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
<td><p>Accounts payable (Fabrikam)</p></td>
<td><p>600.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Cash (Fabrikam)</p></td>
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
<td><p>Due from Fabrikam East (Fabrikam)</p></td>
<td><p>600.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Accounts payable (Fabrikam)</p></td>
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
<td><p>Accounts payable (Fabrikam East)</p></td>
<td><p>600.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Due to Fabrikam (Fabrikam East)</p></td>
<td><p></p></td>
<td><p>600.00</p></td>
</tr>
</tbody>
</table>


## Example 2: Vendor payment of invoice from another legal entity with cash discount

Fabrikam East has an open invoice for vendor 100, Fourth Coffee. The invoice has a 20.00 cash discount available. Fabrikam enters and posts a payment of 580.00 for Fabrikam vendor 3004, Fourth Coffee. The payment is settled with the open Fabrikam East invoices. The cash discount is posted to the legal entity of the invoice, Fabrikam East.

## Invoice is posted in Fabrikam East for Fabrikam East vendor 100

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
<td><p>Expense (Fabrikam East)</p></td>
<td><p>600.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Accounts payable (Fabrikam East)</p></td>
<td><p></p></td>
<td><p>600.00</p></td>
</tr>
</tbody>
</table>


## Payment is generated and posted in Fabrikam for Fabrikam vendor 3004

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
<td><p>Accounts payable (Fabrikam)</p></td>
<td><p>580.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Cash (Fabrikam)</p></td>
<td><p></p></td>
<td><p>580.00</p></td>
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
<td><p>Due from Fabrikam East (Fabrikam)</p></td>
<td><p>580.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Accounts payable (Fabrikam)</p></td>
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
<td><p>Accounts payable (Fabrikam East)</p></td>
<td><p>580.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Due to Fabrikam (Fabrikam East)</p></td>
<td><p></p></td>
<td><p>580.00</p></td>
</tr>
<tr class="odd">
<td><p>Accounts payable (Fabrikam East)</p></td>
<td><p>20.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Cash discount (Fabrikam East)</p></td>
<td><p></p></td>
<td><p>20.00</p></td>
</tr>
</tbody>
</table>


## Example 3: Vendor payment of invoice from another legal entity with realized exchange rate loss

Fabrikam East has an open invoice for vendor 100, Fourth Coffee. Fabrikam enters and posts a payment for Fabrikam vendor 3004, Fourth Coffee. The payment is settled with the open Fabrikam East invoice. A currency exchange loss transaction is generated during the settlement process.

  - Exchange rate for EUR to USD as of the invoice date: 1.2062

  - Exchange rate for EUR to USD as of the payment date: 1.2277

## Invoice is posted in Fabrikam East for Fabrikam East vendor 100

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
<td><p>Expense (Fabrikam East)</p></td>
<td><p>600.00 EUR / 723.72 USD</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Accounts payable (Fabrikam East)</p></td>
<td><p></p></td>
<td><p>600.00 EUR / 723.72 USD</p></td>
</tr>
</tbody>
</table>


## Payment is generated and posted in Fabrikam for Fabrikam vendor 3004

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
<td><p>Accounts payable (Fabrikam)</p></td>
<td><p>600.00 EUR / 736.62 USD</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Cash (Fabrikam)</p></td>
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
<td><p>Due from Fabrikam East (Fabrikam)</p></td>
<td><p>600.00 EUR / 736.62 USD</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Accounts payable (Fabrikam)</p></td>
<td><p></p></td>
<td><p>600.00 EUR / 736.62 USD</p></td>
</tr>
<tr class="odd">
<td><p>Realized loss (Fabrikam)</p></td>
<td><p>0.00 EUR / 12.90 USD</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Due from Fabrikam East (Fabrikam)</p></td>
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
<td><p>Accounts payable (Fabrikam East)</p></td>
<td><p>600.00 EUR / 736.62 USD</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Due to Fabrikam (Fabrikam East)</p></td>
<td><p></p></td>
<td><p>600.00 EUR / 736.62 USD</p></td>
</tr>
<tr class="odd">
<td><p>Due to Fabrikam (Fabrikam East)</p></td>
<td><p>0.00 EUR / 12.90 USD</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Accounts payable (Fabrikam East)</p></td>
<td><p></p></td>
<td><p>0.00 EUR / 12.90 USD</p></td>
</tr>
</tbody>
</table>


## Example 4: Vendor payment of invoice from another legal entity with cash discount and realized exchange rate loss

Fabrikam East has an open invoice for vendor 100, Fourth Coffee. The invoice has a cash discount available and a sales tax transaction is generated. Fabrikam posts a payment for Fabrikam vendor 3004, Fourth Coffee. The payment is settled with the open Fabrikam East invoice. A currency exchange loss transaction is generated during the settlement process. The cash discount is posted to the legal entity of the invoice (Fabrikam East) and the currency exchange loss is posted to the legal entity of the payment (Fabrikam).

  - Exchange rate for EUR to USD as of the invoice date: 1.2062

  - Exchange rate for EUR to USD as of the payment date: 1.2277

## Invoice is posted and a tax transaction is generated in Fabrikam East for vendor 100

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
<td><p>Expense (Fabrikam East)</p></td>
<td><p>564.07 EUR / 680.38 USD</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Sales tax (Fabrikam East)</p></td>
<td><p>35.93 EUR / 43.34 USD</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Accounts payable (Fabrikam East)</p></td>
<td><p></p></td>
<td><p>600.00 EUR / 723.72 USD</p></td>
</tr>
</tbody>
</table>


## Payment is generated and posted in Fabrikam for vendor 3004

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
<td><p>Accounts payable (Fabrikam)</p></td>
<td><p>588.72 EUR / 722.77 USD</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Cash (Fabrikam East)</p></td>
<td><p></p></td>
<td><p>588.72 EUR / 722.77 USD</p></td>
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
<td><p>Due from Fabrikam East (Fabrikam)</p></td>
<td><p>588.72 EUR / 722.77 USD</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Accounts payable (Fabrikam)</p></td>
<td><p></p></td>
<td><p>588.72 EUR / 722.77 USD</p></td>
</tr>
<tr class="odd">
<td><p>Realized loss (Fabrikam)</p></td>
<td><p>0.00 EUR / 12.66 USD</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Due from Fabrikam East (Fabrikam)</p></td>
<td><p></p></td>
<td><p>0.00 EUR / 12.66 USD</p></td>
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
<td><p>Accounts payable (Fabrikam East)</p></td>
<td><p>588.72 EUR / 722.77 USD</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Due to Fabrikam (Fabrikam East)</p></td>
<td><p></p></td>
<td><p>588.72 EUR / 722.77 USD</p></td>
</tr>
<tr class="odd">
<td><p>Due to Fabrikam (Fabrikam East</p></td>
<td><p>0.00 EUR / 12.66 USD</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Accounts payable (Fabrikam East)</p></td>
<td><p></p></td>
<td><p>0.00 EUR / 12.66 USD</p></td>
</tr>
<tr class="odd">
<td><p>Accounts payable (Fabrikam East)</p></td>
<td><p>11.28 EUR / 13.61 USD</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Cash discount (Fabrikam East)</p></td>
<td><p></p></td>
<td><p>11.28 EUR / 13.61 USD</p></td>
</tr>
</tbody>
</table>


## Example 5: Vendor credit note with primary payment

Fabrikam generates a payment of 75.00 for vendor 3004, Fourth Coffee. The payment is settled with an open invoice for Fabrikam West vendor 3004 and an open credit note for Fabrikam East vendor 100. The payment is selected as the primary payment in the **Settle open transactions** form.

## Invoice is posted to Fabrikam West for vendor 3004

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
<td><p>Expense (Fabrikam West)</p></td>
<td><p>100.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Accounts payable (Fabrikam West)</p></td>
<td><p></p></td>
<td><p>100.00</p></td>
</tr>
</tbody>
</table>


## Credit note is posted to Fabrikam East for vendor 100

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
<td><p>Accounts payable (Fabrikam East)</p></td>
<td><p>25.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Purchase returns (Fabrikam East)</p></td>
<td><p></p></td>
<td><p>25.00</p></td>
</tr>
</tbody>
</table>


## Payment is posted to Fabrikam for vendor 3004

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
<td><p>Accounts payable (Fabrikam)</p></td>
<td><p>75.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Cash (Fabrikam)</p></td>
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
<td><p>Accounts payable (Fabrikam)</p></td>
<td><p>25.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Due to Fabrikam East (Fabrikam)</p></td>
<td><p></p></td>
<td><p>25.00</p></td>
</tr>
<tr class="odd">
<td><p>Due from Fabrikam West (Fabrikam)</p></td>
<td><p>100.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Accounts payable (Fabrikam)</p></td>
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
<td><p>Due from Fabrikam (Fabrikam East)</p></td>
<td><p>25.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Accounts payable (Fabrikam East)</p></td>
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
<td><p>Accounts payable (Fabrikam West)</p></td>
<td><p>100.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Due to Fabrikam (Fabrikam West)</p></td>
<td><p></p></td>
<td><p>100.00</p></td>
</tr>
</tbody>
</table>


## Example 6: Vendor credit note without primary payment

Fabrikam generates a payment of 75.00 for vendor 3004, Fourth Coffee. The payment is settled with an open invoice for Fabrikam West vendor 3004 and an open credit note for Fabrikam East vendor 100. The payment is not selected as the primary payment in the **Settle open transactions** form.

## Invoice is posted to Fabrikam West for vendor 3004

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
<td><p>Expense (Fabrikam West)</p></td>
<td><p>100.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Accounts payable (Fabrikam West)</p></td>
<td><p></p></td>
<td><p>100.00</p></td>
</tr>
</tbody>
</table>


## Credit note is posted to Fabrikam East for vendor 100

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
<td><p>Accounts payable (Fabrikam East)</p></td>
<td><p>25.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Purchase returns (Fabrikam East)</p></td>
<td><p></p></td>
<td><p>25.00</p></td>
</tr>
</tbody>
</table>


## Payment is posted to Fabrikam for vendor 3004

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
<td><p>Accounts payable (Fabrikam)</p></td>
<td><p>75.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Cash (Fabrikam)</p></td>
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
<td><p>Due from Fabrikam West (Fabrikam)</p></td>
<td><p>75.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Accounts payable (Fabrikam)</p></td>
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
<td><p>Due from Fabrikam West (Fabrikam East)</p></td>
<td><p>25.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Accounts payable (Fabrikam East)</p></td>
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
<td><p>Accounts payable (Fabrikam West)</p></td>
<td><p>75.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Due to Fabrikam (Fabrikam West)</p></td>
<td><p></p></td>
<td><p>75.00</p></td>
</tr>
<tr class="odd">
<td><p>Accounts payable (Fabrikam West)</p></td>
<td><p>25.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Due to Fabrikam East (Fabrikam West)</p></td>
<td><p></p></td>
<td><p>25.00</p></td>
</tr>
</tbody>
</table>


## See also

[Set up centralized vendor payments](set-up-centralized-vendor-payments.md)

[Scenario: Single-company and cross-company payment settlements](scenario-single-company-and-cross-company-payment-settlements.md)

[About cross-company payment settlements](about-cross-company-payment-settlements.md)

[Print copies of payments as non-negotiable checks](print-copies-of-payments-as-non-negotiable-checks.md)

  


