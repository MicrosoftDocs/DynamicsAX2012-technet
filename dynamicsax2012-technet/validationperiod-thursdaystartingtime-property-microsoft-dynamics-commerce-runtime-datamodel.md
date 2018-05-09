---
title: ValidationPeriod.ThursdayStartingTime Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ThursdayStartingTime Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.ThursdayStartingTime
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.validationperiod.thursdaystartingtime(v=AX.60)
ms:contentKeyID: 49839565
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.ThursdayStartingTime
dev_langs:
- CSharp
- C++
- VB
---

# ThursdayStartingTime Property

Gets the starting time for Thursdays in this period.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("THURSDAYSTARTINGTIME")> _
<DataMemberAttribute> _
Public Property ThursdayStartingTime As Integer
    Get
    Friend Set
'Usage
Dim instance As ValidationPeriod
Dim value As Integer

value = instance.ThursdayStartingTime
```

``` csharp
[ColumnAttribute("THURSDAYSTARTINGTIME")]
[DataMemberAttribute]
public int ThursdayStartingTime { get; internal set; }
```

``` c++
[ColumnAttribute(L"THURSDAYSTARTINGTIME")]
[DataMemberAttribute]
public:
property int ThursdayStartingTime {
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

