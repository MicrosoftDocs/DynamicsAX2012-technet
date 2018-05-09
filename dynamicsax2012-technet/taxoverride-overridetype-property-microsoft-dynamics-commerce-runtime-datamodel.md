---
title: TaxOverride.OverrideType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OverrideType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxOverride.OverrideType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.taxoverride.overridetype(v=AX.60)
ms:contentKeyID: 62207445
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxOverride.OverrideType
dev_langs:
- CSharp
- C++
- VB
---

# OverrideType Property

Gets or sets the type of the tax override.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("OVERRIDETYPE")> _
Public Property OverrideType As TaxOverrideType
    Get
    Set
'Usage
Dim instance As TaxOverride
Dim value As TaxOverrideType

value = instance.OverrideType

instance.OverrideType = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("OVERRIDETYPE")]
public TaxOverrideType OverrideType { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"OVERRIDETYPE")]
public:
property TaxOverrideType OverrideType {
    TaxOverrideType get ();
    void set (TaxOverrideType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxOverrideType](taxoverridetype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [TaxOverrideType](taxoverridetype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[TaxOverride Class](taxoverride-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

