---
title: Online Store
TOCTitle: Online Store
ms:assetid: 56364854-9730-4afa-8cf7-ae337ce2257a
ms:mtpsurl: https://technet.microsoft.com/library/JJ937972(v=AX.60)
ms:contentKeyID: 50950762
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Online Store 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

Microsoft Dynamics AX 2012 includes a suite of features that help you deploy, manage, and customize an online sales channel that is fully integrated with Microsoft Dynamics AX. E-commerce investments include two starter online stores that are built on Microsoft SharePoint Server 2013, developer tools, and administrative and runtime components that integrate the online channel with Microsoft Dynamics AX.

By using this new suite of e-commerce features, you can centrally manage products, merchandizing, and order fulfillment for all aspects of your online sales channel directly in Microsoft Dynamics AX. The runtime component enables you to deliver content and retail services in a scalable way. The starter stores accelerate the development of a highly customized online channel. The starter stores include the patterns and best practices that are required to support production-ready deployments, including powerful, search-driven, adaptive experiences offered by the SharePoint Server 2013.

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
<p><a href="https://go.microsoft.com/fwlink/?linkid=397740">Resource page for Microsoft Dynamics AX 2012 for Retail</a></p>
<p><a href="retail-for-application-users.md">Retail for application users</a></p></td>
</tr>
</tbody>
</table>


## Learn

The Microsoft Dynamics AX Retail online store is built on the cross-site publishing features of Microsoft SharePoint 2013 Products. Before you install and configure the online store you must familiarize yourself with the SharePoint 2013 planning documentation.

The following table includes information about the SharePoint 2013 for Internet Sites platform and the Retail online store architecture.

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
<td><p>Plan the retail deployment</p></td>
<td><p>Before you install Microsoft Dynamics AX 2012 for Retail, you must decide on the system topology.</p></td>
<td><p><a href="deployment-topologies-for-retail.md">Deployment topologies for Retail</a></p></td>
</tr>
<tr class="even">
<td><p>Plan for an online store</p></td>
<td><p>You do not have to create applications or sites from scratch as discussed in the SharePoint 2013 planning documentation. When you deploy the Microsoft Dynamics AX Retail online store, you deploy a starter store that includes pre-constructed web applications, sites, and services. You can then configure, customize, and rebrand the starter online store to meet your needs.</p>
<p>Search is the primary means by which customers find products in an online store. For this reason, you should also familiarize yourself with SharePoint 2013 search concepts.</p>
<p>We recommend that you familiarize yourself with concepts provided by the following links before you deploy the Microsoft Dynamics AX Retail online store.</p></td>
<td><p><a href="https://technet.microsoft.com/library/jj635876.aspx">Plan for cross-site publishing in SharePoint Server 2013</a></p>
<p><a href="https://go.microsoft.com/fwlink/?linkid=328499">Overview of search in SharePoint Server 2013</a></p>
<p><a href="https://go.microsoft.com/fwlink/?linkid=328500">Content Search Web Part in SharePoint 2013</a></p>
<p><a href="https://go.microsoft.com/fwlink/?linkid=328501">Estimate capacity and performance for Web Content Management (SharePoint Server 2013)</a></p>
<p><a href="https://go.microsoft.com/fwlink/?linkid=328502">Estimate capacity and performance for Managed Metadata Service (SharePoint Server 2013)</a></p>
<p><a href="https://go.microsoft.com/fwlink/?linkid=266472">Internet Sites Search Architectures for SharePoint Server 2013</a></p></td>
</tr>
<tr class="odd">
<td><p>Learn about the architecture of the Microsoft Dynamics AX Retail online store</p></td>
<td><p>The Retail online store uses several components of the Microsoft Dynamics AX Retail suite to publish the channel and data to SharePoint 2013.</p></td>
<td><p><a href="architecture-of-the-microsoft-dynamics-ax-retail-online-store.md">Architecture of the Microsoft Dynamics AX Retail online store</a></p>
<p><a href="retail-online-store-publishing-architecture.md">Retail online store publishing architecture</a></p></td>
</tr>
<tr class="even">
<td><p>Learn about Commerce Data Exchange</p></td>
<td><p>Commerce Data Exchange is a system that transfers data between Microsoft Dynamics AX and retail channels, such as online stores or brick-and-mortar stores.</p></td>
<td><p><a href="commerce-data-exchange.md">Commerce Data Exchange</a></p></td>
</tr>
</tbody>
</table>


## Install

