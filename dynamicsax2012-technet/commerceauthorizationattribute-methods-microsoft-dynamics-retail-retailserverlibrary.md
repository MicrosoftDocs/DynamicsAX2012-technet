---
title: CommerceAuthorizationAttribute Methods (Microsoft.Dynamics.Retail.RetailServerLibrary)
TOCTitle: CommerceAuthorizationAttribute Methods
ms:assetid: Methods.T:Microsoft.Dynamics.Retail.RetailServerLibrary.CommerceAuthorizationAttribute
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.commerceauthorizationattribute_methods(v=AX.60)
ms:contentKeyID: 62203075
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
---

# CommerceAuthorizationAttribute Methods


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The [CommerceAuthorizationAttribute](commerceauthorizationattribute-class-microsoft-dynamics-retail-retailserverlibrary.md) type exposes the following members.

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
<td><a href="https://technet.microsoft.com/library/09ds241w(v=ax.60)">Equals</a></td>
<td>(Inherited from <a href="https://technet.microsoft.com/library/e8kc3626(v=ax.60)">Attribute</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.protmethod(en-us,AX.60).gif" title="Protected method" alt="Protected method" /></td>
<td><a href="https://technet.microsoft.com/library/4k87zsw7(v=ax.60)">Finalize</a></td>
<td>(Inherited from <a href="https://technet.microsoft.com/library/e5kfa45b(v=ax.60)">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="https://technet.microsoft.com/library/365e1bxs(v=ax.60)">GetHashCode</a></td>
<td>(Inherited from <a href="https://technet.microsoft.com/library/e8kc3626(v=ax.60)">Attribute</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="https://technet.microsoft.com/library/dfwy45w9(v=ax.60)">GetType</a></td>
<td>(Inherited from <a href="https://technet.microsoft.com/library/e5kfa45b(v=ax.60)">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.protmethod(en-us,AX.60).gif" title="Protected method" alt="Protected method" /></td>
<td><a href="commerceauthorizationattribute-handleunauthorizedrequest-method-microsoft-dynamics-retail-retailserverlibrary.md">HandleUnauthorizedRequest</a></td>
<td>Handles all unauthorized errors to return proper HttpCode to client. (Overrides AuthorizeAttributeHandleUnauthorizedRequest(HttpActionContext).)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.protmethod(en-us,AX.60).gif" title="Protected method" alt="Protected method" /></td>
<td><a href="commerceauthorizationattribute-isauthorized-method-microsoft-dynamics-retail-retailserverlibrary.md">IsAuthorized</a></td>
<td>Checks authorization for all OData calls. (Overrides AuthorizeAttributeIsAuthorized(HttpActionContext).)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="https://technet.microsoft.com/library/tbkb5x6t(v=ax.60)">IsDefaultAttribute</a></td>
<td>(Inherited from <a href="https://technet.microsoft.com/library/e8kc3626(v=ax.60)">Attribute</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="https://technet.microsoft.com/library/wy7chz44(v=ax.60)">Match</a></td>
<td>(Inherited from <a href="https://technet.microsoft.com/library/e8kc3626(v=ax.60)">Attribute</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.protmethod(en-us,AX.60).gif" title="Protected method" alt="Protected method" /></td>
<td><a href="https://technet.microsoft.com/library/57ctke0a(v=ax.60)">MemberwiseClone</a></td>
<td>(Inherited from <a href="https://technet.microsoft.com/library/e5kfa45b(v=ax.60)">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td>OnAuthorization</td>
<td>(Inherited from AuthorizeAttribute.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="https://technet.microsoft.com/library/7bxwbwt2(v=ax.60)">ToString</a></td>
<td>(Inherited from <a href="https://technet.microsoft.com/library/e5kfa45b(v=ax.60)">Object</a>.)</td>
</tr>
</tbody>
</table>


Top

## Explicit Interface Implementations

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
<td><img src="images/Dn966581.pubinterface(en-us,AX.60).gif" title="Explicit interface implemetation" alt="Explicit interface implemetation" /> <img src="images/Dn998570.privmethod(en-us,AX.60).gif" title="Private method" alt="Private method" /></td>
<td>System#Web#Http#Filters#IAuthorizationFilter#ExecuteAuthorizationFilterAsync</td>
<td>(Inherited from AuthorizationFilterAttribute.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn966581.pubinterface(en-us,AX.60).gif" title="Explicit interface implemetation" alt="Explicit interface implemetation" /> <img src="images/Dn998570.privmethod(en-us,AX.60).gif" title="Private method" alt="Private method" /></td>
<td>_Attribute.GetIDsOfNames</td>
<td>(Inherited from <a href="https://technet.microsoft.com/library/e8kc3626(v=ax.60)">Attribute</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn966581.pubinterface(en-us,AX.60).gif" title="Explicit interface implemetation" alt="Explicit interface implemetation" /> <img src="images/Dn998570.privmethod(en-us,AX.60).gif" title="Private method" alt="Private method" /></td>
<td>_Attribute.GetTypeInfo</td>
<td>(Inherited from <a href="https://technet.microsoft.com/library/e8kc3626(v=ax.60)">Attribute</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn966581.pubinterface(en-us,AX.60).gif" title="Explicit interface implemetation" alt="Explicit interface implemetation" /> <img src="images/Dn998570.privmethod(en-us,AX.60).gif" title="Private method" alt="Private method" /></td>
<td>_Attribute.GetTypeInfoCount</td>
<td>(Inherited from <a href="https://technet.microsoft.com/library/e8kc3626(v=ax.60)">Attribute</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn966581.pubinterface(en-us,AX.60).gif" title="Explicit interface implemetation" alt="Explicit interface implemetation" /> <img src="images/Dn998570.privmethod(en-us,AX.60).gif" title="Private method" alt="Private method" /></td>
<td>_Attribute.Invoke</td>
<td>(Inherited from <a href="https://technet.microsoft.com/library/e8kc3626(v=ax.60)">Attribute</a>.)</td>
</tr>
</tbody>
</table>


Top

## See Also

#### Reference

[CommerceAuthorizationAttribute Class](commerceauthorizationattribute-class-microsoft-dynamics-retail-retailserverlibrary.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary Namespace](microsoft-dynamics-retail-retailserverlibrary-namespace.md)

