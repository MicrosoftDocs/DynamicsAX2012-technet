---
title: Point of Sale
TOCTitle: Point of Sale
ms:assetid: 2051b6fa-b8a1-4254-a115-a3480ad31143
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ937969(v=AX.60)
ms:contentKeyID: 50950757
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Point of Sale 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Microsoft Dynamics AX for Retail POS is the point of sale (POS) program for Microsoft Dynamics AX. POS tasks are performed by using a POS register. The graphical user interface (GUI) is easy to use and can be set up to meet the requirements of many industries, such as food service, fashion, and grocery.

This topic includes links to important information about how to plan, deploy, configure, and customize Retail POS.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><img src="images/Gg723980.TopicIcon_Lifecycle(AX.60).png" title="Lifecycle" alt="Lifecycle" />
<p>Learn</p>
<p>Install</p>
<p>Extend</p>
<p>Configure</p></td>
<td><img src="images/Dn507140.TopicIcons_Resources(AX.60).png" title="Resources" alt="Resources" />
<p><a href="http://go.microsoft.com/fwlink/?linkid=397740">Resource page for Retail</a></p>
<p><a href="retail-benchmark-for-microsoft-dynamics-ax-2012-r2.md">Retail Benchmark for Microsoft Dynamics AX 2012 R2</a></p></td>
</tr>
</tbody>
</table>


## Learn

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
<th><p>Topics</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Learn about new features in the latest release.</p></td>
<td><p>Review new and changed Retail features since the release of Microsoft Dynamics AX 2012.</p></td>
<td><p><a href="what-s-new-retail-features.md">What's new: Retail features</a></p></td>
</tr>
</tbody>
</table>


## Install

The following tables provide information about the Microsoft Dynamics AX features and components that you must install before you install Retail POS.

### ![JJ937969.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ937969.collapse_all(en-us,AX.60).gif")Install components at headquarters

Install the following components at the headquarters location.

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
<th><p>Topics</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Deploy Microsoft Dynamics AX</p></td>
<td><p>Retail POS is a component of AX 2012 R3.</p></td>
<td><p><a href="http://go.microsoft.com/fwlink/?linkid=163797">Implementation Planning Guide (PDF)</a></p>
<p><a href="http://go.microsoft.com/fwlink/?linkid=165377">System requirements (PDF)</a></p>
<p><a href="install-microsoft-dynamics-ax-2012.md">Install Microsoft Dynamics AX 2012</a></p></td>
</tr>
<tr class="even">
<td><p>Install and configure Retail Headquarters</p></td>
<td><p>When you install Retail Headquarters by using Setup, you install the basic components to run Microsoft Dynamics AX Retail.</p></td>
<td><p><a href="install-retail-headquarters.md">Install Retail Headquarters</a></p></td>
</tr>
<tr class="odd">
<td><p>Install and configure components of Commerce Data Exchange</p></td>
<td><p>Commerce Data Exchange is a system that transfers data between Microsoft Dynamics AX and retail channels. At headquarters, you must install Commerce Data Exchange: Async Server and Commerce Data Exchange: Real-time Service.</p></td>
<td><p><a href="install-commerce-data-exchange-async-server.md">Install Commerce Data Exchange: Async Server</a></p>
<p><a href="specify-working-folders-for-commerce-data-exchange.md">Specify working folders for Commerce Data Exchange</a></p>
<p><a href="install-commerce-data-exchange-real-time-service-retail-transaction-service.md">Install Commerce Data Exchange: Real-time Service (Retail Transaction Service)</a></p></td>
</tr>
<tr class="even">
<td><p>Install Retail SDK</p></td>
<td><p>The Retail Software Development Kit (SDK) includes code samples, templates, and tools to customize Microsoft Dynamics AX 2012 Retail clients.</p></td>
<td><p><a href="install-retail-sdk-retail-pos-plug-ins.md">Install Retail SDK (Retail POS Plug-ins)</a></p>
<p><a href="retail-sdk.md">Retail SDK</a></p></td>
</tr>
</tbody>
</table>


### ![JJ937969.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ937969.collapse_all(en-us,AX.60).gif")Install components at the stores

