---
title: SalesLineShippingRate.NetWeight Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: NetWeight Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLineShippingRate.NetWeight
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.saleslineshippingrate.netweight(v=AX.60)
ms:contentKeyID: 49852838
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLineShippingRate.NetWeight
dev_langs:
- CSharp
- C++
- VB
---

# NetWeight Property

Gets the combined weight of all the items on the sales line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Property NetWeight As Decimal
    Get
    Private Set
'Usage
Dim instance As SalesLineShippingRate
Dim value As Decimal

value = instance.NetWeight
```

``` csharp
public decimal NetWeight { get; private set; }
```

``` c++
public:
property Decimal NetWeight {
    Decimal get ();
    private: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[SalesLineShippingRate Class](saleslineshippingrate-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

