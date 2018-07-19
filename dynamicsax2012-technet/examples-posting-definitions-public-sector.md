---
title: 'Examples: Posting definitions (Public sector)'
TOCTitle: 'Examples: Posting definitions (Public sector)'
ms:assetid: 70e37c7c-84b1-4a49-a19f-7bf2fd0d4a81
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh412236(v=AX.60)
ms:contentKeyID: 36916345
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- public sector
- posting definition examples
- posting definition
- posting definitions
- posting definition example
audience: Application User
ms.search.region: Denmark, France
---

# Examples: Posting definitions (Public sector) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before you read this topic, you should be familiar with posting definitions and transaction posting definitions. For more information, see [About posting definitions](about-posting-definitions.md).


> [!NOTE]
> <P>This topic includes information about features that were added or changed for Microsoft Dynamics AX 2012 R3 Cumulative Update 8. For more information, see the section later in this topic.</P>




> [!NOTE]
> <P>This topic has been updated to include information about features that were added or changed in the following hotfix for Microsoft Dynamics AX 2012 R3 Cumulative Update 8: KB3047235</P>



The following examples can be set up in the **Posting definitions** form. (Click **General ledger** \> **Setup** \> **Posting** \> **Posting definitions**.) Each example contains these sections:

  - Posting definition – Match criteria

  - Posting definition – Generated entries

  - Transactions with the accounts, dimension values, and amounts

  - Ledger entries generated from the posting definition

When a match occurs between the accounts and dimension values in the **Match criteria** pane for the posting definition and the accounts and dimension values on the transaction, ledger entries are generated based on the **Generated entries** pane for the posting definition.


> [!NOTE]
> <P>To associate a posting definition with a specific transaction type, use the <STRONG>Transaction posting definitions</STRONG> form. (Click <STRONG>General ledger</STRONG> &gt; <STRONG>Setup</STRONG> &gt; <STRONG>Posting</STRONG> &gt; <STRONG>Transaction posting definitions</STRONG>.) After you associate a posting definition with a transaction type and select <STRONG>Use posting definitions</STRONG> in the <STRONG>General ledger parameters</STRONG> form, all transactions of the selected transaction type must use posting definitions.</P>



## Example: Budget appropriations

For public sector organizations, original budget balances are recorded as either appropriations for expenses or estimated revenues. The original budget balances are used to track available budget balances against expenditures and the actual revenues that are collected.

A posting definition is created to support recording budget register entries to the general ledger, and a transaction posting definition is set up for budget register entries that have a budget type of **Original budget**.

**Posting definition – Match criteria – Row 1**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Account structure</strong></p></th>
<th><p><strong>Match account number</strong>*</p></th>
<th><p><strong>Priority</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Expense</p></td>
<td><p>101 - - -</p></td>
<td><p>1</p></td>
</tr>
</tbody>
</table>


\*A blank value in the **Match account number** field means that all matching accounts in the defined account structure will be part of the matching rule.

**Posting definition – Generated entries for Match criteria – Row 1**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Account structure</strong></p></th>
<th><p><strong>Generated account number</strong></p></th>
<th><p><strong>Generated debit/credit</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Balance</p></td>
<td><p>-36300</p>
<p>(Budgetary fund balance account)</p></td>
<td><p>Same</p></td>
</tr>
<tr class="even">
<td><p>Balance</p></td>
<td><p>-36350</p>
<p>(Appropriation account)</p></td>
<td><p>Balancing</p></td>
</tr>
</tbody>
</table>


**Posting definition – Match criteria – Row 2**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Account structure</strong></p></th>
<th><p><strong>Match account number</strong>*</p></th>
<th><p><strong>Priority</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Revenue</p></td>
<td><p>101 - - -</p></td>
<td><p>1</p></td>
</tr>
</tbody>
</table>


\*A blank value in the Match account number means that all matching accounts in the defined account structure will be part of the matching rule.

**Posting definition – Generated entries for Match criteria – Row 2**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Account structure</strong></p></th>
<th><p><strong>Generated account number</strong></p></th>
<th><p><strong>Generated debit/credit</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Balance</p></td>
<td><p>-36300</p>
<p>(Budgetary fund balance account)</p></td>
<td><p>Balancing</p></td>
</tr>
<tr class="even">
<td><p>Balance</p></td>
<td><p>-36340</p>
<p>(Estimated revenue account)</p></td>
<td><p>Same</p></td>
</tr>
</tbody>
</table>


**Transactions with the accounts, dimension values, and amounts**

You enter the accounts, dimension values, and amounts on the budget account entry in the **Budget register entry** form. (Click **Budgeting** \> **Common** \> **Budget register entries** \> **All budget register entries**. Click **Budget register entry**.)

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account + Dimensions</p></th>
<th><p>Debit</p></th>
<th><p>Credit</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>101-606400-OU_1-OU_3566-Training</p></td>
<td><p></p></td>
<td><p>250.00</p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


**Ledger entries generated from the posting definition**

Generated ledger entries are created to record the original budget in each dimension.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account + Dimensions</p></th>
<th><p>Debit</p></th>
<th><p>Credit</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>101-36300</p></td>
<td><p></p></td>
<td><p>250.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>101-36350</p></td>
<td><p>250.00</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


In this example, the fund dimension and account part of the Expense account structure match the posting definition criteria. Therefore, when 101-606400-OU\_1-OU\_3566-Training is evaluated, the generated ledger entries are created.

## Examples: Pooled cash settlements

In the public sector, pooled cash accounting consists of amounts that are deposited by individual departments or agencies into a combined ledger account. This improves the control and custody over liquid assets and promotes the efficient management of excess funds. These amounts can be managed by using a Treasurer’s fund. As a result, the appropriate proportional amount of the pooled cash and investment balances must be reported for each fund participating in the pool. To guarantee this, appropriate due-to and due-from entries must be added to the settlements that transfer amounts from one fund to another to accomplish the settlement.


> [!NOTE]
> <P>No error message is displayed if a posting definition for settlements is not specified or if a match criteria in the posting definition is not available. Public sector installations that do not use pooled cash settlements or that do not require balancing entries on the settlement voucher do not have to set up posting definitions for settlements when posting definitions are enabled for other transactions.</P>



