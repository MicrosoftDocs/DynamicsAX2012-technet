---
title: GetPriceAndDiscountDataServiceRequest.MaxActiveDate Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: MaxActiveDate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPriceAndDiscountDataServiceRequest.MaxActiveDate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getpriceanddiscountdataservicerequest.maxactivedate(v=AX.60)
ms:contentKeyID: 65319325
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPriceAndDiscountDataServiceRequest.MaxActiveDate
dev_langs:
- CSharp
- C++
- VB
---

# MaxActiveDate Property

Gets or sets the maximum active date.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property MaxActiveDate As DateTimeOffset
    Get
    Protected Set
'Usage
Dim instance As GetPriceAndDiscountDataServiceRequest
Dim value As DateTimeOffset

value = instance.MaxActiveDate

instance.MaxActiveDate = value
```

``` csharp
[DataMemberAttribute]
public DateTimeOffset MaxActiveDate { get; protected set; }
```

``` c++
[DataMemberAttribute]
public:
property DateTimeOffset MaxActiveDate {
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

