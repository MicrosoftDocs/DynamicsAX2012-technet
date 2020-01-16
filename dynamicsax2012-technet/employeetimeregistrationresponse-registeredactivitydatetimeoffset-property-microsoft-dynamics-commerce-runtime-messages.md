---
title: EmployeeTimeRegistrationResponse.RegisteredActivityDateTimeOffset Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: RegisteredActivityDateTimeOffset Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.EmployeeTimeRegistrationResponse.RegisteredActivityDateTimeOffset
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.employeetimeregistrationresponse.registeredactivitydatetimeoffset(v=AX.60)
ms:contentKeyID: 62210153
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.EmployeeTimeRegistrationResponse.RegisteredActivityDateTimeOffset
dev_langs:
- CSharp
- C++
- VB
---

# RegisteredActivityDateTimeOffset Property

Gets the current registered activity datetime.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property RegisteredActivityDateTimeOffset As DateTimeOffset
    Get
    Private Set
'Usage
Dim instance As EmployeeTimeRegistrationResponse
Dim value As DateTimeOffset

value = instance.RegisteredActivityDateTimeOffset
```

``` csharp
[DataMemberAttribute]
public DateTimeOffset RegisteredActivityDateTimeOffset { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property DateTimeOffset RegisteredActivityDateTimeOffset {
    DateTimeOffset get ();
    private: void set (DateTimeOffset value);
}
```

#### Property Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  
Returns [DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\)).  

## See Also

#### Reference

[EmployeeTimeRegistrationResponse Class](employeetimeregistrationresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

