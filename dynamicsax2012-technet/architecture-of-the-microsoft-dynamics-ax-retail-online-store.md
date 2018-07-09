---
title: Architecture of the Microsoft Dynamics AX Retail online store
TOCTitle: Architecture of the online store
ms:assetid: 009f2b6d-b7ea-4fb9-b75b-98b26f89c1cc
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn194016(v=AX.60)
ms:contentKeyID: 52348271
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Architecture of the Microsoft Dynamics AX Retail online store [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

The Microsoft Dynamics AX Retail online store enables you to deploy, manage, and customize an online sales channel that is fully integrated with Microsoft Dynamics AX. The online store is built on the Microsoft SharePoint Server 2013 cross-site publishing platform. Cross-site publishing uses one or more authoring site collections to author and store content, and one or more publishing site collections to control the design of the site and to show content. The authoring site collection can contain catalogs such as Pages libraries, and lists of items that are tagged with metadata. These catalogs are indexed by the search system and made available to the Publishing Portal. The Publishing Portal displays previously indexed data on web pages by using search-driven Web Parts.

This topic describes the architecture, features, and components of the Retail online store. Before you continue, we suggest that you learn about the features and architecture of SharePoint cross-site publishing. For more information, see [Plan for cross-site publishing in SharePoint Server 2013](http://go.microsoft.com/fwlink/?linkid=282721) and [Plan the logical architecture for cross-site publishing in SharePoint Server 2013](http://go.microsoft.com/fwlink/?linkid=285203).

## Features and components of the Retail online store

This section describes the features and components of the Retail online store. Figure 1 shows the logical architecture and the flow of information between some of the features and components discussed in this section.

![Online store](images/JJ937972.OnlineStoreArchitecture(en-us,AX.60).jpg "Online store")

Figure 1 High-level architecture of the Retail online store

### ![Dn194016.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn194016.collapse_all(en-us,AX.60).gif")Real-time Service

The Commerce Data Exchange: Real-time Service is a Windows Communication Foundation (WCF) service that uses .NET Business Connector to facilitate communication between Microsoft Dynamics AX Retail headquarters and the Microsoft Dynamics AX commerce runtime (CRT). In previous releases, this service was called the Retail Transaction Service. This service is installed by using Microsoft Dynamics AX Setup. For more information about this service, see [Install Commerce Data Exchange: Real-time Service (Retail Transaction Service)](install-commerce-data-exchange-real-time-service-retail-transaction-service.md).

### ![Dn194016.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn194016.collapse_all(en-us,AX.60).gif")Commerce Data Exchange: Async Server

Commerce Data Exchange: Async Server is part of the system for asynchronous data exchange between Microsoft Dynamics AX and retail channels such as the Retail online store. Async Server is installed at headquarters and communicates with Microsoft Dynamics AX. For more information, see [Commerce Data Exchange: Async Server](commerce-data-exchange-async-server.md).

### ![Dn194016.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn194016.collapse_all(en-us,AX.60).gif")Commerce Data Exchange: Async Client

Commerce Data Exchange: Async Client is part of the system for asynchronous data exchange between Microsoft Dynamics AX and retail channels such as the Retail online store. Async Client is installed at the channel, and communicates with the channel database. Typically, you will install one instance of Async Client for each channel. For more information, see [Commerce Data Exchange: Async Client](commerce-data-exchange-async-client.md).

### ![Dn194016.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn194016.collapse_all(en-us,AX.60).gif")Commerce runtime

The Microsoft Dynamics AX commerce runtime is a set of .dlls that perform business logic and data processing for an online store. The CRT has four layers (data access, services, workflow, API) and a database. For more information about the CRT, see [Commerce Runtime](commerce-runtime.md).

### ![Dn194016.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn194016.collapse_all(en-us,AX.60).gif")Search

The Microsoft SharePoint Server 2013 cross-site publishing platform uses Microsoft FAST Search and search-driven pages to dynamically display content for customers. For more information about FAST Search in cross-site publishing, see [Plan search for cross-site publishing sites in SharePoint Server 2013](http://go.microsoft.com/fwlink/?linkid=286142)

### ![Dn194016.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn194016.collapse_all(en-us,AX.60).gif")Term sets

You use term sets to tag catalog content such as pages or list items on the authoring site. By doing this, terms help categorize the content into a hierarchy. These same terms are later used on the publishing site to issue queries, show information about category and catalog item pages, create friendly URLs, and for managed navigation. For more information, see [Plan terms and term sets in SharePoint Server 2013](http://go.microsoft.com/fwlink/?linkid=282752).

### ![Dn194016.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn194016.collapse_all(en-us,AX.60).gif")Retail online store databases

When you deploy the online store, the system creates the following databases in Microsoft SQL Server.

  - **Channel database(s)**: The online store uses this database as a data store before pushing data into SharePoint. By default, the database is named AxRetailSP. Settings for this database are stored in the oob-topology.xml file under Settings/Channel.

  - **Identity Provider database**: This database stores user credentials for forms-based authentication. By default, the database is named SPFBA. Settings for this database are stored in the oob-topology.xml file under Settings/IdentityProvider.

  - **Custom Claims Provider database**: This database stores the mapping between a user’s identify and their Microsoft Dynamics AX customer number when the user has created an account. By default, the database is named SPAuthZ. Settings for this database are stored in the oob-topology.xml file under Settings/CustomClaimsProvider.

Figure 2 provides a detailed view of the Microsoft Dynamics AX Retail online store and SharePoint features and components.

![Expanded architecture of the Retail online store](images/Dn194016.Onlinestoreexpandedview(en-us,AX.60).jpg "Expanded architecture of the Retail online store")

Figure 2 Detailed view of the Retail online store architecture

## The starter stores

Microsoft Dynamics AX 2012 for Retail includes two Retail online “starter” stores. The Contoso store is modeled after a fictitious online electronics retailer. The Fabrikam store is modeled after a fictitious online clothing store. When you install the Retail online store by using Setup.exe or PowerShell, you specify which starter store to deploy in your environment. You can then customize and rebrand the starter store to meet your needs. The starter stores consist of the following site collections and controls.

### ![Dn194016.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn194016.collapse_all(en-us,AX.60).gif")Site collections

The product catalog and publishing portal site collections are located in separate web applications. The product catalog content web application uses AD DS to authenticate content authors. The publishing portal web application uses AD DS authentication for designers and forms-based authentication for web users. This web application is configured to allow anonymous access for web users. The product catalog site collection contains a list of product data, including the Microsoft Dynamics AX navigational hierarchy which is stored in the SharePoint Term Store. Those lists created by the online store publishing process are shared.

Internal users such as designers and other content authors have Contribute permission level to add, update, and delete items in the asset library. The asset library is added to the Suggested Content Browser Locations list for the authoring and product catalog site collections so that content authors can use those assets in their content.The search system indexes content from the authoring site and the product catalog site collection. When a user views a page on one of the publishing sites, queries from Search Web Parts on that page are sent to the search index. Results are returned from the search index, and shown in the Search Web Parts on the page.

Figure 3 provides a detailed view of the web applications and site collections that are created on the SharePoint server when you deploy the Retail online store. Figure 3 also lists the associated classes for the applications and site collections.

![Architecture of the online store site collections](images/Dn194016.OnlineStoreWebAppsAndSitesArch(en-us,AX.60).jpg "Architecture of the online store site collections")

Figure 3 Detailed view of the Retail online store web applications and site collections

The Microsoft Dynamics AX Connector (also named the Channel Connector) is a SharePoint service publishing job that runs in the context of the OWSTimer.exe service, which is standard SharePoint Timer Windows service. The publishing job retrieves updated product, product schema, category hierarchy information from the channel database and pushes it into the product catalog database. The information is then crawled by Search.

The Secure Token Service is a SharePoint service that is used for validating forms-based authentication users.

### ![Dn194016.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn194016.collapse_all(en-us,AX.60).gif")Controls

The starter online store includes the following customizable controls.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Control type</p></th>
<th><p>Available in starter store</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Page layouts</p></td>
<td><p>Address edit</p>
<p>Associate customer</p>
<p>Change password</p>
<p>Checkout confirm</p>
<p>Facebook logon</p>
<p>Issue gift card</p>
<p>Logon</p>
<p>Loyalty</p>
<p>My account</p>
<p>Order review</p>
<p>Order confirm</p>
<p>Order history</p>
<p>Product details</p>
<p>Product gallery</p>
<p>Product quick view</p></td>
</tr>
<tr class="even">
<td><p>Display templates</p></td>
<td><p>Contoso_Default_Item_ProductDetails</p>
<p>Contoso_Default_Item_ProductGallery</p>
<p>Contoso_Default_Item_ProductQuickView</p>
<p>Control_KitRetailListWithPaging</p>
<p>Control_ProductVariants</p>
<p>Control_RetailListWithCarouselPaging</p>
<p>Control_RetailListWithPaging</p>
<p>Control_RetailListWithPagingNoCrt</p>
<p>Fabrikam_Default_Item_ProductDetails</p>
<p>Fabrikam_Default_Item_ProductGallery</p>
<p>Fabrikam_Default_Item_ProductQuickView</p>
<p>Filter_RetailMultiValue</p>
<p>Filter_RetailMultiValue_Body</p>
<p>GiftCard_Item_ProductDetails</p>
<p>GiftCard_ProductVariants</p>
<p>Item_KitComponentDetails_Contoso_Default</p>
<p>Item_Recommended</p>
<p>Item_SelectComponentSubstitutesQuickView_Contoso_Default</p></td>
</tr>
<tr class="odd">
<td><p>Controls/Web parts</p></td>
<td><p><a href="shopping-cart.md">Shopping Cart</a></p>
<p>Mini shopping cart</p>
<p>Order history</p>
<p>Address – display, edit</p>
<p>Customer – display, edit</p>
<p>Wish List</p>
<p>Category landing</p>
<p>Welcome bar</p>
<p>Store product availability</p></td>
</tr>
</tbody>
</table>


## See also

[Online Store](online-store.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