The Retail online store utilizes the data, components, and services of Microsoft Dynamics AX Retail components such as Retail Headquarters and a Retail channel database, as well as SharePoint 2013. You must install these other components and applications before you install the online store.

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
<td><p>Prepare for installation</p></td>
<td><p>Before you install Microsoft Dynamics AX components, including Retail components, you should prepare the computers in your environment.</p></td>
<td><p><a href="pre-installation-checklist.md">Pre-installation checklist</a></p>
<p><a href="configure-sql-server-for-the-retail-databases.md">Configure SQL Server for the Retail databases</a></p></td>
</tr>
<tr class="even">
<td><p>Install Microsoft Dynamics AX</p></td>
<td><p>The installation guide includes information about deployment planning, system requirements and specific instructions for installing Microsoft Dynamics AX features and components. We recommend that you install and configure the core components of Microsoft Dynamics AX before you install retail components.</p></td>
<td><p><a href="install-microsoft-dynamics-ax-2012.md">Install Microsoft Dynamics AX 2012</a></p></td>
</tr>
<tr class="odd">
<td><p>Install Retail Headquarters</p></td>
<td><p>When you install Retail Headquarters by using Setup, you install the basic components to run Microsoft Dynamics AX Retail.</p></td>
<td><p><a href="install-retail-headquarters.md">Install Retail Headquarters</a></p></td>
</tr>
<tr class="even">
<td><p>Install and configure components of Commerce Data Exchange</p></td>
<td><p>Commerce Data Exchange is a system that transfers data between Microsoft Dynamics AX and retail channels.</p>
<p>At retail headquarters, you must install Commerce Data Exchange: Async Server and Commerce Data Exchange: Real-time Service.</p>
<p>For an online store, you must install an instance of Commerce Data Exchange: Async Client.</p></td>
<td><p><a href="install-commerce-data-exchange-async-server.md">Install Commerce Data Exchange: Async Server</a></p>
<p><a href="install-commerce-data-exchange-async-client.md">Install Commerce Data Exchange: Async Client</a></p>
<p><a href="specify-working-folders-for-commerce-data-exchange.md">Specify working folders for Commerce Data Exchange</a></p>
<p><a href="install-commerce-data-exchange-real-time-service-retail-transaction-service.md">Install Commerce Data Exchange: Real-time Service (Retail Transaction Service)</a></p></td>
</tr>
<tr class="odd">
<td><p>Install a Retail channel database</p></td>
<td><p>Channel databases hold retail data for one or more retail channels, such as online stores or brick-and-mortar stores. The data for a channel can be included in more than one channel database.</p></td>
<td><p><a href="install-a-retail-channel-database.md">Install a Retail channel database</a></p></td>
</tr>
<tr class="even">
<td><p>Install and configure SharePoint Server 2013</p></td>
<td><p>You must install and configure SharePoint Server 2013 before you deploy the Microsoft Dynamics AX Retail online store.</p></td>
<td><p><a href="https://go.microsoft.com/fwlink/?linkid=286388">Overview of SharePoint 2013 installation and configuration</a></p>
<p><a href="https://go.microsoft.com/fwlink/?linkid=286427&amp;clcid=0x409">Install SharePoint 2013 across multiple servers for a three-tier farm</a></p></td>
</tr>
<tr class="odd">
<td><p>Install the Retail online store</p></td>
<td><p>Microsoft Dynamics AX 2012 for Retail includes two Retail online “starter” stores. The Contoso store is modeled after a fictitious online electronics retailer. The Fabrikam store is modeled after a fictitious online clothing store. When you install the Retail online store by using Setup.exe or PowerShell, you specify which starter store to deploy in your environment. You can then customize and rebrand the starter store to meet your needs.</p></td>
<td><p><a href="install-a-retail-online-store-e-commerce.md">Install a Retail online store (e-commerce)</a></p></td>
</tr>
</tbody>
</table>


## Extend

Microsoft Dynamics AX 2012 comes with several Retail online sample stores. This section outlines how you can customize the look and feel of a sample online store so that your store reflects the brand of your business, and how you can extend the functionality of the sample online store to meet your business needs.

