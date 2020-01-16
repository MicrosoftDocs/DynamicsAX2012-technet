---
title: "What's new: Procurement and sourcing features"
TOCTitle: Procurement and sourcing features
ms:assetid: 7c8d311d-a6af-47c8-8012-fc5a9d5136dd
ms:mtpsurl: https://technet.microsoft.com/library/Dn527153(v=AX.60)
ms:contentKeyID: 59623282
author: Khairunj
ms.date: 06/08/2015
mtps_version: v=AX.60
f1_keywords:
- procurement
- sourcing
---

# What's new: Procurement and sourcing features 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

We have changed and added functionality in the [Procurement and sourcing](procurement-and-sourcing.md) area for Microsoft Dynamics AX 2012. For more information, see the tables that apply to your version of the product.

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
<td><p>Evaluate vendors based on their ability to provide products and services.</p></td>
<td><p>You can rate vendors based on criteria that you define for each category of item or service that the vendors provide. You can evaluate a vendor for each transaction that you have with the vendor.</p>
<p>For more information, see <a href="set-up-vendor-evaluation-criteria.md">Set up vendor evaluation criteria</a>.</p></td>
</tr>
<tr class="even">
<td><p>Support for multiple languages for procurement catalogs.</p></td>
<td><p>You can create one procurement catalog that can be viewed in multiple languages, based on the setting for the user profile language and locale in Microsoft Dynamics AX. Purchasing managers can define the translated text that appears on the procurement site.</p>
<p>For more information, see <a href="procurement-catalogs-overview.md">Procurement catalogs overview</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Rate and provide feedback about products and vendors on the procurement site.</p></td>
<td><p>Workers can rate products that they have ordered and vendors with whom they have done business, and can provide feedback about their experiences. The feedback is compiled and displayed on the procurement site, so that all users can make informed decisions when they order products or do business with a particular vendor. Purchasing managers can control whether ratings and comments are allowed on the procurement site, and whether all comments must be reviewed before they appear on the procurement site.</p>
<p>For more information, see <a href="rate-products-and-vendors.md">Rate products and vendors</a>.</p></td>
</tr>
<tr class="even">
<td><p>New <strong>Employee service</strong> page.</p></td>
<td><p>The Employee services site in Enterprise Portal for Microsoft Dynamics AX has been updated to improve usability. You can now view all available tasks in one place. Related tasks are grouped under a task heading, and when you click the heading for a task group, a new activity site or list page opens, where you can quickly and easily complete tasks.</p>
<p>For more information, see <a href="using-the-employee-services-site.md">Using the Employee Services site</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Import commodity codes and minimum or maximum order quantities into vendor catalogs.</p></td>
<td><p>Vendors can generate catalogs that include standard commodity codes, and those codes can be automatically mapped to procurement categories in Microsoft Dynamics AX. Vendors must comply with the Microsoft Dynamics AX customer’s unit of measure for quantities. Vendors can specify minimum, maximum, and standard order quantities for products in the vendor catalog. Vendors can also specify the lead time, which is the number of days that a vendor requires between the order date and the shipment date.</p>
<p>For more information, see <a href="https://technet.microsoft.com/library/hh242810(v=ax.60)">Import categories (form)</a>.</p></td>
</tr>
<tr class="even">
<td><p>Enhancements to the catalog import schema.</p></td>
<td><p>The catalog import schema has been updated so that vendors can more easily modify an existing catalog or overwrite an existing catalog with a new catalog. When a vendor uploads a new catalog to replace an existing catalog, the matching items and services are replaced with the new data. Any new items and services that are not in the existing catalog are added, and any items and services in the existing catalog that do not match the items and services in the new catalog are deleted. When the vendor modifies selected items in an existing catalog, only the modifications that are included in the catalog schema are applied to the existing catalog products. Any new items and services that are not in the existing catalog, but that are included in the modified catalog file, are added.</p>
<p>For more information, see <a href="upload-a-catalog-maintenance-request.md">Upload a catalog maintenance request</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Consolidate the navigation categories on the procurement site.</p></td>
<td><p>When you set up a catalog, you define the catalog navigation hierarchy that appears on the procurement site. The catalog navigation hierarchy can contain multiple levels of detail for each procurement category. You can define the level of detail for the catalog navigation categories that you display on your procurement site. By consolidating the category levels, you can limit the levels of detail that workers have to sort through to find the product that they want to order.</p>
<p>For more information, see <a href="key-tasks-create-procurement-catalogs.md">Key tasks: Create procurement catalogs</a>.</p></td>
</tr>
<tr class="even">
<td><p>Enhancements to the navigation and usability of the procurement site.</p></td>
<td><p>The following changes have been made to improve usability on the Order products site:</p>
<ul>
<li><p>Navigation is simplified, so that you can search for products by category, item, vendor, and vendor catalog. The filters have been moved to the top of the webpage.</p></li>
<li><p>Visibility into the status of orders that have been entered is improved. A single list displays all orders that were entered and the status of each order, from the creation and approval of the purchase requisition to the generation and fulfillment of a purchase order. You can also view the details for a selected order.</p></li>
<li><p>You can now add selected products to the shopping cart directly from the product list page. The product details page is displayed only if order details for the product must be entered.</p></li>
<li><p>You can now configure the data that is displayed for each procurement category. For example, if you only order office supplies directly from a vendor, you can configure the category to display only links to vendor catalogs.</p></li>
<li><p>The visibility for ordering from a vendor is improved.</p></li>
<li><p>The usability of the shopping cart is improved. For example, you can now select all items in the cart for checkout.</p></li>
<li><p>Fewer steps are required when you use the Checkout Wizard to create a purchase requisition.</p></li>
<li><p>Additional details about existing purchase requisitions are added, so that it is easier to add items from a shopping cart to an existing purchase requisition during checkout.</p></li>
<li><p>Purchase requisitions are accessible from the Employee services site.</p></li>
</ul>
<p>For more information, see <a href="using-the-procurement-site.md">Using the Procurement site</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Enhancements to Role Centers for purchasing professionals in Enterprise Portal.</p></td>
<td><p>New Web Part reports can be added to the Role Centers for the purchasing agent and purchasing manager. The Web Part data includes metrics and reporting that provide visibility into vendor and procurement spending. The Web Part data also includes additional cues for purchasing professionals, and an expanded work list that shows alerts or workflow notifications. You can click a report to view the details for the reported data.</p></td>
</tr>
<tr class="even">
<td><p>Policy framework.</p></td>
<td><p>You can create rules and apply them to different parts of the enterprise. These rules help the organization enforce standard internal business controls for processes such as requisitions, submission of corporate expenses, and enforcement of corporate audits. For more information about the policy framework, see the white paper <a href="http://go.microsoft.com/fwlink/?linkid=213137%26clcid=0x409">Using the Policy Framework in Microsoft Dynamics AX 2012</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Set up spending limits and approval limits.</p></td>
<td><p>You can define spending and approval limits and then apply them based on your organization’s requirements. You can also define and apply default limits that are based on job or compensation level. For example, two legal entities can have different limits for employees who have the job of purchasing manager.</p>
<p>For more information, see <a href="about-signing-limits.md">About signing limits</a>.</p></td>
</tr>
<tr class="even">
<td><p>Manage internal catalogs.</p></td>
<td><p>You can set up and maintain catalogs for ordering the items or services that employees require to perform their daily activities. You can set up the catalog’s navigation structure, import catalog data from vendors, associate products with catalog categories, and design the welcome message that is displayed on the procurement site for the catalog. After a catalog is set up, you can publish the catalog to make it available to your employees.</p>
<p>For more information, see <a href="procurement-catalogs-overview.md">Procurement catalogs overview</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Add items and services to a shopping cart.</p></td>
<td><p>When you select items or services from a procurement catalog or a vendor catalog, you can add those items to a shopping cart. You can view the items in your shopping cart at any time, delete items that you no longer want, modify any configurable product attributes, or modify the quantity of the items that you want to purchase. When you are ready to check out, you can create a purchase requisition directly from the shopping cart and submit it for processing. You can then return to the procurement order site to continue searching for items or services, or you can exit the procurement order site when you have finished.</p>
<p>For more information, see <a href="add-items-to-the-shopping-cart.md">Add items to the shopping cart</a>.</p></td>
</tr>
<tr class="even">
<td><p>Manage catalogs that are hosted externally.</p></td>
<td><p>Catalog managers can now set up a direct link to an external vendor catalog that is hosted on the vendor’s website. The vendor manages the product data and metadata. Users are directed to the vendor’s website to select products, and then, based on the configurations that are defined by the purchasing manager or purchasing agent, users can either check out directly from the vendor’s website or return to the Microsoft Dynamics AX procurement order site to check out.</p>
<p>For more information, see <a href="external-vendor-catalogs-overview.md">External vendor catalogs overview</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Search for items or services in a procurement catalog.</p></td>
<td><p>Use the search functionality on the procurement site to search for items or services by category, or by using keywords. You can search both procurement catalogs and vendor catalogs, and filter the search results to quickly find the exact item or service that you are looking for.</p>
<p>For more information, see <a href="about-ordering-products.md">About ordering products</a>.</p></td>
</tr>
<tr class="even">
<td><p>Import catalog data.</p></td>
<td><p>Purchasing managers or purchasing agents can import catalog data from vendors by using a delivered XML schema. Purchasing managers or purchasing agents can then review and modify product data before they pass that data to the procurement order site.</p>
<p>For more information, see <a href="import-a-catalog-from-a-vendor.md">Import a catalog from a vendor</a>. Additionally, the Supply Chain Management in Dynamics AX team blog has a three-part blog series that walks you through the process for importing catalogs:</p>
<ul>
<li><p><a href="http://blogs.msdn.com/b/dynamicsaxscm/archive/2012/08/29/import-vendor-catalogs-from-setup-to-importing-a-sample-catalog-part-1-setup.aspx">Import vendor catalogs: from setup to importing a sample catalog – Part 1 (Setup)</a></p></li>
<li><p><a href="http://blogs.msdn.com/b/dynamicsaxscm/archive/2012/09/09/import-vendor-catalogs-from-setup-to-importing-a-sample-catalog-part-2-importing-a-sample-catalog.aspx">Import vendor catalogs: from setup to importing a sample catalog – Part 2 (Importing a sample catalog)</a></p></li>
<li><p><a href="http://blogs.msdn.com/b/dynamicsaxscm/archive/2013/03/07/import-vendor-catalogs-part-3-troubleshooting.aspx">Import Vendor Catalogs – Part 3 (Troubleshooting)</a></p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Set up a procurement site.</p></td>
<td><p>You can set up a procurement site that employees can use to order items and services that they require for daily work activities. You can create a procurement catalog, post the catalog to the procurement site in Enterprise Portal, and create a welcome message that employees see when they first open the site. User access to the procurement catalog is through the Employee Services site, and access can be controlled by using purchasing policies.</p>
<p>For more information, see <a href="key-tasks-create-procurement-catalogs.md">Key tasks: Create procurement catalogs</a>.</p></td>
</tr>
<tr class="even">
<td><p>Processing of imported catalog data</p></td>
<td><p>You can use the catalog import feature to import catalog maintenance request (CMR) files that are received from your vendors, and that contain the products, product images, and services that you offer to your employees for purchase. From Microsoft Dynamics AX, purchasing managers can review, approve, or reject any or all of the products or product change requests that are contained in the file.</p>
<p>Any products that are approved are automatically uploaded to the product master in Microsoft Dynamics AX and can be displayed in the procurement catalog.</p>
<p>For more information, see <a href="import-a-catalog-from-a-vendor.md">Import a catalog from a vendor</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Create purchasing policy rules to control spending in your organization.</p></td>
<td><p>You can define complex purchasing rules and apply those rules to your organizational entities in various ways to control the spending behavior of your organizations. These rules help guarantee that your employees buy from the correct purchasing catalogs and the appropriate preferred vendors, and that they spend within the prescribed limits for their organizations.</p>
<p>For more information, see <a href="about-purchasing-policies.md">About purchasing policies</a>.</p></td>
</tr>
<tr class="even">
<td><p>Import vendor catalogs.</p></td>
<td><p>Authorized vendors can use the vendor self-service portal to upload their most recent catalog by using a delivered XML catalog template. Vendors can also view the status of the import process. This feature provides tools and support processes, so that vendors can manage catalog integration tasks by using web services and the vendor self-service portal.</p>
<p>For more information, see <a href="set-up-and-maintain-your-product-catalogs.md">Set up and maintain your product catalogs</a>.</p></td>
</tr>
<tr class="odd">
<td><p>View the details for a procurement category.</p></td>
<td><p>You can view preferred vendors, links, and other information about a procurement category. The category manager can add customized text and links to intranet and extranet sites.</p>
<p>For more information, see <a href="key-tasks-create-procurement-catalogs.md">Key tasks: Create procurement catalogs</a>.</p></td>
</tr>
<tr class="even">
<td><p>Define category hierarchies.</p></td>
<td><p>You can define various category hierarchies that are independent of, but still related to, commodity codes or catalog and item hierarchies. The following list describes some of the ways that you can manage categories on a day-to-day basis:</p>
<ul>
<li><p>Add attributes, such as a category that is used on a global or local level.</p></li>
<li><p>Define approval processes for new and existing categories.</p></li>
<li><p>Define categories on a global level.</p></li>
<li><p>Define permissions for category users to make changes.</p></li>
</ul>
<p>For more information, see <a href="about-category-hierarchies.md">About category hierarchies</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Enhancements to the methods for creating purchase requisitions</p></td>
<td><p>You can import purchase requisitions that are created in a third-party application into Microsoft Dynamics AX by using web services and an XML schema. This feature validates the purchase requisition data that is received from the third-party application and then sends a status back to the external source application. Additional processing of the purchase requisition in Microsoft Dynamics AX follows the existing application pattern.</p>
<p>The copy functionality has also been enhanced so that you can copy data from purchase requisition headers and lines to create a new purchase requisition in the same organization and legal entity. The copy functionality in Enterprise Portal has been expanded so that you can copy requisition lines from an existing purchase requisition that is in the same legal entity or organization.</p>
<p>For more information, see <a href="about-purchase-requisitions.md">About purchase requisitions</a>.</p></td>
</tr>
<tr class="even">
<td><p>History of tracked changes for purchase requisitions</p></td>
<td><p>Any changes that are made to a purchase requisition from its creation to its completion are tracked as versions, and these versions can be compared as the purchase requisition moves through the review process. The whole purchase requisition is copied to the history record when the purchase requisition is first submitted for review. Any changes that are made during the review process are also saved to the history record for the data row that is affected by the change.</p>
<p>For more information, see <a href="view-the-history-for-a-purchase-requisition.md">View the history for a purchase requisition</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Identify fixed assets based on monetary thresholds.</p></td>
<td><p>You can define organization-wide business rules, which can be overridden at the legal entity level to identify fixed assets.</p>
<p>For more information, see <a href="about-fixed-asset-determination-rules.md">About fixed asset determination rules</a>.</p></td>
</tr>
<tr class="even">
<td><p>Configure rules for creating purchase orders for purchase requisitions.</p></td>
<td><p>You can define the following configuration options for creating purchase orders:</p>
<ul>
<li><p>Determine how requisition lines are combined into purchase orders.</p></li>
<li><p>Determine which purchase requisition lines are held so that manual purchase orders can be created, and which lines are automatically converted into purchase orders.</p></li>
<li><p>Determine which purchase requisitions are eligible for requisition consolidation.</p></li>
<li><p>Determine the price increase tolerance for purchase requisition lines from approval to purchase order creation.</p></li>
</ul>
<p>For more information, see <a href="defining-and-maintaining-rules-for-purchasing.md">Defining and maintaining rules for purchasing</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Purchase requisition enhancements</p></td>
<td><p>Enhancements to the purchase requisition process and the <strong>Purchase requisition</strong> form include the following changes:</p>
<ul>
<li><p>Purchase requisition lines for different requesters, legal entities, and operating units can be created in one purchase requisition.</p></li>
<li><p>Purchase requisitions can be created by and for contract workers.</p></li>
<li><p>Permissions can be configured so that a requester can enter requests on behalf of someone else across legal entities.</p></li>
<li><p>Purchase requisitions can be created for requesters who are not Microsoft Dynamics AX users.</p></li>
<li><p>Data from requisition headers and lines can be copied into a new requisition that is created in the same organization and legal entity, both in Microsoft Dynamics AX and in Enterprise Portal.</p></li>
<li><p>Purchase requisitions can be created for items that are not found in a catalog. A false item does not have to be created in the item master.</p></li>
<li><p>Statutory and operational purchasing policies have been applied to the purchase requisition process.</p></li>
<li><p>Optional fields have been added to capture information if the requester negotiated a prepayment with a vendor.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Enhancements to the <strong>Purchase requisitions</strong> form</p></td>
<td><p>The <strong>Purchase requisitions</strong> form has been modified to provide an intuitive user experience for both the novice or casual requester and the power user. Therefore, the requisitioning process is both efficient and effective.</p>
<p>The <strong>Purchase requisitions</strong> form is now dynamic and includes only the fields that are important in the context of the purchase request.</p>
<p>For more information, see <a href="https://technet.microsoft.com/library/hh209453(v=ax.60)">Purchase requisitions (form)</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Manage categories on a daily basis.</p></td>
<td><p>View details about a category hierarchy and commodity codes on a new report.</p>
<p>For more information, see <a href="commodity-codes-by-category-report-proccategorycommoditycode.md">Commodity codes by category report (ProcCategoryCommodityCode)</a>.</p></td>
</tr>
<tr class="even">
<td><p>Commodity codes for classifying and mapping entities</p></td>
<td><p>You can create and support multiple global and proprietary classification systems of commodity codes. You can then use the commodity codes to classify items, services, and vendors, and to map items to product categories.</p>
<p>For more information, see <a href="about-category-hierarchies.md">About category hierarchies</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Create a purchase requisition directly from your procurement order site or by using a requisition wizard.</p></td>
<td><p>When you order items or services for indirect procurement, and you add those items or services to a shopping cart, you can now automatically create a purchase requisition during the checkout process.</p>
<p>You have two options when you create a purchase requisition. You can either add items directly to a purchase requisition from the shopping cart or use a wizard that guides you through the process for creating a requisition. You can select one of these options from your shopping cart at the time of checkout.</p>
<p>For more information, see <a href="key-tasks-order-items-and-services-from-a-catalog.md">Key tasks: Order items and services from a catalog</a></p></td>
</tr>
<tr class="even">
<td><p>Consolidate requisitions to minimize procurement costs.</p></td>
<td><p>The purchasing manager or purchasing agent can now consolidate requisition line items. Users who have these roles can identify which approved purchase requisitions must be processed manually, and whether those purchase requisitions are eligible for demand consolidation. Purchase requisition lines that are eligible for demand consolidation can be grouped, and the vendor, price, requested date, or quotation data can be modified to achieve the best pricing.</p>
<p>For more information, see <a href="key-tasks-consolidate-purchase-requisitions.md">Key tasks: Consolidate purchase requisitions</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Enhancements to the review process for purchase requisitions.</p></td>
<td><p>The overall process for reviewing purchase requisitions has been improved. When a purchase requisition is submitted for review, the individual purchase requisition lines can now be routed to the appropriate reviewers independently of one another. Therefore, reviewers can take action only on purchase requests that are in their area of responsibility. Therefore, this feature reduces the processing time for purchase requisitions that have multiple line items.</p>
<p>Reviewers can be identified based on the individual purchase line requests, distribution data, or even the budgets that the expenditure is eventually charged to.</p>
<p>You can define a workflow for purchase requisition review that routes whole purchase requisitions or individual lines. Project-related purchase requests can use the same review workflow for processing.</p>
<p>For more information, see <a href="overview-of-a-purchase-requisition-workflow.md">Overview of a purchase requisition workflow</a>.</p></td>
</tr>
<tr class="even">
<td><p>Business rules for fixed assets that are based on monetary thresholds.</p></td>
<td><p>You can now define business rules at the global level and then override the rules at the local level to determine fixed assets.</p>
<p>For more information, see <a href="key-tasks-set-up-business-rules-for-fixed-asset-determination.md">Key tasks: Set up business rules for fixed asset determination</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Perform a check of the budget for purchase requisitions.</p></td>
<td><p>You can require a check of the budget balance for purchase requisitions.</p>
<p>For more information, see <a href="set-up-budget-control.md">Set up budget control</a> and <a href="create-and-maintain-purchase-requisitions.md">Create and maintain purchase requisitions</a>.</p></td>
</tr>
<tr class="even">
<td><p>Record transaction dates on purchase requisitions.</p></td>
<td><p>Purchase requisition headers and lines now contain a field for the transaction date. The transaction date is used to determine the fiscal period for budget control and for posting purchase requisitions.</p></td>
</tr>
<tr class="odd">
<td><p>Archive closed purchase requisitions by using the Intelligent Data Management Framework for Microsoft Dynamics AX (IDMF).</p></td>
<td><p>You can no longer delete approved purchase requisitions that you do not have to store in your production system. This is because of the budget control and pre-encumbrances on purchase requisitions that are introduced in this version. To archive or purge the records for approved purchase requisitions, you must use the IDMF.</p>
<p>For more information, see <a href="overview-of-the-microsoft-dynamics-ax-intelligent-data-management-framework-idmf.md">Overview of the Microsoft Dynamics AX Intelligent Data Management Framework (IDMF)</a>.</p></td>
</tr>
<tr class="even">
<td><p>Search for vendors across your organization.</p></td>
<td><p>You can search for active vendors, prospective vendors, and unsolicited vendors. If a vendor is not yet approved by your organization, you can create a request to consider the vendor for approval.</p>
<p>For more information, see <a href="key-tasks-work-with-vendor-search-and-search-results.md">Key tasks: Work with vendor search and search results</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Work item queues for processing transaction documents.</p></td>
<td><p>If you use either internal teams or external partner organizations to process business transaction documents, such as purchase requisitions, purchase orders, or new vendor justifications, you might need to set up work item queues so that these teams can manage the flow of the transactions as those transaction come in from your company and are processed by the appropriate organization. The work item queue provides the infrastructure that is required for the following functionality:</p>
<ul>
<li><p>Users who belong to a queue can claim work items that are not assigned to anyone else and can perform the workflow actions that are configured on the work items in the queue.</p></li>
<li><p>Users can reassign work items from one work item queue to another work item queue in the same work item queue group.</p></li>
<li><p>Queue owners can reassign work items from one queue user to another in the same work item queue group.</p></li>
</ul>
<p>For more information, see <a href="configure-work-item-queues.md">Configure work item queues</a>.</p></td>
</tr>
<tr class="even">
<td><p>Enhancements to support vendors.</p></td>
<td><p>Enhancements have been made to the vendor profile. These enhancements include the following changes:</p>
<ul>
<li><p>You can define the industries that a vendor operates in.</p></li>
<li><p>You can define diversity criteria for the owner of the vendor company. For example, you can specify that the owner must be a service veteran.</p></li>
</ul>
<p>You can define the procurement categories that the vendor provides items and services in. By categorizing vendors, you help with spending analysis. These categories also improve strategic sourcing and help provide critical data, such as the following information:</p>
<ul>
<li><p>The number of suppliers by category</p></li>
<li><p>The total value of spending per year by category</p></li>
<li><p>The top 10 suppliers by value per category</p></li>
<li><p>The number of vendors that are minority-owned businesses</p></li>
<li><p>The number of vendors that are female-owned businesses</p></li>
</ul>
<p>For more information, see <a href="procurement-and-sourcing-reports.md">Procurement and sourcing reports</a>.</p>
<div class="alert">

