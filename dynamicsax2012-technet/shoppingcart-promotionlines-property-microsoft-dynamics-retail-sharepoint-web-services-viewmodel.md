---
title: ShoppingCart.PromotionLines Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: PromotionLines Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCart.PromotionLines
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.shoppingcart.promotionlines(v=AX.60)
ms:contentKeyID: 62206960
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCart.PromotionLines
dev_langs:
- CSharp
- C++
- VB
---

# PromotionLines Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a collection of all promotions belonging to the shopping cart.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PromotionLines As Collection(Of String)
    Get
    Private Set
'Usage
Dim instance As ShoppingCart
Dim value As Collection(Of String)

value = instance.PromotionLines
```

``` csharp
[DataMemberAttribute]
public Collection<string> PromotionLines { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<String^>^ PromotionLines {
    Collection<String^>^ get ();
    private: void set (Collection<String^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  
Returns [Collection\<T\>](https://technet.microsoft.com/library/ms132397\(v=ax.60\)).  

## See Also

#### Reference

[ShoppingCart Class](shoppingcart-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

