---
title: GetPickingListServiceResponse.PickingLists Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: PickingLists Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetPickingListServiceResponse.PickingLists
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getpickinglistserviceresponse.pickinglists(v=AX.60)
ms:contentKeyID: 62211007
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetPickingListServiceResponse.PickingLists
dev_langs:
- CSharp
- C++
- VB
---

# PickingLists Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the picking lists.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property PickingLists As ReadOnlyCollection(Of PickingList)
    Get
    Private Set
'Usage
Dim instance As GetPickingListServiceResponse
Dim value As ReadOnlyCollection(Of PickingList)

value = instance.PickingLists
```

``` csharp
public ReadOnlyCollection<PickingList> PickingLists { get; private set; }
```

``` c++
public:
property ReadOnlyCollection<PickingList^>^ PickingLists {
    ReadOnlyCollection<PickingList^>^ get ();
    private: void set (ReadOnlyCollection<PickingList^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[PickingList](pickinglist-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetPickingListServiceResponse Class](getpickinglistserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

