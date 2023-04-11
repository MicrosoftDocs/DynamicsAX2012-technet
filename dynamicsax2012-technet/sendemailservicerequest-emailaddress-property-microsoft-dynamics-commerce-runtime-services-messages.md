---
title: SendEmailServiceRequest.EmailAddress Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: EmailAddress Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SendEmailServiceRequest.EmailAddress
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.sendemailservicerequest.emailaddress(v=AX.60)
ms:contentKeyID: 49846694
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SendEmailServiceRequest.EmailAddress
dev_langs:
- CSharp
- C++
- VB
---

# EmailAddress Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the e-mail address.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property EmailAddress As String
    Get
    Private Set
'Usage
Dim instance As SendEmailServiceRequest
Dim value As String

value = instance.EmailAddress
```

``` csharp
[DataMemberAttribute]
public string EmailAddress { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ EmailAddress {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[SendEmailServiceRequest Class](sendemailservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

