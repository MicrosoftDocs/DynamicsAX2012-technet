---
title: SaveCustomerAccountActivationServiceRequest Constructor (String, String, Int32) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: SaveCustomerAccountActivationServiceRequest Constructor (String, String, Int32)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveCustomerAccountActivationServiceRequest.#ctor(System.String,System.String,System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.savecustomeraccountactivationservicerequest.savecustomeraccountactivationservicerequest(v=AX.60)
ms:contentKeyID: 65321549
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# SaveCustomerAccountActivationServiceRequest Constructor (String, String, Int32)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    emailAddress As String, _
    activationToken As String, _
    status As Integer _
)
'Usage
Dim emailAddress As String
Dim activationToken As String
Dim status As Integer

Dim instance As New SaveCustomerAccountActivationServiceRequest(emailAddress, _
    activationToken, status)
```

``` csharp
public SaveCustomerAccountActivationServiceRequest(
    string emailAddress,
    string activationToken,
    int status
)
```

``` c++
public:
SaveCustomerAccountActivationServiceRequest(
    String^ emailAddress, 
    String^ activationToken, 
    int status
)
```

#### Parameters

  - emailAddress  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - activationToken  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - status  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[SaveCustomerAccountActivationServiceRequest Class](savecustomeraccountactivationservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[SaveCustomerAccountActivationServiceRequest Overload](savecustomeraccountactivationservicerequest-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

