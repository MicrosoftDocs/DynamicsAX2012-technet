---
title: CompleteAccountActivationRequest.ActivationToken Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ActivationToken Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.CompleteAccountActivationRequest.ActivationToken
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.completeaccountactivationrequest.activationtoken(v=AX.60)
ms:contentKeyID: 62212773
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.CompleteAccountActivationRequest.ActivationToken
dev_langs:
- CSharp
- C++
- VB
---

# ActivationToken Property

Gets or sets the activation token.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ActivationToken As String
    Get
    Set
'Usage
Dim instance As CompleteAccountActivationRequest
Dim value As String

value = instance.ActivationToken

instance.ActivationToken = value
```

``` csharp
[DataMemberAttribute]
public string ActivationToken { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ActivationToken {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The account activation token.  

## See Also

#### Reference

[CompleteAccountActivationRequest Class](completeaccountactivationrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

