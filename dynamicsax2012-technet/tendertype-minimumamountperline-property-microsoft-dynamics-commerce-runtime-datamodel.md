---
title: TenderType.MinimumAmountPerLine Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MinimumAmountPerLine Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderType.MinimumAmountPerLine
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.tendertype.minimumamountperline(v=AX.60)
ms:contentKeyID: 62207283
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderType.MinimumAmountPerLine
dev_langs:
- CSharp
- C++
- VB
---

# MinimumAmountPerLine Property

Gets or sets the minimum amount per line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("MINIMUMAMOUNTPERLINE")> _
Public Property MinimumAmountPerLine As Decimal
    Get
    Set
'Usage
Dim instance As TenderType
Dim value As Decimal

value = instance.MinimumAmountPerLine

instance.MinimumAmountPerLine = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("MINIMUMAMOUNTPERLINE")]
public decimal MinimumAmountPerLine { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"MINIMUMAMOUNTPERLINE")]
public:
property Decimal MinimumAmountPerLine {
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

