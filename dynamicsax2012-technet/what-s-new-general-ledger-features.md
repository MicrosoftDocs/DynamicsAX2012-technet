---
title: "What's new: General ledger features"
TOCTitle: General ledger features
ms:assetid: 1162f17e-46b7-4b40-8fbe-7f6626e79634
ms:mtpsurl: https://technet.microsoft.com/library/Dn507123(v=AX.60)
ms:contentKeyID: 59623212
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# What's new: General ledger features 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

We have changed and added functionality in the [General ledger](general-ledger.md) area for Microsoft Dynamics AX 2012. For more information, see the tables that apply to your version of the product.

## What’s new in AX 2012

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
<td><p>Print financial statements to Microsoft Excel.</p></td>
<td><p>You can print financial statements to Excel.</p>
<p>For more information, see <a href="generate-print-and-export-a-traditional-financial-statement.md">Generate, print, and export a traditional financial statement</a>.</p></td>
</tr>
<tr class="even">
<td><p>Separate ledgers for each legal entity</p></td>
<td><p>Each legal entity has a separate ledger, where you define a chart of accounts, the accounting currency, the reporting currency, and the fiscal calendar for that legal entity.</p>
<p>For more information, see <a href="set-up-a-ledger.md">Set up a ledger</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Changes to Finance list pages and Finance reports.</p></td>
<td><p>In Enterprise Portal for Microsoft Dynamics AX, list pages that are related to Finance are included in the Sales and Procurement areas. The following list pages use standard elements for list pages, such as Action Panes, FactBoxes, and preview panes: Customer invoices, Unpaid customer invoices, Latest invoiced items, Interest notes, Collection letters, and Vendor invoices. The following details pages use standard elements for details pages, such as Action Panes, FactBoxes, and FastTabs: Customer invoice, Interest note, Collection letter, and Vendor invoice. A new Finance reports list page provides access to financial reports in Enterprise Portal.</p></td>
</tr>
<tr class="even">
<td><p>Shared exchange rates for the General ledger consolidation process</p></td>
<td><p>You can define multiple exchange rates between two currencies, and select a currency rate type for each range of accounts and company accounts that is being consolidated.</p>
<p>For more information, see the white paper titled <a href="https://download.microsoft.com/download/4/e/3/4e36b655-568e-4d4a-b161-152b28baaf30/shared_currencies_and_exchange_rates_ax2012.pdf">Shared Currencies and Exchange Rates for Microsoft Dynamics AX 2012</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Reporting currency</p></td>
<td><p>The reporting currency is the accounting currency amount multiplied by the exchange rate. The reporting currency must be calculated and revalued, even if the exchange rate for the accounting currency does not change.</p>
<p>For more information, see the white paper <a href="https://download.microsoft.com/download/f/0/e/f0e719b8-aded-4157-b31b-d036f8308f1f/microsoft+dynamics+ax+shared+financial+data+management+white+paper.pdf">Shared financial data management for Microsoft Dynamics AX 2012</a>.</p></td>
</tr>
<tr class="even">
<td><p>Enhancements to financial analysis cubes</p></td>
<td><p>The following changes are included:</p>
<ul>
<li><p>Data in the General ledger, Accounts payable, and Accounts receivable cubes can be analyzed as of a specific date.</p></li>
<li><p>The currency conversion process that is used to analyze financial cube data in Excel has been updated.</p></li>
<li><p>The following key performance indicators (KPIs) for General ledger are calculated based on dates, not periods: Average Days Delinquent, Accounts Receivable Days Outstanding, Best Possible Days Sales Outstanding, and Collection Effectiveness Index.</p></li>
<li><p>Trend calculations for the following General ledger KPIs have been removed: Average Days Delinquent, Accounts Receivable Days Outstanding, Best Possible Days Sales Outstanding, and Collection Effectiveness Index.</p></li>
</ul>
<p>For more information, see <a href="cube-and-kpi-reference-for-microsoft-dynamics-ax-2012-and-microsoft-dynamics-ax-2012-feature-pack.md">Cube and KPI reference for Microsoft Dynamics AX 2012 and Microsoft Dynamics AX 2012 Feature Pack</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Relieve encumbrances when you confirm purchase orders.</p></td>
<td><p>When you confirm a purchase order that is generated from one or more pre-encumbered purchase requisition lines, the purchase order is posted to the general ledger. Any pre-encumbrances are also relieved.</p>
<p>For more information, see <a href="about-purchase-order-encumbrances.md">About purchase order encumbrances</a>.</p></td>
</tr>
<tr class="even">
<td><p>Reason codes for purchase order transactions</p></td>
<td><p>You can now add reason codes to the posting transactions for purchase orders. Reason codes help explain why transactions were entered, such as why an order was returned, or why the amount that was received differs from the amount that was ordered.</p>
<p>For more information, see <a href="about-financial-reason-codes.md">About financial reason codes</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Record purchase order encumbrances in the general ledger.</p></td>
<td><p>When you confirm a purchase order, you can record the encumbrances in general ledger accounts. Therefore, you can accrue liabilities.</p>
<p>Most public sector organizations record encumbrance transactions to record accruals of liabilities for committed, or obligated, purchases. In the <strong>General ledger parameters</strong> form, you can select the <strong>Enable encumbrance process</strong> check box to activate recording in ledger accounts. The ledger accounts that you record in are specified by posting definitions, and you associate these ledger accounts with the purchase order transaction by using the <strong>Transaction posting definitions</strong> form.</p>
<p>For more information, see <a href="encumber-purchase-orders.md">Encumber purchase orders</a>.</p></td>
</tr>
<tr class="even">
<td><p>View and track encumbered amounts on purchase orders.</p></td>
<td><p>When the encumbrance process is enabled, you can view the encumbered amounts, encumbrances that are relieved through invoice processing, and encumbered amounts that remain after invoice processing.</p>
<p>For more information, see <a href="about-purchase-order-encumbrances.md">About purchase order encumbrances</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Create reports that group vendor invoices or customer invoices by a selected financial dimension.</p></td>
<td><p>The <strong>Open invoice transactions</strong> report and the <strong>Sales invoice journal</strong> report have been changed. These reports are now the <strong>Vendor invoice transactions</strong> report, which is created in Accounts payable, and the <strong>Customer invoice transactions</strong> report, which is created in Accounts receivable. You can create the reports to group transactions by a selected financial dimension. You can select invoices for both reports by using various criteria. Both reports include options to select invoices by date or date range, and you can display all invoices, only paid invoices, or only invoices that are in an open state.</p>
<p>For more information, see <a href="vendor-invoice-transactions-report-vendinvoice.md">Vendor invoice transactions report (VendInvoice)</a> and <a href="customer-invoice-transactions-report-custinvoice.md">Customer invoice transactions report (CustInvoice)</a>.</p></td>
</tr>
<tr class="even">
<td><p>Create a reconciliation report of purchase order encumbrances.</p></td>
<td><p>You can create a reconciliation report that is grouped by the general ledger chart of accounts dimension that you select. This report identifies differences between budget reservations for encumbrances and the corresponding encumbrances that are tracked in the general ledger. You can view either a detailed version of the report or only the differences. The detailed version shows totals by transaction or document number for all encumbrances. The version that displays differences shows only instances where the budget reservation amount for encumbrances does not balance with the corresponding encumbrance accounts in the general ledger.</p>
<p>For more information, see <a href="encumbrance-and-ledger-reconciliation-report-ledgerencumbrancereconciliation.md">Encumbrance and ledger reconciliation report (LedgerEncumbranceReconciliation)</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Accounts payable payments and payment clearing</p></td>
<td><p>You can use posting definitions to record vendor payments for vendor invoices and promissory notes. For example, you can record a vendor payment by posting a vendor payment journal. The vendor payment journal can generate multiple transactions, and uses the distributions on the vendor invoice and the posting definitions to support pooled cash accounting. When bridged costing is enabled on the method of payment, you can use a clearing account for payments to track checks or warrants that have been issued, but that have not yet cleared the bank.</p>
<p>For more information, see <a href="examples-posting-definitions.md">Examples: Posting definitions</a> and <a href="examples-posting-definitions-public-sector.md">Examples: Posting definitions (Public sector)</a>.</p></td>
</tr>
<tr class="even">
<td><p>Simplified calendar options</p></td>
<td><p>You can use the streamlined <strong>Fiscal calendars</strong> form to create multiple calendars in Accounts payable, Accounts receivable, General ledger, Project, and Inventory management. You can maintain all calendar types, even fixed asset calendars and fiscal year calendars, in one form. You can also define multiple closing periods for a specific date. This feature helps you better track and report on multiple audit adjustments.</p>
<p>For more information, see the white paper <a href="https://download.microsoft.com/download/f/0/e/f0e719b8-aded-4157-b31b-d036f8308f1f/microsoft+dynamics+ax+shared+financial+data+management+white+paper.pdf">Shared financial data management for Microsoft Dynamics AX 2012</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Enhancements to fiscal periods</p></td>
<td><p>Many enhancements have been made to the functionality for fiscal periods. You can now use multiple fiscal years, enter multiple closing periods that have the same starting and ending dates, and copy the setup of periods to the next year. You can also change a sequence of months more quickly. To support these enhancements, the <strong>Periods</strong> and <strong>Fixed asset calendars</strong> forms have been removed, and fiscal period functionality is included in the <strong>Fiscal calendars</strong> and <strong>Ledger calendar</strong> forms.</p>
<p>For more information, see <a href="about-fiscal-calendars-fiscal-years-and-periods.md">About fiscal calendars, fiscal years, and periods</a>.</p></td>
</tr>
<tr class="even">
<td><p>Create shared fiscal calendars that can be used by different entities.</p></td>
<td><p>You can create and use calendars that are independent of your organization and shared by multiple legal entities. An organization can create one or more calendars that can be used by different legal entities that are part of the organization.</p>
<p>For more information, see <a href="key-tasks-fiscal-calendars-fiscal-years-and-periods.md">Key tasks: Fiscal calendars, fiscal years, and periods</a>.</p></td>
</tr>
<tr class="odd">
<td><p>New Treasurer Role Center</p></td>
<td><p>The Treasurer Role Center is a default home page that provides an overview of information that pertains to your work, such as your work list, frequently used links, and KPI information. The Treasurer Role Center includes two new KPI reports: Treasurer asset analysis (TreasurerAssetAnalysis) and Treasurer liabilities analysis (TreasurerLiabilitiesAnalysis).</p>
<p>The Treasurer Role Center has the same four KPIs that the Role Centers for the controller, CFO, accountant, and accounting manager have, but the reports match the treasurer title: Treasurer profitability analysis, Treasurer operational efficiency, Treasurer short-term solvency, and Treasurer long-term solvency. This Role Center also has pie charts for check information and outstanding debt, and a Fixed asset replacements list report. This Role Center uses existing General ledger cube measures and dimensions.</p></td>
</tr>
<tr class="even">
<td><p>Updates to posting definitions</p></td>
<td><p>If your organization requires multiple offsetting entries for transactions, you can set up posting definitions that determine the balanced set of ledger posting entries that is generated, based on the originating entry for a transaction. You can set up posting definition versions that have date-effective ranges, and the criteria for matching account numbers can include account structures, dimensions that are enabled for budgeting, and accounts that are generated from account rules. You can use transaction posting definitions to specify the posting definitions that are used, and to assign those posting definitions to transaction posting types.</p>
<p>For more information, see <a href="about-posting-definitions.md">About posting definitions</a>.</p></td>
</tr>
<tr class="odd">
<td><p>New distributions and budget-related functionality for year-end processing</p></td>
<td><p>You can close purchase orders in the fiscal year that is ending and open them in the next fiscal year. You can also create budget adjustments and carry-forward budget register entries.</p>
<p>For more information, see <a href="process-purchase-orders-at-year-end.md">Process purchase orders at year end</a>.</p></td>
</tr>
</tbody>
</table>


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
<td><p>Interunit accounting</p></td>
<td><p>Interunit accounting can be used to identify a financial dimension as balancing, so that a balanced balance sheet can be generated for the selected financial dimension. After a balancing financial dimension is defined on the ledger, every accounting entry is validated to make sure that it is also balanced at the financial dimension level. If any financial dimension values are unbalanced, interunit due-to and interunit due-from account entries are generated to balance the accounting entry.</p>
<p>For more information, see <a href="enable-interunit-accounting.md">Enable interunit accounting</a>.</p></td>
</tr>
<tr class="even">
<td><p>Legal entities can have more than one consolidation account.</p></td>
<td><p>Some local governments might mandate a specific chart of accounts, which is also known as a statutory chart of accounts. Main accounts can be shared between legal entities, and you can map the same main account to multiple consolidation accounts to create a statutory chart of accounts, which can also be shared between legal entities. The additional consolidation accounts are grouped in a consolidation account group, which you can select during the consolidation process.</p>
<p>For more information, see <a href="create-consolidation-groups-and-additional-consolidation-accounts.md">Create consolidation groups and additional consolidation accounts</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Tax registration numbers can be defined at the party address record level.</p></td>
<td><p>You can create tax registration number types and set up tax registration numbers for customers, vendors, and legal entities at the address level.</p>
<p>For more information, see <a href="set-up-a-tax-registration-type.md">Set up a tax registration type</a>.</p></td>
</tr>
<tr class="even">
<td><p>Fixed values for financial dimensions</p></td>
<td><p>For each main account in a specific chart of accounts, you can designate a default financial dimension value as a fixed value for each company that uses the chart of accounts. If the default financial dimension value differs, or if the user manually changes the default financial dimension value for the main account to a fixed dimension value, the financial dimension is changed to the fixed value during posting.</p>
<p>For more information, see the white paper <a href="https://download.microsoft.com/download/c/2/7/c27f2e17-e439-4eee-9630-0aae6eb44935/microsoft+dynamics+ax+2012+r2+shared+financial+data+management+white+paper.pdf">Microsoft Dynamics AX 2012 R2 Shared Financial Data Management‎</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Expanded support for default descriptions</p></td>
<td><p>For several countries and regions, you can add parameters to the three default parameters to format the contents of descriptions that are added to lines that are posted to the general ledger.</p>
<p>In the <strong>Default descriptions</strong> form, you can use the following parameters to create default descriptions for the following transaction types:</p>
<ul>
<li><p>Customer – cash payment</p></li>
<li><p>Customer – credit note, customer</p></li>
<li><p>Customer – credit note, ledger</p></li>
<li><p>Customer – invoice, customer</p></li>
<li><p>Customer – invoice, ledger</p></li>
<li><p>Customer – payment, customer</p></li>
<li><p>Fixed asset – posting, ledger</p></li>
<li><p>Inventory – journal – adjustment</p></li>
<li><p>Inventory – journal – BOM</p></li>
<li><p>Inventory – journal – counting</p></li>
<li><p>Inventory – journal – move</p></li>
<li><p>Inventory – journal – transaction</p></li>
<li><p>MRP – costing</p></li>
<li><p>MRP – job card</p></li>
<li><p>MRP – picking list</p></li>
<li><p>MRP – report as finished</p></li>
<li><p>MRP – route card</p></li>
<li><p>Purchase order – invoice, ledger</p></li>
<li><p>Purchase order – credit note, vendor</p></li>
<li><p>Purchase order – invoice, ledger</p></li>
<li><p>Purchase order – invoice, vendor</p></li>
<li><p>Purchase order – product receipt, ledger</p></li>
<li><p>Purchase order – purchase order confirmation, ledger</p></li>
<li><p>Sales order – credit note, customer</p></li>
<li><p>Sales order – credit note, ledger</p></li>
<li><p>Sales order – invoice, customer</p></li>
<li><p>Sales order – invoice, ledger</p></li>
<li><p>Sales order – packing slip, ledger</p></li>
<li><p>Sales order – cash payment</p></li>
<li><p>Sales order – payment, vendor</p></li>
</ul>
<p>This feature is available for the following countries and regions:</p>
<ul>
<li><p>China</p></li>
<li><p>India</p></li>
<li><p>Japan</p></li>
<li><p>Czech Republic</p></li>
<li><p>Estonia</p></li>
<li><p>Hungary</p></li>
<li><p>Lithuania</p></li>
<li><p>Latvia</p></li>
<li><p>Poland</p></li>
<li><p>Russian Federation</p></li>
<li><p>Brazil</p></li>
</ul>
<p>For more information, see <a href="set-up-default-descriptions-for-automatic-posting.md">Set up default descriptions for automatic posting</a>.</p></td>
</tr>
<tr class="even">
<td><p>New framework for importing exchange rates</p></td>
<td><p>Existing exchange rate import features that were available for various countries/regions, which include Russia and Eastern Europe, have been consolidated, and a framework for exchange rate import features is available.</p>
<p>New providers can be added in C# or X++ and used by the framework. You can define a provider for importing currency exchange rates and periodically import those exchange rates between pairs of currencies.</p>
<p>For more information, see the white paper <a href="http://www.microsoft.com/en-us/download/details.aspx?id=36047">Creating Exchange Rate Providers for Microsoft Dynamics AX 2012</a> and the topic <a href="rus-set-up-import-of-exchange-rates.md">(RUS) Set up import of exchange rates</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Shared lists of main accounts</p></td>
<td><p>In AX 2012 R2, the same chart of accounts can be shared across legal entities. The list of main accounts in the chart of accounts can contain various account structures, and more than one account structure can be assigned to each legal entity's ledger.</p>
<p>For more information, see the white paper <a href="https://go.microsoft.com/fwlink/?linkid=246258">Microsoft Dynamics AX Shared Financial Data Management</a>.</p></td>
</tr>
<tr class="even">
<td><p>Updates to General ledger reports</p></td>
<td><p>Reports that display amounts in the accounting currency, transaction currency, and reporting currency have been updated to display those amounts in both debit and credit columns, instead of just one column.</p></td>
</tr>
<tr class="odd">
<td><p>Configure a recurring schedule batch job to clear purchase accrual for product receipt source documents.</p></td>
<td><p>You can configure when and where to run the process for clearing purchase accrual. A recurring schedule batch job to clear purchase accrual for product receipt source documents is installed for each legal entity. You can configure the batch job to specify how many sub-batch tasks the batch job can use to process a subset of product receipt source documents that have an accounting event type of <strong>Finalized</strong> and an accounting event status of <strong>Started</strong>.</p>
<p>For more information, see <a href="set-up-parameters-for-the-journalized-finalized-product-receipt-batch-job.md">Set up parameters for the Journalized finalized product receipt batch job</a>.</p></td>
</tr>
<tr class="even">
<td><p>General ledger balances are updated when a process requires balances.</p></td>
<td><p>General ledger balances are no longer updated during the posting process. Instead, general ledger balances are updated whenever a process requires balances. For example, the general ledger balances are updated when you view the <strong>Trial balance</strong> list page. If you are using cubes that rely on updated general ledger balances, you must click the <strong>Update balances</strong> button in the <strong>Financial dimension sets</strong> form before you process cube data. To improve performance during balance calculations, you can schedule a batch to update balances more frequently, such as every two hours. When balances have to be calculated, only two hours’ worth of data has to be calculated.</p>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="https://technet.microsoft.com/library/aa597282(v=ax.60)">Financial dimension sets (form)</a></p></li>
<li><p><a href="general-ledger-cube-ledgercube-for-microsoft-dynamics-ax-2012-r2-and-r3.md">General ledger cube (LedgerCube) for Microsoft Dynamics AX 2012 R2</a></p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Language translations for the main account name and the financial dimension description</p></td>
<td><p>You can enter a language translation for the main account name and the custom description of the financial dimension value.</p>
<p>For more information, see <a href="https://technet.microsoft.com/library/hh209695(v=ax.60)">Main accounts - chart of accounts (form)</a>.</p></td>
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
<td><p>Multiple reporting currencies can be displayed on financial statements when you use Management Reporter for Microsoft Dynamics ERP.</p></td>
<td><p>If you use Management Reporter to generate financial statements for your organization, you can display data in multiple reporting currencies on those statements.</p>
<p>For more information, see Planning your financial statements.</p></td>
</tr>
<tr class="even">
<td><p>Updates to list pages for trial balances</p></td>
<td><p>You can view the following additional information on the <strong>Trial balance</strong> list page:</p>
<ul>
<li><p>Ledger account names.</p></li>
<li><p>Each account segment in a separate column, when you select the <strong>Display account number segments in separate columns</strong> option. This option is useful when you export the information on the list page.</p></li>
<li><p>Links to details for the amounts that are displayed.</p></li>
<li><p>Journal entries that are included in the ending balance amount for a ledger account.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Financial reporting options</p></td>
<td><p>A configuration key controls access to the traditional financial statement functionality and forms that are included with Microsoft Dynamics AX. The configuration key is not selected automatically in new installations of Microsoft Dynamics AX so that new users can use Management Reporter.</p>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="financial-statements-traditional-configuration-key-ledgerbalancestatement.md">Financial statements (traditional) configuration key (LedgerBalanceStatement)</a></p></li>
<li><p><a href="about-traditional-financial-statements.md">About traditional financial statements</a></p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Suspended or inactive financial dimension values are not displayed in lookup forms.</p></td>
<td><p>Financial dimension values that are inactive or suspended are not displayed in lookup forms for account number fields in the Microsoft Dynamics AX client.</p>
<p>To indicate that a financial dimension value is suspended, select the <strong>Suspended</strong> check box in the <strong>Financial dimension values</strong> form. A financial dimension value is considered inactive when the system date falls outside the range that is specified by the <strong>Active from</strong> and <strong>Active to</strong> dates in the <strong>Financial dimension values</strong> form.</p></td>
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
<td><p>An Excel template for journal entries is included on the virtual machine for demo data.</p></td>
<td><p>You can more easily generate journal entries in the Contoso demo data by using the Office Add-ins for Microsoft Dynamics AX. The GLJournal_usmf.xls file is located in C:/GeneralLedgerTemplates on the virtual machine. Make changes in Excel, and then import the journal entries into the appropriate journal.</p>
<p>You can use the Excel template as a guide to create your own template. Don’t modify the sample template, because this template contains metadata that is based on the installation that was used to create it. You must create your own template, so that the metadata is correct.</p>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="about-using-the-microsoft-dynamics-ax-add-in-for-excel.md">About using the Microsoft Dynamics AX Add-in for Excel</a></p></li>
<li><p><a href="about-importing-data-from-microsoft-excel.md">About importing data from Microsoft Excel</a></p></li>
<li><p><a href="update-microsoft-dynamics-ax-data-by-using-microsoft-excel.md">Update Microsoft Dynamics AX data by using Microsoft Excel</a></p></li>
<li><p><a href="key-tasks-create-and-share-an-excel-template-by-using-the-office-add-ins.md">Key tasks: Create and share an Excel template by using the Office Add-ins</a></p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>More understandable posting messages for journal lines that have errors in the account combination</p></td>
<td><p>In earlier releases, error and warning messages that are associated with posting processes were sometimes hard to understand. Now, the messages are grouped by voucher, so that it’s easier to determine which journal lines have errors in the account combination. Lines that have errors in the account combination are indicated by a visual indicator. You can also display only the lines that have errors. For more information, see <a href="https://technet.microsoft.com/library/aa591466(v=ax.60)">Journal voucher - General journal (form)</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Delete an unposted journal that contains lines.</p></td>
<td><p>In earlier releases, you had to delete the lines first, and then you could delete an unposted journal. Now, if you delete the journal, the lines are automatically deleted.</p></td>
</tr>
<tr class="even">
<td><p>View advanced rules for a main account.</p></td>
<td><p>You can view the advanced rules that a main account is associated with. For more information, see <a href="https://technet.microsoft.com/library/hh209695(v=ax.60)">Main accounts - chart of accounts (form)</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Easier dimension setup for Excel integration</p></td>
<td><p>You can select financial dimensions that are displayed in Excel. Use the <strong>Financial dimensions used as document data sources</strong> form to select financial dimensions.</p>
<p>For more information, see <a href="set-up-financial-dimensions-for-integrating-applications-excel-and-management-reporter.md">Set up financial dimensions for integrating applications (Excel and Management Reporter)</a> and <a href="https://technet.microsoft.com/library/hh242667(v=ax.60)">Financial dimension values (form)</a>.</p></td>
</tr>
<tr class="even">
<td><p>Display dimensions in a specified order in Management Reporter.</p></td>
<td><p>You can select the order in which financial dimensions are displayed in Management Reporter. Use the <strong>Financial dimensions used as document data sources</strong> form to specify the order.</p>
<p>For more information, see <a href="set-up-financial-dimensions-for-integrating-applications-excel-and-management-reporter.md">Set up financial dimensions for integrating applications (Excel and Management Reporter)</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Default dimension values follow a consistent pattern in accounting distributions.</p></td>
<td><p>Default dimension values follow a consistent pattern. For example, the default dimension values for tax for a charge use values from the distributions in the following hierarchy:</p>
<p>Parent distribution (charge) &gt; Grandparent distribution (extended price) &gt; Default dimensions on the document line &gt; Main account</p></td>
</tr>
<tr class="even">
<td><p>Currency translation and rounding enhancements for source documents</p></td>
<td><p>Document-level rounding of currency translation is applied to accounting entries for sales tax only if no other accounting entries exist. Document-level rounding of currency translation is required for reconciliation with subledgers, accounts payable, and accounts receivable, for example.</p></td>
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
<td><p>Opening transactions (year-end closing)</p></td>
<td><p>In earlier releases, the transfer of opening balances for more than one company at a time caused performance issues. You can now transfer the opening balances for balance sheet accounts to a new fiscal year in multiple companies at the same time.</p></td>
</tr>
<tr class="even">
<td><p>Accounting for stocked items on product receipts and vendor invoices</p></td>
<td><p>The results of the accounting entries for stocked items on product receipts and vendor invoices are combined into one subledger journal entry and voucher.</p>
<p>Accounting entries for Purchase expenditure, un-invoiced are not transferred to the general ledger if the amount for both the accounting currency and the reporting currency adds up to 0 (zero) per voucher, currency code, and ledger dimension.</p>
<p>Accounting entries for Purchase expenditure for product are transferred in summary form to the general ledger per voucher, currency code, and ledger dimension.</p></td>
</tr>
</tbody>
</table>

  


