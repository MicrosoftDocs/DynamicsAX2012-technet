---
title: GetItemsDataResponse Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetItemsDataResponse Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetItemsDataResponse.#ctor(System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.Item})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getitemsdataresponse.getitemsdataresponse(v=AX.60)
ms:contentKeyID: 65318103
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetItemsDataResponse.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetItemsDataResponse Constructor

Initializes a new instance of the [GetItemsDataResponse](getitemsdataresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    items As ReadOnlyCollection(Of Item) _
)
'Usage
Dim items As ReadOnlyCollection(Of Item)

Dim instance As New GetItemsDataResponse(items)
```

``` csharp
public GetItemsDataResponse(
    ReadOnlyCollection<Item> items
)
```

``` c++
public:
GetItemsDataResponse(
    ReadOnlyCollection<Item^>^ items
)
```

#### Parameters

  - items  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[Item](item-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetItemsDataResponse Class](getitemsdataresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