> [!NOTE]
> <P>All reports for spend analytics contain the word ”Spend” in the internal report name. For example, the <STRONG>Spend by procurement category and vendor invoice classification</STRONG> report has the internal name <STRONG>VendSpendCategoryInvoice</STRONG>.</P>


</div>
<p>You can also place vendors on hold, so that purchasing transactions cannot continue toward completion. Vendors that you no longer do business with must be inactivated and removed from the view that purchasing agents and employees use to find vendors.</p>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="set-up-the-profile-page-in-the-vendor-portal.md">Set up the Profile page in the Vendor portal</a></p></li>
<li><p><a href="procurement-and-sourcing-reports.md">Procurement and sourcing reports</a></p></li>
<li><p><a href="create-or-modify-a-vendor-account.md">Create or modify a vendor account</a></p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Reason codes for replies to requests for quotation (RFQs).</p></td>
<td><p>You can now use the same reason codes in RFQ replies that you use in other vendor transactions. Reason codes help explain why transactions were entered, such as why an RFQ was rejected.</p>
<p>For more information, see <a href="set-up-requests-for-quotation.md">Set up requests for quotation</a>.</p></td>
</tr>
<tr class="even">
<td><p>Displayed and required fields and data validations for vendor-related requests.</p></td>
<td><p>You can define the visible and required fields that are displayed to employees, prospective vendors, and vendors for each type of vendor-related request that is submitted via Enterprise Portal. You can also define the data validation checks that are required for each request type. These setup tasks are completed in the Microsoft Dynamics AX client.</p>
<p>For more information, see <a href="about-vendor-request-configuration.md">About vendor request configuration</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Allow vendor registration for unsolicited vendors.</p></td>
<td><p>External vendors, or vendors in Microsoft Dynamics AX who are interested in becoming approved vendors, can register through an anonymous external portal. This feature provides an efficient source of potential new vendors and supports a competitive procurement process.</p>
<p>For more information, see <a href="checklist-deploy-an-unsolicited-vendor-portal.md">Checklist: Deploy an unsolicited vendor portal</a> and <a href="set-up-the-signup-page-for-unsolicited-vendors.md">Set up the Signup page for unsolicited vendors</a>.</p></td>
</tr>
<tr class="even">
<td><p>Maintain vendor data through the vendor self-service portal.</p></td>
<td><p>The vendor self-service portal has two new Role Centers, Vendor and Vendor portal administrator.</p>
<p>Users who have the Vendor role can complete the following tasks in the vendor self-service portal:</p>
<ul>
<li><p>Maintain the vendor profile.</p></li>
<li><p>Update invoices.</p></li>
<li><p>Submit requests for permission to do business in additional procurement categories.</p></li>
<li><p>Submit confirmation that the vendor can do business in the additional procurement categories that are outlined in a vendor category extension request that an employee submitted.</p></li>
<li><p>Reply to RFQs.</p></li>
<li><p>Respond to purchase orders, which are sales orders on the vendor side.</p></li>
<li><p>View purchase order confirmations.</p></li>
<li><p>View product receipt journals.</p></li>
</ul>
<p>For more information, see <a href="vendor-security-role-vendvendor.md">Vendor security role (VendVendor)</a>.</p>
<p>Users who have the Vendor portal administrator role can complete the following tasks in the vendor self-service portal:</p>
<ul>
<li><p>View the vendor profile.</p></li>
<li><p>Create requests to add or delete users.</p></li>
<li><p>Maintain procurement catalogs.</p></li>
<li><p>View purchase orders and RFQs.</p></li>
</ul>
<p>For more information, see <a href="vendor-portal-administrator-security-role-vendvendorportaladministrator.md">Vendor portal administrator security role (VendVendorPortalAdministrator)</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Authorize employees to request approval for new vendors.</p></td>
<td><p>Employees can use the new <strong>Vendor</strong> form in the employee portal to request that a vendor be added to the vendor list. After vendors are approved, they are added to the vendor list and are then available for transaction processing.</p>
<p>For more information, see <a href="key-tasks-set-up-vendor-add-requests.md">Key tasks: Set up vendor add requests</a>.</p></td>
</tr>
<tr class="even">
<td><p>Spend analytics for Purchasing.</p></td>
<td><p>Several preconfigured reports have been added that purchasing agents and purchasing managers can use to analyze spending trends for their organization, based on dimensions such as vendor, procurement category, and location.</p>
<p>For more information, see <a href="procurement-and-sourcing-reports.md">Procurement and sourcing reports</a>.</p>
<div class="alert">

