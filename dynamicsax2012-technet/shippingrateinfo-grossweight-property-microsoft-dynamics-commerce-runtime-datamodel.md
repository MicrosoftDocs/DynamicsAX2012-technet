---
title: ShippingRateInfo.GrossWeight Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: GrossWeight Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShippingRateInfo.GrossWeight
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shippingrateinfo.grossweight(v=AX.60)
ms:contentKeyID: 49847073
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShippingRateInfo.GrossWeight
dev_langs:
- CSharp
- C++
- VB
---

# GrossWeight Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the gross weight.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property GrossWeight As Decimal
    Get
    Set
'Usage
Dim instance As ShippingRateInfo
Dim value As Decimal

value = instance.GrossWeight

instance.GrossWeight = value
```

``` csharp
[DataMemberAttribute]
public decimal GrossWeight { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal GrossWeight {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The gross weight.  

## See Also

#### Reference

[ShippingRateInfo Class](shippingrateinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

