---
title: UnitOfMeasureConversion.Numerator Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Numerator Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.UnitOfMeasureConversion.Numerator
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.unitofmeasureconversion.numerator(v=AX.60)
ms:contentKeyID: 49848194
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.UnitOfMeasureConversion.Numerator
dev_langs:
- CSharp
- C++
- VB
---

# Numerator Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the this.Numerator.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ReadOnlyAttribute("NUMERATOR")> _
<ColumnAttribute("NUMERATOR")> _
<DataMemberAttribute> _
Public Property Numerator As Integer
    Get
    Set
'Usage
Dim instance As UnitOfMeasureConversion
Dim value As Integer

value = instance.Numerator

instance.Numerator = value
```

``` csharp
[ReadOnlyAttribute("NUMERATOR")]
[ColumnAttribute("NUMERATOR")]
[DataMemberAttribute]
public int Numerator { get; set; }
```

``` c++
[ReadOnlyAttribute(L"NUMERATOR")]
[ColumnAttribute(L"NUMERATOR")]
[DataMemberAttribute]
public:
property int Numerator {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[UnitOfMeasureConversion Class](unitofmeasureconversion-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

