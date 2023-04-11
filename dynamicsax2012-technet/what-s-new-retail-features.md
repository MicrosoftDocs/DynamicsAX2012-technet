---
title: "What's new: Retail features"
TOCTitle: Retail features
ms:assetid: 6e6b8efb-ba6d-4825-b938-502fc8fc7d0b
ms:mtpsurl: https://technet.microsoft.com/library/Dn527132(v=AX.60)
ms:contentKeyID: 59623261
author: tonyafehr
ms.date: 06/09/2015
mtps_version: v=AX.60
---

# What's new: Retail features 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

This topic describes new and changed Retail features since the release of Microsoft Dynamics AX 2012. Changes are described in the following tables according to the update in which they were released.

  - Cumulative update 8 for Microsoft Dynamics AX 2012 R3

  - Microsoft Dynamics AX 2012 R3

  - Cumulative update 7 for Microsoft Dynamics AX 2012 R2

  - Microsoft Dynamics AX 2012 R2

  - Microsoft Dynamics AX 2012 Feature Pack

## What’s new in cumulative update 8 for Microsoft Dynamics AX 2012 R3

## What's new for developers and IT professionals

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What's new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Seamless offline processing mode now available in supported Modern Point of Sale (POS) clients</p></td>
<td><p>Modern POS clients for Microsoft Dynamics AX Retail are now provisioned with a local database and a local instance of the Commerce Runtime (CRT). In the event that a Modern POS client cannot communicate with a Retail Server (either a local or centrally-hosted Retail Server) for normal CRT processing, the Modern POS client seamlessly shifts to offline processing mode. In offline processing mode, the local instance of the CRT and the local database perform operations such as processing transactions. When the connection to the Retail Server is restored, the Modern POS client automatically shifts processing back to the Retail Server and the channel database for normal operations.  </p>
<div class="alert">

> [!WARNING]
> <P>Due to the database and CRT footprint on the Modern POS device, offline processing includes a subset of normal processing with a subset of data.</P>


</div></td>
</tr>
<tr class="even">
<td><p>Self-service deployment for store components</p></td>
<td><p>In AX 2012 R3 and previous releases of AX 2012, setting up a new retail store or updating the software at existing stores is a long and complicated process. A system administrator must install multiple Retail components on multiple computers at each store. It can take days to install and configure all of the required components on all affected computers.</p>
<p>In CU8, a self-service deployment option is available. In a self-service deployment, users at each store can easily install the software that is required at the store. At headquarters, the system administrator plans the topology of the store and the software that must be installed on each computer. Then the system administrator enters deployment information in Microsoft Dynamics AX.</p>
<p>The user at the store is provided with basic information about how to deploy the components that the administrator has specified, including a URL where the user can download an installation package and a password to securely decode the installation package. The user goes to each computer in the store and runs the installation package. Special permissions and knowledge of the deployment topology are not necessary to complete the deployment.</p></td>
</tr>
<tr class="odd">
<td><p>Retail mass deployment improvements</p></td>
<td><p>In CU8, Retail Hardware Station and Modern POS offline databases can be deployed by using the mass deployment toolkit. Enhancements have also been made to the performance of the mass deployment tools.</p></td>
</tr>
<tr class="even">
<td><p>Support added for migrating transaction data from Microsoft Dynamics Retail Management System to Retail essentials</p></td>
<td><p>Support has been added for migrating transaction data from Microsoft Dynamics Retail Management System to Retail essentials. Users can access read-only transaction data after migrating.</p>
<p>For more information, see <a href="migrate-data-from-microsoft-dynamics-retail-management-system-retail-essentials.md">Migrate data from Microsoft Dynamics Retail Management System (Retail essentials)</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Retail management pack updated</p></td>
<td><p>The Management Pack for Microsoft Dynamics AX Retail 2012 R3 has been updated to monitor the system for key failure states, and collect events for all Retail components. Support for monitoring modern Point of Sale devices and other Point of Sale devices has also been added.</p></td>
</tr>
</tbody>
</table>


## What's new for end users

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What's new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Shared shifts can be used in Microsoft Dynamics AX Retail and Modern POS</p></td>
<td><p>In this release of Microsoft Dynamics AX and Modern POS, you can use shared shift in your retail stores. Because Modern POS can run on Modern devices, multiple employees must have access to multiple cash drawers, receipt printers, etc. during a shift. Also, new staff permissions control access to opening and closing shared shifts.</p></td>
</tr>
<tr class="even">
<td><p>The PCI Implementation Guide has been updated for Microsoft Dynamics AX 2012 R3 CU8</p></td>
<td><p>The PCI Implementation Guide has been updated for Microsoft Dynamics AX 2012 R3 CU8 to reflect enhancements to Dynamics Online Payment Services online payment processing in Modern POS. The enhancements include authorization, capture, refund, and void card processes for pay-n-carry transactions and customer orders. The PCI Implementation guide also incorporates comments by the Payment Application Data Security Standard (PA-DSS) audit.</p></td>
</tr>
<tr class="odd">
<td><p>Create role-based screen layouts for Modern POS on Windows phones</p></td>
<td><p>You can now create role-based screen layouts and button grids for Modern POS on Windows phones. This support for Windows phone adds to the existing support for role-based screen layouts for Modern POS on tablets, laptops, and PCs.</p></td>
</tr>
<tr class="even">
<td><p>In Retail essentials, you can view the transactions that have been migrated from Microsoft Dynamics RMS</p></td>
<td><p>In Retail essentials, you can view the transactions that have been migrated from Microsoft Dynamics RMS. These transactions appear in the Retail sales form and the Retail store transactions form. The transactions also appear in reports. The transactions are marked as “Posted,” so that they won’t be picked up for statement posting.</p></td>
</tr>
<tr class="odd">
<td><p>Add the ability to apply filters to product searches on any Modern point-of-sale device</p></td>
<td><p>This feature adds the ability to set up filtering capabilities for products that you offer in your store. You can set up different filter types that can be applied to product attributes. This enables your store employees to quickly and easily search all product offerings. Based on a set of criteria, the employee can find the products that your customers are looking for without having to view the details for each possible product match.</p></td>
</tr>
<tr class="even">
<td><p>Add the ability to resize columns on the Modern POS transaction screen</p></td>
<td><p>This feature adds the ability to resize the column widths in the line summary list for the Modern POS transaction screen. Using the screen layout designer you can design your till with the specific column size that you need.</p></td>
</tr>
<tr class="odd">
<td><p>Add the ability to search for products by using product categories or from within a retail product catalog on any Modern point-of-sale device</p></td>
<td><p>This feature adds a tree view of all product categories to the left navigation bar. This enables your store employees to quickly and easily search all product offerings by product category for the product that a customer is asking for as well as to offer possible related products that are in the same or related product categories. A catalog menu option is also being added to the left navigation bar to enable employees to quickly search for the products that a customer wants to buy.</p></td>
</tr>
<tr class="even">
<td><p>Add the ability to compare product details side by side and provide an enhanced product details view on any Modern point-of-sale device</p></td>
<td><p>This feature adds a product comparison window with horizontal scroll to the product details view. A larger screen area will also be added to display the product specifications in greater detail. The ability to open the product image in full screen mode will also be added along with the ability to zoom in on specific details of the image.</p></td>
</tr>
</tbody>
</table>


## What’s new in Microsoft Dynamics AX 2012 R3

