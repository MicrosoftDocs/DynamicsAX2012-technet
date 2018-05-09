---
title: GetAvailableShiftsResponse Constructor (IEnumerable(Shift)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetAvailableShiftsResponse Constructor (IEnumerable(Shift))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetAvailableShiftsResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getavailableshiftsresponse.getavailableshiftsresponse(v=AX.60)
ms:contentKeyID: 62210572
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetAvailableShiftsResponse Constructor (IEnumerable(Shift))

Initializes a new instance of the [GetAvailableShiftsResponse](getavailableshiftsresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    shifts As IEnumerable(Of Shift) _
)
'Usage
Dim shifts As IEnumerable(Of Shift)

Dim instance As New GetAvailableShiftsResponse(shifts)
```

``` csharp
public GetAvailableShiftsResponse(
    IEnumerable<Shift> shifts
)
```

``` c++
public:
GetAvailableShiftsResponse(
    IEnumerable<Shift^>^ shifts
)
```

#### Parameters

  - shifts  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[Shift](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetAvailableShiftsResponse Class](getavailableshiftsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetAvailableShiftsResponse Overload](getavailableshiftsresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

