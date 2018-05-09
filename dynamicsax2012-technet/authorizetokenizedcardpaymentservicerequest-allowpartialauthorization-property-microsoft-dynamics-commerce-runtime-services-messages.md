---
title: AuthorizeTokenizedCardPaymentServiceRequest.AllowPartialAuthorization Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: AllowPartialAuthorization Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AuthorizeTokenizedCardPaymentServiceRequest.AllowPartialAuthorization
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.authorizetokenizedcardpaymentservicerequest.allowpartialauthorization(v=AX.60)
ms:contentKeyID: 65319808
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.AuthorizeTokenizedCardPaymentServiceRequest.AllowPartialAuthorization
dev_langs:
- CSharp
- C++
- VB
---

# AllowPartialAuthorization Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property AllowPartialAuthorization As Boolean
    Get
    Private Set
'Usage
Dim instance As AuthorizeTokenizedCardPaymentServiceRequest
Dim value As Boolean

value = instance.AllowPartialAuthorization
```

``` csharp
[DataMemberAttribute]
public bool AllowPartialAuthorization { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property bool AllowPartialAuthorization {
    bool get ();
    private: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[AuthorizeTokenizedCardPaymentServiceRequest Class](authorizetokenizedcardpaymentservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

