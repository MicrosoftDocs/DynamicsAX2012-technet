---
title: What's new in Microsoft Dynamics AX 2012 R2
TOCTitle: What's new in Microsoft Dynamics AX 2012 R2
ms:assetid: 44593f89-d305-49ad-875a-b1d4e484ad61
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn529285(v=AX.60)
ms:contentKeyID: 59644561
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# What's new in Microsoft Dynamics AX 2012 R2 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In Microsoft Dynamics AX 2012 R2, we added and changed several features. This topic lists the feature changes by module and by country/region, and provides links to related topics.

## New features for AX 2012 R2

The following table outlines the features that were added in AX 2012 R2.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Module</p></th>
<th><p>What’s new</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Accounts payable</p></td>
<td><ul>
<li><p>You can adjust the taxes that are calculated on an invoice line before you post the invoice.</p></li>
<li><p>You can use a payment calendar to control due dates for payments. You can also use the date control to make sure that the calculations of grace periods for interest and fees for payments start on the nearest business day.</p></li>
</ul>
<p>For more information, see <a href="what-s-new-accounts-payable-features.md">What's new: Accounts payable features</a>.</p></td>
</tr>
<tr class="even">
<td><p>Accounts receivable</p></td>
<td><p>You can add freight and other charges to each line in a free text invoice, and distribute charges to dimensions and ledger lines. For more information, see <a href="what-s-new-accounts-receivable-features.md">What's new: Accounts receivable features</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Budgeting</p></td>
<td><p>You can use budget planning in AX 2012 R2 to establish a base budget, prepare and evaluate budget plans, and approve or revise budget plans. For more information, see <a href="what-s-new-budgeting-features.md">What's new: Budgeting features</a>.</p></td>
</tr>
<tr class="even">
<td><p>General ledger</p></td>
<td><ul>
<li><p>Interunit accounting can be used to identify a financial dimension as balancing, so that a balanced balance sheet can be generated for the selected financial dimension.</p></li>
<li><p>Legal entities can have more than one consolidation account.</p></li>
<li><p>Tax registration numbers can be defined at the level of the party address record.</p></li>
<li><p>For each main account in a specific chart of accounts, you can designate a default financial dimension value as a fixed value for each company that uses the chart of accounts.</p></li>
<li><p>You can set up default descriptions for automatic posting.</p></li>
<li><p>There is a new framework for importing exchange rates.</p></li>
<li><p>The General ledger reports have been updated to display amounts in both debit and credit columns.</p></li>
<li><p>You can configure a recurring schedule batch job to clear purchase accrual for product receipt source documents.</p></li>
<li><p>General ledger balances are updated when a process requires balances.</p></li>
<li><p>You can enter a language translation for the main account name and the custom description of the financial dimension value.</p></li>
</ul>
<p>For more information, see <a href="what-s-new-general-ledger-features.md">What's new: General ledger features</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Human resources</p></td>
<td><ul>
<li><p>You can create a budget for filled or vacant positions.</p></li>
<li><p>There are worker education enhancements.</p></li>
<li><p>You can require that applicants and employees pass tests to obtain or hold their position.</p></li>
<li><p>You can copy existing positions, mass update positions, and block position assignments.</p></li>
<li><p>You can adjust multiple values in the compensation grid for fixed compensation plans at the same time.</p></li>
<li><p>You can use an actions process, together with optional workflow, to gather details and easily track history when positions are created or modified.</p></li>
<li><p>There is a new Staffing manager Role Center.</p></li>
<li><p>Eligibility rules provide greater control and fewer errors when you sign up workers for benefits.</p></li>
<li><p>There is a new HR manager Role Center.</p></li>
<li><p>There is a new HR training and development manager Role Center.</p></li>
<li><p>There are enhancements to the benefit setup and the <strong>Benefits</strong> list page.</p></li>
<li><p>Changes have been made to the <strong>HcmWorkerImportService</strong> service for Microsoft Dynamics AX Application Integration Framework (AIF).</p></li>
<li><p>You can require that applicants and employees take or pass designated screenings.</p></li>
</ul>
<p>For more information, see <a href="what-s-new-human-resources-features.md">What's new: Human resources features</a>.</p></td>
</tr>
<tr class="even">
<td><p>Inventory management</p></td>
<td><p>The performance of the Inventory close and Recalculation batch jobs has been significantly improved. For more information, see <a href="what-s-new-inventory-and-warehouse-management-features.md">What's new: Inventory and warehouse management features</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Process manufacturing production and logistics</p></td>
<td><ul>
<li><p>When you define an item, you can specify the concentration of active ingredients, adjust the quantity of material that is required for item production, calculate the amount of money that is paid to a vendor for the item, and select an ingredient type for a formula line.</p></li>
<li><p>You can add the actual value of a base inventory batch attribute to the registered inventory batch of a purchase order.</p></li>
<li><p>You can set up a pricing formula for potency items that is based on batch attributes.</p></li>
<li><p>You can configure an item so that its batch attributes and shelf life information are updated based on the ingredients of the formula that is used to produce the item.</p></li>
<li><p>You can use product sequencing to define one or more sequences that are assigned to various items.</p></li>
</ul>
<p>For more information, see <a href="what-s-new-process-manufacturing-production-and-logistics-features.md">What's new: Process manufacturing production and logistics features</a>.</p></td>
</tr>
<tr class="even">
<td><p>Procurement and sourcing</p></td>
<td><ul>
<li><p>There are enhancements to the change management process for purchase orders.</p></li>
<li><p>An option has been added that lets you define data partitions during the upgrade of Order management data.</p></li>
<li><p>The amount of information that employees must provide before they can submit a new vendor request has been reduced.</p></li>
<li><p>Order management features have been updated in AX 2012 R2.</p></li>
<li><p>In AX 2012 R2, the sales return order line can be associated with the sales agreement line that is related to the order.</p></li>
<li><p>Requisition demand can be fulfilled by means other than a purchase order, such as a transfer order or a production order.</p></li>
<li><p>Product search on the Employee Services site has been improved.</p></li>
</ul>
<p>For more information, see <a href="what-s-new-procurement-and-sourcing-features.md">What's new: Procurement and sourcing features</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Product information management</p></td>
<td><ul>
<li><p>The <strong>Configure line</strong> form in Product configurator is easier to extend.</p></li>
<li><p>You can now view the relationships between actions on planned orders. You can also view relationships to orders that are already approved.</p></li>
<li><p>Fields and controls have been added to the <strong>Edit job list</strong> form to provide shop floor supervisors with a better overview of the production information that is involved in production orders.</p></li>
<li><p>There are additional modeling capabilities in Product configurator.</p></li>
</ul>
<p>For more information, see <a href="what-s-new-product-information-management-features.md">What's new: Product information management features</a>.</p></td>
</tr>
<tr class="even">
<td><p>Production control</p></td>
<td><ul>
<li><p>You can define a formula and perform batch balancing of a potency item that is used in production.<br />
(Process manufacturing, production, and logistics)</p></li>
<li><p>You can configure an item to inherit shelf life and batch attributes from intermediate items of the finished goods.<br />
(Process manufacturing, production, and logistics)</p></li>
<li><p>You can create an attribute-based pricing formula for a potency item.<br />
(Process manufacturing, production, and logistics)</p></li>
<li><p>You can add an actual value for a batch attribute to a registered inventory batch.<br />
(Process manufacturing, production, and logistics)</p></li>
<li><p>You can create sequences for production.<br />
(Process manufacturing, production, and logistics)</p></li>
<li><p>Several features have been added to Lean manufacturing.<br />
(Lean manufacturing)</p></li>
</ul>
<p>For more information, see <a href="what-s-new-production-control-features.md">What's new: Production control features</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Project management and accounting</p></td>
<td><ul>
<li><p>You can specify a worker's hourly cost price on projects as an effective labor rate. The effective labor rate defines the hourly cost if the worker works all the hours in a work week.</p></li>
<li><p>For investment projects, in the <strong>Estimate</strong> <strong>Estimate</strong> form, you can now select the value model that is applied when the value from an estimate project is eliminated to a fixed asset.</p></li>
<li><p>There are several enhancements to project invoice proposals and printing project documents.</p></li>
<li><p>There is improved support for project estimates and revenue recognition.</p></li>
<li><p>There are several improvements to intercompany resource scheduling and several UX improvements.</p></li>
<li><p>Budget checks are now triggered when changes are made to specific fields on hour journals, expense journals, fee journals, and item journals.</p></li>
<li><p>Project items can be consumed immediately and invoiced to the project’s contract funding source, before the vendor invoice for the purchase order is posted, even if an item requirement does not precede the purchase order.</p></li>
<li><p>The funding limits in the project contract can now be used to track revenue that has not yet been posted as commitments.</p></li>
</ul>
<p>For more information, see <a href="what-s-new-project-management-and-accounting-features.md">What's new: Project management and accounting features</a>.</p></td>
</tr>
<tr class="even">
<td><p>Public Sector</p></td>
<td><ul>
<li><p>Several improvements have been made to the Public sector Role Centers and business intelligence content.</p></li>
<li><p>Public sector customers can display revenues and expenditures by financial dimension, by using a combination of data from budget register entries, the general ledger, and budget control.</p></li>
</ul>
<p>For more information, see <a href="what-s-new-public-sector-features.md">What's new: Public sector features</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Retail</p></td>
<td><ul>
<li><p>Microsoft Dynamics AX 2012 for Retail components are easier to install and configure.</p></li>
<li><p>The system diagnostics and options for audit logs are more comprehensive.</p></li>
<li><p>New features are available for point of sale (POS) hardware. For example, a second cash drawer, multiple shifts, multiple POS printers, signature capture, and dual scanners are supported.</p></li>
<li><p>There is now out-of- box support for customer-facing devices in the United States.</p></li>
<li><p>Retailers can use a time clock to keep track of time and attendance for retail store employees.</p></li>
<li><p>The values for store and staff IDs are now stored in global variables that are unique across all companies in a partition.</p></li>
<li><p>New features are available for pn_MSDAXPOS_1st, such as smarter search functionality.</p></li>
<li><p>Retailers can create and manage product catalogs.</p></li>
<li><p>Retailers can group attributes and attribute groups, and apply them to products and categories in a catalog.</p></li>
<li><p>In Microsoft Dynamics AX, retailers can set up and configure an online store that can be published to the Microsoft SharePoint Online store.</p></li>
<li><p>In Microsoft Dynamics AX, retailers can set up and configure an online marketplace to sell goods through established marketplaces, such as eBay and Amazon.com.</p></li>
<li><p>Fulfillment of online retail orders is now supported.</p></li>
<li><p>Customers can order from online stores, and then either have the items shipped to them or pick up the items in the brick-and-mortar stores.</p></li>
<li><p>Retailers can create a retail product catalog in Microsoft Dynamics AX, enhance the product offerings by adding attributes, images, and video, and then publish the catalogs to one or more online channels.</p></li>
<li><p>There are new inventory management features. For example, you can create and maintain product variants, and create bar codes and bar code masks.</p></li>
<li><p>Customers can use the new store locator service to query item availability in stores that are located within a specified distance.</p></li>
<li><p>Cashiers can see more information about products in Microsoft Dynamics AX for Retail POS.</p></li>
<li><p>Cashiers can view additional customer information in Retail POS.</p></li>
<li><p>The Pricing service is more comprehensive, and gives an online store the same advanced pricing and discount capabilities that are currently available in Retail POS.</p></li>
<li><p>AX 2012 R2 includes a new dedicated Retail cube that provides business intelligence data to help retailers make business decisions.</p></li>
<li><p>AX 2012 R2 supports operations that use two versions of Retail POS software at the same time.</p></li>
<li><p>Cashiers can manually enter a discount code for discount offers without having to create a campaign. Discount codes can be applied to both brick-and-mortar stores and online stores.</p></li>
<li><p>You can view all transactions for an online store by using the new inquiry form for online stores.</p></li>
</ul>
<p>For more information, see <a href="what-s-new-retail-features.md">What's new: Retail features</a>.</p></td>
</tr>
<tr class="even">
<td><p>Sales and marketing</p></td>
<td><ul>
<li><p>You can update the name of a party record either in the party record's form or in the role form of the party record.</p></li>
<li><p>Several enhancements have been made to Sales and marketing Role Centers, and to the reporting information that is provided.</p></li>
<li><p>When you update the list of party records that are assigned to an address book, you can update the list of records as a group instead of one record at a time.</p></li>
<li><p>You can generate a lead or opportunity record directly from the target record list of a campaign or call list.</p></li>
<li><p>You can grant permission to view and update cases, based on the case category type and the user's security role.</p></li>
</ul>
<p>For more information, see <a href="what-s-new-sales-and-marketing-features.md">What's new: Sales and marketing features</a>.</p></td>
</tr>
</tbody>
</table>


