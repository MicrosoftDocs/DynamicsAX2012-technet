---
title: ValidationPeriod.FridayStartingTime Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: FridayStartingTime Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.FridayStartingTime
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.validationperiod.fridaystartingtime(v=AX.60)
ms:contentKeyID: 49840434
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.FridayStartingTime
dev_langs:
- CSharp
- C++
- VB
---

# FridayStartingTime Property

Gets the starting time for Fridays in this period.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("FRIDAYSTARTINGTIME")> _
<DataMemberAttribute> _
Public Property FridayStartingTime As Integer
    Get
    Friend Set
'Usage
Dim instance As ValidationPeriod
Dim value As Integer

value = instance.FridayStartingTime
```

``` csharp
[ColumnAttribute("FRIDAYSTARTINGTIME")]
[DataMemberAttribute]
public int FridayStartingTime { get; internal set; }
```

``` c++
[ColumnAttribute(L"FRIDAYSTARTINGTIME")]
[DataMemberAttribute]
public:
property int FridayStartingTime {
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

