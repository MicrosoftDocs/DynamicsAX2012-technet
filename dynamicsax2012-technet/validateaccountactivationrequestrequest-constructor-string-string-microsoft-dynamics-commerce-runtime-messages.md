---
title: ValidateAccountActivationRequestRequest Constructor (String, String) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ValidateAccountActivationRequestRequest Constructor (String, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.ValidateAccountActivationRequestRequest.#ctor(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.validateaccountactivationrequestrequest.validateaccountactivationrequestrequest(v=AX.60)
ms:contentKeyID: 62208516
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ValidateAccountActivationRequestRequest Constructor (String, String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [ValidateAccountActivationRequestRequest](validateaccountactivationrequestrequest-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    emailAddress As String, _
    activationToken As String _
)
'Usage
Dim emailAddress As String
Dim activationToken As String

Dim instance As New ValidateAccountActivationRequestRequest(emailAddress, _
    activationToken)
```

``` csharp
public ValidateAccountActivationRequestRequest(
    string emailAddress,
    string activationToken
)
```

``` c++
public:
ValidateAccountActivationRequestRequest(
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

[ValidateAccountActivationRequestRequest Class](validateaccountactivationrequestrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[ValidateAccountActivationRequestRequest Overload](validateaccountactivationrequestrequest-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

