---
title: DbElementCollection(T).Contains Method (String) (Microsoft.Dynamics.Commerce.Runtime.Data.Types)
TOCTitle: Contains Method (String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.Types.DbElementCollection`1.Contains(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/Dn968833(v=AX.60)
ms:contentKeyID: 65321953
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Contains Method (String)

Returns whether this collection contains a specific key.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Types](microsoft-dynamics-commerce-runtime-data-types-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Function Contains ( _
    key As String _
) As Boolean
'Usage
Dim instance As DbElementCollection
Dim key As String
Dim returnValue As Boolean

returnValue = instance.Contains(key)
```

``` csharp
public bool Contains(
    string key
)
```

``` c++
public:
bool Contains(
    String^ key
)
```

#### Parameters

  - key  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Whether this collection contains a specific key.  

## See Also

#### Reference

[DbElementCollection\<T\> Class](dbelementcollection-t-class-microsoft-dynamics-commerce-runtime-data-types.md)

[Contains Overload](dbelementcollection-t-contains-method-microsoft-dynamics-commerce-runtime-data-types.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Types Namespace](microsoft-dynamics-commerce-runtime-data-types-namespace.md)

