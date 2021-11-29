---
title: ValidationPeriod.TuesdayEndingTime Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TuesdayEndingTime Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.TuesdayEndingTime
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.validationperiod.tuesdayendingtime(v=AX.60)
ms:contentKeyID: 49850742
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.TuesdayEndingTime
dev_langs:
- CSharp
- C++
- VB
---

# TuesdayEndingTime Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the ending time for Tuesdays in this period.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("THUESDAYENDINGTIME")> _
<DataMemberAttribute> _
Public Property TuesdayEndingTime As Integer
    Get
    Friend Set
'Usage
Dim instance As ValidationPeriod
Dim value As Integer

value = instance.TuesdayEndingTime
```

``` csharp
[ColumnAttribute("THUESDAYENDINGTIME")]
[DataMemberAttribute]
public int TuesdayEndingTime { get; internal set; }
```

``` c++
[ColumnAttribute(L"THUESDAYENDINGTIME")]
[DataMemberAttribute]
public:
property int TuesdayEndingTime {
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

