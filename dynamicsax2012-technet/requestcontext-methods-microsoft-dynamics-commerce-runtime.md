---
title: RequestContext Methods (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: RequestContext Methods
ms:assetid: Methods.T:Microsoft.Dynamics.Commerce.Runtime.RequestContext
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.requestcontext_methods(v=AX.60)
ms:contentKeyID: 49844059
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# RequestContext Methods


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The [RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md) type exposes the following members.

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
<td><a href="https://technet.microsoft.com/library/bsc2ak47(v=ax.60)">Equals</a></td>
<td>(Inherited from <a href="https://technet.microsoft.com/library/e5kfa45b(v=ax.60)">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.protmethod(en-us,AX.60).gif" title="Protected method" alt="Protected method" /></td>
<td><a href="https://technet.microsoft.com/library/4k87zsw7(v=ax.60)">Finalize</a></td>
<td>(Inherited from <a href="https://technet.microsoft.com/library/e5kfa45b(v=ax.60)">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="https://technet.microsoft.com/library/zdee4b3y(v=ax.60)">GetHashCode</a></td>
<td>(Inherited from <a href="https://technet.microsoft.com/library/e5kfa45b(v=ax.60)">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="https://technet.microsoft.com/library/dfwy45w9(v=ax.60)">GetType</a></td>
<td>(Inherited from <a href="https://technet.microsoft.com/library/e5kfa45b(v=ax.60)">Object</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.protmethod(en-us,AX.60).gif" title="Protected method" alt="Protected method" /></td>
<td><a href="https://technet.microsoft.com/library/57ctke0a(v=ax.60)">MemberwiseClone</a></td>
<td>(Inherited from <a href="https://technet.microsoft.com/library/e5kfa45b(v=ax.60)">Object</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="requestcontext-setinitialized-method-microsoft-dynamics-commerce-runtime.md">SetInitialized</a></td>
<td></td>
</tr>
<tr class="odd">
<td><img src="images/Dn987397.pubmethod(en-us,AX.60).gif" title="Public method" alt="Public method" /></td>
<td><a href="https://technet.microsoft.com/library/7bxwbwt2(v=ax.60)">ToString</a></td>
<td>(Inherited from <a href="https://technet.microsoft.com/library/e5kfa45b(v=ax.60)">Object</a>.)</td>
</tr>
</tbody>
</table>


Top

## Extension Methods

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
<td><img src="images/Dn684868.pubextension(en-us,AX.60).gif" title="Public Extension Method" alt="Public Extension Method" /></td>
<td><a href="requestcontextextensions-convertdatetimetochanneldate-method-microsoft-dynamics-commerce-runtime.md">ConvertDateTimeToChannelDate</a></td>
<td>Gets a <a href="https://technet.microsoft.com/library/bb341783(v=ax.60)">DateTimeOffset</a> object that is set to the current date and time on the current computer, with the offset set to the channel time's offset from Coordinated Universal Time (UTC). (Defined by <a href="requestcontextextensions-class-microsoft-dynamics-commerce-runtime.md">RequestContextExtensions</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn684868.pubextension(en-us,AX.60).gif" title="Public Extension Method" alt="Public Extension Method" /></td>
<td><a href="requestcontextextensions-execute-tresponse-method-requestcontext-request-microsoft-dynamics-commerce-runtime.md">Execute&lt;TResponse&gt;(Request)</a></td>
<td>Overloaded. Executes the specified request using the specified request context. (Defined by <a href="requestcontextextensions-class-microsoft-dynamics-commerce-runtime.md">RequestContextExtensions</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn684868.pubextension(en-us,AX.60).gif" title="Public Extension Method" alt="Public Extension Method" /></td>
<td><a href="requestcontextextensions-execute-tresponse-method-requestcontext-request-irequesthandler-microsoft-dynamics-commerce-runtime.md">Execute&lt;TResponse&gt;(Request, IRequestHandler)</a></td>
<td>Overloaded. Executes the specified request using the specified request context and handler. (Defined by <a href="requestcontextextensions-class-microsoft-dynamics-commerce-runtime.md">RequestContextExtensions</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn684868.pubextension(en-us,AX.60).gif" title="Public Extension Method" alt="Public Extension Method" /></td>
<td><a href="requestcontextextensions-getchannelconfiguration-method-microsoft-dynamics-commerce-runtime.md">GetChannelConfiguration</a></td>
<td>Gets the channel configuration for the current request. (Defined by <a href="requestcontextextensions-class-microsoft-dynamics-commerce-runtime.md">RequestContextExtensions</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn684868.pubextension(en-us,AX.60).gif" title="Public Extension Method" alt="Public Extension Method" /></td>
<td><a href="requestcontextextensions-getchannelid-method-microsoft-dynamics-commerce-runtime.md">GetChannelId</a></td>
<td>Gets the channel identifier for the request. Used only for Login request. (Defined by <a href="requestcontextextensions-class-microsoft-dynamics-commerce-runtime.md">RequestContextExtensions</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn684868.pubextension(en-us,AX.60).gif" title="Public Extension Method" alt="Public Extension Method" /></td>
<td><a href="requestcontextextensions-getcheckaccessismanageraction-method-microsoft-dynamics-commerce-runtime.md">GetCheckAccessIsManagerAction</a></td>
<td>Gets the delegate to check if user is manager. (Defined by <a href="requestcontextextensions-class-microsoft-dynamics-commerce-runtime.md">RequestContextExtensions</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn684868.pubextension(en-us,AX.60).gif" title="Public Extension Method" alt="Public Extension Method" /></td>
<td><a href="requestcontextextensions-getcheckaccessisshiftopenaction-method-microsoft-dynamics-commerce-runtime.md">GetCheckAccessIsShiftOpenAction</a></td>
<td>Gets the delegate to check if user has an open shift. (Defined by <a href="requestcontextextensions-class-microsoft-dynamics-commerce-runtime.md">RequestContextExtensions</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn684868.pubextension(en-us,AX.60).gif" title="Public Extension Method" alt="Public Extension Method" /></td>
<td><a href="requestcontextextensions-getcheckaccessretailoperationaction-method-microsoft-dynamics-commerce-runtime.md">GetCheckAccessRetailOperationAction</a></td>
<td>Gets the delegate to check access for <a href="retailoperation-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md">RetailOperation</a>. (Defined by <a href="requestcontextextensions-class-microsoft-dynamics-commerce-runtime.md">RequestContextExtensions</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn684868.pubextension(en-us,AX.60).gif" title="Public Extension Method" alt="Public Extension Method" /></td>
<td><a href="requestcontextextensions-getnowinchanneltimezone-method-microsoft-dynamics-commerce-runtime.md">GetNowInChannelTimeZone</a></td>
<td>Gets a <a href="https://technet.microsoft.com/library/bb341783(v=ax.60)">DateTimeOffset</a> object that is set to the current date and time on the current computer, with the offset set to the channel time's offset from Coordinated Universal Time (UTC). (Defined by <a href="requestcontextextensions-class-microsoft-dynamics-commerce-runtime.md">RequestContextExtensions</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn684868.pubextension(en-us,AX.60).gif" title="Public Extension Method" alt="Public Extension Method" /></td>
<td><a href="requestcontextextensions-getorgunit-method-microsoft-dynamics-commerce-runtime.md">GetOrgUnit</a></td>
<td>Gets the organization unit for the current request. (Defined by <a href="requestcontextextensions-class-microsoft-dynamics-commerce-runtime.md">RequestContextExtensions</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn684868.pubextension(en-us,AX.60).gif" title="Public Extension Method" alt="Public Extension Method" /></td>
<td><a href="requestcontextextensions-getprincipal-method-microsoft-dynamics-commerce-runtime.md">GetPrincipal</a></td>
<td>Gets the principal for the request. (Defined by <a href="requestcontextextensions-class-microsoft-dynamics-commerce-runtime.md">RequestContextExtensions</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn684868.pubextension(en-us,AX.60).gif" title="Public Extension Method" alt="Public Extension Method" /></td>
<td><a href="requestcontextextensions-getreturnedsalestransaction-method-microsoft-dynamics-commerce-runtime.md">GetReturnedSalesTransaction</a></td>
<td>Gets the returned sales transaction object from <a href="requestcontext-class-microsoft-dynamics-commerce-runtime.md">RequestContext</a>. (Defined by <a href="requestcontextextensions-class-microsoft-dynamics-commerce-runtime.md">RequestContextExtensions</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn684868.pubextension(en-us,AX.60).gif" title="Public Extension Method" alt="Public Extension Method" /></td>
<td><a href="requestcontextextensions-getsalestransaction-method-microsoft-dynamics-commerce-runtime.md">GetSalesTransaction</a></td>
<td>Gets the sales transaction object from <a href="requestcontext-class-microsoft-dynamics-commerce-runtime.md">RequestContext</a>. (Defined by <a href="requestcontextextensions-class-microsoft-dynamics-commerce-runtime.md">RequestContextExtensions</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn684868.pubextension(en-us,AX.60).gif" title="Public Extension Method" alt="Public Extension Method" /></td>
<td><a href="requestcontextextensions-getterminal-method-microsoft-dynamics-commerce-runtime.md">GetTerminal</a></td>
<td>Gets the terminal for the current request. (Defined by <a href="requestcontextextensions-class-microsoft-dynamics-commerce-runtime.md">RequestContextExtensions</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn684868.pubextension(en-us,AX.60).gif" title="Public Extension Method" alt="Public Extension Method" /></td>
<td><a href="requestcontextextensions-setchannelconfiguration-method-microsoft-dynamics-commerce-runtime.md">SetChannelConfiguration</a></td>
<td>Sets the channel configuration for the current request. (Defined by <a href="requestcontextextensions-class-microsoft-dynamics-commerce-runtime.md">RequestContextExtensions</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn684868.pubextension(en-us,AX.60).gif" title="Public Extension Method" alt="Public Extension Method" /></td>
<td><a href="requestcontextextensions-setchannelid-method-microsoft-dynamics-commerce-runtime.md">SetChannelId</a></td>
<td>Sets the channel identifier for the current request. Used only for Login request. (Defined by <a href="requestcontextextensions-class-microsoft-dynamics-commerce-runtime.md">RequestContextExtensions</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn684868.pubextension(en-us,AX.60).gif" title="Public Extension Method" alt="Public Extension Method" /></td>
<td><a href="requestcontextextensions-setcheckaccessismanageraction-method-microsoft-dynamics-commerce-runtime.md">SetCheckAccessIsManagerAction</a></td>
<td>Sets the delegate to check if user is manager. (Defined by <a href="requestcontextextensions-class-microsoft-dynamics-commerce-runtime.md">RequestContextExtensions</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn684868.pubextension(en-us,AX.60).gif" title="Public Extension Method" alt="Public Extension Method" /></td>
<td><a href="requestcontextextensions-setcheckaccessisshiftopenaction-method-microsoft-dynamics-commerce-runtime.md">SetCheckAccessIsShiftOpenAction</a></td>
<td>Sets the delegate to check if user has an open shift. (Defined by <a href="requestcontextextensions-class-microsoft-dynamics-commerce-runtime.md">RequestContextExtensions</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn684868.pubextension(en-us,AX.60).gif" title="Public Extension Method" alt="Public Extension Method" /></td>
<td><a href="requestcontextextensions-setcheckaccessretailoperationaction-method-microsoft-dynamics-commerce-runtime.md">SetCheckAccessRetailOperationAction</a></td>
<td>Sets the delegate to check access for <a href="retailoperation-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md">RetailOperation</a>. (Defined by <a href="requestcontextextensions-class-microsoft-dynamics-commerce-runtime.md">RequestContextExtensions</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn684868.pubextension(en-us,AX.60).gif" title="Public Extension Method" alt="Public Extension Method" /></td>
<td><a href="requestcontextextensions-setorgunit-method-microsoft-dynamics-commerce-runtime.md">SetOrgUnit</a></td>
<td>Sets the organization unit for the current request. (Defined by <a href="requestcontextextensions-class-microsoft-dynamics-commerce-runtime.md">RequestContextExtensions</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn684868.pubextension(en-us,AX.60).gif" title="Public Extension Method" alt="Public Extension Method" /></td>
<td><a href="requestcontextextensions-setprincipal-method-microsoft-dynamics-commerce-runtime.md">SetPrincipal</a></td>
<td>Sets the principal for the request. (Defined by <a href="requestcontextextensions-class-microsoft-dynamics-commerce-runtime.md">RequestContextExtensions</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn684868.pubextension(en-us,AX.60).gif" title="Public Extension Method" alt="Public Extension Method" /></td>
<td><a href="requestcontextextensions-setreturnedsalestransaction-method-microsoft-dynamics-commerce-runtime.md">SetReturnedSalesTransaction</a></td>
<td>Sets the returned sales transaction object in <a href="requestcontext-class-microsoft-dynamics-commerce-runtime.md">RequestContext</a>. (Defined by <a href="requestcontextextensions-class-microsoft-dynamics-commerce-runtime.md">RequestContextExtensions</a>.)</td>
</tr>
<tr class="odd">
<td><img src="images/Dn684868.pubextension(en-us,AX.60).gif" title="Public Extension Method" alt="Public Extension Method" /></td>
<td><a href="requestcontextextensions-setsalestransaction-method-microsoft-dynamics-commerce-runtime.md">SetSalesTransaction</a></td>
<td>Sets the sales transaction object in <a href="requestcontext-class-microsoft-dynamics-commerce-runtime.md">RequestContext</a>. (Defined by <a href="requestcontextextensions-class-microsoft-dynamics-commerce-runtime.md">RequestContextExtensions</a>.)</td>
</tr>
<tr class="even">
<td><img src="images/Dn684868.pubextension(en-us,AX.60).gif" title="Public Extension Method" alt="Public Extension Method" /></td>
<td><a href="requestcontextextensions-setterminal-method-microsoft-dynamics-commerce-runtime.md">SetTerminal</a></td>
<td>Sets the terminal for the current request. (Defined by <a href="requestcontextextensions-class-microsoft-dynamics-commerce-runtime.md">RequestContextExtensions</a>.)</td>
</tr>
</tbody>
</table>


Top

## See Also

#### Reference

[RequestContext Class](requestcontext-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