### ![JJ937972.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ937972.collapse_all(en-us,AX.60).gif")Getting started with Retail online sample stores

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
<td><p>View the functionality and appearance of the online sample stores on a demonstration virtual machine</p></td>
<td><p>Demonstration virtual machines are pre-configured virtual machines with software and data to support business scenarios such as provisioning an online channel, creating and publishing online catalogs, and buying online for in-store pickup.</p></td>
<td><p><a href="https://go.microsoft.com/fwlink/?linkid=394231&amp;clcid=0x409">Microsoft Dynamics AX 2012 Solution Demos</a>(To access this site, you must be enrolled in a service plan)</p></td>
</tr>
<tr class="even">
<td><p>Familiarize yourself with the tools and procedures for developing with Retail online sample stores</p></td>
<td><p>When you work with a Retail online sample store, you can extend data in AX 2012, work with services and the commerce runtime (CRT), and extend or customize the user interface in SharePoint 2013.</p></td>
<td><p><a href="getting-started-with-customizing-the-retail-online-sample-store.md">Getting started with customizing the Retail online sample store</a></p></td>
</tr>
<tr class="odd">
<td><p>Learn about the different elements in a Retail online sample stores</p></td>
<td><p>The Retail online sample stores are content-driven web sites that authenticate users, capture user information, and enable customization by administrators and web developers.</p></td>
<td><p><a href="components-of-the-retail-online-sample-store.md">Components of the Retail online sample store</a></p></td>
</tr>
<tr class="even">
<td><p>Learn about the code behind the SharePoint site pages</p></td>
<td><p>The Retail online sample stores use the page framework in SharePoint 2013 to display products, enable customer login, and implement the shopping experience.</p></td>
<td><p><a href="https://go.microsoft.com/fwlink/?linkid=395069&amp;clcid=0x409">Overview of the SharePoint 2013 page model</a></p></td>
</tr>
<tr class="odd">
<td><p>Set up the development environment to debug your code in the Retail online store.</p></td>
<td><p>You use the source code in the Retail SDK as the basis for your customizations.</p></td>
<td><p><a href="debug-code-in-a-retail-online-sample-store.md">Debug code in a Retail online sample store</a></p>
<p><a href="debug-x-code-for-retail.md">Debug X++ Code for Retail</a></p></td>
</tr>
<tr class="even">
<td><p>Understand how the Retail online sample stores authenticate users.</p></td>
<td><p>The sample online stores use Windows authentication for system administrators and forms-based authentication for users.</p></td>
<td><p><a href="authenticating-users-in-retail-online-sample-stores.md">Authenticating users in Retail online sample stores</a></p>
<p><a href="https://go.microsoft.com/fwlink/?linkid=395067&amp;clcid=0x409">Plan for user authentication methods in SharePoint 2013</a></p></td>
</tr>
<tr class="odd">
<td><p>Learn about using content search web parts in the sample stores.</p></td>
<td><p>The Retail online sample stores use SharePoint content search web parts to display products in the store catalogs.</p></td>
<td><p><a href="https://go.microsoft.com/fwlink/?linkid=395068&amp;clcid=0x409">Content Search Web Part in SharePoint 2013</a></p>
<p><a href="https://go.microsoft.com/fwlink/?linkid=395066&amp;clcid=0x409">Edit existing Web Parts in SharePoint 2013</a></p></td>
</tr>
<tr class="even">
<td><p>Learn how to deploy your Retail online store customizations.</p></td>
<td><p>You customize the online sample stores by using SharePoint features and the Visual Studio source-code projects that are included in the Retail SDK. This topic describes how to deploy customizations in development, test, and production environments.</p></td>
<td><p><a href="quick-guide-how-to-customize-a-microsoft-dynamics-ax-for-retail-online-store.md">Quick Guide: How to customize a Microsoft Dynamics AX for Retail online store</a></p></td>
</tr>
<tr class="odd">
<td><p>Walkthroughs with detailed steps to extend the Retail online sample store</p></td>
<td><p>These walkthroughs illustrate the process of adding a data field to the Retail online store. In this scenario, the retailer wants to enable customers to check a box on the Retail store site to indicate that they wish to receive email about special offers.</p>
<p>The walkthroughs demonstrate extending all the required components including the AX 2012 database, the CRT, data distribution, and the Retail online sample store site to include the field EmailOptIn that indicates customer preference in receiving email offers.</p></td>
<td><p><a href="walkthrough-adding-a-table-for-customer-preferences-to-the-ax-2012-database.md">Walkthrough: Adding a table for customer preferences to the AX 2012 database</a></p>
<p><a href="walkthrough-extending-the-crt-to-add-customer-preference-data-for-retail-clients.md">Walkthrough: Extending the CRT to add customer preference data for Retail clients</a></p>
<p><a href="walkthrough-extending-retail-data-distribution-infrastructure-for-customer-preferences.md">Walkthrough: Extending retail data distribution infrastructure for customer preferences</a></p>
<p><a href="walkthrough-adding-customer-preferences-to-the-retail-online-sample-store.md">Walkthrough: Adding customer preferences to the Retail online sample store</a></p></td>
</tr>
</tbody>
</table>


