---
title: ItemIdSearchTableType Constructor (IEnumerable(ProductLookupClause)) (Microsoft.Dynamics.Commerce.Runtime.Data.Types)
TOCTitle: ItemIdSearchTableType Constructor (IEnumerable(ProductLookupClause))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.Types.ItemIdSearchTableType.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductLookupClause})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.types.itemidsearchtabletype.itemidsearchtabletype(v=AX.60)
ms:contentKeyID: 65320563
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ItemIdSearchTableType Constructor (IEnumerable(ProductLookupClause))

Initializes a new instance of the [ItemIdSearchTableType](itemidsearchtabletype-class-microsoft-dynamics-commerce-runtime-data-types.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Types](microsoft-dynamics-commerce-runtime-data-types-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    itemLookups As IEnumerable(Of ProductLookupClause) _
)
'Usage
Dim itemLookups As IEnumerable(Of ProductLookupClause)

Dim instance As New ItemIdSearchTableType(itemLookups)
```

``` csharp
public ItemIdSearchTableType(
    IEnumerable<ProductLookupClause> itemLookups
)
```

``` c++
public:
ItemIdSearchTableType(
    IEnumerable<ProductLookupClause^>^ itemLookups
)
```

#### Parameters

  - itemLookups  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[ProductLookupClause](productlookupclause-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ItemIdSearchTableType Class](itemidsearchtabletype-class-microsoft-dynamics-commerce-runtime-data-types.md)

[ItemIdSearchTableType Overload](itemidsearchtabletype-constructor-microsoft-dynamics-commerce-runtime-data-types.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Types Namespace](microsoft-dynamics-commerce-runtime-data-types-namespace.md)

