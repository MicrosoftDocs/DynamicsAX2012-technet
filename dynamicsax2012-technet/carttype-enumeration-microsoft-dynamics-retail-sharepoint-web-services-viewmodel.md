---
title: CartType Enumeration (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: CartType Enumeration
ms:assetid: T:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.CartType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.carttype(v=AX.60)
ms:contentKeyID: 62206500
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.CartType
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.CartType.Shopping
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.CartType.Checkout
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.CartType.None
dev_langs:
- CSharp
- C++
- VB
---

# CartType Enumeration

Represents the shopping cart type.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Enumeration CartType
'Usage
Dim instance As CartType
```

``` csharp
[DataContractAttribute]
public enum CartType
```

``` c++
[DataContractAttribute]
public enum class CartType
```

## Members

<table>
<thead>
<tr class="header">
<th></th>
<th>Member name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td></td>
<td>None</td>
<td>None (Cart Type not defined).</td>
</tr>
<tr class="even">
<td></td>
<td>Shopping</td>
<td>Shopping cart.</td>
</tr>
<tr class="odd">
<td></td>
<td>Checkout</td>
<td>Checkout cart - The temporary copy of the shopping cart created during the checkout process.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

