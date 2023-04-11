---
title: GetStoresServiceRequest.SearchArea Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: SearchArea Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetStoresServiceRequest.SearchArea
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getstoresservicerequest.searcharea(v=AX.60)
ms:contentKeyID: 62214356
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetStoresServiceRequest.SearchArea
dev_langs:
- CSharp
- C++
- VB
---

# SearchArea Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the search area.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SearchArea As SearchArea
    Get
    Private Set
'Usage
Dim instance As GetStoresServiceRequest
Dim value As SearchArea

value = instance.SearchArea
```

``` csharp
[DataMemberAttribute]
public SearchArea SearchArea { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property SearchArea^ SearchArea {
    SearchArea^ get ();
    private: void set (SearchArea^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SearchArea](searcharea-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [SearchArea](searcharea-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetStoresServiceRequest Class](getstoresservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

