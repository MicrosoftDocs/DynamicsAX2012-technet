---
title: GetPickingListResponse Constructor (IEnumerable(PickingList)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetPickingListResponse Constructor (IEnumerable(PickingList))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetPickingListResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.PickingList})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getpickinglistresponse.getpickinglistresponse(v=AX.60)
ms:contentKeyID: 62215104
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetPickingListResponse Constructor (IEnumerable(PickingList))

Initializes a new instance of the [GetPickingListResponse](getpickinglistresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    pickingLists As IEnumerable(Of PickingList) _
)
'Usage
Dim pickingLists As IEnumerable(Of PickingList)

Dim instance As New GetPickingListResponse(pickingLists)
```

``` csharp
public GetPickingListResponse(
    IEnumerable<PickingList> pickingLists
)
```

``` c++
public:
GetPickingListResponse(
    IEnumerable<PickingList^>^ pickingLists
)
```

#### Parameters

  - pickingLists  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[PickingList](pickinglist-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetPickingListResponse Class](getpickinglistresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetPickingListResponse Overload](getpickinglistresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

