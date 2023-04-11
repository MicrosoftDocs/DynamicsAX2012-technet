---
title: SearchStoreResponse Constructor (IEnumerable(OrgUnit)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: SearchStoreResponse Constructor (IEnumerable(OrgUnit))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.SearchStoreResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnit})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.searchstoreresponse.searchstoreresponse(v=AX.60)
ms:contentKeyID: 62212259
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# SearchStoreResponse Constructor (IEnumerable(OrgUnit))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [SearchStoreResponse](searchstoreresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    stores As IEnumerable(Of OrgUnit) _
)
'Usage
Dim stores As IEnumerable(Of OrgUnit)

Dim instance As New SearchStoreResponse(stores)
```

``` csharp
public SearchStoreResponse(
    IEnumerable<OrgUnit> stores
)
```

``` c++
public:
SearchStoreResponse(
    IEnumerable<OrgUnit^>^ stores
)
```

#### Parameters

  - stores  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[OrgUnit](orgunit-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[SearchStoreResponse Class](searchstoreresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[SearchStoreResponse Overload](searchstoreresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

