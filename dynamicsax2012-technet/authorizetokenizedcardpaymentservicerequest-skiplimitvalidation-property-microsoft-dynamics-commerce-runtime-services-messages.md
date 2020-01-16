---
title: AuthorizeTokenizedCardPaymentServiceRequest.SkipLimitValidation Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: SkipLimitValidation Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AuthorizeTokenizedCardPaymentServiceRequest.SkipLimitValidation
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.authorizetokenizedcardpaymentservicerequest.skiplimitvalidation(v=AX.60)
ms:contentKeyID: 65322167
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AuthorizeTokenizedCardPaymentServiceRequest.SkipLimitValidation
dev_langs:
- CSharp
- C++
- VB
---

# SkipLimitValidation Property

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
Dim instance As AuthorizeTokenizedCardPaymentServiceRequest
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

## See Also

#### Reference

[AuthorizeTokenizedCardPaymentServiceRequest Class](authorizetokenizedcardpaymentservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

