---
title: SalesLineShippingRate.ShippingCharge Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ShippingCharge Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLineShippingRate.ShippingCharge
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.saleslineshippingrate.shippingcharge(v=AX.60)
ms:contentKeyID: 49827801
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLineShippingRate.ShippingCharge
dev_langs:
- CSharp
- C++
- VB
---

# ShippingCharge Property

Gets or sets the shipping charge.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Property ShippingCharge As Decimal
    Get
    Set
'Usage
Dim instance As SalesLineShippingRate
Dim value As Decimal

value = instance.ShippingCharge

instance.ShippingCharge = value
```

``` csharp
public decimal ShippingCharge { get; set; }
```

``` c++
public:
property Decimal ShippingCharge {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[SalesLineShippingRate Class](saleslineshippingrate-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

