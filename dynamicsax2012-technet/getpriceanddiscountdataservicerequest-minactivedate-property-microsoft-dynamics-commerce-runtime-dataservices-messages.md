---
title: GetPriceAndDiscountDataServiceRequest.MinActiveDate Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: MinActiveDate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPriceAndDiscountDataServiceRequest.MinActiveDate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getpriceanddiscountdataservicerequest.minactivedate(v=AX.60)
ms:contentKeyID: 65317251
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPriceAndDiscountDataServiceRequest.MinActiveDate
dev_langs:
- CSharp
- C++
- VB
---

# MinActiveDate Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the minimum active date.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property MinActiveDate As DateTimeOffset
    Get
    Protected Set
'Usage
Dim instance As GetPriceAndDiscountDataServiceRequest
Dim value As DateTimeOffset

value = instance.MinActiveDate

instance.MinActiveDate = value
```

``` csharp
[DataMemberAttribute]
public DateTimeOffset MinActiveDate { get; protected set; }
```

``` c++
[DataMemberAttribute]
public:
property DateTimeOffset MinActiveDate {
    DateTimeOffset get ();
    protected: void set (DateTimeOffset value);
}
```

#### Property Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  
Returns [DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\)).  

## See Also

#### Reference

[GetPriceAndDiscountDataServiceRequest Class](getpriceanddiscountdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

