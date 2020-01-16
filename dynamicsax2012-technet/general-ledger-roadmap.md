---
title: General ledger roadmap
TOCTitle: General ledger roadmap
ms:assetid: 7d832e8d-954b-4f14-807d-932f9d5c603b
ms:mtpsurl: https://technet.microsoft.com/library/Dn783392(v=AX.60)
ms:contentKeyID: 62838586
author: Khairunj
ms.date: 11/14/2014
mtps_version: v=AX.60
f1_keywords:
- General ledger roadmap
- GL roadmap
audience: Application User
ms.search.region: Global
---

# General ledger roadmap 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic is a roadmap to additional information about General ledger in Microsoft Dynamics AX. It includes links to information about how to get started, configure, and use General ledger, and which modules integrate with General ledger.

General ledger provides an efficient way for organizations to manage their financial records. The general ledger is a register of debit and credit entries that are classified by using the accounts and financial dimensions that are listed in the chart of accounts.

General ledger offers flexible options for setting up and maintaining shared charts of accounts, currencies, exchange rates, and fiscal calendars. You can allocate costs and income by using the period-end allocation, elimination, and multicompany consolidation processes. You can quickly inquire and report on ledger transactions and account balances, and use financial dimensions to analyze your organization’s financial data from a variety of perspectives.

General ledger also covers fixed assets, cost accounting, cash flow forecasting, currency requirement projections, and country/region-specific capabilities. Other capabilities include audit workbench, budget control, compliance management, and shared services.

This topic includes links to important information about how to set up and use General ledger.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><img src="images/Dn800886.TopicIcons_OnThisPage(AX.60).png" title="On this page" alt="On this page" />
<p>Get started</p>
<p>Configure</p>
<p>Use</p>
<p>Reports</p>
<p>Integration with General ledger</p>
<p>Still didn’t find what you were looking for?</p></td>
<td><img src="images/Dn800886.TopicIcons_RelatedResources(AX.60).png" title="Related resources" alt="Related resources" />
<p><a href="http://go.microsoft.com/fwlink/?linkid=507515">Planning your chart of accounts in AX 2012</a> (blog)</p>
<p><a href="http://go.microsoft.com/fwlink/?linkid=397377">Shared Financial Data Management for Microsoft Dynamics AX 2012 R2</a> (white paper)</p>
<p><a href="http://go.microsoft.com/fwlink/?linkid=397378">Implementing the account and dimensions framework</a> (white paper)</p>
<p><a href="financial-consolidations-and-currency-translation.md">Financial consolidations and currency translation by using Management Reporter</a> (white paper)</p>
<p><a href="http://blogs.msdn.com/b/dynamics_financial_reporting/">Dynamics Financial Reporting</a> (blog)</p>
<p><a href="http://community.dynamics.com/ax/f/33.aspx">Microsoft Dynamics AX Forum</a> (forum)</p>
<p><a href="http://www.microsoft.com/en-us/download/details.aspx?displaylang=en%26id=29210">Help and Resources Datasheet for Dynamics AX 2012</a> (download)</p>
<p><a href="https://lcs.dynamics.com/home/homeindex">Lifecycle Services</a>* (cloud-based workspace)</p>
<p>* In order to use Lifecycle Services, you must have a CustomerSource or PartnerSource account, and have created a project. For more information, see the <a href="lifecycle-services-for-microsoft-dynamics-user-guide-lcs.md">Lifecycle Services for Microsoft Dynamics User Guide (LCS)</a></p></td>
</tr>
</tbody>
</table>


## Get started

The section includes information about General ledger and how you can set up and use it in a Microsoft Dynamics AX 2012 implementation.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Details</p></th>
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Learn about General ledger</p></td>
<td><p>General ledger provides a way for organizations to define and manage their financial records.</p></td>
<td><p>We recommend that you become familiar with the concepts described in these links before you set up and use General ledger.</p>
<p><a href="general-ledger.md">General ledger</a></p></td>
</tr>
<tr class="even">
<td><p>Learn what’s new in General ledger</p></td>
<td><p>Review new and changed General ledger features since the release of AX 2012.</p></td>
<td><p><a href="what-s-new-general-ledger-features.md">What's new: General ledger features</a></p></td>
</tr>
</tbody>
</table>


Back to top

## Configure

This section provides information about how to set up General ledger.

## Prerequisites