> [!NOTE]
> <P>All reports for spend analytics contain the word ”Spend” as part of the internal report name. For example, the <STRONG>Spend by procurement category and vendor invoice classification</STRONG> report has the internal name <STRONG>VendSpendCategoryInvoice</STRONG>.</P>


</div></td>
</tr>
<tr class="odd">
<td><p>Vendor extension requests</p></td>
<td><p>After vendors have been approved, they can request to be added to additional procurement categories. The process for category extension requests makes it easy for approved vendors to expand their business opportunities in your organization. However, this process also puts controls in place to guarantee appropriate oversight.</p>
<p>For more information, see <a href="manage-your-category-assignments.md">Manage your category assignments</a>.</p></td>
</tr>
<tr class="even">
<td><p>Vendor requests from employees</p></td>
<td><p>Employees can submit new vendor requests in Enterprise Portal. A new vendor request is an internal request that you submit to your purchasing department to request that a specified vendor be allowed to do business in your company, selling items or services in specific procurement categories. There are several kinds of vendor request:</p>
<ul>
<li><p>Request that a vendor that is not a vendor for any legal entity in the organization be allowed to do business with your legal entity.</p></li>
<li><p>Request that an existing vendor that is allowed to do business with other legal entities in the organization be added as a vendor for your legal entity.</p></li>
<li><p>Request that a vendor be allowed to provide goods and services in additional procurement categories.</p></li>
<li><p>Request that a vendor’s hold status be changed.</p></li>
</ul>
<p>For more information, see <a href="maintaining-vendor-requests.md">Maintaining vendor requests</a>.</p>
<p>In the Microsoft Dynamics AX client, an enhancement has been made so that procurement professionals can perform the following tasks:</p>
<ul>
<li><p>Expand the vendor scope beyond the scope that was originally requested, either for categories or companies. For more information, see <a href="maintain-vendor-category-assignments.md">Maintain vendor category assignments</a>.</p></li>
<li><p>Reject prospective vendors that reside in a country/region that is subject to embargo. For more information, see <a href="key-tasks-manage-prospective-vendor-requests.md">Key tasks: Manage prospective vendor requests</a>.</p></li>
<li><p>Configure questionnaires that employees and vendors must complete as part of the request process. For more information, see the following topics:</p>
<ul>
<li><p><a href="key-tasks-set-up-vendor-add-requests.md">Key tasks: Set up vendor add requests</a></p></li>
<li><p><a href="key-tasks-set-up-vendor-extension-requests.md">Key tasks: Set up vendor extension requests</a></p></li>
<li><p><a href="key-tasks-set-up-vendor-category-requests.md">Key tasks: Set up vendor category requests</a></p></li>
</ul></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Vendors can view and reply to RFQs in the vendor self-service portal.</p></td>
<td><p>Approved vendors can respond to RFQs directly from the vendor self-service portal. You can view the replies in the list of RFQ replies in the Microsoft Dynamics AX client.</p>
<p>For more information, see <a href="view-and-reply-to-a-request-for-quotation.md">View and reply to a request for quotation</a>.</p></td>
</tr>
<tr class="even">
<td><p>Support for flexible authentication in customer, employee, and vendor self-service portals</p></td>
<td><p>Microsoft SharePoint flexible authentication mechanisms, such as form-based authentication and Windows Live ID authentication, are supported as authentication mechanisms for Microsoft Dynamics AX users. The vendor onboarding process and vendor self-service portal incorporate support for flexible authentication.</p>
<p>The user request process supports the onboarding of all Microsoft Dynamics AX users by using pluggable authentication in the following areas: customers in the customer self-service portal, employees in the employee self-service portal, and vendors in the vendor self-service portal.</p>
<p>For more information, see <a href="deploy-an-enterprise-portal-site-that-uses-forms-based-authentication.md">Deploy an Enterprise Portal site that uses forms-based authentication</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Corrections to a product receipt (previously, a purchase packing slip)</p></td>
<td><p>In earlier versions of Microsoft Dynamics AX, the approach that was used to correct or reverse a product receipt had several issues. The user had to post a new, negative product receipt that had a new product receipt number, and the system arbitrarily picked one of the posted product receipts for reversal.</p>
<p>A new, dedicated process is introduced for corrections to purchase receipts. You can now correct, or partially or fully reverse, a specific product receipt that has been posted. When you correct or reverse a product receipt, the product receipt does not introduce a new product receipt number. Instead a new version of the product receipt is introduced.</p>
<p>For more information, see <a href="correct-a-vendor-invoice-that-was-matched-to-the-wrong-product-receipt-line.md">Correct a vendor invoice that was matched to the wrong product receipt line</a>.</p></td>
</tr>
<tr class="even">
<td><p>Confirmation of product receipts</p></td>
<td><p>The requester of products can confirm product receipts. This feature is especially useful in organizations where employees perform a large volume of indirect material procurement.</p>
<p>The feature provides a simple user interface in Enterprise Portal. The user interface lets the user perform the following tasks:</p>
<ul>
<li><p>Confirm full and partial receipt of requested products.</p></li>
<li><p>Reject a full or partial quantity of requested products, and add comments to explain why the receipt is rejected.</p></li>
<li><p>Change the delivery date on selected line items.</p></li>
<li><p>Create fixed asset entries in relation to the action for confirmation of product receipts.</p></li>
</ul>
<p>The feature also provides the following types of notification workflows:</p>
<ul>
<li><p>Notify the requester that products are due to arrive.</p></li>
<li><p>Notify the requester that the invoice of ordered products is registered, but that the confirmation of product receipt action has not yet been performed.</p></li>
<li><p>Notify a specific client user that line items have been rejected by the requester of products.</p></li>
<li><p>Notify a specific client user that the confirmation of product receipt action that was performed by the requester of goods has failed.</p></li>
</ul>
<p>For more information, see <a href="about-confirmation-of-product-receipts.md">About confirmation of product receipts</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Line numbers in purchase orders</p></td>
<td><p>A line number has been introduced in the purchase order form. The main purpose of the new line number is as follows:</p>
<ul>
<li><p>Identify line items in a purchase order.</p></li>
<li><p>Sort purchase order lines according to the line number.</p></li>
</ul>
<p>When an order line is created, a line number is assigned to the line at an increment that is set in a global parameter. A user can manually change the assigned number.</p>
<p>The feature also provides a renumbering function that reassigns line numbers to the purchase order lines according to an increment that is set globally.</p>
<p>For more information, see <a href="set-up-update-of-purchase-order-lines.md">Set up update of purchase order lines</a>.</p></td>
</tr>
<tr class="even">
<td><p>Enhancements to trade agreements</p></td>
<td><p>Trade agreements are now created and maintained in journals. This change allows for better control, usability, and transparency. Microsoft Dynamics AX now supports one view that includes all trade agreements for a selected set of items, customers, and vendors. Microsoft Dynamics AX also supports separate roles for creating or maintaining trade agreements, and for approving, bulk updating, and controlling date types in trade agreements.</p>
<p>In earlier versions of Microsoft Dynamics AX, changes to an order or an order line could indirectly cause the trade agreements to be reevaluated. This reevaluation could overwrite values that had been entered manually or entered by an external source. External sources include sales quotations, project quotations, purchase requisitions, RFQs, purchase agreements or sales agreements, projects, Microsoft Dynamics AX Application Integration Framework (AIF), or Enterprise Portal. Now, configuration settings can prevent unintended reevaluation of trade agreements.</p>
<p>The smart rounding concept has also been introduced. Smart rounding is a type of psychological pricing or price ending that is based on the marketing theory that prices have a psychological impact on people. Smart rounding pertains to unusual prices that are somewhat less than a round number, such as USD 19.99. Smart rounding can be applied after a bulk adjustment of trade agreements, or it can be applied automatically after a unit price has been calculated, based on a generic currency and an exchange rate. Date type control enables trade agreements to be evaluated, based not only on the entry dates but also on the requested dates.</p>
<p>For more information, see <a href="http://download.microsoft.com/download/4/e/3/4e36b655-568e-4d4a-b161-152b28baaf30/implementing_the_agreement_framework_ax2012.pdf">Implementing the Agreement Framework</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Enhanced purchase agreement functionality</p></td>
<td><p>The blanket purchase order functionality has been redesigned and renamed “purchase agreement.” Whereas blanket purchase orders were previously handled in the <strong>Purchase order details</strong> form, purchase agreements now have their own simplified form. Some of the changes are as follows:</p>
<ul>
<li><p>Microsoft Dynamics AX supports both value-based and quantity-based purchase agreements.</p></li>
<li><p>You can order certain products and procurement categories directly by using the new <strong>Purchase agreement lines</strong> view of the <strong>Purchase agreements</strong> form.</p></li>
<li><p>You can apply the terms and conditions of a purchase agreement, such as the prices and discounts, when you create an.</p></li>
<li><p>You can control whether to search for purchase agreements when purchase order lines are created indirectly, such as when planned orders are firmed.</p></li>
<li><p>You can define a validity period for a purchase agreement. The delivery date of a purchase must be in the validity period.</p></li>
<li><p>You can put purchase agreements on hold to control whether those purchase agreements are available to purchasing agents during ordering.</p></li>
</ul>
<p>For more information, see <a href="about-purchase-agreements.md">About purchase agreements</a>.</p></td>
</tr>
<tr class="even">
<td><p>Improvements to the allocation of charges</p></td>
<td><p>You can allocate charges to specific lines on a purchase order or an invoice. For example, if some items on a purchase order were picked up at the vendor’s location, and some were delivered, you can allocate the delivery charges only to the items that were delivered.</p>
<p>For more information, see <a href="adjust-charges-on-vendor-invoices.md">Adjust charges on vendor invoices</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Purchase orders and change management</p></td>
<td><p>Change management lets you request changes to purchase orders. Change management includes workflow integration, which must be set up to manage the approval process for change requests. When workflow has been configured, it determines the route of the purchase order, the tasks that must be completed, who must complete the tasks and under what circumstances, and whether tasks require user interaction or take place automatically.</p>
<p>When a change is requested, the purchase order is set to a draft state until it is approved. Only an approved purchase order can be confirmed. Even if change management is not enabled, confirmation of purchase orders is mandatory. Therefore, orders cannot be received and invoiced until the purchase order has been confirmed.</p>
<p>If change management is enabled, purchase orders cannot be deleted. Instead, purchase orders become obsolete and are replaced by the most recent purchase order for which a change request has been approved. Purchase orders that were previously approved are stored in a separate form.</p>
<p>Even if change management is enabled on a global level, it can be inactivated for individual vendors and purchase orders if, for example, orders from a particular vendor do not require approval.</p>
<p>For more information, see <a href="key-tasks-change-management-for-purchase-orders.md">Key tasks: Change management for purchase orders</a>.</p></td>
</tr>
<tr class="even">
<td><p>Changes to intercompany setup</p></td>
<td><p>Intercompany relations and policies are set up in a new form that contains the same content as the form that is used in earlier versions. The new setup form can be accessed from a button on the customer and vendor pages. The setup in this form is shared for the vendor and the customer in the trading relationship, and only has to be defined one time. In earlier versions, the setup was not shared, and had to be defined in both the vendor company account and the customer company account. There are no functional changes because of this change.</p>
<p>For more information, see <a href="organizing-an-intercompany-setup.md">Organizing an intercompany setup</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Finalize purchase orders and purchase order lines.</p></td>
<td><p>You can finalize purchase order lines that have been completed. A line is completed when the ordered quantity has been received in full and matched to vendor invoices. The whole purchase order can be finalized if all its lines have been completed or canceled.</p>
<p>For more information, see <a href="https://technet.microsoft.com/library/hh209586(v=ax.60)">Finalize purchase order (form)</a>.</p></td>
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
<td><p>Enhancements to the change management process for purchase orders</p>
<p></p></td>
<td><p>When a purchase order is resubmitted to the workflow for re-approval, the workflow system is responsible for determining whether the changes to the purchase order can be automatically approved.</p>
<p>For more information, see <a href="key-tasks-change-management-for-purchase-orders.md">Key tasks: Change management for purchase orders</a>.</p></td>
</tr>
<tr class="even">
<td><p>Data partitions are added for the Order management upgrade.</p></td>
<td><p>An option to define data partitions during the upgrade of Order management data has been added. By setting up a data partition in Microsoft Dynamics AX, you make sure that, after the upgrade, historical transactions can be referenced between companies that are contained in the same data partition.</p>
<p>For more information, see <a href="about-purchase-order-upgrade.md">About purchase order upgrade</a> and <a href="configure-partitions.md">Configure partitions</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Enhancements to the new vendor registration process</p></td>
<td><p>Employees can submit new vendor requests in Enterprise Portal. The amount of information that employees must provide before they can submit a request has been reduced.</p></td>
</tr>
<tr class="even">
<td><p>Sales automatic charges that are based on tiers and modes of delivery in sales orders</p></td>
<td><p>This feature provides an interface for retail channels that presents the available modes of delivery, calculates shipping charges, and obtains tracking information.</p>
<p>For more information, see <a href="about-tiered-charges-on-sales-orders.md">About tiered charges on sales orders</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Changes to Order management features</p></td>
<td><p>The following Order management features have been updated in AX 2012 R2:</p>
<ul>
<li><p>Purchase order</p></li>
<li><p>Agreement</p></li>
<li><p>Trade agreement</p></li>
<li><p>Intercompany</p></li>
<li><p>Sales order</p></li>
<li><p>Sales return</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Integration of sales agreements and return orders</p></td>
<td><p>In AX 2012 R2, the sales return order line can be associated with the sales agreement line that is related to the order.</p>
<p>For more information, see <a href="return-an-item-ordered-from-a-sales-agreement.md">Return an item ordered from a sales agreement</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Fulfillment of purchase requisition demand is orchestrated by master planning.</p></td>
<td><p>The purchase requisition functionality that was introduced in AX 2009 assumes that requisition demand is always fulfilled by a purchase order. This feature is generalized in AX 2012 R2. Therefore, requisition demand can be fulfilled by means other than a purchase order, such as a transfer order or a production order.</p>
<p>For more information, see <a href="about-purchase-requisitions.md">About purchase requisitions</a>.</p></td>
</tr>
<tr class="even">
<td><p>Product search on the Employee Services site</p></td>
<td><p>Employees can order products from the AX 2012 Employee Services site. As part of the experience, employees can search for products. To enhance the performance of product searches on the Employee Services site when products are ordered, AX 2012 R2 includes a new job that synchronizes product search data. In AX 2012 R2, when procurement product catalogs are created and updated, this new job must be run to synchronize the product data with the Employee Services site. The job updates both product search data and the products that are displayed in the catalog on the site. To access the job click <strong>Procurement and sourcing</strong> &gt; <strong>Periodic</strong> &gt; <strong>Employee services</strong>, and then click <strong>Synchronize product search data</strong>.</p>
<p>After an upgrade, the batch job must be run to upload the product data to the Employee Services site.</p></td>
</tr>
</tbody>
</table>


