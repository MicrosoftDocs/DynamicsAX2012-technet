---
title: GetPickingListServiceResponse Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetPickingListServiceResponse Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetPickingListServiceResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.PickingList})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getpickinglistserviceresponse.getpickinglistserviceresponse(v=AX.60)
ms:contentKeyID: 62214382
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetPickingListServiceResponse.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetPickingListServiceResponse Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the GetPickingListServiceResponse class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    pickingLists As IEnumerable(Of PickingList) _
)
'Usage
Dim pickingLists As IEnumerable(Of PickingList)

Dim instance As New GetPickingListServiceResponse(pickingLists)
```

``` csharp
public GetPickingListServiceResponse(
    IEnumerable<PickingList> pickingLists
)
```

``` c++
public:
GetPickingListServiceResponse(
    IEnumerable<PickingList^>^ pickingLists
)
```

#### Parameters

  - pickingLists  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[PickingList](pickinglist-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetPickingListServiceResponse Class](getpickinglistserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