### ![JJ937972.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ937972.collapse_all(en-us,AX.60).gif")Development process

The following diagram shows the components of the online store you can customize: Microsoft Dynamics AX, commerce runtime (CRT), and Microsoft SharePoint.

![Online store](images/JJ937972.OnlineStoreArchitecture(en-us,AX.60).jpg "Online store")

The Retail Software Development Kit (SDK) is a super set of the online store binaries. It provides you with additional tools and source code that you can customize to fit the needs of your business. For more information about the contents of the Retail SDK, see [Retail SDK](retail-sdk.md).

In a typical development process, you would perform the following steps:

1.  [Install the Retail SDK](install-retail-sdk-retail-pos-plug-ins.md) and deployment packages on a stand-alone server

2.  Gather version number and strong name key for source code signing

3.  Update the source code to use the strong name certificate

4.  Configure the topology according to the development or test environment

5.  Customize the online store in Visual Studio

6.  Deploy your customized online store to a development or test environment

7.  Verify your customizations

8.  If needed, go back to step 5

9.  Copy the online store deployment packages from the development or test environment to your production environment

10. Configure the topology on your production environment

11. Deploy your production environment

12. Verify your production environment

For more information about the deployment steps, see [Online Store](online-store.md).

The following sections describe the customizations you can perform in Microsoft Dynamics AX, Commerce Runtime (CRT), and SharePoint Microsoft.

### ![JJ937972.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ937972.collapse_all(en-us,AX.60).gif")Extend commerce runtime

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
<td><p>Microsoft Dynamics AX offers many services in the commerce runtime that support the basic functionality of an online store. If one of these services does not meet the needs of your store, you can replace it with your own service and continue to use the other services that are installed with the commerce runtime.</p></td>
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
<td><p><a href="net-framework-classes-for-microsoft-dynamics-ax-commerce-runtime.md">.NET Framework Classes for Microsoft Dynamics AX Commerce Runtime</a></p></td>
</tr>
<tr class="odd">
<td><p>Deploy your commerce runtime customizations</p></td>
<td><p>After you customize the functionality of your store in the commerce runtime, use the GAC utility to copy your new DLLs to your solution. Then deploy your online store to a test or production environment.</p></td>
<td><p><a href="install-a-retail-online-store-e-commerce.md">Install a Retail online store (e-commerce)</a></p></td>
</tr>
</tbody>
</table>


### ![JJ937972.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ937972.collapse_all(en-us,AX.60).gif")Extend SharePoint

