---
title: ValidateAccountActivationRequestServiceRequest Constructor (String, String) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ValidateAccountActivationRequestServiceRequest Constructor (String, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateAccountActivationRequestServiceRequest.#ctor(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.validateaccountactivationrequestservicerequest.validateaccountactivationrequestservicerequest(v=AX.60)
ms:contentKeyID: 65321616
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ValidateAccountActivationRequestServiceRequest Constructor (String, String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

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

Dim instance As New ValidateAccountActivationRequestServiceRequest(emailAddress, _
    activationToken)
```

``` csharp
public ValidateAccountActivationRequestServiceRequest(
    string emailAddress,
    string activationToken
)
```

``` c++
public:
ValidateAccountActivationRequestServiceRequest(
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

[ValidateAccountActivationRequestServiceRequest Class](validateaccountactivationrequestservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[ValidateAccountActivationRequestServiceRequest Overload](validateaccountactivationrequestservicerequest-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