## What’s new for developers and IT professionals

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
<td><p>Commerce Data Exchange</p></td>
<td><p>The following updates and improvements were made to Commerce Data Exchange in AX 2012 R3. For more information, see <a href="commerce-data-exchange.md">Commerce Data Exchange</a>.</p>
<p><strong>Commerce Data Exchange architecture</strong></p>
<p>In earlier releases, Synch Service was a Windows service that was installed at headquarters and at stores. In AX 2012 R3, Synch Service is replaced by two components, Commerce Data Exchange: Async Server and Commerce Data Exchange: Async Client:</p>
<ul>
<li><p>Async Server is a Windows Communication Foundation (WCF) service that is installed at headquarters and hosted in Internet Information Services (IIS). Because the service is hosted in IIS, you can take advantage of the scalability and reliability features of IIS, such as load balancing.</p></li>
<li><p>Async Client is a Windows service that is installed at the channel.</p></li>
</ul>
<p><strong>Database architecture</strong></p>
<p>In earlier releases, store databases and online channel databases differed from each other. In AX 2012 R3, store databases, online channel databases, and any other channel-specific databases are just known as channel databases. A channel database can contain data for one or more channels, and the same channel can be included in more than one channel database.</p>
<p><strong>Change tracking</strong></p>
<p>In earlier releases, preactions and actions were used to collect updates to data in the Microsoft Dynamics AX database. In AX 2012 R3, Microsoft SQL Server change tracking is used instead. Because preactions and actions have been eliminated, fewer records are created in the Microsoft Dynamics AX database, and performance is improved.</p>
<p><strong>Retail Scheduler jobs</strong></p>
<p>In earlier releases, three types of scheduler jobs were available:</p>
<ul>
<li><p>A-jobs used actions and preactions to transfer only changed data from Microsoft Dynamics AX to a channel.</p></li>
<li><p>N-jobs were used to transfer all data from Microsoft Dynamics AX to a channel, regardless of whether the data had changed.</p></li>
<li><p>P-jobs were used to transfer data from the point of sale to Microsoft Dynamics AX.</p></li>
</ul>
<p>In AX 2012 R3, only two types of jobs are available, and jobs no longer use the prefixes A, N, and P:</p>
<ul>
<li><p>Outgoing jobs are used to send data from Microsoft Dynamics AX to channels.</p></li>
<li><p>Incoming jobs are used to receive data from channels into Microsoft Dynamics AX.</p></li>
</ul>
<p><strong>Data distribution</strong></p>
<p>In earlier releases, an instance of Synch Service at the head office read data from Microsoft Dynamics AX and sent that data to a channel instance of Synch Service. In AX 2012 R3, data transfer is asynchronous and is initiated by the client.</p>
<p>Based on a distribution schedule, data packages are generated from Microsoft Dynamics AX and deposited in a file storage system. At a regular interval, Async Client checks with Async Server to determine whether there are new data packages. If there is new data, Async Client takes the data from the storage location and applies it to the local channel database.</p>
<p>Therefore, you no longer have to use static IP addresses or name resolution in the store to enable instances of Synch Service to communicate with each other. Additionally, because Async Client does not communicate directly with Microsoft Dynamics AX, .NET Business Connector is no longer required.</p>
<p>To reduce the number of data packages that are generated, you can group retail channel databases. When you create a group of channel databases, the data is created one time for the group, and then multiple channels can pick it up. For example, stores in the same region or of the same type can use the same data, and therefore can be grouped.</p>
<p><strong>Troubleshooting data distribution issues</strong></p>
<p>Several new forms are available to help you troubleshoot data distribution issues:</p>
<ul>
<li><p><strong>Async Server connection status</strong> – This form in Microsoft Dynamics AX shows the last date and time that each instance of Async Client connected to Async Server to check for updates.</p></li>
<li><p><strong>Download sessions</strong> and <strong>Upload sessions</strong> – These forms in Microsoft Dynamics AX show detailed status information for each data transfer. For example, the forms show when a data package was created, when a data package was uploaded or downloaded, and when a data package was applied to the destination database.</p></li>
<li><p><strong>Download history</strong> – This form shows detailed status information for a selected distribution schedule.</p></li>
</ul>
<p>For more information, see <a href="view-history-for-a-distribution-schedule.md">View history for a distribution schedule</a> or <a href="view-or-cancel-retail-data-distribution-sessions.md">View or cancel retail data distribution sessions</a>.</p></td>
</tr>
<tr class="even">
<td><p>Retail Server</p></td>
<td><p>Retail Server is the primary server-side component for Retail Modern POS. This feature processes business logic for Retail Modern POS. Retail Server is to Retail Modern POS clients what Microsoft Dynamics AX Application Object Server (AOS) is to Microsoft Dynamics AX clients. You can deploy Retail Server in a store or in a data center. Retail Server must communicate with a software component of AX 2012 R3 that is named Retail Hardware Station.</p>
<p>For more information, see <a href="microsoft-dynamics-ax-retail-server.md">Microsoft Dynamics AX Retail Server</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Retail Hardware Station</p></td>
<td><p>Hardware Station enables peripherals in the store, such as Modern POS clients, cash drawers, and credit card terminals, to communicate with Retail Server and AX 2012 R3.</p>
<p>For more information, see <a href="microsoft-dynamics-ax-retail-hardware-station.md">Microsoft Dynamics AX Retail Hardware Station</a>.</p></td>
</tr>
<tr class="even">
<td><p>New Retail e-commerce starter stores</p></td>
<td><p>AX 2012 R3 adds two more starter stores to help developers quickly create and brand an e-commerce site. AX 2012 R2 included the Contoso electronics starter store. AX 2012 R3 includes the Fabrikam clothing starter store and the Fabrikam French starter store.</p>
<p>For more information, see <a href="online-store.md">Online Store</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Setup.exe support for starter stores</p></td>
<td><p>In AX 2012 R3, you can install any Retail online starter store by using Setup.exe. However, you can still manually deploy the starter stores by using Windows PowerShell.</p>
<p>For more information, see <a href="install-a-retail-online-store-e-commerce.md">Install a Retail online store (e-commerce)</a>.</p></td>
</tr>
<tr class="even">
<td><p>Support for multiple stores in different languages</p></td>
<td><p>Developers and IT professionals can create multiple Retail online stores that support different currencies and translations, such as translated terms and product listings. These stores can be located in the same SharePoint farm. Therefore, businesses and organizations can sell products in native languages, report financials for different countries, and maximize hardware purchases. Online stores in different languages can connect to the same or different channel databases, and to the same or different product catalog sites.</p></td>
</tr>
<tr class="odd">
<td><p>Additional controls for Retail online stores that are published to Microsoft SharePoint</p></td>
<td><p>The Retail SDK has been updated to contain code for new controls. These controls include a size picker, a zoom control, a category landing page, and category promotions. You can modify and reuse these controls when you customize a Retail online store.</p>
<p>For more information, see the section titled <strong>Extend an online store</strong> in <a href="online-store.md">Online Store</a>.</p></td>
</tr>
<tr class="even">
<td><p>Retail SDK</p></td>
<td><p>The Retail SDK is enhanced to include code samples, templates, and tools that you can use to customize new Retail clients. For more information, see <a href="retail-sdk.md">Retail SDK</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Mass deployment</p></td>
<td><p>In earlier releases of Retail, there was no easy method for deploying Retail components to multiple computers. For example, Retail POS software had to be installed manually on every register in a store. This process could be time-consuming and could create an inconsistent implementation.</p>
<p>In AX 2012 R3, you can use System Center Configuration Manager (SCCM) to automate and centralize the deployment of Retail components. This process is scalable to many components and computers. You can set up topology and configuration information in Microsoft Dynamics AX, and then deploy the correct configuration to all computers by using SCCM.</p>
<p>The following components can be deployed by using SCCM:</p>
<ul>
<li><p>Real-time Service</p></li>
<li><p>Synch Service</p></li>
<li><p>Async Server</p></li>
<li><p>Async Client</p></li>
<li><p>Channel databases</p></li>
<li><p>Retail POS (including offline databases)</p></li>
<li><p>Retail Modern POS</p></li>
<li><p>Retail Server</p></li>
</ul>
<p>For more information, see <a href="mass-deploy-retail-components-by-using-system-center-configuration-manager.md">Mass deploy Retail components by using System Center Configuration Manager</a>.</p></td>
</tr>
<tr class="even">
<td><p>Retail monitoring in System Center Operations Manager</p></td>
<td><p>You can now monitor your Retail environment by using System Center Operations Manager. The System Center Management Pack for Retail in AX 2012 R3 provides a monitoring solution for Microsoft Dynamics AX Retail components. The management pack automatically discovers the Retail components in your environment, and monitors the configuration and availability of those components. The management pack provides early warnings that an operator can use to proactively identify issues that can affect the availability of the Retail system. For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=393807%26clcid=0x409">System Center Management Pack for Microsoft Dynamics AX Retail 2012 R3</a>.</p></td>
</tr>
</tbody>
</table>


