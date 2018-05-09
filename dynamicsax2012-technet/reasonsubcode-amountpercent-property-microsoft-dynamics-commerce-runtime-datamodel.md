---
title: ReasonSubCode.AmountPercent Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AmountPercent Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonSubCode.AmountPercent
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.reasonsubcode.amountpercent(v=AX.60)
ms:contentKeyID: 62201853
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonSubCode.AmountPercent
dev_langs:
- CSharp
- C++
- VB
---

# AmountPercent Property

Gets the amount percent.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("AMOUNTPERCENT")> _
<DataMemberAttribute> _
Public Property AmountPercent As Decimal
    Get
    Friend Set
'Usage
Dim instance As ReasonSubCode
Dim value As Decimal

value = instance.AmountPercent
```

``` csharp
[ColumnAttribute("AMOUNTPERCENT")]
[DataMemberAttribute]
public decimal AmountPercent { get; internal set; }
```

``` c++
[ColumnAttribute(L"AMOUNTPERCENT")]
[DataMemberAttribute]
public:
property Decimal AmountPercent {
    Decimal get ();
    internal: void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
The amount percent.  

## See Also

#### Reference

[ReasonSubCode Class](reasonsubcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

