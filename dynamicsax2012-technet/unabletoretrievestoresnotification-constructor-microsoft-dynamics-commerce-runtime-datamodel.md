---
title: UnableToRetrieveStoresNotification Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: UnableToRetrieveStoresNotification Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.UnableToRetrieveStoresNotification.#ctor(System.Int64,Microsoft.Dynamics.Commerce.Runtime.DataModel.SearchArea)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.unabletoretrievestoresnotification.unabletoretrievestoresnotification(v=AX.60)
ms:contentKeyID: 65320165
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.UnableToRetrieveStoresNotification.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# UnableToRetrieveStoresNotification Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [UnableToRetrieveStoresNotification](unabletoretrievestoresnotification-class-microsoft-dynamics-commerce-runtime-datamodel.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    channelId As Long, _
    searchArea As SearchArea _
)
'Usage
Dim channelId As Long
Dim searchArea As SearchArea

Dim instance As New UnableToRetrieveStoresNotification(channelId, _
    searchArea)
```

``` csharp
public UnableToRetrieveStoresNotification(
    long channelId,
    SearchArea searchArea
)
```

``` c++
public:
UnableToRetrieveStoresNotification(
    long long channelId, 
    SearchArea^ searchArea
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - searchArea  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SearchArea](searcharea-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[UnableToRetrieveStoresNotification Class](unabletoretrievestoresnotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

