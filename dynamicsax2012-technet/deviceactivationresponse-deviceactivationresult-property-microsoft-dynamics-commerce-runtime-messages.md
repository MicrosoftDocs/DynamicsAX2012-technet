---
title: DeviceActivationResponse.DeviceActivationResult Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: DeviceActivationResult Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.DeviceActivationResponse.DeviceActivationResult
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.deviceactivationresponse.deviceactivationresult(v=AX.60)
ms:contentKeyID: 65322384
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.DeviceActivationResponse.DeviceActivationResult
dev_langs:
- CSharp
- C++
- VB
---

# DeviceActivationResult Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DeviceActivationResult As DeviceActivationResult
    Get
    Private Set
'Usage
Dim instance As DeviceActivationResponse
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

[DeviceActivationResponse Class](deviceactivationresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

