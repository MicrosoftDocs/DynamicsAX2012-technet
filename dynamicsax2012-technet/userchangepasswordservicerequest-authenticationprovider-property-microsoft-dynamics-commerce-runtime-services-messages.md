---
title: UserChangePasswordServiceRequest.AuthenticationProvider Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: AuthenticationProvider Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UserChangePasswordServiceRequest.AuthenticationProvider
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.userchangepasswordservicerequest.authenticationprovider(v=AX.60)
ms:contentKeyID: 62214820
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UserChangePasswordServiceRequest.AuthenticationProvider
dev_langs:
- CSharp
- C++
- VB
---

# AuthenticationProvider Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the Authentication Provider.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property AuthenticationProvider As String
    Get
    Private Set
'Usage
Dim instance As UserChangePasswordServiceRequest
Dim value As String

value = instance.AuthenticationProvider
```

``` csharp
[DataMemberAttribute]
public string AuthenticationProvider { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ AuthenticationProvider {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[UserChangePasswordServiceRequest Class](userchangepasswordservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

