---
title: CompleteAccountActivationRequest Constructor (String, String) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: CompleteAccountActivationRequest Constructor (String, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.CompleteAccountActivationRequest.#ctor(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.completeaccountactivationrequest.completeaccountactivationrequest(v=AX.60)
ms:contentKeyID: 62214387
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CompleteAccountActivationRequest Constructor (String, String)

Initializes a new instance of the [CompleteAccountActivationRequest](completeaccountactivationrequest-class-microsoft-dynamics-commerce-runtime-messages.md) class.

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

Dim instance As New CompleteAccountActivationRequest(emailAddress, _
    activationToken)
```

``` csharp
public CompleteAccountActivationRequest(
    string emailAddress,
    string activationToken
)
```

``` c++
public:
CompleteAccountActivationRequest(
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

[CompleteAccountActivationRequest Class](completeaccountactivationrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[CompleteAccountActivationRequest Overload](completeaccountactivationrequest-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

