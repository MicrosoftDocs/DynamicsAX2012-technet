---
title: GetPickingListResponse.PickingLists Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: PickingLists Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetPickingListResponse.PickingLists
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getpickinglistresponse.pickinglists(v=AX.60)
ms:contentKeyID: 62205522
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetPickingListResponse.PickingLists
dev_langs:
- CSharp
- C++
- VB
---

# PickingLists Property

Gets the collection of picking lists.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PickingLists As ReadOnlyCollection(Of PickingList)
    Get
    Private Set
'Usage
Dim instance As GetPickingListResponse
Dim value As ReadOnlyCollection(Of PickingList)

value = instance.PickingLists
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<PickingList> PickingLists { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<PickingList^>^ PickingLists {
    ReadOnlyCollection<PickingList^>^ get ();
    private: void set (ReadOnlyCollection<PickingList^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[PickingList](pickinglist-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetPickingListResponse Class](getpickinglistresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

