---
title: UnitOfMeasureConversion.Denominator Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Denominator Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.UnitOfMeasureConversion.Denominator
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.unitofmeasureconversion.denominator(v=AX.60)
ms:contentKeyID: 49844908
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.UnitOfMeasureConversion.Denominator
dev_langs:
- CSharp
- C++
- VB
---

# Denominator Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the this.Denominator.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DENOMINATOR")> _
<ReadOnlyAttribute("DENOMINATOR")> _
<DataMemberAttribute> _
Public Property Denominator As Integer
    Get
    Set
'Usage
Dim instance As UnitOfMeasureConversion
Dim value As Integer

value = instance.Denominator

instance.Denominator = value
```

``` csharp
[ColumnAttribute("DENOMINATOR")]
[ReadOnlyAttribute("DENOMINATOR")]
[DataMemberAttribute]
public int Denominator { get; set; }
```

``` c++
[ColumnAttribute(L"DENOMINATOR")]
[ReadOnlyAttribute(L"DENOMINATOR")]
[DataMemberAttribute]
public:
property int Denominator {
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

