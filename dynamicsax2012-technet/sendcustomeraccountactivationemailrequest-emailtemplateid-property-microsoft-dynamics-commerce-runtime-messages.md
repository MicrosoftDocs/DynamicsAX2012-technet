---
title: SendCustomerAccountActivationEmailRequest.EmailTemplateId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: EmailTemplateId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.SendCustomerAccountActivationEmailRequest.EmailTemplateId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.sendcustomeraccountactivationemailrequest.emailtemplateid(v=AX.60)
ms:contentKeyID: 62215012
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.SendCustomerAccountActivationEmailRequest.EmailTemplateId
dev_langs:
- CSharp
- C++
- VB
---

# EmailTemplateId Property

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
Dim instance As SendCustomerAccountActivationEmailRequest
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

[SendCustomerAccountActivationEmailRequest Class](sendcustomeraccountactivationemailrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