Install the following components at each store location.

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
<th><p>Topics</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Install and configure components of Commerce Data Exchange</p></td>
<td><p>Commerce Data Exchange is a system that transfers data between Microsoft Dynamics AX and retail channels. At stores, you must install Commerce Data Exchange: Async Client.</p></td>
<td><p><a href="install-commerce-data-exchange-async-client.md">Install Commerce Data Exchange: Async Client</a></p>
<p><a href="specify-working-folders-for-commerce-data-exchange.md">Specify working folders for Commerce Data Exchange</a></p></td>
</tr>
<tr class="even">
<td><p>Create channel databases and offline databases</p></td>
<td><p>Each store location must have a channel database to store the data that is needed for retail transactions. POS registers connect to the channel database to access data and to upload transactions.</p>
<p>Optionally, you can also have an offline database at each register. An offline database lets you continue to use the register even if the connection to the channel database is temporarily lost.</p></td>
<td><p><a href="create-a-channel-database-or-an-offline-database-ax-2012-r3.md">Create a channel database or an offline database (AX 2012 R3)</a></p>
<p><a href="create-a-store-database-or-an-offline-database-ax-2012-r2-and-ax-2012-feature-pack.md">Create a store database or an offline database (AX 2012 R2 and AX 2012 Feature Pack)</a></p>
<p><a href="use-retail-pos-in-offline-mode.md">Use Retail POS in offline mode</a></p></td>
</tr>
<tr class="odd">
<td><p>Install Retail POS</p></td>
<td><p>Install Retail POS on point of sale registers.</p></td>
<td><p><a href="install-retail-pos.md">Install Retail POS</a></p></td>
</tr>
</tbody>
</table>


## Extend

### ![JJ937969.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ937969.collapse_all(en-us,AX.60).gif")Extend and customize Retail POS

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
<th><p>Topics</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Extend Retail POS</p></td>
<td><p>The Retail Software Development Kit (SDK) includes .NET libraries you can use to extend existing Retail POS functionality.</p></td>
<td><ul>
<li><p><a href="extend-point-of-sale.md">Extend Point of Sale</a></p></li>
<li><p><a href="walkthrough-adding-an-image-to-product-search-results.md">Walkthrough: Adding an Image to Product Search Results</a></p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Customize Retail POS</p></td>
<td><p>The Retail Software Development Kit (SDK) includes .NET libraries that you can use to customize Retail POS functionality. You can also build your own libraries and integrate them with Retail POS.</p></td>
<td><ul>
<li><p><a href="use-blankoperations-to-implement-custom-features.md">Use BlankOperations to implement custom features</a></p></li>
<li><p><a href="modify-a-form.md">Modify a form</a></p></li>
<li><p><a href="modify-a-trigger.md">Modify a trigger</a></p></li>
<li><p><a href="create-and-implement-a-retail-pos-skin.md">Create and implement a Retail POS skin</a></p></li>
</ul></td>
</tr>
</tbody>
</table>


## Configure

Microsoft Dynamics AX 2012 for Retail supports multiple retail channels, including online stores, online marketplaces, and brick-and-mortar stores. In Retail, a brick-and-mortar store is called a retail store. Each retail store can have its own payment methods, price groups, point-of-sale (POS) registers, income accounts and expense accounts, and staff.

After you create a retail store, you assign the products that you want the store to carry. You also assign employees, registers, and customers to the store. Finally, you add the new store to an organization hierarchy.

The following tables describe the configuration tasks that you must complete in Microsoft Dynamics AX for a brick-and-mortar store.

