---
title: GetExchangeRatesDataRequest.ActiveDate Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: ActiveDate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetExchangeRatesDataRequest.ActiveDate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getexchangeratesdatarequest.activedate(v=AX.60)
ms:contentKeyID: 65323237
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetExchangeRatesDataRequest.ActiveDate
dev_langs:
- CSharp
- C++
- VB
---

# ActiveDate Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the date for which the exchange rate should be active.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ActiveDate As DateTime
    Get
    Private Set
'Usage
Dim instance As GetExchangeRatesDataRequest
Dim value As DateTime

value = instance.ActiveDate
```

``` csharp
[DataMemberAttribute]
public DateTime ActiveDate { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property DateTime ActiveDate {
    DateTime get ();
    private: void set (DateTime value);
}
```

#### Property Value

Type: [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))  
Returns [DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\)).  

## See Also

#### Reference

[GetExchangeRatesDataRequest Class](getexchangeratesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

