---
title: UnableToDetermineQuantityNotification Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: UnableToDetermineQuantityNotification Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.UnableToDetermineQuantityNotification.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemVariantInventoryDimension})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.unabletodeterminequantitynotification.unabletodeterminequantitynotification(v=AX.60)
ms:contentKeyID: 65320428
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.UnableToDetermineQuantityNotification.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# UnableToDetermineQuantityNotification Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [UnableToDetermineQuantityNotification](unabletodeterminequantitynotification-class-microsoft-dynamics-commerce-runtime-datamodel.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    inventVariantIds As IEnumerable(Of ItemVariantInventoryDimension) _
)
'Usage
Dim inventVariantIds As IEnumerable(Of ItemVariantInventoryDimension)

Dim instance As New UnableToDetermineQuantityNotification(inventVariantIds)
```

``` csharp
public UnableToDetermineQuantityNotification(
    IEnumerable<ItemVariantInventoryDimension> inventVariantIds
)
```

``` c++
public:
UnableToDetermineQuantityNotification(
    IEnumerable<ItemVariantInventoryDimension^>^ inventVariantIds
)
```

#### Parameters

  - inventVariantIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ItemVariantInventoryDimension](itemvariantinventorydimension-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[UnableToDetermineQuantityNotification Class](unabletodeterminequantitynotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

