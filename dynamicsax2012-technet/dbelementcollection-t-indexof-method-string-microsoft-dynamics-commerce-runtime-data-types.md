---
title: DbElementCollection(T).IndexOf Method (String) (Microsoft.Dynamics.Commerce.Runtime.Data.Types)
TOCTitle: IndexOf Method (String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.Types.DbElementCollection`1.IndexOf(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/Dn998819(v=AX.60)
ms:contentKeyID: 65317503
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# IndexOf Method (String)

Searches for the specified object and returns the zero-based index of the first occurrence within the entire collection.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Types](microsoft-dynamics-commerce-runtime-data-types-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Function IndexOf ( _
    key As String _
) As Integer
'Usage
Dim instance As DbElementCollection
Dim key As String
Dim returnValue As Integer

returnValue = instance.IndexOf(key)
```

``` csharp
public int IndexOf(
    string key
)
```

``` c++
public:
int IndexOf(
    String^ key
)
```

#### Parameters

  - key  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The zero-based index of the first occurrence of key within the entire collection, if found; otherwise, –1.  

## See Also

#### Reference

[DbElementCollection\<T\> Class](dbelementcollection-t-class-microsoft-dynamics-commerce-runtime-data-types.md)

[IndexOf Overload](dbelementcollection-t-indexof-method-microsoft-dynamics-commerce-runtime-data-types.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Types Namespace](microsoft-dynamics-commerce-runtime-data-types-namespace.md)

