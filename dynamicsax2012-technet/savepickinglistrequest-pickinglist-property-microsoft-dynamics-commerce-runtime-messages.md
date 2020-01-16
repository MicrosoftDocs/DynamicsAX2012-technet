---
title: SavePickingListRequest.PickingList Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: PickingList Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.SavePickingListRequest.PickingList
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.savepickinglistrequest.pickinglist(v=AX.60)
ms:contentKeyID: 62211366
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.SavePickingListRequest.PickingList
dev_langs:
- CSharp
- C++
- VB
---

# PickingList Property

Gets the picking list to save.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PickingList As PickingList
    Get
    Private Set
'Usage
Dim instance As SavePickingListRequest
Dim value As PickingList

value = instance.PickingList
```

``` csharp
[DataMemberAttribute]
public PickingList PickingList { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property PickingList^ PickingList {
    PickingList^ get ();
    private: void set (PickingList^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PickingList](pickinglist-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [PickingList](pickinglist-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[SavePickingListRequest Class](savepickinglistrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

