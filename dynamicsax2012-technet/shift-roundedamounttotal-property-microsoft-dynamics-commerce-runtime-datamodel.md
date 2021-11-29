---
title: Shift.RoundedAmountTotal Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RoundedAmountTotal Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.RoundedAmountTotal
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shift.roundedamounttotal(v=AX.60)
ms:contentKeyID: 62209007
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.RoundedAmountTotal
dev_langs:
- CSharp
- C++
- VB
---

# RoundedAmountTotal Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets total of rounded amount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ROUNDEDAMOUNTTOTAL")> _
<DataMemberAttribute> _
Public Property RoundedAmountTotal As Decimal
    Get
    Set
'Usage
Dim instance As Shift
Dim value As Decimal

value = instance.RoundedAmountTotal

instance.RoundedAmountTotal = value
```

``` csharp
[ColumnAttribute("ROUNDEDAMOUNTTOTAL")]
[DataMemberAttribute]
public decimal RoundedAmountTotal { get; set; }
```

``` c++
[ColumnAttribute(L"ROUNDEDAMOUNTTOTAL")]
[DataMemberAttribute]
public:
property Decimal RoundedAmountTotal {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[Shift Class](shift-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

