---
title: ShoppingCartDataLevel Enumeration (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: ShoppingCartDataLevel Enumeration
ms:assetid: T:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCartDataLevel
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.shoppingcartdatalevel(v=AX.60)
ms:contentKeyID: 62206065
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCartDataLevel
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCartDataLevel.All
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCartDataLevel.Extended
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCartDataLevel.Minimal
dev_langs:
- CSharp
- C++
- VB
---

# ShoppingCartDataLevel Enumeration

Represents the level of information contained in shopping cart entity in storefront.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Enumeration ShoppingCartDataLevel
'Usage
Dim instance As ShoppingCartDataLevel
```

``` csharp
[DataContractAttribute]
public enum ShoppingCartDataLevel
```

``` c++
[DataContractAttribute]
public enum class ShoppingCartDataLevel
```

## Members

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
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
<td>Minimal</td>
<td>The default level which indicates only minimal information is obtained.
<p>This data level is mainly used for mini shopping cart where product details and pricing details will suffice.</p></td>
</tr>
<tr class="even">
<td></td>
<td>Extended</td>
<td>This data level indicates that cart contains additional information such as shipping options, discount codes, loyalty details.
<p>This is used everywhere except mini shopping cart and the shopping cart display pages.</p></td>
</tr>
<tr class="odd">
<td></td>
<td>All</td>
<td>This level indicates that cart contains all information associated with it.
<p>This includes the kit component level details and cart promotions. This is used in the shopping cart display in the 'View shopping cart', 'checkout review', 'order details' pages.</p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

