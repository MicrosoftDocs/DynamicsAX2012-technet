---
title: HardwareProfile.DualDisplayDisplayType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DualDisplayDisplayType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.DualDisplayDisplayType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.dualdisplaydisplaytype(v=AX.60)
ms:contentKeyID: 62207102
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.DualDisplayDisplayType
dev_langs:
- CSharp
- C++
- VB
---

# DualDisplayDisplayType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the dual display type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DUALDISPLAYTYPE")> _
<DataMemberAttribute> _
Public Property DualDisplayDisplayType As DualDisplayType
    Get
    Set
'Usage
Dim instance As HardwareProfile
Dim value As DualDisplayType

value = instance.DualDisplayDisplayType

instance.DualDisplayDisplayType = value
```

``` csharp
[ColumnAttribute("DUALDISPLAYTYPE")]
[DataMemberAttribute]
public DualDisplayType DualDisplayDisplayType { get; set; }
```

``` c++
[ColumnAttribute(L"DUALDISPLAYTYPE")]
[DataMemberAttribute]
public:
property DualDisplayType DualDisplayDisplayType {
    DualDisplayType get ();
    void set (DualDisplayType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.DualDisplayType](dualdisplaytype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
The DualDisplayType value.  

## See Also

#### Reference

[HardwareProfile Class](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

