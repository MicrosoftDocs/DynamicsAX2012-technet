---
title: UserAuthenticationRequest.StaffId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: StaffId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.UserAuthenticationRequest.StaffId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.userauthenticationrequest.staffid(v=AX.60)
ms:contentKeyID: 62209173
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.UserAuthenticationRequest.StaffId
dev_langs:
- CSharp
- C++
- VB
---

# StaffId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

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
Dim instance As UserAuthenticationRequest
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

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The staff identifier.  

## See Also

#### Reference

[UserAuthenticationRequest Class](userauthenticationrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

