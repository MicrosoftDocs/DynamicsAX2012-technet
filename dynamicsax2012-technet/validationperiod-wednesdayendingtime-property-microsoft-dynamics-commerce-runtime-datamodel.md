---
title: ValidationPeriod.WednesdayEndingTime Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: WednesdayEndingTime Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.WednesdayEndingTime
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.validationperiod.wednesdayendingtime(v=AX.60)
ms:contentKeyID: 49838537
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.WednesdayEndingTime
dev_langs:
- CSharp
- C++
- VB
---

# WednesdayEndingTime Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the ending time for Wednesdays in this period.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("WEDNESDAYENDINGTIME")> _
Public Property WednesdayEndingTime As Integer
    Get
    Friend Set
'Usage
Dim instance As ValidationPeriod
Dim value As Integer

value = instance.WednesdayEndingTime
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("WEDNESDAYENDINGTIME")]
public int WednesdayEndingTime { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"WEDNESDAYENDINGTIME")]
public:
property int WednesdayEndingTime {
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

