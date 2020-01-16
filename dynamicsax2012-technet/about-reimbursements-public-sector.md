---
title: About reimbursements (Public sector)
TOCTitle: About reimbursements (Public sector)
ms:assetid: 9819a2ef-105a-48e8-bcd4-b54afb911e83
ms:mtpsurl: https://technet.microsoft.com/library/Hh334467(v=AX.60)
ms:contentKeyID: 36676451
ms.date: 05/01/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Denmark, France
---

# About reimbursements (Public sector) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Reimbursements are issued to customers who have overpaid, or customers who have been issued a credit and have an outstanding credit balance. (This can be accomplished by using a general ledger credit voucher or a credit note.) When customer credit transactions are processed for reimbursement, a reimbursement transaction is created for each unique customer balance posting type entry across the vouchers of the transactions. This process can create several reimbursement transactions for a single credit transaction. If you select to create a separate reimbursement transaction for each billing classification, reimbursement transactions will be grouped by the unique customer balance posting type entry and billing classification. The resulting reimbursement transactions will be assigned a classification value.

Reimbursement transactions contain a debit entry for each unique customer balance posting entry type. This value equals the total of the credit transaction balances for the customer and can be separated by billing classification if the option is enabled. This is offset by a credit entry to the vendor summary account by using the financial dimensions defaulted from the debit entry. Once created, the reimbursement transactions are automatically settled against their source accounts receivables credit transactions to bring their balance to zero.

Reimbursements are always issued for the full outstanding credit amounts on selected credit transactions, even if outstanding debit transactions exist for the customer. Reimbursements are not processed for any customer who has pending settlements that have not been posted to the journal. Reimbursement settlements cannot be reversed using the Closed transaction editing. To generate a reimbursement check, you can select the reimbursement transactions for settlement against a vendor payment in the Journals.


> [!NOTE]
> <P>To process reimbursements for customers who have outstanding credit and debit transactions, select the <STRONG>Include customers with outstanding debit transactions</STRONG> check box.</P>



## Example 1: Do not separate reimbursements by billing classification

In this example, the customer has overpaid, there are two credit notes from different billing classifications, and **Create a separate reimbursement for each billing classification** is not selected.

**Accounts receivables – payment voucher (Overpayment)**

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account + dimensions</p></th>
<th><p>Outstanding debit</p></th>
<th><p>Outstanding credit</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>999 – 11530</p></td>
<td><p></p></td>
<td><p>50.00</p></td>
<td><p>Customer summary account and financial dimensions (customer balance posting type entry)</p></td>
</tr>
<tr class="even">
<td><p>999 – 11020</p></td>
<td><p>50.00</p></td>
<td><p></p></td>
<td><p>Bank account for payment</p></td>
</tr>
</tbody>
</table>


**Accounts receivables – Credit note voucher (Billing classification PARKS)**

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account + dimensions</p></th>
<th><p>Outstanding debit</p></th>
<th><p>Outstanding credit</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>101 – 44200 - -</p></td>
<td><p>10.00</p></td>
<td><p></p></td>
<td><p>Revenue account</p></td>
</tr>
<tr class="even">
<td><p>101 – 11530</p></td>
<td><p></p></td>
<td><p>10.00</p></td>
<td><p>Accounts receivable (customer balance posting type entry)</p></td>
</tr>
</tbody>
</table>


**Accounts receivables – Credit note voucher (Billing classification UTL)**

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account + dimensions</p></th>
<th><p>Outstanding debit</p></th>
<th><p>Outstanding credit</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>101 – 44400 - -</p></td>
<td><p>10.00</p></td>
<td><p></p></td>
<td><p>Revenue account</p></td>
</tr>
<tr class="even">
<td><p>601 – 44400 - -</p></td>
<td><p>45.00</p></td>
<td><p></p></td>
<td><p>Revenue account</p></td>
</tr>
<tr class="odd">
<td><p>602 – 44400 - -</p></td>
<td><p>45.00</p></td>
<td><p></p></td>
<td><p>Revenue account</p></td>
</tr>
<tr class="even">
<td><p>101 – 11530</p></td>
<td><p></p></td>
<td><p>10.00</p></td>
<td><p>Accounts receivable (customer balance posting type entry)</p></td>
</tr>
<tr class="odd">
<td><p>601 – 11530</p></td>
<td><p></p></td>
<td><p>45.00</p></td>
<td><p>Accounts receivable (customer balance posting type entry)</p></td>
</tr>
<tr class="even">
<td><p>602 – 11530</p></td>
<td><p></p></td>
<td><p>45.00</p></td>
<td><p>Accounts receivable (customer balance posting type entry)</p></td>
</tr>
</tbody>
</table>


