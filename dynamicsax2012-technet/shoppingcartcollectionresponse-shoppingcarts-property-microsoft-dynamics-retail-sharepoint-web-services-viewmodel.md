---
title: ShoppingCartCollectionResponse.ShoppingCarts Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: ShoppingCarts Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCartCollectionResponse.ShoppingCarts
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.shoppingcartcollectionresponse.shoppingcarts(v=AX.60)
ms:contentKeyID: 62206980
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCartCollectionResponse.ShoppingCarts
dev_langs:
- CSharp
- C++
- VB
---

# ShoppingCarts Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the shopping carts.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ShoppingCarts As Collection(Of ShoppingCart)
    Get
    Friend Set
'Usage
Dim instance As ShoppingCartCollectionResponse
Dim value As Collection(Of ShoppingCart)

value = instance.ShoppingCarts
```

``` csharp
[DataMemberAttribute]
public Collection<ShoppingCart> ShoppingCarts { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<ShoppingCart^>^ ShoppingCarts {
    Collection<ShoppingCart^>^ get ();
    internal: void set (Collection<ShoppingCart^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[ShoppingCart](shoppingcart-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)\>  
The shopping carts.  

## See Also

#### Reference

[ShoppingCartCollectionResponse Class](shoppingcartcollectionresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

