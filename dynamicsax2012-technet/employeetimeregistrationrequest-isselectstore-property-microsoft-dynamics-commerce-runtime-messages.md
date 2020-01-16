---
title: EmployeeTimeRegistrationRequest.IsSelectStore Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: IsSelectStore Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.EmployeeTimeRegistrationRequest.IsSelectStore
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.employeetimeregistrationrequest.isselectstore(v=AX.60)
ms:contentKeyID: 62209697
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.EmployeeTimeRegistrationRequest.IsSelectStore
dev_langs:
- CSharp
- C++
- VB
---

# IsSelectStore Property

Gets or sets a value indicating whether to select store flag.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsSelectStore As Boolean
    Get
    Set
'Usage
Dim instance As EmployeeTimeRegistrationRequest
Dim value As Boolean

value = instance.IsSelectStore

instance.IsSelectStore = value
```

``` csharp
[DataMemberAttribute]
public bool IsSelectStore { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsSelectStore {
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

