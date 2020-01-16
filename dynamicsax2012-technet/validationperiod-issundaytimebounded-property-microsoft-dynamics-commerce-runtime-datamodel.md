---
title: ValidationPeriod.IsSundayTimeBounded Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsSundayTimeBounded Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.IsSundayTimeBounded
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.validationperiod.issundaytimebounded(v=AX.60)
ms:contentKeyID: 49848633
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.IsSundayTimeBounded
dev_langs:
- CSharp
- C++
- VB
---

# IsSundayTimeBounded Property

Gets whether valid time is inside or outside specified bounds for Sundays in this period.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("SUNDAYTIMEWITHINBOUNDS")> _
Public Property IsSundayTimeBounded As Integer
    Get
    Friend Set
'Usage
Dim instance As ValidationPeriod
Dim value As Integer

value = instance.IsSundayTimeBounded
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("SUNDAYTIMEWITHINBOUNDS")]
public int IsSundayTimeBounded { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"SUNDAYTIMEWITHINBOUNDS")]
public:
property int IsSundayTimeBounded {
    int get ();
    internal: void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[ValidationPeriod Class](validationperiod-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

