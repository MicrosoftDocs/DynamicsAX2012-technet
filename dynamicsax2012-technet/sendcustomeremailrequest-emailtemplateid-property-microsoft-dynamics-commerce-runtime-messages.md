---
title: SendCustomerEmailRequest.EmailTemplateId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: EmailTemplateId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.SendCustomerEmailRequest.EmailTemplateId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.sendcustomeremailrequest.emailtemplateid(v=AX.60)
ms:contentKeyID: 49840737
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.SendCustomerEmailRequest.EmailTemplateId
dev_langs:
- CSharp
- C++
- VB
---

# EmailTemplateId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the e-mail template identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property EmailTemplateId As String
    Get
    Set
'Usage
Dim instance As SendCustomerEmailRequest
Dim value As String

value = instance.EmailTemplateId

instance.EmailTemplateId = value
```

``` csharp
[DataMemberAttribute]
public string EmailTemplateId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ EmailTemplateId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The e-mail template identifier.  

## See Also

#### Reference

[SendCustomerEmailRequest Class](sendcustomeremailrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

