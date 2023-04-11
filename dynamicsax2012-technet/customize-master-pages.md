---
title: Customize master pages
TOCTitle: Customize master pages
ms:assetid: 89b478b3-b920-4eb8-8100-5cc10168e03d
ms:mtpsurl: https://technet.microsoft.com/library/Dn151159(v=AX.60)
ms:contentKeyID: 53095773
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Customize master pages 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

The Microsoft Dynamics AX 2012 R2 Retail starter store is a site built by using the commerce runtime (CRT) and the new site authoring and publishing model in Microsoft SharePoint Server 2013. For more information, see [Overview of the SharePoint 2013 page model](https://msdn.microsoft.com/library/jj191506.aspx). You can use the Retail starter store as a basis for developing your own online store. To customize the shared framing elements such as the header and footer for all the pages in your site, you can modify the site’s master pages.

This topic shows you how to customize a master page by updating the Welcome page of the starter store.

### To update a master page

1.  Open a web browser and navigate to the Welcome page for the starter store. Typically, the URL for the Welcome page resembles the following:
    
    http://\<your-server-name\>:40002/sites/RetailPublishingPortal
    

    > [!NOTE]
    > <P>Observe the behavior of the page. A slide show cycles through three pictures representing product categories. At the top left-hand side of the page, you can see the Contoso logo.</P>



2.  Open a web browser on a computer where you are logged in using [the administrative account for SharePoint](https://technet.microsoft.com/library/ee662513.aspx).

3.  Navigate to the **Site Settings** page of the store. Use port 40003 and sign in with administrative credentials. The link to the **Site Settings** page is typically found at a URL that resembles the following:
    
    http://\<computer-name\>:40003/sites/RetailPublishingPortal/\_layouts/15/settings.aspx
    

    > [!TIP]
    > <P>Add this page to your <STRONG>Favorites</STRONG> to make it easy to return to it in the future.</P>



4.  Click **Master pages and page layouts** in **Web Designer Galleries** to view a list of files in the **Master Page Gallery** page.

5.  Right-click a file that you want to edit, such as **Storefront.master**, and then click **Check Out**.

6.  Right-click the file and then click **Download a Copy**.

7.  Edit the file by using Visual Studio or another editor. For example, in the following code from **Storefront.master**, you can change the logo file that is displayed on each page. The file is named logo\_Contoso\_main.png. You can edit that file or replace the file name with the name of a file that contains a graphic of similar size to display your company logo. The following code shows the path and file name of the logo in the **Storefront.master** file:
    
        <div class="msax-Main">
                            <div class="s4-notdlg msax-LogoBar">
                                <div class="msax-Logo">
                                    <a id="A1" href="<% $SPUrl:~sitecollection/ %>" runat="server">
                                        <img src="/_layouts/15/Images/Storefront/logo_Contoso_main.png" />
                                    </a>
                                </div>

8.  To upload the file and add your changes to the site, click **Upload Document** on the **Files** ribbon.
    

    > [!TIP]
    > <P>This procedure illustrates one way of changing master pages and page layouts for the online starter store. For more information about how to use Microsoft SharePoint Server 2013 to modify the visual site design, see <A href="https://msdn.microsoft.com/library/jj733518.aspx">Develop the site design in SharePoint 2013</A>.</P>



9.  Refresh the Welcome page in your initial browser session to see your changes.


> [!NOTE]
> <P>You can edit the master page files directly by mapping a network drive. For more information, see <A href="map-a-network-drive-to-the-sharepoint-2013-files-for-online-stores.md">Map a network drive to the SharePoint 2013 files for online stores</A>.</P>



## See also

[How to: Apply a master page to a site in SharePoint Server 2013](https://msdn.microsoft.com/library/jj862339.aspx)

  