## What’s new in cumulative update 6 for Microsoft Dynamics AX 2012

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
<td><p>Confirm purchase orders with vendors before purchase orders are confirmed and created.</p></td>
<td><p>Before a purchase order is confirmed and created, you can send a purchase inquiry to the vendor to validate that the vendor can fulfill the purchase order with regard to the product, quantity, and delivery dates. You can use the vendor’s response to decide whether to create, change, or cancel the purchase order.</p>
<p>For more information, see <a href="create-a-purchase-inquiry.md">Create a purchase inquiry</a>.</p></td>
</tr>
<tr class="even">
<td><p>New purchasing policy: Price/discount transfer</p></td>
<td><p>You can use the new purchasing policy, Price/discount transfer, to control how prices are applied to purchase orders that are created from purchase requisitions for catalog items. Prices and discounts for catalog items can be calculated based on trade agreements, or they can be transferred directly from the purchase requisitions, depending on the requirements of your business. If you create a Price/discount transfer policy, users can override the policy on the purchase requisition line.</p>
<p>For more information, see <a href="set-up-rules-for-demand-consolidation-and-for-creating-purchase-orders.md">Set up rules for demand consolidation and for creating purchase orders</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Price information from a sales agreement or purchase agreement is automatically copied to updated order lines.</p></td>
<td><p>When you update a sales order line or a purchase order line to match the conditions on the associated purchase agreement or sales agreement, any relevant data from the agreement is automatically copied to the order line.</p></td>
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
<td><p>Financial dimensions can be specified on sales agreements or purchase agreements.</p></td>
<td><p>You can now specify financial dimensions on sales agreements or purchase agreements. Dimensions can be added to the document headers or to individual lines. The financial dimensions of a sales or purchase order agreement are copied to the header of a sales or purchase order that refers to the agreement. The dimensions are then copied to the sales or purchase order lines when the agreement is referenced by the order lines.</p></td>
</tr>
<tr class="even">
<td><p>A <strong>Totals</strong> FactBox is added to the <strong>Purchase orders</strong> list page.</p></td>
<td><p>The <strong>Purchase orders</strong> list page now has a FactBox that lists information such as the total amount, charges, and discounts for all purchase orders. The information is the same as the information that is available in the <strong>Totals</strong> form for purchase orders. The values that are displayed in the FactBox are not automatically updated if you make a change to a purchase order. To update the values, click the <strong>Refresh</strong> button, or open the <strong>Totals</strong> form. The data is also updated when you confirm a purchase order.</p></td>
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
<td><p>Setting a request for quotation expiration date and time</p></td>
<td><p>You can specify an expiration date and time on a request for quotation (RFQ) so that bids are received in a timely manner.</p>
<p>For more information, see <a href="create-a-request-for-quotation.md">Create a request for quotation</a>.</p></td>
</tr>
<tr class="even">
<td><p>Specifying a sealed bidding process</p></td>
<td><p>You can specify that bids (replies to an RFQ) are sealed until the solicitation closing date. They are hidden until bid tabulation starts.</p>
<p>For more information, see <a href="about-sealed-bids.md">About sealed bids</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Creating scoring methods and criteria so that you can score bids</p></td>
<td><p>You can define sets of scoring criteria and scoring methods that will be used for evaluating bids (RFQ replies).</p>
<p>For more information, see <a href="create-and-use-scoring-criteria-and-methods.md">Create and use scoring criteria and methods</a>.</p></td>
</tr>
<tr class="even">
<td><p>Creating custom solicitation types</p></td>
<td><p>You can create solicitation types in order to match procurement requirements in your organization. You can filter on those categories to make finding documents easier.</p>
<p>For more information, see <a href="create-and-use-a-solicitation-type.md">Create and use a solicitation type</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Authorizing alternate or substitute items in bids</p></td>
<td><p>You can allow vendors to provide alternate items or services, so that you can be notified of better alternatives or changes to the requested item or service.</p>
<p>For more information, see <a href="add-an-alternate-line-to-a-request-for-quotation.md">Add an alternate line to a request for quotation</a>.</p></td>
</tr>
<tr class="even">
<td><p>Assign numbers to lines in an RFQ</p></td>
<td><p>Each line in an RFQ is assigned a number. You can add items and renumber the list as needed. The numbers appear in all the RFQ-related documents.</p>
<p>For more information, see <a href="create-a-request-for-quotation.md">Create a request for quotation</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Automatically add vendors to an RFQ</p></td>
<td><p>You can easily add vendors to the RFQ who are approved for selling at least one of the categories you’ve specified on the RFQ lines.</p>
<p>For more information, see <a href="create-a-request-for-quotation.md">Create a request for quotation</a>.</p></td>
</tr>
<tr class="even">
<td><p>Creating a questionnaire for vendors</p></td>
<td><p>You can create and administer a questionnaire by either collecting questions from other users, attaching one or more questionnaires to an RFQ at the header level, or requiring vendors to complete the questionnaire as part of the reply.</p>
<p>For more information, see <a href="create-a-request-for-quotation.md">Create a request for quotation</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Amending an RFQ or attaching documents after sending it</p></td>
<td><p>After you issue an RFQ, you can make updates and add attachments as long as no replies have been registered. You can communicate these changes through the Vendor portal to keep prospective bidders aware of updates.</p>
<p>For more information, see <a href="modify-a-request-for-quotation.md">Modify a request for quotation</a>.</p></td>
</tr>
<tr class="even">
<td><p>Ranking received bids</p></td>
<td><p>You can compare bids, and rank them at the header level. You can filter and sort for the most relevant information.</p>
<p>For more information, see <a href="compare-bids-and-award-a-contract.md">Compare bids and award a contract</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Placing a purchase requisition on hold</p></td>
<td><p>You can hold a requisition from further processing and indicate the reason for the hold, so that you can better manage requisitions and communicate status.</p>
<p>For more information, see <a href="key-tasks-create-and-submit-a-purchase-requisition.md">Key tasks: Create and submit a purchase requisition</a>.</p></td>
</tr>
<tr class="even">
<td><p>Publishing an RFQ</p></td>
<td><p>You can publish your RFQ to the public Vendor portal so that unregistered vendors can view it. All lines on the RFQ are also sent to the vendors that are selected in the RFQ.</p>
<p>This control is available only if the <strong>Public Sector</strong> configuration key is selected.</p>
<p>For more information, see <a href="create-a-request-for-quotation.md">Create a request for quotation</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Creating vendor rebate agreements</p></td>
<td><p>You can set up vendor rebate agreements to define the rebates that vendors (suppliers) offer to your company. Rebate amounts can be based on the monetary value of the purchase or the number of items that are purchased.</p>
<p>For more information, see <a href="set-up-vendor-rebate-agreements.md">Set up vendor rebate agreements</a>.</p></td>
</tr>
<tr class="even">
<td><p>Working with vendor rebates</p></td>
<td><p>You can apply vendor rebates to purchase orders and process rebate claims.</p>
<p>For more information, see <a href="work-with-vendor-rebates.md">Work with vendor rebates</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Viewing price details for purchase order lines</p></td>
<td><p>The <strong>Price details</strong> form displays detailed information about the prices, agreements, and trade agreements that are associated with the product in a purchase order line. This information is used to calculate discounts, rebates, margins, and royalties for the order line.</p>
<p>You must enable price details in the procurement and sourcing parameters. For more information, see <a href="enable-price-details-on-orders.md">Enable price details on orders</a>.</p></td>
</tr>
<tr class="even">
<td><p>Using the direct delivery workbench</p></td>
<td><p>Use the direct delivery workbench to create and manage purchase orders for direct deliveries.</p>
<p>For more information, see <a href="create-direct-deliveries.md">Create direct deliveries</a>.</p></td>
</tr>
</tbody>
</table>


