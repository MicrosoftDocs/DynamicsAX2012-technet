---
title: AuthorizePaymentServiceRequest.SkipLimitValidation Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: SkipLimitValidation Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AuthorizePaymentServiceRequest.SkipLimitValidation
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.authorizepaymentservicerequest.skiplimitvalidation(v=AX.60)
ms:contentKeyID: 62213351
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AuthorizePaymentServiceRequest.SkipLimitValidation
dev_langs:
- CSharp
- C++
- VB
---

# SkipLimitValidation Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether validation will be skipped.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SkipLimitValidation As Boolean
    Get
    Private Set
'Usage
Dim instance As AuthorizePaymentServiceRequest
Dim value As Boolean

value = instance.SkipLimitValidation
```

``` csharp
[DataMemberAttribute]
public bool SkipLimitValidation { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property bool SkipLimitValidation {
    bool get ();
    private: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[AuthorizePaymentServiceRequest Class](authorizepaymentservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

