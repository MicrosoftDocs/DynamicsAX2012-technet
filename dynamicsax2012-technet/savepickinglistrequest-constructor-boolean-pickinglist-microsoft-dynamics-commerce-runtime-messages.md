---
title: SavePickingListRequest Constructor (Boolean, PickingList) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: SavePickingListRequest Constructor (Boolean, PickingList)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.SavePickingListRequest.#ctor(System.Boolean,Microsoft.Dynamics.Commerce.Runtime.DataModel.PickingList)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.savepickinglistrequest.savepickinglistrequest(v=AX.60)
ms:contentKeyID: 62212420
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# SavePickingListRequest Constructor (Boolean, PickingList)

Initializes a new instance of the [SavePickingListRequest](savepickinglistrequest-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

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

Dim instance As New SavePickingListRequest(commit, _
    pickingList)
```

``` csharp
public SavePickingListRequest(
    bool commit,
    PickingList pickingList
)
```

``` c++
public:
SavePickingListRequest(
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

[SavePickingListRequest Class](savepickinglistrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[SavePickingListRequest Overload](savepickinglistrequest-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

