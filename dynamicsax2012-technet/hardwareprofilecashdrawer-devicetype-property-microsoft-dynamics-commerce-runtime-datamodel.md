---
title: HardwareProfileCashDrawer.DeviceType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DeviceType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfileCashDrawer.DeviceType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofilecashdrawer.devicetype(v=AX.60)
ms:contentKeyID: 62213419
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfileCashDrawer.DeviceType
dev_langs:
- CSharp
- C++
- VB
---

# DeviceType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the cash drawer device type value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("DRAWERTYPE")> _
Public Property DeviceType As DeviceType
    Get
    Set
'Usage
Dim instance As HardwareProfileCashDrawer
Dim value As DeviceType

value = instance.DeviceType

instance.DeviceType = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("DRAWERTYPE")]
public DeviceType DeviceType { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"DRAWERTYPE")]
public:
property DeviceType DeviceType {
    DeviceType get ();
    void set (DeviceType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceType](devicetype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
The DeviceType value.  

## See Also

#### Reference

[HardwareProfileCashDrawer Class](hardwareprofilecashdrawer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

