---
title: ValidationPeriod.IsSaturdayEndTimeAfterMidnight Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsSaturdayEndTimeAfterMidnight Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.IsSaturdayEndTimeAfterMidnight
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.validationperiod.issaturdayendtimeaftermidnight(v=AX.60)
ms:contentKeyID: 49842500
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.IsSaturdayEndTimeAfterMidnight
dev_langs:
- CSharp
- C++
- VB
---

# IsSaturdayEndTimeAfterMidnight Property

Gets whether ending time wraps around after midnight for Saturdays in this period.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("SATURDAYENDINGTIMEAFTERMIDNIGHT")> _
Public Property IsSaturdayEndTimeAfterMidnight As Integer
    Get
    Friend Set
'Usage
Dim instance As ValidationPeriod
Dim value As Integer

value = instance.IsSaturdayEndTimeAfterMidnight
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("SATURDAYENDINGTIMEAFTERMIDNIGHT")]
public int IsSaturdayEndTimeAfterMidnight { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"SATURDAYENDINGTIMEAFTERMIDNIGHT")]
public:
property int IsSaturdayEndTimeAfterMidnight {
    int get ();
    internal: void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[ValidationPeriod Class](validationperiod-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