## What’s new for application users

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
<td><p>The call center has been added as a new retail channel type</p></td>
<td><p>The call center is a new channel type that you can set up in the <strong>Retail</strong> module. In a call center, workers take customer orders over the telephone and create sales orders. Many of the maintenance tasks for call centers are performed in the new <strong>Call center</strong> module.</p>
<p>For more information about call center features and the <strong>Call center</strong> module, see <a href="what-s-new-call-center-features.md">What's new: Call center features</a>.</p></td>
</tr>
<tr class="even">
<td><p>Catalog features have been added for call center users</p></td>
<td><p>The <strong>Catalogs</strong> form contains functionality that is available to users who are associated with a call center.</p>
<p>For more information, see <a href="what-s-new-call-center-features.md">What's new: Call center features</a> and <a href="setting-up-call-center-catalogs.md">Setting up call center catalogs</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Enhance the usability of info codes by using info code groups</p></td>
<td><p>Info codes let you capture data at the point of sale when a cashier performs various actions. You can also create a hard-coded dependency between info codes to gather data in sequential order.</p>
<p>This feature enhances the existing functionality for info codes by letting you group info codes. Info code groups add flexibility, because you can define fewer info codes but use them in more versatile ways. Info code groups let you perform the following tasks:</p>
<ul>
<li><p>Define fewer info codes and easily reuse them. Info codes that are included in info code groups have no hard-coded dependencies on other info codes. You can include the same info code in multiple info code groups and then use prioritization to present the same info codes in the order that makes sense for your various information gathering requirements.</p></li>
<li><p>Link info codes to other info codes or to info code groups, so that you can gather information about a product or transaction in exactly the way that you require. You do not have to define a separate info code or linked info code for each scenario.</p></li>
</ul>
<p>For more information, see <a href="set-up-info-code-groups.md">Set up info code groups</a>.</p></td>
</tr>
<tr class="even">
<td><p>Enhanced functionality for printing product labels and shelf labels</p></td>
<td><p>This feature lets you print product labels for multiple products at the same time by using the <strong>Released products</strong> list page. This feature also extends the functionality for printing product labels, so that you can automatically print labels for products that are included on a purchase order or transfer order.</p>
<p>You can print product labels for products that are included on a purchase order at any time or only when the products are received. You can print labels for products that are included on a transfer order either when the products are shipped or when the products are received.</p>
<p>For more information about how to print product labels, see <a href="generate-and-print-product-labels.md">Generate and print product labels</a>. For more information about how to print shelf labels, see <a href="generate-and-print-shelf-labels.md">Generate and print shelf labels</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Gift card enhancements</p></td>
<td><p>This feature adds flexibility for gift cards. Gift cards can be set up as a product, and can be made available as a physical product in retail brick-and-mortar stores. You can also sell gift cards as a physical or virtual product, in the form of an electronic gift card, in your online stores and call centers. If the call center functionality is enabled, you can void gift card transactions. Funds can be added to gift cards that are sold through either the call center or the retail point of sale.</p>
<p>Gift cards that are purchased from a store that belongs to one legal entity can now be redeemed in a store that belongs to a different legal entity, if those stores support intercompany transactions.</p>
<p>If your organization supports intercompany transactions, you can set up one company as the parent company. This company can hold the liability for all gift card sales from all stores that are participating in the gift card program. The other stores can be assigned to a different legal entity, but they must roll up to the parent company’s legal entity. When gift cards are sold or redeemed, the liability is increased or decreased accordingly in the parent company by using intercompany posting rules. When statements are posted for retail channels, the liability is increased for the parent company. When payments are made by using the gift card, the liability is decreased for the parent company.</p>
<p>For more information about gift cards, see <a href="about-gift-cards-in-ax-2012-r3.md">About gift cards in AX 2012 R3</a>.</p></td>
</tr>
<tr class="even">
<td><p>Create and maintain product kits</p></td>
<td><p>You can group and package individual products in one sellable unit or product kit. A product kit can include multiple products, variants of those products, and substitutes for any products. The products that are included in a kit are referred to as components. The set of products that make up a product kit are referred to as kit configurations. One product kit can have one or more configurations.</p>
<p>After you define the kit configurations, you release the product kit to your legal entities and set up any product properties for the kit. You can price the kit by using the sum of the base price of the kit components when they are added to the kit, or you can set an overall kit price. The kit price can also be adjusted at the time of sale if additional charges apply for products that are substituted for a standard kit component.</p>
<p>After the kit is created and priced, you can generate assembly orders to send the assembly and packaging instructions to the warehouse, so that the kits can be picked, packed, and shipped to the stores. After the kit configurations are approved, assembly orders can be manually generated at the warehouse or from a sales order if kit components are out of stock. Product kits can also be disassembled at the POS register or at the warehouse.</p>
<p>When assembly or disassembly orders are created and processed, bill of materials (BOM) journals are generated to create the required inventory transactions.</p>
<p>For more information, see <a href="about-setting-up-retail-product-kits.md">About setting up retail product kits</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Cashiers can disassemble or reconfigure kits at the point of sale</p></td>
<td><p>Enhancements have been made to Retail POS and Retail Modern POS to handle kit products in various ways. For example, cashiers can disassemble kit products into their component products or make substitutions for individual products in the kit.</p>
<p>For more information, see About kit products.</p></td>
</tr>
<tr class="even">
<td><p>Cashiers can sell, return, or exchange kit products at the point of sale</p></td>
<td><p>Cashiers can sell, return, or exchange kit products in Retail POS and Retail Modern POS. Cashiers can not only ring up the kit product but also view the kit’s components in the transaction. Cashiers can accept the return and exchange of kits, and also exchange individual components of the kit.</p>
<p>For more information, see About kit products.</p></td>
</tr>
<tr class="odd">
<td><p>Redesign of the Retail loyalty feature</p></td>
<td><p>Previously, loyalty programs were configured by using a loyalty scheme. The loyalty scheme was assigned to a loyalty card, and included rules that were used to determine the loyalty points that could be earned or redeemed for that loyalty card.</p>
<p>In AX 2012 R3, the Retail loyalty program has been completely redesigned. The loyalty scheme still exists but is now mapped to the enhancements that were added to the loyalty feature. The new loyalty feature includes the following changes:</p>
<ul>
<li><p>Use loyalty programs to define the various loyalty events that you offer. You also define the loyalty tiers that apply to each loyalty program. You can assign price groups to a loyalty program to apply specific pricing.</p></li>
<li><p>Define multiple levels for your loyalty programs. Loyalty tiers are based on loyalty rewards. You can set criteria that customers must meet to qualify for each level, and also criteria that customers must meet to maintain their membership in a level.</p></li>
<li><p>Use date intervals to set up the duration of loyalty tiers. You can also use date intervals to define the time spans that apply to qualifying rules for loyalty tiers.</p></li>
<li><p>Loyalty cards are assigned to one or more loyalty programs. You can optionally assign a loyalty card to a customer. A loyalty customer can also be assigned to more than one loyalty card.</p></li>
<li><p>Loyalty cards can be used as a payment method.</p></li>
<li><p>Loyalty schemes are assigned to a loyalty program and to retail channels. You define loyalty earning rules and redemption rules as part of the loyalty scheme.</p></li>
<li><p>Loyalty rewards are defined as points. Loyalty rewards can be redeemed for products or used as payment for products.</p></li>
<li><p>Set up loyalty reward points. You define the type of reward point, the currency for amount-based rewards, and expiration dates. You also specify whether the reward is redeemable.</p></li>
<li><p>Retailers can manually adjust loyalty rewards. You can add loyalty points to accommodate or reward a customer. For example, you can move a customer up to the next tier. You can also remove loyalty points, such as when a product is returned.</p></li>
</ul>
<p>For more information, see <a href="set-up-loyalty-programs.md">Set up loyalty programs</a>.</p></td>
</tr>
<tr class="even">
<td><p>Issue loyalty cards at the point of sale</p></td>
<td><p>Previously, cashiers could use a customer’s loyalty card to add the customer to a transaction and credit the purchase to the customer’s loyalty account. Cashiers can now issue loyalty cards to customers in Retail POS and Retail Modern POS.</p>
<p>For more information, see <a href="set-up-loyalty-programs.md">Set up loyalty programs</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Enhancements for maintaining channel product attributes</p></td>
<td><p>These feature enhancements let you maintain attributes for products that are offered in a brick-and-mortar store, an online store, or through a call center catalog. You can add, modify, or remove product attributes, attribute values, and attribute metadata for any category in a retail product hierarchy that is assigned to a store or catalog. Child category nodes can inherit attribute data from their parent categories, and any attribute data that is inherited from a parent can be overridden at the level of the child category.</p>
<p>You can maintain product attributes at the level of the individual node. Alternatively, you can maintain product attributes in bulk by using Microsoft Excel. In this case, the following enhancements apply:</p>
<ul>
<li><p>Required attributes are easily identified in the Excel worksheet.</p></li>
<li><p>For attributes of the <strong>video</strong> or <strong>image</strong> type, a dialog box is available that lets you enter the URL where the attribute value is stored.</p></li>
<li><p>For attributes that have multiple values associated with them, a field is available that lets you select values from the appropriate value set.</p></li>
<li><p>Minimum and maximum attribute ranges are enforced for attribute values. Attributes for which minimum and maximum value ranges are not defined use the minimum and maximum value ranges that are defined for the system.</p></li>
<li><p>Upload the new channel attribute values for products that are offered in online stores or call center catalogs by using the catalog publishing feature.</p></li>
</ul>
<p>For more information, see <a href="add-and-update-product-attributes-for-retail-channels.md">Add and update product attributes for retail channels</a> and <a href="bulk-edit-product-attributes-by-using-excel.md">Bulk edit product attributes by using Excel</a>.</p></td>
</tr>
<tr class="even">
<td><p>Set up filters to improve searches for retail channel products</p></td>
<td><p>This feature lets you manually set up product filters to improve the search experience for retail products that are offered through any retail channel. Filters can be applied to any channel product attribute that is set up so that it can be refined. Filters that apply to products that are offered through an online store can now be set up either in SharePoint or manually in AX 2012 R3.</p>
<p>For more information, see <a href="add-and-update-product-attributes-for-retail-channels.md">Add and update product attributes for retail channels</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Configure screen layouts for Retail Modern POS</p></td>
<td><p>Microsoft Dynamics AX now includes Retail Modern POS, a Windows 8 POS app that can be used on Windows 8 tablets and computers. IT staff can configure screen layouts in Microsoft Dynamics AX and then send the layouts to the Windows 8 POS apps that are used at the organization’s stores.</p>
<p>For more information, see <a href="setting-up-screen-layouts.md">Setting up screen layouts</a>.</p></td>
</tr>
<tr class="even">
<td><p>Customer accounts can be accessed by retail channels across all locations</p></td>
<td><p>Customer accounts can be accessed by all retail channels across all locations, regardless of the organization’s legal entities. When cashiers add a customer to a transaction, they can select the customer from any of these accounts.</p></td>
</tr>
<tr class="odd">
<td><p>Set up affiliations and their discounts</p></td>
<td><p>Retail staff at the head office can set up affiliations for customers who are affiliated with a group, such as students or seniors. Discounts can be associated with these affiliations, and can be assigned to customer profiles and transactions in Retail POS and Retail Modern POS.</p>
<p>For more information, see <a href="setting-up-affiliations.md">Setting up affiliations</a>.</p></td>
</tr>
<tr class="even">
<td><p>Set up threshold discounts</p></td>
<td><p>You can now set up threshold discounts, which give customers a discount when a transaction’s total reaches one or more specified amounts. For example, you can create a threshold discount that gives a 10 percent discount for purchases over 100.00 and a flat 25.00 discount for purchases over 200.00.</p>
<p>For more information, see <a href="set-up-a-threshold-discount.md">Set up a threshold discount</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Category-based pricing</p></td>
<td><p>You can specify category-based pricing to more easily manage pricing for many products at the same time. For example, you can apply a markup of 10 percent to children’s shoes or mark down a particular vendor’s tennis rackets by 20 percent.</p>
<p>For more information, see <a href="set-category-based-prices.md">Set category-based prices</a>.</p></td>
</tr>
<tr class="even">
<td><p>More flexible retail discounts</p></td>
<td><p>You can use price groups to more easily create and manage prices and discounts for retail products. For example, you can use price groups to offer specific products at different prices to different groups of customers in different stores. A price group is the central point in a many-to-many relationship between prices and discounts on the one hand, and channels, catalogs, affiliations, and loyalty programs on the other hand.</p>
<p>For more information, see <a href="setting-up-prices-using-price-groups.md">Setting up prices using price groups</a>.</p></td>
</tr>
<tr class="odd">
<td><p>View information about discount transactions</p></td>
<td><p>You can now view detailed information about discount transactions. This information is available from the following locations:</p>
<ul>
<li><p>A command in the <strong>Retail store transactions</strong> form</p></li>
<li><p>A command in the <strong>Transactions</strong> form</p></li>
<li><p>The Business Intelligence (BI) cube</p></li>
</ul>
<p>For more information, see <a href="view-store-transactions.md">View store transactions</a>.</p></td>
</tr>
<tr class="even">
<td><p>Enhancements to buyer’s push</p></td>
<td><p>In Retail, the following enhancements have been made to the functionality for replenishing inventory by using buyer’s push:</p>
<ul>
<li><p>You can remove multiple product lines at the same time.</p></li>
<li><p>You can update quantities at the line level.</p></li>
</ul>
<p>For more information, see <a href="use-buyer-s-push-to-distribute-products.md">Use buyer's push to distribute products</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Enhancements to cross-docking</p></td>
<td><p>In Retail, the following enhancements have been made to the functionality for replenishing inventory by using cross-docking:</p>
<ul>
<li><p>Inventory transfers that are created by using cross-docking are marked and are linked to their purchase order. Therefore, these inventory transfers will not be used for any other purpose, and other products will not be used for the transfers.</p></li>
<li><p>You can update quantities at the line level.</p></li>
</ul>
<p>For more information, see <a href="use-cross-docking-to-distribute-products.md">Use cross docking to distribute products</a>.</p></td>
</tr>
<tr class="even">
<td><p>Export accounting information from Retail essentials</p></td>
<td><p>In Retail essentials, you can schedule the periodic export of accounting information, so that this information can be used by a third-party accounting program. A default chart of accounts is included that can be modified and mapped to the accounts in the destination accounting system.</p></td>
</tr>
<tr class="odd">
<td><p>Create return locations</p></td>
<td><p>You can specify that returned products are assigned to different return locations in inventory, depending on the cashier’s response to info codes that are displayed at the point of sale.</p>
<p>A return location can be a store, a warehouse, a location in a store or warehouse, or a specific pallet, depending on the locations that your organization has set up. You can map each return location to one or more <strong>Retail</strong> info codes and <strong>Sales and marketing</strong> reason codes.</p></td>
</tr>
</tbody>
</table>


