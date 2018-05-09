---
title: ShoppingCartResponse.ShoppingCart Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: ShoppingCart Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCartResponse.ShoppingCart
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.shoppingcartresponse.shoppingcart(v=AX.60)
ms:contentKeyID: 62205907
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCartResponse.ShoppingCart
dev_langs:
- CSharp
- C++
- VB
---

# ShoppingCart Property

Gets or sets the shopping cart.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ShoppingCart As ShoppingCart
    Get
    Set
'Usage
Dim instance As ShoppingCartResponse
Dim value As ShoppingCart

value = instance.ShoppingCart

instance.ShoppingCart = value
```

``` csharp
[DataMemberAttribute]
public ShoppingCart ShoppingCart { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property ShoppingCart^ ShoppingCart {
    ShoppingCart^ get ();
    void set (ShoppingCart^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCart](shoppingcart-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
Returns [ShoppingCart](shoppingcart-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md).  

## See Also

#### Reference

[ShoppingCartResponse Class](shoppingcartresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

