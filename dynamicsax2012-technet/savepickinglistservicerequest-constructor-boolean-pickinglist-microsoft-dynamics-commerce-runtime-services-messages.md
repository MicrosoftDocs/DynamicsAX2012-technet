---
title: SavePickingListServiceRequest Constructor (Boolean, PickingList) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: SavePickingListServiceRequest Constructor (Boolean, PickingList)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SavePickingListServiceRequest.#ctor(System.Boolean,Microsoft.Dynamics.Commerce.Runtime.DataModel.PickingList)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.savepickinglistservicerequest.savepickinglistservicerequest(v=AX.60)
ms:contentKeyID: 65319125
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# SavePickingListServiceRequest Constructor (Boolean, PickingList)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    commit As Boolean, _
    pickingList As PickingList _
)
'Usage
Dim commit As Boolean
Dim pickingList As PickingList

Dim instance As New SavePickingListServiceRequest(commit, _
    pickingList)
```

``` csharp
public SavePickingListServiceRequest(
    bool commit,
    PickingList pickingList
)
```

``` c++
public:
SavePickingListServiceRequest(
    bool commit, 
    PickingList^ pickingList
)
```

#### Parameters

  - commit  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - pickingList  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PickingList](pickinglist-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[SavePickingListServiceRequest Class](savepickinglistservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[SavePickingListServiceRequest Overload](savepickinglistservicerequest-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