## Generated reimbursement transactions for the customer against these credit transactions

**Reimbursement transaction 1 voucher (billing classification value is blank)**

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account + dimensions</p></th>
<th><p>Debit</p></th>
<th><p>Credit</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>999 – 11530</p></td>
<td><p>50.00</p></td>
<td><p></p></td>
<td><p>Customer balance posting type entry</p></td>
</tr>
<tr class="even">
<td><p>999 – 24210</p></td>
<td><p></p></td>
<td><p>50.00</p></td>
<td><p>Vendor summary account and debit entry financial dimensions</p></td>
</tr>
</tbody>
</table>


**Reimbursement transaction 2 voucher (billing classification value is blank)**

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account + dimensions</p></th>
<th><p>Debit</p></th>
<th><p>Credit</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>101 – 11530</p></td>
<td><p>20.00</p></td>
<td><p></p></td>
<td><p>Customer balance posting type entry from PARKS and UTL</p></td>
</tr>
<tr class="even">
<td><p>101 – 24210</p></td>
<td><p></p></td>
<td><p>20.00</p></td>
<td><p>Vendor summary account and debit entry financial dimensions</p></td>
</tr>
</tbody>
</table>


**Reimbursement transaction 3 voucher (billing classification value is blank)**

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account + dimensions</p></th>
<th><p>Debit</p></th>
<th><p>Credit</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>601 – 11530</p></td>
<td><p>45.00</p></td>
<td><p></p></td>
<td><p>Customer balance posting type entry from UTL</p></td>
</tr>
<tr class="even">
<td><p>601 – 24210</p></td>
<td><p></p></td>
<td><p>45.00</p></td>
<td><p>Vendor summary account and debit entry financial dimensions</p></td>
</tr>
</tbody>
</table>


**Reimbursement transaction 4 voucher (billing classification value is blank)**

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account + dimensions</p></th>
<th><p>Debit</p></th>
<th><p>Credit</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>601 – 11530</p></td>
<td><p>45.00</p></td>
<td><p></p></td>
<td><p>Customer balance posting type entry from UTL</p></td>
</tr>
<tr class="even">
<td><p>601 – 24210</p></td>
<td><p></p></td>
<td><p>45.00</p></td>
<td><p>Vendor summary account and debit entry financial dimensions</p></td>
</tr>
</tbody>
</table>


## Example 2: Separate reimbursements by billing classification

In this example, the customer has overpaid, there are two credit notes from different billing classifications, and **Create a separate reimbursement for each billing classification** is selected.

**Accounts receivables – payment voucher (Overpayment)**

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account + dimensions</p></th>
<th><p>Outstanding debit</p></th>
<th><p>Outstanding credit</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>999 – 11530</p></td>
<td><p></p></td>
<td><p>50.00</p></td>
<td><p>Customer summary account and financial dimensions (customer balance posting type entry)</p></td>
</tr>
<tr class="even">
<td><p>999 – 11020</p></td>
<td><p>50.00</p></td>
<td><p></p></td>
<td><p>Bank account for payment</p></td>
</tr>
</tbody>
</table>


**Accounts receivables – Credit note voucher (Billing classification PARKS)**

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account + dimensions</p></th>
<th><p>Outstanding debit</p></th>
<th><p>Outstanding credit</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>101 – 44200 - -</p></td>
<td><p>10.00</p></td>
<td><p></p></td>
<td><p>Revenue account</p></td>
</tr>
<tr class="even">
<td><p>101 – 11530</p></td>
<td><p></p></td>
<td><p>10.00</p></td>
<td><p>Accounts receivable (customer balance posting type entry)</p></td>
</tr>
</tbody>
</table>


