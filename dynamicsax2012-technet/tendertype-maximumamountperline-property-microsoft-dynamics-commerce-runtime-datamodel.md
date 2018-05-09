---
title: TenderType.MaximumAmountPerLine Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MaximumAmountPerLine Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderType.MaximumAmountPerLine
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.tendertype.maximumamountperline(v=AX.60)
ms:contentKeyID: 62212437
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderType.MaximumAmountPerLine
dev_langs:
- CSharp
- C++
- VB
---

# MaximumAmountPerLine Property

Gets or sets the maximum amount per line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("MAXIMUMAMOUNTPERLINE")> _
<DataMemberAttribute> _
Public Property MaximumAmountPerLine As Decimal
    Get
    Set
'Usage
Dim instance As TenderType
Dim value As Decimal

value = instance.MaximumAmountPerLine

instance.MaximumAmountPerLine = value
```

``` csharp
[ColumnAttribute("MAXIMUMAMOUNTPERLINE")]
[DataMemberAttribute]
public decimal MaximumAmountPerLine { get; set; }
```

``` c++
[ColumnAttribute(L"MAXIMUMAMOUNTPERLINE")]
[DataMemberAttribute]
public:
property Decimal MaximumAmountPerLine {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[TenderType Class](tendertype-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

