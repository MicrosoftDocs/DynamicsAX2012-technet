---
title: PeriodicDiscount.OfferPrice Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OfferPrice Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscount.OfferPrice
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.periodicdiscount.offerprice(v=AX.60)
ms:contentKeyID: 49838614
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PeriodicDiscount.OfferPrice
dev_langs:
- CSharp
- C++
- VB
---

# OfferPrice Property

Gets the final discount price if this is a discount offer rule.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("OFFERPRICE")> _
<DataMemberAttribute> _
Public Property OfferPrice As Decimal
    Get
    Friend Set
'Usage
Dim instance As PeriodicDiscount
Dim value As Decimal

value = instance.OfferPrice
```

``` csharp
[ColumnAttribute("OFFERPRICE")]
[DataMemberAttribute]
public decimal OfferPrice { get; internal set; }
```

``` c++
[ColumnAttribute(L"OFFERPRICE")]
[DataMemberAttribute]
public:
property Decimal OfferPrice {
    Decimal get ();
    internal: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[PeriodicDiscount Class](periodicdiscount-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

