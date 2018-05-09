---
title: "What's new: Country-specific features for Brazil (BRA)"
TOCTitle: Country-specific features for Brazil
ms:assetid: a7489a4d-65f6-4600-9e82-b4a6daf0657f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn486931(v=AX.60)
ms:contentKeyID: 59631346
ms.date: 06/09/2015
mtps_version: v=AX.60
---

# What's new: Country-specific features for Brazil (BRA) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In Microsoft Dynamics AX 2012 R2, we changed and added country-specific functionality for Brazil. This topic is divided into two sections. The first section outlines the key features that have a broad impact on Brazilian installations, such as features that support fiscal establishments, fiscal documents, and specific requirements for regulatory reporting. The second section describes additional changes to country-specific functionality for Brazil. For more information about specific features for Brazil, see [TechNet Library for Application Users - Brazil](http://go.microsoft.com/fwlink/?linkid=299904).

## Key features for Brazil

## Overview

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Item</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Required</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="even">
<td><p>Feature areas affected</p></td>
<td><p>All</p></td>
</tr>
<tr class="odd">
<td><p>Stakeholders</p></td>
<td><p>Business decision makers</p>
<p>Technical decision makers</p>
<p>Implementation team members</p>
<p>Independent software vendors (ISVs)/developers</p>
<p>Partners</p></td>
</tr>
</tbody>
</table>


## New functionality

Country/region-specific features are now enabled for organizations that have some of or all their operations based in Brazil. These features are implicitly enabled when you install AX 2012 R2 and then set up a legal entity that has an address in Brazil.

## Comparison with Microsoft Dynamics AX 2009

Features for Brazil have changed considerably since AX 2009. Microsoft Dynamics AX 2012 includes new functionality for fiscal establishments and fiscal documents.

## Fiscal establishments and fiscal documents

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012 R2</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Use fiscal establishments to issue fiscal documents for sales invoices, purchase invoices, and free text invoices.</p></td>
<td><p>Not available</p></td>
<td><p>A fiscal establishment is a physical location of a legal entity. A fiscal establishment is assigned a tax registration number, issues and receives legal documentation, and assesses or pays taxes. The tax registration number is either Cadastro Nacional da Pessoa Jurídica (CNPJ) or Inscrição Estadual (IE). A legal entity can have multiple fiscal establishments. Therefore, a fiscal establishment is required to issue and receive fiscal documents in processes that involve sales orders, sales returns, purchase orders, purchase returns, free text invoices, transfer orders, and tax fiscal documents.</p></td>
<td><p>You can track fiscal operations and purposes for regulatory reporting.</p></td>
</tr>
<tr class="even">
<td><p>Transfer warehouse items between warehouses that are located in different fiscal establishments, or that are owned by third-party entities.</p></td>
<td><p>Not available</p></td>
<td><p>When you transfer items between fiscal establishments, the following transfer fiscal documents are issued and received:</p>
<ul>
<li><p><strong>Outbound fiscal document</strong> – Ship items to a warehouse that is located in a different fiscal establishment. You can issue an outbound fiscal document when you ship the items.</p></li>
<li><p><strong>Inbound fiscal document</strong> – Receive items that are shipped from a warehouse that is located in a different fiscal establishment. You can register an inbound fiscal document when you receive the items.</p></li>
</ul></td>
<td><p>You can track transfers of items for reporting of fiscal operations.</p></td>
</tr>
<tr class="odd">
<td><p>Create fiscal documents and reports from a single source.</p></td>
<td><p>Fiscal documents for sales and purchases were saved to separate locations in the database.</p></td>
<td><p>A fiscal document framework is used to guarantee that a fiscal document that is posted conforms to rules and a specific structure, regardless of the transaction from which the fiscal document was originally generated.</p>
<p>The fiscal document framework keeps all fiscal documents in a single repository that contains all information that the government requires for reporting, regardless of the reporting format.</p>
<p>The fiscal document viewer is also available as part of the fiscal document framework. The fiscal document viewer lets you drill down to all information that is related to fiscal documents:</p>
<ul>
<li><p>Relationships between fiscal documents and their source documents</p></li>
<li><p>Fiscal references, sales taxes, referenced processes, fatura and installments, miscellaneous charges, legal texts, and additional information</p></li>
</ul></td>
<td><p>This feature provides a structure for creating customized reports for fiscal operations.</p></td>
</tr>
</tbody>
</table>


## Additional features