The user interface for the online starter store is based on Microsoft SharePoint Server 2013. You can customize the visual design of the starter store by modifying certain types of files. For example, you can change the store logo by modifying master pages, or you can change the background color of store pages by making modifications to cascading style sheet (CSS) files.

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
<td><p>Learn about the design and operation of the Retail online sample stores</p></td>
<td><p>Get started with customizing the Retail online sample stores by understanding the technologies involved in the functionality, appearance, and security settings of the sites.</p></td>
<td><p><a href="getting-started-with-customizing-the-retail-online-sample-store.md">Getting started with customizing the Retail online sample store</a></p></td>
</tr>
<tr class="even">
<td><p>Set up a SharePoint development environment</p></td>
<td><p>You use SharePoint Server 2013 and Microsoft Visual Studio to customize the user interface for the online sample stores.</p></td>
<td><p><a href="https://go.microsoft.com/fwlink/?linkid=328504">SharePoint 2013 development overview</a></p>
<p><a href="https://go.microsoft.com/fwlink/?linkid=313705">Set up the development environment for SharePoint 2013</a></p>
<p><a href="https://go.microsoft.com/fwlink/?linkid=328505.">Develop the site design in SharePoint 2013</a></p>
<p><a href="https://go.microsoft.com/fwlink/?linkid=328506">Build sites for SharePoint 2013</a></p>
<p><a href="map-a-network-drive-to-the-sharepoint-2013-files-for-online-stores.md">Map a network drive to the SharePoint 2013 files for online stores</a></p>
<p></p></td>
</tr>
<tr class="odd">
<td><p>Create a new web part</p></td>
<td><p>You can create new Web parts that allow users to directly modify content, appearance, and behavior of SharePoint Server 2013 site pages.</p>
<p>In the properties for your SharePoint Server 2013 Web Part project, set the <strong>Site URL</strong> to resemble the following:</p>
<p></p>
<p><strong>http://&lt;computer&gt;:40003/sites/RetailPublishingPortal</strong></p>
<p>For more information, see <a href="https://go.microsoft.com/fwlink/?linkid=313704">Creating Web Parts for SharePoint</a>.</p></td>
<td><p><a href="https://go.microsoft.com/fwlink/?linkid=313703">Walkthrough: Creating a Web Part for SharePoint</a></p></td>
</tr>
<tr class="even">
<td><p>Customize master pages</p></td>
<td><p>Master pages define the shared framing elements – the chrome – for all pages in the online store. You can impact the look and feel of your store by customizing master pages with your logo and design.</p></td>
<td><p><a href="https://go.microsoft.com/fwlink/?linkid=328507">Overview of the SharePoint 2013 page model</a></p>
<p><a href="customize-master-pages.md">Customize master pages</a></p>
<p><a href="https://msdn.microsoft.com/library/jj862339.aspx">How to: Apply a master page to a site in SharePoint Server 2013</a></p></td>
</tr>
<tr class="odd">
<td><p>Customize page layouts</p></td>
<td><p>Page layouts contain the page contents and its layout. Each page layout uses a specific master page and can act as a base page for multiple instances of the page layout. Each instance has a different page name. In the starter store, each page has a corresponding page layout. For example, Welcome.aspx has a corresponding file, WelcomeLayout.aspx.</p></td>
<td><p><a href="customize-page-layouts.md">Customize page layouts</a></p>
<p><a href="https://msdn.microsoft.com/library/jj822368.aspx">How to: Create a page layout in SharePoint Server 2013</a></p></td>
</tr>
<tr class="even">
<td><p>Customize display templates</p></td>
<td><p>Display templates control how products are displayed in the pages of an online store. This walkthrough illustrates customizing product display by comparing the SharePoint pages in the user interface in the Contoso and Fabrikam sample online stores.</p></td>
<td><p>Walkthrough: Changing how products are displayed in the Contoso Retail online sample store</p></td>
</tr>
<tr class="odd">
<td><p>Customize the Cascading Style Sheets (CSS) of an online store</p></td>
<td><p>You can customize the appearance and behavior of site pages by customizing the CSS files that are included in the Retail SDK for the Retail online sample stores.</p></td>
<td><p><a href="customize-the-appearance-and-behavior-of-site-pages.md">Customize the appearance and behavior of site pages</a></p>
<p><a href="cascading-style-sheet-css-files-for-retail-online-store.md">Cascading style sheet (CSS) files for Retail online store</a></p>
<p><a href="https://msdn.microsoft.com/library/bb398932.aspx">Walkthrough: Creating and Modifying a CSS File</a></p></td>
</tr>
<tr class="even">
<td><p>Utilize JavaScript</p></td>
<td><p>JavaScript files provide the page layouts with client-side scripting functionality.</p></td>
<td><ul>
<li><p><a href="https://msdn.microsoft.com/library/jj163201.aspx">How to: Complete basic operations using JavaScript library code in SharePoint 2013</a></p></li>
<li><p><a href="https://msdn.microsoft.com/library/jj193034.aspx">JavaScript API reference for SharePoint 2013</a></p></li>
<li><p><a href="http://code.msdn.microsoft.com/sharepoint-2013-execute-a41c49ff">Execute basic tasks using the JavaScript object model</a></p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Customize device channels</p></td>
<td><p>You can customize the sample sites to use different styles based on device channels. The Contoso site includes a master page for displaying the site on a mobile device.</p></td>
<td><p><a href="https://msdn.microsoft.com/library/jj862343.aspx">SharePoint 2013 Design Manager device channels</a></p></td>
</tr>
<tr class="even">
<td><p>Maintain online channels</p></td>
<td><p>You can use the online channel tools to:</p>
<ul>
<li><p>Clean up an online channel.</p></li>
<li><p>Update the channel record ID or operating unit number for the SharePoint web application, web site, and publishing job.</p></li>
<li><p>Configure the publishing job.</p></li>
</ul></td>
<td><p><a href="microsoft-dynamics-ax-for-retail-online-channel-tools.md">Microsoft Dynamics AX for Retail online channel tools</a></p></td>
</tr>
</tbody>
</table>


## Configure