## Retail essentials

Retail essentials provides a new, retail-centric configuration option for Microsoft Dynamics AX. Retail essentials provides a simplified, streamlined user experience that is optimized for organizations that will use only the retail management functions of Microsoft Dynamics AX.

Retail essentials is ideal for companies with less complex requirements that need to manage store-only environments. In this configuration, access to typical Microsoft Dynamics AX functions is limited. Additionally, omni-channel retail capabilities such as e-commerce are not available.

The following sections describe the highlights of the retail-centric experience.

## Retail-centric user interface

Retail essentials includes just enough functionality to enable POS operations, provide retail user rights, and perform other functions that retailers require. Users of Retail essentials see only one area page when they open AX 2012 R3. This area page is designed to provide access to all the components that are required for retail management from one location. Users do not have to be familiar with other areas of the product or access other modules. Additionally, some forms have been simplified so that they show only fields, functions, and labels that are relevant to retail.

## Easier deployment

A Retail deployment requires setup in many areas that aren't directly related to retail. By contrast, the initialization process for Retail essentials automatically configures reference data in over 40 areas of Microsoft Dynamics AX. Therefore, deployment time is significantly reduced, and forms and fields that are used only for initial setup can be omitted.

## Integration with existing accounting systems

If you already have an accounting system, Retail essentials makes it easy to provide critical financial data to the primary accounting system. For example, you can use accounting export functionality to provide account-level sales data to your accounting system. By using built-in accounts, you can create profiles to map totals from Retail essentials to an account in the accounting system. At required intervals, account activity can be exported to a directory that is available to the accounting system. The accounting system can then obtain the totals and post to the appropriate accounts.

## Capability to expand the system

Retail essentials can support your future software requirements and new business endeavors. Management of multiple systems in a complex environment can be expensive, and systems become obsolete over time. By using Retail essentials, you can decide when and how system consolidation occurs.

Retail essentials has Microsoft Dynamics AX at its core. All the capabilities that are provided through Microsoft Dynamics AX are available to Retail essentials, and you can easily enable these capabilities by modifying the user interface.

## Data migration from another retail system

Retail essentials uses the Microsoft Dynamics AX Data Import/Export Framework to provide an easy way to import retail-specific data. By default, entities are mapped for users who are migrating from Microsoft Dynamics Retail Management System (RMS). To import RMS data into Retail essentials, you must add the Data Import/Export Framework to your Retail essentials installation, create an ODBC connection to the RMS headquarters database, then use Data Import/Export Framework entities to migrate the data. For more information, see [Migrate data from Microsoft Dynamics Retail Management System (Retail essentials)](migrate-data-from-microsoft-dynamics-retail-management-system-retail-essentials.md).