For accounts payable settlements, vendor payables in one or more funds are used to record the appropriate fund equity transactions in the Treasurer’s fund. For accounts receivable settlements, the customer credit from the payments in the Treasurer’s fund is used to settle the receivables in one or more funds. The vendor balance or customer balance posting entries on the transactions being settled are automatically reversed. The use of posting definitions for settlement is optional. The posting definitions are applied at the time of settlement to generate the additional ledger transactions for due-to and due-from entries to balance the settlement voucher by fund.

For payroll disbursements, the use of a separate payroll clearing fund necessitates the use of posting definitions to generate the balancing entries when net earnings accumulated in the payroll clearing fund is paid out through the bank in the Treasurer’s fund.


> [!NOTE]
> <P>The payroll examples that are referenced in this section apply only to Microsoft Dynamics AX 2012 R3 or cumulative update 7 or later for AX 2012 R2.</P>



Posting definitions can be used for the following settlement transaction types:

  - Vendor payment journals, which include vendor payments against invoices, reimbursements, and general ledger credit vouchers and credit memos against invoices.

  - Promissory notes, which include payments using the draw, redraw, remit, and settlement of promissory notes.

  - Customer payment journals, which include customer payments, customer general ledger credit vouchers, and credit notes against free text invoices, project invoices, interest notes, and collection letter transactions.

  - Payroll disbursements using a separate payroll clearing fund.

Posting definitions for vendor payment journals, promissory notes, customer payment journals, and payroll disbursement journals can be set up by selecting the **Bank** module in the **Posting definitions** form. Then, on the **Bank** tab of the **Transaction posting definitions** form, you can select the appropriate transaction types to associate with the posting definitions.


> [!NOTE]
> <P>A single posting definition, if widely defined, can be used for most vendor, customer settlement, and payroll payment scenarios. The single posting definition would still have to be associated with both vendor and customer payment journals, and payroll disbursements on the <STRONG>Bank</STRONG> tab of the <STRONG>Transaction posting definitions</STRONG> form.</P>



You can specify a different posting definition for a specific Bank and Method of payment for vendor and customer payment journals. You can only define a single posting definition for the Payroll disbursement journal.

Before posting definitions are applied on settlements, complete the following:

  - Associate each vendor or customer who has the Treasurer’s fund (999) on the **Financial dimensions** tab of the **Vendor** or **Customers** forms. This includes the payroll disbursement vendor account specified in the Payroll \> Setup \> Payroll parameters \> Payroll parameters Payment issuance page. This enables the vendor or customer payments to be generated in the Treasurer’s fund against the vendor or customer summary account specified in the vendor or customer posting profiles. For Accounts receivable, you can set the default fund value by selecting **Setup** on the **Customer groups** form. Then the Treasurer’s fund will become the default fund when new customers are associated with a customer group.

  - Associate each bank account that is used in settlements with the Treasurer’s fund. This allows the posted bank account to be in balance by fund with the vendor or customer payment. For payroll, the payroll disbursement bank specified in the payroll parameters would also be associated with the Treasurer’s fund.

And do one of the following two options:

  - Option A: Specify a single “due-to” account in the Treasurer’s fund for all funds. A single global match criteria addresses all funds (excluding the Treasurer’s fund), you must specify the following Match criteria and Generated entries on the posting definition:

**Settlement posting definition – Match criteria**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Account structure</strong></p></th>
<th><p><strong>Match account number</strong>*</p></th>
<th><p><strong>Priority</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Balance</p></td>
<td><p>999 -</p>
<p>Specify a higher priority match entry for the Treasurer’s fund so that balancing entries are not generated for this fund.</p></td>
<td><p>1</p></td>
</tr>
</tbody>
</table>


\*A blank value in the **Match account number** field means that all matching accounts in the defined account structure will be part of the matching rule.

**Settlement posting definition – Generated entries for Match criteria**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Account structure</strong></p></th>
<th><p><strong>Generated account number</strong></p></th>
<th><p><strong>Generated debit/credit</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p></p></td>
<td><p>No generated entries defined against the match entry for the treasurer’s fund.</p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


**Settlement posting definition – Match criteria**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Account structure</strong></p></th>
<th><p><strong>Match account number</strong>*</p></th>
<th><p><strong>Priority</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Balance</p></td>
<td><p>Use a global match entry of lower priority to create balancing entries for all other funds.</p></td>
<td><p>10</p></td>
</tr>
</tbody>
</table>


\*A blank value in the **Match account number** field means that all matching accounts in the defined account structure will be part of the matching rule.

**Settlement posting definition – Generated entries for Match criteria**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Account structure</strong></p></th>
<th><p><strong>Generated account number</strong></p></th>
<th><p><strong>Generated debit/credit</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Balance</p></td>
<td><p>- 10110</p>
<p>(Equity account in the match entry – Cash account)</p></td>
<td><p>Balancing</p></td>
</tr>
<tr class="even">
<td><p>Balance</p></td>
<td><p>999 – 37000</p>
<p>(Equity account in the Treasurer’s fund for all funds)</p></td>
<td><p>Same</p></td>
</tr>
</tbody>
</table>


  - Option B: Specify a different “due-to” account in the Treasurer’s fund for each fund. For every fund that a vendor payable or customer receivable will be generated in (excluding the Treasurer’s fund), you must specify the following Match criteria and Generated entries on the posting definition:

**Settlement posting definition – Match criteria**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Account structure</strong></p></th>
<th><p><strong>Match account number</strong>*</p></th>
<th><p><strong>Priority</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Balance</p></td>
<td><p>101 -</p>
<p>Using a fund value and blank main account makes it applicable to both customer receivables and vendor payables.</p></td>
<td><p>1</p></td>
</tr>
</tbody>
</table>


\*A blank value in the **Match account number** field means that all matching accounts in the defined account structure will be part of the matching rule.

**Settlement posting definition – Generated entries for Match criteria**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Account structure</strong></p></th>
<th><p><strong>Generated account number</strong></p></th>
<th><p><strong>Generated debit/credit</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Balance</p></td>
<td><p>101 - 10110</p>
<p>(Equity account in Fund 101 – Cash account)</p></td>
<td><p>Balancing</p></td>
</tr>
<tr class="even">
<td><p>Balance</p></td>
<td><p>999 – 37001</p>
<p>(Equity account in the Treasurer’s fund for Fund 101)</p></td>
<td><p>Same</p></td>
</tr>
</tbody>
</table>


You must add additional match criteria rows for each fund with generated entries to reflect the appropriate fund balancing entry and the equity account of the fund in the Treasurer’s fund.

