---
title: What's new in Microsoft Dynamics AX 2012 R3
TOCTitle: What's new in Microsoft Dynamics AX 2012 R3
ms:assetid: 94f33aa0-c17e-477f-8e44-c4f9998fe261
ms:mtpsurl: https://technet.microsoft.com/library/Dn600262(v=AX.60)
ms:contentKeyID: 62200291
author: tonyafehr
ms.date: 06/27/2014
mtps_version: v=AX.60
---

# What's new in Microsoft Dynamics AX 2012 R3 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In Microsoft Dynamics AX 2012 R3, we added and changed several features. This topic lists the feature changes by module and by country/region, and provides links to related topics.

## New features for AX 2012 R3

The following table outlines the features that were added in AX 2012 R3.

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
<td><p>Call center</p></td>
<td><ul>
<li><p>A new retail channel type is added: call center. In a call center, workers take customer orders over the phone and create sales orders. Call centers can be added to organization hierarchies, and can be managed together with online stores and retail stores.</p></li>
<li><p>You can create catalogs for call centers, and use new catalog features.</p></li>
<li><p>You can associate details with sales items. This feature lets you view additional information about the selected line in the sales order form, such as images, purchase order information, delivery dates, and other relevant text.</p></li>
<li><p>You can create scripts that appear in the <strong>Sales order</strong> form at the time of order entry.</p></li>
<li><p>You can prompt the clerk who enters sales orders to up-sell or cross-sell products.</p></li>
<li><p>You can set up and manage continuity programs, in which customers receive regular product shipments on a predefined schedule.</p></li>
<li><p>You can create orders from an item list, which is a saved list of products that customers frequently order together.</p></li>
<li><p>You can track the status of a direct delivery purchase order via the associated sales order, and use the direct delivery workbench to create and release purchase orders for direct delivery. You can also specify products that are always sent to customers via direct delivery.</p></li>
<li><p>You can perform full-text searches for products in the <strong>Sales order</strong> form.</p></li>
<li><p>Precise control over pricing for call center sales orders is available.</p></li>
<li><p>You can view the calculated margin values for broker royalties and rebates in the sales order form.</p></li>
<li><p>Enhanced payment functionality can be used for call center orders.</p></li>
<li><p>Default sales tax groups can be used to create and view default priorities for calculating sales tax groups.</p></li>
<li><p>You can create coupons that can be applied to call center sales orders.</p></li>
<li><p>Installment payments can be used in sales orders.</p></li>
<li><p>Broker support is available.</p></li>
<li><p>You can put sales orders on hold.</p></li>
<li><p>You can set up an expedited shipping mode that can be applied to a sales order or sales order line.</p></li>
<li><p>Automatic notification and cancellation for backorders is available.</p></li>
<li><p>You can track sales order events.</p></li>
<li><p>You can view detailed order status.</p></li>
<li><p>You can attach notes to a customer, order, or order line.</p></li>
<li><p>You can define letter templates that can be used to generate personalized customer communications.</p></li>
<li><p>You can define fraud rules to warn call center workers about potential fraud situations.</p></li>
<li><p>RFM analysis can be performed on customers.</p></li>
<li><p>You can track customer statistics.</p></li>
<li><p>Enhanced functionality for customer service is added.</p></li>
<li><p>You can track customer cases.</p></li>
<li><p>Sales history can be purged.</p></li>
</ul>
<p>For more information, see <a href="what-s-new-call-center-features.md">What's new: Call center features</a>.</p></td>
</tr>
<tr class="even">
<td><p>General ledger</p></td>
<td><ul>
<li><p>You can transfer the opening balances for balance sheet accounts to a new fiscal year in multiple companies at the same time.</p></li>
<li><p>The results of the accounting entries for stocked items on product receipts and vendor invoices are combined into one subledger journal entry and voucher.</p></li>
</ul>
<p>For more information, see <a href="what-s-new-general-ledger-features.md">What's new: General ledger features</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Inventory and warehouse management</p></td>
<td><ul>
<li><p>The <strong>Compare item prices</strong> report lets you compare the prices in a costing version to the pending prices in another costing version, or to the active prices on an effective date.</p></li>
<li><p>The posting routine in the <strong>BOM journal</strong> is redesigned and enhanced.</p></li>
<li><p>The <strong>Inventory aging</strong> report displays the on-hand quantity, the inventory value, and the related aging periods for a selected item or an item group. You can use the report parameters to filter the data that is displayed on the report.</p></li>
</ul>
<p>For more information, see <a href="what-s-new-inventory-and-warehouse-management-features.md">What's new: Inventory and warehouse management features</a>.</p></td>
</tr>
<tr class="even">
<td><p>Master planning</p></td>
<td><p>Demand forecasting is a set of tools that enable you to estimate future demand and create demand forecasts based on historical transaction data. The demand forecasting process includes the following tasks:</p>
<ul>
<li><p>Complete the prerequisite setup tasks before you can use demand forecasting.</p></li>
<li><p>Create a baseline forecast from historical demand data that is gathered and loaded in a Microsoft SQL Server Analysis Services cube.</p></li>
<li><p>Open the demand forecast file, and use the PivotTable tools in Excel to filter and display the forecast data that is stored in the cube.</p></li>
<li><p>Optional: Make manual adjustments to the forecasted quantities in the demand forecast file.</p></li>
<li><p>Import a demand forecast to Microsoft Dynamics AX so specific companies and forecast models can use the forecast data as input to master planning.</p></li>
<li><p>Optional: Calculate the accuracy of past demand forecasts against past actual demand to improve forecast accuracy.</p></li>
<li><p>Optional: Remove outliers from the historical data to improve demand forecast accuracy.</p></li>
</ul>
<p>You can specify whether a customer forecast is included in the overall forecast. This setting determines how actual demand reduces the forecasted demand. You can use this setting to ensure that master planning covers the supply of items that are purchased by specific customers.</p>
<p>You can select the start time to schedule production orders. The start time can be the start of the calendar work day or the current time. The current time option is used with the delivery date control and capable to promise (CTP) feature.</p>
<p>For more information, see <a href="what-s-new-master-planning-features.md">What's new: Master planning features</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Microsoft Dynamics ERP RapidStart Services</p></td>
<td><p>For more information, see <a href="what-s-new-in-microsoft-dynamics-erp-rapidstart-services.md">What's new in Microsoft Dynamics ERP RapidStart Services</a>.</p></td>
</tr>
<tr class="even">
<td><p>Procurement and sourcing</p></td>
<td><ul>
<li><p>You can create your own solicitation types for requests for quotation (RFQs). This feature lets you match the procurement requirements for your organization. You can filter on those categories to find documents more easily.</p></li>
<li><p>You can define sets of scoring criteria and scoring methods that can be used to evaluate bids (RFQ replies).</p></li>
<li><p>You can allow vendors to provide alternate items or services, so that you can be notified of better alternatives or changes to a requested item or service.</p></li>
<li><p>Each line in an RFQ is assigned a number. You can add items and renumber the list as you require. The numbers appear in all the RFQ-related documents.</p></li>
<li><p>You can quickly add vendors for your RFQ who are approved for selling at least one of the categories on the RFQ lines.</p></li>
<li><p>You can create and administer a questionnaire by collecting questions from other users, by attaching one or more questionnaires to an RFQ at the header level, or by requiring vendors to complete the questionnaire as part of the reply.</p></li>
<li><p>After you issue an RFQ, you can make changes or updates. You can also add attachments, provided that no replies have been registered. You can communicate these changes through the Vendor portal to keep prospective bidders aware of updates.</p></li>
<li><p>You can hold a requisition from further processing and indicate the reason for the hold, so that you can better manage requisitions and communicate status.</p></li>
<li><p>You can specify that bids are sealed until the solicitation closing date. These bids are hidden until bid tabulation starts.</p></li>
<li><p>You can publish your RFQ to the public Vendor portal, so that unregistered vendors can see it. All lines on the RFQ are also sent to the vendors that are selected in the RFQ.</p></li>
</ul>
<p>The following features are new for Enterprise Portal for Microsoft Dynamics AX.</p>
<ul>
<li><p>If the requester allows this, all vendors can submit an alternate item on an RFQ and provide a reason for the alternate.</p></li>
<li><p>All vendors can enter a charge on the RFQ reply line, in addition to the quantity and unit price.</p></li>
<li><p>Customers can now include a questionnaire with the RFQ and require that you fill out the questionnaire as part of your bid.</p></li>
<li><p>Customers can change the content of an RFQ after they send it. You can view the changes, and any attachments, on the <strong>Amendments</strong> FastTab in the RFQ.</p></li>
<li><p>Public sector vendors that are not yet registered on the Vendor portal can access a public, non–claims-aware site as a &quot;guest,&quot; so that they can view publicly available documents, such as lists of open RFQs and purchase orders.</p>
<div class="alert">

