---
title: "What's new: Country-specific features for Spain (ESP)"
TOCTitle: Country-specific features for Spain
ms:assetid: a6f5749d-440d-4cb0-9fb0-3777187c995b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn527194(v=AX.60)
ms:contentKeyID: 59623323
ms.date: 06/08/2015
mtps_version: v=AX.60
---

# What's new: Country-specific features for Spain (ESP) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In cumulative update 7 for Microsoft Dynamics AX 2012 R2, we changed and added country-specific functionality for Spain.

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
<td><p>You can generate electronic payment files for SEPA) direct debits in the updated ISO 20022 XML format and the pain.008.001.02 version. You can generate the payment files for a selected SEPA country format.</p>
<p>For more information, see <a href="create-payments-for-customers-who-have-direct-debit-mandates.md">Create payments for customers who have direct debit mandates</a>.</p></td>
</tr>
<tr class="even">
<td><p>Generate electronic payment files for SEPA credit transfers.</p></td>
<td><p>You can generate electronic payment files in the SEPA credit transfer format, which supports the pain.001.001.03 version. You can generate the payment files for a selected SEPA country format.</p>
<p>For more information, see <a href="aut-bel-deu-esp-fin-fra-ita-nld-create-a-country-region-specific-sepa-credit-transfer-payment-file.md">(AUT, BEL, DEU, ESP, FIN, FRA, ITA, NLD) Create a country/region-specific SEPA credit transfer payment file</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Generate a payment due date compliance report that includes both vendor payments and promissory note transactions.</p></td>
<td><p>When you generate the payment due date compliance report, the transactions from the vendor payments and promissory note journals are included on the report.</p></td>
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
<td><p>eInvoice updates</p></td>
<td><p>To support the January 15, 2015 legal requirements that all invoices sent to or received from Spanish Government Agencies and State owned companies must be submitted only in electronic format, Dynamics AX has introduced new functionality. This functionality also follows the requirement to generate Electronic invoices (eInvoices) using a standard format defined by the AEAT (Spanish Tax Administration) known as “FacturaE”. The new functionality includes:</p>
<ul>
<li><p>New eInvoices parameters in the <strong>Accounts Receivable</strong> module that can help to define different business scenarios.</p></li>
<li><p>Ability to create eInvoices automatically when a sales invoice, free text invoice, project invoice, or credit note is posted.</p></li>
<li><p>Electronic signing of eInvoices, either by company certificate or user certificate.</p></li>
<li><p>Functionality for defining if eInvoices will be created automatically for particular customers.</p></li>
<li><p>The ability to monitor, re-create, re-sign, or re-send eInvoices in case these actions must be performed multiple times.</p></li>
<li><p>Supported versions of “FacturaE” format are 3.2 and 3.2.1.</p></li>
</ul>
<p>For more information, see:<a href="https://mbs.microsoft.com/files/customer/ax/learning/whitepapers/microsoftdynamicsaxspanisheinvoicesfacturaesupport.pdf">https://mbs.microsoft.com/files/customer/AX/Learning/whitepapers/MicrosoftDynamicsAXSpanisheInvoicesFacturaEsupport.pdf</a>.</p></td>
</tr>
<tr class="even">
<td><p>Spanish Declaration 347</p></td>
<td><p>The Spanish Tax Agency (AEAT) has issued the Order HAP/1732/2014 defining a new 347 model that supersedes the previous model approved per Order EHA 3012/2008. Microsoft Dynamics AX 2012 R3 Cumulative Update 9 includes the solution for address abbreviation length and position in exported files for the tenants.</p>
<p>For more information about this change and the corresponding changes in Dynamics AX, see <a href="https://mbs.microsoft.com/customersource/spain/ax/learning/documentation/white-papers/msdaxdec347wpspain">https://mbs.microsoft.com/customersource/Spain/AX/learning/documentation/white-papers/msdaxdec347wpspain</a>.</p></td>
</tr>
</tbody>
</table>

  