From the vendor or customer payment journal, enter the vendor or customer accounts or create a payment proposal and select the invoices to be paid. When the journal is posted, the vendor or customer balance posting entries on both the invoice and payment are matched against the posting definition for settlement. If match criteria are found, the generated due-to and due-from entries are added to the settlement voucher. For payroll payments, submit pay statements and post the payment in the payroll payment journal.

**Examples:**

The following vouchers are representative of a typical invoice, payment and settlement scenario.

## Accounts payable example

**Accounts payable invoice voucher**

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account + Dimensions</p></th>
<th><p>Debit</p></th>
<th><p>Credit</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>101 – 66100 – 150</p></td>
<td><p>250.00</p></td>
<td><p></p></td>
<td><p>Expenditure account</p></td>
</tr>
<tr class="even">
<td><p>101 – 24210</p></td>
<td><p></p></td>
<td><p>250.00</p></td>
<td><p>Accounts payable</p></td>
</tr>
</tbody>
</table>


**Accounts payable payment voucher**

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account + Dimensions</p></th>
<th><p>Debit</p></th>
<th><p>Credit</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>999 – 24210</p></td>
<td><p>250.00</p></td>
<td><p></p></td>
<td><p>Vendor summary</p></td>
</tr>
<tr class="even">
<td><p>999 – 11020</p></td>
<td><p></p></td>
<td><p>250.00</p></td>
<td><p>Bank/cash account</p></td>
</tr>
</tbody>
</table>


**Accounts payable settlement voucher** (Accessed through the related vouchers on the vendor payment voucher.)

In this example, the match account number values for the posting definition match the vendor balance posting type accounts. When 999 - 24210 and 101 – 24210 are evaluated, the generated ledger entries will only be created for the Fund 101 because no match entries are set up for 999 - the Treasurer’s fund.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account + Dimensions</p></th>
<th><p>Debit</p></th>
<th><p>Credit</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>999 – 24210</p></td>
<td><p></p></td>
<td><p>250.00</p></td>
<td><p>Vendor summary (System generated)</p></td>
</tr>
<tr class="even">
<td><p>101 – 24210</p></td>
<td><p>250.00</p></td>
<td><p></p></td>
<td><p>Invoice payable (System generated)</p></td>
</tr>
<tr class="odd">
<td><p>101 – 11010</p></td>
<td><p></p></td>
<td><p>250.00</p></td>
<td><p>Equity for Fund 101 (Posting definition for settlement)</p></td>
</tr>
<tr class="even">
<td><p>999 - 37001</p></td>
<td><p>250.00</p></td>
<td><p></p></td>
<td><p>Treasurer’s fund – Due from Fund 101 (Posting definition for settlement)</p></td>
</tr>
</tbody>
</table>


**Summarizing the entries across the invoice, payment and settlement vouchers**

The final ledger accounts are affected as follows:

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account + Dimensions</p></th>
<th><p>Debit</p></th>
<th><p>Credit</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>999 – 11020</p></td>
<td><p></p></td>
<td><p>250.00</p></td>
<td><p>Bank/Cash account</p></td>
</tr>
<tr class="even">
<td><p>101 – 66100 – 150</p></td>
<td><p>250.00</p></td>
<td><p></p></td>
<td><p>Expenditure account</p></td>
</tr>
<tr class="odd">
<td><p>101 – 11010</p></td>
<td><p></p></td>
<td><p>250.00</p></td>
<td><p>Equity for Fund 101 (Posting definition for settlement)</p></td>
</tr>
<tr class="even">
<td><p>999 - 37001</p></td>
<td><p>250.00</p></td>
<td><p></p></td>
<td><p>Treasurer’s fund – Due from Fund 101 (Posting definition for settlement)</p></td>
</tr>
</tbody>
</table>


## Accounts receivable example

**Accounts receivable invoice voucher**

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account + Dimensions</p></th>
<th><p>Debit</p></th>
<th><p>Credit</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>101 – 44400</p></td>
<td><p></p></td>
<td><p>250.00</p></td>
<td><p>Revenue account</p></td>
</tr>
<tr class="even">
<td><p>101 – 11530</p></td>
<td><p>250.00</p></td>
<td><p></p></td>
<td><p>Accounts receivable</p></td>
</tr>
</tbody>
</table>


**Accounts receivable payment voucher**

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account + Dimensions</p></th>
<th><p>Debit</p></th>
<th><p>Credit</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>999 – 11530</p></td>
<td><p></p></td>
<td><p>250.00</p></td>
<td><p>Customer summary</p></td>
</tr>
<tr class="even">
<td><p>999 – 11020</p></td>
<td><p>250.00</p></td>
<td><p></p></td>
<td><p>Bank/cash account</p></td>
</tr>
</tbody>
</table>


**Accounts receivables settlement voucher** (accessed through the related vouchers on the customer payment voucher)

In this example, the Match account number values for the posting definition match the customer balance posting type accounts. When 999 - 11530 and 101 – 11530 are evaluated, the generated ledger entries are created only for the Fund 101 because no match entries are set up for the 999 Treasurer’s fund.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account + Dimensions</p></th>
<th><p>Debit</p></th>
<th><p>Credit</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>999 – 11530</p></td>
<td><p>250.00</p></td>
<td><p></p></td>
<td><p>Customer summary (System generated)</p></td>
</tr>
<tr class="even">
<td><p>101 – 11530</p></td>
<td><p></p></td>
<td><p>250.00</p></td>
<td><p>Invoice receivable (System generated)</p></td>
</tr>
<tr class="odd">
<td><p>101 – 11010</p></td>
<td><p>250.00</p></td>
<td><p></p></td>
<td><p>Equity for Fund 101 (Posting definition for settlement)</p></td>
</tr>
<tr class="even">
<td><p>999 - 37001</p></td>
<td><p></p></td>
<td><p>250.00</p></td>
<td><p>Treasurer’s fund – Due to Fund 101 (Posting definition for settlement)</p></td>
</tr>
</tbody>
</table>


**Summarizing the entries across the invoice, payment and settlement vouchers**