> [!NOTE]
> <P>This control is available only if the <STRONG>Public Sector</STRONG> configuration key is selected.</P>


</div></li>
<li><p>Public sector vendors can view all open and closed purchase orders, RFQs, and their details. These details include scoring and award notes on accepted bids.</p>
<div class="alert">

> [!NOTE]
> <P>This control is available only if the <STRONG>Public Sector</STRONG> configuration key is selected.</P>


</div></li>
<li><p>Public sector vendors can request to reply to RFQs that have been published to the <strong>Open requests for quotations</strong> list page, even if they have not been included as a vendor in the RFQ.</p>
<div class="alert">

> [!NOTE]
> <P>This control is available only if the <STRONG>Public Sector</STRONG> configuration key is selected.</P>


</div></li>
</ul>
<p>For more information, see <a href="what-s-new-procurement-and-sourcing-features.md">What's new: Procurement and sourcing features</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Production control</p></td>
<td><p>A new option for automating material reservations has been added to the <strong>Reservation</strong> field in the <strong>Production orders</strong> form, where the value is set for a specific production order. A new option has also been added to the <strong>Production control parameters</strong> form, where the default value is specified.</p>
<p>In the <strong>Reservation</strong> field, if you select <strong>Release</strong>, all materials are reserved when the production order is released.</p>
<p>For more information, see <a href="what-s-new-production-control-features.md">What's new: Production control features</a>.</p></td>
</tr>
<tr class="even">
<td><p>Project management and accounting</p></td>
<td><ul>
<li><p>You can create an on-account billing rule type that is based on the milestones that you specify in the billing rule.</p></li>
<li><p>You can create fee transactions and modify the sales price of lines in an invoice proposal.</p></li>
</ul>
<p>For more information, see <a href="what-s-new-project-management-and-accounting-features.md">What's new: Project management and accounting features</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Public Sector</p></td>
<td><ul>
<li><p>You can publish a request for quotation (RFQ) to the public Vendor portal, so that unregistered vendors can view it.</p></li>
<li><p>Public sector vendors can view all open and closed purchase orders, RFQs, and their details.</p></li>
</ul>
<p>For more information, see <a href="what-s-new-public-sector-features.md">What's new: Public sector features</a>.</p></td>
</tr>
<tr class="even">
<td><p>Retail</p></td>
<td><ul>
<li><p>The call center is a new channel type that you can set up in the <strong>Retail</strong> module.</p></li>
<li><p>The <strong>Catalogs</strong> form contains functionality that is available to users who are associated with a call center.</p></li>
<li><p>Enhanced usability of info codes by using info code groups is added.</p></li>
<li><p>Enhanced functionality for printing product labels and shelf labels is available.</p></li>
<li><p>Gift card enhancements are added.</p></li>
<li><p>You can group and package individual products in one sellable unit or product kit.</p></li>
<li><p>Cashiers can disassemble or reconfigure kits at the point of sale.</p></li>
<li><p>Cashiers can sell, return, or exchange kit products at the point of sale.</p></li>
<li><p>The Retail loyalty program has been completely redesigned.</p></li>
<li><p>Cashiers can issue loyalty cards at the point of sale.</p></li>
<li><p>Enhancements for maintaining channel product attributes are added.</p></li>
<li><p>You can set up filters to improve searches for retail channel products.</p></li>
<li><p>IT staff can configure screen layouts for Modern POS.</p></li>
<li><p>Customer accounts can be accessed by retail channels across all locations.</p></li>
<li><p>You can set up affiliations and their discounts.</p></li>
<li><p>You can set up threshold discounts.</p></li>
<li><p>You can specify category-based pricing to more easily manage pricing for many products at the same time.</p></li>
<li><p>You can use price groups to more easily create and manage prices and discounts for retail products.</p></li>
<li><p>You can view detailed information about discount transactions.</p></li>
<li><p>Enhancements to buyer’s push are added.</p></li>
<li><p>Enhancements to cross-docking are added.</p></li>
<li><p>In Retail essentials, you can schedule the periodic export of accounting information, so that this information can be used by a third-party accounting program.</p></li>
<li><p>You can specify that returned products are assigned to different return locations in inventory, depending on the cashier’s response to info codes that are displayed at the point of sale.</p></li>
<li><p>You can determine and plan a top-down trade fund.</p></li>
<li><p>You can set up vendor rebates.</p></li>
<li><p>You can manage your trade fund budgets so that they include specific merchandise, promotion dates, and monetary values.</p></li>
<li><p>You can set up rebates that include deductions.</p></li>
<li><p>By using royalty payment management, you can create an agreement between a licensee and a licensor. You can then manage payments between the two parties.</p></li>
</ul>
<p>For more information, see <a href="what-s-new-retail-features.md">What's new: Retail features</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Sales and marketing</p></td>
<td><p>You can now also register serial numbers during the sales process when you prepare the packing slip or the invoice for a sales order.</p>
<p>You can register serial numbers on the packing slip or invoice either by entering them manually or by using a scanner.</p>
<p>The following list illustrates some of the scenarios that this feature is intended for:</p>
<ul>
<li><p>Registering serial numbers for items on sales orders on the packing slip or invoice.</p></li>
<li><p>Customer pickup of sales orders with serialized items.</p></li>
<li><p>Partial delivery and invoicing of sales orders with serialized items.</p></li>
<li><p>Correcting packing slips and invoices with serialized items.</p></li>
<li><p>Returning serialized items.</p></li>
<li><p>Tracing the history of orders that include serialized items.</p></li>
</ul>
<p>For more information, see <a href="what-s-new-sales-and-marketing-features.md">What's new: Sales and marketing features</a>.</p></td>
</tr>
<tr class="even">
<td><p>Trade allowance management</p></td>
<td><ul>
<li><p>You can define merchandising events, assign a trade allowance to them, and manage customers, invoices, or vendors that are related to the agreement.</p></li>
<li><p>You can manage your trade fund budgets so that they include specific merchandise, promotion dates, and monetary values.</p></li>
<li><p>You can process customer payments that include deductions.</p></li>
<li><p>By using royalty payment management, you can create an agreement between a licensee and a licensor. You can then manage payments between the two parties.</p></li>
</ul>
<p>For more information, see <a href="what-s-new-trade-allowance-management-features.md">What's new: Trade allowance management features</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Transportation management</p></td>
<td><ul>
<li><p>You can plan transportation for inbound and outbound shipments, manage routes, and consolidate shipments.</p></li>
<li><p>You can configure rating structures and shop for rates, based on charges such as fuel and customs duties.</p></li>
<li><p>You can view driver check-in and check-out history and driver logs.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Warehouse management</p></td>
<td><ul>
<li><p>You can configure inbound and outbound intelligent workflows.</p></li>
<li><p>You can assign orders to clusters to pick from a single location, and configure profiles to control the validation and packing of items into shipping containers. You can also alternate between picking strategies for batch and non-batch items.</p></li>
<li><p>You can create, implement, and release work by using batch-scheduled or manual processing of waves.</p></li>
<li><p>You can set up cycle counting thresholds, and create ad-hoc cycle counting plans, schedule plans, and cycle count locations and items.</p></li>
<li><p>You can set up container groups to order the sequence of the packing process and create templates to support packing strategies.</p></li>
<li><p>You can use scanners or other mobile devices to optimize precision in the picking and put-away processes.</p></li>
</ul>
<p>For more information, see <a href="what-s-new-warehouse-management-features.md">What's new: Warehouse management features</a>.</p></td>
</tr>
</tbody>
</table>


