---
title: GetPricesServiceRequest.ActiveDate Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ActiveDate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetPricesServiceRequest.ActiveDate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getpricesservicerequest.activedate(v=AX.60)
ms:contentKeyID: 62213707
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetPricesServiceRequest.ActiveDate
dev_langs:
- CSharp
- C++
- VB
---

# ActiveDate Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the active date for the price calculation.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<RequiredAttribute> _
Public Property ActiveDate As DateTimeOffset
    Get
    Private Set
'Usage
Dim instance As GetPricesServiceRequest
Dim value As DateTimeOffset

value = instance.ActiveDate
```

``` csharp
[DataMemberAttribute]
[RequiredAttribute]
public DateTimeOffset ActiveDate { get; private set; }
```

``` c++
[DataMemberAttribute]
[RequiredAttribute]
public:
property DateTimeOffset ActiveDate {
    DateTimeOffset get ();
    private: void set (DateTimeOffset value);
}
```

#### Property Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  
Returns [DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\)).  

## See Also

#### Reference

[GetPricesServiceRequest Class](getpricesservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

