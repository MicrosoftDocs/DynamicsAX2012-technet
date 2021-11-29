---
title: ValidationPeriod.SundayEndingTime Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SundayEndingTime Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.SundayEndingTime
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.validationperiod.sundayendingtime(v=AX.60)
ms:contentKeyID: 49839136
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.SundayEndingTime
dev_langs:
- CSharp
- C++
- VB
---

# SundayEndingTime Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the ending time for Sundays in this period.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("SUNDAYENDINGTIME")> _
<DataMemberAttribute> _
Public Property SundayEndingTime As Integer
    Get
    Friend Set
'Usage
Dim instance As ValidationPeriod
Dim value As Integer

value = instance.SundayEndingTime
```

``` csharp
[ColumnAttribute("SUNDAYENDINGTIME")]
[DataMemberAttribute]
public int SundayEndingTime { get; internal set; }
```

``` c++
[ColumnAttribute(L"SUNDAYENDINGTIME")]
[DataMemberAttribute]
public:
property int SundayEndingTime {
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

