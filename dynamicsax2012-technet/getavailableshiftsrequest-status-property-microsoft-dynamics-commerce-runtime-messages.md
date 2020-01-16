---
title: GetAvailableShiftsRequest.Status Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Status Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetAvailableShiftsRequest.Status
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getavailableshiftsrequest.status(v=AX.60)
ms:contentKeyID: 62210694
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetAvailableShiftsRequest.Status
dev_langs:
- CSharp
- C++
- VB
---

# Status Property

Gets or sets the expected shift status.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Status As ShiftStatus
    Get
    Set
'Usage
Dim instance As GetAvailableShiftsRequest
Dim value As ShiftStatus

value = instance.Status

instance.Status = value
```

``` csharp
[DataMemberAttribute]
public ShiftStatus Status { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property ShiftStatus Status {
    ShiftStatus get ();
    void set (ShiftStatus value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftStatus](shiftstatus-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ShiftStatus](shiftstatus-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetAvailableShiftsRequest Class](getavailableshiftsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

