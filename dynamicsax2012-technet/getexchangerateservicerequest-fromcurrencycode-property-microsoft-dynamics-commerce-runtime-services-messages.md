---
title: GetExchangeRateServiceRequest.FromCurrencyCode Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: FromCurrencyCode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetExchangeRateServiceRequest.FromCurrencyCode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getexchangerateservicerequest.fromcurrencycode(v=AX.60)
ms:contentKeyID: 62209015
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetExchangeRateServiceRequest.FromCurrencyCode
dev_langs:
- CSharp
- C++
- VB
---

# FromCurrencyCode Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the currency code which is being converted from.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<RequiredAttribute> _
Public Property FromCurrencyCode As String
    Get
    Private Set
'Usage
Dim instance As GetExchangeRateServiceRequest
Dim value As String

value = instance.FromCurrencyCode
```

``` csharp
[DataMemberAttribute]
[RequiredAttribute]
public string FromCurrencyCode { get; private set; }
```

``` c++
[DataMemberAttribute]
[RequiredAttribute]
public:
property String^ FromCurrencyCode {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetExchangeRateServiceRequest Class](getexchangerateservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