The final ledger accounts are affected as follows:

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account + Dimensions</p></th>
<th><p>Debit</p></th>
<th><p>Credit</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>999 – 11020</p></td>
<td><p>250.00</p></td>
<td><p></p></td>
<td><p>Bank/cash account</p></td>
</tr>
<tr class="even">
<td><p>101 – 44400</p></td>
<td><p></p></td>
<td><p>250.00</p></td>
<td><p>Revenue account</p></td>
</tr>
<tr class="odd">
<td><p>101 – 11010</p></td>
<td><p>250.00</p></td>
<td><p></p></td>
<td><p>Equity for Fund 101 (Posting definition for settlement)</p></td>
</tr>
<tr class="even">
<td><p>999 - 37001</p></td>
<td><p></p></td>
<td><p>250.00</p></td>
<td><p>Treasurer’s fund – Due to Fund 101 (Posting definition for settlement)</p></td>
</tr>
</tbody>
</table>


In addition to the example earlier in this section, posting definitions for settlements associated with the customer payment journal transaction type can also be applied in the following scenarios:

  - Accounts receivables write-offs

  - Accounts receivables free-text invoice cash-on-delivery (cash payment) settlements

Accounts receivables write-offs can use posting definitions defined for settlement for balancing-by-fund the general ledger credit voucher generated when the general ledger journals for accounts receivable write-offs are posted. Both ledger and customer account type entries on the journal lines are evaluated against the posting definition for settlement. Both use the posting definition assigned to the transaction type on the **Accounts receivable** tab of the **Transaction posting definitions** form. Depending on how the write-off is designed to be executed, the posting definition for settlement may need additional match criteria.

When the write-off posting definition is set up to write-off balances to an allowance for the Doubtful receivables contra asset account, the posting definition for settlement can also be used for write-offs as long as the match criterion is already set up for balance sheet accounts that have a mask for the main account. (For more information, see earlier examples, such as the Settlement posting definition – Match criteria.)

When the write-off posting definition is set up to reverse the originating revenue account, the posting definition for settlement must have the appropriate match criteria for revenue structures with the due-to and due-from entries on the generated entries. For each fund not in the Treasurer’s fund (999), the following entries must be present on the posting definition for settlement:

**Posting definition – Match criteria**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Account structure</strong></p></th>
<th><p><strong>Match account number</strong>*</p></th>
<th><p><strong>Priority</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Revenue</p></td>
<td><p>101 - - -</p>
<p>Using a fund value and blank main account makes the criteria applicable to all ledger entries.</p></td>
<td><p>1</p></td>
</tr>
</tbody>
</table>


\*A blank value in the **Match account number** field means that all matching accounts in the defined account structure will be part of the matching rule.

**Posting definition – Generated entries for Match criteria**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Account structure</strong></p></th>
<th><p><strong>Generated account number</strong></p></th>
<th><p><strong>Generated debit/credit</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Balance</p></td>
<td><p>101 - 10110</p>
<p>(Equity account in Fund 101)</p></td>
<td><p>Balancing</p></td>
</tr>
<tr class="even">
<td><p>Same</p></td>
<td><p>999 – 37001</p>
<p>(Treasurer’s fund - Fund equity account for Fund 101. A single account may be used instead of individual fund equity accounts)</p></td>
<td><p>Same</p></td>
</tr>
</tbody>
</table>


## Accounts receivable write off example

**Accounts receivable invoice voucher**

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account + Dimensions</p></th>
<th><p>Debit</p></th>
<th><p>Credit</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>101 – 44400 - -</p></td>
<td><p></p></td>
<td><p>250.00</p></td>
<td><p>Revenue account</p></td>
</tr>
<tr class="even">
<td><p>101 – 11530</p></td>
<td><p>250.00</p></td>
<td><p></p></td>
<td><p>Accounts receivable</p></td>
</tr>
</tbody>
</table>


**Accounts receivable write off – General ledger credit voucher**

In this example, the posting definition for write-off is set to reverse the revenue account.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account + Dimensions</p></th>
<th><p>Debit</p></th>
<th><p>Credit</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>999 – 11530</p></td>
<td><p></p></td>
<td><p>250.00</p></td>
<td><p>Customer summary</p></td>
</tr>
<tr class="even">
<td><p>101 – 44400 - -</p></td>
<td><p>250.00</p></td>
<td><p></p></td>
<td><p>Bank/cash account</p></td>
</tr>
<tr class="odd">
<td><p>101 – 11010</p></td>
<td><p></p></td>
<td><p>250.00</p></td>
<td><p>Equity for Fund 101 (Posting definition for settlement)</p></td>
</tr>
<tr class="even">
<td><p>999 - 37001</p></td>
<td><p>250.00</p></td>
<td><p></p></td>
<td><p>Treasurer’s fund – Due to Fund 101 (Posting definition for settlement)</p></td>
</tr>
</tbody>
</table>


**Accounts receivable write off - Settlement voucher**

In this example, the credit created in the general ledger voucher is applied to the write-off transaction. Additionally, the match account number values for the posting definition match the customer balance posting type accounts. Therefore, when 999 - 11530 and 101 – 11530 are evaluated, the generated ledger entries are created only for Fund 101 because no match entries are set up for the 999 Treasurer’s fund.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account + Dimensions</p></th>
<th><p>Debit</p></th>
<th><p>Credit</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>999 – 11530</p></td>
<td><p>250.00</p></td>
<td><p></p></td>
<td><p>Customer summary (System generated)</p></td>
</tr>
<tr class="even">
<td><p>101 – 11530</p></td>
<td><p></p></td>
<td><p>250.00</p></td>
<td><p>Invoice receivable (System generated)</p></td>
</tr>
<tr class="odd">
<td><p>101 – 11010</p></td>
<td><p>250.00</p></td>
<td><p></p></td>
<td><p>Equity for Fund 101 (Posting definition for settlement)</p></td>
</tr>
<tr class="even">
<td><p>999 - 37001</p></td>
<td><p></p></td>
<td><p>250.00</p></td>
<td><p>Treasurer’s fund – Due to Fund 101 (Posting definition for settlement)</p></td>
</tr>
</tbody>
</table>


Summarizing the entries across the vouchers for invoice, write-off credit, and settlement, there is no net effect on the ledger accounts after an invoice is written off in full.

## Accounts receivable free text invoice cash-on-delivery (cash payment) settlement example

Free text invoices, that use a terms-of-payment with the payment method set to COD and with cash payment enabled, instantly settle themselves at the time of posting without having to use the payment journal. When this kind of settlement occurs, a credit note is created that uses the specified cash account on the terms of payment offset by the customer summary account using customer financial dimensions. The appropriate receivable accounts specified on the invoice in this kind of settlement are not automatically reversed. As a result, the posting definition for settlement must also address the reversal of the customer balance posting entries on the invoice and credit. This is in addition to generating the due-to and due-from entries for settlement.

