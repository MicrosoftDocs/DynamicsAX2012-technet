---
title: Retail Modern Point of Sale
TOCTitle: Retail Modern Point of Sale
ms:assetid: a670f147-1648-4077-9c39-dc032079f8bb
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn741450(v=AX.60)
ms:contentKeyID: 62219728
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Retail Modern Point of Sale 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

Microsoft Dynamics AX 2012 R3 includes Retail Modern POS, a point-of-sale app for PCs, tablets, and phones. Sales staff can process sales transactions, customer orders, and perform daily operations and inventory management with mobile devices anywhere in the store, as well as at PC-based registers.

The Retail Modern POS app can either connect to a database directly, or to Retail Server.

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
<p><a href="http://go.microsoft.com/fwlink/?linkid=397740">Resource page for Microsoft Dynamics AX 2012 for Retail</a></p>
<p><a href="retail-for-application-users.md">Retail for application users</a></p></td>
</tr>
</tbody>
</table>


## Learn

Retail Modern POS clients can communicate with databases in your store, or Retail Servers that are deployed in your store or in a data center. Retail Modern POS clients can also communicate with peripheral devices such as cash drawers, credit card readers, and printers either directly, or by using Microsoft Dynamics AX Hardware Station. If you use Hardware Station, it must be deployed in your store, so that all Retail Modern POS clients can connect to the same Hardware Station.

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
<td><p>Learn about the Retail Modern POS architecture</p></td>
<td><p>The topic describes the components of Retail Modern POS and includes technical architecture diagrams.</p></td>
<td><p><a href="retail-modern-pos-architecture.md">Retail Modern POS architecture</a></p></td>
</tr>
<tr class="even">
<td><p>Learn about the Retail Server architecture</p></td>
<td><p>The topic describes the components of Retail Server and includes technical architecture diagrams.</p></td>
<td><p><a href="architecture-of-microsoft-dynamics-ax-retail-server.md">Architecture of Microsoft Dynamics AX Retail Server</a></p></td>
</tr>
</tbody>
</table>


## Install

The following tables provide information about the Microsoft Dynamics AX features and components that you must install before you install Retail Modern POS.

### ![Dn741450.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn741450.collapse_all(en-us,AX.60).gif")Install components at headquarters

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
<td><p>Retail Modern POS is a component of AX 2012 R3.</p></td>
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


### ![Dn741450.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn741450.collapse_all(en-us,AX.60).gif")Install components at the stores

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
<td><p>Create channel databases</p></td>
<td><p>Each store location must have a channel database to store the data that is needed for retail transactions. POS devices connect to the channel database to access data and to upload transactions.</p></td>
<td><p><a href="create-a-channel-database-or-an-offline-database-ax-2012-r3.md">Create a channel database or an offline database (AX 2012 R3)</a></p></td>
</tr>
<tr class="odd">
<td><p>Install Retail Server</p></td>
<td><p>Retail Server provides services and business logic for Retail Modern POS clients.</p></td>
<td><p><a href="install-retail-server.md">Install Retail Server</a></p></td>
</tr>
<tr class="even">
<td><p>Install the Windows 8.1 packaged Retail Modern POS app</p></td>
<td><p>The Microsoft Dynamics AX Windows 8.1 Retail Modern POS is a fully-functional app. You can install it by using the Microsoft Dynamics AX setup wizard or Windows PowerShell. If you want to customize this app, then you must use a different installation method. See the next row in this table.</p></td>
<td><p><a href="install-retail-modern-pos.md">Install Retail Modern POS</a></p></td>
</tr>
<tr class="odd">
<td><p>Install an app from the Retail SDK</p></td>
<td><p>You may want to install another app. For example, you can install the Windows 8.1 app or the Windows Phone app from the Retail SDK. You can customize those apps or create your own.</p>
<p>If you do, you must utilize side-loading to install your app.</p>
<p>For more information, see Extend.</p></td>
<td><p><a href="install-retail-modern-pos.md">Install Retail Modern POS</a></p></td>
</tr>
</tbody>
</table>


## Extend

You can customize the behavior of your modern POS system in several ways. For example, you can modify the information that is made available to modern POS by extending a commerce entity to include a new column from your Microsoft Dynamics AX database. You can then make use of that new column in commerce runtime in a service and workflow, and then expose it in the commerce runtime API. Because you modified the commerce entity, you would also need to customize the corresponding controller and metadata in Retail Server. For an end to end customization example, see Walkthrough: Extend Modern Point of Sale for Microsoft Dynamics AX.

