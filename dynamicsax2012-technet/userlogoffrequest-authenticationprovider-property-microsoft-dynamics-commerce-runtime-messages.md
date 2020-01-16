---
title: UserLogOffRequest.AuthenticationProvider Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: AuthenticationProvider Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.UserLogOffRequest.AuthenticationProvider
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.userlogoffrequest.authenticationprovider(v=AX.60)
ms:contentKeyID: 62208942
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.UserLogOffRequest.AuthenticationProvider
dev_langs:
- CSharp
- C++
- VB
---

# AuthenticationProvider Property

Gets or sets the Authentication Provider.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property AuthenticationProvider As String
    Get
    Set
'Usage
Dim instance As UserLogOffRequest
Dim value As String

value = instance.AuthenticationProvider

instance.AuthenticationProvider = value
```

``` csharp
[DataMemberAttribute]
public string AuthenticationProvider { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ AuthenticationProvider {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The authentication provider.  

## See Also

#### Reference

[UserLogOffRequest Class](userlogoffrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

