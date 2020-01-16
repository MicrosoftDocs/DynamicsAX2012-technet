---
title: DeviceDataManager.GetDeviceByDeviceId Method (String, Boolean) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetDeviceByDeviceId Method (String, Boolean)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.DeviceDataManager.GetDeviceByDeviceId(System.String,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.devicedatamanager.getdevicebydeviceid(v=AX.60)
ms:contentKeyID: 65322287
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetDeviceByDeviceId Method (String, Boolean)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetDeviceByDeviceId ( _
    deviceId As String, _
    isActivatedOnly As Boolean _
) As Device
'Usage
Dim instance As DeviceDataManager
Dim deviceId As String
Dim isActivatedOnly As Boolean
Dim returnValue As Device

returnValue = instance.GetDeviceByDeviceId(deviceId, _
    isActivatedOnly)
```

``` csharp
public Device GetDeviceByDeviceId(
    string deviceId,
    bool isActivatedOnly
)
```

``` c++
public:
Device^ GetDeviceByDeviceId(
    String^ deviceId, 
    bool isActivatedOnly
)
```

#### Parameters

  - deviceId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - isActivatedOnly  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Device](device-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[DeviceDataManager Class](devicedatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[GetDeviceByDeviceId Overload](devicedatamanager-getdevicebydeviceid-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