In other extensibility scenarios, you wouldn’t need to modify every layer of the stack. For example, you could simply modify the way a workflow behaves without modifying the database schema.

The Retail SDK includes apps for various clients. You can customize those apps to match the branding of your organization or to extend their functionality.

### ![Dn741450.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn741450.collapse_all(en-us,AX.60).gif")Extend Microsoft Dynamics AX

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
<td><p>Customize the database schema</p></td>
<td><p>If you add one or more new fields to a table in Microsoft Dynamics AX, a commerce entity in the commerce runtime automatically includes those fields as long as you make changes to the stored procedure or view to return the additional field.</p></td>
<td><p><a href="customize-the-data-in-a-commerce-entity.md">Customize the Data in a Commerce Entity</a></p>
<p><a href="walkthrough-adding-a-table-for-customer-preferences-to-the-ax-2012-database.md">Walkthrough: Adding a table for customer preferences to the AX 2012 database</a></p></td>
</tr>
<tr class="even">
<td><p>Customize Commerce Data Exchange: Real-time Service</p></td>
<td><p>Commerce Data Exchange: Real-time Service is a Windows Communication Foundation (WCF) service that uses .NET Business Connector to enable retail clients to communicate with Microsoft Dynamics AX in real time. You can customize Real-time Service by adding extension methods to the <a href="https://technet.microsoft.com/en-us/library/hh813763(v=ax.60)">RetailTransactionServiceEx</a> class.</p></td>
<td><p><a href="extend-the-commerce-data-exchange-real-time-service.md">Extend the Commerce Data Exchange: Real-time Service</a></p></td>
</tr>
<tr class="odd">
<td><p>Enable debugging</p></td>
<td><p>You can use the X++ debugger to debug from commerce runtime to Real-time Service to Microsoft Dynamics AX, but you must create Microsoft Dynamics AX configurations for your local client and Business Connector, and then update the Business Connector configuration in the registry editor.</p></td>
<td><p><a href="debug-x-code-for-retail.md">Debug X++ Code for Retail</a></p></td>
</tr>
</tbody>
</table>


### ![Dn741450.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn741450.collapse_all(en-us,AX.60).gif")Extend commerce runtime

The commerce runtime is a set of assemblies that enables your store to obtain interactive data based on a shopping cart. The commerce runtime includes several services that query for real-time data. It also includes workflow business logic that enforces rules for your store.

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
<td><p>Customize data in a commerce entity</p></td>
<td><p>The CommerceEntity class is a property bag of key value pairs of C# properties. These properties provide string representations of fields from the database so that you do not need to remember the names of columns in your database when you write code. For any existing data type, if you add one or more new fields to a table in Microsoft Dynamics AX, the commerce entity automatically includes those fields as long as you make changes to the stored procedure or view to return the additional field.</p></td>
<td><p><a href="customize-the-data-in-a-commerce-entity.md">Customize the Data in a Commerce Entity</a></p>
<p><a href="walkthrough-adding-a-table-for-customer-preferences-to-the-ax-2012-database.md">Walkthrough: Adding a table for customer preferences to the AX 2012 database</a></p>
<p><a href="walkthrough-extending-the-crt-to-add-customer-preference-data-for-retail-clients.md">Walkthrough: Extending the CRT to add customer preference data for Retail clients</a></p></td>
</tr>
<tr class="even">
<td><p>Customize services</p></td>
<td><p>Microsoft Dynamics AX offers many services in the commerce runtime that support the basic functionality of a store. If one of these services does not meet the needs of your store, you can replace it with your own service and continue to use the other services that are installed with the commerce runtime.</p></td>
<td><p><a href="services-overview-for-commerce-runtime.md">Services Overview for Commerce Runtime</a></p>
<p><a href="integrate-a-service-into-the-commerce-runtime.md">Integrate a Service into the Commerce Runtime</a></p>
<p><a href="walkthrough-integrating-a-new-shipping-service.md">Walkthrough: Integrating a new Shipping Service</a></p></td>
</tr>
<tr class="odd">
<td><p>Customize workflow</p></td>
<td><p>The commerce runtime includes workflow business logic that enforces rules for your business. You can use the workflows that are included in commerce runtime or create your own.</p></td>
<td><p><a href="create-commerce-runtime-workflows.md">Create Commerce Runtime Workflows</a></p></td>
</tr>
<tr class="even">
<td><p>Use the API</p></td>
<td><p>You can use the API for things like getting information about items, price calculation, shipping calculation, and placing orders. You can extend the API to fit your business processes.</p></td>
<td><p><a href="crt-ref/net-framework-classes-for-microsoft-dynamics-ax-commerce-runtime.md">.NET Framework Classes for Microsoft Dynamics AX Commerce Runtime</a></p></td>
</tr>
<tr class="odd">
<td><p>Deploy your commerce runtime customizations</p></td>
<td><p>After you customize the functionality of your store in the commerce runtime, use the GAC utility to copy your new DLLs to your solution.</p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