### ![JJ937969.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ937969.collapse_all(en-us,AX.60).gif")Prerequisites

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
<th><p>Topics</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Configure organization structures for Retail</p></td>
<td><p>Set up organization hierarchies for retail assortments, replenishment, and reporting.</p>
<p>Organization hierarchies represent the relationships between the organizations that make up your business. When you set up stores, you can add them to an organization hierarchy. The stores then share data that is used for assortments, replenishment, and reporting.</p></td>
<td><p><a href="create-or-modify-an-organization-hierarchy.md">Create or modify an organization hierarchy</a></p></td>
</tr>
<tr class="even">
<td><p>Set up address books for employees and customers</p></td>
<td><p>Microsoft Dynamics AX 2012 includes a global address book that is shared among all companies in your environment. The global address book stores party record information for each organization or person that your organization has contact with.</p></td>
<td><p><a href="create-address-books.md">Create address books</a></p></td>
</tr>
<tr class="odd">
<td><p>Set up a warehouse to represent the retail store</p></td>
<td><p>A retail store is considered a type of warehouse. First, you create a warehouse and define it as a store. Then, you create a new store and assign the warehouse to it.</p></td>
<td><p><a href="set-up-a-retail-store.md">Set up a retail store</a></p></td>
</tr>
<tr class="even">
<td><p>Set up number sequences for retail stores, store statements, and statement vouchers</p></td>
<td><p>Before you can create stores, statements and statement vouchers, you must set up number sequences for them.</p></td>
<td><p><a href="set-up-number-sequences.md">Set up number sequences</a></p></td>
</tr>
<tr class="odd">
<td><p>Configure parameters for Retail</p></td>
<td><p>Set parameters to configure Retail for your business. Parameters provide default settings and values.</p></td>
<td><p><a href="configure-parameters.md">Configure parameters</a></p></td>
</tr>
<tr class="even">
<td><p>Set up the methods of payment that the store accepts</p></td>
<td><p>If you accept payments that are made by using checks, credit cards, debit cards, corporate charge cards, gift cards, customer credit, and other forms of payment, you must set up each payment method for your organization. You can assign specific payment methods to each store and then set up store-specific settings for each payment method.</p>
<p>To process credit card transactions at retail point-of-sale (POS) registers, you can also set up payment services.</p></td>
<td><p><a href="setting-up-payment-methods-retail.md">Setting up payment methods (Retail)</a></p>
<p><a href="set-up-payment-services.md">Set up Payment Services</a></p>
<p><a href="https://technet.microsoft.com/en-us/library/jj683232(v=ax.60)">Set up payment connector</a> (optional)</p></td>
</tr>
<tr class="odd">
<td><p>Set up sales tax groups</p></td>
<td><p>Sales tax groups are groups of sales tax codes that are attached to customers and vendors.</p>
<p>The sales taxes that apply to a transaction are determined by the sales tax codes that are included both in the sales tax group and in the item sales tax group of the transaction.</p></td>
<td><p><a href="setting-up-taxes.md">Setting up taxes</a></p></td>
</tr>
<tr class="even">
<td><p>Set up retail products, product hierarchies, product variants, and product assortments</p></td>
<td><p>Before you can offer products for resale in your retail channels, you must create and configure the products in Microsoft Dynamics AX. To link the products that you sell to the retail channels that sell those products, you must set up assortments.</p></td>
<td><p><a href="setting-up-retail-products.md">Setting up retail products</a></p>
<p><a href="retail-hierarchy.md">Retail hierarchy</a></p>
<p><a href="variants.md">Variants</a></p>
<p><a href="assortments.md">Assortments</a></p></td>
</tr>
<tr class="odd">
<td><p>Set up retail product pricing</p></td>
<td><p>Use price groups to create and manage prices and discounts for retail products. For example, you could use price groups to offer specific products at different prices to different groups of customers in different stores.</p></td>
<td><p><a href="setting-up-prices-using-price-groups.md">Setting up prices using price groups</a></p>
<p><a href="setting-up-price-adjustments-and-discounts.md">Setting up price adjustments and discounts</a></p></td>
</tr>
<tr class="even">
<td><p>Set up staff</p></td>
<td><p>Before workers can perform their job duties in the retail store, you must set up the workers in Microsoft Dynamics AX. You must also assign appropriate permissions to the workers, so that they can log on and perform tasks.</p></td>
<td><p><a href="setting-up-staff.md">Setting up staff</a></p></td>
</tr>
<tr class="odd">
<td><p>Configure the Retail POS profiles and other settings to assign to the store</p></td>
<td><p>Profiles include basic information about the receipts, appearance, and functionality of the registers at the stores.</p></td>
<td><p><a href="setting-up-retail-pos.md">Setting up Retail POS</a></p>
<p><a href="setting-up-functionality-profiles.md">Setting up functionality profiles</a></p></td>
</tr>
</tbody>
</table>


