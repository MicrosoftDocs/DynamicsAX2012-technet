---
title: ValidateAccountActivationRequestServiceRequest.ActivationToken Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ActivationToken Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateAccountActivationRequestServiceRequest.ActivationToken
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.validateaccountactivationrequestservicerequest.activationtoken(v=AX.60)
ms:contentKeyID: 62215007
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateAccountActivationRequestServiceRequest.ActivationToken
dev_langs:
- CSharp
- C++
- VB
---

# ActivationToken Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the activation token of the request.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ActivationToken As String
    Get
    Private Set
'Usage
Dim instance As ValidateAccountActivationRequestServiceRequest
Dim value As String

value = instance.ActivationToken
```

``` csharp
[DataMemberAttribute]
public string ActivationToken { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ActivationToken {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ValidateAccountActivationRequestServiceRequest Class](validateaccountactivationrequestservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

