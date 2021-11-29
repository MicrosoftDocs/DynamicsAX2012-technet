---
title: SavePickingListServiceRequest.PickingList Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: PickingList Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SavePickingListServiceRequest.PickingList
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.savepickinglistservicerequest.pickinglist(v=AX.60)
ms:contentKeyID: 62212233
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SavePickingListServiceRequest.PickingList
dev_langs:
- CSharp
- C++
- VB
---

# PickingList Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the picking list to be saved.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PickingList As PickingList
    Get
    Set
'Usage
Dim instance As SavePickingListServiceRequest
Dim value As PickingList

value = instance.PickingList

instance.PickingList = value
```

``` csharp
[DataMemberAttribute]
public PickingList PickingList { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property PickingList^ PickingList {
    PickingList^ get ();
    void set (PickingList^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PickingList](pickinglist-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [PickingList](pickinglist-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[SavePickingListServiceRequest Class](savepickinglistservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

