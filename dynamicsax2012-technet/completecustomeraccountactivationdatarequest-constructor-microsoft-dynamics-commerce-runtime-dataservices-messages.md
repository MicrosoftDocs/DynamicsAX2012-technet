---
title: CompleteCustomerAccountActivationDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: CompleteCustomerAccountActivationDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.CompleteCustomerAccountActivationDataRequest.#ctor(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.completecustomeraccountactivationdatarequest.completecustomeraccountactivationdatarequest(v=AX.60)
ms:contentKeyID: 65321961
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.CompleteCustomerAccountActivationDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# CompleteCustomerAccountActivationDataRequest Constructor

Initializes a new instance of the [CompleteCustomerAccountActivationDataRequest](completecustomeraccountactivationdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    email As String, _
    activationToken As String _
)
'Usage
Dim email As String
Dim activationToken As String

Dim instance As New CompleteCustomerAccountActivationDataRequest(email, activationToken)
```

``` csharp
public CompleteCustomerAccountActivationDataRequest(
    string email,
    string activationToken
)
```

``` c++
public:
CompleteCustomerAccountActivationDataRequest(
    String^ email, 
    String^ activationToken
)
```

#### Parameters

  - email  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - activationToken  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[CompleteCustomerAccountActivationDataRequest Class](completecustomeraccountactivationdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