## Other features

Other features were added or changed in AX 2012 R3.

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
<td><p>Microsoft Azure deployments</p></td>
<td><p>In Microsoft Dynamics Lifecycle Services, Cloud hosted environments is a new tool that you can use to deploy Microsoft Dynamics AX 2012 R3 environments on Microsoft Azure.</p>
<p>When you use the Cloud hosted environments tool, you’ll need to select the type of Microsoft Dynamics AX environment that you want to deploy, such as a demo, developer/test, or production environment. Based on your selection, the Cloud hosted environments tool provisions the appropriate number of virtual machines in Azure. These virtual machines have Microsoft Dynamics AX components (and all of their prerequisites) already installed on them.</p>
<p>For detailed instructions about how to deploy Microsoft Dynamics AX environments on Azure, see <a href="deploy-microsoft-dynamics-ax-2012-r3-on-azure-using-lifecycle-services.md">Deploy Microsoft Dynamics AX 2012 R3 on Azure using Lifecycle Services</a>.</p></td>
</tr>
<tr class="even">
<td><p>Analysis cubes</p></td>
<td><p>Microsoft Dynamics AX provides cubes that you can use to analyze your business data. Three new cubes have been added in this release:</p>
<ul>
<li><p>Demand forecast cube</p></li>
<li><p>Demand forecast accuracy cube</p></li>
<li><p>Trade allowance management cube</p></li>
</ul>
<p>For more information, see <a href="what-s-new-analytics.md">What's new: Analytics</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Store more than 16 dimensions in the InventDim table and its DimIdx index.</p></td>
<td><p>The InventDim table stores information about inventory dimensions. Before Microsoft Dynamics AX 2012 R2, the table could store a maximum of 16 dimensions.</p>
<p>A new hash field has been added to the InventDim table and to its DimIdx index. By following the steps of a simple workaround, you can now store unique combinations that involve more than 16 dimensions in the InventDim table and its DimIdx index.</p>
<p>For more information, see <a href="https://technet.microsoft.com/library/dn495386(v=ax.60)">Walkthrough: More than 14 InventDim Dimensions Despite Index Limit</a>.</p></td>
</tr>
<tr class="even">
<td><p>Update installer</p></td>
<td><p>Updates for AX 2012 R3: The Updates page on Lifecycle Services hosts the update installer for AX 2012 R3 that is used for cumulative updates or the group of most recent updates. It also provides access to groups of updates that can be used for slipstream installations. For more information, see <a href="updates-for-microsoft-dynamics-ax-2012-r3-lifecycle-services-lcs.md">Updates for Microsoft Dynamics AX 2012 R3 (Lifecycle Services, LCS)</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Cloud powered support</p></td>
<td><p>Cloud powered support is a part of Lifecycle Services that enables customers to manage support incidents for all versions of Microsoft Dynamics AX 2012. It enables you to create a virtual machine in Azure that has the same hotfixes installed as your local environment, reproduce and record the incident on the virtual machine and then submit it to our support team. Support follows up by investigating, and if possible, testing a fix on the virtual machine, and sending it back to you to verify. For more information, see <a href="cloud-powered-support-lifecycle-services-lcs.md">Cloud powered support (Lifecycle Services, LCS)</a>.</p></td>
</tr>
</tbody>
</table>


