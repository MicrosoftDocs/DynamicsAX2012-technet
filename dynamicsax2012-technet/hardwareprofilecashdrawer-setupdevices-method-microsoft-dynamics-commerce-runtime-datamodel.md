---
title: HardwareProfileCashDrawer.SetupDevices Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SetupDevices Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfileCashDrawer.SetupDevices(System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfileCashDrawerPoolDevice})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofilecashdrawer.setupdevices(v=AX.60)
ms:contentKeyID: 65318872
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfileCashDrawer.SetupDevices
dev_langs:
- CSharp
- C++
- VB
---

# SetupDevices Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub SetupDevices ( _
    devicePool As ReadOnlyCollection(Of HardwareProfileCashDrawerPoolDevice) _
)
'Usage
Dim instance As HardwareProfileCashDrawer
Dim devicePool As ReadOnlyCollection(Of HardwareProfileCashDrawerPoolDevice)

instance.SetupDevices(devicePool)
```

``` csharp
public void SetupDevices(
    ReadOnlyCollection<HardwareProfileCashDrawerPoolDevice> devicePool
)
```

``` c++
public:
void SetupDevices(
    ReadOnlyCollection<HardwareProfileCashDrawerPoolDevice^>^ devicePool
)
```

#### Parameters

  - devicePool  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[HardwareProfileCashDrawerPoolDevice](hardwareprofilecashdrawerpooldevice-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[HardwareProfileCashDrawer Class](hardwareprofilecashdrawer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