**Accounts receivables – Credit note voucher (Billing classification UTL)**

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account + dimensions</p></th>
<th><p>Outstanding debit</p></th>
<th><p>Outstanding credit</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>101 – 44400 - -</p></td>
<td><p>10.00</p></td>
<td><p></p></td>
<td><p>Revenue account</p></td>
</tr>
<tr class="even">
<td><p>601 – 44400 - -</p></td>
<td><p>45.00</p></td>
<td><p></p></td>
<td><p>Revenue account</p></td>
</tr>
<tr class="odd">
<td><p>602 – 44400 - -</p></td>
<td><p>45.00</p></td>
<td><p></p></td>
<td><p>Revenue account</p></td>
</tr>
<tr class="even">
<td><p>101 – 11530</p></td>
<td><p></p></td>
<td><p>10.00</p></td>
<td><p>Accounts receivable (customer balance posting type entry)</p></td>
</tr>
<tr class="odd">
<td><p>601 – 11530</p></td>
<td><p></p></td>
<td><p>45.00</p></td>
<td><p>Accounts receivable (customer balance posting type entry)</p></td>
</tr>
<tr class="even">
<td><p>602 – 11530</p></td>
<td><p></p></td>
<td><p>45.00</p></td>
<td><p>Accounts receivable (customer balance posting type entry)</p></td>
</tr>
</tbody>
</table>


## Generated reimbursement transactions for the customer against these credit transactions

**Reimbursement transaction 1 voucher (billing classification value is blank)**

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account + dimensions</p></th>
<th><p>Debit</p></th>
<th><p>Credit</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>999 – 11530</p></td>
<td><p>50.00</p></td>
<td><p></p></td>
<td><p>Customer balance posting type entry</p></td>
</tr>
<tr class="even">
<td><p>999 – 24210</p></td>
<td><p></p></td>
<td><p>50.00</p></td>
<td><p>Vendor summary account and debit entry financial dimensions</p></td>
</tr>
</tbody>
</table>


**Reimbursement transaction 2 voucher (billing classification value is PARKS)**

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account + dimensions</p></th>
<th><p>Debit</p></th>
<th><p>Credit</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>101 – 11530</p></td>
<td><p>10.00</p></td>
<td><p></p></td>
<td><p>Customer balance posting type entry from PARKS</p></td>
</tr>
<tr class="even">
<td><p>101 – 24210</p></td>
<td><p></p></td>
<td><p>10.00</p></td>
<td><p>Vendor summary account and debit entry financial dimensions</p></td>
</tr>
</tbody>
</table>


**Reimbursement transaction 3 voucher (billing classification value is UTL)**

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account + dimensions</p></th>
<th><p>Debit</p></th>
<th><p>Credit</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>101 – 11530</p></td>
<td><p>10.00</p></td>
<td><p></p></td>
<td><p>Customer balance posting type entry from UTL</p></td>
</tr>
<tr class="even">
<td><p>601 – 24210</p></td>
<td><p></p></td>
<td><p>10.00</p></td>
<td><p>Vendor summary account and debit entry financial dimensions</p></td>
</tr>
</tbody>
</table>


**Reimbursement transaction 4 voucher (billing classification value is UTL)**

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account + dimensions</p></th>
<th><p>Debit</p></th>
<th><p>Credit</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>601 – 11530</p></td>
<td><p>45.00</p></td>
<td><p></p></td>
<td><p>Customer balance posting type entry from UTL</p></td>
</tr>
<tr class="even">
<td><p>601 – 24210</p></td>
<td><p></p></td>
<td><p>45.00</p></td>
<td><p>Vendor summary account and debit entry financial dimensions</p></td>
</tr>
</tbody>
</table>


**Reimbursement transaction 5 voucher (billing classification value is UTL)**

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account + dimensions</p></th>
<th><p>Debit</p></th>
<th><p>Credit</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>602 – 11530</p></td>
<td><p>45.00</p></td>
<td><p></p></td>
<td><p>Customer balance posting type entry from UTL</p></td>
</tr>
<tr class="even">
<td><p>602 – 24210</p></td>
<td><p></p></td>
<td><p>45.00</p></td>
<td><p>Vendor summary account and debit entry financial dimensions</p></td>
</tr>
</tbody>
</table>


## See also

[Reimbursement (class form)](https://technet.microsoft.com/library/aa553712\(v=ax.60\))

  


