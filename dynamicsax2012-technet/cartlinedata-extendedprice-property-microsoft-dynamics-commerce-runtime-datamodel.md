---
title: CartLineData.ExtendedPrice Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ExtendedPrice Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.ExtendedPrice
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cartlinedata.extendedprice(v=AX.60)
ms:contentKeyID: 62210614
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.ExtendedPrice
dev_langs:
- CSharp
- C++
- VB
---

# ExtendedPrice Property

Gets the extended price. The extended price is the net amount for the line (which includes the discounts) and optionally the tax amount if tax inclusive.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("NETAMOUNT")> _
<DataMemberAttribute> _
Public Property ExtendedPrice As Decimal
    Get
    Friend Set
'Usage
Dim instance As CartLineData
Dim value As Decimal

value = instance.ExtendedPrice
```

``` csharp
[ColumnAttribute("NETAMOUNT")]
[DataMemberAttribute]
public decimal ExtendedPrice { get; internal set; }
```

``` c++
[ColumnAttribute(L"NETAMOUNT")]
[DataMemberAttribute]
public:
property Decimal ExtendedPrice {
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

