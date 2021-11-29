---
title: GetStoreAvailabilityServiceResponse Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetStoreAvailabilityServiceResponse Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetStoreAvailabilityServiceResponse.#ctor(System.Collections.Generic.IList{Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailableStore})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getstoreavailabilityserviceresponse.getstoreavailabilityserviceresponse(v=AX.60)
ms:contentKeyID: 65315527
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetStoreAvailabilityServiceResponse.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetStoreAvailabilityServiceResponse Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    itemsAvailability As IList(Of ItemAvailableStore) _
)
'Usage
Dim itemsAvailability As IList(Of ItemAvailableStore)

Dim instance As New GetStoreAvailabilityServiceResponse(itemsAvailability)
```

``` csharp
public GetStoreAvailabilityServiceResponse(
    IList<ItemAvailableStore> itemsAvailability
)
```

``` c++
public:
GetStoreAvailabilityServiceResponse(
    IList<ItemAvailableStore^>^ itemsAvailability
)
```

#### Parameters

  - itemsAvailability  
    Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[ItemAvailableStore](itemavailablestore-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetStoreAvailabilityServiceResponse Class](getstoreavailabilityserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