To use posting definitions for settlement for this scenario, complete the following additional setup steps:

  - Create a distinct method of payment for free text invoices that will be settled through this method.

  - Create a new posting definition for the free text invoice cash-on-delivery settlement

  - Associate the new posting definition (for the customer payment journal against the specific method of payment) on the **Bank** tab of the **Transaction posting definitions** form. Select this unique method of payment and the COD/cash payment terms of payment on the invoice to apply the posting definition setup specified for this kind of settlement.

  - In the posting definition, enter the following match criteria and generated entries for the 999 fund.

**Posting definition –Match criteria - Row 1**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Account structure</strong></p></th>
<th><p><strong>Match account number</strong>*</p></th>
<th><p><strong>Generated debit/credit</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Balance</p></td>
<td><p>999 -</p>
<p>This match criteria is only used for receivables in the 999 fund. Only two generated entries for this match criteria are needed because due-to and due-from entries are not applicable for the Treasurer’s fund.</p></td>
<td><p>1</p></td>
</tr>
</tbody>
</table>


\*A blank value in the **Match account number** field means that all matching accounts in the defined account structure will be part of the matching rule.

**Posting definition – Generated entries for Match criteria - Row 1**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Account structure</strong></p></th>
<th><p><strong>Generated account number</strong></p></th>
<th><p><strong>Generated debit/credit</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Balance</p></td>
<td><p>999 - 11530</p>
<p>(Debit the customer balance posting type entry on the credit issued)</p></td>
<td><p>Balancing</p></td>
</tr>
<tr class="even">
<td><p>Same</p></td>
<td><p>999 –</p>
<p>(Credit the receivable in the 999 fund)</p></td>
<td><p>Same</p></td>
</tr>
</tbody>
</table>


The posting definition must contain the following entry for every fund other than the Treasurer’s fund (999):

**Posting definition – Match criteria – Row 2**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Account structure</strong></p></th>
<th><p><strong>Match account number</strong>*</p></th>
<th><p><strong>Priority</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Balance</p></td>
<td><p>101 -</p>
<p>For match criteria not in the Treasurer’s fund, four sets of generated entries are necessary. Two entries reverse the customer balance posting type entries on the credit and invoice, and two additional entries generate the necessary due-to and due-from entries.</p></td>
<td><p>1</p></td>
</tr>
</tbody>
</table>


\*A blank value in the **Match account number** field means that all matching accounts in the defined account structure will be part of the matching rule.

**Posting definition – Generated entries for Match criteria - Row 2**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Account structure</strong></p></th>
<th><p><strong>Generated account number</strong></p></th>
<th><p><strong>Generated debit/credit</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Balance</p></td>
<td><p>999 - 11530</p>
<p>(Debit the customer balance posting type entry on the credit issued)</p></td>
<td><p>Balancing</p></td>
</tr>
<tr class="even">
<td><p>Same</p></td>
<td><p>999 –</p>
<p>(Credit the receivable in Fund 101)</p></td>
<td><p>Same</p></td>
</tr>
<tr class="odd">
<td><p>Balance</p></td>
<td><p>101 – 10110</p>
<p>(Equity account in Fund 101)</p></td>
<td><p>Balancing</p></td>
</tr>
<tr class="even">
<td><p>Same</p></td>
<td><p>999 – 37001</p>
<p>(Treasurer’s fund - Fund equity account for Fund 101. A single account may be used instead of individual fund equity accounts)</p></td>
<td><p>Same</p></td>
</tr>
</tbody>
</table>


## Accounts receivable cash on delivery (cash payment) settlement example

**Accounts receivables invoice voucher (including additional credit entries in the voucher)**

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account + Dimensions</p></th>
<th><p>Debit</p></th>
<th><p>Credit</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>101 – 44400 - -</p></td>
<td><p></p></td>
<td><p>250.00</p></td>
<td><p>Revenue account in Fund 101</p></td>
</tr>
<tr class="even">
<td><p>999 – 44400 - -</p></td>
<td><p></p></td>
<td><p>250.00</p></td>
<td><p>Revenue account in Fund 999</p></td>
</tr>
<tr class="odd">
<td><p>101 – 11530</p></td>
<td><p>250.00</p></td>
<td><p></p></td>
<td><p>Accounts receivable in Fund 101</p></td>
</tr>
<tr class="even">
<td><p>999 - 11535</p></td>
<td><p>250.00</p></td>
<td><p></p></td>
<td><p>Accounts receivable in Fund 999</p></td>
</tr>
<tr class="odd">
<td><p>999-11530</p></td>
<td><p></p></td>
<td><p>500.00</p></td>
<td><p>Customer summary</p></td>
</tr>
<tr class="even">
<td><p>999 - 11020</p></td>
<td><p>500.00</p></td>
<td><p></p></td>
<td><p>Cash account on terms of payment</p></td>
</tr>
</tbody>
</table>


**Accounts receivables settlement voucher**

In this example, the match account number values for the posting definition match the customer balance posting type accounts only on the invoice.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account + Dimensions</p></th>
<th><p>Debit</p></th>
<th><p>Credit</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>999 - 11530</p></td>
<td><p>250.00</p></td>
<td><p></p></td>
<td><p>Customer summary (Posting definition for settlement)</p></td>
</tr>
<tr class="even">
<td><p>101 – 11530</p></td>
<td><p></p></td>
<td><p>250.00</p></td>
<td><p>Invoice receivable (Posting definition for settlement)</p></td>
</tr>
<tr class="odd">
<td><p>101 – 11010</p></td>
<td><p>250.00</p></td>
<td><p></p></td>
<td><p>Equity for Fund 101 (Posting definition for settlement)</p></td>
</tr>
<tr class="even">
<td><p>999 - 37001</p></td>
<td><p></p></td>
<td><p>250.00</p></td>
<td><p>Treasurer’s fund – Due to Fund 101 (Posting definition for settlement)</p></td>
</tr>
<tr class="odd">
<td><p>999 – 11530</p></td>
<td><p>250.00</p></td>
<td><p></p></td>
<td><p>Customer summary (Posting definition for settlement)</p></td>
</tr>
<tr class="even">
<td><p>999 – 11535</p></td>
<td><p></p></td>
<td><p>250.00</p></td>
<td><p>Customer summary (Posting definition for settlement)</p></td>
</tr>
</tbody>
</table>


