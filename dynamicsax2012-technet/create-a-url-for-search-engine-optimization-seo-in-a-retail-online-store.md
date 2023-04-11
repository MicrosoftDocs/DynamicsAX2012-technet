---
title: Create a URL for search engine optimization (SEO) in a Retail online store
TOCTitle: Create a URL for search engine optimization (SEO) in a Retail online store
ms:assetid: ed13dd2d-014a-41ab-bddb-4010b78d7e87
ms:mtpsurl: https://technet.microsoft.com/library/Dn741460(v=AX.60)
ms:contentKeyID: 62219739
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Create a URL for search engine optimization (SEO) in a Retail online store 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_


> [!NOTE]
> <P>This topic applies only to installations of Retail in Microsoft Dynamics AX 2012 R2.</P>



To improve search engine optimization (SEO) in a Retail online store, you can add product names to the URLs on your site pages. Search engines use keywords in URLs to return search results. When customers type product names into a search engine, they will see your store pages returned if you have included those product titles in your catalog URLs.

To create these user-friendly URLs you set values on the **Catalog Source Settings** page in the **Site Settings** area in SharePoint.

## Create a user-friendly URL that contains the product name of an item from the catalog in the Contoso online sample store

The following procedure describes how to include a product name in a URL.

### To create a URL that contains a product title

1.  Visit http://\<*your SharePoint server name*\>:40003/sites/RetailPublishingPortal/\_layouts/15/ManageCatalogSources.aspx.

2.  Click the name of the catalog from the list under **Catalog Name**. If you deployed the Contoso online sample store without customizations, the catalog name may resemble the following:
    
    **Retail Product Catalog – UncategorizedList\_000**

3.  On the **Catalog Source Settings** page, set **Catalog Item URL Behavior** to **Make URLs relative to this site**.

4.  In the **Catalog Item URL Format** area, select **Construct a URL format from catalog properties**.

5.  Add the desired **Available Fields** to the **Selected Fields** list.
    
    For example, select the **Title** field from the list of **Available Fields** and then click **Add**. Move **Title** to the top of the list.

6.  Click **Ok** to save your changes.
    
    Notice that for the URL displayed earlier in this section the **Ok** button changes to include the fields you have selected. For example, you can select **Title** and move it to the top of the list of **Selected Fields** in the Contoso online sample store. The original URL has the elements in the following example.
    
    http://\< *your SharePoint server name*\>:40003/sites/RetailPublishingPortal/TermRoot/Term/\[ProductCatalogGroupNumberOWSTEXT\]/\[ProductCatalogItemNumberOWSTEXT\]
    
    After moving **Title** to the top of the list, the URL contains the value for **Title** (in other words, the product name) as shown in the following example.
    
    http:// \<*your SharePoint server name*\>:40003/sites/RetailPublishing Portal/TermRoot/Term/**Title**/\[ProductCatalogGroupNumberOWSTEXT\]/\[ProductCatalogItemNumberOWSTEXT\]
    

    > [!NOTE]
    > <P>The numbers for ProductCatalogGroupNumber and ProductCatalogItemNumber must be retained at the end of the URL string to make sure that the product can be uniquely identified.</P>



7.  Close and re-open the browser to view your changes in the URLs for the products.
    

    > [!NOTE]
    > <P>Be sure to specify the site by using portal number 40002, in order to view what an end-user customer sees. For example, you might see a URL that resembles the following example to locate the item that has the title <STRONG>Contoso Multi-line phone 20m30</STRONG>: Http:// <EM>&lt;your-SharePoint-server-name&gt;</EM>:40002/ sites/RetailPublishingPortal/phones/home-and-office-phones/Contoso%20Multi-line%20phones%20M30/22565424432/22565424433.</P>



If you want to add other fields to the **Available Fields** list, you can create additional attributes for the catalog. After you add the attributes to the channel, you republish the channel and the catalog. For more information about how to set up attributes, see [Set up an online store](set-up-an-online-store.md).

## See also

[Search Engine Optimization (SEO) in SharePoint Server 2013](https://go.microsoft.com/fwlink/?linkid=389180)

[White Paper: Optimizing SharePoint Server 2013 websites for Internet search engines](https://go.microsoft.com/fwlink/?linkid=389181)

  


