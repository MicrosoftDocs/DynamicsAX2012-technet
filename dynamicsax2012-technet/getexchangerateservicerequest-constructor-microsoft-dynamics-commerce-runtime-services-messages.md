---
title: GetExchangeRateServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetExchangeRateServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetExchangeRateServiceRequest.#ctor(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getexchangerateservicerequest.getexchangerateservicerequest(v=AX.60)
ms:contentKeyID: 65322602
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetExchangeRateServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetExchangeRateServiceRequest Constructor

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    fromCurrencyCode As String, _
    toCurrencyCode As String _
)
'Usage
Dim fromCurrencyCode As String
Dim toCurrencyCode As String

Dim instance As New GetExchangeRateServiceRequest(fromCurrencyCode, _
    toCurrencyCode)
```

``` csharp
public GetExchangeRateServiceRequest(
    string fromCurrencyCode,
    string toCurrencyCode
)
```

``` c++
public:
GetExchangeRateServiceRequest(
    String^ fromCurrencyCode, 
    String^ toCurrencyCode
)
```

#### Parameters

  - fromCurrencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - toCurrencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[GetExchangeRateServiceRequest Class](getexchangerateservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

