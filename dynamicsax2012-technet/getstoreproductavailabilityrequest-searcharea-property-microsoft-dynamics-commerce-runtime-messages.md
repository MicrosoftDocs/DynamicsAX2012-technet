---
title: GetStoreProductAvailabilityRequest.SearchArea Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: SearchArea Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetStoreProductAvailabilityRequest.SearchArea
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getstoreproductavailabilityrequest.searcharea(v=AX.60)
ms:contentKeyID: 49846707
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetStoreProductAvailabilityRequest.SearchArea
dev_langs:
- CSharp
- C++
- VB
---

# SearchArea Property

Gets or sets the search area.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SearchArea As SearchArea
    Get
    Set
'Usage
Dim instance As GetStoreProductAvailabilityRequest
Dim value As SearchArea

value = instance.SearchArea

instance.SearchArea = value
```

``` csharp
[DataMemberAttribute]
public SearchArea SearchArea { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property SearchArea^ SearchArea {
    SearchArea^ get ();
    void set (SearchArea^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SearchArea](searcharea-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The search area.  

## See Also

#### Reference

[GetStoreProductAvailabilityRequest Class](getstoreproductavailabilityrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

