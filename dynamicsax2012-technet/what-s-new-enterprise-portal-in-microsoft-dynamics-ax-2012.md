---
title: "What's New: Enterprise Portal in Microsoft Dynamics AX 2012"
TOCTitle: "What's New: Enterprise Portal"
ms:assetid: 9c88a619-774e-4808-9ae6-cba4d7f8c316
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dd362012(v=AX.60)
ms:contentKeyID: 35132782
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# What's New: Enterprise Portal in Microsoft Dynamics AX 2012 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Microsoft Dynamics AX provides a set of web sites that give you access to data. On these sites, you can also participate in business processes by using Web-based forms. These sites are collectively called Enterprise Portal for Microsoft Dynamics AX. This topic describes the enhancements and improvements in Enterprise Portal in Microsoft Dynamics AX 2012.

## Support for data partitioning

You can configure Enterprise Portal so that users can access data and reports in a specific partition. By default, Enterprise Portal sites are not configured to use a partition, which means they are partition independent. For more information about partitions, see [What's new: Data partitioning](what-s-new-data-partitioning.md) and [Data partitioning architecture](data-partitioning-architecture.md). For more information about how to configure Enterprise Portal for data partitioning, see [Configure Enterprise Portal to access data in a partition](configure-enterprise-portal-to-access-data-in-a-partition.md).

## New SharePoint platform

Enterprise Portal requires one of the following SharePoint products.

  - Microsoft SharePoint Foundation 2010

  - Microsoft SharePoint Server 2010

  - Microsoft SharePoint Foundation 2013

  - Microsoft SharePoint Server 2013

For a complete comparison between the SharePoint offerings, see [Compare SharePoint Editions](http://go.microsoft.com/fwlink/?linkid=225033) on the web.

## New features and enhancements

## Improved appearance and behavior

The following improvements have been made to the appearance and behavior of Enterprise Portal:

  - **Improved access to common tasks by using an Action Pane**. Enterprise Portal pages include an Action Pane that provides easy access to common tasks. The Action Pane is divided into tabs that can contain button groups. Each button group contains action buttons that you can use to move to other pages and add records to list pages. You can also use the action buttons to perform common tasks for a selected record, such as creating a new sales order for a customer. Developers can customize the buttons that are available on a user's Action Pane.

  - **Improved access to information by using FactBoxes**. FactBoxes display information that is related to a selected record, or information that is displayed in a form or on a list page. Users can customize the type of information that is displayed in FactBoxes.

  - **Improved cue creation by using advanced filtering**. By using the **Advanced filter** option in the Microsoft Dynamics AX client, users can save list items to a cue on their Role Center page.

  - **Enhanced grid support**. In hierarchical grid views, users can now move tasks by using a drag-and-drop operation. Users can also indent or outdent tasks. Users can also select multiple rows at the same time.

  - **Enhanced integration with Microsoft Excel**. Users can export data from grids to Microsoft Excel in static or dynamic mode. In a static export, the data in Excel remains unchanged, unless the user directly modifies the data. In a dynamic export, when the data is refreshed in the database, Excel retrieves the updated data from Microsoft Dynamics AX by using Query Services.

  - **Bookmarks**. For ease of access, users can now create bookmarks for the URLs of specific task pages.

  - **The Microsoft Dynamics Online Connect Gadget Web part**. Enterprise Portal includes the Microsoft Dynamics Online Connect Gadget Web part for Role Centers. The Web part contains a slide deck of links and information that are relevant to a user's role. The Web part includes links to CustomerSource, community content, training materials, and knowledge base articles.

  - **Improved Quick Links**. The **Quick Links** form in Role Center pages has been redesigned to make it easier to create and manage Quick Links.

For more information about these features and enhancements, see [About Enterprise Portal pages](about-enterprise-portal-pages.md) on the web.

## Improved installation and deployment

The following improvements make it easier to install and deploy Enterprise Portal:

  - **No compilation necessary**. In earlier versions, you could not install Enterprise Portal on a server where the initialization checklist was not completed. The installation failed, because the Enterprise Portal X++ classes were not previously compiled on the server. You no longer have to compile these classes to install and deploy Enterprise Portal.

  - **Improved deployment and administration by using the AXUpdatePortal utility**. Microsoft Dynamics AX includes the AxUpdatePortal utility, which you can use to deploy Enterprise Portal on remote servers, create sites, and deploy changes to existing sites.

  - **Enhanced AOT support for 32-bit clients**. In earlier versions, administrators could not deploy changes to Enterprise Portal from the Application Object Tree (AOT) on a 32-bit client to a 64-bit Windows Server. In this version of Microsoft Dynamics AX, administrators can deploy changes from 32-bit clients to 64-bit clients by clicking a button.

For more information about how to install and deploy Enterprise Portal, see [Checklists for deploying Enterprise Portal sites](checklists-for-deploying-enterprise-portal-sites.md). For more information about how to deploy changes to a different server, see [Checklist: Deploy Enterprise Portal changes to a different server](checklist-deploy-enterprise-portal-changes-to-a-different-server.md).

## Improved upgrade

Microsoft Dynamics AX 2012 provides an improved upgrade experience from Enterprise Portal on Windows SharePoint Services 3.0 or Microsoft Office SharePoint Server 2007 to Microsoft SharePoint Foundation 2010 or Microsoft SharePoint Server 2010. However, you must first complete all other Microsoft Dynamics AX upgrade tasks. Earlier deployments must be migrated to Windows SharePoint Services 3.0 or Microsoft Office SharePoint Server 2007 before you can upgrade to Enterprise Portal on Microsoft Dynamics AX 2012. For more information, see [Upgrade Enterprise Portal](upgrade-enterprise-portal.md).

## Improved security administration

Enterprise Portal automatically grants and denies access to data and Web pages according to the role-based security framework in Microsoft Dynamics AX 2012. Before users can view data or Enterprise Portal pages, administrators must configure role-based security. For more information, see [Set up user security in Microsoft Dynamics AX](set-up-user-security-in-microsoft-dynamics-ax.md).

This version of Enterprise Portal also supports flexible authentication. Flexible authentication includes Active Directory Federated Services (ADFS) and form-based authentication. Flexible authentication can help ease administrative overhead if your organization authenticates many external user accounts in Active Directory. For more information, see [Flexible authentication](http://go.microsoft.com/fwlink/?linkid=188717).

## Improved search

Enterprise Portal search is provided by a product-wide feature of Microsoft Dynamics AX that is named Enterprise Search. Enterprise Search lets users search through data, metadata, and documents that are attached to records. Users can search for common nouns, such as 'customer' and 'cash flow report.' Users can also search for specific data, such as a customer name, product ID, or telephone number.

All aspects of crawling, indexing, and retrieving Microsoft Dynamics AX data and metadata for Search are performed by one of the following products:

  - Microsoft SharePoint Foundation 2010 or Microsoft SharePoint Server 2010

  - Microsoft Search Server 2010 or Microsoft Search Server Express 2010

  - Microsoft FAST Search Server 2010

  - Microsoft SharePoint Foundation 2013 or Microsoft SharePoint Server 2013

One of these products must be available in the computing environment before you can install Enterprise Search. For more information about Enterprise Search, see [Enterprise Search](enterprise-search.md).

## Improved page load and data refresh

Role Center pages are now designed to load faster, and to refresh data automatically when a page is loaded.

## See also

[Overview of Enterprise Portal for Microsoft Dynamics AX](overview-of-enterprise-portal-for-microsoft-dynamics-ax.md)

  


