﻿---
title: GetShiftRequest.ShiftId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ShiftId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetShiftRequest.ShiftId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getshiftrequest.shiftid(v=AX.60)
ms:contentKeyID: 62210011
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetShiftRequest.ShiftId
dev_langs:
- CSharp
- C++
- VB
---

# ShiftId Property

Gets or sets the shift identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ShiftId As Long
    Get
    Set
'Usage
Dim instance As GetShiftRequest
Dim value As Long

value = instance.ShiftId

instance.ShiftId = value
```

``` csharp
[DataMemberAttribute]
public long ShiftId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property long long ShiftId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[GetShiftRequest Class](getshiftrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)
