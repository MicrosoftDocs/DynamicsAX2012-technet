---
title: TaxOverride.OverrideBy Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OverrideBy Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxOverride.OverrideBy
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.taxoverride.overrideby(v=AX.60)
ms:contentKeyID: 62209560
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxOverride.OverrideBy
dev_langs:
- CSharp
- C++
- VB
---

# OverrideBy Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the type of the tax override by.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("OVERRIDEBY")> _
Public Property OverrideBy As TaxOverrideBy
    Get
    Set
'Usage
Dim instance As TaxOverride
Dim value As TaxOverrideBy

value = instance.OverrideBy

instance.OverrideBy = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("OVERRIDEBY")]
public TaxOverrideBy OverrideBy { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"OVERRIDEBY")]
public:
property TaxOverrideBy OverrideBy {
    TaxOverrideBy get ();
    void set (TaxOverrideBy value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxOverrideBy](taxoverrideby-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [TaxOverrideBy](taxoverrideby-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[TaxOverride Class](taxoverride-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

