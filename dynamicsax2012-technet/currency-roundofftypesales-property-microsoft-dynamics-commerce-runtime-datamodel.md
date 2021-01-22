---
title: Currency.RoundOffTypeSales Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RoundOffTypeSales Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Currency.RoundOffTypeSales
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.currency.roundofftypesales(v=AX.60)
ms:contentKeyID: 62208199
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Currency.RoundOffTypeSales
dev_langs:
- CSharp
- C++
- VB
---

# RoundOffTypeSales Property

Gets or sets the round off type sales.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ROUNDOFFTYPESALES")> _
<DataMemberAttribute> _
Public Property RoundOffTypeSales As Integer
    Get
    Set
'Usage
Dim instance As Currency
Dim value As Integer

value = instance.RoundOffTypeSales

instance.RoundOffTypeSales = value
```

``` csharp
[ColumnAttribute("ROUNDOFFTYPESALES")]
[DataMemberAttribute]
public int RoundOffTypeSales { get; set; }
```

``` c++
[ColumnAttribute(L"ROUNDOFFTYPESALES")]
[DataMemberAttribute]
public:
property int RoundOffTypeSales {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[Currency Class](currency-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

