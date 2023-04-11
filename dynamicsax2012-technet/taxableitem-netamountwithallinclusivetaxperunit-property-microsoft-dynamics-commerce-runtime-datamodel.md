---
title: TaxableItem.NetAmountWithAllInclusiveTaxPerUnit Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: NetAmountWithAllInclusiveTaxPerUnit Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxableItem.NetAmountWithAllInclusiveTaxPerUnit
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.taxableitem.netamountwithallinclusivetaxperunit(v=AX.60)
ms:contentKeyID: 49829707
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxableItem.NetAmountWithAllInclusiveTaxPerUnit
dev_langs:
- CSharp
- C++
- VB
---

# NetAmountWithAllInclusiveTaxPerUnit Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the net amount with all inclusive taxes (even non-exempt) per unit.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property NetAmountWithAllInclusiveTaxPerUnit As Decimal
    Get
'Usage
Dim instance As TaxableItem
Dim value As Decimal

value = instance.NetAmountWithAllInclusiveTaxPerUnit
```

``` csharp
public decimal NetAmountWithAllInclusiveTaxPerUnit { get; }
```

``` c++
public:
property Decimal NetAmountWithAllInclusiveTaxPerUnit {
    Decimal get ();
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[TaxableItem Class](taxableitem-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