Enterprise Portal updates for Microsoft Dynamics AX 2012 R3 include the following.

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
<td><p>Using claims-mode authentication for registered vendors.</p></td>
<td><p>After registering with your business or organization, vendors can access the Vendor portal outside your Active Directory domain by using one of the following types of accounts: Windows Live (Microsoft account), Yahoo, or Facebook.</p>
<p>For more information, see <a href="deploy-enterprise-portal-for-vendor-registration-with-windows-azure-active-directory-access-control.md">Deploy Enterprise Portal for vendor registration with Windows Azure Active Directory Access Control</a>.</p>
<p>If you use a Google account, see Google as an ACS Identity Providerand Migrating ACS Namespaces to Google OpenID Connect on MSDN.</p></td>
</tr>
<tr class="even">
<td><p>Viewing RFQs as an unsolicited vendor or guest.</p></td>
<td><p>Public sector vendors not yet registered on the Vendor portal can access a public, non–claims-aware site as a &quot;guest&quot; so they can view publicly available documents, such as lists of open requests for quotation or purchase orders.</p>
<p>For more information, see <a href="bid-on-a-request-for-quotation.md">Bid on a request for quotation</a>.</p>
<div class="alert">

> [!NOTE]
> <P>This control is available only if the <STRONG>Public Sector</STRONG> configuration key is selected.</P>


