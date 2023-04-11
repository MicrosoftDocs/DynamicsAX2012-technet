---
title: Getting started with customizing the Retail online sample store
TOCTitle: Getting started with customizing the Retail online sample store
ms:assetid: 78860e27-5f80-4b97-a529-460403e021d6
ms:mtpsurl: https://technet.microsoft.com/library/Dn741227(v=AX.60)
ms:contentKeyID: 62219119
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Getting started with customizing the Retail online sample store 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

Retail in Microsoft Dynamics AX 2012 R3 includes starter stores that you can customize: the Contoso store that sells electronics and the Fabrikam store that sells clothing. These stores are built on the Microsoft SharePoint Server 2013 cross-site publishing platform. Source code and sample customizations for the starter stores are included in the [Retail SDK](install-retail-sdk-retail-pos-plug-ins.md).

Before you begin working with the Retail online sample stores, you should understand the technologies that support the online stores.

  - To understand the capabilities in Microsoft SharePoint Server 2013, see [Build sites for SharePoint 2013](https://go.microsoft.com/fwlink/?linkid=394770&clcid=0x409).

  - In AX 2012, you set up Retail catalogs as part of configuring an online store. For more information, see [Set up an online store](set-up-an-online-store.md) and [Configure online store products in Microsoft Dynamics AX](online-store.md).

  - For a step-by-step guide to creating an online shopping site by using SharePoint, see [How to set up a product-centric website in SharePoint Server 2013](https://go.microsoft.com/fwlink/?linkid=394769&clcid=0x409).

The following articles can help you to understand the capabilities and design of the Retail online sample stores.

  - [System architecture for the Retail online store](architecture-of-the-microsoft-dynamics-ax-retail-online-store.md)

  - [Retail online store publishing architecture](retail-online-store-publishing-architecture.md)

The following table lists some of the common tasks in customizing a starter store.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>How do I</p></th>
<th><p>Topics</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Understand the lifecycle of a Retail online store</p></td>
<td><p><a href="online-store.md">Online Store</a></p></td>
</tr>
<tr class="even">
<td><p>View the functionality and appearance of the online sample stores on a demonstration virtual machine</p></td>
<td><p><a href="https://go.microsoft.com/fwlink/?linkid=394231&amp;clcid=0x409">Microsoft Dynamics AX 2012 Solution Demos</a>*</p></td>
</tr>
<tr class="odd">
<td><p>Learn how the Retail online sample stores authenticate users and administrators, and learn how to add a logon provider such as Facebook</p></td>
<td><p><a href="authenticating-users-in-retail-online-sample-stores.md">Authenticating users in Retail online sample stores</a></p></td>
</tr>
<tr class="even">
<td><p>Create customizations of the components of the Retail online sample stores</p></td>
<td><p><a href="components-of-the-retail-online-sample-store.md">Components of the Retail online sample store</a></p></td>
</tr>
<tr class="odd">
<td><p>Extend customer data in the online store</p></td>
<td><p><a href="walkthrough-adding-a-table-for-customer-preferences-to-the-ax-2012-database.md">Walkthrough: Adding a table for customer preferences to the AX 2012 database</a></p>
<p><a href="walkthrough-extending-the-crt-to-add-customer-preference-data-for-retail-clients.md">Walkthrough: Extending the CRT to add customer preference data for Retail clients</a></p>
<p><a href="walkthrough-extending-retail-data-distribution-infrastructure-for-customer-preferences.md">Walkthrough: Extending retail data distribution infrastructure for customer preferences</a></p>
<p><a href="walkthrough-adding-customer-preferences-to-the-retail-online-sample-store.md">Walkthrough: Adding customer preferences to the Retail online sample store</a></p></td>
</tr>
<tr class="even">
<td><p>Customize the appearance and behavior of the user interface for the Retail online sample store</p></td>
<td><p><a href="customize-the-appearance-and-behavior-of-site-pages.md">Customize the appearance and behavior of site pages</a></p></td>
</tr>
<tr class="odd">
<td><p>Debug customizations in the Retail online sample stores</p></td>
<td><p><a href="debug-code-in-a-retail-online-sample-store.md">Debug code in a Retail online sample store</a></p></td>
</tr>
<tr class="even">
<td><p>Deploy customizations to a test environment</p></td>
<td><p><a href="quick-guide-how-to-customize-a-microsoft-dynamics-ax-for-retail-online-store.md">Quick Guide: How to customize a Microsoft Dynamics AX for Retail online store</a></p></td>
</tr>
<tr class="odd">
<td><p>Use tools to help you configure publishing jobs, update the channel against which the online store operates, and clean up your SharePoint site.</p></td>
<td><p><a href="microsoft-dynamics-ax-for-retail-online-channel-tools.md">Microsoft Dynamics AX for Retail online channel tools</a></p></td>
</tr>
</tbody>
</table>



> [!NOTE]
> <P>*To access this site, you must be enrolled in a service plan.</P>



## Understanding the functionality of Retail online sample stores

Before you begin to plan and design your customizations, consider the current functionality of the starter stores.

The Retail online sample stores extend the product catalogs and business data managed in Microsoft Dynamics AX 2012 to online shoppers. All the code for the Retail online samples store is available for you to customize in the [Retail SDK](retail-sdk.md). The code supports sales transactions, manages authentication for new and returning customers, and manages data by using the Commerce Runtime (CRT).

### ![Dn741227.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn741227.collapse_all(en-us,AX.60).gif")Data flow in Retail online sample stores

Data in the Retail online sample stores is stored in the AX 2012 database and two SharePoint site collections. Product catalog data includes all data about product items: for example, color, size, and description. Other data displayed on the store pages includes information about customer accounts, transactions, and store locations. These two types of data, product catalog data and publishing portal data, are stored in two site collections that are located in separate web applications. For more information about these site collections that includes how security is implemented, see the [Site collections section](architecture-of-the-microsoft-dynamics-ax-retail-online-store.md) in the article [Architecture of the Microsoft Dynamics AX Retail online store](architecture-of-the-microsoft-dynamics-ax-retail-online-store.md).

### ![Dn741227.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn741227.collapse_all(en-us,AX.60).gif")Customizing product catalog data

You control the products that appear in your online store by configuring catalogs and data distribution parameters in Microsoft Dynamics AX 2012 when you configure the online channel. For more information, see [Configure online store products in Microsoft Dynamics AX](online-store.md).

The Retail online sample stores display products by using sample data in AX 2012. Several display templates are provided when you install the sample stores. You can find them in the folder that is available when you [map a network drive](map-a-network-drive-to-the-sharepoint-2013-files-for-online-stores.md). The path to the folder resembles the following:

Z:\\\_catalogs\\masterpage\\Display Templates\\Content Web Parts

To customize the appearance of products in the sample stores, you can:

  - Use standard SharePoint Content Search Web Parts to display the products. To view the web parts for the Retail online sample stores, open the SharePoint Central Administration page and then click the **Site Settings** button and then click **Web parts** under **Web Designer Galleries**. For example, the Product Gallery page uses the Product Gallery web part. For more information, see [Content Search Web Part in SharePoint 2013](https://msdn.microsoft.com/library/office/jj163789\(v=office.15\).aspx).

  - Modify the sample display templates that are provided by changing code in the HTML files on the mapped drive. Each HTML file has a corresponding .js file that SharePoint updates automatically after any changes that you make. For more information about mapping a network drive, see [Map a network drive to the SharePoint 2013 files for online stores](map-a-network-drive-to-the-sharepoint-2013-files-for-online-stores.md).

  - Customize the CSWPs in the sample stores. For more information, see [Edit existing Web Parts in SharePoint 2013](https://go.microsoft.com/fwlink/?linkid=395066&clcid=0x409).

### ![Dn741227.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn741227.collapse_all(en-us,AX.60).gif")Managing data in the store pages

The data distribution infrastructure manages data transfer from AX 2012 to the channel database. For example, data such as customer name and address are displayed in the Contoso online sample store. For more information, see [Configure and schedule retail data distribution](configure-and-schedule-retail-data-distribution.md).

CRT services support the transfer of data in the channel database to the online store. For more information, see [Services Overview for Commerce Runtime](services-overview-for-commerce-runtime.md).

The Retail online sample stores use a model-view-controller pattern to present data on store pages. Data from the CRT services is mapped to the object model and then to the view model in code that supports the store pages. For an example that sets up this mapping for a new data element, see [Walkthrough: Adding customer preferences to the Retail online sample store](walkthrough-adding-customer-preferences-to-the-retail-online-sample-store.md).

### ![Dn741227.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn741227.collapse_all(en-us,AX.60).gif")Customizing the appearance of store pages

You can customize the appearance of store pages in two ways. You can:

  - Customize the pages that are available on the mapped network drive. For more information, see [Map a network drive to the SharePoint 2013 files for online stores](map-a-network-drive-to-the-sharepoint-2013-files-for-online-stores.md) and [Customize the appearance and behavior of site pages](customize-the-appearance-and-behavior-of-site-pages.md).

  - Customize the pages in the source code provided in the Retail SDK in the Online Channel\\Storefront folder. Open the Storefront.sln solution to view the code. After you rebuild the solution, you can [deploy your changes](quick-guide-how-to-customize-a-microsoft-dynamics-ax-for-retail-online-store.md) to create your customized site.

For more information about each component and the data elements that are included in the Retail online sample stores, see [Components of the Retail online sample store](components-of-the-retail-online-sample-store.md).

## See also

[Retail SDK](retail-sdk.md)

  