### ![Dn741450.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn741450.collapse_all(en-us,AX.60).gif")Extend Retail Server

The Microsoft Dynamics AX Commerce runtime is wrapped in a Retail Server layer. Retail Server uses a web API with OData to support thin clients within the store like tablets and phones. Commerce runtime communicates through Commerce Data Exchange services to Microsoft Dynamics AX for Retail Headquarters.

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
<td><p>Create a new controller</p></td>
<td><p>If you create a new commerce entity or complex type, you need to create a new controller to expose actions that you want to be available. After you create a new controller, you must modify the metadata to use it.</p></td>
<td><p><a href="create-a-new-retail-server-controller.md">Create a new Retail Server Controller</a></p></td>
</tr>
<tr class="even">
<td><p>Extend an existing controller</p></td>
<td><p>You can integrate a new controller or extend on of the controllers that come with Microsoft Dynamics AX. If you add a commerce entity or action, you must modify the metadata to use it.</p></td>
<td><p><a href="extend-a-retail-server-odata-controller.md">Extend a Retail Server OData Controller</a></p></td>
</tr>
<tr class="odd">
<td><p>Extend metadata (OData)</p></td>
<td><p>Metadata defines a contract between client and server. It exposes the entity definition and action definition, so when you make a change on the server side, you can use a tool on the client side to generate proxy code, reducing maintenance effort for developers. To consume new commerce entities and actions, you must extend the metadata, otherwise the client won’t know about it.</p></td>
<td><p><a href="extend-the-metadata.md">Extend the metadata</a></p></td>
</tr>
<tr class="even">
<td><p>Use Web API and OData controllers together</p></td>
<td><p>You can create your own Web API controller and extend the Web API configuration as an alternative to using the standard OData controllers.</p></td>
<td><p><a href="use-web-api-and-odata-controllers-together.md">Use Web API and OData controllers together</a></p></td>
</tr>
<tr class="odd">
<td><p>Retail Server reference</p></td>
<td><p>You can reference API documentation for the Microsoft.Dynamics.Retail.RetailServerLibrary assembly.</p></td>
<td><p><a href="retail-server-ref/net-framework-classes-for-microsoft-dynamics-ax-retail-server.md">.NET Framework Classes for Microsoft Dynamics AX Retail Server</a></p></td>
</tr>
<tr class="even">
<td><p>Incorporate your changes</p></td>
<td><p>You need to copy the DLL into the retail server bin folder. You need to repackage the new DLL into the same MSI installation package. You also need to modify the Web.config file to make sure the DLL is processed, just like the commerceruntime.config file.</p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


### ![Dn741450.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn741450.collapse_all(en-us,AX.60).gif")Extend clients

