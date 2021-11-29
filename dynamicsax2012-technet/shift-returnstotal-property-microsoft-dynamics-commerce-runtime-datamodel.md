---
title: Shift.ReturnsTotal Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReturnsTotal Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.ReturnsTotal
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shift.returnstotal(v=AX.60)
ms:contentKeyID: 62211125
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift.ReturnsTotal
dev_langs:
- CSharp
- C++
- VB
---

# ReturnsTotal Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets total of returns.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("RETURNSTOTAL")> _
<DataMemberAttribute> _
Public Property ReturnsTotal As Decimal
    Get
    Set
'Usage
Dim instance As Shift
Dim value As Decimal

value = instance.ReturnsTotal

instance.ReturnsTotal = value
```

``` csharp
[ColumnAttribute("RETURNSTOTAL")]
[DataMemberAttribute]
public decimal ReturnsTotal { get; set; }
```

``` c++
[ColumnAttribute(L"RETURNSTOTAL")]
[DataMemberAttribute]
public:
property Decimal ReturnsTotal {
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

