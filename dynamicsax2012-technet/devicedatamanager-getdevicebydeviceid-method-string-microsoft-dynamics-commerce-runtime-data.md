---
title: DeviceDataManager.GetDeviceByDeviceId Method (String) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetDeviceByDeviceId Method (String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.DeviceDataManager.GetDeviceByDeviceId(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.devicedatamanager.getdevicebydeviceid(v=AX.60)
ms:contentKeyID: 62204226
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetDeviceByDeviceId Method (String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the device by it's unique device identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetDeviceByDeviceId ( _
    deviceId As String _
) As Device
'Usage
Dim instance As DeviceDataManager
Dim deviceId As String
Dim returnValue As Device

returnValue = instance.GetDeviceByDeviceId(deviceId)
```

``` csharp
public Device GetDeviceByDeviceId(
    string deviceId
)
```

``` c++
public:
Device^ GetDeviceByDeviceId(
    String^ deviceId
)
```

#### Parameters

  - deviceId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Device](device-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The device.  

## See Also

#### Reference

[DeviceDataManager Class](devicedatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[GetDeviceByDeviceId Overload](devicedatamanager-getdevicebydeviceid-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

