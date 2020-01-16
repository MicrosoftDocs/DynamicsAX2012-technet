---
title: AuthenticateDeviceServiceRequest.Token Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: Token Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AuthenticateDeviceServiceRequest.Token
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.authenticatedeviceservicerequest.token(v=AX.60)
ms:contentKeyID: 62208931
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AuthenticateDeviceServiceRequest.Token
dev_langs:
- CSharp
- C++
- VB
---

# Token Property

Gets the device token.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Token As String
    Get
    Private Set
'Usage
Dim instance As AuthenticateDeviceServiceRequest
Dim value As String

value = instance.Token
```

``` csharp
[DataMemberAttribute]
public string Token { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Token {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[AuthenticateDeviceServiceRequest Class](authenticatedeviceservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

