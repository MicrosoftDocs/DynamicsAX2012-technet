---
title: GetStoreAvailabilityServiceResponse.ItemsAvailability Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ItemsAvailability Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetStoreAvailabilityServiceResponse.ItemsAvailability
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getstoreavailabilityserviceresponse.itemsavailability(v=AX.60)
ms:contentKeyID: 65315664
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetStoreAvailabilityServiceResponse.ItemsAvailability
dev_langs:
- CSharp
- C++
- VB
---

# ItemsAvailability Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property ItemsAvailability As IList(Of ItemAvailableStore)
    Get
    Private Set
'Usage
Dim instance As GetStoreAvailabilityServiceResponse
Dim value As IList(Of ItemAvailableStore)

value = instance.ItemsAvailability
```

``` csharp
public IList<ItemAvailableStore> ItemsAvailability { get; private set; }
```

``` c++
public:
property IList<ItemAvailableStore^>^ ItemsAvailability {
    IList<ItemAvailableStore^>^ get ();
    private: void set (IList<ItemAvailableStore^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[ItemAvailableStore](itemavailablestore-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetStoreAvailabilityServiceResponse Class](getstoreavailabilityserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