### ![JJ937969.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ937969.collapse_all(en-us,AX.60).gif")Set up a retail store

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
<th><p>Topics</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Create a retail store</p></td>
<td><p>A retail store is considered a type of warehouse. First, you create a warehouse and define it as a store. Then, you create a new store and assign the warehouse to it.</p></td>
<td><p><a href="set-up-a-retail-store.md">Set up a retail store</a></p></td>
</tr>
<tr class="even">
<td><p>Assign a sales tax group to the store</p></td>
<td><p>A sales tax group is required for each store.</p></td>
<td><p><a href="assign-sales-tax-groups-to-stores.md">Assign sales tax groups to stores</a></p></td>
</tr>
<tr class="odd">
<td><p>Assign the accepted payment methods to the store</p></td>
<td><p>After you create a payment method in Retail, you can assign the payment method to stores. Multiple payment methods for stores can be based on a single organization-wide payment method. Each store payment method can have different settings.</p></td>
<td><p><a href="set-up-store-payment-methods.md">Set up store payment methods</a></p></td>
</tr>
<tr class="even">
<td><p>Add details to product descriptions</p></td>
<td><p>Use product attributes to add merchandising details, such as rich text, images, and videos to the descriptions of products that you offer in your retail stores or in product catalogs.</p></td>
<td><p><a href="add-and-update-product-attributes-for-retail-channels.md">Add and update product attributes for retail channels</a></p></td>
</tr>
<tr class="odd">
<td><p>Add the store to an organization hierarchy</p></td>
<td><p>Add the store to an organization hierarchy that is assigned to a purpose of Retail assortment, Retail replenishment and Retail reporting.</p>
<p>You use the hierarchy to select the stores that you distribute assortments to or replenish stock for. For example, you assign a store to an organization hierarchy with a purpose of Retail assortment. Then, when you distribute assortments to retail channels, you can select only the retail channels that are included in this organization hierarchy.</p></td>
<td><p><a href="create-or-modify-an-organization-hierarchy.md">Create or modify an organization hierarchy</a></p></td>
</tr>
</tbody>
</table>


### ![JJ937969.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ937969.collapse_all(en-us,AX.60).gif")After you set up a retail store

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
<th><p>Topics</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Configure the point of sale (POS) registers for the store</p></td>
<td><p>When you set up a register in Retail POS, you select a hardware profile and a visual profile for the terminal. A hardware profile determines the physical configuration of a terminal and a visual profile determines its screen characteristics.</p>
<p>You can assign the profiles either to a specific register or to a group of registers.</p></td>
<td><p><a href="set-up-registers.md">Set up registers</a></p></td>
</tr>
<tr class="even">
<td><p>Assign product assortments to the store</p></td>
<td><p>The assortment that is assigned to a store contains a list of products that are available in the store.</p>
<div class="alert">
<div class="mtps-table">
<div class="mtps-row">
<img src="images/Dn527205.alert_note(AX.60).gif" title="Note" alt="Note" class="note" /><strong>Note</strong>
</div>
<div class="mtps-row">
You can assign the retail store to an existing assortment or create a new assortment for the retail store.
</div>
</div>
</div></td>
<td><p><a href="set-up-an-assortment.md">Set up an assortment</a></p></td>
</tr>
<tr class="odd">
<td><p>Process assortments</p></td>
<td><p>Process assortments to generate the list of products that are included in the assortment and to make the products available in the retail store.</p></td>
<td><p><a href="configure-the-retail-assortments-job.md">Configure the retail assortments job</a></p></td>
</tr>
</tbody>
</table>


