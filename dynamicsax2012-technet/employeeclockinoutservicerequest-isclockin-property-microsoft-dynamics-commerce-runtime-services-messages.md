---
title: EmployeeClockInOutServiceRequest.IsClockIn Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: IsClockIn Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.EmployeeClockInOutServiceRequest.IsClockIn
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.employeeclockinoutservicerequest.isclockin(v=AX.60)
ms:contentKeyID: 65319502
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.EmployeeClockInOutServiceRequest.IsClockIn
dev_langs:
- CSharp
- C++
- VB
---

# IsClockIn Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsClockIn As Boolean
    Get
    Private Set
'Usage
Dim instance As EmployeeClockInOutServiceRequest
Dim value As Boolean

value = instance.IsClockIn
```

``` csharp
[DataMemberAttribute]
public bool IsClockIn { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsClockIn {
    bool get ();
    private: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[EmployeeClockInOutServiceRequest Class](employeeclockinoutservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

