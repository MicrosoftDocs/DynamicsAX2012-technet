---
title: ValidationPeriod.IsThursdayTimeBounded Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsThursdayTimeBounded Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.IsThursdayTimeBounded
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.validationperiod.isthursdaytimebounded(v=AX.60)
ms:contentKeyID: 49837517
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.IsThursdayTimeBounded
dev_langs:
- CSharp
- C++
- VB
---

# IsThursdayTimeBounded Property

Gets whether valid time is inside or outside specified bounds for Thursdays in this period.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("THURSDAYTIMEWITHINBOUNDS")> _
Public Property IsThursdayTimeBounded As Integer
    Get
    Friend Set
'Usage
Dim instance As ValidationPeriod
Dim value As Integer

value = instance.IsThursdayTimeBounded
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("THURSDAYTIMEWITHINBOUNDS")]
public int IsThursdayTimeBounded { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"THURSDAYTIMEWITHINBOUNDS")]
public:
property int IsThursdayTimeBounded {
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

