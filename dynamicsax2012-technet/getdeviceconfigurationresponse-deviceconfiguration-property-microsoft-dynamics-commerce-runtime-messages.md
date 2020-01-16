---
title: GetDeviceConfigurationResponse.DeviceConfiguration Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: DeviceConfiguration Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetDeviceConfigurationResponse.DeviceConfiguration
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getdeviceconfigurationresponse.deviceconfiguration(v=AX.60)
ms:contentKeyID: 62211345
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetDeviceConfigurationResponse.DeviceConfiguration
dev_langs:
- CSharp
- C++
- VB
---

# DeviceConfiguration Property

Gets the device configuration.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DeviceConfiguration As DeviceConfiguration
    Get
    Private Set
'Usage
Dim instance As GetDeviceConfigurationResponse
Dim value As DeviceConfiguration

value = instance.DeviceConfiguration
```

``` csharp
[DataMemberAttribute]
public DeviceConfiguration DeviceConfiguration { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property DeviceConfiguration^ DeviceConfiguration {
    DeviceConfiguration^ get ();
    private: void set (DeviceConfiguration^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [DeviceConfiguration](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetDeviceConfigurationResponse Class](getdeviceconfigurationresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

