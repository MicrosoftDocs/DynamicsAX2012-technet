---
title: CartLineData.NetAmountWithoutTax Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: NetAmountWithoutTax Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.NetAmountWithoutTax
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cartlinedata.netamountwithouttax(v=AX.60)
ms:contentKeyID: 65320817
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.NetAmountWithoutTax
dev_langs:
- CSharp
- C++
- VB
---

# NetAmountWithoutTax Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("NETAMOUNTWITHOUTTAX")> _
<DataMemberAttribute> _
Public Property NetAmountWithoutTax As Decimal
    Get
    Set
'Usage
Dim instance As CartLineData
Dim value As Decimal

value = instance.NetAmountWithoutTax

instance.NetAmountWithoutTax = value
```

``` csharp
[ColumnAttribute("NETAMOUNTWITHOUTTAX")]
[DataMemberAttribute]
public decimal NetAmountWithoutTax { get; set; }
```

``` c++
[ColumnAttribute(L"NETAMOUNTWITHOUTTAX")]
[DataMemberAttribute]
public:
property Decimal NetAmountWithoutTax {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[CartLineData Class](cartlinedata-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

