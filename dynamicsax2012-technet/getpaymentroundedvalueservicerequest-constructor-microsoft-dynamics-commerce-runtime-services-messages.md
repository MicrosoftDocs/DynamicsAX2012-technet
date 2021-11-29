---
title: GetPaymentRoundedValueServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetPaymentRoundedValueServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetPaymentRoundedValueServiceRequest.#ctor(System.Decimal,System.String,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getpaymentroundedvalueservicerequest.getpaymentroundedvalueservicerequest(v=AX.60)
ms:contentKeyID: 65319708
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetPaymentRoundedValueServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetPaymentRoundedValueServiceRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    value As Decimal, _
    tenderTypeId As String, _
    isChange As Boolean _
)
'Usage
Dim value As Decimal
Dim tenderTypeId As String
Dim isChange As Boolean

Dim instance As New GetPaymentRoundedValueServiceRequest(value, tenderTypeId, _
    isChange)
```

``` csharp
public GetPaymentRoundedValueServiceRequest(
    decimal value,
    string tenderTypeId,
    bool isChange
)
```

``` c++
public:
GetPaymentRoundedValueServiceRequest(
    Decimal value, 
    String^ tenderTypeId, 
    bool isChange
)
```

#### Parameters

  - value  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - tenderTypeId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - isChange  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[GetPaymentRoundedValueServiceRequest Class](getpaymentroundedvalueservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

