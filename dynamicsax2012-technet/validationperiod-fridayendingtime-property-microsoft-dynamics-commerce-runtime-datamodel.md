---
title: ValidationPeriod.FridayEndingTime Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: FridayEndingTime Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.FridayEndingTime
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.validationperiod.fridayendingtime(v=AX.60)
ms:contentKeyID: 49820834
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.FridayEndingTime
dev_langs:
- CSharp
- C++
- VB
---

# FridayEndingTime Property

Gets the ending time for Fridays in this period.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("FRIDAYENDINGTIME")> _
<DataMemberAttribute> _
Public Property FridayEndingTime As Integer
    Get
    Friend Set
'Usage
Dim instance As ValidationPeriod
Dim value As Integer

value = instance.FridayEndingTime
```

``` csharp
[ColumnAttribute("FRIDAYENDINGTIME")]
[DataMemberAttribute]
public int FridayEndingTime { get; internal set; }
```

``` c++
[ColumnAttribute(L"FRIDAYENDINGTIME")]
[DataMemberAttribute]
public:
property int FridayEndingTime {
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