To migrate data from a third-party retail system, you must create entity mappings that are specific to the data in the third-party system. However, the architecture is optimized so that this data can be mapped to staging tables in Retail essentials. The data import/export framework then creates the data correctly. For more information, see [Use the Data import/export framework to migrate data (Retail essentials)](use-the-data-import-export-framework-to-migrate-data-retail-essentials.md).

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
<td><p>Prompt for a reason code when the cashier opens the cash register drawer without performing a sale transaction</p></td>
<td><p>You can set up reason codes and then capture a reason code when the cashier opens the register without performing a sales transaction. You can define reason codes in the <strong>Info codes</strong> form. A new field on the <strong>Info codes</strong> tab in the <strong>POS functionality profile</strong> form lets you set the reason code that is triggered when the open drawer operation occurs. When the cashier opens the drawer for a purpose other than a sale, the cashier is prompted to select a value or a reason subcode.</p>
<p>For more information, see <a href="about-info-codes-retail.md">About info codes (Retail)</a>.</p></td>
</tr>
<tr class="even">
<td><p>Post store transactions from statements based on the end of the business day instead of the calendar day</p></td>
<td><p>This feature adds an option for posting end-of-day statements for stores that have extended business hours. You can now calculate end-of-day transactions for statement processing based on the time that the store closes. However, in earlier releases, you could only post the statement based on the calendar day. If your store operating hours extended past 12:00 AM, two sales orders are created when you posted the statement. One sales order was created for sales transactions that occurred before 12:00 AM, and the other sales order was created for the transactions that occurred between 12:00 AM and the end of the business day.</p>
<p>This feature lets you configure your statement posting process so that you can post the statements based on the end of the business day instead of the end of the calendar day.</p>
<p>For more information, see <a href="about-statements.md">About statements</a>.</p></td>
</tr>
<tr class="odd">
<td><p>You can use a new statement method to calculate statements by shift</p></td>
<td><p>This feature adds a statement method so that stores can calculate statements by shift. When this option is selected for the store and the statement is generated, the transaction lines are summarized by payment method and shift. The summarized transaction lines are displayed in the <strong>Statements</strong> form, and the shifts are listed for each line. You can also select the <strong>Split by Statement method</strong> on the <strong>Statement/closing</strong> FastTab in the <strong>Stores</strong> form to generate a separate statement for each shift.</p>
<p>For more information, see <a href="about-statements.md">About statements</a>.</p></td>
</tr>
<tr class="even">
<td><p>Passwords can now be changed and reset in Retail POS</p></td>
<td><p>In Retail POS, the following enhancements have been made:</p>
<ul>
<li><p>A cashier can change his or her password.</p></li>
<li><p>A cashier can have his or her password reset. For example, a cashier might forget his or her password.</p></li>
</ul>
<p>There are minimum requirements for passwords, such as length and complexity.</p></td>
</tr>
<tr class="odd">
<td><p>Cashiers can view additional customer account information in Retail POS</p></td>
<td><p>In Retail POS, the following enhancements have been made:</p>
<ul>
<li><p>Cashiers can view customer account balances.</p></li>
<li><p>Cashiers can view invoice accounts, if invoice accounts are present.</p></li>
</ul></td>
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
<td><p>Improvements for point of sale (POS) hardware</p></td>
<td><p>The following improvements for POS hardware have been made:</p>
<ul>
<li><p>Support for a second cash drawer and multiple shifts</p></li>
<li><p>Support for a second POS printer</p></li>
<li><p>Support for signature capture</p></li>
<li><p>Support for dual scanners</p></li>
</ul>
<p>For more information, see <a href="set-up-hardware-profiles.md">Set up hardware profiles</a>.</p></td>
</tr>
<tr class="even">
<td><p>Group attributes and attribute groups, and apply them to products and categories in a catalog</p></td>
<td><p>This feature lets users enhance their retail catalog offerings by including attributes for products in the catalog. You can create attribute groups for a set of defined attributes, and add the attribute groups to a catalog navigation category or a retail channel. Retail supports system properties and attributes, user-defined attributes, and rich media attributes, such as videos, images, or HTML text.</p>
<p>For more information, see <a href="setting-up-retail-product-catalogs.md">Setting up retail product catalogs</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Setup improvements for Retail components</p></td>
<td><p>The following improvements have been made to the Setup experience for Retail components:</p>
<ul>
<li><p>The Retail Store Connect message database and service account can be configured in Setup.</p></li>
<li><p>.NET Business Connector is automatically installed together with Retail Transaction Service.</p></li>
<li><p>Online and offline databases can be configured in Setup when you install the Retail Store Database Utility.</p></li>
<li><p>Retail Online Channel is a new component that can be installed in AX 2012 R2.</p></li>
<li><p>Retail store components can be deployed through Microsoft System Center.</p></li>
</ul>
<p>For more information, see <a href="install-retail-components.md">Install retail components</a>.</p></td>
</tr>
<tr class="even">
<td><p>Improved Retail POS experience</p></td>
<td><p>Smarter search functionality makes Retail POS much easier and faster to use. Product, category, and customer lookups have been brought together into one place. Additionally, a search algorithm determines how data that is swiped, scanned, or manually entered is used, based on the input method and matching search results.</p>
<p>For more information, see the following topics in Retail POS Help:</p>
<ul>
<li><p>“Check the price or quantity of a product”</p></li>
<li><p>“View or edit customer information”</p></li>
</ul>
<p>Preset themes makes the POS screen easier to use and more enjoyable to work with. For more information, see <a href="set-up-visual-profiles.md">Set up visual profiles</a>.</p>
<p>Employees can log on to POS by swiping employee cards. For more information, see “Start or exit Retail POS” in Retail POS Help.</p></td>
</tr>
<tr class="odd">
<td><p>Upgrade to global store and staff IDs</p></td>
<td><p>The values for store and staff IDs are now stored in global variables. Global variables are unique across all companies in a partition. Tasks have been added to the Preprocessing data checklist to resolve this schema change from Microsoft Dynamics AX 2009 for Retail.</p>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="setting-up-retail-stores.md">Setting up retail stores</a></p></li>
<li><p><a href="setting-up-staff.md">Setting up staff</a></p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Fulfill online retail orders in Microsoft Dynamics AX</p></td>
<td><p>Customer orders and order fulfillment have been expanded to include the following scenarios:</p>
<ul>
<li><p>An order is created online and picked up in a store.</p></li>
<li><p>An order is created online and shipped.</p></li>
<li><p>An order is created in a store and picked up in a store.</p></li>
<li><p>An order is created in a store and shipped.</p></li>
</ul>
<p>These orders are fulfilled in Microsoft Dynamics AX, and customers can be notified via email during various stages of order fulfillment.</p>
<p>For more information, see the following topics:</p>
<ul>
<li><p>“Sales orders” in Retail POS Help</p></li>
<li><p><a href="process-sales-orders-overview.md">Process sales orders overview</a></p></li>
<li><p><a href="setting-up-email-receipts.md">Setting up email receipts</a></p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Support catalog management for the <strong>Retail</strong> module</p></td>
<td><p>The <strong>Retail</strong> module now uses the catalog management feature that was introduced in Microsoft Dynamics AX.</p>
<p>You can create one or more retail catalogs. Each catalog includes navigational categories, and each navigational category can include one or more product offerings that are assigned to a product assortment. Each offering can be enhanced by attributes that are included for the products at either the category level or the product level. You can assign the catalog to one or more retail channels.</p>
<p>After a catalog is validated, reviewed, approved, and finally published, the catalog products are displayed as listings on the channels that the catalog is assigned to. Any changes to the catalog products can be reflected in the channels.</p>
<p>For more information, see <a href="setting-up-retail-product-catalogs.md">Setting up retail product catalogs</a>.</p></td>
</tr>
<tr class="even">
<td><p>Customer-facing device support</p></td>
<td><p>Changes to the POS and EFT (electronic funds transfer) plug-in provide out-of-box support for customer-facing devices in the US. The changes also support partner plug-ins that give partners a head start in developing their own solutions for this kind of device.</p>
<p>For more information, see <a href="set-up-hardware-profiles.md">Set up hardware profiles</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Time clock</p></td>
<td><p>A time clock can be used to keep track of time and attendance for retail store employees. This feature consists of a time clock in Retail POS, manager viewing capability in Retail POS, and record keeping in Microsoft Dynamics AX.</p>
<p>For more information, see “Use the time clock” in Retail POS Help.</p></td>
</tr>
<tr class="even">
<td><p>Improvements to inventory management</p></td>
<td><p>The usability of the following inventory features has been improved:</p>
<ul>
<li><p>Creating and maintaining product variants</p></li>
<li><p>The <strong>Add products</strong> dialog box</p></li>
<li><p>Creating bar codes and bar code masks</p></li>
<li><p>The mass update worksheet</p></li>
</ul>
<p>For more information, see the following topics:</p>
<ul>
<li><p><a href="setting-up-retail-products.md">Setting up retail products</a></p></li>
<li><p><a href="setting-up-retail-product-catalogs.md">Setting up retail product catalogs</a></p></li>
<li><p><a href="setting-up-bar-codes.md">Setting up bar codes</a></p></li>
<li><p><a href="manage-retail-product-catalogs-overview.md">Manage retail product catalogs overview</a></p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>The store locator service was added for retail and online stores</p></td>
<td><p>The store locator service enables queries about item availability in stores within a specified distance. This capability can be used when, for example, an online shopper wants to pick up the item in a physical store instead of having it shipped.</p>
<p>Results can be limited to a specific subset of stores. For example, when a shopper queries item inventory for a hat in an online store for fashion clothing, the results can be configured to include inventory only from specific stores. Additionally, the results can be filtered based on distance from a location that the shopper specifies.</p>
<p>For more information, see <a href="set-up-store-locator-groups-in-retail.md">Set up store locator groups in Retail</a>.</p></td>
</tr>
<tr class="even">
<td><p>Customer orders from online stores</p></td>
<td><p>Customer orders in the <strong>Retail</strong> module of Microsoft Dynamics AX and in Retail POS have been enhanced to support online stores. Orders that customers create in an online store can be shipped to the customers or picked up in brick-and-mortar stores. Email notifications are sent during the sales and shipping processes. Enhancements have also been made to the recall order and order list features.</p>
<p>For more information, see the following topics:</p>
<ul>
<li><p>“Sales orders” in Retail POS Help</p></li>
<li><p><a href="process-sales-orders-overview.md">Process sales orders overview</a></p></li>
<li><p><a href="setting-up-email-receipts.md">Setting up email receipts</a></p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Online marketplaces</p></td>
<td><p>Retailers can now set up and configure an online marketplace as a retail channel directly in Microsoft Dynamics AX. (Previously, this functionality was offered only on the web in Commerce Services.) Retailers can use online marketplaces to easily sell products online through established marketplaces, such as eBay and Amazon.com. Catalogs and product listings are centrally managed, and sales orders flow seamlessly back into Microsoft Dynamics AX for processing.</p>
<p>For more information, see <a href="usa-setting-up-online-marketplaces.md">(USA) Setting up online marketplaces</a>.</p></td>
</tr>
<tr class="even">
<td><p>Enhanced tracing and diagnostics</p></td>
<td><p>In earlier versions, Retail POS wrote any errors or tracing information to the RetailLog table in the POS database. In this release, the tracing has been separated into two segments:</p>
<ul>
<li><p><strong>System diagnostics</strong> – Retail POS uses the standard .NET diagnostics functionality, and the level of logging is controlled in the POS.exe.config file. By default, the log file is created in the user temp folder under RetailLogs. Logging can be configured to write an XML log file or the Windows event log.</p></li>
<li><p><strong>Audit log</strong> – For auditing purposes, Retail POS writes events such as logons and manager overrides to the RetailLog table. The auditing can be turned on in the functionality profile.</p></li>
</ul>
<p>For more information, see <a href="configuring-parameters-and-initial-settings.md">Configuring parameters and initial settings</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Additional product details are available in Retail POS</p></td>
<td><p>More details about products are available to cashiers in Retail POS. These details include product attributes, bar codes, issue dates, and pictures.</p>
<p>For more information, see “View information about a product” in Retail POS Help.</p></td>
</tr>
<tr class="even">
<td><p>View and edit customer information in Retail POS</p></td>
<td><p>Cashiers can view and modify information about a customer in Retail POS. This information includes the customer’s address, telephone number, and email address.</p>
<p>For more information, see the following topics in Retail POS Help:</p>
<ul>
<li><p>“View a customer’s purchase history”</p></li>
<li><p>“View or edit customer information”</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Additional customer information in Retail POS</p></td>
<td><p>Additional customer information is available to cashiers in Retail POS. This information includes an enhanced history of purchases for a customer, and also additional details about a customer, such as contact information, the customer’s currency and language, and a picture.</p>
<p>For more information, see <a href="point-of-sale.md">Point of Sale</a>.</p></td>
</tr>
<tr class="even">
<td><p>Component names have changed</p></td>
<td><p>Retail Store Connect is now Commerce Data Exchange: Synch Service. Retail Transaction Service is now Commerce Data Exchange: Real-time Service.</p>
<p>For more information, see <a href="commerce-data-exchange-synch-service.md">Commerce Data Exchange: Synch Service</a> and <a href="commerce-data-exchange-real-time-service.md">Commerce Data Exchange: Real-time Service</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Enhance product offerings in retail catalogs</p></td>
<td><p>This feature lets users enhance their retail catalog offerings.</p>
<ul>
<li><p>A catalog manager can enrich products by adding descriptions, specifications, product relationships, images, videos, rich text content, and other data.</p></li>
<li><p>You can use attribute groups to apply multiple attributes to products in a catalog.</p></li>
<li><p>The catalog is based on a highly configurable attribute schema at the product, category, or channel level.</p></li>
<li><p>Enhancements can be shared among channels or targeted to a specific channel.</p></li>
</ul>
<p>For more information, see <a href="about-retail-product-catalogs.md">About retail product catalogs</a>.</p></td>
</tr>
<tr class="even">
<td><p>Publish retail product catalogs to create product listings in online channels</p></td>
<td><p>This feature lets you create a retail product catalog in Microsoft Dynamics AX. You can also enhance the product offerings by adding attributes, images, videos, and so on, and then publish the catalog. When the catalog is published, product listings are generated in one or more online channels, such as an online store.</p>
<p>You can publish catalogs to one or more channels by using one of the following methods:</p>
<ul>
<li><p>Manually publish a catalog.</p></li>
<li><p>Auto-publish a catalog, based on the effective date of the catalog.</p></li>
</ul>
<p>For more information, see <a href="about-retail-product-catalogs.md">About retail product catalogs</a>.</p>
<div class="alert">

