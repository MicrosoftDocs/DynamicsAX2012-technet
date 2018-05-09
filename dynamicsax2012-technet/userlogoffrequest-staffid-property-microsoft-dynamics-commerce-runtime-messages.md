---
title: UserLogOffRequest.StaffId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: StaffId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.UserLogOffRequest.StaffId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.userlogoffrequest.staffid(v=AX.60)
ms:contentKeyID: 62212957
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.UserLogOffRequest.StaffId
dev_langs:
- CSharp
- C++
- VB
---

# StaffId Property

Gets or sets the staff identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property StaffId As String
    Get
    Set
'Usage
Dim instance As UserLogOffRequest
Dim value As String

value = instance.StaffId

instance.StaffId = value
```

``` csharp
[DataMemberAttribute]
public string StaffId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ StaffId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The staff identifier.  

## See Also

#### Reference

[UserLogOffRequest Class](userlogoffrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

