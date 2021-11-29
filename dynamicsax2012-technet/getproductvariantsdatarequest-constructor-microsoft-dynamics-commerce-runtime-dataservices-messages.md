---
title: GetProductVariantsDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetProductVariantsDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductVariantsDataRequest.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemVariantInventoryDimension})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getproductvariantsdatarequest.getproductvariantsdatarequest(v=AX.60)
ms:contentKeyID: 65320161
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductVariantsDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetProductVariantsDataRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetProductVariantsDataRequest](getproductvariantsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    itemAndInventoryDimensionIds As IEnumerable(Of ItemVariantInventoryDimension) _
)
'Usage
Dim itemAndInventoryDimensionIds As IEnumerable(Of ItemVariantInventoryDimension)

Dim instance As New GetProductVariantsDataRequest(itemAndInventoryDimensionIds)
```

``` csharp
public GetProductVariantsDataRequest(
    IEnumerable<ItemVariantInventoryDimension> itemAndInventoryDimensionIds
)
```

``` c++
public:
GetProductVariantsDataRequest(
    IEnumerable<ItemVariantInventoryDimension^>^ itemAndInventoryDimensionIds
)
```

#### Parameters

  - itemAndInventoryDimensionIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ItemVariantInventoryDimension](itemvariantinventorydimension-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetProductVariantsDataRequest Class](getproductvariantsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