> [!NOTE]
> <P>Before you can publish retail product catalogs, a catalog publishing job must be scheduled via the Microsoft Dynamics AX batch job framework.</P>


</div></td>
</tr>
<tr class="odd">
<td><p>The existing pricing service for POS was extended to include online stores</p></td>
<td><p>The commerce runtime provides omni-channel commerce capability that has uniform extensibility across channels. The commerce runtime enables the online storefront, Retail POS, and back office business calculations and business processes. The runtime also supports more than 30 markets and is highly extensible to fill in gaps in a customer’s ERP implementation.</p>
<p>The commerce runtime includes the following components:</p>
<ul>
<li><p>Pricing service</p></li>
<li><p>Tax service</p></li>
<li><p>Shipping service</p></li>
<li><p>Shopping card and checkout</p></li>
<li><p>Store locator service</p></li>
<li><p>Order service</p></li>
<li><p>Address service</p></li>
</ul>
<p>The pricing service feature gives an online store the same advanced pricing and discount capabilities that are currently available for Retail POS. The pricing service is enabled when a retail product catalog is published to the online store. The catalog products and their prices are displayed to customers who browse for products in the online store. Any discounts that are available for the products are calculated and displayed after the products are added to the shopping cart at checkout time.</p>
<p>For more information, see <a href="commerce-runtime.md">Commerce Runtime</a>.</p></td>
</tr>
<tr class="even">
<td><p>Retail reporting enhancements</p></td>
<td><p>AX 2012 R2 includes a new dedicated Retail cube that provides business intelligence data to help retailers make business decisions. You can customize the new Retail cube by adding data sources, measures, dimensions, calculations, key performance indicators (KPIs), and so on. You can also define your own reports by using Microsoft SQL Server Reporting Services or Microsoft Excel.</p>
<p>The following Retail reports have been added or enhanced:</p>
<ul>
<li><p>Inventory Turnover and GMROII by product</p></li>
<li><p>Inventory Turnover and GMROII by category</p></li>
<li><p>Retail store metrics</p></li>
<li><p>Sales performance by products</p></li>
<li><p>Sales performance by retail product category</p></li>
<li><p>Sales performance by category by store</p></li>
<li><p>Performance by terminal</p></li>
<li><p>Top 10 OU performers in current year</p></li>
<li><p>Trend by operating unit</p></li>
<li><p>Sales comparison year over year by operating unit</p></li>
</ul>
<p>The following KPIs have been added:</p>
<ul>
<li><p>Average ticket size</p></li>
<li><p>COGS</p></li>
<li><p>Days of inventory amount</p></li>
<li><p>Days of inventory quantity</p></li>
<li><p>GMROII</p></li>
<li><p>Gross margin</p></li>
<li><p>Gross margin percentage</p></li>
<li><p>Inventory turn amount</p></li>
<li><p>Inventory turn quantity</p></li>
<li><p>Inventory turnover</p></li>
<li><p>Months of inventory amount</p></li>
<li><p>Months of inventory quantity</p></li>
<li><p>Sales by hour</p></li>
<li><p>Sale per unit area</p></li>
<li><p>Total customers</p></li>
<li><p>Total returns</p></li>
<li><p>Total sales</p></li>
<li><p>Week of inventory amount</p></li>
</ul>
<p>For more information, see <a href="retail-cube-retailcube-for-microsoft-dynamics-ax-2012-r2-and-r3.md">Retail cube (RetailCube) for Microsoft Dynamics AX 2012 R2 and R3</a> and <a href="retail-reports.md">Retail reports</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Multi-version POS support during upgrade</p></td>
<td><p>To upgrade retail functionality, you must redeploy (replace and reconfigure) the earlier POS software on each terminal in each store. You must perform this redeployment during a tightly constrained time window to avoid disrupting retail activities. Although earlier releases required that all stores be upgraded at the same time, AX 2012 R2 supports operations that use two versions of Microsoft Dynamics AX POS software at the same time. Multi-version support lets upgrade administrators upgrade one store at a time while maintaining regular operations in stores that are still awaiting upgrade.</p>
<p>For more information, see <a href="scenario-upgrade-a-retail-system.md">Scenario: Upgrade a Retail system</a>.</p></td>
</tr>
<tr class="even">
<td><p>Manually enter a coupon code for discount offers</p></td>
<td><p>This feature lets you manually enter a discount code for discount offers without having to create a campaign. Discount codes can be applied to both brick-and-mortar stores and online stores. If you create a discount code for a campaign and enter the discount code manually, the system does not use number sequences and bar codes to automatically generate the code. Instead, the system uses the manual code.</p>
<p>For more information, see <a href="setting-up-price-adjustments-and-discounts.md">Setting up price adjustments and discounts</a>. Additionally, see the post <a href="https://blogs.msdn.com/b/axsupport/archive/2013/01/25/ax-2012-r2-for-retail-setting-up-discounts-coupons-with-bar-codes-for-scanning-into-pos.aspx">AX 2012 R2 for Retail - Setting up discount coupons with bar codes for scanning into POS</a> on the Microsoft Dynamics AX Support blog.</p></td>
</tr>
<tr class="odd">
<td><p>An inquiry form was added, so that you can view transactions for online stores</p></td>
<td><p>This feature enhances the functionality for transaction inquiries and adds a new inquiry form for online store transactions. You can view all transactions for a retail store by using the existing inquiry form. Then you can view all transactions for an online store by using the new inquiry form for online stores.</p>
<p>For more information, see <a href="view-inquiries-and-reports-overview.md">View inquiries and reports overview</a>.</p></td>
</tr>
</tbody>
</table>


