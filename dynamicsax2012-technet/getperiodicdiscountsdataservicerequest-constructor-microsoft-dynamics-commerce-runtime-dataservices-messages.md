---
title: GetPeriodicDiscountsDataServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetPeriodicDiscountsDataServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPeriodicDiscountsDataServiceRequest.#ctor(System.Int64,System.Int64,System.Collections.Generic.IEnumerable{System.Int64},System.String,System.DateTimeOffset)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getperiodicdiscountsdataservicerequest.getperiodicdiscountsdataservicerequest(v=AX.60)
ms:contentKeyID: 65320885
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetPeriodicDiscountsDataServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetPeriodicDiscountsDataServiceRequest Constructor

Initializes a new instance of the [GetPeriodicDiscountsDataServiceRequest](getperiodicdiscountsdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    productId As Long, _
    variantId As Long, _
    priceGroupIds As IEnumerable(Of Long), _
    currencyCode As String, _
    activeDate As DateTimeOffset _
)
'Usage
Dim productId As Long
Dim variantId As Long
Dim priceGroupIds As IEnumerable(Of Long)
Dim currencyCode As String
Dim activeDate As DateTimeOffset

Dim instance As New GetPeriodicDiscountsDataServiceRequest(productId, _
    variantId, priceGroupIds, currencyCode, _
    activeDate)
```

``` csharp
public GetPeriodicDiscountsDataServiceRequest(
    long productId,
    long variantId,
    IEnumerable<long> priceGroupIds,
    string currencyCode,
    DateTimeOffset activeDate
)
```

``` c++
public:
GetPeriodicDiscountsDataServiceRequest(
    long long productId, 
    long long variantId, 
    IEnumerable<long long>^ priceGroupIds, 
    String^ currencyCode, 
    DateTimeOffset activeDate
)
```

#### Parameters

  - productId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - variantId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - priceGroupIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

<!-- end list -->

  - currencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - activeDate  
    Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  

## See Also

#### Reference

[GetPeriodicDiscountsDataServiceRequest Class](getperiodicdiscountsdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

