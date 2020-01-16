---
title: Retail online store publishing architecture
TOCTitle: Online store publishing architecture
ms:assetid: 9067f24f-8665-4cfa-a5f5-c8abbd38e2db
ms:mtpsurl: https://technet.microsoft.com/library/Dn463983(v=AX.60)
ms:contentKeyID: 56686739
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Retail online store publishing architecture 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic contains conceptual information to help developers and system administrators understand how channels and catalogs are published from the Microsoft Dynamics AX Retail module to an online store in Microsoft SharePoint 2013 Products. Understanding the publishing process can help you develop, manage, and troubleshoot your Retail online store. Before you read this topic, we recommend that you read about SharePoint cross-site publishing concepts. For more information, see [Plan for cross-site publishing in SharePoint Server 2013](https://go.microsoft.com/fwlink/?linkid=282721) and [Plan terms and term sets in SharePoint Server 2013](https://go.microsoft.com/fwlink/?linkid=311567)

Figure 1 shows the architecture and flow of the publishing processes. These processes are described in more detail in this topic.

![Overview of Retail online store publishing](images/Dn463983.RetailPublishOverivew(en-us,AX.60).jpg "Overview of Retail online store publishing")

Figure 1 High-level architecture of Retail online store publishing processes

## Publish a Retail online store channel

To publish the Retail online store channel means to replicate the basic structure of your online store between Microsoft Dynamics AX and SharePoint. You create the basic structure of your online store channel in the Microsoft Dynamics AX Retail module. The following set up tasks must be completed before you can publish the channel:

1.  Add the online store to the organization hierarchy. For more information, see [Create or modify an organization hierarchy](create-or-modify-an-organization-hierarchy.md).

2.  Create the online store and configure properties in Microsoft Dynamics AX. For more information, see [Set up an online store](set-up-an-online-store.md).

3.  Configure category hierarchy of you site. For more information, see [Set up a retail hierarchy](set-up-a-retail-hierarchy.md)

4.  Create the online store in SharePoint. [Install a Retail online store (e-commerce)](install-a-retail-online-store-e-commerce.md).

After you completed these steps, you are ready to publish the product schema to SharePoint. Figure 2 shows the publishing process for a Retail online store channel.

![Publishing process: Retail online store channel](images/Dn463983.RetailOnlineStoreChannelPublishFlow(en-us,AX.60).jpg "Publishing process: Retail online store channel")

Figure 2 Process flow for publishing a Retail online store channel

1.  You create the online store in Microsoft Dynamics AX and publish it from the **Online stores** form. The publish status changes from *Draft* to *In progress*.

2.  Microsoft Dynamics AX takes a snapshot of the category hierarchies (called the Retail hierarchy) and properties.

3.  The Commerce Data Exchange: Async server reads information about the online store, hierarchies, and properties in the Retail store database and sends it to the Commerce runtime (CRT).

4.  The Async server synchronizes the tables in the channel database.

5.  The Retail publishing job, which runs as a SharePoint timer job, receives information about synchronized tables from the CRT API and creates hierarchies for the site that you created in SharePoint.

6.  The Retail publishing job creates term sets in SharePoint.

7.  The Commerce Data Exchange: Real Time Service receives the status of the Retail publishing job actions from the CRT API and publishes that status in Microsoft Dynamics AX. The status shows either *Published* or *Error*.

For the specific procedures to publish a channel, see [Set up an online store](set-up-an-online-store.md). After you published the channel, you can publish a catalog.

## Publish a Retail online store catalog

A Retail product catalog lets you identify the products that you want to offer in your online stores. When you create a catalog, you identify the online stores where the products will be offered, add products, and enhance the product offerings by adding merchandising details. After the catalog is approved, you publish it to make products available in the online store. The following set up tasks must be completed before you can publish a catalog:

1.  Set up retail products and configure hierarchies, assortments, and variants. For more information, see [Setting up retail products](setting-up-retail-products.md)

2.  Set up retail product catalogs and configure attribute groups and workflow. For more information, see [Setting up retail product catalogs](setting-up-retail-product-catalogs.md).

Figure 3 shows the publishing process for a Retail online store catalog.

![Publishing process for a Retail Online Store](images/Dn463983.RetailOnlineStorePublishingProcess(en-us,AX.60).jpg "Publishing process for a Retail Online Store")

Figure 3 Process flow for publishing a Retail online store catalog

1.  Microsoft Dynamics AX reads the product tables in the Retail database.

2.  The Commerce Data Exchange: Async Server synchronizes all products in the channel database.

3.  The CRT/Publishing Connector creates a listing. A listing is an instance of a product for a channel at a given point in time. For example, a product might be “jeans” and the variant might be “red”. The system creates a listing for “red jeans”.

4.  The system determines whether any new attributes were added for the listing. If a new attribute exists, for example if the listing “red jeans” includes a new attribute called “texture”, and this attribute is marked as “Included” at the channel level, then the system creates a custom site column for that attribute. The system creates a new rule for this list item and finishes the process in SharePoint by creating a new row for the “red jeans” listing.

5.  The CRT records the publishing status for the listing.

6.  The Commerce Data Exchange: Async Server synchronizes the publishing status of the “red jeans” listing with all other publishing statuses.

7.  The status shows either *Published* or *Error*.


> [!NOTE]
> <P>To learn more about custom site columns and list items, see <A href="https://go.microsoft.com/fwlink/?linkid=311682">Introduction to Columns</A> and the section titled "Share a library or list as a catalog" in <A href="https://go.microsoft.com/fwlink/?linkid=311683">Configure cross-site publishing in SharePoint Server 2013</A>.</P>



Figure 4 shows the various features of an Microsoft Dynamics AX Retail catalog. When these features are published, they are mapped to the SharePoint cross-site publishing platform.

![Features of the Retail Online Store catalog](images/Dn463983.CatalogFeatures(en-us,AX.60).jpg "Features of the Retail Online Store catalog")

Figure 4 Mapping of Microsoft Dynamics AX catalog features after they are published to SharePoint

## See also

[Update the Publishing Job Configuration](update-the-publishing-job-configuration.md)

[Microsoft Dynamics AX for Retail online channel tools](microsoft-dynamics-ax-for-retail-online-channel-tools.md)

  