This section provides information about what to consider before you set up General ledger.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Details</p></th>
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Plan and create organizations and organizational hierarchies</p></td>
<td><p>Plan and create organizations such as legal entities, operating units, and teams. The organizational hierarchies that you create represent the relationships between the organizations that make up your business. The organizational hierarchies affect the setup of the account structure in General ledger.</p></td>
<td><p>We recommend that you become familiar with the concepts and limitations of organizations and organizational hierarchies that are described in these links before you set up General ledger.</p>
<p><a href="organizations-and-organizational-hierarchies.md">Organizations and organizational hierarchies</a></p></td>
</tr>
<tr class="even">
<td><p>Plan the chart of accounts</p></td>
<td><p>Account structures in General ledger consist of main accounts and can include financial dimension segments. The account structures are used to define the valid combinations which, together with the main accounts, form a chart of accounts.</p>
<p>If two or more segments of an account structure are organization units, such as Business unit or Department, an organization hierarchy can be used to determine the valid combinations. The constraints would not have to be defined directly in the account structure.</p></td>
<td><p><a href="http://go.microsoft.com/fwlink/?linkid=507724">Planning your chart of accounts in AX 2012</a></p></td>
</tr>
</tbody>
</table>


## Set up General ledger

This section lists tasks you can complete to set up General ledger.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Details</p></th>
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Set up required General ledger information</p></td>
<td><p>Set up ledgers, enable interunit accounting, and create currency codes.</p></td>
<td><p><a href="set-up-a-ledger.md">Set up a ledger</a></p>
<p><a href="enable-interunit-accounting.md">Enable interunit accounting</a></p>
<p><a href="create-a-currency-code.md">Create a currency code</a></p>
<p><a href="example-balanced-accounting-entry-for-interunit-accounting.md">Example: Balanced accounting entry for interunit accounting</a></p></td>
</tr>
<tr class="even">
<td><p>Set up the chart of accounts</p></td>
<td><p>Create main accounts and financial dimensions, set up charts of accounts, set up ledger account aliases, set up main account categories, and create advanced account structures.</p></td>
<td><p><a href="setting-up-the-chart-of-accounts.md">Setting up the chart of accounts</a></p>
<p><a href="about-the-chart-of-accounts.md">About the chart of accounts</a></p>
<p><a href="about-main-account-types.md">About main account types</a></p>
<p><a href="create-a-main-account.md">Create a main account</a></p>
<p><a href="create-a-financial-dimension.md">Create a financial dimension</a></p>
<p><a href="create-consolidation-groups-and-additional-consolidation-accounts.md">Create consolidation groups and additional consolidation accounts</a></p>
<p><a href="set-up-a-chart-of-accounts.md">Set up a chart of accounts</a></p>
<p><a href="about-the-configure-account-structures-form.md">About the Configure account structures form</a></p>
<p><a href="set-up-a-ledger-account-alias.md">Set up a ledger account alias</a></p>
<p><a href="set-up-main-account-categories.md">Set up main account categories</a></p>
<p><a href="main-account-categories-and-analysis-cubes.md">Main account categories and analysis cubes</a></p>
<p><a href="create-advanced-account-structures-and-rules-for-a-chart-of-accounts.md">Create advanced account structures and rules for a chart of accounts</a></p>
<p><a href="create-advanced-account-structures-and-rules-for-budget-planning.md">Create advanced account structures and rules for budget planning</a></p>
<p><a href="link-main-accounts-to-main-account-categories.md">Link main accounts to main account categories</a></p>
<p><a href="create-a-financial-dimension-default-template.md">Create a financial dimension default template</a></p>
<p><a href="create-a-financial-dimension-set.md">Create a financial dimension set</a></p></td>
</tr>
<tr class="odd">
<td><p>Set up and maintain journals</p></td>
<td><p>Create ledger accrual transactions, post and print journals or journal lines, post multiple journals, set up financial journal approvals, delete posted ledger journals, set up General ledger workflows, set up posting restrictions, and approve journals.</p></td>
<td><p><a href="setting-up-and-maintaining-journals.md">Setting up and maintaining journals</a></p></td>
</tr>
<tr class="even">
<td><p>Set up posting</p></td>
<td><p>Set up posting definitions, create accrual schemes, and create and validate journals and journal lines.</p></td>
<td><p><a href="about-posting-definitions.md">About posting definitions</a></p>
<p><a href="examples-posting-definitions.md">Examples: Posting definitions</a></p>
<p><a href="set-up-posting-definitions.md">Set up posting definitions</a></p>
<p><a href="set-up-default-descriptions-for-automatic-posting.md">Set up default descriptions for automatic posting</a></p>
<p><a href="assign-posting-definitions-to-transaction-posting-types.md">Assign posting definitions to transaction posting types</a></p>
<p><a href="create-accrual-schemes.md">Create accrual schemes</a></p>
<p><a href="create-and-validate-journals-and-journal-lines.md">Create and validate journals and journal lines</a></p></td>
</tr>
<tr class="odd">
<td><p>Set up sales tax codes</p></td>
<td><p>Set up sales tax codes that contain basic information about the tax amounts you collect and pay to the tax authorities.</p>
<p>When you set up sales tax codes, you define the amounts or percentages that must be collected. You also define the various methods by which those amounts or percentages are applied to transaction amounts.</p></td>
<td><p><a href="about-the-marginal-base-field.md">About the Marginal base field</a></p>
<p><a href="about-the-sales-tax-calculation-methods-in-the-origin-field.md">About the sales tax calculation methods in the Origin field</a></p>
<p><a href="about-the-whole-amount-and-interval-options-for-sales-tax-codes.md">About the Whole amount and Interval options for sales tax codes</a></p>
<p><a href="set-up-and-use-sales-tax-codes.md">Set up and use sales tax codes</a></p>
<p><a href="create-various-kinds-of-sales-tax-codes.md">Create various kinds of sales tax codes</a></p>
<p><a href="set-up-a-sales-tax-on-a-sales-tax.md">Set up a sales tax on a sales tax</a></p>
<p><a href="setting-up-sales-tax-codes.md">Setting up sales tax codes</a></p></td>
</tr>
<tr class="even">
<td><p>Set up sales tax</p></td>
<td><p>Set up the sales tax functionality, such as sales tax, sales tax on sales tax, packing duties, and purchase duties.</p></td>
<td><p><a href="set-up-sales-tax-on-prepayments.md">Set up sales tax on prepayments</a></p>
<p><a href="set-up-a-sales-tax-settlement-period.md">Set up a sales tax settlement period</a></p>
<p><a href="set-up-conditional-sales-taxes.md">Set up conditional sales taxes</a></p>
<p><a href="about-including-sales-tax-in-journal-amounts.md">About including sales tax in journal amounts</a></p>
<p><a href="revise-the-sales-tax-amount-on-a-transaction-before-posting.md">Revise the sales tax amount on a transaction before posting</a></p>
<p><a href="assign-a-tax-exempt-number-to-a-customer.md">Assign a tax exempt number to a customer</a></p>
<p><a href="set-up-a-tax-registration-type.md">Set up a tax registration type</a></p></td>
</tr>
<tr class="odd">
<td><p>Set up sales tax groups and item sales tax groups</p></td>
<td><p>Set up groups of sales tax codes that are attached to customers, vendors, and ledger accounts for transactions that are not posted to a particular vendor account or customer account.</p></td>
<td><p><a href="set-up-and-use-a-sales-tax-group.md">Set up and use a sales tax group</a></p>
<p><a href="set-up-a-default-tax-profile-for-a-customer-or-vendor.md">Set up a default tax profile for a customer or vendor</a></p>
<p><a href="create-item-sales-tax-groups.md">Create item sales tax groups</a></p>
<p><a href="set-up-a-default-item-sales-tax-group-for-a-main-account.md">Set up a default item sales tax group for a main account</a></p>
<p><a href="set-up-ledger-posting-groups-for-sales-tax.md">Set up ledger posting groups for sales tax</a></p></td>
</tr>
<tr class="even">
<td><p>Set up sales tax authorities</p></td>
<td><p>Set up the sales tax authorities who require that you collect sales tax on their behalf and pay those taxes regularly.</p></td>
<td><p><a href="set-up-sales-tax-authorities.md">Set up sales tax authorities</a></p>
<p><a href="set-up-a-sales-tax-authority-as-a-vendor.md">Set up a sales tax authority as a vendor</a></p>
<p><a href="example-rounding-payments-made-to-sales-tax-authorities.md">Example: Rounding payments made to sales tax authorities</a></p>
<p><a href="view-or-print-sales-tax-payments-without-posting.md">View or print sales tax payments without posting</a></p></td>
</tr>
<tr class="odd">
<td><p>Set up U.S. sales tax</p></td>
<td><p>Set up sales tax jurisdictions and other sales tax and use rules that are specific to the United States.</p></td>
<td><p><a href="set-up-sales-tax-for-the-united-states.md">Set up sales tax for the United States</a></p>
<p><a href="set-up-sales-tax-jurisdictions.md">Set up sales tax jurisdictions</a></p>
<p><a href="set-up-sales-tax-groups-for-jurisdictions.md">Set up sales tax groups for jurisdictions</a></p>
<p><a href="usa-applying-u-s-sales-tax-and-use-tax-rules.md">(USA) Applying U.S. sales tax and use tax rules</a></p></td>
</tr>
<tr class="even">
<td><p>Set up withholding tax</p></td>
<td><p>Set up withholding tax that customers have to pay vendors in many countries/regions.</p></td>
<td><p><a href="set-up-withholding-tax-in-system-administration-and-general-ledger.md">Set up withholding tax in System administration and General ledger</a></p>
<p><a href="calculate-and-post-withholding-tax.md">Calculate and post withholding tax</a></p>
<p></p></td>
</tr>
<tr class="odd">
<td><p>Set up traditional financial statements</p></td>
<td><p>Set up row definitions and column definitions that are used to generate, print, and export traditional financial statements.</p></td>
<td><p><a href="setting-up-traditional-financial-statements.md">Setting up traditional financial statements</a></p></td>
</tr>
<tr class="even">
<td><p>Set up financial reports by using Management Reporter for Microsoft Dynamics ERP</p></td>
<td><p>Create, maintain, deploy, and view financial reports by using Management Reporter for Microsoft Dynamics ERP (recommended) instead of using the traditional financial statements in Microsoft Dynamics AX.</p>
<p>Management Reporter for Microsoft Dynamics ERP lets you design financial reports based on ledger accounts and financial dimensions, drill down to transaction-level detail, and use web-based report viewing.</p></td>
<td><p><a href="http://go.microsoft.com/fwlink/?linkid=324762">Management Reporter for Microsoft Dynamics ERP</a></p></td>
</tr>
<tr class="odd">
<td><p>Set up financial reason codes</p></td>
<td><p>Set up financial reason codes that are used to record changes, such as write-down adjustments or payment reversals.</p></td>
<td><p><a href="about-financial-reason-codes.md">About financial reason codes</a></p>
<p><a href="set-up-reason-codes-for-financial-modules.md">Set up reason codes for financial modules</a></p></td>
</tr>
<tr class="even">
<td><p>Maintain transactions in General ledger</p></td>
<td><p>Create reversing entries or place General ledger transactions on hold.</p></td>
<td><p><a href="create-a-reversing-entry.md">Create a reversing entry</a></p>
<p><a href="place-a-general-ledger-transaction-on-hold.md">Place a General ledger transaction on hold</a></p></td>
</tr>
<tr class="odd">
<td><p>Set up fiscal calendars, fiscal years, and periods</p></td>
<td><p>Set up fiscal calendars, fiscal years, and periods that can be shared by multiple legal entities.</p></td>
<td><p><a href="about-fiscal-calendars-fiscal-years-and-periods.md">About fiscal calendars, fiscal years, and periods</a></p>
<p><a href="key-tasks-fiscal-calendars-fiscal-years-and-periods.md">Key tasks: Fiscal calendars, fiscal years, and periods</a></p>
<p><a href="select-a-fiscal-calendar-for-a-ledger.md">Select a fiscal calendar for a ledger</a></p>
<p><a href="specify-which-users-can-post-to-a-period.md">Specify which users can post to a period</a></p></td>
</tr>
<tr class="even">
<td><p>Set up information for letters of guarantee</p></td>
<td><p>Activate letters of guarantee, and set up payment purposes or reason codes that specify the objective of letter of guarantee transactions or agreements.</p></td>
<td><p><a href="activate-the-letter-of-guarantee.md">Activate the letter of guarantee</a></p>
<p><a href="set-up-letter-of-guarantee-cancellation-reasons-and-purpose-code-types.md">Set up letter of guarantee cancellation reasons and purpose code types</a></p></td>
</tr>
</tbody>
</table>


