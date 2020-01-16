---
title: Customize the functionality of an online store
TOCTitle: Customize the functionality of an online store
ms:assetid: 661cba1c-017d-474e-aa70-6281428bb21c
ms:mtpsurl: https://technet.microsoft.com/library/Dn169144(v=AX.60)
ms:contentKeyID: 53382653
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Customize the functionality of an online store 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The Microsoft Dynamics AX 2012 R2 Retail starter store is a site built by using the commerce runtime (CRT) and the new site authoring and publishing model in Microsoft SharePoint Server 2013. You can use the Retail starter store as a basis for developing your own online store by calling JavaScript methods for supported events. The starter store includes events that correspond to certain shopping activities such as *add item to shopping cart* and *remove item from shopping cart*. You can use these events to add functionality of your own, in a way that resembles using the [jQuery eventing model](https://go.microsoft.com/fwlink/?linkid=296268&clcid=0x409). You turn your custom functionality on and off by using methods such as OnAddToCart and OffAddToCart. For example, you can change the message that is displayed when an item is added to the shopping cart.

This topic shows you how to change the message that is displayed when an item is added to the shopping cart. It also lists the methods for the types of events that are available to modify the behavior of the starter store.

### To change the message displayed when an item is added to the shopping cart

1.  Open a web browser and move to the Welcome page for the starter store. Typically, the URL for the Welcome page resembles the following:
    
    http://\<your-server-name\>:40002/sites/RetailPublishingPortal
    
    Add some items to the shopping cart.
    

    > [!NOTE]
    > <P>Observe the behavior of the page. When you click <STRONG>Add to cart</STRONG> under one of the items, a popup is displayed with the message <STRONG>Updating shopping cart…</STRONG>.</P>



2.  Navigate to the folders on the computer where the online starter store is deployed. Typically, files that contain JavaScript for the starter store pages are found in a path that resembles the following:
    
    …\\Program Files\\Common Files\\Microsoft Shared\\Web Server Extensions\\15\\TEMPLATE\\LAYOUTS\\Storefront\\js

3.  Open the file Storefront.js. You can use Visual Studio or any editor that you prefer.

4.  Find the line that contains msaxServices.OnAddToCart. The following example shows how to modify the code after line 170.
    
        msaxServices.OnAddToCart(function () {
                // msaxPopupOverlay.show('Updating shopping cart...');
                alert('Adding to cart...');
            });

5.  Refresh the store pages and add an item to the cart. You see the message **Adding to cart…** in the message window. Click **Ok** to continue.

## Extending the Functionality of the Online Store

The starter store is designed to be extensible at many points in the shopping experience. For example, you can add the following JavaScript code in any JavaScript file for a page that includes the shopping cart objects. The following example causes a message to display before an item is added to the shopping cart.

    var addToCartVM = new Microsoft.Dynamics.Retail.SharePoint.Web.UI.ViewModel.AddToCartViewModel(services, $view);
    
    // Performed before AddToCart
    addToCartVM.OnAddToCart(function (event) {
    alert('Adding item to cart');
    });

## Method Names for Supported Events and Objects

The following tables list the method names and objects available for turning on and off functionality for supported events in the view models for the starter store. Typically, the JavaScript code for the view models can be found in a path that resembles the following, after you [map a drive](map-a-network-drive-to-the-sharepoint-2013-files-for-online-stores.md) to the SharePoint Server 2013 files:

Z:\\Scripts\\ViewModel

The following table lists methods for Microsoft.Dynamics.Retail.SharePoint.Web.UI.ViewModel.AddToCartViewModel. The code for this view model is found in the file AddToCart.js.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Method Name</p></th>
<th><p>Data Object Available</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>OnAddToCart, OffAddToCart</p></td>
<td><p>None</p></td>
<td><p>Raised on a call to AddToCart.</p></td>
</tr>
<tr class="even">
<td><p>OnAddToCartSuccess, OffAddToCartSuccess</p></td>
<td><p>ShoppingCart</p></td>
<td><p>Raised after a successful return from AddToCart.</p></td>
</tr>
<tr class="odd">
<td><p>OnAddToCartFailure, OffAddToCartFailure</p></td>
<td><p>None</p></td>
<td><p>Raised if no response is returned from a call to AddToCart.</p></td>
</tr>
</tbody>
</table>


The following table lists methods for the Microsoft.Dynamics.Retail.SharePoint.Web.UI.ViewModel.CheckoutViewModel. The code for this view model is found in the file Checkout.js.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Method Name</p></td>
<td><p>Data Object Available</p></td>
<td><p>Description</p></td>
</tr>
<tr class="even">
<td><p>OnCheckout, OffCheckout</p></td>
<td><p>None</p></td>
<td><p>Raised on a call to the Checkout method.</p></td>
</tr>
<tr class="odd">
<td><p>OnNoItemCheckout, OffNoItemCheckout</p></td>
<td><p>None</p></td>
<td><p>Raised on a successful response to the AddToCart method.</p></td>
</tr>
</tbody>
</table>


The following table lists methods for the Microsoft.Dynamics.Retail.SharePoint.Web.UI.ViewModel.ShoppingCartViewModel. The code for this view model is found in the file ShoppingCart.js.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Method Name</p></td>
<td><p>Data Objects Available</p></td>
<td><p>Description</p></td>
</tr>
<tr class="even">
<td><p>OnBeforeRender, OffBeforeRender</p></td>
<td><p>ShoppingCart</p></td>
<td><p>Raised on a call to the Render method of the shopping cart view.</p></td>
</tr>
<tr class="odd">
<td><p>OnAfterRender, OffAfterRender</p></td>
<td><p>ShoppingCart</p></td>
<td><p>Raised after execution of the Render method of the shopping cart view.</p></td>
</tr>
<tr class="even">
<td><p>OnRemoveFromCart, OffRemoveFromCart</p></td>
<td><p>ShoppingCart</p></td>
<td><p>Raised on a call to the RemoveFromTCart method.</p></td>
</tr>
<tr class="odd">
<td><p>OnUpdateQuantity, OffUpdateQuantity</p></td>
<td><p>ShoppingCart</p></td>
<td><p>Raised on a call to the UpdateQuantitymethod.</p></td>
</tr>
</tbody>
</table>


The following table lists methods for the Microsoft.Dynamics.Retail.SharePoint.Web.UI.ViewModel.MiniShoppingCartViewModel. The code for this view model is found in the file MiniShoppingCart.js.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Method Names</p></td>
<td><p>Data Objects Available</p></td>
<td><p>Description</p></td>
</tr>
<tr class="even">
<td><p>OnBeforeRender, OffBeforeRender</p></td>
<td><p>ShoppingCart</p></td>
<td><p>Raised on a call to the Render method of the MiniShoppingCartViewModel.</p></td>
</tr>
<tr class="odd">
<td><p>OnAfterRender, OffAfterRender</p></td>
<td><p>ShoppingCart</p></td>
<td><p>Raised after execution of the Render method of the MiniShoppingCartViewModel.</p></td>
</tr>
<tr class="even">
<td><p>OnShow, OffShow</p></td>
<td><p>None</p></td>
<td><p>Raised on a call to the Show method of the MiniShoppingCartViewModel.</p></td>
</tr>
<tr class="odd">
<td><p>OnHide, OffHide</p></td>
<td><p>None</p></td>
<td><p>Raised on a call to the Hide method of the MiniShoppingCartViewModel.</p></td>
</tr>
</tbody>
</table>


## See also

[How to use F12 Developer Tools to Debug your Webpages](https://go.microsoft.com/fwlink/?linkid=294914&clcid=0x409)

  


