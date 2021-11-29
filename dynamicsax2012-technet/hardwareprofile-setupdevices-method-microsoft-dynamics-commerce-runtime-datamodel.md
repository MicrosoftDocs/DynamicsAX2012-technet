---
title: HardwareProfile.SetupDevices Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SetupDevices Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.SetupDevices(System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfilePrinter},System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfileScanner},System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfileCashDrawer})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.hardwareprofile.setupdevices(v=AX.60)
ms:contentKeyID: 65317390
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile.SetupDevices
dev_langs:
- CSharp
- C++
- VB
---

# SetupDevices Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub SetupDevices ( _
    printers As ReadOnlyCollection(Of HardwareProfilePrinter), _
    scanners As ReadOnlyCollection(Of HardwareProfileScanner), _
    cashDrawers As ReadOnlyCollection(Of HardwareProfileCashDrawer) _
)
'Usage
Dim instance As HardwareProfile
Dim printers As ReadOnlyCollection(Of HardwareProfilePrinter)
Dim scanners As ReadOnlyCollection(Of HardwareProfileScanner)
Dim cashDrawers As ReadOnlyCollection(Of HardwareProfileCashDrawer)

instance.SetupDevices(printers, scanners, _
    cashDrawers)
```

``` csharp
public void SetupDevices(
    ReadOnlyCollection<HardwareProfilePrinter> printers,
    ReadOnlyCollection<HardwareProfileScanner> scanners,
    ReadOnlyCollection<HardwareProfileCashDrawer> cashDrawers
)
```

``` c++
public:
void SetupDevices(
    ReadOnlyCollection<HardwareProfilePrinter^>^ printers, 
    ReadOnlyCollection<HardwareProfileScanner^>^ scanners, 
    ReadOnlyCollection<HardwareProfileCashDrawer^>^ cashDrawers
)
```

#### Parameters

  - printers  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[HardwareProfilePrinter](hardwareprofileprinter-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - scanners  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[HardwareProfileScanner](hardwareprofilescanner-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - cashDrawers  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[HardwareProfileCashDrawer](hardwareprofilecashdrawer-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[HardwareProfile Class](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

