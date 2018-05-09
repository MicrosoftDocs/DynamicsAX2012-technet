---
title: CreateShiftRequest.ShiftId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ShiftId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.CreateShiftRequest.ShiftId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.createshiftrequest.shiftid(v=AX.60)
ms:contentKeyID: 65320606
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.CreateShiftRequest.ShiftId
dev_langs:
- CSharp
- C++
- VB
---

# ShiftId Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ShiftId As Nullable(Of Long)
    Get
    Set
'Usage
Dim instance As CreateShiftRequest
Dim value As Nullable(Of Long)

value = instance.ShiftId

instance.ShiftId = value
```

``` csharp
[DataMemberAttribute]
public Nullable<long> ShiftId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Nullable<long long> ShiftId {
    Nullable<long long> get ();
    void set (Nullable<long long> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))\>  

## See Also

#### Reference

[CreateShiftRequest Class](createshiftrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

