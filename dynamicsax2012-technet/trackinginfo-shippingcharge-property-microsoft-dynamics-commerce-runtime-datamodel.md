---
title: TrackingInfo.ShippingCharge Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ShippingCharge Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TrackingInfo.ShippingCharge
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.trackinginfo.shippingcharge(v=AX.60)
ms:contentKeyID: 49834823
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TrackingInfo.ShippingCharge
dev_langs:
- CSharp
- C++
- VB
---

# ShippingCharge Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets charge of the shipping.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ShippingCharge As Decimal
    Get
    Set
'Usage
Dim instance As TrackingInfo
Dim value As Decimal

value = instance.ShippingCharge

instance.ShippingCharge = value
```

``` csharp
[DataMemberAttribute]
public decimal ShippingCharge { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal ShippingCharge {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[TrackingInfo Class](trackinginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