## Other features

Other features were added or changed in AX 2012 R2.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Feature area</p></th>
<th><p>What’s new</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Combine XPO</p></td>
<td><p>The Combine XPO Tool is a command line program that combines a set of interdependent XPO files into a single XPO. It was moved from InformationSource into the product in AX 2012 R2.</p>
<p>For more information, see <a href="https://technet.microsoft.com/en-us/library/jj225589(v=ax.60)">Combine XPO Tool User Guide</a>.</p></td>
</tr>
<tr class="even">
<td><p>Database split</p></td>
<td><p>AX 2012 R2 has two databases. The business database contains transaction data and master data. The model database contains application objects, which are managed as model files. The model database replaces the application file store (AOD) that previous versions had. You can name the business database. The model database has the same name as the business database, but _model is appended. Both databases must be stored on the same instance of Microsoft SQL Server.</p>
<p>For more information, see <a href="what-s-new-database-changes.md">What's new: Database changes</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Data partitioning</p></td>
<td><p>AX 2012 R2 enables data isolation by using data partitions.</p>
<p>For more information, see <a href="what-s-new-data-partitioning.md">What's new: Data partitioning</a>.</p></td>
</tr>
<tr class="even">
<td><p>E-commerce investments for omni-channel retail</p></td>
<td><p>Several e-commerce features and capabilities are included in AX 2012 R2. Some of these features and capabilities are as follows:</p>
<ul>
<li><p>Centralized management of channels and publishing</p></li>
<li><p>Enhancements to catalog management and publishing, and to attributes</p></li>
<li><p>The addition of navigation hierarchies and category attributes</p></li>
<li><p>A deployment checklist</p></li>
<li><p>Commerce runtime that supports scalable integration of remote sales channels in Microsoft Dynamics AX in near real time</p></li>
<li><p>A starter online store that helps accelerate implementation of an online channel</p></li>
</ul>
<p>For more information, see <a href="what-s-new-retail-features.md">What's new: Retail features</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Enhancements to analytic capabilities</p></td>
<td><p>New cubes have been introduced in AX 2012 R2:</p>
<ul>
<li><p>Budget control cube</p></li>
<li><p>Budget plan cube</p></li>
<li><p>Inventory value cube</p></li>
<li><p>Profit tax totals cube</p></li>
<li><p>Retail cube</p></li>
<li><p>Sales and marketing cube</p></li>
</ul>
<p>Windows PowerShell commands for cube deployment are also supported, as are Power View and data partitions. Additionally, the Business overview Web Part can now display financial indicators or key performance indicators (KPIs).</p>
<p>For more information, see <a href="what-s-new-analytics.md">What's new: Analytics</a>.</p></td>
</tr>
<tr class="even">
<td><p>New features for the Office Add-ins for Microsoft Dynamics AX</p></td>
<td><ul>
<li><p>You can add descriptions to financial dimensions.</p></li>
<li><p>You can lock a template that is created by using the Office Add-ins.</p></li>
<li><p>When you create a workbook by using the Office Add-ins, you can add filters to the data in the workbook.</p></li>
<li><p>The Office Add-ins create localized worksheets, based on the language setting for the current user in Microsoft Dynamics AX.</p></li>
</ul>
<p>For more information, see <a href="what-s-new-microsoft-office-add-in-features.md">What's new: Microsoft Office Add-in features</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Reporting enhancements</p></td>
<td><p>There are several enhancement to reporting in AX 2012 R2:</p>
<ul>
<li><p>Support for data partitions</p></li>
<li><p>Support for report servers that run in SharePoint integration mode</p></li>
<li><p>Support for PowerView</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Microsoft Dynamics AX Application Integration Framework (AIF) enhancements</p></td>
<td><p>There are several enhancement to Microsoft Dynamics AX Application Integration Framework (AIF) in AX 2012 R2:</p>
<ul>
<li><p>Windows Communication Foundation (WCF) support for data partitions</p></li>
<li><p>WCF configuration</p></li>
<li><p>Additions to the standard document service</p></li>
<li><p>Support for optional replacement fields for a surrogate key</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Upgrade enhancements</p></td>
<td><p>There are several enhancement to the upgrade process in AX 2012 R2:</p>
<ul>
<li><p>Support for data partitioning</p></li>
<li><p>Enhancement code upgrade toolset</p></li>
<li><p>Division of a database into data and metadata</p></li>
<li><p>Enhanced international support</p></li>
<li><p>Multi-version support for Retail POS deployment</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Country/region-specific new features

