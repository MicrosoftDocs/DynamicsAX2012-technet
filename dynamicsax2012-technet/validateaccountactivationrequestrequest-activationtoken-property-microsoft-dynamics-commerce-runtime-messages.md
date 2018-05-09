---
title: ValidateAccountActivationRequestRequest.ActivationToken Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ActivationToken Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.ValidateAccountActivationRequestRequest.ActivationToken
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.validateaccountactivationrequestrequest.activationtoken(v=AX.60)
ms:contentKeyID: 62214593
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.ValidateAccountActivationRequestRequest.ActivationToken
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
Dim instance As ValidateAccountActivationRequestRequest
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

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The account activation token.  

## See Also

#### Reference

[ValidateAccountActivationRequestRequest Class](validateaccountactivationrequestrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

