---
title: CartLine.TaxRatePercent Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxRatePercent Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine.TaxRatePercent
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cartline.taxratepercent(v=AX.60)
ms:contentKeyID: 62207783
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLine.TaxRatePercent
dev_langs:
- CSharp
- C++
- VB
---

# TaxRatePercent Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the tax rate percentage.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TaxRatePercent As Decimal
    Get
    Set
'Usage
Dim instance As CartLine
Dim value As Decimal

value = instance.TaxRatePercent

instance.TaxRatePercent = value
```

``` csharp
[DataMemberAttribute]
public decimal TaxRatePercent { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal TaxRatePercent {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The tax rate percentage.  

## See Also

#### Reference

[CartLine Class](cartline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

