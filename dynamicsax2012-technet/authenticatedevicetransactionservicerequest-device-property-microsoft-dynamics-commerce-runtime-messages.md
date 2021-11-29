---
title: AuthenticateDeviceTransactionServiceRequest.Device Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Device Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.AuthenticateDeviceTransactionServiceRequest.Device
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.authenticatedevicetransactionservicerequest.device(v=AX.60)
ms:contentKeyID: 65322733
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.AuthenticateDeviceTransactionServiceRequest.Device
dev_langs:
- CSharp
- C++
- VB
---

# Device Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Device As Device
    Get
    Private Set
'Usage
Dim instance As AuthenticateDeviceTransactionServiceRequest
Dim value As Device

value = instance.Device
```

``` csharp
[DataMemberAttribute]
public Device Device { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Device^ Device {
    Device^ get ();
    private: void set (Device^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Device](device-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[AuthenticateDeviceTransactionServiceRequest Class](authenticatedevicetransactionservicerequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

