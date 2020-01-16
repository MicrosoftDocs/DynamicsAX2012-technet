---
title: ShoppingCartItemType Enumeration (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: ShoppingCartItemType Enumeration
ms:assetid: T:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCartItemType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.shoppingcartitemtype(v=AX.60)
ms:contentKeyID: 62207665
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCartItemType
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCartItemType.Kit
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCartItemType.None
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCartItemType.KitComponent
dev_langs:
- CSharp
- C++
- VB
---

# ShoppingCartItemType Enumeration

Represents the shopping cart item type.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Enumeration ShoppingCartItemType
'Usage
Dim instance As ShoppingCartItemType
```

``` csharp
[DataContractAttribute]
public enum ShoppingCartItemType
```

``` c++
[DataContractAttribute]
public enum class ShoppingCartItemType
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
<td>None (indicates that the shopping cart item is neither a kit nor a kit component).</td>
</tr>
<tr class="even">
<td></td>
<td>Kit</td>
<td>Indicates that the shopping cart item is a kit.</td>
</tr>
<tr class="odd">
<td></td>
<td>KitComponent</td>
<td>Indicates that the shopping cart item is a kit component.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

