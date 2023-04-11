---
title: ItemVariantInventoryDimension Constructor (String, String) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ItemVariantInventoryDimension Constructor (String, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemVariantInventoryDimension.#ctor(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.itemvariantinventorydimension.itemvariantinventorydimension(v=AX.60)
ms:contentKeyID: 62210808
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ItemVariantInventoryDimension Constructor (String, String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [ItemVariantInventoryDimension](itemvariantinventorydimension-class-microsoft-dynamics-commerce-runtime-datamodel.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    itemId As String, _
    variantInventoryDimensionId As String _
)
'Usage
Dim itemId As String
Dim variantInventoryDimensionId As String

Dim instance As New ItemVariantInventoryDimension(itemId, _
    variantInventoryDimensionId)
```

``` csharp
public ItemVariantInventoryDimension(
    string itemId,
    string variantInventoryDimensionId
)
```

``` c++
public:
ItemVariantInventoryDimension(
    String^ itemId, 
    String^ variantInventoryDimensionId
)
```

#### Parameters

  - itemId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - variantInventoryDimensionId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ItemVariantInventoryDimension Class](itemvariantinventorydimension-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[ItemVariantInventoryDimension Overload](itemvariantinventorydimension-constructor-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

