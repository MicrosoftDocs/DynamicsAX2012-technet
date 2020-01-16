---
title: UserAuthenticationRenewalResponse.LogonCredentials Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: LogonCredentials Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.UserAuthenticationRenewalResponse.LogonCredentials
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.userauthenticationrenewalresponse.logoncredentials(v=AX.60)
ms:contentKeyID: 65322761
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.UserAuthenticationRenewalResponse.LogonCredentials
dev_langs:
- CSharp
- C++
- VB
---

# LogonCredentials Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LogonCredentials As LogonCredentials
    Get
    Private Set
'Usage
Dim instance As UserAuthenticationRenewalResponse
Dim value As LogonCredentials

value = instance.LogonCredentials
```

``` csharp
[DataMemberAttribute]
public LogonCredentials LogonCredentials { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property LogonCredentials^ LogonCredentials {
    LogonCredentials^ get ();
    private: void set (LogonCredentials^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Entities.LogonCredentials](logoncredentials-class-microsoft-dynamics-commerce-runtime-entities.md)  

## See Also

#### Reference

[UserAuthenticationRenewalResponse Class](userauthenticationrenewalresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

