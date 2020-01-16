---
title: ShoppingCartMapper.GetProducts Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel)
TOCTitle: GetProducts Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel.ShoppingCartMapper.GetProducts(System.Collections.Generic.IEnumerable{System.Int64})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.objectmodel.shoppingcartmapper.getproducts(v=AX.60)
ms:contentKeyID: 62207211
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel.ShoppingCartMapper.GetProducts
dev_langs:
- CSharp
- C++
- VB
---

# GetProducts Method

Gets the products.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel](microsoft-dynamics-retail-sharepoint-web-services-objectmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetProducts ( _
    productIds As IEnumerable(Of Long) _
) As IEnumerable(Of Product)
'Usage
Dim productIds As IEnumerable(Of Long)
Dim returnValue As IEnumerable(Of Product)

returnValue = ShoppingCartMapper.GetProducts(productIds)
```

``` csharp
public static IEnumerable<Product> GetProducts(
    IEnumerable<long> productIds
)
```

``` c++
public:
static IEnumerable<Product^>^ GetProducts(
    IEnumerable<long long>^ productIds
)
```

#### Parameters

  - productIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<Product\>  
Products.  

## See Also

#### Reference

[ShoppingCartMapper Class](shoppingcartmapper-class-microsoft-dynamics-retail-sharepoint-web-services-objectmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-objectmodel-namespace.md)

