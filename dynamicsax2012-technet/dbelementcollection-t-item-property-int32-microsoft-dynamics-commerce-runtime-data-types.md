---
title: DbElementCollection(T).Item Property (Int32) (Microsoft.Dynamics.Commerce.Runtime.Data.Types)
TOCTitle: Item Property (Int32)
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.Types.DbElementCollection`1.Item(System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/Dn989422(v=AX.60)
ms:contentKeyID: 65319375
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Item Property (Int32)

Gets or sets the value based on an index.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Types](microsoft-dynamics-commerce-runtime-data-types-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property Item ( _
    index As Integer _
) As T
    Get
    Set
'Usage
Dim instance As DbElementCollection
Dim index As Integer
Dim value As T

value = instance.Item(index)

instance.Item(index) = value
```

``` csharp
public T this[
    int index
] { get; set; }
```

``` c++
public:
virtual property T Item[int index] {
    T get (int index) sealed;
    void set (int index, T value) sealed;
}
```

#### Parameters

  - index  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

#### Property Value

Type: [T](dbelementcollection-t-class-microsoft-dynamics-commerce-runtime-data-types.md)  
The value corresponding to the index provided.  

#### Implements

[IList\<T\>.Item\[Int32\]](https://technet.microsoft.com/library/ewthkb10\(v=ax.60\))  

## See Also

#### Reference

[DbElementCollection\<T\> Class](dbelementcollection-t-class-microsoft-dynamics-commerce-runtime-data-types.md)

[Item Overload](dbelementcollection-t-item-property-microsoft-dynamics-commerce-runtime-data-types.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Types Namespace](microsoft-dynamics-commerce-runtime-data-types-namespace.md)

