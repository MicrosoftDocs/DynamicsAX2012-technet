---
title: CartLineData.LineManualDiscountPercentage Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LineManualDiscountPercentage Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.LineManualDiscountPercentage
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cartlinedata.linemanualdiscountpercentage(v=AX.60)
ms:contentKeyID: 62211796
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.LineManualDiscountPercentage
dev_langs:
- CSharp
- C++
- VB
---

# LineManualDiscountPercentage Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the manual line percent off value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("LINEMANUALDISCOUNTPERCENTAGE")> _
Public Property LineManualDiscountPercentage As Decimal
    Get
    Friend Set
'Usage
Dim instance As CartLineData
Dim value As Decimal

value = instance.LineManualDiscountPercentage
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("LINEMANUALDISCOUNTPERCENTAGE")]
public decimal LineManualDiscountPercentage { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"LINEMANUALDISCOUNTPERCENTAGE")]
public:
property Decimal LineManualDiscountPercentage {
    Decimal get ();
    internal: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[CartLineData Class](cartlinedata-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