In AX 2012 R2, we added and changed several country/region-specific features.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Country/region</p></th>
<th><p>What’s new</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Belgium</p></td>
<td><p>You can generate European Union (EU) sales list reports, value-added tax (VAT) declaration reports, and annual list reports in the updated XML format. You can also replace EU sales list reports, VAT declaration reports, and annual list reports that were already submitted to the Belgian tax authorities. For more information, see <a href="what-s-new-country-specific-features-for-belgium-bel.md">What's new: Country-specific features for Belgium (BEL)</a>.</p></td>
</tr>
<tr class="even">
<td><p>Brazil</p></td>
<td><ul>
<li><p>The Códigos Fiscais de Operações E Prestações (CFOP) codes now include a direction (incoming or outgoing) and a purpose (return, shipment, or fiscal establishment transfer).</p></li>
<li><p>You can use fiscal establishments to post sales and purchases for Brazil.</p></li>
<li><p>You can create and post a purchase invoice by specifying the CFOP codes.</p></li>
<li><p>You can use a check or the Bordero method of payment to make vendor payments.</p></li>
<li><p>You can relate taxes with fiscal values 1 and 3 by setting a delivery item sales tax group and a delivery sales tax group for the sales order when a CFOP has an associated delivery CFOP that allows a delivery slip to be used together with the Nota fiscal eletrônica (NF-e) feature when a delivery slip fiscal document is posted. You can also cancel a delivery slip fiscal document.</p></li>
<li><p>You can set up master data for legal text, and link that data to the CFOP, vendor, customer, item, sales order, or purchase order. You can set legal text so that it is printed automatically on fiscal documents and Documento Auxiliar da Nota Fiscal Eletrônica (DANFE). Legal text is also sent to Sistema Publico de Escrituração Digital (SPED).</p></li>
<li><p>You can use debit notes to reimburse expenses that a service provider makes for a project. You can also cancel an incorrect debit note.</p></li>
<li><p>You can cancel a project invoice that has been posted, provided that the posting date is not in a closed period, and provided that the customer invoice has not been paid or settled.</p></li>
<li><p>Withholding tax can now be determined by fiscal document line.</p></li>
<li><p>You can configure the purchase and sales operation types in the <strong>Operation type</strong> form.</p></li>
<li><p>There are enhancements to the Brazilian tax calculations.</p></li>
<li><p>You can generate fiscal documents for project sales orders and project item requirements for Brazil when packing slips are posted.</p></li>
<li><p>The setup of cost centers in the absorption cost functionality lets you calculate and post the direct and indirect costs that are incurred by the manufacturing process for a fiscal period.</p></li>
<li><p>Project invoices are integrated with fiscal documents, and you can generate an NF-e federal or municipal from the project invoices that have been posted.</p></li>
<li><p>You can create and post a sales complementary fiscal document.</p></li>
<li><p>There are several enhancements to the NF-e process.</p></li>
<li><p>There are several changes to the general ledger functionality for Brazil.</p></li>
<li><p>You can use fiscal establishments to issue fiscal documents for sales invoices, purchase invoices, and free text invoices.</p></li>
<li><p>There are several enhancements to free text invoices for Brazil.</p></li>
<li><p>You can issue an import fiscal document when you create a purchase order to import items from a foreign vendor.</p></li>
<li><p>You can use Imposto Sobre Circulação de Mercadorias e Serviços (ICMS) tax documents to record tax adjustment transactions between fiscal establishments by issuing an NF-e.</p></li>
<li><p>There is a new fiscal documents framework.</p></li>
<li><p>By using Retail, you can modify product attributes by using a mass update tool. You can also manage products by using the retail category hierarchy feature and by using the released product model that is supported in AX 2012 R2. The Brazil-specific product attribute fields have been added to these features, so that users in Brazil can take advantage of these tools to easily manage their retail products.</p></li>
<li><p>You can transfer warehouse items between warehouses that are located in different fiscal establishments, or transfer items to third-party warehouses, by using transfer fiscal documents.</p></li>
</ul>
<p>For more information, see <a href="what-s-new-country-specific-features-for-brazil-bra.md">What's new: Country-specific features for Brazil (BRA)</a>.</p></td>
</tr>
<tr class="odd">
<td><p>China</p></td>
<td><p>The following features were added to comply with Chinese accounting and regulatory requirements:</p>
<ul>
<li><p>You can define a hierarchical structure for a chart of accounts.</p></li>
<li><p>You can use financial dimensions to allocate and post transactions to ledger accounts, bank reconciliation journals, and the Chinese voucher system.</p></li>
<li><p>Voucher types and Chinese voucher numbers are implemented in source documents, reports, and queries.</p></li>
<li><p>Subledger journal entries are created for most transactions. Use the subledger journal to view a summary of transaction amounts before the transaction is posted to the general ledger.</p></li>
<li><p>Inventory reports provide details about inventory transactions and balances.</p></li>
<li><p>You can define parameters and XML files for the GB/T 24589-2010 report.</p></li>
</ul>
<p>For more information, see <a href="what-s-new-country-specific-features-for-china-chn.md">What's new: Country-specific features for China (CHN)</a>.</p></td>
</tr>
<tr class="even">
<td><p>Czech Republic</p></td>
<td><ul>
<li><p>Cash discounts are now included when unrealized gain and loss adjustments for exchange rates are calculated.</p></li>
<li><p>Intracommunity VAT can be posted as two tax transactions.</p></li>
<li><p>A new option in the <strong>Depreciation proposal</strong> form enables half-yearly depreciation.</p></li>
<li><p>Additional information about the VAT register date can now be included on tax transactions when you generate the <strong>Sales tax reconciliation</strong> report.</p></li>
</ul>
<p>For more information, see <a href="what-s-new-country-specific-features-for-the-czech-republic-cze.md">What's new: Country-specific features for the Czech Republic (CZE)</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Eastern Europe</p></td>
<td><ul>
<li><p>In Lithuania and Latvia, you can assign specific numbers to sales invoices by user or user group.</p></li>
<li><p>Asset acquisition can be split into two separate steps, each of which has its own general ledger (GL) postings and fixed asset updates.</p></li>
<li><p>You can set up tax directives for the corresponding sales tax codes and print the tax directives on sales invoices in multiples languages for all Eastern European countries/regions.</p></li>
<li><p>You can round fixed asset depreciation amounts up or down to the nearest number, as specified in the <strong>Round off depreciation</strong> field.</p></li>
<li><p>In the Czech Republic and Poland, you can report tax information on a date that differs from the posting date.</p></li>
<li><p>For Eastern European countries/regions, you can create and post a canceling free text invoice without creating a corrective free text invoice.</p></li>
<li><p>Customer and vendor settlement transactions can now be viewed for specific settlement types.</p></li>
<li><p>Support was added so that several EU member states could easily create a generic sales list report for the sale of goods and services to VAT-registered entities in other EU member states.</p></li>
<li><p>You can set up workers as advance holders and post vendor invoices together with advance holder details.</p></li>
<li><p>For some Eastern European countries/regions, fields for entering a reason code and reason comment have been added to the <strong>Invoice proposals</strong>, <strong>Invoice journals</strong>, and <strong>Select for credit note</strong> forms.</p></li>
<li><p>The <strong>Fixed asset counting</strong> report is available in Estonia and Latvia.</p></li>
<li><p>Application of the storno accounting principle to correction postings is expanded to all Eastern European countries/regions.</p></li>
<li><p>If the exchange rate between the accounting currency and the reporting currency changes, you can revalue bank account transactions and cash transactions in the accounting currency.</p></li>
</ul>
<p>For more information, see <a href="what-s-new-region-specific-features-for-eastern-europe-eeur.md">What's new: Region-specific features for Eastern Europe (EEUR)</a>.</p></td>
</tr>
<tr class="even">
<td><p>Hungary</p></td>
<td><p>To support a Hungarian legislative requirement about exchange rate calculation, an average rate method for calculating exchange rate adjustments has been added. For more information, see <a href="what-s-new-country-specific-features-for-hungary-hun.md">What's new: Country-specific features for Hungary (HUN)</a>.</p></td>
</tr>
<tr class="odd">
<td><p>India</p></td>
<td><ul>
<li><p>You can add tax details to invoice lines, and calculate direct and indirect taxes on free text invoices.</p></li>
<li><p>You can create, modify, and reverse a free text invoice.</p></li>
<li><p>You can make corrections to a packing slip for a sales order.</p></li>
<li><p>You can make and track corrections to an import purchase order.</p></li>
<li><p>Transaction amounts can be distributed among more than 10 dimensions. These dimensions include the three predefined financial dimensions.</p></li>
<li><p>You can view direct and indirect tax transactions together with accounting entries in subledger journals, and distribute the tax amount among the various dimensions.</p></li>
<li><p>You can adjust direct tax entries by using the <strong>Withholding tax journal</strong> that is generated from the general ledger.</p></li>
<li><p>You can select the types of exchange rates that are used to calculate the customs duties for import and export transactions.</p></li>
<li><p>You can set up number sequences for additional transaction types.</p></li>
<li><p>You can transfer fixed assets among various dimension values for a selected value model.</p></li>
<li><p>You can calculate depreciation of assets based on the number of days that the asset is used by using the <strong>Straight line percentage</strong> or <strong>Reducing balance</strong> depreciation method, or by using the monthly depreciation that is based on the actual number of days in a month.</p></li>
<li><p>You can define unlimited financial dimensions and use those financial dimensions as account segments in the chart of accounts.</p></li>
<li><p>There is support for transactions for the export/import (EXIM) Export Promotion Capital Goods (EPCG) incentive scheme.</p></li>
<li><p>Changes have been made to the electronic file format for Tax Deducted at Source (TDS) and Tax Collected at Source (TCS) statements.</p></li>
<li><p>You can increase the quantity of an item on an import order line after you update the invoice registration for the order. However, you cannot decrease the quantity of an item on an import order line after you update the invoice registration for the order.</p></li>
<li><p>You can create and enter an invoice line that is not related to a purchase order on an invoice.</p></li>
<li><p>You can transfer fixed assets among dimension values for a selected value model by using accounting entries.</p></li>
<li><p>The Indian functionality that is used to account for TDS and TCS direct tax amounts has been applied to the subledger journal and distribution framework.</p></li>
<li><p>You can manually adjust recoverable tax values for each transaction.</p></li>
<li><p>The subledger accounting distribution framework lets you obtain an overview of the distribution on cost centers before you post an amount to ledger accounts.</p></li>
<li><p>You can specify the item type of an item as <strong>Item</strong> or <strong>Service</strong> instead of <strong>BOM</strong>.</p></li>
<li><p>In AX 2012 R2, each line in a bill of exchange (BOE) is calculated for taxes, posted, and recorded individually.</p></li>
<li><p>AX 2012 R2 supports Standard Input Output Norms (SION) in <strong>Inventory management</strong>.</p></li>
<li><p>You can allocate miscellaneous charges for a purchase order to selected purchase order lines. You can allocate miscellaneous charges by using the whole amount and per-invoice allocation methods.</p></li>
<li><p>You can view a summary of open invoice transactions, invoice amounts, references, payments, interest, and fees that are associated with the invoices and balances at the invoice level and the invoice line level.</p></li>
<li><p>Recalculation of indirect taxes is triggered by specific conditions.</p></li>
<li><p>AX 2012 R2 supports the EXIM Duty Free Import Authorization (DFIA) incentive scheme.</p></li>
<li><p>You can update tax information in a corrective free text invoice.</p></li>
<li><p>There are several enhancements to purchase orders for India.</p></li>
<li><p>You can assign financial dimensions to entries that are generated in the <strong>Transfer orders</strong> form.</p></li>
<li><p>You can generate financial statements, such as balance sheets and profit and loss statements, in Microsoft Excel.</p></li>
<li><p>The subledger accounting distribution framework affects the functionality for customs duty. The framework lets you obtain an overview of the distribution on cost centers before an amount is posted to ledger accounts.</p></li>
<li><p>A cache for withholding tax is implemented for all transactions from subledger journals, such as invoices, free text invoices, vendor invoices, and purchase orders.</p></li>
<li><p>AX 2012 R2 includes the Global address book functionality for India.</p></li>
<li><p>There are several updates to General ledger and tax inquiry forms.</p></li>
<li><p>AX 2012 R2 includes improvements to tax registration number assignments.</p></li>
<li><p>AX 2012 R2 includes several enhancements to the Organization model for India.</p></li>
<li><p>Duties and privileges are added for user roles in features for India.</p></li>
<li><p>AX 2012 R2 includes expanded support for tax types for service industry transactions</p></li>
<li><p>You can view and modify accounting entries before you post them to the general ledger.</p></li>
<li><p>When no Permanent Account Number (PAN) is registered for a customer or vendor, the TDS is automatically calculated at a higher rate.</p></li>
<li><p>For India customs duty and Export Import Policy (EXIM), if the charge as expense ratio is used, the related customs duty is charged to the expense account.</p></li>
<li><p>You can set up number sequences based on the data area for ledger vouchers that are generated for EXIM incentive schemes, VAT deferments, withholding tax payments, and shipping bill references.</p></li>
<li><p>AX 2012 R2 includes expanded support for tax types for project transactions, billing processes, and tax settlements.</p></li>
<li><p>AX 2012 R2 supports the EXIM Advance Authorization (AA) incentive scheme.</p></li>
<li><p>There are several General ledger updates for India.</p></li>
<li><p>AX 2012 R2 supports the EXIM Duty Drawback (DBK) incentive scheme.</p></li>
<li><p>You can print group commodity codes and state commodity codes for each item on sales invoices.</p></li>
<li><p>The Upgrade toolkit has been updated.</p></li>
<li><p>BOE and invoice registration can now be canceled if the invoice registration has not been updated, and if the related product receipts or invoices have not been posted.</p></li>
</ul>
<p>For more information, see <a href="what-s-new-country-specific-features-for-india-ind.md">What's new: Country-specific features for India (IND)</a>.</p></td>
</tr>
<tr class="even">
<td><p>Japan</p></td>
<td><ul>
<li><p>You can consolidate monthly invoices.</p></li>
<li><p>You can calculate the due date for a vendor or customer payment, based on the cutoff date.</p></li>
<li><p>You can now set the status of consolidated invoices.</p></li>
<li><p>You can reopen a consolidated vendor invoice.</p></li>
<li><p>When you create a consolidated vendor invoice, you can include amounts from partially settled invoices.</p></li>
<li><p>You can consolidate Accounts receivable (AR) invoices based on the execution date instead of the consolidation date.</p></li>
<li><p>You can define a consolidation date for each customer.</p></li>
<li><p>You can create consolidated invoices for payment proposals for vendors.</p></li>
<li><p>You can add non-purchase order lines to a consolidated invoice.</p></li>
<li><p>You can set a parameter to enable consolidation of invoices by customer. You can also set a parameter to enable consolidation of invoices by vendor.</p></li>
<li><p>You can generate a cash flow statement for a financial dimension that you specify. You can also export cash flow statements to Excel.</p></li>
<li><p>You can endorse a BOE by settling the BOE and setting the status to <strong>Drawn</strong>. You can then redraw the BOE and generate the endorsement accounting journal voucher.</p></li>
<li><p>You can define financial dimensions for debits and credits separately. The debit and credit amounts can be entered as two lines in the journal voucher.</p></li>
<li><p>You can set up phonetic names for your companies, customers, vendors, employees, and contact persons.</p></li>
<li><p>You can include a letter of credit when you create a consolidated invoice. This feature is available only for Japan.</p></li>
<li><p>You can export financial statements, such as balance sheets, profit and loss statements, and cash flow statements, to Excel.</p></li>
<li><p>The <strong>Target of consolidation</strong> check box is available in the <strong>Sales order</strong>, <strong>Purchase order</strong>, and <strong>Vendor invoice</strong> forms. When this check box is selected, a transaction is invoiced by using invoice consolidation.</p></li>
</ul>
<p>For more information, see <a href="what-s-new-country-specific-features-for-japan-jpn.md">What's new: Country-specific features for Japan (JPN)</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Latvia</p></td>
<td><p>AX 2012 R2 keeps track of all changes to the <strong>Responsible</strong>, <strong>Department</strong>, and <strong>Location</strong> fields for every fixed asset as each change is saved. For more information, see <a href="what-s-new-country-specific-features-for-latvia-lva.md">What's new: Country-specific features for Latvia (LVA)</a>.</p></td>
</tr>
<tr class="even">
<td><p>Lithuania</p></td>
<td><ul>
<li><p>You can use the <strong>Repair</strong> form under the <strong>Fixed assets</strong> &gt; <strong>Value models</strong> form to record repairs that are made to fixed assets.</p></li>
<li><p>You can enter packing slip details for the transfer of fixed assets to a different location.</p></li>
<li><p>There are several changes to invoice numbering and packing slip registration.</p></li>
</ul>
<p>For more information, see <a href="what-s-new-country-specific-features-for-lithuania-ltu.md">What's new: Country-specific features for Lithuania (LTU)</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Norway</p></td>
<td><ul>
<li><p>You can make online payments by using Nordea Corporate Netbank.</p></li>
<li><p>Collection letters can be sent in Elektronisk Handelsformat (EHF) format, which is the standard format for Norway's public sector.</p></li>
</ul>
<p>For more information, see <a href="what-s-new-country-specific-features-for-norway-nor.md">What's new: Country-specific features for Norway (NOR)</a>.</p></td>
</tr>
<tr class="even">
<td><p>Poland</p></td>
<td><p>AX 2012 R2 supports tracking Numeru Identyfikacji Podatkowej (NIP) tax identification information. For more information, see <a href="what-s-new-country-specific-features-for-poland-pol.md">What's new: Country-specific features for Poland (POL)</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Russia</p></td>
<td><ul>
<li><p>You can view, modify, and print transactions on subledger journal lines before you post the transactions to the general ledger. You can also allocate transaction lines among multiple financial dimensions.</p></li>
<li><p>You can set up budget control for advance reports.</p></li>
<li><p>You can set up a default inventory profile for retail transactions.</p></li>
<li><p>You can create sales agreements and purchase agreements, and refer to agreements in transactions with customers and vendors.</p></li>
<li><p>You can adjust taxes on an invoice line.</p></li>
<li><p>You can create vendor invoices by selecting open purchase orders and purchase lines when you update the facture from the <strong>Purchase order</strong> form. You can verify invoices and then post them as a group.</p></li>
<li><p>You can create a credit correction for a vendor invoice and a free text invoice.</p></li>
<li><p>You can retrieve purchase orders or product receipts in the <strong>Update facture</strong> form.</p></li>
<li><p>You can create free text lines in a vendor invoice that are not associated with a purchase order. You can also create recurring vendor invoices from a free text vendor invoice.</p></li>
<li><p>You can create a template for a free text customer invoice and cancel a free text invoice.</p></li>
<li><p>You can distribute amounts on a vendor invoice line to multiple ledger accounts.</p></li>
<li><p>Optionally, you can use a transit expense account when you post a purchase invoice.</p></li>
<li><p>You can process incoming VAT and calculate exchange rate adjustments.</p></li>
<li><p>You can set up Retail parameters so that a facture is automatically updated when the sales invoice and the retail statement are posted.</p></li>
<li><p>You can view, analyze, and print information about inventory balance turnover.</p></li>
<li><p>Microsoft Dynamics AX has incorporated additional sections into the layout of the <strong>VAT declaration</strong> report to calculate the VAT amount.</p></li>
<li><p>Changes have been made that support calculating cost for work in progress (WIP) and finished goods.</p></li>
<li><p>You can split all the lines for selected factures by using a template when you process incoming VAT.</p></li>
<li><p>You can set up an intermediate bank account for a foreign vendor.</p></li>
<li><p>You can use storno transactions to post corrections in transfer orders that are made by using shipments and receipt orders.</p></li>
<li><p>You can choose not to generate corrected free text invoices when you cancel incorrect invoices that were previously posted.</p></li>
<li><p>You can allocate miscellaneous charges from a purchase order header to a category-based purchase order line, based on the weight or volume information on the lines. You can also print the weight and volume information for the category-based order lines.</p></li>
<li><p>Several updates have been made to currency valuation.</p></li>
<li><p>There are limitations on the status changes that you can make to company bank accounts for the Russian Federation.</p></li>
<li><p>AX 2012 R2 supports new requirements for bank payment orders for the Russian Federation.</p></li>
<li><p>AX 2012 R2 supports non-recoverable VAT amounts as part of the budget.</p></li>
<li><p>From the <strong>Inventory balance turnover</strong> form, you can generate balance turnover details for customers and vendors, general ledger accounts, and contracts for settled transactions.</p></li>
<li><p>You can create and print corrective and revised factures that are based on credit notes, corrective invoices, and tax correction transactions.</p></li>
<li><p>You can define a worker table number for each position that a worker holds. You can define multiple worker table numbers for the personnel number of a worker.</p></li>
<li><p>You can create a major repair transaction for a fixed asset, and specify the bonus depreciation and bonus start date.</p></li>
<li><p>You can post storno transactions for adjustments to the inventory cost value.</p></li>
<li><p>By using the manual write-off method for deferrals, you can now specify a write-off amount or percentage in the <strong>Writing off methods</strong> form.</p></li>
<li><p>You can now create and post a customs journal to calculate payments for customs clearance of imported or exported goods.</p></li>
<li><p>You can sort inventory adjustments and inventory settlements by charges code.</p></li>
<li><p>You can create inventory profiles to determine the movement of items and balance turnover.</p></li>
<li><p>You can transfer proprietary rights for goods that are in transit.</p></li>
<li><p>Customer invoices and vendor invoices can be posted and printed in the TORG-12 and M-15 formats.</p></li>
<li><p>You can select an expense invoice to allocate miscellaneous charges to other invoices that have the same vendor account.</p></li>
<li><p>AX 2012 R2 includes several updates to purchase invoices.</p></li>
<li><p>Fixed assets, such as vehicles and realty, can be depreciated starting on the date when they are registered.</p></li>
<li><p>You can retrieve information about purchase orders or product receipts from the vendor invoice form. For Russia, you can now also retrieve this information from the <strong>Update facture</strong> form, which is based on the <strong>Posting invoice for payment</strong> form.</p></li>
<li><p>AX 2012 R2 supports inventory adjustments that use offset accounts and storno transactions.</p></li>
<li><p>AX 2012 R2 includes several enhancements to the inventory management process for Russia.</p></li>
<li><p>AX 2012 R2 includes updates to the calculation of write-off time for deferrals.</p></li>
<li><p>AX 2012 R2 lets you account for working clothes, special rigging, and not valuable fixed assets (NVFAs).</p></li>
<li><p>You can set up financial report layouts by using the Financial reports generator, and you can copy the report layout settings of one legal entity to another.</p></li>
<li><p>AX 2012 R2 supports vendor invoices that are not associated with a purchase order and recurring invoices.</p></li>
<li><p>AX 2012 R2 includes changes to the calculation of amount differences and exchange adjustments for prepayments.</p></li>
<li><p>You can generate subledgers from source documents such as invoices, packing slips, and picking lists for customers and vendors. Before you post the voucher information to the general ledger, you can view or modify subledger journals by using a new method that is named distribution.</p></li>
<li><p>You can import currency exchange rates from the Central Bank of the Russian Federation (CBRF) website into AX 2012 R2.</p></li>
<li><p>The invoices and factures for a purchase order or a sales order can be posted at the same time.</p></li>
<li><p>You can use non-linear depreciation to mark accrued depreciation for the previous year for taxation purposes.</p></li>
<li><p>AX 2012 R2 supports the bailment process and calculation of storage service amounts.</p></li>
<li><p>You can generate and print a transportation invoice and a job ticket, based on a bill of lading.</p></li>
<li><p>All general ledger postings for Russia are made under the correspondence rule, where a one-to-one relationship is established between a debit transaction and a credit transaction. Correspondence of ledger transactions is enabled for purchase overheads and for all general ledger postings in Lean manufacturing.</p></li>
<li><p>AX 2012 R2 supports exchange adjustment and profit/loss calculation on the Remittance en route account.</p></li>
<li><p>Exchange adjustments on advance payments that were issued or received in currency no longer have to be calculated in business accounting.</p></li>
<li><p>AX 2012 R2 includes enhancements to fixed asset transfers for Russia.</p></li>
<li><p>You can use dimension control settlement to help you accurately manage and analyze accounting with vendors, customers, and advance holders by financial dimension.</p></li>
<li><p>You can generate the Counting act (INV-6) report as an Excel worksheet.</p></li>
<li><p>You can generate the NVFA accounting card (No. MB-2), NVFA Act on disposal (No. MB-4), and NVFA Statement of writing-off (No. MB-8) reports.</p></li>
<li><p>You can create and print new versions of the receipt statement reports (TORG-1, TORG-2, TORG-3, M-4, and M-7) when you correct purchase order receipts.</p></li>
<li><p>AX 2012 R2 lets you perform more tasks that are related to VAT for export trade enhancements.</p></li>
<li><p>There are several enhancements to Accounts receivable and Accounts payable invoices for Russia.</p></li>
<li><p>AX 2012 R2 supports amount difference factures for sales and purchase orders.</p></li>
<li><p>Enhancements have been made to the Accounts payable payment grouping and payments at the invoice line level.</p></li>
<li><p>AX 2012 R2 lets you allocate miscellaneous charges for service items in several different ways.</p></li>
<li><p>You can generate assessed tax, transport tax, or land tax declarations that contain information that is categorized by the Russian Federation tax authority.</p></li>
<li><p>You can use budget control to monitor budget funds, based on source documents such as purchase orders and expense reports. In the Russian Federation, advance reports are generated to register incurred expenses.</p></li>
<li><p>Enhancements have been made to the Global address book (GAB) to support address formats in Russia.</p></li>
<li><p>When you sell a fixed asset before the end of its depreciation life cycle, you can recover the depreciation bonus for the remainder of the life cycle.</p></li>
<li><p>AX 2012 R2 supports electronic exchange formats for client bank payments.</p></li>
<li><p>AX 2012 R2 includes changes to sales agreements and purchase agreements.</p></li>
<li><p>AX 2012 R2 includes changes to the facture report that is issued by tax agents.</p></li>
<li><p>You can create and post a storno transfer journal to reverse a journal transaction that is posted incorrectly.</p></li>
<li><p>You can enter tax rates that contain five decimal places to calculate the sales tax amount.</p></li>
<li><p>You can use the <strong>General ledger parameters</strong> form and the <strong>Accounts payable parameters</strong> form to activate the VAT deduction for deferrals.</p></li>
<li><p>AX 2012 R2 supports changes that are required for the accounting and cost calculation of by-products and defective products.</p></li>
<li><p>You can run the <strong>Inventory balance turnover</strong> report to verify the quantity, income, consumption, and stock balance in warehouses, based on dimensions such as sites, warehouses, ledger accounts, or financial dimensions.</p></li>
<li><p>The <strong>VAT declaration</strong> report can be generated in both .xls and .xml formats.</p></li>
<li><p>In AX 2012 R2, tax registration numbers are no longer defined at the company level or the party record level. Instead, you can define the tax registration number on the party's primary address record.</p></li>
<li><p>The template for the land tax declaration in Russia has changed.</p></li>
<li><p>The template for the transport tax declaration in Russia has changed.</p></li>
<li><p>The template for the property tax declaration in Russia has changed.</p></li>
<li><p>You can perform cost value accounting by using a reporting currency.</p></li>
<li><p>For electronic reporting, you can set up financial report layouts, document templates, and fixed requisites by using the Financial reports generator.</p></li>
<li><p>You can use print management for bills of lading and transportation documents. You can print the reports for bills of lading in Excel format and on a standard Microsoft SQL Server Reporting Services report.</p></li>
<li><p>You can use the purchase expenditure for product account to post a purchase invoice before the document date for vendor invoices is set. This feature lets you select different dates during vendor balance posting and inventory posting.</p></li>
<li><p>To process VAT, you can include unpaid export factures in sales books when you run processing for outgoing VAT.</p></li>
<li><p>You can select an inventory profile that is applied by default to sales orders that are created from transactions in Retail POS.</p></li>
<li><p>You can set the Retail parameters so that the facture is automatically updated when the sales invoice is posted at the same time as the retail statement.</p></li>
</ul>
<p>For more information, see <a href="what-s-new-country-specific-features-for-russia-rus.md">What's new: Country-specific features for Russia (RUS)</a>.</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

