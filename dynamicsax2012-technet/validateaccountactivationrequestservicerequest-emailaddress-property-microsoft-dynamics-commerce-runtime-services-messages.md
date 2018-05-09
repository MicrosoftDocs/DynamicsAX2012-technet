---
title: ValidateAccountActivationRequestServiceRequest.EmailAddress Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: EmailAddress Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateAccountActivationRequestServiceRequest.EmailAddress
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.validateaccountactivationrequestservicerequest.emailaddress(v=AX.60)
ms:contentKeyID: 62212204
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ValidateAccountActivationRequestServiceRequest.EmailAddress
dev_langs:
- CSharp
- C++
- VB
---

# EmailAddress Property

Gets the email address.

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
Dim instance As ValidateAccountActivationRequestServiceRequest
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

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ValidateAccountActivationRequestServiceRequest Class](validateaccountactivationrequestservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

