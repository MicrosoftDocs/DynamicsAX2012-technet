---
title: ChangeShiftStatusRequest.ToStatus Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ToStatus Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.ChangeShiftStatusRequest.ToStatus
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.changeshiftstatusrequest.tostatus(v=AX.60)
ms:contentKeyID: 62212357
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.ChangeShiftStatusRequest.ToStatus
dev_langs:
- CSharp
- C++
- VB
---

# ToStatus Property

Gets or sets the target shift status.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ToStatus As ShiftStatus
    Get
    Set
'Usage
Dim instance As ChangeShiftStatusRequest
Dim value As ShiftStatus

value = instance.ToStatus

instance.ToStatus = value
```

``` csharp
[DataMemberAttribute]
public ShiftStatus ToStatus { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property ShiftStatus ToStatus {
    ShiftStatus get ();
    void set (ShiftStatus value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftStatus](shiftstatus-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ShiftStatus](shiftstatus-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[ChangeShiftStatusRequest Class](changeshiftstatusrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

