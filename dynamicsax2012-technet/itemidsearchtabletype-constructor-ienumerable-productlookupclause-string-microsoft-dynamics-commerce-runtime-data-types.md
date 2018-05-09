---
title: ItemIdSearchTableType Constructor (IEnumerable(ProductLookupClause), String) (Microsoft.Dynamics.Commerce.Runtime.Data.Types)
TOCTitle: ItemIdSearchTableType Constructor (IEnumerable(ProductLookupClause), String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.Types.ItemIdSearchTableType.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductLookupClause},System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.types.itemidsearchtabletype.itemidsearchtabletype(v=AX.60)
ms:contentKeyID: 65321945
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ItemIdSearchTableType Constructor (IEnumerable(ProductLookupClause), String)

Initializes a new instance of the [ItemIdSearchTableType](itemidsearchtabletype-class-microsoft-dynamics-commerce-runtime-data-types.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Types](microsoft-dynamics-commerce-runtime-data-types-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    itemLookups As IEnumerable(Of ProductLookupClause), _
    joinColumn As String _
)
'Usage
Dim itemLookups As IEnumerable(Of ProductLookupClause)
Dim joinColumn As String

Dim instance As New ItemIdSearchTableType(itemLookups, _
    joinColumn)
```

``` csharp
public ItemIdSearchTableType(
    IEnumerable<ProductLookupClause> itemLookups,
    string joinColumn
)
```

``` c++
public:
ItemIdSearchTableType(
    IEnumerable<ProductLookupClause^>^ itemLookups, 
    String^ joinColumn
)
```

#### Parameters

  - itemLookups  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[ProductLookupClause](productlookupclause-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - joinColumn  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ItemIdSearchTableType Class](itemidsearchtabletype-class-microsoft-dynamics-commerce-runtime-data-types.md)

[ItemIdSearchTableType Overload](itemidsearchtabletype-constructor-microsoft-dynamics-commerce-runtime-data-types.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Types Namespace](microsoft-dynamics-commerce-runtime-data-types-namespace.md)