**Summarizing the entries across the invoice, payment and settlement vouchers**

The final ledger accounts are affected as follows:

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account + Dimensions</p></th>
<th><p>Debit</p></th>
<th><p>Credit</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>999 – 11020</p></td>
<td><p>500.00</p></td>
<td><p></p></td>
<td><p>Cash account on terms of payment</p></td>
</tr>
<tr class="even">
<td><p>101 – 44400 - -</p></td>
<td><p></p></td>
<td><p>250.00</p></td>
<td><p>Revenue in Fund 101</p></td>
</tr>
<tr class="odd">
<td><p>999 – 44400 - -</p></td>
<td><p></p></td>
<td><p>250.00</p></td>
<td><p>Revenue in Fund 999</p></td>
</tr>
<tr class="even">
<td><p>101 – 11010</p></td>
<td><p>250.00</p></td>
<td><p></p></td>
<td><p>Equity for Fund 101</p>
<p>(Posting definition for settlement)</p></td>
</tr>
<tr class="odd">
<td><p>999 - 37001</p></td>
<td><p></p></td>
<td><p>250.00</p></td>
<td><p>Treasurer’s fund – Due-to Fund 101</p>
<p>(Posting definition for settlement)</p></td>
</tr>
</tbody>
</table>


## Example: Payroll disbursement

When you submit a generated pay statement for payment, the payroll process automatically creates an AP invoice to record the net earnings in the payroll clearing fund. When posting the payroll payment journal, the AP invoice is paid to specific employees using the bank in the Treasurer’s fund specified on the payroll parameters. No settlement voucher is created during this process, and so the balancing entries are added to the payment voucher.

**Submit for payment voucher**

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account + Dimensions</p></th>
<th><p>Debit</p></th>
<th><p>Credit</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>998 – 24610</p></td>
<td><p>250</p></td>
<td><p></p></td>
<td><p>Net earnings in the payroll clearing fund and account</p></td>
</tr>
<tr class="even">
<td><p>998 – 24210</p></td>
<td><p></p></td>
<td><p>250</p></td>
<td><p>Accounts payable (Vendor summary)</p></td>
</tr>
</tbody>
</table>


**Post the payroll payment journal**

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account + Dimensions</p></th>
<th><p>Debit</p></th>
<th><p>Credit</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>998 – 24210</p></td>
<td><p>250</p></td>
<td><p></p></td>
<td><p>Vendor summary</p></td>
</tr>
<tr class="even">
<td><p>999 – 11020</p></td>
<td><p></p></td>
<td><p>250</p></td>
<td><p>Bank/cash account</p></td>
</tr>
<tr class="odd">
<td><p>999 - 37015</p></td>
<td><p>250</p></td>
<td><p></p></td>
<td><p>Treasurer’s fund – Due-to Fund 998</p>
<p>(Posting definition for payroll disbursement)</p></td>
</tr>
<tr class="even">
<td><p>998 – 11010</p></td>
<td><p></p></td>
<td><p>250</p></td>
<td><p>Equity for Fund 998 – Payroll clearing fund</p>
<p>(Posting definition for payroll disbursement)</p></td>
</tr>
</tbody>
</table>


## Example: Advanced ledger entries

When you create advanced ledger entries, you must select a default posting definition. Then for each advanced ledger entry line, you can use the default posting definition or select another one. The posting definitions generate the accounting distributions and subledger journal entries that create, adjust or reverse the ledger entries and update the ledger accounts. You set up each posting definition for the **General ledger** module, but unlike other posting definitions, you do not associate the posting definition with a transaction type. Instead, you select the posting definition in the advanced ledger entry.

In this scenario, Accounts payable invoice AP\_0949 was mistakenly posted to the Capital improvement fund 300-12300-51002 instead of to the General fund 100-39810-51001. The following example shows how an advanced ledger entry can use a posting definition to debit the Capital improvement fund and credit the General fund.

**Posting definition – Match criteria – Row 1**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Account structure</strong></p></th>
<th><p><strong>Match account number</strong>*</p></th>
<th><p><strong>Priority</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Balance</p></td>
<td><p>300- -</p></td>
<td><p>1</p></td>
</tr>
</tbody>
</table>


\*A blank value in the **Match account number** field means that all matching accounts in the defined account structure will be part of the matching rule.

**Posting definition – Generated entries for Match criteria – Row 1**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Account structure</strong></p></th>
<th><p><strong>Generated account number</strong></p></th>
<th><p><strong>Generated debit/credit</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Balance</p></td>
<td><p>300-11001</p>
<p></p></td>
<td><p>Balancing</p></td>
</tr>
<tr class="even">
<td><p>Balance</p></td>
<td><p>900-11001</p></td>
<td><p>Balancing</p></td>
</tr>
<tr class="odd">
<td><p>Balance</p></td>
<td><p>900-37300</p></td>
<td><p>Same</p></td>
</tr>
</tbody>
</table>


**Posting definition – Match criteria – Row 2**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Account structure</strong></p></th>
<th><p><strong>Match account number</strong>*</p></th>
<th><p><strong>Priority</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Balance</p></td>
<td><p>100 - -</p></td>
<td><p>1</p></td>
</tr>
</tbody>
</table>


\*A blank value in the **Match account number** field means that all matching accounts in the defined account structure will be part of the matching rule.

**Posting definition – Generated entries for Match criteria – Row 2**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Account structure</strong></p></th>
<th><p><strong>Generated account number</strong></p></th>
<th><p><strong>Generated debit/credit</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Balance</p></td>
<td><p>100-11001</p>
<p></p></td>
<td><p>Balancing</p></td>
</tr>
<tr class="even">
<td><p>Balance</p></td>
<td><p>900-11001</p></td>
<td><p>Balancing</p></td>
</tr>
<tr class="odd">
<td><p>Balance</p></td>
<td><p>900-37301</p></td>
<td><p>Same</p></td>
</tr>
</tbody>
</table>


**Transactions with the accounts, dimension values, and amounts**

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account + Dimensions</p></th>
<th><p>Debit</p></th>
<th><p>Credit</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>300-12300-51002</p></td>
<td><p>350</p></td>
<td><p></p></td>
<td><p>Advanced ledger entry line</p></td>
</tr>
<tr class="even">
<td><p>100-39810-51001</p></td>
<td><p></p></td>
<td><p>350</p></td>
<td><p>Advanced ledger entry line</p></td>
</tr>
</tbody>
</table>


