---
title: GetCurrencyValueServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetCurrencyValueServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCurrencyValueServiceRequest.#ctor(System.String,System.String,System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getcurrencyvalueservicerequest.getcurrencyvalueservicerequest(v=AX.60)
ms:contentKeyID: 65319531
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetCurrencyValueServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetCurrencyValueServiceRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    fromCurrencyCode As String, _
    toCurrencyCode As String, _
    amountToConvert As Decimal _
)
'Usage
Dim fromCurrencyCode As String
Dim toCurrencyCode As String
Dim amountToConvert As Decimal

Dim instance As New GetCurrencyValueServiceRequest(fromCurrencyCode, _
    toCurrencyCode, amountToConvert)
```

``` csharp
public GetCurrencyValueServiceRequest(
    string fromCurrencyCode,
    string toCurrencyCode,
    decimal amountToConvert
)
```

``` c++
public:
GetCurrencyValueServiceRequest(
    String^ fromCurrencyCode, 
    String^ toCurrencyCode, 
    Decimal amountToConvert
)
```

#### Parameters

  - fromCurrencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - toCurrencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - amountToConvert  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[GetCurrencyValueServiceRequest Class](getcurrencyvalueservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

