---
title: ShoppingCartService Methods (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: ShoppingCartService Methods
ms:assetid: Methods.T:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ShoppingCartService
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.services.shoppingcartservice_methods(v=AX.60)
ms:contentKeyID: 62204691
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# ShoppingCartService Methods

The [ShoppingCartService](shoppingcartservice-class-microsoft-dynamics-retail-sharepoint-web-services.md) type exposes the following members.

## Methods

<table>
<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="shoppingcartservice-additems-method-microsoft-dynamics-retail-sharepoint-web-services.md">AddItems</a></td>
<td>Adds items to the shopping cart associated with the given identifier.</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="shoppingcartservice-applypromotioncode-method-microsoft-dynamics-retail-sharepoint-web-services.md">ApplyPromotionCode</a></td>
<td>Applies a promotion code to the shopping cart.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="shoppingcartservice-claimanonymouscart-method-microsoft-dynamics-retail-sharepoint-web-services.md">ClaimAnonymousCart</a></td>
<td>If a cart already exissd resolor the anonymous user, we need to claim the cart after a successful login. Attempting to claim a cart that has been claimed by another user will result in a security exception. If the cart has already been claimed by the current user, no error is thrown.</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="shoppingcartservice-deleteshoppingcarts-method-microsoft-dynamics-retail-sharepoint-web-services.md">DeleteShoppingCarts</a></td>
<td>Deletes the shopping carts associated with given identifiers and the current user.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="https://technet.microsoft.com/en-us/library/bsc2ak47(v=ax.60)">Equals</a></td>
<td>(Inherited from <a href="https://technet.microsoft.com/en-us/library/e5kfa45b(v=ax.60)">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.protmethod(en-us,AX.60).gif" title="Protected method" alt="Protected method" /></td>
<td><a href="https://technet.microsoft.com/en-us/library/4k87zsw7(v=ax.60)">Finalize</a></td>
<td>(Inherited from <a href="https://technet.microsoft.com/en-us/library/e5kfa45b(v=ax.60)">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="shoppingcartservice-generateloyaltycardid-method-microsoft-dynamics-retail-sharepoint-web-services.md">GenerateLoyaltyCardId</a></td>
<td>Issues a new loyalty card ID for the customer.</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="shoppingcartservice-getallloyaltycardsstatus-method-microsoft-dynamics-retail-sharepoint-web-services.md">GetAllLoyaltyCardsStatus</a></td>
<td>Gets a read only collection of all loyalty card with their status</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="https://technet.microsoft.com/en-us/library/zdee4b3y(v=ax.60)">GetHashCode</a></td>
<td>(Inherited from <a href="https://technet.microsoft.com/en-us/library/e5kfa45b(v=ax.60)">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="shoppingcartservice-getkitcomponentvariants-method-microsoft-dynamics-retail-sharepoint-web-services.md">GetKitComponentVariants</a></td>
<td>Gets the applicable variants of a kit component.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="shoppingcartservice-getkitconfigurationinformation-method-microsoft-dynamics-retail-sharepoint-web-services.md">GetKitConfigurationInformation</a></td>
<td>Gets information about the specific kit configuration that has the provided kit line values.</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="shoppingcartservice-getloyaltycards-method-microsoft-dynamics-retail-sharepoint-web-services.md">GetLoyaltyCards</a></td>
<td>Gets a read only collection of all loyalty card numbers</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="shoppingcartservice-getloyaltycardstatus-method-microsoft-dynamics-retail-sharepoint-web-services.md">GetLoyaltyCardStatus</a></td>
<td>Gets the status of a loyalty card given it's id</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="shoppingcartservice-getloyaltycardtransactions-method-microsoft-dynamics-retail-sharepoint-web-services.md">GetLoyaltyCardTransactions</a></td>
<td>Gets a stream with all the transaction data specific to a a loyalty card number for a given points category</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="shoppingcartservice-getpromotions-method-microsoft-dynamics-retail-sharepoint-web-services.md">GetPromotions</a></td>
<td>Gets all the promotions for the shopping cart items.</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="shoppingcartservice-getshoppingcart-method-microsoft-dynamics-retail-sharepoint-web-services.md">GetShoppingCart</a></td>
<td>Gets the shopping cart associated</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="shoppingcartservice-getshoppingcarts-method-microsoft-dynamics-retail-sharepoint-web-services.md">GetShoppingCarts</a></td>
<td>Gets all shopping carts associated with the current user.</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="https://technet.microsoft.com/en-us/library/dfwy45w9(v=ax.60)">GetType</a></td>
<td>(Inherited from <a href="https://technet.microsoft.com/en-us/library/e5kfa45b(v=ax.60)">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.protmethod(en-us,AX.60).gif" title="Protected method" alt="Protected method" /></td>
<td><a href="https://technet.microsoft.com/en-us/library/57ctke0a(v=ax.60)">MemberwiseClone</a></td>
<td>(Inherited from <a href="https://technet.microsoft.com/en-us/library/e5kfa45b(v=ax.60)">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="shoppingcartservice-removeitems-method-microsoft-dynamics-retail-sharepoint-web-services.md">RemoveItems</a></td>
<td>Removes items from the shopping cart associated with the given identifier.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="shoppingcartservice-saveshoppingcart-method-microsoft-dynamics-retail-sharepoint-web-services.md">SaveShoppingCart</a></td>
<td>Saves the name of the shopping cart associated with the given identifier.</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="https://technet.microsoft.com/en-us/library/7bxwbwt2(v=ax.60)">ToString</a></td>
<td>(Inherited from <a href="https://technet.microsoft.com/en-us/library/e5kfa45b(v=ax.60)">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="shoppingcartservice-updateitems-method-microsoft-dynamics-retail-sharepoint-web-services.md">UpdateItems</a></td>
<td>Updates items on the shopping cart associated with the given identifier.</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="shoppingcartservice-updateloyaltycardid-method-microsoft-dynamics-retail-sharepoint-web-services.md">UpdateLoyaltyCardId</a></td>
<td>Updates the loyalty card ID on the shopping cart.</td>
</tr>
</tbody>
</table>


Top

## See Also

#### Reference

[ShoppingCartService Class](shoppingcartservice-class-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