Back to top

## Use

This section provides information about how to work with General ledger.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Details</p></th>
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Process closing transactions</p></td>
<td><p>Set up allocation rules and journals that you can use to allocate transactions, view posted journal entries, adjust ledger exchange transactions, journalize ledger transactions, and settle transactions between ledger accounts.</p></td>
<td><p><a href="process-closing-transactions-overview.md">Process closing transactions overview</a></p>
<p><a href="allocate-transactions.md">Allocate transactions</a></p>
<p><a href="maintain-ledger-accounts.md">Maintain ledger accounts</a></p>
<p><a href="close-transactions.md">Close transactions</a></p></td>
</tr>
<tr class="even">
<td><p>Allocate costs and income</p></td>
<td><p>Consolidate transactions, create cash flow forecasts and currency requirements forecasts, and eliminate transactions.</p></td>
<td><p><a href="allocate-costs-and-income-overview.md">Allocate costs and income overview</a></p>
<p><a href="consolidate-transactions.md">Consolidate transactions</a></p>
<p><a href="forecast-cash-flow-and-currency-requirements.md">Forecast cash flow and currency requirements</a></p>
<p><a href="eliminate-transactions.md">Eliminate transactions</a></p>
<p><a href="financial-consolidations-and-currency-translation.md">Financial consolidations and currency translation</a></p></td>
</tr>
<tr class="odd">
<td><p>Revalue currency amounts</p></td>
<td><p>Convert the accounting currency amounts to another currency on a specific date.</p></td>
<td><p><a href="revalue-currency-amounts-overview.md">Revalue currency amounts overview</a></p></td>
</tr>
<tr class="even">
<td><p>Close books</p></td>
<td><p>Complete closing procedures at the end of a month, period, or year. At the end of a period, you can close the period and prepare the accounting system for a new period.</p></td>
<td><p><a href="close-books-overview.md">Close books overview</a></p>
<p><a href="closing-the-month-period-and-fiscal-year.md">Closing the month, period, and fiscal year</a></p></td>
</tr>
</tbody>
</table>