### ![JJ937969.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ937969.collapse_all(en-us,AX.60).gif")Set up data exchange between Microsoft Dynamics AX and the store

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
<th><p>Topics</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Set up channel integration profiles</p></td>
<td><p>Profiles enable the components of Retail to communicate with each other. Set up profiles before you configure data exchange settings.</p></td>
<td><p><a href="set-up-a-profile-for-async-server.md">Set up a profile for Async Server</a> <em>(AX 2012 R3 only)</em></p>
<p><a href="set-up-a-real-time-service-profile.md">Set up a Real-time Service profile</a></p>
<p><a href="set-up-a-profile-for-synch-service.md">Set up a profile for Synch Service</a> <em>(AX 2012 R2 and AX 2012 Feature Pack only)</em></p>
<p><a href="set-up-a-channel-database-profile.md">Set up a channel database profile</a> <em>(AX 2012 R3 only)</em></p>
<p><a href="set-up-a-store-database-profile.md">Set up a store database profile</a> <em>(AX 2012 R2 and AX 2012 Feature Pack only)</em></p>
<p><a href="set-up-an-aos-profile.md">Set up an AOS profile</a> <em>(AX 2012 R2 and AX 2012 Feature Pack only)</em></p></td>
</tr>
<tr class="even">
<td><p>Configure data distribution and scheduling.</p></td>
<td><p>In AX 2012 R3, a channel data group is a group of one or more retail channel databases. A data package is generated for each data group. All channel databases in a data group subscribe to the same data.</p>
<p>In AX 2012 R2 and AX 2012 Feature Pack, a distribution location is a record that links a store to the database. Distribution locations represent the destinations of distributed data. A distribution location list is a group of distribution locations. For example, you can set up a distribution location list per region or per time zone.</p>
<p>Scheduler jobs are the mechanism for distributing data to and from stores. Jobs are made up of subjobs, which specify how to distribute the data in selected tables and selected table fields.</p></td>
<td><p><em>In AX 2012 R3:</em></p>
<p><a href="create-a-channel-data-group.md">Create a channel data group</a></p>
<p><a href="configure-jobs-and-subjobs-in-retail-scheduler.md">Configure jobs and subjobs in Retail Scheduler</a></p>
<p><em>In AX 2012 R2 and AX 2012 Feature Pack:</em></p>
<p><a href="create-distribution-locations-for-retail-databases.md">Create distribution locations for retail databases</a></p>
<p><a href="set-up-a-distribution-location-list.md">Set up a distribution location list</a></p>
<p><a href="configure-jobs-and-subjobs-in-retail-scheduler.md">Configure jobs and subjobs in Retail Scheduler</a></p></td>
</tr>
<tr class="odd">
<td><p>Send configuration settings and data to the stores</p></td>
<td><p>After store settings and data exchange settings have been configured in Microsoft Dynamics AX, run jobs to distribute data to the store databases.</p>
<p><em>In AX 2012 R3:</em></p>
<p>Synchronize all data for the channel database. In the <strong>Channel database</strong> form, click <strong>Full data sync</strong> and then select the distribution schedule that is named <strong>Full sync</strong>.</p>
<p><em>In AX 2012 R2 and AX 2012 Feature Pack:</em></p>
<p>When you set up a new store database, you must run all A jobs for that location. In addition, run the following N jobs:</p>
<ul>
<li><p>N-1000 – Currency</p></li>
<li><p>N-1010 – Customer</p></li>
<li><p>N-1030 – Reason code information, if reason codes are used</p></li>
<li><p>N-1050 – Loyalty, if loyalty discounts are given</p></li>
<li><p>N-1080 – Tax</p></li>
<li><p>N-1100 – Item and price parameters</p></li>
<li><p>N-1110 – Global configuration</p></li>
<li><p>N-1115 – Global address book reference data</p></li>
</ul>
<p>To avoid sending all data to all locations, you can temporarily modify the distribution schedule for the job, so that the data is sent only to the new location.</p></td>
<td><p><a href="schedule-and-run-jobs-in-retail-scheduler.md">Schedule and run jobs in Retail Scheduler</a></p></td>
</tr>
<tr class="even">
<td><p>Set up offline database synchronization for registers</p></td>
<td><p>Offline profiles define which data is synchronized from the store database to the offline databases on POS registers. Each offline profile consists of several offline scopes. The default scopes are modeled after the jobs that are used to synchronize data between Microsoft Dynamics AX and the stores. For example, a scheduler job pushes tax-related information from Microsoft Dynamics AX to the stores. The tables that are included in that scheduler job are also included in the offline scope that pushes tax-related information from the store database to the offline database.</p></td>
<td><p><a href="set-up-offline-profiles.md">Set up offline profiles</a></p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

