---
title: CartLineData.LineDiscount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LineDiscount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.LineDiscount
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.cartlinedata.linediscount(v=AX.60)
ms:contentKeyID: 62212303
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.LineDiscount
dev_langs:
- CSharp
- C++
- VB
---

# LineDiscount Property

Gets or sets total line discount given in this transaction(excluding the tax).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("LINEDISCOUNTAMOUNT")> _
Public Property LineDiscount As Decimal
    Get
    Set
'Usage
Dim instance As CartLineData
Dim value As Decimal

value = instance.LineDiscount

instance.LineDiscount = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("LINEDISCOUNTAMOUNT")]
public decimal LineDiscount { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"LINEDISCOUNTAMOUNT")]
public:
property Decimal LineDiscount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[CartLineData Class](cartlinedata-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

