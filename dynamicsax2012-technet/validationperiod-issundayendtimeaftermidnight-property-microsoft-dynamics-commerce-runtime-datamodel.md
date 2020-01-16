---
title: ValidationPeriod.IsSundayEndTimeAfterMidnight Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsSundayEndTimeAfterMidnight Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.IsSundayEndTimeAfterMidnight
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.validationperiod.issundayendtimeaftermidnight(v=AX.60)
ms:contentKeyID: 49836437
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.IsSundayEndTimeAfterMidnight
dev_langs:
- CSharp
- C++
- VB
---

# IsSundayEndTimeAfterMidnight Property

Gets whether ending time wraps around after midnight for Sundays in this period.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("SUNDAYENDINGTIMEAFTERMIDNIGHT")> _
Public Property IsSundayEndTimeAfterMidnight As Integer
    Get
    Friend Set
'Usage
Dim instance As ValidationPeriod
Dim value As Integer

value = instance.IsSundayEndTimeAfterMidnight
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("SUNDAYENDINGTIMEAFTERMIDNIGHT")]
public int IsSundayEndTimeAfterMidnight { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"SUNDAYENDINGTIMEAFTERMIDNIGHT")]
public:
property int IsSundayEndTimeAfterMidnight {
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