</div></td>
</tr>
<tr class="odd">
<td><p>Viewing details of closed RFQs.</p></td>
<td><p>Public sector vendors can view all open and closed purchase orders, RFQs, and their details, including scoring and award notes on accepted bids.</p>
<p>For more information, see <a href="bid-on-a-request-for-quotation.md">Bid on a request for quotation</a>.</p>
<div class="alert">

> [!NOTE]
> <P>This control is available only if the <STRONG>Public Sector</STRONG> configuration key is selected.</P>


</div></td>
</tr>
<tr class="even">
<td><p>Requesting to reply to (bid on) an RFQ that has not specifically been sent.</p></td>
<td><p>Public sector vendors can request to reply to RFQs that have been published to the <strong>Open requests for quotations</strong> list page even if the vendors have not been included as a vendor on the RFQ.</p>
<p>For more information, see <a href="bid-on-a-request-for-quotation.md">Bid on a request for quotation</a>.</p>
<div class="alert">

> [!NOTE]
> <P>This control is available only if the <STRONG>Public Sector</STRONG> configuration key is selected.</P>


</div></td>
</tr>
<tr class="odd">
<td><p>Adding alternate or substitute items to bids.</p></td>
<td><p>If the requester allows it, all vendors can submit an alternate item on an RFQ and provide a reason for the alternate.</p>
<p>For more information, see <a href="bid-on-a-request-for-quotation.md">Bid on a request for quotation</a> or <a href="view-and-reply-to-a-request-for-quotation.md">View and reply to a request for quotation</a>.</p></td>
</tr>
<tr class="even">
<td><p>Adding fees and charges on bids.</p></td>
<td><p>All vendors can enter a charge on the RFQ reply line in addition to the quantity and unit price.</p>
<p>For more information, see <a href="bid-on-a-request-for-quotation.md">Bid on a request for quotation</a> or <a href="view-and-reply-to-a-request-for-quotation.md">View and reply to a request for quotation</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Answering an RFQ questionnaire.</p></td>
<td><p>Requesters can now include a questionnaire with the RFQ and require vendors to fill it out as part of the bid.</p>
<p>For more information, see <a href="bid-on-a-request-for-quotation.md">Bid on a request for quotation</a> or <a href="view-and-reply-to-a-request-for-quotation.md">View and reply to a request for quotation</a>.</p></td>
</tr>
<tr class="even">
<td><p>Viewing RFQ amendments.</p></td>
<td><p>Customers can change the contents of an RFQ after sending it. You can view the changes, including attachments, on the <strong>Amendments</strong> FastTab in the RFQ.</p>
<p>For more information, see <a href="bid-on-a-request-for-quotation.md">Bid on a request for quotation</a> or <a href="view-and-reply-to-a-request-for-quotation.md">View and reply to a request for quotation</a>.</p></td>
</tr>
</tbody>
</table>


