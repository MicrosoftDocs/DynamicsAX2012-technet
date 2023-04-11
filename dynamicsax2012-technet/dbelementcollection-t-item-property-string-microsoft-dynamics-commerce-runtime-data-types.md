---
title: DbElementCollection(T).Item Property (String) (Microsoft.Dynamics.Commerce.Runtime.Data.Types)
TOCTitle: Item Property (String)
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.Types.DbElementCollection`1.Item(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/Dn988404(v=AX.60)
ms:contentKeyID: 65317959
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Item Property (String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the value based on a key.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Types](microsoft-dynamics-commerce-runtime-data-types-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property Item ( _
    key As String _
) As T
    Get
    Set
'Usage
Dim instance As DbElementCollection
Dim key As String
Dim value As T

value = instance.Item(key)

instance.Item(key) = value
```

``` csharp
public T this[
    string key
] { get; set; }
```

``` c++
public:
property T Item[String^ key] {
    T get (String^ key);
    void set (String^ key, T value);
}
```

#### Parameters

  - key  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Property Value

Type: [T](dbelementcollection-t-class-microsoft-dynamics-commerce-runtime-data-types.md)  
The value corresponding to the key provided.  

## See Also

#### Reference

[DbElementCollection\<T\> Class](dbelementcollection-t-class-microsoft-dynamics-commerce-runtime-data-types.md)

[Item Overload](dbelementcollection-t-item-property-microsoft-dynamics-commerce-runtime-data-types.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Types Namespace](microsoft-dynamics-commerce-runtime-data-types-namespace.md)

