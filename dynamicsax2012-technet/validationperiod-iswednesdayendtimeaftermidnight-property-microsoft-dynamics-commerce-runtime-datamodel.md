---
title: ValidationPeriod.IsWednesdayEndTimeAfterMidnight Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsWednesdayEndTimeAfterMidnight Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.IsWednesdayEndTimeAfterMidnight
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.validationperiod.iswednesdayendtimeaftermidnight(v=AX.60)
ms:contentKeyID: 49855237
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.IsWednesdayEndTimeAfterMidnight
dev_langs:
- CSharp
- C++
- VB
---

# IsWednesdayEndTimeAfterMidnight Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets whether ending time wraps around after midnight for Wednesdays in this period.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("WEDNESDAYENDINGTIMEAFTERMIDNIGHT")> _
<DataMemberAttribute> _
Public Property IsWednesdayEndTimeAfterMidnight As Integer
    Get
    Friend Set
'Usage
Dim instance As ValidationPeriod
Dim value As Integer

value = instance.IsWednesdayEndTimeAfterMidnight
```

``` csharp
[ColumnAttribute("WEDNESDAYENDINGTIMEAFTERMIDNIGHT")]
[DataMemberAttribute]
public int IsWednesdayEndTimeAfterMidnight { get; internal set; }
```

``` c++
[ColumnAttribute(L"WEDNESDAYENDINGTIMEAFTERMIDNIGHT")]
[DataMemberAttribute]
public:
property int IsWednesdayEndTimeAfterMidnight {
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

