---
title: Set up and configure refiners for a Retail online store
TOCTitle: Set up and configure refiners
ms:assetid: f1a86608-4949-4a3b-8e0a-e373030f8f43
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn458951(v=AX.60)
ms:contentKeyID: 59326703
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Set up and configure refiners for a Retail online store 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes how to set up and configure refiners for a Microsoft Dynamics AX Retail online store. Refiners are a component of search-driven navigation on a web page.

You can add refiners to a page to help users quickly browse to specific content. Refiners are based on managed properties from the search index. For example, in a Retail online store, a refiner could be a color, a brand, or a material for a product in your catalog. If you specify a color refiner, The Refinement Panel Web Part will show the available colors for a product. When users click a specific color, only the selected colors are listed.

Refiners are used with terms in a term set in SharePoint Server 2013 faceted navigation. Faceted navigation helps users browse for content more easily by filtering on refiners that are tied to terms in a term set. By using faceted navigation, you can configure different refiners for different terms in a term set without having to create additional pages. For example, in an Internet business scenario in which a catalog of electronic products is shown, a term set might be used to categorize different products, such as computers or cameras. The same category page is used for both terms. After you enable the managed properties Screen size and Megapixels as refiners, you can configure faceted navigation so that Screen size is shown as a refiner for computers, and Megapixels is shown as a refiner for cameras. This means that you do not have to create additional pages to guide users to content that is relevant for a specific category. For more information, see "Plan refiners and faceted navigation" in [Plan search for cross-site publishing sites in SharePoint Server 2013](http://go.microsoft.com/fwlink/?linkid=325273).

This topic includes the following sections.

  - Map a network drive

  - Configure refiners

  - Configure refiner labels

## Map a network drive

The procedures in this topic require that you map a WebDAV network drive for the Retail online store publishing portal and the product catalog. By default the URLs for the Contoso publishing portal and catalog are as follows:

http://ServerName:40003/sites/RetailPublishingPortal

http://ServerName:40001/sites/RetailProductCatalog

For the Fabrikam publishing portal and catalog, substitute 40003 and 40001 with 50003 and 50001. Use the procedure in the following topic to map a WebDAV network drive for each of these URLS: [Map a network drive to the SharePoint 2013 files for online stores](map-a-network-drive-to-the-sharepoint-2013-files-for-online-stores.md)

## Configure refiners

Use the following procedure to set up and configure refiners for a Retail online store. This procedure describes, as an example, how to configure a Retail price refiner.


> [!NOTE]
> <P>The following procedure requires that you select a display template. You can select one of the default SharePoint templates or you can copy an existing template and customize it. For more information, about default display templates, see the SharePoint Server 2013&nbsp;<A href="http://go.microsoft.com/fwlink/?linkid=328204">Display template reference</A>.</P>



1.  Use Windows Explorer to open the following folder on the RetailPublishingPortal network drive:
    
    %Portal\_Drive%:\\\_catalogs\\masterpage\\Display Templates\\Filters

2.  Copy the following files:
    
    Filter\_MultiValue\_Body.html
    
    Filter\_RetailMultiValue.html

3.  Paste the files into the following folder on the RetailProductCatalog network drive:
    
    %Catalog\_Drive%:\\\_catalogs\\masterpage\\Display Templates\\Filters

4.  Press F5 on the keyboard to refresh the folder view on the RetailProductCatalog network drive. Verify that you see the following four (4) new files in the folder:
    
    Filter\_MultiValue\_Body.html
    
    Filter\_MultiValue\_Body.js
    
    Filter\_RetailMultiValue.html
    
    Filter\_RetailMultiValue.js

5.  In a web browser, open the product catalog site. By default, the URL is http://*ServerName*:40001/sites/RetailProductCatalog

6.  Click **Manage item hierarchy in Term Store**.

7.  On the **Site Settings – Term Store Management Tool** page, in the left pane, expand the **Site Collection–** *ServerName* **–Sites–RetailProductCatalog** node.

8.  Expand **Product Hierarchy** and then click a category.

9.  In the right pane, click the **Faceted Navigation** tab and then click **Customize Refiners**.

10. Locate RetPrice in the list of available refiners. Click **Add**.

11. Select an option from the **Display template** list. For example, select **Retail Multi-value Refinement Item**.

12. Click **Custom** and specify price ranges. For example: 5;10;50;100;500

13. Click **OK** and then click **Save**.

14. Repeat steps 8-12 as needed to create more refiners for the same or for different categories.
    

    > [!IMPORTANT]
    > <P>By default, child categories recursively inherit all refiners specified on a parent category. If you want to specify a different set of refiners for a child category (a common scenario) then you must break inheritance and add specific refiners, as needed. To break inheritance, select a child category and then click <STRONG>Stop inheriting</STRONG>. The <STRONG>Customize refiners</STRONG> button is now active. Click this button to set up additional refiners on the child category.&nbsp;</P>



15. Validate you changes in the publishing portal. Open the portal in a Web browser. By default, the URL is http://*ServerName*:40003/sites/RetailPublishingPortal. Click a category and verify that you see the refiners you created.

## Configure refiner labels

By default, refiner labels display the name of their corresponding managed property. For example, a managed property named RetColor displays a refiner label of RetColor. If you want a refiner label to display something other than the name of the managed property, for example Color, and then you must configure labels as described in the following procedure.

1.  Create a list of each managed property that you want to configure to display a different refiner label. You can create this list in a simple text editor like Notepad.

2.  Add the following prefix string to each managed property in the text editor: rf\_RefinementTitle\_

3.  For each property, add a colon (:) followed by the new refiner label in parentheses. For example:
    
    "rf\_RefinementTitle\_RetColor": "Color"

4.  In Windows Explorer, open the following folder in the RetailPublishingPortal network drive that you mapped earlier in this topic:
    
    %Portal\_Drive%:\\\_catalogs\\masterpage\\Display Templates\\Language Files\\en-us\\
    

    > [!NOTE]
    > <P>This procedure updates a file in the en-us folder, which means this procedure configures English language labels. To configure refiner labels in a different language, modify the following file in a different language folder.</P>



5.  Edit the CustomStrings.js file.

6.  Copy and paste the list of managed properties you created in the text editor into the CustomStrings.js file.

7.  Save your changes in the file and then browse the publishing portal. By default, the URL is http://*ServerName*:40003/sites/RetailPublishingPortal.

## See also

[Quick Guide: How to customize a Microsoft Dynamics AX for Retail online store](quick-guide-how-to-customize-a-microsoft-dynamics-ax-for-retail-online-store.md)

[Online Store](online-store.md)

  


