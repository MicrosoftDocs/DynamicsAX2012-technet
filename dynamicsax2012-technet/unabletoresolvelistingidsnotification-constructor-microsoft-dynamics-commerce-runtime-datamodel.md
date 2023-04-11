---
title: UnableToResolveListingIdsNotification Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: UnableToResolveListingIdsNotification Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.UnableToResolveListingIdsNotification.#ctor(System.Collections.Generic.IEnumerable{System.Int64})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.unabletoresolvelistingidsnotification.unabletoresolvelistingidsnotification(v=AX.60)
ms:contentKeyID: 65320252
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.UnableToResolveListingIdsNotification.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# UnableToResolveListingIdsNotification Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [UnableToResolveListingIdsNotification](unabletoresolvelistingidsnotification-class-microsoft-dynamics-commerce-runtime-datamodel.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    listingIds As IEnumerable(Of Long) _
)
'Usage
Dim listingIds As IEnumerable(Of Long)

Dim instance As New UnableToResolveListingIdsNotification(listingIds)
```

``` csharp
public UnableToResolveListingIdsNotification(
    IEnumerable<long> listingIds
)
```

``` c++
public:
UnableToResolveListingIdsNotification(
    IEnumerable<long long>^ listingIds
)
```

#### Parameters

  - listingIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

## See Also

#### Reference

[UnableToResolveListingIdsNotification Class](unabletoresolvelistingidsnotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