For more information about additional country-specific features that we added for Brazil, see the tables that apply to your version of the product.

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
<td><p>Updates to Fiscal operation codes for Brazil</p></td>
<td><p>The Códigos Fiscais de Operações E Prestações (CFOP) codes now include a direction (incoming or outgoing) and a purpose (return, shipment, or fiscal establishment transfer). The CFOP matrix lets you determine the CFOP codes that are used in each transaction, and new transaction types were added:</p>
<ul>
<li><p><strong>Free text invoice</strong> – CFOP codes that can be used in free text invoices.</p></li>
<li><p><strong>Item requirement</strong> – CFOP codes that can be used in project item requirement forms.</p></li>
<li><p><strong>Third party transfer</strong> – CFOP codes that can be used for shipments of items to customers or vendors, or receipts of items from customers or vendors, in transfer orders.</p></li>
<li><p><strong>Fiscal establishment transfer</strong> – CFOP codes that can be used for transfers between fiscal establishments in transfer orders.</p></li>
<li><p><strong>Tax fiscal document</strong> – CFOP codes that can be used for tax fiscal document transactions.</p></li>
</ul>
<p>Additionally, the earlier transaction types are still valid:</p>
<ul>
<li><p><strong>Sales</strong> – CFOP codes that can be used in sales orders and sales quotations.</p></li>
<li><p><strong>Purchase</strong> – CFOP codes that can be used in purchase orders, purchase quotations, purchase requisitions, and vendor invoices.</p></li>
</ul>
<p>For more information about the CFOP matrix, see <a href="bra-set-up-the-cfop-matrix.md">(BRA) Set up the CFOP matrix</a>.</p>
<p>For more information about CFOP changes and how the changes affect upgrade, see <a href="bra-cfop-code-upgrade.md">(BRA) CFOP code (upgrade)</a>.</p></td>
</tr>
<tr class="even">
<td><p>Use fiscal establishments to post sales and purchases for Brazil.</p></td>
<td><p>A fiscal establishment is a physical location of a legal entity. A fiscal establishment requires tax registration numbers (CNPJ or IE), issues and receives legal documentation, and assesses or pays taxes. Because a legal entity can have multiple fiscal establishments, each fiscal establishment is now required to issue and receive fiscal documents in processes that involve sales orders, sales returns, purchase orders, purchase returns, free text invoices, transfer orders, and tax fiscal documents.</p>
<p>In processes that involve sales orders, sales returns, purchase orders, purchase returns, and transfer orders, the fiscal establishment is determined by a relation that is defined between the fiscal establishment and the site.</p>
<p>In processes that involve free text invoices and tax fiscal documents, the fiscal establishment has to be determined by the user before fiscal document posting.</p>
<p>For more information, see <a href="bra-create-a-fiscal-establishment.md">(BRA) Create a fiscal establishment</a> and <a href="bra-about-fiscal-establishments.md">(BRA) About fiscal establishments</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Purchase posting enhancements for Brazil</p></td>
<td><p>You can create and post a purchase invoice by specifying the CFOP codes. You must specify CFOP codes for a purchase order, a returned item, or an item that has a product type of <strong>Item</strong>. You can also specify the fiscal document type for a return purchase order.</p>
<p>You can also perform the following tasks:</p>
<ul>
<li><p>Set up the fiscal document text for a purchase order or a vendor invoice.</p></li>
<li><p>Create reference invoices that link one or more vendor invoice references when an invoice is created.</p></li>
<li><p>Generate, post, and print the vendor invoice from a non-taxpayer vendor, and then post the purchase invoice.</p></li>
<li><p>Cancel an incorrect fiscal document, and indicate that the fiscal document is canceled, and that all ledger and financial transactions are reversed.</p></li>
</ul>
<p>For more information, see <a href="bra-set-up-the-cfop-codes.md">(BRA) Set up the CFOP codes</a>.</p></td>
</tr>
<tr class="even">
<td><p>Check payments and Bordero payments for Brazil</p></td>
<td><p>You can use a check or the Bordero method of payment to make vendor payments. The check or Bordero payment is generated by Microsoft SQL Server Reporting Services (SSRS). When you use a check, you can post and print one check per bank or vendor. The check is issued in the name of the bank or the vendor. When you use the Bordero method of payment, you can post and print one Bordero payment per bank. You can also generate the Bordero report for a bank.</p>
<p>You can reverse a check or Bordero payment. When you reverse a payment, the transaction is canceled, and the related vendor invoices are available for settlement. If taxes were withheld from the check or Bordero payment, the withholding taxes are also reversed.</p>
<p>For more information, see <a href="bra-about-check-payments-and-bordero-payments.md">(BRA) About check payments and Bordero payments</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Brazilian fiscal documents for the direct delivery process</p></td>
<td><p>You can now relate taxes with fiscal values 1 and 3 by setting a delivery item sales tax group and a delivery sales tax group for the sales order when a CFOP has an associated delivery CFOP that allows a delivery slip to be used together with the Nota fiscal eletrônica (NF-e) feature when a delivery slip fiscal document is posted.</p>
<p>You can cancel a delivery slip fiscal document.</p>
<p>For more information, see <a href="bra-set-up-the-cfop-codes.md">(BRA) Set up the CFOP codes</a>.</p></td>
</tr>
<tr class="even">
<td><p>Fiscal document texts</p></td>
<td><p>Brazilian law requires that you print text for some transactions. Legal text is a short message that is printed on fiscal documents and the Documento Auxiliar da Nota fiscal eletrônica (DANFE). Legal text provides additional information for a fiscal document, such as the fiscal purpose of the document or complementary information about the fiscal document.</p>
<p>You can now set up master data for legal text, and link that data to the CFOP, vendor, customer, item, sales order, or purchase order. You can set legal text so that it is printed automatically on fiscal documents and DANFE. Legal text is also sent to Sistema Publico de Escrituração Digital (SPED).</p>
<p>For more information, see <a href="bra-setting-up-fiscal-document-texts.md">(BRA) Setting up fiscal document texts</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Project debit notes for Brazil</p></td>
<td><p>You can use debit notes to reimburse expenses that a service provider makes for a project. You can also cancel an incorrect debit note. When you cancel a debit note, the related transactions are reversed, and the status of the original debit note is updated to <strong>Canceled</strong>.</p>
<p>For more information, see <a href="bra-about-project-debit-notes.md">(BRA) About project debit notes</a>.</p></td>
</tr>
<tr class="even">
<td><p>Cancel a posted project invoice for Brazil.</p></td>
<td><p>You can cancel a project invoice that has been posted if the posting date is not in a closed period, and if the customer invoice has not been paid or settled. The cancellation reverses all postings for the transaction to ledger accounts such as accounts receivable, tax accounts, and sales.</p>
<p>For more information, see <a href="bra-cancel-a-project-invoice.md">(BRA) Cancel a project invoice</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Withholding tax for Brazil</p></td>
<td><p>Withholding tax can now be determined by fiscal document line. Therefore, the process now resembles the process for determining taxes.</p>
<p>You can specify a withholding tax group for customers and vendors. You can also specify an item withholding tax group that is used by default for items on sales order and purchase order lines, but that can be modified.</p>
<p>For more information, see <a href="bra-set-up-a-withholding-tax.md">(BRA) Set up a withholding tax</a>.</p></td>
</tr>
<tr class="even">
<td><p>Updates to Sales and purchase operation types in Brazil</p></td>
<td><p>Companies in Brazil follow a different process for posting purchase orders and sales orders when there is no inventory movement or related customer/vendor transaction. You implement this process by configuring the purchase and sales operation types in the <strong>Operation type</strong> form. The operation types control the process of sales and purchase postings while you perform the following tasks:</p>
<ul>
<li><p>Create inventory movements.</p></li>
<li><p>Create customer/vendor transactions.</p></li>
<li><p>Identify posting account numbers.</p></li>
<li><p>Identify customer/vendor posting profiles</p></li>
<li><p>Identify items that are in a transit warehouse.</p></li>
</ul>
<p>The Brazilian government also requires that companies in Brazil create fiscal documents for every inbound and outbound transaction, regardless of the transaction type.</p>
<p>For more information, see <a href="bra-set-up-operation-types.md">(BRA) Set up operation types</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Enhancements for Brazilian tax calculations</p></td>
<td><p>You can set up taxation codes based on the validity period that is specified by the government. Multiple fiscal values can be specified for one taxation code. When the taxation code is selected for the sales tax code and the item sales tax group, the correct taxation code and fiscal value should be selected.</p>
<p>The following new tax types were added:</p>
<ul>
<li><p><strong>ICMS-ST</strong> – This tax type determines tributary substitution of Imposto Sobre Circulação de Mercadorias e Serviços (ICMS).</p></li>
<li><p><strong>ICMS-DIF</strong> – This tax type determines whether a purchase has a differential rate in an interstate purchase of ICMS.</p></li>
</ul>
<p>For ICMS-ST Tax types, you can select a tributary substitution method of either <strong>Markup</strong> or <strong>Simplified</strong> to calculate the tributary substitution. Tax substitution is the collection of sales tax at the first point of sale, where the markup tax rate is estimated by the fiscal authorities. This is done to expedite the collection of taxes.</p>
<div class="alert">

