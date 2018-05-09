---
title: ValidationPeriod.MondayEndingTime Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MondayEndingTime Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.MondayEndingTime
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.validationperiod.mondayendingtime(v=AX.60)
ms:contentKeyID: 49832748
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.MondayEndingTime
dev_langs:
- CSharp
- C++
- VB
---

# MondayEndingTime Property

Gets the ending time for Mondays in this period.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("MONDAYENDINGTIME")> _
Public Property MondayEndingTime As Integer
    Get
    Friend Set
'Usage
Dim instance As ValidationPeriod
Dim value As Integer

value = instance.MondayEndingTime
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("MONDAYENDINGTIME")]
public int MondayEndingTime { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"MONDAYENDINGTIME")]
public:
property int MondayEndingTime {
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