**Ledger entries generated from the posting definition**

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account + Dimensions</p></th>
<th><p>Debit</p></th>
<th><p>Credit</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>300-11001</p></td>
<td><p></p></td>
<td><p>350</p></td>
<td><p>Summary entry</p></td>
</tr>
<tr class="even">
<td><p>900-11001</p></td>
<td><p></p></td>
<td><p>350</p></td>
<td><p>Summary entry</p></td>
</tr>
<tr class="odd">
<td><p>900-37300</p></td>
<td><p>350</p></td>
<td><p></p></td>
<td><p>Summary entry</p></td>
</tr>
<tr class="even">
<td><p>100-11001</p></td>
<td><p>350</p></td>
<td><p></p></td>
<td><p>Summary entry</p></td>
</tr>
<tr class="odd">
<td><p>900-11001</p></td>
<td><p>350</p></td>
<td><p></p></td>
<td><p>Summary entry</p></td>
</tr>
<tr class="even">
<td><p>900-37301</p></td>
<td><p></p></td>
<td><p>350</p></td>
<td><p>Summary entry</p></td>
</tr>
</tbody>
</table>


## Examples: General ledger year-end close

Public sector organizations use posting definitions in the year-end closing of the general ledger accounts. Posting definitions can be used to close the accounts to fund balances or retained earnings, based on the fund (dimension) class attribute, together with the account close type attribute. Posting definitions are required to close the general ledger accounts and to transfer balances to the opening period in the new fiscal year.


> [!NOTE]
> <P>To use posting definitions for year-end closing and opening, follow these steps:</P>
> <UL>
> <LI>
> <P>Select the <STRONG>Create closing transactions during transfer</STRONG> check box on the <STRONG>Fiscal year close</STRONG> FastTab in the <STRONG>Ledger</STRONG> area of the <STRONG>General ledger parameters</STRONG> form.</P>
> <LI>
> <P>Create a closing account in the <STRONG>Main accounts - chart of accounts: %1</STRONG> form.</P></LI></UL>



**Examples:**

The following posting definition examples show the year-end close for governmental funds and proprietary funds.

## Governmental funds example

**Governmental funds - Posting definition – Match criteria – Row 1**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Account structure</strong></p></th>
<th><p><strong>Match account number</strong>*</p></th>
<th><p><strong>Priority</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Expense</p></td>
<td><p>- - -</p></td>
<td><p>1</p></td>
</tr>
</tbody>
</table>


\*A blank value in the **Match account number** field means that all matching accounts in the defined account structure will be part of the matching rule.

**Governmental funds - Posting definition – Generated entries for Match criteria – Row 1**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Account structure</strong></p></th>
<th><p><strong>Generated account number</strong></p></th>
<th><p><strong>Generated debit/credit</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Account structure</p></td>
<td><p>-37300</p>
<p>(Unreserved fund balance )</p></td>
<td><p>Balancing</p></td>
</tr>
</tbody>
</table>


**Governmental funds - Posting definition – Match criteria – Row 2**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Account structure</strong></p></th>
<th><p><strong>Match account number</strong>*</p></th>
<th><p><strong>Priority</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Expense</p></td>
<td><p>- - -</p></td>
<td><p>1</p></td>
</tr>
</tbody>
</table>


\*A blank value in the **Match account number** field means that all matching accounts in the defined account structure will be part of the matching rule.

**Governmental funds - Posting definition – Generated entries for match criteria – Row 2**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Account structure</strong></p></th>
<th><p><strong>Generated account number</strong></p></th>
<th><p><strong>Generated debit/credit</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Account structure</p></td>
<td><p>-37300</p>
<p>(Unreserved fund balance )</p></td>
<td><p>Balancing</p></td>
</tr>
</tbody>
</table>


**Governmental funds - Posting definition – Match criteria – Row 3**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Account structure</strong></p></th>
<th><p><strong>Match account number</strong>*</p></th>
<th><p><strong>Priority</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Revenue</p></td>
<td><p>- - -</p></td>
<td><p>1</p></td>
</tr>
</tbody>
</table>


\*A blank value in the **Match account number** field means that all matching accounts in the defined account structure will be part of the matching rule.

**Governmental funds - Posting definition – Generated entries for match criteria – Row 3**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Account structure</strong></p></th>
<th><p><strong>Generated account number</strong></p></th>
<th><p><strong>Generated debit/credit</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Account structure</p></td>
<td><p>-37300</p>
<p>(Unreserved fund balance )</p></td>
<td><p>Balancing</p></td>
</tr>
</tbody>
</table>


After you set up the posting definition, assign it to the **General ledger close** transaction type the **Transaction posting definitions** form. (Click **General ledger** \> **Setup** \> **Posting** \> **Transaction posting definitions**.)

**Governmental funds - Transactions with the accounts, dimension values, and amounts**

The ledger accounts balance through the selected period in the **Opening transactions** form. (Click **General ledger** \> **Periodic** \> **Fiscal year close** \> **Opening transactions**.)

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account + Dimensions</p></th>
<th><p>Debit</p></th>
<th><p>Credit</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>101-66100-130</p></td>
<td><p>250.00</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


**Governmental funds - Ledger entries generated from the posting definition**

Generated ledger entries are created to record the closing entry.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account + Dimensions</p></th>
<th><p>Debit</p></th>
<th><p>Credit</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>101-66100-130-</p></td>
<td><p></p></td>
<td><p>250.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>101-37300</p></td>
<td><p>250.00</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


In this example, Fund 101 is defined as a **Governmental** fund class in the **Fund** form. (Click **General ledger** \> **Setup** \> **Fund** \> **Funds**.) In the **Transaction posting definitions** form, the **General ledger close** transaction type is associated with the **Governmental** fund class and the posting definition.

The posting definition matches on any account part of the Expense account structure. Therefore, when 101-66100-130- is evaluated, the same ledger account is used, the amount is reversed to close the account, and the balancing generated ledger entry is created.

## Proprietary funds example

**Proprietary funds - Posting definition – Match criteria – Row 1**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Account structure</strong></p></th>
<th><p><strong>Match account number</strong>*</p></th>
<th><p><strong>Priority</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Balance</p></td>
<td><p>- - -</p></td>
<td><p>1</p></td>
</tr>
</tbody>
</table>


\*A blank value in the **Match account number** field means that all matching accounts in the defined account structure will be part of the matching rule.

