---
title: TaxCodeInterval.TaxCalculationMethod Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxCalculationMethod Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxCodeInterval.TaxCalculationMethod
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.taxcodeinterval.taxcalculationmethod(v=AX.60)
ms:contentKeyID: 62210144
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxCodeInterval.TaxCalculationMethod
dev_langs:
- CSharp
- C++
- VB
---

# TaxCalculationMethod Property

Gets the tax calculation method.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TAXCALCMETHOD")> _
<DataMemberAttribute> _
Public Property TaxCalculationMethod As Integer
    Get
    Friend Set
'Usage
Dim instance As TaxCodeInterval
Dim value As Integer

value = instance.TaxCalculationMethod
```

``` csharp
[ColumnAttribute("TAXCALCMETHOD")]
[DataMemberAttribute]
public int TaxCalculationMethod { get; internal set; }
```

``` c++
[ColumnAttribute(L"TAXCALCMETHOD")]
[DataMemberAttribute]
public:
property int TaxCalculationMethod {
    int get ();
    internal: void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[TaxCodeInterval Class](taxcodeinterval-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

