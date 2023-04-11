---
title: GetQuantityDiscountDataServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetQuantityDiscountDataServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetQuantityDiscountDataServiceRequest.#ctor(System.String,System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getquantitydiscountdataservicerequest.getquantitydiscountdataservicerequest(v=AX.60)
ms:contentKeyID: 65322743
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetQuantityDiscountDataServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetQuantityDiscountDataServiceRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetQuantityDiscountDataServiceRequest](getquantitydiscountdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    offerId As String, _
    quantity As Decimal _
)
'Usage
Dim offerId As String
Dim quantity As Decimal

Dim instance As New GetQuantityDiscountDataServiceRequest(offerId, _
    quantity)
```

``` csharp
public GetQuantityDiscountDataServiceRequest(
    string offerId,
    decimal quantity
)
```

``` c++
public:
GetQuantityDiscountDataServiceRequest(
    String^ offerId, 
    Decimal quantity
)
```

#### Parameters

  - offerId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - quantity  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[GetQuantityDiscountDataServiceRequest Class](getquantitydiscountdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

