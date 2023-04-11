---
title: HardwareProfileCashDrawer.DevicePool Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DevicePool Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfileCashDrawer.DevicePool
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofilecashdrawer.devicepool(v=AX.60)
ms:contentKeyID: 65322296
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfileCashDrawer.DevicePool
dev_langs:
- CSharp
- C++
- VB
---

# DevicePool Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DevicePool As ReadOnlyCollection(Of HardwareProfileCashDrawerPoolDevice)
    Get
    Private Set
'Usage
Dim instance As HardwareProfileCashDrawer
Dim value As ReadOnlyCollection(Of HardwareProfileCashDrawerPoolDevice)

value = instance.DevicePool
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<HardwareProfileCashDrawerPoolDevice> DevicePool { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<HardwareProfileCashDrawerPoolDevice^>^ DevicePool {
    ReadOnlyCollection<HardwareProfileCashDrawerPoolDevice^>^ get ();
    private: void set (ReadOnlyCollection<HardwareProfileCashDrawerPoolDevice^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[HardwareProfileCashDrawerPoolDevice](hardwareprofilecashdrawerpooldevice-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[HardwareProfileCashDrawer Class](hardwareprofilecashdrawer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

