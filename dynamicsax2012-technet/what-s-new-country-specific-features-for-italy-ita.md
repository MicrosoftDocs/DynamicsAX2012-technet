---
title: "What's new: Country-specific features for Italy (ITA)"
TOCTitle: Country-specific features for Italy
ms:assetid: 9d4e046e-1fb9-4997-b9cd-8206981a7531
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn527202(v=AX.60)
ms:contentKeyID: 59623331
ms.date: 06/08/2015
mtps_version: v=AX.60
---

# What's new: Country-specific features for Italy (ITA) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In Microsoft Dynamics AX 2012 R2, we changed and added country-specific functionality for Italy. For more information, see the tables that apply to your version of the product.

## What’s new in AX 2012 R2

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Updates to the Italian fiscal journal report</p></td>
<td><p>The Italian fiscal journal report lists all the vouchers and journal entries that are created for a specific month. The report now includes the following information: line numbers, the posting date, voucher numbers, tax vouchers, the document date, account numbers and descriptions, customer or vendor numbers and names, posting text, and posting amounts. The report also includes debit and credit totals, which are calculated yearly. Additionally, if a header is printed on the report, the company’s name and tax exempt number, and the page numbers, must be printed.</p>
<p>For more information, see <a href="http://support.microsoft.com/kb/2711379">KB article 2711379: “Country-specific update for the Fiscal Journal report in Italy for Microsoft Dynamics AX 2012”</a>.</p></td>
</tr>
<tr class="even">
<td><p>Updates to the Italian sales tax payment report</p></td>
<td><p>The Italian sales tax payment report lists all the sales and purchase invoices and credit notes that must be printed in a periodic register. This periodic register is also known as a sales tax book. The sales tax payment report has been updated to comply with requirements of the Italian sales tax system.</p></td>
</tr>
<tr class="odd">
<td><p>Updates to the Italian black list report</p></td>
<td><p>The Italian government maintains a list of countries/regions that have preferential income tax. You can print a report that includes taxable transactions for the legal entities that reside in those countries/regions. You can then electronically submit this report in an ASCII file.</p>
<p>For more information, see <a href="ita-italian-black-list-report-blacklist.md">(ITA) Italian black list report (BlackList)</a>.</p></td>
</tr>
</tbody>
</table>


## What’s new in cumulative update 7 for Microsoft Dynamics AX 2012 R2

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Generate electronic payment files for Single Euro Payments Area (SEPA) direct debits.</p></td>
<td><p>You can generate electronic payment files for SEPA direct debits in the updated ISO 20022 XML format and the pain.008.001.02 version. You can also select the SEPA country/region format for which to generate the payment files.</p>
<p>For more information, see <a href="create-payments-for-customers-who-have-direct-debit-mandates.md">Create payments for customers who have direct debit mandates</a>.</p></td>
</tr>
<tr class="even">
<td><p>Generate electronic payment files for SEPA credit transfers.</p></td>
<td><p>You can generate electronic payment files in the SEPA credit transfer format, which supports the pain.001.001.03 version. You can also select the SEPA country/region format for which to generate the payment files.</p>
<p>For more information, see <a href="aut-bel-deu-esp-fin-fra-ita-nld-create-a-country-region-specific-sepa-credit-transfer-payment-file.md">(AUT, BEL, DEU, ESP, FIN, FRA, ITA, NLD) Create a country/region-specific SEPA credit transfer payment file</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Generate a Spesometro declaration for domestic value-added tax (VAT) transactions.</p></td>
<td><p>You can generate a Spesometro declaration report to declare domestic VAT transactions for which invoices must be issued by the taxable legal entities that are involved in the transaction. These domestic VAT transactions include the receipt or supply of items or services. You can also declare the following transaction types:</p>
<ul>
<li><p>Credit note transactions</p></li>
<li><p>Non-invoice transactions for which the amount is in a predefined range</p></li>
<li><p>Non-recoverable VAT transactions</p></li>
<li><p>Intra-community service invoice transactions</p></li>
</ul></td>
</tr>
</tbody>
</table>


## What’s new in Microsoft Dynamics AX 2012 R3

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Updates to the Italian black list report</p></td>
<td><p>A report that includes all taxable transactions for the legal entities that reside in those countries/regions can be printed. You can also exclude transactions that are below the threshold amount from the Italian black list report by applying a threshold to the transactions. The report can then be generated and exported in the ASCII file format.</p>
<p>For more information, see <a href="ita-italian-black-list-report-blacklist.md">(ITA) Italian black list report (BlackList)</a>.</p></td>
</tr>
</tbody>
</table>


## What’s new in Microsoft Dynamics AX 2012 R3 Cumulative Update 9

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Black list submissions</p></td>
<td><p>The frequency of Black list submissions has changed from monthly or quarterly to annually, however, this change applies only for amounts greater than €10,000 (instead of €500).</p></td>
</tr>
<tr class="even">
<td><p>Inventory movements report</p></td>
<td><p>The Italian report, <strong>Inventory movements in a period</strong>, contains transaction sequences that are divided by item and with on-hand quantities.</p></td>
</tr>
<tr class="odd">
<td><p>Electronic invoice formats</p></td>
<td><p>The new version 1.1 of electronic invoices format, known as FatturaPA, is now available and supported. The previous version 1.0 is discontinued.</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

