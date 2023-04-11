---
title: DbElementCollection(T).Add Method (T, String, Nullable(Int32)) (Microsoft.Dynamics.Commerce.Runtime.Data.Types)
TOCTitle: Add Method (T, String, Nullable(Int32))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.Types.DbElementCollection`1.Add(`0,System.String,System.Nullable{System.Int32})
ms:mtpsurl: https://technet.microsoft.com/library/Dn990930(v=AX.60)
ms:contentKeyID: 65322120
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Add Method (T, String, Nullable(Int32))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Adds an element to the collection.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Types](microsoft-dynamics-commerce-runtime-data-types-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Protected Sub Add ( _
    value As T, _
    key As String, _
    index As Nullable(Of Integer) _
)
'Usage
Dim value As T
Dim key As String
Dim index As Nullable(Of Integer)

Me.Add(value, key, index)
```

``` csharp
protected void Add(
    T value,
    string key,
    Nullable<int> index
)
```

``` c++
protected:
void Add(
    T value, 
    String^ key, 
    Nullable<int> index
)
```

#### Parameters

  - value  
    Type: [T](dbelementcollection-t-class-microsoft-dynamics-commerce-runtime-data-types.md)  

<!-- end list -->

  - key  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - index  
    Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))\>  

## See Also

#### Reference

[DbElementCollection\<T\> Class](dbelementcollection-t-class-microsoft-dynamics-commerce-runtime-data-types.md)

[Add Overload](dbelementcollection-t-add-method-microsoft-dynamics-commerce-runtime-data-types.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Types Namespace](microsoft-dynamics-commerce-runtime-data-types-namespace.md)

