---
title: SendEmailServiceRequest.Language Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: Language Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SendEmailServiceRequest.Language
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.sendemailservicerequest.language(v=AX.60)
ms:contentKeyID: 49840721
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SendEmailServiceRequest.Language
dev_langs:
- CSharp
- C++
- VB
---

# Language Property

Gets the language to send the e-mail.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Language As String
    Get
    Private Set
'Usage
Dim instance As SendEmailServiceRequest
Dim value As String

value = instance.Language
```

``` csharp
[DataMemberAttribute]
public string Language { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Language {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[SendEmailServiceRequest Class](sendemailservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