> [!NOTE]
> <P>You can no longer change the taxation code or fiscal value on sales order and purchase order lines.</P>


</div>
<p>For more information, see <a href="bra-set-up-and-calculate-tax-on-sales-and-purchases.md">(BRA) Set up and calculate tax on sales and purchases</a> <a href="https://technet.microsoft.com/en-us/library/jj663982(v=ax.60)">(BRA) Sales tax codes (modified form)</a>.</p></td>
</tr>
<tr class="even">
<td><p>Updates to fiscal document types for Brazil</p></td>
<td><p>The fiscal document type classifies the type of fiscal document that is involved in sales, purchases, and tax fiscal document transactions between companies. The fiscal document type defines the number sequence, series, document model, specie, and layout of the purchase invoice, sales invoice, free text invoice, and tax fiscal document transaction.</p>
<p>You can modify a fiscal document type if no transaction has been created that uses the fiscal document type.</p>
<p>You can specify the default fiscal document type for customers and vendors. You can specify the fiscal document type for sales orders, purchase orders, free text invoices, and tax fiscal document transactions.</p>
<p>For more information, see <a href="bra-about-updates-to-fiscal-document-types.md">(BRA) About updates to fiscal document types</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Distribute direct and indirect costs among manufactured products for Brazil.</p></td>
<td><p>The setup of cost centers in the absorption cost functionality lets you calculate and post the direct and indirect costs that are incurred by the manufacturing process for a fiscal period. You can then calculate absorption costs by distributing the total direct and indirect costs among the products that are manufactured during the fiscal period.</p>
<p>For more information, see <a href="bra-set-up-create-and-manage-absorption-costs.md">(BRA) Set up, create, and manage absorption costs</a>.</p></td>
</tr>
<tr class="even">
<td><p>Project management and accounting</p></td>
<td><p>Project invoices are integrated with fiscal documents, and you can generate an NF-e federal or municipal from the project invoices that have been posted.</p>
<p>You can cancel a project invoice. In this case, you also cancel a fiscal document that is related to the project invoice.</p>
<p>You can generate a delivery slip fiscal document from a project. This feature combines the functionality for item requirements and delivery slips.</p>
<p>For more information, see <a href="bra-cancel-a-project-invoice.md">(BRA) Cancel a project invoice</a> and <a href="bra-post-delivery-slips-for-project-item-requirements.md">(BRA) Post delivery slips for project item requirements</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Generate fiscal documents for project sales orders and project item requirements for Brazil when packing slips are posted.</p></td>
<td><p>In AX 2012 R2, when the packing slips for project sales orders and project item requirements are posted, the taxes that are included are calculated, and the corresponding fiscal documents are generated.</p>
<p>For more information, see <a href="bra-about-calculation-of-taxes.md">(BRA) About calculation of taxes</a> and <a href="bra-about-fiscal-documents-and-the-fiscal-document-framework.md">(BRA) About fiscal documents and the fiscal document framework</a>.</p></td>
</tr>
<tr class="even">
<td><p>Complementary invoices</p></td>
<td><p>You must create a complementary invoice or nota fiscal complementar to adjust a fiscal document that was generated for an incorrect price, Imposto Sobre Produtos Industrializados (IPI), or ICMS amount. A complementary invoice is issued only to adjust a positive difference. For example, a complementary invoice is generated if the price of an item on the original invoice is incorrect, and the correct price for the item is higher than the price that is recorded on the original invoice. You can create a complementary invoice to adjust errors in the price or quantity of goods or services, in the tax percentage, or in the tax calculation. The complementary invoice is a fiscal document that complements the original fiscal document. All information except miscellaneous charges is updated from the original fiscal document. You cannot add or delete lines from a complementary invoice.</p>
<p>For more information, see <a href="bra-create-and-post-a-sales-complementary-fiscal-document.md">(BRA) Create and post a sales complementary fiscal document</a>.</p></td>
</tr>
<tr class="odd">
<td><p>NF-e process</p></td>
<td><p>The following enhancements have been made to the NF-e process:</p>
<ul>
<li><p>You can set up web services, rejection codes, and schemas for a domain.</p></li>
<li><p>For each fiscal establishment, you can set up a certificate, environment, NF-e version, authority, template, schema validation, automatic printing of the DANFE after NF-e approval, and a contingency mode for NF-e.</p></li>
<li><p>You can set up web services that are related to an authority. You can then share the same set of web services between fiscal establishments that are located in different states.</p></li>
<li><p>You can print the DANFE as a pro-forma document without posting the invoice. The pro-forma DANFE is marked with the &quot;Sem validade fiscal&quot; watermark. The DANFE can also be printed automatically when the NF-e is approved by the government tax authority (SEFAZ).</p></li>
<li><p>You can check and update a rejected or pending NF-e on the <strong>Rejected fiscal documents with pending cancellation</strong> list page and the <strong>Fiscal documents pending an update to contingency mode</strong> list page.</p></li>
</ul>
<p>For more information, see <a href="bra-about-the-nf-e-process.md">(BRA) About the NF-e process</a>.</p></td>
</tr>
<tr class="even">
<td><p>Updates to the general ledger for Brazil</p></td>
<td><p>The updates to the general ledger for Brazil include the following changes:</p>
<ul>
<li><p>New rules for day books.</p></li>
<li><p>You can generate accounting books for trial balances.</p></li>
<li><p>You can use the analytical ledger.</p></li>
<li><p>You can open and close terms for legal accounting reports.</p></li>
<li><p>You can create parent ledger accounts that have children.</p></li>
<li><p>Default descriptions and journal text for withholding tax, interest, and fine payments.</p></li>
<li><p>Consolidated company accounts.</p></li>
<li><p>Updates to several general ledger forms and reports.</p></li>
</ul>
<p>For more information, see <a href="bra-general-ledger.md">(BRA) General ledger</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Use fiscal establishments to post sales and purchases for Brazil.</p></td>
<td><p>Use fiscal establishments to issue fiscal documents for sales invoices, purchase invoices, and free text invoices. A fiscal establishment is a physical location of a legal entity. A fiscal establishment requires tax registration numbers (CNPJ or IE), issues and receives legal documentation, and assesses or pays taxes. A legal entity can have multiple fiscal establishments.</p>
<p>For more information, see <a href="bra-about-fiscal-establishments.md">(BRA) About fiscal establishments</a>.</p></td>
</tr>
<tr class="even">
<td><p>Enhancements to free text invoices for Brazil</p></td>
<td><p>You can create and post a free text invoice by specifying fiscal information. You can also perform the following tasks:</p>
<ul>
<li><p>Add fiscal document texts or legal texts to a free text invoice.</p></li>
<li><p>Correct a free text invoice to generate a corrected free text invoice and a credit note for the canceled invoice.</p></li>
<li><p>Cancel a free text invoice.</p></li>
<li><p>View information about a bill of lading for fixed asset sales in the <strong>Post free text invoice</strong> form.</p></li>
<li><p>Create and post a free text invoice that includes miscellaneous charges for a fixed asset.</p></li>
</ul>
<p>In accordance with Brazilian regulations, the revenue in the subledger journal is booked based on the gross amount and includes all the taxes that apply to sales. The taxes that apply to sales are booked as credit in the tax payable account and as debit in the tax expense account. You can use the <strong>Sales tax offset</strong> posting type to book the tax expenses.</p>
<p>For more information, see <a href="bra-free-text-invoices.md">(BRA) Free text invoices</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Import fiscal documents for Brazil.</p></td>
<td><p>You can issue an import fiscal document when you create a purchase order to import items from a foreign vendor. You can specify the import declaration information for a purchase order for a foreign vendor before you post the purchase order. You can also cancel an incorrect import fiscal document.</p>
<p>For more information, see <a href="bra-about-import-fiscal-documents.md">(BRA) About import fiscal documents</a>.</p></td>
</tr>
<tr class="even">
<td><p>ICMS tax documents for Brazil</p></td>
<td><p>You can use ICMS tax documents to record tax adjustment transactions between fiscal establishments by issuing an NF-e. You can also and recover the ICMS tax amount in installments for the purchase of fixed assets.</p>
<p>For more information, see <a href="bra-about-icms-tax-fiscal-documents.md">(BRA) About ICMS tax fiscal documents</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Fiscal documents and the fiscal document framework</p></td>
<td><p>A fiscal document framework is used to guarantee that fiscal documents that are posted conform to rules and a specific structure, regardless of the transaction from which a fiscal document was originally generated.</p>
<p>The fiscal document framework keeps all fiscal documents in a single repository. This repository contains all the information that the government requires for reporting, regardless of the reporting format.</p>
<p>The fiscal document viewer is also available as part of the fiscal document framework. The fiscal document view lets you drill down to all information that is related to fiscal documents:</p>
<ul>
<li><p>Relationships between fiscal documents and their source documents</p></li>
<li><p>Fiscal references, sales taxes, referenced processes, fatura and installments, miscellaneous charges, legal texts, and additional information</p></li>
</ul>
<p>For more information, see <a href="bra-about-fiscal-documents-and-the-fiscal-document-framework.md">(BRA) About fiscal documents and the fiscal document framework</a>.</p></td>
</tr>
<tr class="even">
<td><p>Uptake of Brazilian localization requirements for retail product management</p></td>
<td><p>Microsoft Dynamics AX 2012 for Retail supports several features that help users easily manage their retail products. For example, you can modify product attributes by using a mass update tool, manage products by using the retail category hierarchy feature, and manage products by using the released product model that is supported in AX 2012. This feature adds the Brazil-specific product attribute fields to these features, so that users in Brazil can take advantage of these tools to easily manage their retail products.</p>
<p>For more information, see <a href="about-retail-hierarchies.md">About retail hierarchies</a> and <a href="about-setting-up-retail-products.md">About setting up retail products</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Transfer items between fiscal establishments.</p></td>
<td><p>You can transfer warehouse items between warehouses that are located in different fiscal establishments, or transfer items to third-party warehouses, by using transfer fiscal documents.</p>
<p>When you transfer items between fiscal establishments, the following transfer fiscal documents are issued and received:</p>
<ul>
<li><p><strong>Outbound fiscal document</strong> – Ship items to a warehouse that is located in a different fiscal establishment. You can issue an outbound fiscal document when you ship the items.</p></li>
<li><p><strong>Inbound fiscal document</strong> – Receive items that are shipped from a warehouse that is located in a different fiscal establishment. You can register an inbound fiscal document when you receive the items.</p></li>
</ul>
<p>For more information, see <a href="bra-about-transfer-orders.md">(BRA) About transfer orders</a>.</p></td>
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
<td><p>Cancel an NF-e by using an event web service.</p></td>
<td><p>You can cancel an NF-e by using an event web service. You must indicate a reason that is at least 15 characters long when you cancel a fiscal document.</p>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="bra-set-up-nf-e-federal-parameters.md">(BRA) Set up NF-e federal parameters</a></p></li>
<li><p><a href="bra-cancel-a-customer-fiscal-document.md">(BRA) Cancel a customer fiscal document</a></p></li>
<li><p><a href="bra-cancel-a-vendor-fiscal-document.md">(BRA) Cancel a vendor fiscal document</a></p></li>
<li><p><a href="bra-cancel-a-transfer-fiscal-document.md">(BRA) Cancel a transfer fiscal document</a></p></li>
<li><p><a href="bra-cancel-a-sales-complementary-fiscal-document.md">(BRA) Cancel a sales complementary fiscal document</a></p></li>
<li><p><a href="bra-cancel-a-purchase-complementary-fiscal-document.md">(BRA) Cancel a purchase complementary fiscal document</a></p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Sistema de Contingência do Ambiente Nacional (SCAN) contingency mode for Brazil</p></td>
<td><p>You can use the SCAN contingency environment to generate, export, or import an NF-e when the origin Secretaria da Fazenda (SEFAZ) environment is not available.</p>
<p>You can turn on SCAN contingency mode when the origin SEFAZ is not available. You can turn off SCAN contingency mode when the origin SEFAZ is available.</p>
<p>For more information, see <a href="bra-set-up-and-use-scan-contingency-mode.md">(BRA) Set up and use SCAN contingency mode</a> and <a href="bra-scan-contingency-mode.md">(BRA) SCAN contingency mode</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Issue import fiscal documents for services.</p></td>
<td><p>You can issue an import fiscal document when you create a purchase order to import a service from a foreign vendor.</p>
<p>For more information, see <a href="bra-about-import-fiscal-documents.md">(BRA) About import fiscal documents</a> and <a href="bra-create-and-post-a-purchase-order-for-a-foreign-vendor.md">(BRA) Create and post a purchase order for a foreign vendor</a>.</p></td>
</tr>
<tr class="even">
<td><p>Updates to the taxation origin of items</p></td>
<td><p>The <strong>Taxation origin</strong> field is updated and now includes the following eight options:</p>
<ul>
<li><p><strong>National, not related to codes 3 to 5</strong></p></li>
<li><p><strong>Imported, direct import, not related to code 6</strong></p></li>
<li><p><strong>Imported, acquired in internal market, and not related to code 7</strong></p></li>
<li><p><strong>National, import content greater than 40 percent</strong></p></li>
<li><p><strong>National, production compliant with Decreto-Lei nº 288/67, and laws nºs 8.248/91, 8.387/91, 10.176/01 e 11.484/07</strong></p></li>
<li><p><strong>National, import content lower than or equal to 40 percent</strong></p></li>
<li><p><strong>Imported, direct import, no similar item in internal market, and included in the CAMEX list and natural gas</strong></p></li>
<li><p><strong>Imported, acquired in internal market, with no similar in country/region, and included in the CAMEX list and natural gas</strong></p></li>
</ul>
<p>For more information, see <a href="bra-set-up-taxation-origin-for-items.md">(BRA) Set up taxation origin for items</a> and <a href="bra-set-up-fiscal-information.md">(BRA) Set up fiscal information</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Fiscal books information in Microsoft Dynamics AX 2009 can be integrated with Microsoft Dynamics AX 2012.</p></td>
<td><p>Fiscal documents from Microsoft Dynamics AX 2009 can be transferred to a single-computer installation of Microsoft Dynamics AX 2012. You can then assess, declare, pay, and adjust ICMS, ICMS-ST, IPI taxes and prepare fiscal books reports in Microsoft Dynamics AX 2012.</p>
<p>For more information, see <a href="fiscal-books-integration-with-microsoft-dynamics-ax-2009.md">Fiscal books integration with Microsoft Dynamics AX 2009</a>, <a href="perform-a-single-computer-installation.md">Perform a single-computer installation</a>, and <a href="bra-manage-the-fiscal-books-integration.md">(BRA) Manage the fiscal books integration</a>.</p></td>
</tr>
<tr class="even">
<td><p>Fiscal books ease-of-use and retail compliance enhancements</p></td>
<td><p>You can now create booking periods by using a wizard. Tax accountants can mark fiscal documents that have been audited and when they were audited. Retail-specific report features for fiscal books now include a Z-report viewer and fiscal receipt viewer for retail. A retail summary report is available.</p>
<p>For more information, see <a href="bra-create-a-new-booking-period.md">(BRA) Create a new booking period</a> and <a href="bra-working-with-fiscal-books.md">(BRA) Working with fiscal books</a>.</p></td>
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
<td><p>Generate and send the DANFE as a PDF file.</p></td>
<td><p>You can generate the DANFE for an NF-e as a PDF file. You can then send the DANFE PDF file and the NF-e XML file that is generated for an approved NF-e to a third-party customer or vendor via email.</p>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="bra-about-the-nf-e-process.md">(BRA) About the NF-e process</a></p></li>
<li><p><a href="bra-set-up-email-parameters-and-email-templates-for-an-nf-e.md">(BRA) Set up email parameters and email templates for an NF-e</a></p></li>
<li><p><a href="bra-generate-danfe-as-pdf-files.md">(BRA) Generate DANFE as PDF files</a></p></li>
<li><p><a href="bra-generate-emails-for-approved-nf-e-and-attach-danfe-pdf-files-and-nf-e-xml-files-to-the-emails.md">(BRA) Generate emails for approved NF-e and attach DANFE PDF files and NF-e XML files to the emails</a></p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Configure multiple fiscal printers.</p></td>
<td><p>You can configure parameters, such as the configuration type, configuration purpose, and configuration values, for multiple fiscal printers. You can then associate a fiscal printer configuration with multiple stores. Alternatively, you can associate a store with multiple fiscal printer configurations.</p>
<p>For more information, see <a href="bra-configure-fiscal-printers.md">(BRA) Configure fiscal printers</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Approximate taxes for items and services</p></td>
<td><p>Approximate taxes are the taxes from production and the supply chain that apply to an item. You can specify the approximate tax percentages for national and imported items for each fiscal classification code and exception code. You can specify the approximate tax percentage that is applied to an item or service. You can also specify the source and the text about the approximate tax percentage. When you create and post sales orders or free text invoices, Microsoft Dynamics AX calculates the approximate tax amounts for items by using the approximate tax percentages that you specify.</p>
<p>When you print a sales fiscal document, the following information for approximate taxes is printed on the fiscal document:</p>
<ul>
<li><p>The approximate tax amount for each item</p></li>
<li><p>The total approximate tax amount for all the items</p></li>
<li><p>The source and the text for the approximate tax percentage</p></li>
</ul>
<p>The information for approximate taxes is printed on the following sales fiscal documents:</p>
<ul>
<li><p>Fiscal documents that are generated from sales orders</p></li>
<li><p>Fiscal documents that are generated from free text invoices</p></li>
<li><p>NF-e documents</p></li>
<li><p>DANFE</p></li>
<li><p>Fiscal receipts</p></li>
</ul>
<p>For more information, see <a href="bra-set-up-approximate-taxes-for-items-and-services.md">(BRA) Set up approximate taxes for items and services</a>.</p></td>
</tr>
<tr class="even">
<td><p>Import and verify NF-e XML documents and DANFE from email messages.</p></td>
<td><p>You can perform to following tasks to set up and use Microsoft Dynamics AX to import NF-e XML documents and DANFE that you receive in email messages:</p>
<ul>
<li><p>Set up email accounts to import XML files and DANFE for electronic fiscal documents.</p></li>
<li><p>Set up the Instituto Brasileiro de Geografia e Estatistica (IBGE) code for a state, and then set up an authority for the state.</p></li>
<li><p>Import the NF-e XML documents and DANFE that you receive in email messages, and then perform the following tasks:</p>
<ul>
<li><p>View the XML document for an NF-e.</p></li>
<li><p>View the DANFE of the NF-e XML document.</p></li>
<li><p>Inquire about the current status of the NF-e at the SEFAZ by using the access key.</p></li>
</ul></li>
<li><p>Manually enter an access key for an NF-e for which you did not receive an XML document.</p></li>
<li><p>Post electronic fiscal documents that have access keys that are not validated by the SEFAZ. Alternatively, you can set up Microsoft Dynamics AX to post only the electronic fiscal documents that have access keys that are validated by the SEFAZ.</p></li>
<li><p>If you post the electronic fiscal documents for which access keys are not available in the <strong>Received NF-e XML documents</strong> form, you can update the access keys or XML documents for the electronic fiscal documents after posting. You can view the posted NF-e documents that require access keys or XML documents:</p>
<ul>
<li><p>NF-e documents for which the access keys are not validated by the SEFAZ</p></li>
<li><p>NF-e documents for which the status is updated from approved to canceled</p></li>
<li><p>NF-e documents for which XML attachments are not available</p></li>
<li><p>NF-e documents for which the access keys are not available in the NF-e XML documents that are received</p></li>
</ul></li>
<li><p>View the electronic fiscal documents that are not posted, and for which you receive the access keys.</p></li>
</ul>
<p>You can also set up Microsoft Dynamics AX to inquire about the status of NF-e access keys at the SEFAZ multiple times. The last of these inquiries is made after the time during which the vendor can cancel an approved NF-e has passed.</p>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="bra-set-up-import-and-verify-nf-e-xml-documents-and-danfe-that-you-receive-in-emails.md">(BRA) Set up, import, and verify NF-e XML documents and DANFE that you receive in emails</a></p></li>
<li><p><a href="bra-import-and-verify-nf-e-xml-documents-and-danfe-that-you-receive-in-emails.md">(BRA) Import and verify NF-e XML documents and DANFE that you receive in emails</a></p></li>
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
<td><p>Other tax accounting Tax accounting enhancements for fiscal books.</p></td>
<td><p>You can prepare and generated a text file with the format layout required by the Validador SINTEGRA application. You are also able to import the text file that is generated in Fiscal Books into the Validador SINTEGRA application. You can automatically generate tax assessment files for GIA-SP, GIA-ST and SINTEGRA.</p>
<ul>
<li><p>GIA-SP – You can prepare, generate, and import a text file with the format layout required by the Nova GUIA application.</p></li>
<li><p>GIA-ST – You can generate and deliver the GIA-ST tax assessment to the state tax authority.</p></li>
<li><p>SINTEGRA – You can prepare, generate, and import a text file with the format layout required by the Validador SINTEGRA application.</p></li>
</ul>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="bra-set-up-parameters-for-sintegra-tax-statements.md">(BRA) Set up parameters for Sintegra tax statements</a></p></li>
<li><p><a href="bra-generate-the-sintegra-tax-statement.md">(BRA) Generate the Sintegra tax statement</a></p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Tax assessment enhancements for fiscal books.</p></td>
<td><p>You can create the ISS tax assessment per fiscal establishment. This includes determining the balance of ISS tax amount per service code and tax rate (%) combination. The ISS tax assessment includes ISS tax coming from issuing service fiscal documents (NFS-e). Also, you can pay the retained ISS tax when applicable. You can more easily enter tax adjustments for ICMS amounts and automatically update General ledger.</p>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="bra-set-up-adjustment-codes-to-use-to-adjust-icms-tax-on-fiscal-documents.md">(BRA) Set up adjustment codes to use to adjust ICMS tax on fiscal documents</a></p></li>
<li><p><a href="bra-assess-pay-declare-and-adjust-iss-taxes.md">(BRA) Assess, pay, declare, and adjust ISS taxes</a></p></li>
<li><p><a href="bra-enter-and-post-fiscal-books-adjustments-benefits-and-incentives.md">(BRA) Enter and post fiscal books adjustments, benefits, and incentives</a></p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Tax payments in fiscal books.</p></td>
<td><p>You can register the ICMS tax order payment (GARE) for a specific fiscal establishment with all required information. An accounts payable clerk can create a payment based on this information, and you can inquire on tax order payments and their status.</p>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="bra-assess-pay-declare-and-adjust-icms-and-icms-st-taxes.md">(BRA) Assess, pay, declare, and adjust ICMS and ICMS-ST taxes</a></p></li>
<li><p><a href="bra-set-up-brazilian-parameters.md">(BRA) Set up Brazilian parameters</a></p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>SPED accounting statements for fiscal books</p></td>
<td><p>You can generate and import the SPED ECD text file. After the text file is imported into the government application, a receipt number is generated and is stored in Microsoft Dynamics AX. Fiscal Books can generate accounting statements in the format that is required for Block J of the SPED ECD text file. These accounting statements include Balance sheet and Profit and Loss statements that use the hierarchy of accounts defined in the chart of accounts of the company.</p>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="bra-set-up-parameters-for-sped-ecd-text-files.md">(BRA) Set up parameters for SPED ECD text files</a></p></li>
<li><p><a href="bra-generate-and-validate-the-sped-ecd-statement.md">(BRA) Generate and validate the SPED ECD statement</a></p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>SPED contributions in fiscal books</p></td>
<td><p>You can generate and import the text file for SPED EFD Contributions. Record F100 includes operation transactions such as the following examples:</p>
<ul>
<li><p>For revenue:</p>
<ul>
<li><p>Bank applications</p></li>
<li><p>Other rental offices</p></li>
</ul></li>
<li><p>For expenses:</p>
<ul>
<li><p>Bank administration fees</p></li>
<li><p>Goods storage</p></li>
<li><p>Leasing</p></li>
</ul></li>
<li><p>Presumed credit</p></li>
</ul>
<p>For more information, see the following topic:</p>
<ul>
<li><p><a href="bra-all-non-fiscal-operations.md">(BRA) All non fiscal operations</a></p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Reverse opposite sign amounts</p></td>
<td><p>You can post negative debit amounts as credits, and negative credit amounts as debits. You can then run the update process to verify whether negative debit amounts or negative credit amounts already exist in posted journal transactions in the general ledger. The update process reverses the sign so that negative debit amounts become credits, and negative credit amounts become debits.</p>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="bra-mex-set-up-general-ledger-to-reverse-and-update-opposite-sign-amounts.md">(BRA, MEX) Set up General ledger to reverse and update opposite sign amounts</a></p></li>
<li><p><a href="https://technet.microsoft.com/en-us/library/aa557286(v=ax.60)">General ledger parameters (form)</a></p></li>
</ul></td>
</tr>
</tbody>
</table>


