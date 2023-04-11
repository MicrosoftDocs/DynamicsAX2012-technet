---
title: AuthorizePaymentServiceRequest.IsCardTokenRequired Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: IsCardTokenRequired Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AuthorizePaymentServiceRequest.IsCardTokenRequired
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.authorizepaymentservicerequest.iscardtokenrequired(v=AX.60)
ms:contentKeyID: 65321911
author: tonyafehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AuthorizePaymentServiceRequest.IsCardTokenRequired
dev_langs:
- CSharp
- C++
- VB
---

# IsCardTokenRequired Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsCardTokenRequired As Boolean
    Get
    Private Set
'Usage
Dim instance As AuthorizePaymentServiceRequest
Dim value As Boolean

value = instance.IsCardTokenRequired
```

``` csharp
[DataMemberAttribute]
public bool IsCardTokenRequired { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsCardTokenRequired {
    bool get ();
    private: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[AuthorizePaymentServiceRequest Class](authorizepaymentservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

