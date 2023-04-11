---
title: ItemVariantInventoryDimensionTableType Constructor  (Microsoft.Dynamics.Commerce.Runtime.Data.Types)
TOCTitle: ItemVariantInventoryDimensionTableType Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.Types.ItemVariantInventoryDimensionTableType.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemVariantInventoryDimension})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.types.itemvariantinventorydimensiontabletype.itemvariantinventorydimensiontabletype(v=AX.60)
ms:contentKeyID: 65319653
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.Types.ItemVariantInventoryDimensionTableType.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# ItemVariantInventoryDimensionTableType Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [ItemVariantInventoryDimensionTableType](itemvariantinventorydimensiontabletype-class-microsoft-dynamics-commerce-runtime-data-types.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data.Types](microsoft-dynamics-commerce-runtime-data-types-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    items As IEnumerable(Of ItemVariantInventoryDimension) _
)
'Usage
Dim items As IEnumerable(Of ItemVariantInventoryDimension)

Dim instance As New ItemVariantInventoryDimensionTableType(items)
```

``` csharp
public ItemVariantInventoryDimensionTableType(
    IEnumerable<ItemVariantInventoryDimension> items
)
```

``` c++
public:
ItemVariantInventoryDimensionTableType(
    IEnumerable<ItemVariantInventoryDimension^>^ items
)
```

#### Parameters

  - items  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ItemVariantInventoryDimension](itemvariantinventorydimension-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ItemVariantInventoryDimensionTableType Class](itemvariantinventorydimensiontabletype-class-microsoft-dynamics-commerce-runtime-data-types.md)

[Microsoft.Dynamics.Commerce.Runtime.Data.Types Namespace](microsoft-dynamics-commerce-runtime-data-types-namespace.md)

