---
title: ValidateAccountActivationDataRequest.ActivationToken Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: ActivationToken Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ValidateAccountActivationDataRequest.ActivationToken
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.validateaccountactivationdatarequest.activationtoken(v=AX.60)
ms:contentKeyID: 65315888
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ValidateAccountActivationDataRequest.ActivationToken
dev_langs:
- CSharp
- C++
- VB
---

# ActivationToken Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the activation token.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ActivationToken As String
    Get
    Private Set
'Usage
Dim instance As ValidateAccountActivationDataRequest
Dim value As String

value = instance.ActivationToken
```

``` csharp
[DataMemberAttribute]
public string ActivationToken { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ActivationToken {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The activation token.  

## See Also

#### Reference

[ValidateAccountActivationDataRequest Class](validateaccountactivationdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