**Proprietary funds - Posting definition – Generated entries for match criteria – Row 1**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Account structure</strong></p></th>
<th><p><strong>Generated account number</strong></p></th>
<th><p><strong>Generated debit/credit</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Account structure</p></td>
<td><p>-37310</p>
<p>(Retained earnings)</p></td>
<td><p>Balancing</p></td>
</tr>
</tbody>
</table>


**Proprietary funds - Posting definition – Match criteria – Row 2**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Account structure</strong></p></th>
<th><p><strong>Match account number</strong>*</p></th>
<th><p><strong>Priority</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Expense</p></td>
<td><p>- - -</p></td>
<td><p>1</p></td>
</tr>
</tbody>
</table>


\*A blank value in the **Match account number** field means that all matching accounts in the defined account structure will be part of the matching rule.

**Proprietary funds - Posting definition – Generated entries for match criteria – Row 2**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Account structure</strong></p></th>
<th><p><strong>Generated account number</strong></p></th>
<th><p><strong>Generated debit/credit</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Account structure</p></td>
<td><p>-37310</p>
<p>(Retained earnings)</p></td>
<td><p>Balancing</p></td>
</tr>
</tbody>
</table>


**Proprietary funds - Posting definition – Match criteria – Row 3**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Account structure</strong></p></th>
<th><p><strong>Match account number</strong>*</p></th>
<th><p><strong>Priority</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Revenue</p></td>
<td><p>- - -</p></td>
<td><p>1</p></td>
</tr>
</tbody>
</table>


\*A blank value in the **Match account number** field means that all matching accounts in the defined account structure will be part of the matching rule.

**Proprietary funds - Posting definition – Generated entries for match criteria – Row 3**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Account structure</strong></p></th>
<th><p><strong>Generated account number</strong></p></th>
<th><p><strong>Generated debit/credit</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Account structure</p></td>
<td><p>-37310</p>
<p>(Retained earnings)</p></td>
<td><p>Balancing</p></td>
</tr>
</tbody>
</table>


After you set up the posting definition, you assign it to the **General ledger close** transaction in the **Transaction posting definitions** form. (Click **General ledger** \> **Setup** \> **Posting** \> **Transaction posting definitions**.)

**Proprietary funds - Transactions with the accounts, dimension values, and amounts**

The ledger accounts balance through the selected period in the **Opening transactions** form. (Click **General ledger** \> **Periodic** \> **Fiscal year close** \> **Opening transactions**.)

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account + Dimensions</p></th>
<th><p>Debit</p></th>
<th><p>Credit</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>601-66100-130</p></td>
<td><p>250.00</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


**Proprietary funds - Ledger entries generated from the posting definition**

Generated ledger entries are created to record the closing entry.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account + Dimensions</p></th>
<th><p>Debit</p></th>
<th><p>Credit</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>601-66100-130-</p></td>
<td><p></p></td>
<td><p>250.00</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>601-37310</p></td>
<td><p>250.00</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


In this example, Fund 601 is defined as a **Proprietary** fund class in the **Fund** form. (Click **General ledger** \> **Setup** \> **Fund** \> **Funds**.) In the **Transaction posting definitions** form, the **General ledger close** transaction type is associated with the **Proprietary** fund class and the posting definition.

The posting definition matches on any account part of the Expense account structure. Therefore, when 601-66100-130- is evaluated, the same ledger account is used, the amount is reversed to close the account, and the balancing generated ledger entry is created.

## General budget reservations (Public sector)

 If you are in the public sector and use general budget reservations, see also [Set up general budget reservation rules and reservation types (Public sector)](set-up-general-budget-reservation-rules-and-reservation-types-public-sector.md).


> [!NOTE]
> <P>General budget reservations are available only if the <STRONG>Public Sector</STRONG> configuration key is selected and if Microsoft Dynamics AX 2012 R3 Cumulative Update 8 is installed with the following hotfix: KB3047235</P>



Posting definitions for general budget reservations enable you to update different general ledger accounts for various types of general budget reservation.

**Posting definition – Match criteria – Row 1**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Account structure</strong></p></th>
<th><p><strong>Match account number</strong></p></th>
<th><p><strong>Priority</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Expense</p></td>
<td><p>Blank</p>
<p></p></td>
<td><p>1</p></td>
</tr>
</tbody>
</table>


\* A blank value in the **Match account number** field means that all matching accounts in the defined account structure will be part of the matching rule.

**Posting definition – Generated entries for Match criteria – Row 1**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Account structure</strong></p></th>
<th><p><strong>Generated account number</strong></p></th>
<th><p><strong>Generated debit/credit</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Balance</p></td>
<td><p>- 300143 - -(Encumbrance account)</p>
<p></p></td>
<td><p>Same</p></td>
</tr>
<tr class="even">
<td><p>Balance</p></td>
<td><p>- 300144 - -(Reserve for encumbrance account)</p>
<p></p></td>
<td><p>Balancing</p></td>
</tr>
</tbody>
</table>


**Transactions with the accounts, dimension values, and amounts**

The accounts and dimension values come from the accounting distributions that you enter for a general budget reservation line.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account + Dimensions</p></th>
<th><p>Debit</p></th>
<th><p>Credit</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>101-66100-153</p></td>
<td><p>250.00</p></td>
<td><p></p></td>
<td><p>Main account 66100 is an expense account.</p></td>
</tr>
</tbody>
</table>


**Ledger entries generated from the posting definition**

Generated ledger entries are created to record the encumbrance.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Account + Dimensions</p></th>
<th><p>Debit</p></th>
<th><p>Credit</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>101-300143</p></td>
<td><p>250.00</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>101-300144</p></td>
<td><p></p></td>
<td><p>250.00</p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


In this example, any Expense account structure matches the posting definition criteria. Therefore, when 101-66100-153 is evaluated, the generated ledger entries for the encumbrances are created.

## See also

[About posting definitions](about-posting-definitions.md)

[Set up posting definitions](set-up-posting-definitions.md)

[Set up advanced ledger entries (Public sector)](set-up-advanced-ledger-entries-public-sector.md)

[Assign posting definitions to transaction posting types](assign-posting-definitions-to-transaction-posting-types.md)

[Posting definitions (form)](https://technet.microsoft.com/en-us/library/hh227607\(v=ax.60\))

[Transaction posting definitions (form)](https://technet.microsoft.com/en-us/library/hh242550\(v=ax.60\))

[Examples: Posting definitions](examples-posting-definitions.md)

  


