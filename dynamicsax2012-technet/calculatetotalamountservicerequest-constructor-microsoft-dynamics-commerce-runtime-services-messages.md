---
title: CalculateTotalAmountServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: CalculateTotalAmountServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateTotalAmountServiceRequest.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.CurrencyRequest})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.calculatetotalamountservicerequest.calculatetotalamountservicerequest(v=AX.60)
ms:contentKeyID: 65316249
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateTotalAmountServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# CalculateTotalAmountServiceRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    currenciesToConvert As IEnumerable(Of CurrencyRequest) _
)
'Usage
Dim currenciesToConvert As IEnumerable(Of CurrencyRequest)

Dim instance As New CalculateTotalAmountServiceRequest(currenciesToConvert)
```

``` csharp
public CalculateTotalAmountServiceRequest(
    IEnumerable<CurrencyRequest> currenciesToConvert
)
```

``` c++
public:
CalculateTotalAmountServiceRequest(
    IEnumerable<CurrencyRequest^>^ currenciesToConvert
)
```

#### Parameters

  - currenciesToConvert  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[CurrencyRequest](currencyrequest-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[CalculateTotalAmountServiceRequest Class](calculatetotalamountservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