The topics listed in the following table help you configure Microsoft Dynamics AX Retail components and the Retail online store in the Microsoft Dynamics AX client.

### ![JJ937972.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ937972.collapse_all(en-us,AX.60).gif")Configure an online store in Microsoft Dynamics AX

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
<td><p>Configure Retail components</p></td>
<td><p>Set up and maintain information for retail operations. This information includes stores, taxes, products, gift cards, promotions, and discounts.</p></td>
<td><p><a href="setting-up-and-maintaining-retail.md">Setting up and maintaining Retail</a></p></td>
</tr>
<tr class="even">
<td><p>Configure retail channel navigation hierarchy</p></td>
<td><p>Create a retail channel navigation category hierarchy to set up a category structure for products that you offer through an online store. You define the category hierarchy and assign products, product attribute groups, and attribute values to the categories. Then assign the category hierarchy to an online store.</p></td>
<td><p><a href="set-up-a-retail-hierarchy.md">Set up a retail hierarchy</a></p>
<p><a href="set-up-attributes-and-attribute-types.md">Set up attributes and attribute types</a></p>
<p><a href="set-up-retail-attribute-groups.md">Set up retail attribute groups</a></p></td>
</tr>
<tr class="odd">
<td><p>Add online store to the organization hierarchy</p></td>
<td><p>Before you can assign product assortments or fulfill orders for the online store that you created, or generate reports that include information from it, you must assign the store to one or more organization hierarchies. At a minimum, you must assign the online store to an organization hierarchy that includes product assortments.</p></td>
<td><p><a href="set-up-an-online-store.md">Set up an online store</a></p></td>
</tr>
<tr class="even">
<td><p>Add modes of delivery to the online store</p></td>
<td><p>Select the delivery methods that are offered by the online store.</p></td>
<td><p><a href="set-up-an-online-store.md">Set up an online store</a></p></td>
</tr>
<tr class="odd">
<td><p>Map attributes and add metadata</p></td>
<td><p>Select the options that indicate how the attributes for each category or channel product should behave in the online store on the SharePoint site.</p></td>
<td><p><a href="set-up-an-online-store.md">Set up an online store</a></p></td>
</tr>
</tbody>
</table>


### ![JJ937972.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ937972.collapse_all(en-us,AX.60).gif")Configure online store products in Microsoft Dynamics AX

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
<td><p>Add assortments to the online store</p></td>
<td><p>Add the assortments that include the products that you offer in an online store.</p></td>
<td><p><a href="set-up-an-online-store.md">Set up an online store</a></p></td>
</tr>
<tr class="even">
<td><p>Manage catalogs</p></td>
<td><p>Use product catalogs to identify the products that you want to offer in your stores.</p></td>
<td><p><a href="key-tasks-create-retail-product-catalogs.md">Key tasks: Create retail product catalogs</a></p></td>
</tr>
<tr class="odd">
<td><p>Manage prices</p></td>
<td><p>Set up and use price groups, which are the central link between prices and discounts, and channels, catalogs, affiliations, and loyalty programs.</p></td>
<td><p><a href="setting-up-prices-using-price-groups.md">Setting up prices using price groups</a></p>
<p><a href="setting-up-taxes.md">Setting up taxes</a></p></td>
</tr>
<tr class="even">
<td><p>Manage discounts</p></td>
<td><p>Set up and manage price adjustments and four different kinds of discounts.</p></td>
<td><p><a href="setting-up-price-adjustments-and-discounts.md">Setting up price adjustments and discounts</a></p></td>
</tr>
<tr class="odd">
<td><p>Manage shipping charges</p></td>
<td><p>Set up and manage the shipping charges that are specific to the online store.</p></td>
<td><p><a href="set-up-shipping-charges-for-online-stores.md">Set up shipping charges for online stores</a></p></td>
</tr>
<tr class="even">
<td><p>Manage modes of delivery</p></td>
<td><p>Manage the modes of delivery that are offered by the online store.</p></td>
<td><p><a href="set-up-modes-of-delivery.md">Set up modes of delivery</a></p></td>
</tr>
</tbody>
</table>


### ![JJ937972.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ937972.collapse_all(en-us,AX.60).gif")Set up data exchange between Microsoft Dynamics AX and the online store

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
<p><a href="set-up-a-channel-profile.md">Set up a channel profile</a></p>
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
<td><p>After online store settings and data exchange settings have been configured in Microsoft Dynamics AX, run jobs to distribute data to the online store database.</p>
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
</tbody>
</table>

  


