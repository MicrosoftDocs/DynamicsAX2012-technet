---
title: ActivateDeviceServiceResponse.DeviceActivationResult Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: DeviceActivationResult Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ActivateDeviceServiceResponse.DeviceActivationResult
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.activatedeviceserviceresponse.deviceactivationresult(v=AX.60)
ms:contentKeyID: 65321290
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ActivateDeviceServiceResponse.DeviceActivationResult
dev_langs:
- CSharp
- C++
- VB
---

# DeviceActivationResult Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DeviceActivationResult As DeviceActivationResult
    Get
    Private Set
'Usage
Dim instance As ActivateDeviceServiceResponse
Dim value As DeviceActivationResult

value = instance.DeviceActivationResult
```

``` csharp
[DataMemberAttribute]
public DeviceActivationResult DeviceActivationResult { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property DeviceActivationResult^ DeviceActivationResult {
    DeviceActivationResult^ get ();
    private: void set (DeviceActivationResult^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceActivationResult](deviceactivationresult-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ActivateDeviceServiceResponse Class](activatedeviceserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

