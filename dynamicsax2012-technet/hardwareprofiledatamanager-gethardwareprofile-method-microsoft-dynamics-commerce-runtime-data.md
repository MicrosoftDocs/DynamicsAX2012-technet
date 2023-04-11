---
title: HardwareProfileDataManager.GetHardwareProfile Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetHardwareProfile Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.HardwareProfileDataManager.GetHardwareProfile(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.hardwareprofiledatamanager.gethardwareprofile(v=AX.60)
ms:contentKeyID: 62215013
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.HardwareProfileDataManager.GetHardwareProfile
dev_langs:
- CSharp
- C++
- VB
---

# GetHardwareProfile Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the hardware profile with the given profile identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetHardwareProfile ( _
    profileId As String _
) As HardwareProfile
'Usage
Dim instance As HardwareProfileDataManager
Dim profileId As String
Dim returnValue As HardwareProfile

returnValue = instance.GetHardwareProfile(profileId)
```

``` csharp
public HardwareProfile GetHardwareProfile(
    string profileId
)
```

``` c++
public:
HardwareProfile^ GetHardwareProfile(
    String^ profileId
)
```

#### Parameters

  - profileId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.HardwareProfile](hardwareprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The device configuration.  

## See Also

#### Reference

[HardwareProfileDataManager Class](hardwareprofiledatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