You can customize the look and feel of a Modern POS client to make it an extension of your brand. We recommend that you use your own file names and namespaces for any customizations.

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
<td><p>Extend Modern POS for a Windows client</p></td>
<td><p>You can install the Windows 8.1 packaged Retail Modern POS app by using the Microsoft Dynamics AX setup wizard, but you can’t extend it. The Retail SDK includes sample code that you can use to extend the Windows 8.1 Retail Modern POS app to meet your needs.</p>
<p>To use the Windows 8.1 Retail Modern POS sample code that is included in the Retail SDK, you must install for Visual Studio 2012 and 2013.</p></td>
<td><p><a href="retail-sdk.md">Retail SDK</a></p>
<p><a href="http://www.microsoft.com/en-us/download/details.aspx?id=34790">TypeScript for Visual Studio 2012 and 2013</a></p>
<p>Walkthrough: Extend Modern Point of Sale for Microsoft Dynamics AX</p>
<p><a href="http://msdn.microsoft.com/en-us/windows/apps/">Windows Dev Center</a></p></td>
</tr>
<tr class="even">
<td><p>Extend Modern POS for Windows Phone client</p></td>
<td><p>The Retail SDK includes sample code that you can use to create your own Windows Phone Retail Modern POS app.</p></td>
<td><p><a href="retail-sdk.md">Retail SDK</a></p>
<p><a href="http://developer.windowsphone.com/en-us">Windows Phone Dev Center</a></p></td>
</tr>
<tr class="odd">
<td><p>Enable Modern POS for Windows Phone reports</p></td>
<td><p>The Windows Phone app in the Retail SDK contains code you can use for reports. You must install Silverlight libraries, uncomment code from certain files in the Windows Phone app, and then add references to the Silverlight toolkit.</p></td>
<td><p><a href="microsoft-dynamics-ax-retail-windows-phone-point-of-sale.md">Microsoft Dynamics AX Retail Windows Phone Point of Sale</a></p></td>
</tr>
<tr class="even">
<td><p>Package your changes</p></td>
<td><p>After you have customized one of the mobile apps that are available in the Retail SDK, you can package your solution so that it can be installed on devices.</p>
<p>To package your app, in Visual Studio, click <strong>Project</strong> &gt; <strong>Store</strong> &gt; <strong>Create App Packages</strong>. On the <strong>Create Your Packages</strong> screen, select <strong>No</strong>, and then complete the wizard.</p></td>
<td><p><a href="http://msdn.microsoft.com/en-us/windows/apps/hh975357.aspx">Create an app package</a></p></td>
</tr>
<tr class="odd">
<td><p>Install a customized app</p></td>
<td><p>After you extend one of the apps that are available in the Retail SDK, you must use side-loading to install it to devices.</p></td>
<td><p><a href="install-retail-modern-pos.md">Install Retail Modern POS</a></p></td>
</tr>
</tbody>
</table>


## Configure

Before you can process transactions or perform any other retail operations using Retail Modern POS, you must first set up your retail store in Microsoft Dynamics AX. Each retail store can have its own payment methods, price groups, point-of-sale (POS) registers, income accounts and expense accounts, and staff.

The following tables describe the configuration tasks that you must complete in Microsoft Dynamics AX for a retail store.

### ![Dn741450.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn741450.collapse_all(en-us,AX.60).gif")Prerequisites

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
<td><p>Before you can offer products for resale in your retail channels, you must create and configure the products in Microsoft Dynamics AX. To link the products that you sell to the retail channels that sell those products, you must set up product assortments.</p></td>
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


### ![Dn741450.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn741450.collapse_all(en-us,AX.60).gif")Set up a retail store

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


### ![Dn741450.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn741450.collapse_all(en-us,AX.60).gif")After you set up a retail store

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


### ![Dn741450.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn741450.collapse_all(en-us,AX.60).gif")Set up data exchange between Microsoft Dynamics AX and the store

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
<td><p><a href="set-up-a-profile-for-async-server.md">Set up a profile for Async Server</a></p>
<p><a href="set-up-a-real-time-service-profile.md">Set up a Real-time Service profile</a></p>
<p><a href="set-up-a-channel-database-profile.md">Set up a channel database profile</a></p></td>
</tr>
<tr class="even">
<td><p>Configure data distribution and scheduling</p></td>
<td><p>A channel data group is a group of one or more retail channel databases. A data package is generated for each data group. All channel databases in a data group subscribe to the same data.</p>
<p>Scheduler jobs are the mechanism for distributing data to and from stores. Jobs are made up of subjobs, which specify how to distribute the data in selected tables and selected table fields.</p></td>
<td><p><a href="create-a-channel-data-group.md">Create a channel data group</a></p>
<p><a href="configure-jobs-and-subjobs-in-retail-scheduler.md">Configure jobs and subjobs in Retail Scheduler</a></p></td>
</tr>
<tr class="odd">
<td><p>Send configuration settings and data to the stores</p></td>
<td><p>After store settings and data exchange settings have been configured in Microsoft Dynamics AX, run jobs to distribute data to the channel database.</p>
<p>In the <strong>Channel database</strong> form, click <strong>Full data sync</strong> and then select the distribution schedule that is named <strong>Full sync</strong>.</p></td>
<td><p><a href="schedule-and-run-jobs-in-retail-scheduler.md">Schedule and run jobs in Retail Scheduler</a></p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

