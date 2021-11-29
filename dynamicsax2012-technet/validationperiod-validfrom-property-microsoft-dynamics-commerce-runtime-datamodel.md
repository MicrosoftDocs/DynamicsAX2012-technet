---
title: ValidationPeriod.ValidFrom Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ValidFrom Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.ValidFrom
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.validationperiod.validfrom(v=AX.60)
ms:contentKeyID: 49851703
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ValidationPeriod.ValidFrom
dev_langs:
- CSharp
- C++
- VB
---

# ValidFrom Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the starting date for this period.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("VALIDFROM")> _
<DataMemberAttribute> _
Public Property ValidFrom As DateTimeOffset
    Get
    Friend Set
'Usage
Dim instance As ValidationPeriod
Dim value As DateTimeOffset

value = instance.ValidFrom
```

``` csharp
[ColumnAttribute("VALIDFROM")]
[DataMemberAttribute]
public DateTimeOffset ValidFrom { get; internal set; }
```

``` c++
[ColumnAttribute(L"VALIDFROM")]
[DataMemberAttribute]
public:
property DateTimeOffset ValidFrom {
    DateTimeOffset get ();
    internal: void set (DateTimeOffset value);
}
```

#### Property Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  
Returns [DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\)).  

## See Also

#### Reference

[ValidationPeriod Class](validationperiod-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

