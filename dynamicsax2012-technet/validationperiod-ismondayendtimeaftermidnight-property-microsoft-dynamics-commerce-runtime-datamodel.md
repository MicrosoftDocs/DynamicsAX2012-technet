---
title: ValidationPeriod.IsMondayEndTimeAfterMidnight Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsMondayEndTimeAfterMidnight Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.IsMondayEndTimeAfterMidnight
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.validationperiod.ismondayendtimeaftermidnight(v=AX.60)
ms:contentKeyID: 49841392
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.IsMondayEndTimeAfterMidnight
dev_langs:
- CSharp
- C++
- VB
---

# IsMondayEndTimeAfterMidnight Property

Gets whether ending time wraps around after midnight for Mondays in this period.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("MONDAYENDINGTIMEAFTERMIDNIGHT")> _
<DataMemberAttribute> _
Public Property IsMondayEndTimeAfterMidnight As Integer
    Get
    Friend Set
'Usage
Dim instance As ValidationPeriod
Dim value As Integer

value = instance.IsMondayEndTimeAfterMidnight
```

``` csharp
[ColumnAttribute("MONDAYENDINGTIMEAFTERMIDNIGHT")]
[DataMemberAttribute]
public int IsMondayEndTimeAfterMidnight { get; internal set; }
```

``` c++
[ColumnAttribute(L"MONDAYENDINGTIMEAFTERMIDNIGHT")]
[DataMemberAttribute]
public:
property int IsMondayEndTimeAfterMidnight {
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