For more information about the enhancements for Retail in Microsoft Dynamics AX 2012 R2, see [CMO Webcast: Microsoft Dynamics AX 2012 R2 Retail Enhancements](https://msevents.microsoft.com/cui/eventdetail.aspx?culture=en-us%26eventid=1032542150%26countrycode=us).

## E-commerce investments in R2

AX 2012 R2 includes a suite of features that help you deploy, manage, and customize an online sales channel that is fully integrated with Microsoft Dynamics AX. E-commerce investments include two starter online stores which are built on Microsoft SharePoint 2013 Products, developer tools, and administrative and runtime components that integrate the online channel with Microsoft Dynamics AX.

By using this new suite of e-commerce features, you can centrally manage products, merchandising, and order fulfillment for all aspects of your online sales channel in Microsoft Dynamics AX. The runtime components are designed to deliver content and retail services in a scalable way. The starter online store (the Contoso electronics store) accelerates the development of highly customized online channels. The starter online store includes the patterns and best practices that are required for production-ready deployments. These patterns and best practices include powerful, search-driven, adaptive experiences that are offered by the SharePoint 2013 for Internet Sites (FIS) platform.

## E-commerce centralized management

The following table shows the features in AX 2012 R2 that can help you manage your online channel.

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
<td><p>Channel management and publishing</p></td>
<td><p>Channel management lets you define an organizational entity in Microsoft Dynamics AX and associate that entity with an online website. Therefore, you can manage catalogs, prices, promotions, and other content for a brick-and-mortar channel and an online channel in one place. Channel management also lets you define default properties for a channel, such as a default profile for an anonymous shopper, the navigation hierarchy, and payment processing configurations.</p>
<p>Channel publishing lets you publish data and properties for a channel to a website, regardless of where that website is hosted. The data and properties that you can publish include the navigation hierarchy. For example, all Microsoft Dynamics AX administration for a Contoso channel is performed in offices that are located in Seattle, but the data center that hosts Contoso.com is located in Chicago. In this case, administrators can seamlessly manage and publish data from Microsoft Dynamics AX to the data center.</p></td>
</tr>
<tr class="even">
<td><p>Catalog management and publishing, and attribute enhancement</p></td>
<td><p>Catalog management in this version of Microsoft Dynamics AX lets you create product collections, and target those collections at a specific channel or a promotion in a channel. For example, Contoso.com, an electronics retailer, creates a base catalog for all the electronics that are sold through its online channel. The catalog manager can then create a subcatalog for 60 items that will go on sale for a special promotion during the month of June. A single channel can have multiple catalogs. Likewise, one product can be located in multiple catalogs, and product details such as a promotion price can be determined by date.</p>
<p>Catalog publishing lets a catalog manager publish all catalog data to a specific endpoint that was defined through the channel management process that was described earlier. This data includes rich attributes and merchandising content.</p>
<p>Attribute enhancement lets you create attributes and rich content, so that you can market products in the context of the intended sales channel. The attributes and rich content that you can create includes images, extended descriptions, features, and specifications.</p></td>
</tr>
<tr class="odd">
<td><p>Navigation hierarchies and category attributes</p></td>
<td><p>Navigation hierarchies provide a logical taxonomy of categories and subcategories, so that you can group products in a manner that promotes discoverability for users who browse your online store. For example, Contoso.com creates a <strong>Products</strong> category that includes the <strong>Televisions</strong>, <strong>Computers &amp; Tablets</strong>, <strong>Modern Phones</strong>, and <strong>Video Games</strong> subcategories. Navigation hierarchies add an organizing structure to an already rich set of retail categories that are optimized for administrative and reporting purposes.</p>
<p>Category attributes provide a schema for logically describing products in a category. Category attributes enhance product refinement, filtering, and search optimization. For example, Contoso.com offers 40 different televisions. The catalog manager assigns category attributes such as <strong>LCD</strong>, <strong>Plasma</strong>, and <strong>Rear Projection</strong> to refine the category groupings even more, and to reduce duplication of effort and administrative overheard when the catalog is updated. Category attributes can also be configured to provide the automatic product filter groups (refinements) on the landing page of each category. For example, the catalog manager can configure refinement groups such as <strong>Television price</strong>, <strong>Television brand</strong>, and <strong>Screen size</strong>. These refinements can then be displayed on the website as a filter or a search refinement option for shoppers.</p></td>
</tr>
<tr class="even">
<td><p>Deployment checklist</p></td>
<td><p>AX 2012 R2 includes a setup checklist for online stores. This checklist guides you through the process of setting up and configuring services and features for an online store. You can view the checklist in the AX 2012 R2 client by clicking <strong>Retail</strong> &gt; <strong>Setup</strong> &gt; <strong>Online store setup checklist</strong>.</p></td>
</tr>
</tbody>
</table>


## Commerce runtime

The commerce runtime is a significant new feature of Retail in AX 2012 R2. The commerce runtime was engineered to support scalable integration of remote sales channels with Microsoft Dynamics AX in near real time. For more information about this component, see [Commerce Runtime](commerce-runtime.md)

## Starter online store

The Contoso starter online store accelerates implementation of an online channel by providing the code, services, forms, and best practices that you can use to develop a highly customized and branded online store. Out of box, the starter online store provides the major features and functionality that are typically required for an online channel. These starter features can be customized and adapted to meet specific requirements.

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
<td><p>Major features of the starter online store</p></td>
<td><ul>
<li><p>A homepage framework that helps you develop a professional online presence</p></li>
<li><p>A website navigation scheme that is linked to the navigation hierarchy in Microsoft Dynamics AX</p></li>
<li><p>A default category landing page that can display products in response to navigation actions</p></li>
<li><p>Automatic product refinement on category landing pages that are linked to category attributes that are managed in Microsoft Dynamics AX</p></li>
<li><p>A local search service for searching the site</p></li>
<li><p>Search engine optimization for searching the web</p></li>
<li><p>A product details page that displays product enhancements that are managed in Microsoft Dynamics AX, such as images, extended descriptions, features, and specifications</p></li>
<li><p>A store locator service that includes “pick-up-in-store” functionality that is integrated with Bing maps</p></li>
<li><p>Order shipping and line-by-line shipping controls</p></li>
<li><p>Payment processing that is integrated with the Microsoft Dynamics AX online payment service (available only in the U.S.)</p></li>
<li><p>A complete shopping cart interface that includes mini-cart, full cart, and order summary views</p></li>
<li><p>A default order confirmation page</p></li>
<li><p>Online account management, which includes Facebook integration, order history, and address management</p></li>
</ul></td>
</tr>
</tbody>
</table>


## What’s new in Microsoft Dynamics AX 2012 Feature Pack

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
<td><p>Categorize retail products</p></td>
<td><p>Retail products can now be categorized through the category management feature in AX 2012. You can categorize products by using a category hierarchy that is <em>n</em> levels deep. Multiple category hierarchies are supported for special circumstances.</p>
<p>You can more efficiently categorize your retail products. For example, you can create one main category hierarchy for all your retail products, and one or more supplemental category hierarchies for product promotions, vendor products, and so on.</p>
<p>Attributes that are assigned at the category level can be applied to all products in the category. Values that are assigned to a parent category can be inherited by a child category.</p></td>
</tr>
<tr class="even">
<td><p>Product assortments</p></td>
<td><p>You can use the enhancements to products, category hierarchies, and organization hierarchies to more efficiently create and maintain assortments. A status and effective date were added. A new batch job was added for periodic updates of changes that are made to an assortment.</p>
<p>These enhancements let you centrally manage all retail products across legal entities. You can perform the following tasks:</p>
<ul>
<li><p>Efficiently group the stores and channels that assortments are assigned to by using the organization model.</p></li>
<li><p>Create multiple assortments by using category hierarchies.</p></li>
<li><p>Exclude selected products from an assortment.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Retail channels</p></td>
<td><p>A retail channel includes the retail brick-and-mortar store, online store, and online marketplace. Retail channels are a subtype of operating units.</p>
<p>Use the organization hierarchy to model your store relationships and retail channels.</p></td>
</tr>
<tr class="even">
<td><p>Price groups</p></td>
<td><p>Pricing for stores is accomplished by using price groups.</p>
<p>Trade agreements are configured by using price groups. Microsoft Dynamics AX for Retail POS uses trade agreements and the price groups that are assigned to the trade agreements to determine the base price for a product.</p>
<p>Price groups provide more flexibility when you set up product pricing. You can configure multiple price groups to meet the requirements of your various products and retail channels, and then assign one or more price groups to your stores.</p></td>
</tr>
<tr class="odd">
<td><p>Periodic discounts</p></td>
<td><p>AX 2012 Feature Pack includes the following enhancements:</p>
<ul>
<li><p>Concurrency rules let you apply multiple discounts, such as exclusive, best price, and compounded discounts.</p></li>
<li><p>You can define periodic discounts by category, product, or product variant.</p></li>
<li><p>You can use discount codes (coupons) for online promotions in campaigns.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Customer orders</p></td>
<td><p>Two types of customer orders, quotations and sales orders, are supported in the following scenarios:</p>
<ul>
<li><p>An order is created at a store and picked up at the same store.</p></li>
<li><p>An order is created at a store and picked up at a different store.</p></li>
<li><p>An order is created at a store and shipped to the customer.</p></li>
<li><p>An order is created online and picked up at a store.</p></li>
<li><p>Picking and packing workflows are started and completed in Retail POS.</p></li>
<li><p>Order returns or cancellations are processed in Retail POS.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Inventory</p></td>
<td><p>The <strong>Add products</strong> form has been improved to support multiple product hierarchies and a new dialog box for selecting a variant matrix. You can also enter quantity and dimension values. Additionally, you can use a new “mass update worksheet” to make bulk updates to product properties.</p></td>
</tr>
<tr class="even">
<td><p>Staff management</p></td>
<td><p>Retail staff in both the back office and the store are now integrated with the core <strong>Human resources</strong> module as workers. To simplify management of Retail POS permissions across the organization, jobs are associated with Retail POS permission groups. You can define a few standard jobs in your retail organization and have standard permissions for each job. All workers that you hire then automatically have the standard permissions. Additionally, you can associate workers with stores. Therefore, you can restrict a retail staff logon to a single store, a group of stores, or any store in the enterprise.</p></td>
</tr>
<tr class="odd">
<td><p>Store inventory</p></td>
<td><p>Retail store inventory has had major architectural changes to better suit native document support and to create a foundation for stronger retail store inventory functionality in the future. Retail store inventory (RSI) was originally a third-party handheld solution. The solution was then adapted into a module that was included in Microsoft Dynamics AX 2012 for Retail. RSI supported basic picking, receiving, and inventory counting, but was not optimized for Microsoft Dynamics AX. RSI required steps that made the solution less streamlined than other features of Retail.</p>
<p>For AX 2012, RSI is no longer a stand-alone module. The solution is now more intuitive, efficient, and adaptable, and provides a stronger foundation for developing end-to-end store inventory management. Additionally, functional improvements that have been made in Enterprise Portal for Microsoft Dynamics AX and Retail POS make data entry more intuitive and faster.</p></td>
</tr>
<tr class="even">
<td><p>End-of-day improvements</p></td>
<td><p>To help with auditing for loss prevention, retailers rely on a several different processes. Two of these will be addressed in this release:</p>
<ul>
<li><p>You can assign a specific till to a specific cashier, so that one person is responsible for the till. For example, if a cashier returns from a break and is now assigned to a different register, the cashier must physically move the till, and the cashier’s shift must follow him or her. This scenario is known as <em>floating till</em>.</p></li>
<li><p>You can remove the till from the cash drawer without closing the shift, so that the money can be counted in a back room instead of on the sales floor. This scenario is known as <em>blind close</em>. In a blind close, multiple registers can be closed from one physical location. A single person can then count cash at the end of the day, and close all registers in a back room or another location that is away from the sales floor.</p></li>
</ul>
<p>In addition to these key processes, several other improvements are addressed in this release:</p>
<ul>
<li><p>Important usability improvements have been made, such as an option to require starting and ending amounts before a shift can be closed. Additionally, there is an option to prompt for starting and ending amounts in Retail POS.</p></li>
<li><p>A ZZ-report has been added.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Global address book</p></td>
<td><p>Addresses and contact information for retail entities have been migrated to addresses and contact information for parties.</p>
<p>The global address book significantly changes the data structures and relationships of the underlying data for addresses and contact information. For example, when a customer is created in Retail POS, the customer and party are both created, as are the associated addresses and contact information (party locations).</p></td>
</tr>
<tr class="even">
<td><p>Reporting and analytics</p></td>
<td><p>Microsoft Dynamics AX includes a sales cube that provides insight into sales performance:</p>
<p><strong>Merchandizing analytics</strong></p>
<ul>
<li><p>Sales performance by retail category</p></li>
<li><p>Sales performance by product</p></li>
</ul>
<p><strong>Retail channel analytics</strong></p>
<ul>
<li><p>Sales performance by retail channel</p></li>
</ul>
<p><strong>Store analytics</strong></p>
<ul>
<li><p>Store sales by worker</p></li>
<li><p>Store sales by hour</p></li>
<li><p>Store sales performance report</p></li>
</ul>
<p><strong>Operating unit analytics</strong></p>
<ul>
<li><p>Operating unit sales performance</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Sites Services for Microsoft Dynamics ERP</p></td>
<td><p>Microsoft Dynamics AX includes five Sites Services solutions that can streamline and speed business processes:</p>
<ul>
<li><p>Advertise promotions</p></li>
<li><p>Online case request</p></li>
<li><p>Human resources recruitment</p></li>
<li><p>Request for quotation</p></li>
<li><p>Unsolicited vendor registration</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Store database</p></td>
<td><p>An offline feature has been added to the store database to support a central database in the retail store. An offline database can also be used locally to reduce downtime if a network failure occurs, and in scenarios where a register must be used offsite or in a sidewalk sale.</p></td>
</tr>
<tr class="odd">
<td><p>Commerce Services for Microsoft Dynamics ERP</p></td>
<td><p>Enhancements have been made to Commerce Services:</p>
<ul>
<li><p>Retail channels</p></li>
<li><p>Assortments</p></li>
<li><p>Categories</p></li>
<li><p>Buy online and pick up in store</p></li>
<li><p>Sales tax on shipping</p></li>
<li><p>Retail security roles</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Sales tax on shipping</p></td>
<td><p>The sales tax feature extends existing functionality to support sales tax on shipping charges.</p></td>
</tr>
<tr class="odd">
<td><p>Retail Store Connect</p></td>
<td><p>The operation and configuration of scheduler jobs have been separated. Therefore, it is easier to configure different batch schedules or multiple instances of Retail Store Connect for scalability. The scheduler configuration is now global and can be used for multiple legal entities. Performance has also been improved.</p></td>
</tr>
<tr class="even">
<td><p>Role-based security</p></td>
<td><p>Role-based security has been added, and built-in roles that cover all functional aspects of the product have also been added. These built-in roles include the following roles:</p>
<ul>
<li><p>Retail Merchandising Manager</p></li>
<li><p>Retail Operations Manager</p></li>
<li><p>Store Manager</p></li>
<li><p>Store Inventory Clerk</p></li>
</ul></td>
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
<td><p>Reports</p></td>
<td><p>The following new reports have been added to Retail modern point-of-sale and Retail enterprise point-of-sale:</p>
<ul>
<li><p>Store return transactions</p></li>
<li><p>Store sales by discount</p></li>
<li><p>Store sales by tender type</p></li>
<li><p>Store voided transactions</p></li>
<li><p>Offline sync status overview</p></li>
<li><p>Register offline sync status</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Modern point-of-sale (MPOS)</p></td>
<td><p>You can configure MPOS to skip the Welcome screen, login directly to the POS screen, and begin ringing up sales immediately.</p></td>
</tr>
</tbody>
</table>


## See also

[Online Store](online-store.md)

[SharePoint 2013 documentation](https://go.microsoft.com/fwlink/?linkid=263772)

[Retail essentials (Retail essentials)](retail-essentials-retail-essentials.md)

  


