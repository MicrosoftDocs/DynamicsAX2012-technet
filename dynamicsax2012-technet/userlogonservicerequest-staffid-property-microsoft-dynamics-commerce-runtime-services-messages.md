---
title: UserLogOnServiceRequest.StaffId Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: StaffId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UserLogOnServiceRequest.StaffId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.userlogonservicerequest.staffid(v=AX.60)
ms:contentKeyID: 62213029
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UserLogOnServiceRequest.StaffId
dev_langs:
- CSharp
- C++
- VB
---

# StaffId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the Staff Identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property StaffId As String
    Get
    Private Set
'Usage
Dim instance As UserLogOnServiceRequest
Dim value As String

value = instance.StaffId
```

``` csharp
[DataMemberAttribute]
public string StaffId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ StaffId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[UserLogOnServiceRequest Class](userlogonservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

