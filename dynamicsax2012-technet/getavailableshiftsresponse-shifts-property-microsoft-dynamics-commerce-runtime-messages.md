---
title: GetAvailableShiftsResponse.Shifts Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Shifts Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetAvailableShiftsResponse.Shifts
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getavailableshiftsresponse.shifts(v=AX.60)
ms:contentKeyID: 62208399
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetAvailableShiftsResponse.Shifts
dev_langs:
- CSharp
- C++
- VB
---

# Shifts Property

Gets the collection of available shifts.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Shifts As ReadOnlyCollection(Of Shift)
    Get
    Private Set
'Usage
Dim instance As GetAvailableShiftsResponse
Dim value As ReadOnlyCollection(Of Shift)

value = instance.Shifts
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<Shift> Shifts { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<Shift^>^ Shifts {
    ReadOnlyCollection<Shift^>^ get ();
    private: void set (ReadOnlyCollection<Shift^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Shift](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetAvailableShiftsResponse Class](getavailableshiftsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

