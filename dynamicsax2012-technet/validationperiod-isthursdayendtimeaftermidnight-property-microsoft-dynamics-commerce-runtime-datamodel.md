---
title: ValidationPeriod.IsThursdayEndTimeAfterMidnight Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsThursdayEndTimeAfterMidnight Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.IsThursdayEndTimeAfterMidnight
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.validationperiod.isthursdayendtimeaftermidnight(v=AX.60)
ms:contentKeyID: 49842481
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.IsThursdayEndTimeAfterMidnight
dev_langs:
- CSharp
- C++
- VB
---

# IsThursdayEndTimeAfterMidnight Property

Gets whether ending time wraps around after midnight for Thursdays in this period.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("THURSDAYENDINGTIMEAFTERMIDNIGHT")> _
<DataMemberAttribute> _
Public Property IsThursdayEndTimeAfterMidnight As Integer
    Get
    Friend Set
'Usage
Dim instance As ValidationPeriod
Dim value As Integer

value = instance.IsThursdayEndTimeAfterMidnight
```

``` csharp
[ColumnAttribute("THURSDAYENDINGTIMEAFTERMIDNIGHT")]
[DataMemberAttribute]
public int IsThursdayEndTimeAfterMidnight { get; internal set; }
```

``` c++
[ColumnAttribute(L"THURSDAYENDINGTIMEAFTERMIDNIGHT")]
[DataMemberAttribute]
public:
property int IsThursdayEndTimeAfterMidnight {
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

