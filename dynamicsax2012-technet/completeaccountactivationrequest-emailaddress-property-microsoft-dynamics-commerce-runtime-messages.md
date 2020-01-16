---
title: CompleteAccountActivationRequest.EmailAddress Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: EmailAddress Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.CompleteAccountActivationRequest.EmailAddress
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.completeaccountactivationrequest.emailaddress(v=AX.60)
ms:contentKeyID: 62214316
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.CompleteAccountActivationRequest.EmailAddress
dev_langs:
- CSharp
- C++
- VB
---

# EmailAddress Property

Gets or sets the customer email address.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property EmailAddress As String
    Get
    Set
'Usage
Dim instance As CompleteAccountActivationRequest
Dim value As String

value = instance.EmailAddress

instance.EmailAddress = value
```

``` csharp
[DataMemberAttribute]
public string EmailAddress { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ EmailAddress {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The customer's email address.  

## See Also

#### Reference

[CompleteAccountActivationRequest Class](completeaccountactivationrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

