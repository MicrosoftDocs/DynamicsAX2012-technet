---
title: ValidationPeriod.PeriodId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PeriodId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.PeriodId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.validationperiod.periodid(v=AX.60)
ms:contentKeyID: 49846356
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.PeriodId
dev_langs:
- CSharp
- C++
- VB
---

# PeriodId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the alternate identifier for this validation period.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("PERIODID")> _
Public Property PeriodId As String
    Get
    Friend Set
'Usage
Dim instance As ValidationPeriod
Dim value As String

value = instance.PeriodId
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("PERIODID")]
public string PeriodId { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"PERIODID")]
public:
property String^ PeriodId {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ValidationPeriod Class](validationperiod-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

