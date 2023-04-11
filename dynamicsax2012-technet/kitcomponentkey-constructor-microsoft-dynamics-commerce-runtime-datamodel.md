---
title: KitComponentKey Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: KitComponentKey Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.KitComponentKey.#ctor(System.Int64,System.Int64)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.kitcomponentkey.kitcomponentkey(v=AX.60)
ms:contentKeyID: 62211402
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.KitComponentKey.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# KitComponentKey Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [KitComponentKey](kitcomponentkey-class-microsoft-dynamics-commerce-runtime-datamodel.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    kitLineIdentifier As Long, _
    distinctProductId As Long _
)
'Usage
Dim kitLineIdentifier As Long
Dim distinctProductId As Long

Dim instance As New KitComponentKey(kitLineIdentifier, _
    distinctProductId)
```

``` csharp
public KitComponentKey(
    long kitLineIdentifier,
    long distinctProductId
)
```

``` c++
public:
KitComponentKey(
    long long kitLineIdentifier, 
    long long distinctProductId
)
```

#### Parameters

  - kitLineIdentifier  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - distinctProductId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

## See Also

#### Reference

[KitComponentKey Class](kitcomponentkey-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

