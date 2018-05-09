---
title: DeviceConfigurationDataManager.GetDeviceConfiguration Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetDeviceConfiguration Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.DeviceConfigurationDataManager.GetDeviceConfiguration(System.String,System.Nullable{System.Int64},System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.deviceconfigurationdatamanager.getdeviceconfiguration(v=AX.60)
ms:contentKeyID: 65323145
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DeviceConfigurationDataManager.GetDeviceConfiguration
dev_langs:
- CSharp
- C++
- VB
---

# GetDeviceConfiguration Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetDeviceConfiguration ( _
    storeNumber As String, _
    channelId As Nullable(Of Long), _
    terminalId As String, _
    querySettings As QueryResultSettings _
) As DeviceConfiguration
'Usage
Dim instance As DeviceConfigurationDataManager
Dim storeNumber As String
Dim channelId As Nullable(Of Long)
Dim terminalId As String
Dim querySettings As QueryResultSettings
Dim returnValue As DeviceConfiguration

returnValue = instance.GetDeviceConfiguration(storeNumber, _
    channelId, terminalId, querySettings)
```

``` csharp
public DeviceConfiguration GetDeviceConfiguration(
    string storeNumber,
    Nullable<long> channelId,
    string terminalId,
    QueryResultSettings querySettings
)
```

``` c++
public:
DeviceConfiguration^ GetDeviceConfiguration(
    String^ storeNumber, 
    Nullable<long long> channelId, 
    String^ terminalId, 
    QueryResultSettings^ querySettings
)
```

#### Parameters

  - storeNumber  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - channelId  
    Type: [System.Nullable](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))\>  

<!-- end list -->

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - querySettings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[DeviceConfigurationDataManager Class](deviceconfigurationdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

