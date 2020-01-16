---
title: GetCommerceListServiceRequest.FavoriteFilter Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: FavoriteFilter Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCommerceListServiceRequest.FavoriteFilter
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getcommercelistservicerequest.favoritefilter(v=AX.60)
ms:contentKeyID: 62210870
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCommerceListServiceRequest.FavoriteFilter
dev_langs:
- CSharp
- C++
- VB
---

# FavoriteFilter Property

Gets or sets a value indicating whether the commerce lists should be filtered by favorite.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property FavoriteFilter As Boolean
    Get
    Set
'Usage
Dim instance As GetCommerceListServiceRequest
Dim value As Boolean

value = instance.FavoriteFilter

instance.FavoriteFilter = value
```

``` csharp
[DataMemberAttribute]
public bool FavoriteFilter { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool FavoriteFilter {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[GetCommerceListServiceRequest Class](getcommercelistservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

