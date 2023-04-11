---
title: Customize page layouts
TOCTitle: Customize page layouts
ms:assetid: aa55e648-cb03-41e7-a961-0748cbd726bf
ms:mtpsurl: https://technet.microsoft.com/library/Dn151158(v=AX.60)
ms:contentKeyID: 53095771
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Customize page layouts 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

The Microsoft Dynamics AX 2012 R2 Retail starter store is a site built by using the new site authoring and publishing model in Microsoft SharePoint Server 2013. You can use the Retail starter store as a basis for developing your own online store. You can customize individual site pages by modifying the page layout files.

Each page layout uses a specific master page, and each page has a corresponding page layout. For example, the welcome page for the site, Welcome.aspx, has a corresponding page layout file called WelcomeLayout.aspx. For more information about the relationship of master pages and page layouts to site pages, see [Overview of the SharePoint 2013 page model](https://msdn.microsoft.com/library/jj191506.aspx).

This topic shows you how to customize a page layout by updating the starter store’s welcome page layout.

### To update a page layout

1.  Open a web browser and navigate to the Welcome page for the starter store. Typically, the URL for the Welcome page resembles the following:
    
    http://\<your-server-name\>:40002/sites/RetailPublishingPortal
    

    > [!NOTE]
    > <P>Observe the behavior of the page. A slide show cycles through three pictures representing product categories. At the top left-hand side of the page, you can see the Contoso logo.</P>



2.  Open another web browser on a computer where you are logged in using [the administrative account for SharePoint](https://technet.microsoft.com/library/ee662513.aspx).

3.  Navigate to the **Site Settings** page of the store. Use port 40003 and sign in with administrative credentials. The link to the **Site Settings** page is typically found at a URL that resembles the following:
    
    http://\<computer-name\>:40003/sites/RetailPublishingPortal/\_layouts/15/settings.aspx
    

    > [!TIP]
    > <P>Add this page to your <STRONG>Favorites</STRONG> to make it easy to return to it in the future.</P>



4.  Click **Master pages and page layouts** in **Web Designer Galleries** to view a list of files in the **Master Page Gallery** page.

5.  Right-click a file that you want to edit, such as **WelcomeLayout.aspx**, and then click **Check Out**.

6.  Right-click the file and then click **Download a Copy**.

7.  Edit the file by using Visual Studio or another editor. For example, the following code from **WelcomeLayout.aspx** specifies the names of the tabs on the Welcome page.
    
        <div class="msax-tabs">
                <ul>
                    <li><a onclick="return false;" href="#tabs-1">Customer favorites</a></li>
                    <li><a onclick="return false;" href="#tabs-2">Staff recommendations</a></li>
                    <li><a onclick="return false;" href="#tabs-3">Shop by brand</a></li>
                    <li><a onclick="return false;" href="#tabs-4">Clearance items</a></li>

8.  Change the names of the tabs by editing the text. You can use the following code to change the names of the tabs:
    
        <div class="msax-tabs">
                <ul>
                    <li><a onclick="return false;" href="#tabs-1">Your favorites</a></li>
                    <li><a onclick="return false;" href="#tabs-2">Our recommendations</a></li>
                    <li><a onclick="return false;" href="#tabs-3">Shop by brand</a></li>
                    <li><a onclick="return false;" href="#tabs-4">Special offers</a></li>

9.  To upload the file and add your changes to the site, click **Upload Document** on the **Files** ribbon.
    

    > [!TIP]
    > <P>This procedure illustrates one way of changing master pages and page layouts for the online starter store. For more information about how to use Microsoft SharePoint Server 2013 to modify the visual site design, see <A href="https://msdn.microsoft.com/library/jj733518.aspx">Develop the site design in SharePoint 2013</A>.</P>



10. Refresh the Welcome page in your initial browser session to see your changes.


> [!NOTE]
> <P>You can edit the page layout files directly by mapping a network drive. For more information, see <A href="map-a-network-drive-to-the-sharepoint-2013-files-for-online-stores.md">Map a network drive to the SharePoint 2013 files for online stores</A>.</P>



## See also

[How to: Create a page layout in SharePoint Server 2013](https://msdn.microsoft.com/library/jj822368.aspx)

  


