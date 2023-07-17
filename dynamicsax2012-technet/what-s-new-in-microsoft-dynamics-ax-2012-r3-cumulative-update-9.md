---
title: What's new in Microsoft Dynamics AX 2012 R3 cumulative update 9
TOCTitle: What's new in Microsoft Dynamics AX 2012 R3 cumulative update 9
ms:assetid: 7b4e46ff-d16f-4c47-a226-b8761ad65f8f
ms:mtpsurl: https://technet.microsoft.com/library/Mt156976(v=AX.60)
ms:contentKeyID: 65883279
author: tonyafehr
ms.date: 06/08/2015
mtps_version: v=AX.60
---

# What's new in Microsoft Dynamics AX 2012 R3 cumulative update 9 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


This topic lists feature changes and updates by module and by country/region, and provides links to related topics.

## New features for Microsoft Dynamics AX 2012 R3 Cumulative Update 9

The following table outlines the features that were added in Microsoft Dynamics AX 2012 R3 Cumulative Update 9.

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
<td><p>Human resources</p></td>
<td><p>New functionality has been added to Dynamics AX 2012 R2 and R3 to assist employers who need to track information that will be reported on form 1095-C under the Affordable Care Act (ACA) starting in 2016. Note this new functionality is only enabled for US Legal Entities. For more information about how Microsoft Dynamics AX supports these new reporting requirements, see <a href="https://community.dynamics.com/ax/b/axhcmnewslearningshighlights/archive/2015/05/28/affordable-care-act-support-for-reporting-requirements" class="uri">https://community.dynamics.com/ax/b/axhcmnewslearningshighlights/archive/2015/05/28/affordable-care-act-support-for-reporting-requirements</a>.</p></td>
</tr>
<tr class="even">
<td><p>Retail</p></td>
<td><p>The following reports have been added to Retail modern point-of-sale and Retail enterprise point-of-sale:</p>
<ul>
<li><p>Store return transactions</p></li>
<li><p>Store sales by discount</p></li>
<li><p>Store sales by tender type</p></li>
<li><p>Store voided transactions</p></li>
<li><p>Offline sync status overview</p></li>
<li><p>Register offline sync status</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Transportation management</p></td>
<td><p>The Bill of Lading includes additional fields. Plus, it’s possible now to edit the Bill of Lading before printing it.</p>
<p></p>
<p>It is now possible to print multiple packing slips directly from the load planning workbench by selecting multiple loads.</p>
<p></p>
<p>There’s a new <strong>Freight reconciliation</strong> option on the <strong>Transportation management parameters</strong> form. If freight reconciliation is not used, you can clear this option and no freight bill records will be created.</p></td>
</tr>
<tr class="even">
<td><p>Warehouse management</p></td>
<td><p>You can now set up demand replenishment so that it checks whether there’s any demand replenishment work that’s been created in the same location that is not yet finalized. If existing work is found with an appropriate quantity available, the existing work will be used instead of creating new replenishment work. For more information, see <a href="set-up-replenishment.md">Set up replenishment</a>.</p>
<p></p>
<p>It is now possible to display a list of open work items on warehouse mobile devices. The list can be configured to filter on different fields and the user can select any work displayed on the list to be directed to its specific instructions. For more information, see <a href="configure-mobile-devices-for-warehouse-work.md">Configure mobile devices for warehouse work</a>.</p>
<p></p>
<p>You can manually pack transfer orders from the packing station. This is particularly useful in retail environments if you want to pack cartons that will refill retail stores from a distribution center.</p>
<p></p>
<p>Two new locations directive action strategies are now supported for the work order type Inventory movement: Consolidate and Empty location with no incoming work. For more information, see <a href="create-a-location-directive.md">Create a location directive</a>, and <a href="https://blogs.msdn.com/b/dynamicsaxscm/archive/2015/01/30/put-away-strategies-for-purchase-orders-possibilities-performance-and-improvements-in-cu8.aspx">Dynamics AX SCM R&amp;D Team blog</a>.</p>
<p></p>
<p>You can now report as finished on a mobile device in overproduction scenarios. For more information, see <a href="set-up-production-processes-in-a-warehouse.md">Set up production processes in a warehouse</a>.</p>
<p></p>
<p>You can process a wave that includes multiple shipments from both sales and transfer orders. This is useful when you are planning waves according to destinations of shipments.</p>
<p></p>
<p>When using the auto-release to warehouse process you can now consolidate multiple sales orders for the same customer into a single shipment if the <strong>Consolidate shipment at release to warehouse</strong> parameter is set on the <strong>Warehouse</strong> form. For more information, see <a href="sales-orders-and-fulfillment-rates-in-warehouse-management.md">Sales orders and fulfillment rates in Warehouse management</a>.</p>
<p></p>
<p>The following improvements has been made with regard to batch reservation strategies:</p>
<ul>
<li><p>The FEFO batch reservation strategy now takes the “Best before date” and the “Expiration date” of the batches into account.</p></li>
<li><p>You can reserve items across different batch numbers when releasing sales orders.</p></li>
</ul>
<p>For more information, see <a href="create-a-location-directive.md">Create a location directive</a>.</p></td>
</tr>
</tbody>
</table>


