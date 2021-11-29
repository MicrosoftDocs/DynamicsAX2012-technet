---
title: GetChannelCurrencyServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetChannelCurrencyServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetChannelCurrencyServiceRequest.#ctor(System.String,System.Decimal,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getchannelcurrencyservicerequest.getchannelcurrencyservicerequest(v=AX.60)
ms:contentKeyID: 65322293
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetChannelCurrencyServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetChannelCurrencyServiceRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    currencyCode As String, _
    amount As Decimal, _
    resultSettings As QueryResultSettings _
)
'Usage
Dim currencyCode As String
Dim amount As Decimal
Dim resultSettings As QueryResultSettings

Dim instance As New GetChannelCurrencyServiceRequest(currencyCode, _
    amount, resultSettings)
```

``` csharp
public GetChannelCurrencyServiceRequest(
    string currencyCode,
    decimal amount,
    QueryResultSettings resultSettings
)
```

``` c++
public:
GetChannelCurrencyServiceRequest(
    String^ currencyCode, 
    Decimal amount, 
    QueryResultSettings^ resultSettings
)
```

#### Parameters

  - currencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - amount  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - resultSettings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetChannelCurrencyServiceRequest Class](getchannelcurrencyservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

