---
title: SalesLineShippingRate Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SalesLineShippingRate Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLineShippingRate.#ctor(System.String,System.Decimal,System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.saleslineshippingrate.saleslineshippingrate(v=AX.60)
ms:contentKeyID: 49849077
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLineShippingRate.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# SalesLineShippingRate Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [SalesLineShippingRate](saleslineshippingrate-class-microsoft-dynamics-commerce-runtime-datamodel.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    salesLineId As String, _
    shippingCharge As Decimal, _
    netWeight As Decimal _
)
'Usage
Dim salesLineId As String
Dim shippingCharge As Decimal
Dim netWeight As Decimal

Dim instance As New SalesLineShippingRate(salesLineId, _
    shippingCharge, netWeight)
```

``` csharp
public SalesLineShippingRate(
    string salesLineId,
    decimal shippingCharge,
    decimal netWeight
)
```

``` c++
public:
SalesLineShippingRate(
    String^ salesLineId, 
    Decimal shippingCharge, 
    Decimal netWeight
)
```

#### Parameters

  - salesLineId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - shippingCharge  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - netWeight  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[SalesLineShippingRate Class](saleslineshippingrate-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

