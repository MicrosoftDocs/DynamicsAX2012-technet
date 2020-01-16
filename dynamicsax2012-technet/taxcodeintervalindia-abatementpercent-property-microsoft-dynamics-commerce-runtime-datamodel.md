---
title: TaxCodeIntervalIndia.AbatementPercent Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AbatementPercent Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxCodeIntervalIndia.AbatementPercent
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.taxcodeintervalindia.abatementpercent(v=AX.60)
ms:contentKeyID: 62204001
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxCodeIntervalIndia.AbatementPercent
dev_langs:
- CSharp
- C++
- VB
---

# AbatementPercent Property

Gets the abatement percent.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ABATEMENTPERCENT_IN")> _
<DataMemberAttribute> _
Public Property AbatementPercent As Decimal
    Get
    Friend Set
'Usage
Dim instance As TaxCodeIntervalIndia
Dim value As Decimal

value = instance.AbatementPercent
```

``` csharp
[ColumnAttribute("ABATEMENTPERCENT_IN")]
[DataMemberAttribute]
public decimal AbatementPercent { get; internal set; }
```

``` c++
[ColumnAttribute(L"ABATEMENTPERCENT_IN")]
[DataMemberAttribute]
public:
property Decimal AbatementPercent {
    Decimal get ();
    internal: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[TaxCodeIntervalIndia Class](taxcodeintervalindia-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

