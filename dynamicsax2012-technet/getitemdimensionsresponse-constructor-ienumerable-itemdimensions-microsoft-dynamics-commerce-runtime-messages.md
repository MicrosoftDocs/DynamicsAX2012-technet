---
title: GetItemDimensionsResponse Constructor (IEnumerable(ItemDimensions)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetItemDimensionsResponse Constructor (IEnumerable(ItemDimensions))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetItemDimensionsResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemDimensions})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getitemdimensionsresponse.getitemdimensionsresponse(v=AX.60)
ms:contentKeyID: 62206619
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetItemDimensionsResponse Constructor (IEnumerable(ItemDimensions))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetItemDimensionsResponse](getitemdimensionsresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    itemDimensions As IEnumerable(Of ItemDimensions) _
)
'Usage
Dim itemDimensions As IEnumerable(Of ItemDimensions)

Dim instance As New GetItemDimensionsResponse(itemDimensions)
```

``` csharp
public GetItemDimensionsResponse(
    IEnumerable<ItemDimensions> itemDimensions
)
```

``` c++
public:
GetItemDimensionsResponse(
    IEnumerable<ItemDimensions^>^ itemDimensions
)
```

#### Parameters

  - itemDimensions  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ItemDimensions](itemdimensions-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetItemDimensionsResponse Class](getitemdimensionsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetItemDimensionsResponse Overload](getitemdimensionsresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

