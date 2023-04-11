---
title: ValidationPeriod.WednesdayStartingTime Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: WednesdayStartingTime Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.WednesdayStartingTime
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.validationperiod.wednesdaystartingtime(v=AX.60)
ms:contentKeyID: 49831765
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.WednesdayStartingTime
dev_langs:
- CSharp
- C++
- VB
---

# WednesdayStartingTime Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the starting time for Wednesdays in this period.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("WEDNESDAYSTARTINGTIME")> _
<DataMemberAttribute> _
Public Property WednesdayStartingTime As Integer
    Get
    Friend Set
'Usage
Dim instance As ValidationPeriod
Dim value As Integer

value = instance.WednesdayStartingTime
```

``` csharp
[ColumnAttribute("WEDNESDAYSTARTINGTIME")]
[DataMemberAttribute]
public int WednesdayStartingTime { get; internal set; }
```

``` c++
[ColumnAttribute(L"WEDNESDAYSTARTINGTIME")]
[DataMemberAttribute]
public:
property int WednesdayStartingTime {
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

