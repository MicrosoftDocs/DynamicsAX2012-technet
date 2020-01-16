---
title: ValidationPeriod.ThursdayEndingTime Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ThursdayEndingTime Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.ThursdayEndingTime
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.validationperiod.thursdayendingtime(v=AX.60)
ms:contentKeyID: 49826237
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.ThursdayEndingTime
dev_langs:
- CSharp
- C++
- VB
---

# ThursdayEndingTime Property

Gets the ending time for Thursdays in this period.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("THURSDAYENDINGTIME")> _
Public Property ThursdayEndingTime As Integer
    Get
    Friend Set
'Usage
Dim instance As ValidationPeriod
Dim value As Integer

value = instance.ThursdayEndingTime
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("THURSDAYENDINGTIME")]
public int ThursdayEndingTime { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"THURSDAYENDINGTIME")]
public:
property int ThursdayEndingTime {
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

