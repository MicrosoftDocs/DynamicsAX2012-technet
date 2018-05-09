---
title: GetItemByIdResponse Constructor (IEnumerable(Item)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetItemByIdResponse Constructor (IEnumerable(Item))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetItemByIdResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.Item})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getitembyidresponse.getitembyidresponse(v=AX.60)
ms:contentKeyID: 49845036
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetItemByIdResponse Constructor (IEnumerable(Item))

Initializes a new instance of the [GetItemByIdResponse](getitembyidresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    items As IEnumerable(Of Item) _
)
'Usage
Dim items As IEnumerable(Of Item)

Dim instance As New GetItemByIdResponse(items)
```

``` csharp
public GetItemByIdResponse(
    IEnumerable<Item> items
)
```

``` c++
public:
GetItemByIdResponse(
    IEnumerable<Item^>^ items
)
```

#### Parameters

  - items  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[Item](item-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetItemByIdResponse Class](getitembyidresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetItemByIdResponse Overload](getitembyidresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

