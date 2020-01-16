---
title: PriceLine.Value Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Value Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceLine.Value
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.priceline.value(v=AX.60)
ms:contentKeyID: 62213499
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceLine.Value
dev_langs:
- CSharp
- C++
- VB
---

# Value Property

Gets or sets the value of the line. This value is interpreted based on the PriceMethod.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("VALUE")> _
<DataMemberAttribute> _
Public Property Value As Decimal
    Get
    Set
'Usage
Dim instance As PriceLine
Dim value As Decimal

value = instance.Value

instance.Value = value
```

``` csharp
[ColumnAttribute("VALUE")]
[DataMemberAttribute]
public decimal Value { get; set; }
```

``` c++
[ColumnAttribute(L"VALUE")]
[DataMemberAttribute]
public:
property Decimal Value {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[PriceLine Class](priceline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