## Country/region-specific new features

In AX 2012 R3, we added and changed several country/region-specific features.

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
<td><ul>
<li><p>Generate electronic payment files for Single Euro Payments Area (SEPA) credit transfers in the PAIN.001.001.03 XML file format.</p></li>
<li><p>Generate electronic payment files for SEPA direct debits in the PAIN.008.001.02 XML file format.</p></li>
</ul>
<p>For more information, see <a href="what-s-new-country-specific-features-for-austria-aut.md">What's new: Country/region-specific features for Austria (AUT)</a>.</p></td>
</tr>
<tr class="even">
<td><p>Brazil</p></td>
<td><ul>
<li><p>Prepare and generate a text file in the format layout that is required by the Validador SINTEGRA application, and import the text file that is generated in Fiscal Books into the Validador SINTEGRA application. You can automatically generate tax assessment files for GIA-SP, GIA-ST, and SINTEGRA.</p></li>
<li><p>Create the ISS tax assessment per fiscal establishment.</p></li>
<li><p>Register the ICMS tax order payment (GARE) for a specific fiscal establishment with all required information, create a payment that is based on this information, and inquire into tax order payments and their status.</p></li>
<li><p>Create SPED accounting statements for fiscal books.</p></li>
<li><p>Generate and import the text file for SPED EFD Contributions.</p></li>
<li><p>Post negative debit amounts as credits, and negative credit amounts as debits.</p></li>
</ul>
<p>For more information, see <a href="what-s-new-country-specific-features-for-brazil-bra.md">What's new: Country/region-specific features for Brazil (BRA)</a>.</p></td>
</tr>
<tr class="odd">
<td><p>France</p></td>
<td><p>Use a predefined query and predefined methods to export financial data.</p>
<p>For more information, see <a href="what-s-new-country-specific-features-for-france-fra.md">What's new: Country/region-specific features for France (FRA)</a>.</p></td>
</tr>
<tr class="even">
<td><p>Germany</p></td>
<td><ul>
<li><p>Generate electronic payment files for Single Euro Payments Area (SEPA) credit transfers in the PAIN.001.003.03 XML file format.</p></li>
<li><p>Generate electronic payment files for SEPA direct debits in the PAIN.008.003.02 XML file format.</p></li>
</ul>
<p>For more information, see <a href="what-s-new-country-specific-features-for-germany-deu.md">What's new: Country/region-specific features for Germany (DEU)</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Japan</p></td>
<td><ul>
<li><p>Assemble or disassemble fixed assets by using on-hand inventory items.</p></li>
<li><p>Generate fixed asset reports for deferred, low-value, and lump-sum fixed assets.</p></li>
<li><p>Categorize and depreciate deferred, low-value, or lump-sum fixed assets.</p></li>
</ul>
<p>For more information, see <a href="what-s-new-country-specific-features-for-japan-jpn.md">What's new: Country/region-specific features for Japan (JPN)</a>.</p></td>
</tr>
<tr class="even">
<td><p>Mexico</p></td>
<td><p>Post negative debit amounts as credits, and negative credit amounts as debits.</p>
<p>For more information, see <a href="what-s-new-country-specific-features-for-mexico-mex.md">What's new: Country/region-specific features for Mexico (MEX)</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Russia</p></td>
<td><ul>
<li><p>Process gift card operations as prepayments.</p></li>
<li><p>Enhancements are added to refund payment method control in Retail POS.</p></li>
<li><p>Process return transactions during a different shift.</p></li>
<li><p>Redeem loyalty points as discounts for sales transactions, and refund loyalty points for return transactions at the point of sale.</p></li>
<li><p>Enhancements are added to payroll processes and payroll journals.</p></li>
</ul>
<p>For more information, see <a href="what-s-new-country-specific-features-for-russia-rus.md">What's new: Country/region-specific features for Russia (RUS)</a>.</p></td>
</tr>
<tr class="even">
<td><p>United Kingdom</p></td>
<td><p>Withholding tax is calculated during the settlement of vendor invoices that are posted by using purchase orders, an invoice journal, or an invoice register.</p>
<p>For more information, see <a href="calculate-and-post-withholding-tax.md">Calculate and post withholding tax</a>.</p></td>
</tr>
</tbody>
</table>

  