Back to top

## Reports

This section includes information about how to create, maintain, deploy, and view reports for General ledger.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Item</p></th>
<th><p>Details</p></th>
<th><p>More</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Microsoft SQL Server Reporting Services reports</p></td>
<td><p>Several Reporting Services reports for General ledger are provided are available in the Report catalog.</p></td>
<td><p><a href="general-ledger-reports.md">General ledger reports</a></p></td>
</tr>
<tr class="even">
<td><p>Financial reports</p></td>
<td><p>To create, maintain, deploy, and view financial reports, you can use Management Reporter for Microsoft Dynamics ERP (recommended), or you can use the traditional financial statements that are included with AX 2012.</p></td>
<td><p><a href="http://go.microsoft.com/fwlink/?linkid=324762">Management Reporter for Microsoft Dynamics ERP</a></p>
<p><a href="about-traditional-financial-statements.md">About traditional financial statements</a></p></td>
</tr>
<tr class="odd">
<td><p>General ledger cube and Microsoft SQL Server Analysis Services reports</p></td>
<td><p>The General ledger cube is used to report on ledger accounts and bank accounts. Online analytical processing (OLAP) functionality is provided through the use of cubes.</p>
<p>These cubes, built on the Analysis Services platform, help you analyze large amounts of data and identify trends that you might not otherwise discover when you’re viewing data on traditional reports.</p></td>
<td><p><a href="general-ledger-cube-ledgercube-for-microsoft-dynamics-ax-2012-r2-and-r3.md">General ledger cube (LedgerCube) for Microsoft Dynamics AX 2012 R2 and R3</a></p>
<p><a href="analytics-in-microsoft-dynamics-ax.md">Analytics in Microsoft Dynamics AX</a></p></td>
</tr>
</tbody>
</table>


Back to top

## Integration with General ledger

General ledger can be integrated with the following modules and Microsoft products:

  - [Accounts payable](accounts-payable.md)

  - [Accounts receivable](accounts-receivable.md)

  - [Budgeting](budgeting.md)

  - [Cash and bank management](cash-and-bank-management.md)

  - [Fixed assets](fixed-assets.md)

  - [Human resources](human-resources.md)

  - [Inventory management](inventory-management.md)

  - [Payroll](payroll.md)

  - [Procurement and sourcing](procurement-and-sourcing.md)

  - [Project management and accounting](project-management-and-accounting.md)

  - [Retail for application users](retail-for-application-users.md)

  - [Sales and marketing](sales-and-marketing.md)

  - [Trade allowance management](trade-allowance-management.md)

  - [Transportation management](transportation-management.md)

  - [Travel and expense](travel-and-expense.md)

  - [Warehouse management](warehouse-management.md)

  - Microsoft SQL Server Analysis Services

  - Microsoft SQL Server Reporting Services

  - Microsoft Excel

Back to top



