---
title: CustomerManager.ValidateAccountActivationRequest Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: ValidateAccountActivationRequest Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.CustomerManager.ValidateAccountActivationRequest(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.customermanager.validateaccountactivationrequest(v=AX.60)
ms:contentKeyID: 62208872
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.CustomerManager.ValidateAccountActivationRequest
dev_langs:
- CSharp
- C++
- VB
---

# ValidateAccountActivationRequest Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Validate customer account activation request.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Sub ValidateAccountActivationRequest ( _
    emailAddress As String, _
    activationToken As String _
)
'Usage
Dim instance As CustomerManager
Dim emailAddress As String
Dim activationToken As String

instance.ValidateAccountActivationRequest(emailAddress, _
    activationToken)
```

``` csharp
public void ValidateAccountActivationRequest(
    string emailAddress,
    string activationToken
)
```

``` c++
public:
void ValidateAccountActivationRequest(
    String^ emailAddress, 
    String^ activationToken
)
```

#### Parameters

  - emailAddress  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - activationToken  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[CustomerManager Class](customermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

