---
title: DataRowCollection.Add Method (Object ) (Microsoft.Dynamics.Commerce.Runtime.Data.Types)
TOCTitle: Add Method (Object )
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataRowCollection.Add(System.Object[])
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.types.datarowcollection.add(v=AX.60)
ms:contentKeyID: 65317704
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Add Method (Object[])

Adds a new row based on it's data content.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Types](microsoft-dynamics-commerce-runtime-data-types-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Sub Add ( _
    ParamArray data As Object() _
)
'Usage
Dim instance As DataRowCollection
Dim data As Object()

instance.Add(data)
```

``` csharp
public void Add(
    params Object[] data
)
```

``` c++
public:
void Add(
    ... array<Object^>^ data
)
```

#### Parameters

  - data  
    Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))\[\]  

## See Also

#### Reference

[DataRowCollection Class](datarowcollection-class-microsoft-dynamics-commerce-runtime-data-types.md)

[Add Overload](datarowcollection-add-method-microsoft-dynamics-commerce-runtime-data-types.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Types Namespace](microsoft-dynamics-commerce-runtime-data-types-namespace.md)

