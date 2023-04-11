---
title: DeviceConfiguration.TaxOverrideGroup Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxOverrideGroup Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.TaxOverrideGroup
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.taxoverridegroup(v=AX.60)
ms:contentKeyID: 62208535
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.TaxOverrideGroup
dev_langs:
- CSharp
- C++
- VB
---

# TaxOverrideGroup Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the tax override group.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TAXOVERRIDEGROUP")> _
Public Property TaxOverrideGroup As Long
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As Long

value = instance.TaxOverrideGroup

instance.TaxOverrideGroup = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TAXOVERRIDEGROUP")]
public long TaxOverrideGroup { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TAXOVERRIDEGROUP")]
public:
property long long TaxOverrideGroup {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
The tax override group.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

