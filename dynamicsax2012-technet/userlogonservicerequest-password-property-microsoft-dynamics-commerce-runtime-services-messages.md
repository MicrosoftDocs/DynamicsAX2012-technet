---
title: UserLogOnServiceRequest.Password Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: Password Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UserLogOnServiceRequest.Password
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.userlogonservicerequest.password(v=AX.60)
ms:contentKeyID: 62211861
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UserLogOnServiceRequest.Password
dev_langs:
- CSharp
- C++
- VB
---

# Password Property

Gets the password.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Password As String
    Get
    Private Set
'Usage
Dim instance As UserLogOnServiceRequest
Dim value As String

value = instance.Password
```

``` csharp
[DataMemberAttribute]
public string Password { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Password {
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

