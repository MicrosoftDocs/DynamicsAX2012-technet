---
title: "What's new: Country-specific features for Germany (DEU)"
TOCTitle: Country-specific features for Germany
ms:assetid: d8ec2205-08ed-4975-b307-021b603d65ab
ms:mtpsurl: https://technet.microsoft.com/library/Dn527238(v=AX.60)
ms:contentKeyID: 59623366
author: Khairunj
ms.date: 06/08/2015
mtps_version: v=AX.60
---

# What's new: Country-specific features for Germany (DEU) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In Microsoft Dynamics AX 2012, we changed and added country-specific functionality for Germany. For more information, see the tables that apply to your version of the product.

## What’s new in Microsoft Dynamics AX 2012 R2

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
<td><p>Calculating acquisition adjustments</p></td>
<td><p>Acquisition adjustments in Germany must be calculated as if the adjustment was made on the first day of the business year, regardless of the date on which the adjustment transaction was created.</p>
<p>For more information, see <a href="deu-about-additional-acquisition-depreciation.md">(DEU) About additional acquisition depreciation</a>.</p></td>
</tr>
</tbody>
</table>


## What’s new in cumulative update 6 for Microsoft Dynamics AX 2012 R2

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
<td><p>Generate the European Union (EU) sales list for Germany.</p></td>
<td><p>You can generate the EU sales list as an ELMA5 text file. You can generate the EU sales list monthly, bimonthly, or quarterly.</p>
<p>For more information, see <a href="deu-generate-the-eu-sales-list.md">(DEU) Generate the EU sales list</a>.</p></td>
</tr>
<tr class="even">
<td><p>Modify the default IP addresses for VAT reports</p></td>
<td><p>A legal entity can manually update the default electronic tax server IP addresses to be used for submitting VAT reports. If you delete all of the server IP addresses in the <strong>Electronic tax declaration server addresses</strong> form, then you can reopen the <strong>Electronic tax declaration setup</strong> form again to update the default server IP addresses.</p>
<p>For more information, see <a href="deu-set-up-electronic-tax-declaration.md">(DEU) Set up electronic tax declaration</a>.</p></td>
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
<td><p>You can generate electronic payment files for SEPA direct debits in the updated ISO 20022 XML format and the pain.008.001.02 version. You can generate the payment files for a selected SEPA country format.</p>
<p>For more information, see <a href="create-payments-for-customers-who-have-direct-debit-mandates.md">Create payments for customers who have direct debit mandates</a>.</p></td>
</tr>
<tr class="even">
<td><p>Generate electronic payment files for SEPA credit transfers.</p></td>
<td><p>You can generate electronic payment files in the SEPA credit transfer format, which supports the pain.001.001.03 version. You can generate the payment files for a selected SEPA country format.</p>
<p>For more information, see <a href="aut-bel-deu-esp-fin-fra-ita-nld-create-a-country-region-specific-sepa-credit-transfer-payment-file.md">(AUT, BEL, DEU, ESP, FIN, FRA, ITA, NLD) Create a country/region-specific SEPA credit transfer payment file</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Generate and maintain EU entry certificates for items or services.</p></td>
<td><p>You can set up and generate an EU certificate together with a customer invoice or a packing slip when you deliver items or services to EU countries. You can then upload a signed EU certificate that you have received from a customer or a third party, and attach the certificate to the customer invoice that is associated with it. You can update and maintain the status of the EU certificates to determine whether a certificate has been issued or received.</p>
<p>You can generate the <strong>Control</strong> report to verify the status of EU entry certificates. You can correct an incorrect status for an EU entry certificate. If an EU entry certificate is associated with an incorrect invoice, you can remove the incorrect reference, and then attach the EU entry certificate to the correct invoice.</p></td>
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
<td><p>Generate electronic payment files for Single Euro Payments Area (SEPA) credit transfers in the PAIN.001.003.03 XML file format.</p></td>
<td><p>You can generate electronic payment files for SEPA credit transfers in the PAIN.001.003.03 XML file format.</p>
<p>For more information, see <a href="aut-bel-deu-esp-fin-fra-ita-nld-create-a-country-region-specific-sepa-credit-transfer-payment-file.md">(AUT, BEL, DEU, ESP, FIN, FRA, ITA, NLD) Create a country/region-specific SEPA credit transfer payment file</a>.</p></td>
</tr>
<tr class="even">
<td><p>Generate electronic payment files for SEPA direct debits in the PAIN.008.003.02 XML file format.</p></td>
<td><p>You can generate electronic payment files for SEPA direct debits in the PAIN.008.003.02 XML file format.</p>
<p>You can use the COR1 scheme for SEPA direct debit mandates. You can specify the number of days to allow for the first and recurring bank submissions that use the COR1 scheme.</p>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="create-payments-for-customers-who-have-direct-debit-mandates.md">Create payments for customers who have direct debit mandates</a></p></li>
<li><p><a href="set-up-sepa-direct-debit-mandate.md">Set up SEPA direct debit mandate</a></p></li>
<li><p><a href="sepa-direct-debit-overview.md">SEPA direct debit overview</a></p></li>
<li><p><a href="add-direct-debit-mandate-information-to-a-customer-account.md">Add direct debit mandate information to a customer account</a></p></li>
</ul></td>
</tr>
</tbody>
</table>


## What’s new in Microsoft Dynamics AX 2012 R3 Cumulative Update 9

For the straight-line-life remaining depreciation method, a new parameter is added to allow you to apply rules for additional acquisition and acquisition adjustment transactions. After you enable the parameter, the depreciation of additional acquisitions and acquisition adjustments is calculated according to the following rules:

  - The amounts of additional acquisitions that are posted during the year of initial acquisition are depreciated starting from the depreciation run date.

  - The amounts of additional acquisitions posted in the year later than year of initial acquisition are depreciated starting from the first day of the year.

  - The amount of additional depreciation is added to the periodic depreciation amount in the respective period.

If you create depreciation adjustments with basis adjustments marked on the Fixed asset value model, the depreciation adjustment transaction will be created according to the following rules:

  - For additional acquisitions posted in the year of initial acquisition, the depreciation amount is adjusted starting from the depreciation run date.

  - For additional acquisitions posted in the year later than year of initial acquisition, the depreciation amounts are adjusted starting from the first date of the year.

  


