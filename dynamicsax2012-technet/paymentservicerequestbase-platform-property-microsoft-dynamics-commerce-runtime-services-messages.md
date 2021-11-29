---
title: PaymentServiceRequestBase.Platform Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: Platform Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.PaymentServiceRequestBase.Platform
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.paymentservicerequestbase.platform(v=AX.60)
ms:contentKeyID: 65318907
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.PaymentServiceRequestBase.Platform
dev_langs:
- CSharp
- C++
- VB
---

# Platform Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Platform As String
    Get
    Set
'Usage
Dim instance As PaymentServiceRequestBase
Dim value As String

value = instance.Platform

instance.Platform = value
```

``` csharp
[DataMemberAttribute]
public string Platform { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Platform {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[PaymentServiceRequestBase Class](paymentservicerequestbase-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

