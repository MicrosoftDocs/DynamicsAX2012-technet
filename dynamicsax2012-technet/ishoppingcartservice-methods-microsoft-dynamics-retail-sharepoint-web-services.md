---
title: IShoppingCartService Methods (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: IShoppingCartService Methods
ms:assetid: Methods.T:Microsoft.Dynamics.Retail.SharePoint.Web.Services.IShoppingCartService
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.ishoppingcartservice_methods(v=AX.60)
ms:contentKeyID: 62202246
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# IShoppingCartService Methods


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The [IShoppingCartService](ishoppingcartservice-interface-microsoft-dynamics-retail-sharepoint-web-services.md) type exposes the following members.

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
<td><a href="ishoppingcartservice-additems-method-microsoft-dynamics-retail-sharepoint-web-services.md">AddItems</a></td>
<td>Adds items to the shopping cart associated with the given identifier.</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ishoppingcartservice-applypromotioncode-method-microsoft-dynamics-retail-sharepoint-web-services.md">ApplyPromotionCode</a></td>
<td>Applies a promotion code to the shopping cart.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ishoppingcartservice-claimanonymouscart-method-microsoft-dynamics-retail-sharepoint-web-services.md">ClaimAnonymousCart</a></td>
<td>If a cart already exissd resolor the anonymous user, we need to claim the cart after a successful login. Attempting to claim a cart that has been claimed by another user will result in an security exception. If the cart has already been claimed by the current user, no error is thrown.</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ishoppingcartservice-deleteshoppingcarts-method-microsoft-dynamics-retail-sharepoint-web-services.md">DeleteShoppingCarts</a></td>
<td>Deletes the shopping carts associated with given identifiers and the current user.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ishoppingcartservice-generateloyaltycardid-method-microsoft-dynamics-retail-sharepoint-web-services.md">GenerateLoyaltyCardId</a></td>
<td>Issues a new loyalty card id for the customer.</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ishoppingcartservice-getallloyaltycardsstatus-method-microsoft-dynamics-retail-sharepoint-web-services.md">GetAllLoyaltyCardsStatus</a></td>
<td>Gets all loyalty cards with their status</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ishoppingcartservice-getkitcomponentvariants-method-microsoft-dynamics-retail-sharepoint-web-services.md">GetKitComponentVariants</a></td>
<td>Gets the applicable variants of a kit component.</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ishoppingcartservice-getkitconfigurationinformation-method-microsoft-dynamics-retail-sharepoint-web-services.md">GetKitConfigurationInformation</a></td>
<td>Gets information about the specific kit configuration that has the provided kit line values.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ishoppingcartservice-getloyaltycards-method-microsoft-dynamics-retail-sharepoint-web-services.md">GetLoyaltyCards</a></td>
<td>Gets a read only collection of all Loyalty Cards for the customer</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ishoppingcartservice-getloyaltycardstatus-method-microsoft-dynamics-retail-sharepoint-web-services.md">GetLoyaltyCardStatus</a></td>
<td>Gets a loyalty card status given a loyalty card id.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ishoppingcartservice-getloyaltycardtransactions-method-microsoft-dynamics-retail-sharepoint-web-services.md">GetLoyaltyCardTransactions</a></td>
<td>Gets all loyalty card transaction data</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ishoppingcartservice-getpromotions-method-microsoft-dynamics-retail-sharepoint-web-services.md">GetPromotions</a></td>
<td>Gets all the promotions for the shopping cart items.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ishoppingcartservice-getshoppingcart-method-microsoft-dynamics-retail-sharepoint-web-services.md">GetShoppingCart</a></td>
<td>Gets the shopping cart associated with the given identifier.</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ishoppingcartservice-getshoppingcarts-method-microsoft-dynamics-retail-sharepoint-web-services.md">GetShoppingCarts</a></td>
<td>Gets all shopping carts associated with the current user.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ishoppingcartservice-removeitems-method-microsoft-dynamics-retail-sharepoint-web-services.md">RemoveItems</a></td>
<td>Removes items from the shopping cart associated with the given identifier.</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ishoppingcartservice-saveshoppingcart-method-microsoft-dynamics-retail-sharepoint-web-services.md">SaveShoppingCart</a></td>
<td>Saves the name of the shopping cart associated with the given identifier.</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ishoppingcartservice-updateitems-method-microsoft-dynamics-retail-sharepoint-web-services.md">UpdateItems</a></td>
<td>Updates items on the shopping cart associated with the given identifier.</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="ishoppingcartservice-updateloyaltycardid-method-microsoft-dynamics-retail-sharepoint-web-services.md">UpdateLoyaltyCardId</a></td>
<td>Updates the loyalty card id on the shopping cart.</td>
</tr>
</tbody>
</table>


Top

## See Also

#### Reference

[IShoppingCartService Interface](ishoppingcartservice-interface-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

