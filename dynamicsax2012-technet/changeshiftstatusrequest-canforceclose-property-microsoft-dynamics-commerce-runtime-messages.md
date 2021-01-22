---
title: ChangeShiftStatusRequest.CanForceClose Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: CanForceClose Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.ChangeShiftStatusRequest.CanForceClose
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.changeshiftstatusrequest.canforceclose(v=AX.60)
ms:contentKeyID: 62212901
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.ChangeShiftStatusRequest.CanForceClose
dev_langs:
- CSharp
- C++
- VB
---

# CanForceClose Property

Gets or sets a value indicating whether the user can close the shift without check starting amounts and tender declaration.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CanForceClose As Boolean
    Get
    Set
'Usage
Dim instance As ChangeShiftStatusRequest
Dim value As Boolean

value = instance.CanForceClose

instance.CanForceClose = value
```

``` csharp
[DataMemberAttribute]
public bool CanForceClose { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool CanForceClose {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[ChangeShiftStatusRequest Class](changeshiftstatusrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

