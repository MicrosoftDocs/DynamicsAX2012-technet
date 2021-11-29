---
title: WishList.CustomerId Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: CustomerId Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.WishList.CustomerId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.wishlist.customerid(v=AX.60)
ms:contentKeyID: 62206838
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.WishList.CustomerId
dev_langs:
- CSharp
- C++
- VB
---

# CustomerId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the wishlist line customer.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CustomerId As String
    Get
    Set
'Usage
Dim instance As WishList
Dim value As String

value = instance.CustomerId

instance.CustomerId = value
```

``` csharp
[DataMemberAttribute]
public string CustomerId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ CustomerId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[WishList Class](wishlist-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