## What’s new in Microsoft Dynamics AX 2012 R3 Cumulative Update 8

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
<td><p>Creating a contact for an existing unsolicited vendor.</p></td>
<td><p>You can create a contact record from the record of an unsolicited vendor.</p>
<p>For more information, see <a href="create-a-contact-for-an-unsolicited-vendor.md">Create a contact for an unsolicited vendor</a>.</p></td>
</tr>
<tr class="even">
<td><p>(Public sector) Permitting only invited vendors to bid on an RFQ on the Vendor portal</p></td>
<td><p>For public sector users, you can specify that a published RFQ having a specific solicitation type is visible only to vendors that are included on the RFQ.</p>
<p>For more information, see <a href="create-and-use-a-solicitation-type.md">Create and use a solicitation type</a>.</p></td>
</tr>
<tr class="odd">
<td><p>(Public sector) Controlling which details vendors see for closed RFQs on the Vendor portal.</p></td>
<td><p>For public sector users, you can specify which elements to allow vendors to see on the <strong>Closed requests for quotations</strong> page.</p>
<p>For more information, see <a href="create-and-use-a-solicitation-type.md">Create and use a solicitation type</a>.</p></td>
</tr>
<tr class="even">
<td><p>(Public sector) Publishing an RFQ to the Vendor portal and sending it to a vendor at the same time.</p></td>
<td><p>For public sector users, the <strong>Send</strong> button on the RFQ <strong>Action Pane</strong> has been replaced by a <strong>Send and publish to Vendor portal</strong> button, allowing one-step distribution to vendors.</p>
<p>For more information, see <a href="create-a-request-for-quotation.md">Create a request for quotation</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Creating and finalizing an amendment for an RFQ.</p></td>
<td><p>When you add attachments or modify line entries on RFQs that have been sent to vendors, the <strong>Finalize amendment (%1) - Case ID: %2, Document title: %3</strong> wizard helps you invalidate any previously received bids and resend the amended RFQ to the invited vendors. For public sector users, if the RFQ has been published to the Vendor portal, the amended version will be published.</p>
<p>For more information, see <a href="modify-a-request-for-quotation.md">Modify a request for quotation</a>.</p></td>
</tr>
</tbody>
</table>


Enterprise Portal updates for AX 2012 R3 CU8 include the following.

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
<td><p>Adding claims-authenticated users.</p></td>
<td><p>As part of the process for creating new users, Vendor portal administrators can add a vendor that will sign into the portal by using an email address from one of various providers, such as Facebook, Yahoo.com, or Windows Live (Microsoft account). Microsoft Dynamic AX authenticates the user through email.</p>
<p>For information about Google accounts, see Google as an ACS Identity Provider and Migrating ACS Namespaces to Google OpenID Connect.</p></td>
</tr>
<tr class="even">
<td><p>Streamlining the Vendor portal signup process</p></td>
<td><p>Vendor portal signup improvements include being able to specify a default country/region for vendors, require specific fields in the signup forms, and specify levels of product categories for vendors. For Public sector, vendor users can search to see if their organization is already registered and add themselves to that record. This can streamline the signup process.</p></td>
</tr>
</tbody>
</table>

  


