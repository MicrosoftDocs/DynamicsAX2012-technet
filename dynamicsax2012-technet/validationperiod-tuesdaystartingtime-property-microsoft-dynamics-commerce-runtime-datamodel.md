---
title: ValidationPeriod.TuesdayStartingTime Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TuesdayStartingTime Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.TuesdayStartingTime
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.validationperiod.tuesdaystartingtime(v=AX.60)
ms:contentKeyID: 49845035
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.TuesdayStartingTime
dev_langs:
- CSharp
- C++
- VB
---

# TuesdayStartingTime Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the starting time for Tuesdays in this period.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("THUESDAYSTARTINGTIME")> _
Public Property TuesdayStartingTime As Integer
    Get
    Friend Set
'Usage
Dim instance As ValidationPeriod
Dim value As Integer

value = instance.TuesdayStartingTime
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("THUESDAYSTARTINGTIME")]
public int TuesdayStartingTime { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"THUESDAYSTARTINGTIME")]
public:
property int TuesdayStartingTime {
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

