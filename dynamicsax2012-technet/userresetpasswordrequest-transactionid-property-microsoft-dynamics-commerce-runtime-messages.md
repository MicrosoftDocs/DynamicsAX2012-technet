---
title: UserResetPasswordRequest.TransactionId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: TransactionId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.UserResetPasswordRequest.TransactionId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.userresetpasswordrequest.transactionid(v=AX.60)
ms:contentKeyID: 65320228
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.UserResetPasswordRequest.TransactionId
dev_langs:
- CSharp
- C++
- VB
---

# TransactionId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TransactionId As String
    Get
    Set
'Usage
Dim instance As UserResetPasswordRequest
Dim value As String

value = instance.TransactionId

instance.TransactionId = value
```

``` csharp
[DataMemberAttribute]
public string TransactionId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ TransactionId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[UserResetPasswordRequest Class](userresetpasswordrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

