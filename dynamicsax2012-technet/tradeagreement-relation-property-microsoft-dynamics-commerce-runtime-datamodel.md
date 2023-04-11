---
title: TradeAgreement.Relation Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Relation Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TradeAgreement.Relation
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tradeagreement.relation(v=AX.60)
ms:contentKeyID: 49833880
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TradeAgreement.Relation
dev_langs:
- CSharp
- C++
- VB
---

# Relation Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the type of this trade agreement rule (price, line discount, etc).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("RELATION")> _
Public Property Relation As PriceDiscountType
    Get
    Friend Set
'Usage
Dim instance As TradeAgreement
Dim value As PriceDiscountType

value = instance.Relation
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("RELATION")]
public PriceDiscountType Relation { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"RELATION")]
public:
property PriceDiscountType Relation {
    PriceDiscountType get ();
    internal: void set (PriceDiscountType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceDiscountType](pricediscounttype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [PriceDiscountType](pricediscounttype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[TradeAgreement Class](tradeagreement-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

