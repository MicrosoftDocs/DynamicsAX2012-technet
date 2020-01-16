---
title: Wish list
TOCTitle: Wish list
ms:assetid: adc0a086-c90d-4163-a33d-2d71998fe2b2
ms:mtpsurl: https://technet.microsoft.com/library/Dn741452(v=AX.60)
ms:contentKeyID: 62219729
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Wish list 


_**Applies To:** Microsoft Dynamics AX 2012 R3_


> [!NOTE]
> <P>In the Retail online sample store included with Microsoft Dynamics AX 2012 R2, a user’s wish list was implemented as a type of shopping cart.</P>



In Microsoft Dynamics AX 2012 R3 Retail online sample stores, an authenticated user can create one or more named wish lists that contain products that they may want to purchase in the future. Wish list data is stored in the AX 2012 R3 database in the **RetailWishList** and **RetailWishListLines** tables. The data is updated by the [Commerce Data Exchange: Synch service](commerce-data-exchange-synch-service.md) and the [Commerce Data Exchange: Real-time Service](commerce-data-exchange-real-time-service.md).

When an anonymous user clicks on a wish list button, they are redirected to the registration page. For more information about authenticated and anonymous users in the Retail online sample stores, see [Authenticating users in Retail online sample stores](authenticating-users-in-retail-online-sample-stores.md).

## Wish list source code and design

Source code for the wish list display is found in the Storefront.sln solution. This solution is available in the following folder after you install the Retail SDK:

\\Retail SDK\\Online Channel\\Storefront

Services supply data elements for display. Data from the AX 2012 R3 database is represented by entities in the commerce run-time (CRT) object model. Data in the object model is mapped into a view model to be displayed in pages of the Retail online sample stores. Web controls and Cascading Style Sheets (CSS) support the page display.

### ![Dn741452.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn741452.collapse_all(en-us,AX.60).gif")Data elements

In the AX 2012 R3 database, the **RetailWishListTable** table stores the CustomerId (account number) and Name of the wish list. **RetailWishListLineTable** contains one record for each item in the wish list. Each record stores the following information for each item in the wish list: CustomerId, ProductId, Quantity, UnitOfMeasure, and WishListId.

### ![Dn741452.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn741452.collapse_all(en-us,AX.60).gif")Services

In the Storefront.sln solution, the SharePoint.Web.Services project contains source code that supports services and CRT entities. The following table lists the services and interfaces that support the wish list.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Name</p></th>
<th><p>Description</p></th>
<th><p>Link to documentation</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Wish list service</p></td>
<td><p>Represents the AJAX-enabled Windows Communication Foundation (WCF) service.</p></td>
<td><p><a href="wishlistservice-class-microsoft-dynamics-retail-sharepoint-web-services.md">Microsoft.Dynamics.Retail.SharePoint.Web.Services.WishListService</a></p></td>
</tr>
<tr class="even">
<td><p>\ObjectModel\ WishListController.cs</p></td>
<td><p>The controller supports functions that represent actions that can be performed on a wish list. Actions include create a new wish list, rename a wish list, and delete a wish list. To add or remove items from the wish list,</p></td>
<td><p><a href="wishlistcontroller-class-microsoft-dynamics-retail-sharepoint-web-services-objectmodel.md">Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel.WishListController</a></p></td>
</tr>
<tr class="odd">
<td><p>\ObjectModel\ WishListMapper.cs</p></td>
<td><p>The WishListMapper class manages the mappings between the wish list view model and CRT entity. The view model is the representation of the wish list in the online store user interface. The CRT entity is the representation of the wish list data in the channel database.</p></td>
<td><p><a href="wishlistmapper-class-microsoft-dynamics-retail-sharepoint-web-services-objectmodel.md">Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel.WishListMapper</a></p></td>
</tr>
<tr class="even">
<td><p>\ViewModel\WishList.cs</p></td>
<td><p>The wish list view model representation includes the wish list ID, customer ID (account number), wish list name, last modified date, and wish list lines. Each wish list line represents an item in the wish list that includes the following properties: LineId, ProductId, Name (of the product), CustomerId, Quantity, Price, TotalValue. Other properties include the product description, color, size, URL, and ImageURL.</p></td>
<td><p><a href="wishlist-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md">Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.WishList</a></p></td>
</tr>
</tbody>
</table>


### ![Dn741452.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn741452.collapse_all(en-us,AX.60).gif")Controls

In the Storefront.sln solution, the SharePoint.Web.Storefront project contains source code for the wish list control in the \\Controls folder.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Name</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>WishList.ascx.cs</p></td>
<td><p>For more information, see <a href="wishlist-class-microsoft-dynamics-retail-sharepoint-web-storefront-controls.md">WishList</a>.</p></td>
</tr>
<tr class="even">
<td><p>WishList.ascx</p></td>
<td><p>The wish list display control shows the set of wish lists created by a user. It contains the name of the wish list, the last item added, and a set of actions, including delete and rename, that can be performed on the wish list. When a user clicks on the name of a wish list, the wish list line details are displayed.</p></td>
</tr>
</tbody>
</table>


### ![Dn741452.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Dn741452.collapse_all(en-us,AX.60).gif")Page layout and style sheets

You can map a network drive to view the page layout for the wish list. For more information, see [Map a network drive to the SharePoint 2013 files for online stores](map-a-network-drive-to-the-sharepoint-2013-files-for-online-stores.md).

In the Storefront.sln solution, the SharePoint.Web.Storefront project contains Javascript files that support the wish list layout. In the \\Layouts\\Storefront\\js folder, view the WishList.js and WishListDetails.js files for detailed information.

In the Storefront.sln solution, the Share.PointWeb.Storefront project contains source code that supports page display. The following table lists the Cascading Style Sheet (CSS) files in the \\Styles folder that support the wish list.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>File Name</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>WishListSummary.css</p></td>
<td><p>Styles that support the wish list summary.</p></td>
</tr>
<tr class="even">
<td><p>WishListDetails.css</p></td>
<td><p>Styles that support details lines for each wish list.</p></td>
</tr>
</tbody>
</table>


## See also

[Creating WCF Services for ASP.NET AJAX](https://go.microsoft.com/fwlink/?linkid=396549&clcid=0x409)

  


