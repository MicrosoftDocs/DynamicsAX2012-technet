---
title: "What's new: Country-specific features for Poland (POL)"
TOCTitle: Country-specific features for Poland
ms:assetid: 84445b2a-8bef-4c0e-9093-fd6913da4c4f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn527167(v=AX.60)
ms:contentKeyID: 59623296
ms.date: 06/08/2015
mtps_version: v=AX.60
---

# What's new: Country-specific features for Poland (POL) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In Microsoft Dynamics AX 2012 R2, we changed and added country-specific functionality for Poland. For more information, see the tables that apply to your version of the product.

For more information about specific features for Poland, see [TechNet Library for Application Users - Poland](http://go.microsoft.com/fwlink/?linkid=299917).

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
<td><p>Track Numeru Identyfikacji Podatkowej (NIP) tax identification information</p></td>
<td><p>Legal entities in Poland can now store and track tax identification numbers (NIP) for a customer or vendor. Each NIP record stores the customer or vendor name, the tax ID number, the tax exempt number, and the address that is on file for the tax exempt number.</p>
<p>NIP data is entered in a new <strong>NIP table</strong> form and appears in several journal forms in Microsoft Dynamics AX. When transactions are updated or posted, the NIP details are posted to the tax tables. From the tax tables, the NIP details are then printed on the Polish value-added tax (VAT) register.</p>
<p>For more information, see <a href="http://go.microsoft.com/fwlink/?linkid=301254">(POL) Create a NIP record to define VAT register data</a>.</p></td>
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
<td><p>Tax cost adjustments for overdue vendor payments</p></td>
<td><p>You can set up the parameters that are used to identify the transactions that are included in the overdue vendor debt Corporate Income Tax (CIT) and Personal Income Tax (PIT) journal. You can then create an overdue vendor debt CIT and PIT journal for a period. The journal contains the following information:</p>
<ul>
<li><p>A list of overdue payments that require tax cost adjustments. You can manually adjust tax costs for these payments.</p></li>
<li><p>A list of overdue payments for which tax cost was adjusted previously, and for which you made the payments to the vendors. You can reverse the tax cost adjustments for these payments.</p></li>
</ul>
<p>You can exclude debts from the list of overdue payments.</p>
<p>You can generate the <strong>Overdue CIT and PIT journal</strong> report, which contains details about the overdue payments and the tax cost adjustments.</p>
<p>For more information, see <a href="pol-set-up-and-create-an-overdue-vendor-debt-cit-and-pit-journal.md">(POL) Set up and create an overdue vendor debt CIT and PIT journal</a>.</p></td>
</tr>
<tr class="even">
<td><p>VAT corrections for overdue payments</p></td>
<td><p>You can set up the parameters that are used to identify the transactions that are included in the overdue debt journal. You can then generate the following lists of overdue customer or vendor payments for a period parameter that you set up:</p>
<ul>
<li><p>Overdue customer or vendor payments for which you have not yet posted output VAT corrections. You can post VAT corrections for these overdue payments. The corrections are posted in the VAT entries and in the general ledger.</p></li>
<li><p>Overdue customer or vendor payments for which you posted output VAT corrections.</p></li>
<li><p>Overdue customer or vendor payments for which you posted output VAT corrections and received the payments from the customer, or for which you made the payments to the vendor. You can reverse output VAT corrections for these payments.</p></li>
</ul>
<p>You can also exclude customer or vendor debts from the list of overdue payments.</p></td>
</tr>
<tr class="odd">
<td><p>Use exchange rates from the European Central Bank to recalculate VAT for sales invoices that use foreign currency.</p></td>
<td><p>You can use the currency exchange rates that are specified by the European Central Bank to recalculate VAT in Polish złoty for sales invoices that are issued by using foreign currencies. You can also use the currency exchange rates that are specified by the National Bank of Poland to recalculate VAT for sales invoices.</p>
<p>For more information, see <a href="pol-set-up-vat-exchange-rates-for-foreign-currency-sales-invoices.md">(POL) Set up VAT exchange rates for foreign currency sales invoices</a>.</p></td>
</tr>
</tbody>
</table>


## What’s new in Microsoft Dynamics AX 2012 R3 Cumulative Update 9

You can now create advance invoices for prepayments in Retail, including automatic creation, posting and printing of an advance invoice for a customer order deposit received through Retail Enterprise POS, and settlement of the advance invoice upon invoicing the order.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