## Developer features

Changes that affect developers were introduced in Microsoft Dynamics AX 2012 R3 Cumulative Update 9.

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
<td><p>MPOS extensibility</p></td>
<td><p>You can configure MPOS to skip the Welcome screen, login directly to the POS screen, and begin ringing up sales immediately.</p></td>
</tr>
</tbody>
</table>


## Country/region-specific features

In Microsoft Dynamics AX 2012 R3 Cumulative Update 9, we updated several country/region-specific features.

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
<td><p>Austria</p></td>
<td><p>Because half-year convention rules are allowed for fixed assets depreciation calculation, the <strong>Half year convention on additional acquisitions</strong> parameter can now be set up in the depreciation profile for the straight-line-life remaining depreciation method. This method is considered if the <strong>Create depreciation adjustment with bases adjustment</strong> parameter is enabled in the fixed asset value model.</p></td>
</tr>
<tr class="even">
<td><p>Belgium</p></td>
<td><p>As of January 1, 2015, the procedure for submitting Intrastat returns to the National Bank of Belgium (NBB) has changed. Intrastat returns can now be submitted only by using OneGate. This online program enables you to enter the data manually or to import data files in CSV or XML format. The changes are applicable for all Belgian companies and allow you to create Intrastat reports in XML format.</p></td>
</tr>
<tr class="odd">
<td><p>Brazil</p></td>
<td><p>SPED ECD layout version 3.0 is now available.</p>
<p></p>
<p>Layout version 009 is now available for Sped Fiscal version 1.08. The layout includes a new field for record H010. This field represents the item valuation that will be picked up from the inventory valuation method that is selected in the item’s model group.</p></td>
</tr>
<tr class="even">
<td><p>Europe</p></td>
<td><p>You can now print company VAT numbers on the following issued documents:</p>
<ul>
<li><p>Sales quotation</p></li>
<li><p>Sales quotation confirmation</p></li>
<li><p>Sales confirmation</p></li>
<li><p>Sales packing slip</p></li>
<li><p>Sales agreement</p></li>
<li><p>Purchase order confirmation</p></li>
<li><p>Receipts list</p></li>
<li><p>Request for quotation</p></li>
<li><p>Product receipt</p></li>
<li><p>Purchase agreement</p></li>
</ul>
<p></p>
<p>The <strong>Sales</strong> and <strong>Free text invoice</strong> reports include descriptions of the sales tax codes, information about the invoices being corrected, and the VAT registration number for the customer.</p></td>
</tr>
<tr class="odd">
<td><p>Germany</p></td>
<td><p>For the straight-line-life remaining depreciation method, a new parameter is added to allow you to apply rules for additional acquisition and acquisition adjustment transactions. After you enable the parameter, the depreciation of additional acquisitions and acquisition adjustments is calculated according to the following rules:</p>
<ul>
<li><p>The amounts of additional acquisitions that are posted during the year of initial acquisition are depreciated starting from the depreciation run date.</p></li>
<li><p>The amounts of additional acquisitions posted in the year later than year of initial acquisition are depreciated starting from the first day of the year.</p></li>
<li><p>The amount of additional depreciation is added to the periodic depreciation amount in the respective period.</p></li>
</ul>
<p>If you create depreciation adjustments with basis adjustments marked on the Fixed asset value model, the depreciation adjustment transaction will be created according to the following rules:</p>
<ul>
<li><p>For additional acquisitions posted in the year of initial acquisition, the depreciation amount is adjusted starting from the depreciation run date.</p></li>
<li><p>For additional acquisitions posted in the year later than year of initial acquisition, the depreciation amounts are adjusted starting from the first date of the year.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>India</p></td>
<td><p>Under India Companies Act 2013, depreciation is required to calculate the useful life of an asset regardless of the method of depreciation already used. Updates are included in this release to address component accounting and shift depreciation calculation.</p>
<p></p>
<p>When you import services from overseas and the invoice is issued before payment, the payable service tax is expected to be converted using the GAAP rate on the payment date. For TDS, the TT rate is used instead of the GAAP rate.</p>
<p></p>
<p>Electronic reports are now compliant with the File validation utility (FVU) version 4.5 tool. In the <strong>Vendor</strong> and <strong>Customer</strong> forms, on the <strong>Tax details</strong> tab, if the PAN status is <strong>Not Available</strong>, <strong>Applied</strong>, or <strong>Not valid</strong>, the <strong>Reference number</strong> field is enabled so that you can enter the reference number needed by the FVU 4.5 tool.</p>
<p></p>
<p>The functionality that is included for the RG23D requirement regarding invoice references in sales invoices, covers end-to-end scenarios of the sale of goods. These scenarios include, for example, from importer to first stage dealer, first stage to second stage dealer, first stage to manufacturer, second stage to manufacture, second stage to end consumer, and second stage to dealer. This functionality also covers the import scenario where the Special additional duty of custom (SAD) may be passed on to the corresponding posting accounting.</p>
<p></p>
<p>You can now set a default assessable value on returned goods on the purchase return order line, and read the assessable value from the posted purchase order line against which a return order is created for returned goods. The assessable value for the quantity being returned through the return order is calculated and used as the default assessable value on the return order line. The quarterly return for the traders report displays outward transactions and the corresponding inward transactions.</p>
<p></p>
<p>The tax register balance dynamic view functionality is extended to show utilized and adjusted CENVAT credit (RG23 A/C) against service tax liability and other taxes. The view also shows utilized and adjusted service tax credit against excise liability and other taxes extended in the new <strong>Service tax register balance</strong> form.</p>
<p></p>
<p>You can now reverse deferred excise credit to a CENVAT credit account in the next period while tracking the original transaction. You can also avail 100 percent of the CENVAT credit if capital goods are removed in the year of purchase, if one of the following conditions are met:</p>
<ul>
<li><p>Capital goods are removed in good condition.</p></li>
<li><p>Capital goods are removed as write-off.</p></li>
<li><p>Capital goods are removed as waste/scrap.</p></li>
</ul>
<p></p>
<p>New functionality for the excise credit utilization on receipt of goods enables users to do the following:</p>
<ul>
<li><p>Claim CENVAT credit after posting the product receipt.</p></li>
<li><p>Adjust excise duty tax adjustment at the product receipt stage.</p></li>
<li><p>Update RG 23A Part II immediately after posting the product receipt.</p></li>
<li><p>Block excise duty tax adjustment when invoicing CENVAT credit during the product receipt stage.</p></li>
<li><p>Use the CENVAT credit during the sales tax payment process.</p></li>
</ul>
<p></p>
<p>You can now record and print the following information on <strong>Sales excise invoice</strong> reports: notification numbers and dates, serial numbers, effective dates of notifications, and the expiry date of notifications.</p>
<p></p>
<p>The following statutory excise registers and reports have been added:</p>
<ul>
<li><p>Purchase and Sales Register</p></li>
<li><p>CENVAT credit utilization (debit) report</p></li>
<li><p>Inter Unit transaction register inquiry</p></li>
<li><p>Personal ledger account</p></li>
<li><p>Sample register</p></li>
<li><p>Daily stock account register</p></li>
<li><p>RG23 A Part I</p></li>
<li><p>RG23 C Part I</p></li>
<li><p>RG23 A Part II</p></li>
<li><p>RG23 C Part II</p></li>
</ul>
<p>Maintenance of these reports is typically required for all manufacturers. These reports are in addition to the comprehensive excise inquires where users can configure their own reports.</p></td>
</tr>
<tr class="odd">
<td><p>Italy</p></td>
<td><p>The frequency of Black list submissions has changed from monthly or quarterly to annually, however, this change applies only for amounts greater than €10,000 (instead of €500).</p>
<p></p>
<p>The Italian report, <strong>Inventory movements in a period</strong>, contains transaction sequences that are divided by item and with on-hand quantities.</p>
<p></p>
<p>The new version 1.1 of electronic invoices format, known as FatturaPA, is now available and supported. The previous version 1.0 is discontinued.</p></td>
</tr>
<tr class="even">
<td><p>Lithuania</p></td>
<td><p>The procedure for submitting Intrastat returns in Lithuania has changed due to adoption of euro currency. The invoice value and statistical value in the Intrastat declarations and modified declarations, submitted by VAT payers for the reference period since the adoption of euros (January 1, 2015) in the Republic of Lithuania must be selected in the Intrastat declarations in euro. The IDAIS system was updated so that euros are accepted on the Intrastat declarations and submitted by VAT payers in the XML files for the format which corresponds to the new instat.xml data structure. The update provides the ability to create Intrastat declarations in new the XML format.</p></td>
</tr>
<tr class="odd">
<td><p>Mexico</p></td>
<td><p>You can set up and generate the general ledger XML files version 1.1 as required by the Mexican tax authority (SAT) in accordance with Annex 24 of the Miscellaneous Tax Resolution for 2015. You can generate the following XML files required by the SAT for each company:</p>
<ul>
<li><p>Chart of accounts</p></li>
<li><p>Monthly trial balance</p></li>
<li><p>Journal transactions</p></li>
<li><p>Auxiliary account list</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Netherlands</p></td>
<td><p>Updates to the VAT returns and ICP declarations have been made to allow customers to generate VAT and ICP declarations in XBRL format in accordance to the Taxonomy version 9.0. In accordance with the new Taxonomy version, the key updates include:</p>
<ul>
<li><p>The entry point reference to the XSD was updated.</p></li>
<li><p>Namespaces references were updated.</p></li>
<li><p>The length of element bd-alg_MessageReferenceSupplierVAT was increased to 20.</p></li>
<li><p>New elements, bd-alg_ContactInitials and bd-alg_ContactPrefix, were added to the schema and contain Contact Initials and Contact prefix. This information must be defined in <strong>General ledger</strong> &gt; <strong>Setup</strong> &gt; <strong>Sales tax</strong> &gt; <strong>External</strong> &gt; <strong>Netherlands</strong> &gt; <strong>Electronic tax declaration parameters</strong>.</p></li>
<li><p>Contact address information is no longer in the schema.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Poland</p></td>
<td><p>You can now create advance invoices for prepayments in Retail, including automatic creation, posting and printing of an advance invoice for a customer order deposit received through Retail Enterprise POS, and settlement of the advance invoice upon invoicing the order.</p></td>
</tr>
<tr class="even">
<td><p>Russia</p></td>
<td><p>Updates have been made to the VAT deduction acceptance that now allow the following:</p>
<ul>
<li><p>Accept VAT deduction in the period of the document’s receipt or in the current reporting period if the facture is received before the VAT declaration submission date.</p></li>
<li><p>Include only the commissioners’ factures in the Facture journal according to the requirements of the Judgment N 735 from July 30, 2014 from the RF government.</p></li>
</ul>
<p></p>
<p>The journal format used in accounting of the retail sale of alcoholic products has been updated based on the changes enacted on May 23, 2014 N 153 from the Federal Service for Alcohol Market Regulation. The journal format now shows incoming and outgoing documents instead of grouping the documents. The following has also been added to the journal:</p>
<ul>
<li><p>Packing volume in liters and the number of packages.</p></li>
<li><p>Description from transfer type or scrap type.</p></li>
<li><p>Sell products.</p></li>
<li><p>Product loss during transport, fight products, and other losses.</p></li>
<li><p>Production loss identified in inventory.</p></li>
<li><p>Arrested products.</p></li>
</ul>
<p>The procedure for registering and using the requisites of credit institutions of workers has changed. The new 333-FZ introduced changes in the Labor Code of the Russian Federation which allows changes to the requisites of an employee’s credit institution based on their written request to the employer. These changes are applied no later than five working days before the date of payment of wages.</p>
<p></p>
<p>The Transport tax declaration electronic format has been updated according to Federal tax authority order N ММВ-7-11/254@ from April 25, 2014.</p>
<p></p>
<p>The printable format of the 4-FSS report has changed effective Q1 2015. You can now generate the report according to the new printable format.</p>
<p>A new format of the Form No. 1 statistical report is now available.</p>
<p></p>
<p>The facture that is created for the tax agent can have the same number in the purchase book and the sales book because there are two copies of one document.</p>
<p></p>
<p>When you create Facture registration journals, you can now create journals according to the date of registration of the outgoing facture or according to the date of registration of the confirming incoming facture.</p>
<p></p>
<p>The VAT declaration electronic format has been updated to version 5.04.</p>
<p></p>
<p>Customer payments that are registered in Retail Enterprise POS for customer order deposits and partially completed orders can now be reflected in fiscal receipts.</p>
<p></p>
<p>The tax registers, <strong>Amount difference in tax accounting</strong> and <strong>Exchange adjustment in accounting</strong>, show only the amount of the exchange differences from invoices that were posted before January 1, 2015.</p>
<p></p>
<p>The currency exchange differences for invoices that were created after January 1, 2015, either as a result of a periodic exchange adjustment calculation or a settlement, are reflected in the tax registers that collect transactions by the general ledger accounts.</p>
<p></p>
<p>To identify currency exchange differences in general ledger accounts for tax purposes, the dimension <strong>Expense code</strong> is filled with values that were set up to show exchange differences in the <strong>Exchange rates</strong> form (version 5.0 SP1), or in the <strong>Currency parameters</strong> form (version 6.2 and higher). This is the result of periodic currency exchange differences calculated in the accounts receivable and accounts payable modules.</p>
<p></p>
<p>The option to exclude is now available in the <strong>Amount difference in tax accounting</strong> and <strong>Exchange adjustment in accounting</strong> tax registers. If this check box is selected, the register will not be initiated in new tax register journals.</p></td>
</tr>
<tr class="odd">
<td><p>Spain</p></td>
<td><p>To support the January 15, 2015 legal requirements that all invoices sent to or received from Spanish Government Agencies and State owned companies must be submitted only in electronic format, Dynamics AX has introduced new functionality. This functionality also follows the requirement to generate Electronic invoices (eInvoices) using a standard format defined by the AEAT (Spanish Tax Administration) known as “FacturaE”. The new functionality includes:</p>
<ul>
<li><p>New eInvoices parameters in the <strong>Accounts Receivable</strong> module that can help to define different business scenarios.</p></li>
<li><p>Ability to create eInvoices automatically when a sales invoice, free text invoice, project invoice, or credit note is posted.</p></li>
<li><p>Electronic signing of eInvoices, either by company certificate or user certificate.</p></li>
<li><p>Functionality for defining if eInvoices will be created automatically for particular customers.</p></li>
<li><p>The ability to monitor, re-create, re-sign, or re-send eInvoices in case these actions must be performed multiple times.</p></li>
<li><p>Supported versions of “FacturaE” format are 3.2 and 3.2.1.</p></li>
</ul>
<p>For more information, see:<a href="https://mbs.microsoft.com/files/customer/ax/learning/whitepapers/microsoftdynamicsaxspanisheinvoicesfacturaesupport.pdf">https://mbs.microsoft.com/files/customer/AX/Learning/whitepapers/MicrosoftDynamicsAXSpanisheInvoicesFacturaEsupport.pdf</a>.</p>
<p></p>
<p>The Spanish Tax Agency (AEAT) has issued the Order HAP/1732/2014 defining a new 347 model that supersedes the previous model approved per Order EHA 3012/2008. Microsoft Dynamics AX 2012 R3 Cumulative Update 9 includes the solution for address abbreviation length and position in exported files for the tenants.</p>
<p>For more information about this change and the corresponding changes in Dynamics AX, see <a href="https://mbs.microsoft.com/customersource/spain/ax/learning/documentation/white-papers/msdaxdec347wpspain">https://mbs.microsoft.com/customersource/Spain/AX/learning/documentation/white-papers/msdaxdec347wpspain</a>.</p></td>
</tr>
<tr class="even">
<td><p>United Kingdom</p></td>
<td><p>Effective April 1, 2015, the UK Legislation was updated and brought in line with EU VAT rules to avoid ambiguity about VAT on prompt payments. With this change, businesses must account for VAT that they actually receive. Therefore, the business making the supply will have to issue a credit note to account for the discount where this is taken up.</p>
<p>In Microsoft Dynamics AX 2012 R3 Cumulative Update 9, credit notes on the settlement discounts can be automatically created. The original invoice number and date will be printed in the credit note for the discount as well.</p></td>
</tr>
<tr class="odd">
<td><p>USA</p></td>
<td><p>Updates to the VETS preparation report were made to follow the reporting requirements in the new VETS-4212 report.</p>
<ul>
<li><p>The <strong>Veteran status</strong> form is updated with a field to specify which user-defined veteran statuses are considered as protected under VEVRAA.</p></li>
<li><p>Employees who are identified with one of the protected veteran statuses or as a disabled veteran are counted in the aggregate totals on the redesigned VETS preparation report.</p></li>
</ul></td>
</tr>
</tbody>
</table>

  


