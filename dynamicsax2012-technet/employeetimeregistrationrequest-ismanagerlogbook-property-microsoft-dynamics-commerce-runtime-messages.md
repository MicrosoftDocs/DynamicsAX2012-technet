---
title: EmployeeTimeRegistrationRequest.IsManagerLogbook Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: IsManagerLogbook Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.EmployeeTimeRegistrationRequest.IsManagerLogbook
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.employeetimeregistrationrequest.ismanagerlogbook(v=AX.60)
ms:contentKeyID: 62204766
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.EmployeeTimeRegistrationRequest.IsManagerLogbook
dev_langs:
- CSharp
- C++
- VB
---

# IsManagerLogbook Property

Gets or sets a value indicating whether the incoming request is from manager to view log book details.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsManagerLogbook As Boolean
    Get
    Set
'Usage
Dim instance As EmployeeTimeRegistrationRequest
Dim value As Boolean

value = instance.IsManagerLogbook

instance.IsManagerLogbook = value
```

``` csharp
[DataMemberAttribute]
public bool IsManagerLogbook { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsManagerLogbook {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[EmployeeTimeRegistrationRequest Class](employeetimeregistrationrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

