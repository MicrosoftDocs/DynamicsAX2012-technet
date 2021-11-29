---
title: UnitOfMeasure.DecimalPrecision Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DecimalPrecision Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.UnitOfMeasure.DecimalPrecision
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.unitofmeasure.decimalprecision(v=AX.60)
ms:contentKeyID: 49837447
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.UnitOfMeasure.DecimalPrecision
dev_langs:
- CSharp
- C++
- VB
---

# DecimalPrecision Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the number of decimal places used by the unit of measure.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("DECIMALPRECISION")> _
Public Property DecimalPrecision As Integer
    Get
    Set
'Usage
Dim instance As UnitOfMeasure
Dim value As Integer

value = instance.DecimalPrecision

instance.DecimalPrecision = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("DECIMALPRECISION")]
public int DecimalPrecision { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"DECIMALPRECISION")]
public:
property int DecimalPrecision {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[UnitOfMeasure Class](unitofmeasure-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