## What’s new in cumulative update 8 for Microsoft Dynamics AX 2012 R3

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
<td><p>Support for NFC-e in Microsoft Dynamics AX for Retail POS</p></td>
<td><p>A Nota Fiscal Consumidor eletrônica (NFC-e) is an electronic fiscal document that is generated and printed to register the sale of an item to a consumer. You can perform the following tasks for NFC-e documents in Microsoft Dynamics AX and Microsoft Dynamics AX for Retail POS:</p>
<ul>
<li><p>Generate the NFC-e XML and send it to the tax authority for authorization.</p></li>
<li><p>Generate and print a Documento Auxiliar da Nota Fiscal Eletrônica (DANFE) NFC-e for a sales transaction that is performed at the retail point of sale (POS).</p></li>
<li><p>Generate and print a DANFE NFC-e in contingency mode.</p></li>
<li><p>Record customer details before you generate the DANFE NFC-e.</p></li>
<li><p>Post an NFC-e statement for a retail POS sales transaction.</p></li>
<li><p>Void an NFC-e that was issued for a retail POS sales transaction.</p></li>
<li><p>Generate the tax assessment and SPED files for NFC-es.</p></li>
</ul>
<p>For more information, see <a href="bra-set-up-nfc-e-parameters-to-issue-an-nfc-e-for-a-pos-sales-transaction.md">(BRA) Set up NFC-e parameters to issue an NFC-e for a POS sales transaction</a>.</p></td>
</tr>
<tr class="even">
<td><p>Electronic Funds Transfer (EFT) integration for Software Express (SiTef) and Direcao</p></td>
<td><p>You can make credit card payments for a POS sales transaction by using EFT integration for Software Express or Direcao. The EFT integration is available for a POS register and lets you perform NFC-e and fiscal printer sales transactions. After you make a credit card payment using Retail POS, you can print a card payment receipt.</p></td>
</tr>
<tr class="odd">
<td><p>Upgrade to NF-e version 3.1</p></td>
<td><p>You can use the Nota Fiscal eletrônica (NF-e) version 3.1 to generate the NF-e XML file that you submit electronically to the Secretaria da Fazenda (SEFAZ) for any sales or purchase transaction that is made by your fiscal establishment. This upgrade is mandatory to help you comply with the legal requirements of the Brazilian government. When you select version 3.1, the fiscal document layout will contain the following additional information:</p>
<ul>
<li><p>The destination of a fiscal document</p></li>
<li><p>The Imposto sobre Circulação de Mercadorias e Serviços (ICMS tax ) contribution type for customers and vendors</p></li>
<li><p>The foreigner identification number of a customer or vendor who is a foreign national</p></li>
<li><p>The time zone offset for invoice posting when the SEFAZ server is located in a different time zone</p></li>
<li><p>The time zone differences for fiscal documents that are posted in contingency mode</p></li>
<li><p>The Programa de Integração Social (PIS) and Contribuição para o Financiamento da Seguridade Social (COFINS) taxes discount on fiscal document lines for sales that are made to a Superintendência da Zona Franca de Manaus (SUFRAMA) region</p></li>
</ul>
<p>The NF-e XML file is formatted based on the NF-e version that you select. For the NF-e XML file validation process, you must select the NF-e schema that is compatible with the selected NF-e version in the NF-e federal parameters form.</p>
<p>Upgrade process is included to allow users from previous versions to initialize some fields that were introduced in the new layout version of NF-e 3.10.</p></td>
</tr>
<tr class="even">
<td><p>PIS and Cofins tax assessment for Cumulative Regime</p></td>
<td><p>You can create tax assessment for PIS and Cofins taxes in the cumulative regime for fiscal organizations. This includes determining the balance of PIS and Cofins tax amount. The PIS and COFINS tax assessment includes the related taxes coming from incoming and outgoing fiscal documents, Retail, non-fiscal operations transactions and withholding taxes. Also, you can generate the PIS and Cofins payment tax when you generate the applicable liability into the account payment module.” You can more easily enter tax adjustments and deductions for PIS and COFINS amounts and automatically update General ledger.This functionality also includes, the generation of block M and records 1300 and 1700 in Sped Contributions.</p></td>
</tr>
<tr class="odd">
<td><p>Updates in Transportation management (TMS)</p></td>
<td><p>You can create and post transfer orders and deliver slip fiscal documents for a given load. In addition to this, users will be able to know which loads are partially or fully invoiced.</p></td>
</tr>
<tr class="even">
<td><p>Call Center</p></td>
<td><p>In the customer services you can handle customers also using the tax registration ID CPF/CNPJ. While archiving the sales order you also archive together the Brazilian localization data in sales orders.</p></td>
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
<th><p>Desription</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Updates to layouts</p></td>
<td><p>SPED ECD layout version 3.0 is now available.</p>
<p></p>
<p>Layout version 009 is now available for Sped Fiscal version 1.08. The layout includes a new field for record H010. This field represents the item valuation that will be picked up from the inventory valuation method that is selected in the item’s model group.</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

