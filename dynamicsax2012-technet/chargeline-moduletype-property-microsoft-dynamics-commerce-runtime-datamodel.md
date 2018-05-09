---
title: ChargeLine.ModuleType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ModuleType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeLine.ModuleType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.chargeline.moduletype(v=AX.60)
ms:contentKeyID: 49827774
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeLine.ModuleType
dev_langs:
- CSharp
- C++
- VB
---

# ModuleType Property

Gets or sets which module the charge comes from.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("MODULETYPE")> _
<IgnoreDataMemberAttribute> _
Public Property ModuleType As ChargeModule
    Get
    Set
'Usage
Dim instance As ChargeLine
Dim value As ChargeModule

value = instance.ModuleType

instance.ModuleType = value
```

``` csharp
[ColumnAttribute("MODULETYPE")]
[IgnoreDataMemberAttribute]
public ChargeModule ModuleType { get; set; }
```

``` c++
[ColumnAttribute(L"MODULETYPE")]
[IgnoreDataMemberAttribute]
public:
property ChargeModule ModuleType {
    ChargeModule get ();
    void set (ChargeModule value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeModule](chargemodule-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
The type of the charge module.  

## Remarks

Indicates whether this is a customer or delivery charge.

## See Also

#### Reference

[ChargeLine Class](chargeline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

