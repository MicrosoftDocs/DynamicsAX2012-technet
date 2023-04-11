---
title: IssueLoyaltyCardServiceRequest.CustomerAccountNumber Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: CustomerAccountNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.IssueLoyaltyCardServiceRequest.CustomerAccountNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.issueloyaltycardservicerequest.customeraccountnumber(v=AX.60)
ms:contentKeyID: 65316057
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.IssueLoyaltyCardServiceRequest.CustomerAccountNumber
dev_langs:
- CSharp
- C++
- VB
---

# CustomerAccountNumber Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CustomerAccountNumber As String
    Get
    Private Set
'Usage
Dim instance As IssueLoyaltyCardServiceRequest
Dim value As String

value = instance.CustomerAccountNumber
```

``` csharp
[DataMemberAttribute]
public string CustomerAccountNumber { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ CustomerAccountNumber {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[IssueLoyaltyCardServiceRequest Class](issueloyaltycardservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

